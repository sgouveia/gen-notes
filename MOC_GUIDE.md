# Understanding MOCs (Maps of Content)

## What is a MOC?

A **MOC (Map of Content)** is a "hub note" that serves as a **table of contents** for a collection of related notes.

Think of it as:
- 🗺️ A **map** showing where things are
- 🧭 A **navigation hub** for a topic
- 📚 An **index** that grows organically
- 🔗 A **connection point** between ideas

---

## Core Principle

> **Notes can belong to multiple MOCs**

Unlike folders (which force a note into ONE location), MOCs allow a note to exist in **multiple contexts**.

**Example:**
- An exercise about "AI in legal contracts" can be in:
  - [[MOC - Legal AI]]
  - [[MOC - Exercise Bank]]
  - A specific course Week Note

---

## Types of MOCs in Your Vault

### 1. Master MOCs (Top Level)

These are your **entry points**:

#### [[MOC - Exercise Bank]]
**Purpose:** Gateway to all exercises  
**Links to:** Domain MOCs (Legal AI, Teachers AI, etc.)  
**When to use:** Starting any new project or course

```markdown
# MOC: Exercise Bank

## Domínios
- [[MOC - Legal AI]]
- [[MOC - Workspace AI]]
- [[MOC - Teachers AI]]
...
```

#### [[MOC: AI Workflows by Domain]] (if you create it)
**Purpose:** Cross-domain connections  
**Links to:** Similar exercises across different domains

---

### 2. Domain MOCs (Category Level)

One for each knowledge area:

#### [[MOC - Legal AI]]
**Purpose:** All legal AI content  
**Links to:**
- Exercises (Petição Inicial, Contratos)
- Prompt engineering guides
- Case studies

#### [[MOC - Journalism AI]]
**Purpose:** Journalism course  
**Links to:**
- 5 course modules
- Application guides
- Ethics content

#### [[MOC - Teachers AI]]
**Purpose:** Education resources  
**Links to:**
- Subject examples
- Assessment templates
- Communication guides

---

### 3. Topic MOCs (Specific Level)

Deeper dives into specific topics:

#### [[MOC - Petição Inicial]]
**Purpose:** Legal writing exercises  
**Links to:**
- 4 progressive exercises
- Case study
- Review guide

#### [[MOC - Cause and Effect]]
**Purpose:** Philosophical essays  
**Links to:**
- AI limitations essays
- Education philosophy
- Zarathustra analysis

---

## Anatomy of a Good MOC

### Required Elements

```markdown
# MOC: [Name]

## About
Brief description of what this MOC covers.

## Contents
### Category 1
- [[Note 1]]
- [[Note 2]]
- [[Note 3]]

### Category 2
- [[Note 4]]
- [[Note 5]]

## Related MOCs
- [[Parent MOC]]
- [[Sibling MOC]]
- [[Cross-domain MOC]]

---
**Created:** [Date]
**Updated:** [Date]
**Tags:** #topic #category
```

---

## How to Create a New MOC

### Step 1: Identify the Need

Create a MOC when:
- ✅ You have 5+ related notes
- ✅ Navigation is getting difficult
- ✅ You're starting a new project/domain
- ✅ You keep searching for the same notes

### Step 2: Create the File

Name it clearly:
- `MOC - [Topic].md`
- Examples:
  - `MOC - Cybersecurity AI.md`
  - `MOC - Web Dev Course.md`
  - `MOC - Advanced Prompting.md`

### Step 3: Populate with Links

```markdown
# MOC: Cybersecurity AI

## Exercícios Básicos
- [[Password Security Basics]]
- [[Phishing Detection]]
- [[Social Engineering Awareness]]

## Exercícios Avançados
- [[Penetration Testing with AI]]
- [[Incident Response]]
- [[Threat Analysis]]

## Teoria
- [[Fundamentos de Cibersegurança]]
- [[AI em Security Operations]]

## Ferramentas
- [[Prompts para Análise de Logs]]
- [[Automatização de Resposta]]
```

### Step 4: Link to Parent MOCs

```markdown
## Ligações
- Parent: [[MOC - Exercise Bank]]
- Related: [[MOC - Legal AI]] (forensics)
- Related: [[MOC - Workspace AI]] (security)
```

### Step 5: Update Other MOCs

Add link in parent MOC:
```markdown
## Domínios
...
- [[MOC - Cybersecurity AI]] ← NEW!
```

---

## MOC Hierarchy in Your Vault

```
MOC - Exercise Bank (Master)
├── MOC - Legal AI
│   ├── MOC - Petição Inicial
│   └── Prompt Engineering files
├── MOC - Workspace AI
│   └── Tool-specific files
├── MOC - Teachers AI
│   ├── Examples/
│   └── Templates/
├── MOC - Journalism AI
│   ├── Modules/
│   └── Applications/
├── MOC - B-Corp AI
├── MOC - Comms AI
└── MOC - Bootcamp
    ├── MOC - Bootcamp Curriculum
    └── MOC - Bootcamp Evaluation

MOC - Cause and Effect (Thinking)
├── AI Limitations/
├── Education/
└── Philosophy/
```

---

## MOC Patterns

### Pattern 1: The Hub
Central MOC linking to everything in a domain.

**Example:** `MOC - Legal AI` links to ALL legal content.

### Pattern 2: The Index
Alphabetical or categorized list.

**Example:**
```markdown
## A
- [[Análise de Acórdãos]]
- [[Análise Financeira]]

## B
- [[B-Corp Cases]]
- [[Bootcamp Curriculum]]
```

### Pattern 3: The Course Map
Week-by-week structure.

**Example:**
```markdown
## Semana 1: Fundamentos
- [[Módulo I - Fundamentos]]
- [[Exercício 1]]

## Semana 2: Prática
- [[Módulo II]]
- [[Exercício 2]]
```

### Pattern 4: The Dashboard
Overview with status and metrics.

**Example:**
```markdown
## Status
- ✅ Módulos completos: 5
- 📝 Em desenvolvimento: 2
- ⏳ Planeados: 3

## Próximos Passos
1. [[Task 1]]
2. [[Task 2]]
```

---

## Working with MOCs

### Daily Workflow

**Morning - Planning:**
1. Open relevant MOC
2. See what needs attention
3. Choose next task

**Working:**
1. Create new note
2. Link to appropriate MOC
3. Update MOC with new link

**Evening - Review:**
1. Check MOC for orphaned links
2. Add any missing connections
3. Plan tomorrow

### Weekly Review

**Questions to ask:**
- Are there orphaned notes not in any MOC?
- Do MOCs need reorganization?
- Should I create a new MOC?
- Are links working correctly?

---

## Common Mistakes

### ❌ Don't: Create MOCs Too Early
**Bad:** Create MOC with 1-2 notes  
**Better:** Wait until you have 5+ related notes

### ❌ Don't: Over-organize
**Bad:** MOC inside MOC inside MOC (3+ levels)  
**Better:** Max 2-3 levels deep

### ❌ Don't: Forget to Update
**Bad:** Create MOC, never maintain it  
**Better:** Add to MOC every time you create a related note

### ❌ Don't: Duplicate Content
**Bad:** Copy-paste note content into MOC  
**Better:** Just link with `[[...]]`

### ❌ Don't: Too Many Categories
**Bad:** 15+ categories in one MOC  
**Better:** 3-7 main categories max

---

## Examples from Your Vault

### Example 1: Simple MOC
```markdown
# MOC - Workspace AI

## Ferramentas
- [[Gmail - Smart Communication]]
- [[Docs - Content Creation]]
- [[Sheets - Data Intelligence]]

## Workflows
- [[Workflows - Complete Integration]]

## Ligações
- [[MOC - Exercise Bank]]
```

### Example 2: Complex MOC
```markdown
# MOC - Bootcamp Curriculum

## Sobre
Plano curricular completo de 14 semanas.

## Módulos
### Fundamentos
- [[Módulo I - Fundamentos]]

### Java
- [[Módulo II - Java I]]
- [[Módulo III - Web e Redes]]
- [[Módulo IV - Engenharia de Software]]
- [[Módulo V - Frameworks Java]]

### Frontend
- [[Módulo VI - JavaScript]]

## Metodologia
- [[Filosofia Pedagógica]]
- [[Dia Típico no Bootcamp]]

## Ligações
- [[MOC - Bootcamp Evaluation]]
- [[MOC - Exercise Bank]]
```

---

## Quick Reference

### Creating a MOC
1. ✅ Have 5+ related notes
2. ✅ Create `MOC - [Name].md`
3. ✅ Add description
4. ✅ Link to child notes
5. ✅ Link to parent MOCs
6. ✅ Add metadata

### Maintaining MOCs
- **Daily:** Add new links as you create notes
- **Weekly:** Check for orphans
- **Monthly:** Review structure

### Navigation
- Start at `MOC - Exercise Bank`
- Drill down to domain MOCs
- Find specific notes
- Or use Obsidian graph view

---

## Your Current MOCs

✅ **Master MOCs:**
- MOC - Exercise Bank
- MOC - Cause and Effect

✅ **Domain MOCs (7):**
1. MOC - Legal AI
2. MOC - Workspace AI
3. MOC - Teachers AI
4. MOC - Journalism AI
5. MOC - B-Corp AI
6. MOC - Comms AI
7. MOC - Bootcamp (with 2 sub-MOCs)

✅ **Sub-MOCs:**
- MOC - Petição Inicial
- MOC - Bootcamp Curriculum
- MOC - Bootcamp Evaluation

**Total: 10 MOCs navigating 83+ notes**

---

## FAQ

**Q: When should I create a new MOC?**
A: When you have 5+ related notes or navigation becomes hard.

**Q: Can a note be in multiple MOCs?**
A: Yes! That's the power of MOCs vs folders.

**Q: How many MOCs is too many?**
A: There's no limit, but keep hierarchy flat (2-3 levels max).

**Q: Do I need to maintain MOCs manually?**
A: Yes, but it takes seconds when creating new notes.

**Q: What's the difference between a MOC and a folder?**
A: Folders force one location. MOCs allow multiple contexts.

---

**Remember:** MOCs are living documents that grow with your knowledge!
