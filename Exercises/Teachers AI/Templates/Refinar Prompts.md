# Refinar Prompts: Básico vs Refinado

## O Problema

Prompts básicos geram resultados genéricos. Prompts refinados produzem output específico e útil.

---

## Exemplo Comparativo

### ❌ Prompt Básico (Fraco)

```
Preciso de ajuda a planear um curso de literacia em AI for 35 alunos
```

**Problemas:**
- Vago ("for" em vez de "para")
- Sem contexto (idade, nível, formato)
- Sem restrições
- Sem objetivo claro

**Resultado provável:** Resposta genérica, pouco útil

---

### ✅ Prompt Refinado (Forte)

```
Estamos a entregar um curso de literacia em IA que será entregue duas horas por semana. 
Temos 35 alunos inscritos, mas apenas 20 computadores em sala. 
Dá-me uma lista de dez potenciais soluções para este problema
```

**Melhorias:**
- ✅ Contexto claro (curso de literacia em IA)
- ✅ Formato específico (2h/semana)
- ✅ Restrição concreta (35 alunos, 20 computadores)
- ✅ Objetivo definido (lista de 10 soluções)
- ✅ Linguagem consistente (português)

**Resultado provável:** Soluções práticas e aplicáveis

---

## Framework de Refinamento

### Passo 1: Adicionar Contexto

**Antes:**
```
Cria um problema de matemática
```

**Depois:**
```
Sou professor do 6º ano de matemática. Cria um problema...
```

---

### Passo 2: Especificar Restrições

**Antes:**
```
Cria uma avaliação
```

**Depois:**
```
Cria uma avaliação de [duração] para [nível] sobre [tema], 
incluindo [tipos de questões], alinhada com [objetivos]
```

---

### Passo 3: Definir Formato de Output

**Antes:**
```
Fala-me sobre recursos literários
```

**Depois:**
```
Cria um esboço para uma apresentação de 5 slides sobre recursos literários, 
incluindo notas do orador, com cabeçalhos e marcadores
```

---

### Passo 4: Ajustar Tom e Estilo

**Antes:**
```
Escreve um email
```

**Depois:**
```
Escreve um email [formal/acolhedor/profissional] para [audiência] sobre [tema], 
com tom [entusiasta/informativo/persuasivo]
```

---

## Checklist de Refinamento

Antes de usar um prompt, verifique se tem:

- [ ] **Quem** — Persona/contexto ("Sou professor de...")
- [ ] **O quê** — Tarefa específica ("Cria uma lista de...")
- [ ] **Para quem** — Audiência ("para alunos do 9º ano")
- [ ] **Como** — Formato/formato ("em 5 slides", "com marcadores")
- [ ] **Restrições** — Limitações específicas ("em 10 minutos", "sem computadores")
- [ ] **Tom** — Estilo desejado ("formal", "acolhedor", "técnico")

---

## Exercício Prático

### Prompt Original (Fraco)
```
Preciso de ajuda com uma aula
```

### Sua Versão Refinada
Use o checklist acima para criar um prompt forte:

```
[Sou professor de _____ do _____ nível]
[Preciso criar _____ para uma aula sobre _____]
[A audiência é _____]
[O formato deve ser _____]
[Restrições: _____]
[Tom: _____]
```

---

**Tipo:** Guia de técnica  
**Skill:** Prompt engineering  
**Nível:** Todos (fundamental)  
**Aplicação:** Qualquer uso de AI

**Próximo:** [[Adaptar Output]]

**Fonte original:** [[Professores AI Course]]
