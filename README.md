# GenNotes Vault - Organization Guide

## Overview

This vault uses **LYT (Linking Your Thinking)** methodology with **MOCs (Maps of Content)** to organize knowledge in a bottom-up, emergent structure.

**Principle:** *Exercises are atomic, courses are emergent.*

---

## Methodology: LYT + MOCs

### What is LYT?

**Linking Your Thinking** is a methodology by Nick Milo that emphasizes:
- **Bottom-up organization:** Let patterns emerge naturally
- **Bi-directional linking:** Notes connect to each other
- **Maps of Content (MOCs):** Hub notes that link related concepts
- **Atomic notes:** One idea per file

### What are MOCs?

**Maps of Content** are "hubs" that:
- Link to related notes
- Provide navigation
- Can belong to multiple contexts
- Grow organically as you add content

**Example:** `Exercises/MOC - Exercise Bank.md` links to all exercise domains.

---

## Folder Structure

```
├── Exercises/              # Atomic, reusable exercises
│   ├── MOC - Exercise Bank.md    (Master index)
│   ├── Legal AI/
│   ├── Workspace AI/
│   ├── Teachers AI/
│   ├── Journalism AI/
│   ├── B-Corp AI/
│   ├── Comms AI/
│   └── Bootcamp/
│       ├── Curriculum/
│       └── Evaluation/
│
├── The Notes/              # Essays and thinking
│   └── Thinking/
│       ├── MOC - Cause and Effect.md
│       ├── AI Limitations/
│       ├── Education/
│       └── Philosophy/
│
├── AI/                     # Course materials (migrated to Exercises)
├── bootcamp/               # Legacy content
├── education/              # Legacy content
└── [Root files]           # Various notes
```

---

## Atomic Notes Principle

### One Idea = One File

Each file should focus on a **single concept**:
- ✅ Good: `Exercício 1 - Prompt Básico.md`
- ❌ Bad: `All AI Exercises.md` (too big)

### File Size
- **Target:** 20-100 lines
- **Maximum:** 200 lines (break if larger)

### Why Atomic?
- Easy to find
- Easy to reuse
- Easy to link
- Easy to maintain

---

## Creating New Notes

### Method 1: No Template (Preferred for Thinking)

Just create a file and start writing. Add links as you go.

**Good for:**
- Fleeting notes
- Ideas
- Essays
- Journal entries

### Method 2: With Template (For Exercises)

Use this structure for consistent exercise formatting:

```markdown
# [Title]

## Objective
What the learner will achieve.

## Context
Background information.

## Instructions
1. Step one
2. Step two
3. Step three

## Expected Output
What success looks like.

---
**Time:** XX minutes
**Level:** [Beginner/Intermediate/Advanced]
**Prerequisites:** [[Related note]]
```

**Good for:**
- Exercises
- Course modules
- Tutorials
- Documentation

---

## Linking Strategy

### Double Bracket Links `[[...]]`

Use these to connect notes:
```markdown
See [[MOC - Exercise Bank]] for all exercises.
Practice with [[Exercício 1 - Prompt Básico]].
```

### Link Types

1. **Up-links:** To parent MOCs
   ```markdown
   Part of [[MOC - Legal AI]]
   ```

2. **Down-links:** To child notes
   ```markdown
   Modules:
   - [[Módulo I]]
   - [[Módulo II]]
   ```

3. **Cross-links:** To related concepts
   ```markdown
   Related: [[AI and Causality]]
   ```

### When to Link
- ✅ Link to MOCs (navigation)
- ✅ Link to prerequisites
- ✅ Link to related concepts
- ✅ Link to source/original
- ❌ Don't link everything (maintain focus)

---

## Naming Conventions

### Files
- Use clear, descriptive names
- Include domain/category when helpful
- Examples:
  - `Exercício 1 - Prompt Básico.md`
  - `Módulo I - Fundamentos.md`
  - `AI and Causality.md`

### Folders
- Domain-focused: `Legal AI/`, `Teachers AI/`
- Function-focused: `Curriculum/`, `Evaluation/`
- Keep flat when possible (avoid deep nesting)

---

## Building Courses

### The "Week Note" Pattern

Combine atomic exercises into courses:

```markdown
# Week 3: AI for Journalism

## Theory (30 min)
- [[Módulo 1 - Introdução à IA]]
- [[Definições de AI]]

## Practice (90 min)
- [[Exercício - Análise de acórdão]]
- [[Exercício - Resumo automático]]

## Connections
- Conceito X applies to [[Other domain]]
- See also: [[MOC - Teachers AI]]
```

### Rules for Course Notes
1. **Don't duplicate content** — link to atomic notes
2. **Add context** — explain why these exercises together
3. **Add timing** — how long each section takes
4. **Add flow** — order matters

---

## Maintenance

### Regular Tasks
- **Weekly:** Check for orphaned notes (no links)
- **Monthly:** Review MOCs, add new links
- **Quarterly:** Archive old content

### When to Create a New MOC
- When you have 5+ related notes
- When navigation becomes difficult
- When starting a new domain

### When to Split a Note
- Exceeds 200 lines
- Covers multiple concepts
- Hard to find specific info

---

## Examples

### Example 1: Creating an Exercise

```markdown
# Exercício: Análise de Sentimento

## Objective
Classificar o sentimento de textos usando AI.

## Context
Útil para monitorização de marca e análise de feedback.

## Instructions
1. Escolha 3 reviews de produto
2. Use o prompt: "Analisa o sentimento deste texto..."
3. Documente os resultados
4. Compare com análise humana

## Expected Output
Tabela com: texto, sentimento AI, sentimento humano, diferenças.

---
**Time:** 30 minutes
**Level:** Beginner
**Prerequisites:** [[Fundamentos de Prompting]]
```

### Example 2: Creating a MOC

```markdown
# MOC: AI para Recursos Humanos

## Sobre Este Domínio
Aplicações de AI em processos de RH.

## Exercícios
- [[Triagem de CVs com AI]]
- [[Análise de entrevistas]]
- [[Onboarding automatizado]]

## Templates
- [[Template - Descrição de vaga]]
- [[Template - Feedback de desempenho]]

## Casos de Estudo
- [[Caso - Empresa X]]
- [[Caso - Empresa Y]]

---
**Created:** 2025
**Tags:** #hr #ai #recruitment
```

---

## Quick Reference

### Creating a New Exercise
1. Choose folder in `Exercises/`
2. Create file with clear name
3. Use template (optional)
4. Link to relevant MOC
5. Add metadata

### Creating a New Course
1. Create "Week Note" in root or course folder
2. Link to existing exercises
3. Add context and flow
4. Add timing estimates
5. Link to main MOC

### Finding Content
1. Start at `Exercises/MOC - Exercise Bank.md`
2. Navigate to domain MOC
3. Find specific exercise
4. Or use Obsidian search

---

## Tips

### Do
- ✅ Keep notes atomic
- ✅ Link liberally to MOCs
- ✅ Add metadata (time, level)
- ✅ Use clear file names
- ✅ Update MOCs when adding content

### Don't
- ❌ Create monolithic files
- ❌ Duplicate content
- ❌ Link everything to everything
- ❌ Forget to link new notes to MOCs
- ❌ Break the atomic principle

---

## FAQ

**Q: Do I have to use templates?**
A: No. Templates help consistency but aren't required. Use them for exercises, skip them for thinking notes.

**Q: What if an exercise fits multiple domains?**
A: Put it in the best fit domain, then link to it from other MOCs.

**Q: How do I know where to put a new note?**
A: Ask: "What's the main topic?" Put it there. Link from other relevant MOCs.

**Q: Can I change the structure?**
A: Yes! This is emergent. Adapt as your needs change.

**Q: What about the root folder?**
A: Root is for temporary notes and quick capture. Move to appropriate folders when organized.

---

## Resources

- **LYT Method:** Nick Milo's Linking Your Thinking
- **MOCs:** Maps of Content concept
- **Zettelkasten:** Atomic note-taking
- **Obsidian:** Tool for linked notes

---

**Last Updated:** February 2025  
**Vault Version:** 2.0  
**Files:** 200+ atomic notes  
**Structure:** LYT + MOCs
