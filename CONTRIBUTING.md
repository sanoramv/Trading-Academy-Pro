# CONTRIBUTING.md

Trading-Academy-Pro is built like a software project. Whether you're a human
contributor or an AI assistant generating lessons, follow this process.

> **Status:** As of 2026-08-05, the core curriculum and all support
> modules (01-40) are complete — see `ROADMAP.md`. The repository is now
> in **maintenance mode**. The checklist below is mandatory for any new
> file from this point forward, not just during initial buildout.

## Maintainer Checklist (required before creating any new file)

1. **Check for duplicate topics** — search `docs/` (and `docs/33_Glossary/`
   for terminology) to confirm this content doesn't already exist
   elsewhere under a different name.
2. **Ensure links remain valid** — every `[XX.YY]` cross-reference and
   relative Markdown link must resolve to a file that actually exists.
   Run the link/citation audit (see "Validation" below) after any batch of changes.
3. **Update `README.md`** — progress table and file counts.
4. **Update `CURRICULUM.md`** — the syllabus map source of truth.
5. **Update `ROADMAP.md`** — if the change affects a milestone's status.
6. **Update `CHANGELOG.md`** — a dated, most-recent-first entry.
7. **Update the progress percentage** — in `TODO.md`'s snapshot and `README.md`'s table.
8. **Add backlinks to related lessons** — if lesson A newly references
   lesson B, consider whether B's "Further Reading" or body should
   reference A back; cross-references should be bidirectional where it
   aids navigation, not one-directional by default.
9. **Ensure consistent terminology** — check `docs/33_Glossary/` before
   introducing new phrasing for a concept that's already named elsewhere.
10. **Keep every Markdown file under ~2,000 lines** — split into multiple
    files (e.g., an additional glossary range, a second cheat sheet) if a
    file would exceed this for readability.

Treat this repository as a multi-year educational project — quality is
never sacrificed for speed, including during any future large-batch
additions (new modules, revisions, translations, etc.).

## Validation

Before committing a batch of new/changed files, run a link and citation
audit:
```bash
# Broken _Index.md links:
for idx in docs/*/_Index.md; do
  dir=$(dirname "$idx")
  grep -oE '\]\([A-Za-z0-9_.-]+\.md\)' "$idx" | sed 's/^](//; s/)$//' | \
    while read -r t; do [ -f "$dir/$t" ] || echo "BROKEN: $idx -> $t"; done
done

# Broken [XX.YY] citations and duplicate lesson numbers:
# see the Python audit pattern used in the 2026-08-05 CHANGELOG entry.
```

## Before Writing a Lesson

1. Read `MASTER_SKILL.md` in full — it is the constitution for all content.
2. Check `CURRICULUM.md` to confirm the lesson's place in the syllabus and its
   correct module/lesson number.
3. Check `TODO.md` to confirm the lesson hasn't already been generated.
4. Check prerequisite lessons actually exist and are linked correctly.

## Writing a Lesson

1. Copy `templates/LESSON_TEMPLATE.md` as your starting point.
2. Follow the section order exactly as defined in `MASTER_SKILL.md` §3.
3. File name format: `<module>.<lesson>_<Title_In_Snake_Case>.md`, e.g.
   `docs/01_Foundation/01.01_What_Is_a_Financial_Market.md`.
4. Include the lesson ID (e.g. `[01.01]`) in the title heading.
5. Every lesson must include:
   - At least one ASCII diagram or flowchart.
   - At least one Indian market example and one US market example.
   - At least one historical, dated, real example where applicable.
   - A quiz (minimum 5 questions) with an answer key.
   - Homework (minimum 2 tasks).
   - A "Next Lesson" link.
6. Cross-link prerequisites and related lessons using relative Markdown links.
7. Add new terms to the appropriate `docs/33_Glossary/` file.
8. Never include real-time price predictions or buy/sell recommendations.

## After Writing a Lesson

1. Update `TODO.md` — check off the completed item, update the progress
   snapshot table.
2. Update `README.md`'s progress table (lessons-done count for that module).
3. Update `CHANGELOG.md` with a one-line entry.
4. If the lesson introduces a new cross-cutting concept, consider whether a
   flashcard (`docs/34_Flashcards/`) or cheat sheet (`docs/35_CheatSheets/`)
   entry should be updated too — note it in `TODO.md` if deferred.

## Style Guide

- Plain, precise English. No hype, no absolutes ("guaranteed," "always wins").
- Define every technical term on first use in a lesson, even if defined
  elsewhere — link to the glossary, don't assume the reader clicked through.
- Tables and ASCII diagrams over prose wherever a visual would clarify faster.
- Numbers in real-market examples must be sourced/verifiable and dated.
  Hypothetical numbers must be explicitly labeled "Hypothetical Example."
- Indian numbering (lakh/crore) should be introduced and used naturally in
  Indian market examples alongside international (thousand/million) — teach
  the conversion the first time it appears (see `docs/33_Glossary/`).

## Pacing

Per `MASTER_SKILL.md` rule 14, content is generated **one file at a time**.
Do not batch-generate multiple lessons in a single pass — this preserves
quality and lets `TODO.md`/`README.md` stay accurate after every step.
