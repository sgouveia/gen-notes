# GenNotes

An Obsidian vault for AI training materials, exercises, essays, and course design. Organized using LYT (Linking Your Thinking) with Maps of Content (MOCs).

**Core idea:** Exercises are atomic (one file = one exercise), courses are assembled by linking them together.

## Folder Structure

```
Exercises/           77 files — Atomic, reusable exercises organized by domain
  Legal AI/            Petitions, contracts, prompt engineering for law
  Workspace AI/        Google Workspace + Gemini exercises
  Teachers AI/         AI for educators — examples, templates, prompting
  Journalism AI/       14h journalism course (5 modules)
  B-Corp AI/           Sustainability and communication cases
  Comms AI/            Prompt engineering for marketing/PR
  Bootcamp/            14-week programming bootcamp (curriculum + evaluation)

The Notes/           14 files — Essays and original thinking
  Fleeting notes/      Rough captures, ideas in progress
  Thinking/            Polished essays on AI, education, philosophy

Reference/           23 files — Course proposals, client materials, support docs
  Content Writers Claude/   Claude-specific prompting guides
  Materiais de Apoio/       Course module support materials

Education/            3 files — Educational design (CPFO course)
Courses/              3 files — Course outlines (HTML, STAG AI, ML Python)
JavaScript/          44 files — JavaScript notes and exercises
Java/                 1 file  — Java notes
Slides/               1 file  — Presentation materials
Personal/             6 files — Journals and personal notes
Archive/             17 files — Superseded content, old drafts
Resources/                    — Images and assets
```

## Navigation

Start at `Exercises/MOC - Exercise Bank.md` — it links to every domain. Each domain has its own MOC. See `MOC_GUIDE.md` for the full MOC hierarchy and conventions.

## Where to put things

| Content type | Folder |
|---|---|
| New exercise | `Exercises/<domain>/` and link from the domain MOC |
| Essay or idea | `The Notes/Fleeting notes/` (rough) or `The Notes/Thinking/` (developed) |
| Course proposal or client doc | `Reference/` |
| Course outline or project | `Courses/` |
| Personal notes | `Personal/` |
| Old/superseded content | `Archive/` |

## Conventions

- **File names:** Descriptive, title case. `Exercicio 1 - Prompt Basico.md`, not `ex1.md`.
- **Folder names:** Title case. Domain folders include "AI" suffix.
- **MOC files:** Named `MOC - <Topic>.md`. Always link new notes from the relevant MOC.
- **Links:** Use `[[double brackets]]`. Link up to MOCs, down to exercises, across to related notes.
- **One idea per file.** If a note covers multiple concepts, split it.
