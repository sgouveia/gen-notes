# Ferramentas de Avaliação

## 1. Assiduity Tracking (Registo de Assiduidade)

### Objetivo
Registar quem está presente e a que horas.

### Implementação
**Frequência:** Todos os dias

**Momentos:**
- Antes do summarizer
- Antes do almoço
- Depois do almoço

**Método:**
Login-based (sistema digital)

### Dados Coletados
- Presença/ausência
- Horários de entrada
- Padrões de assiduidade

### Uso
- Identificar problemas de engajamento
- Intervenção precoce
- Feedback aos alunos

---

## 2. Exercise Conclusion Tracking

### Objetivo
Verificar quem terminou cada exercício.

### Implementação
**Quando:** Todos os dias, antes do summarizer

**Quem pode fazer:**
- Master Coders
- Padawans (alunos avançados)

### Checklist
- [ ] Exercício iniciado
- [ ] Exercício concluído
- [ ] Número de tentativas
- [ ] Tempo gasto
- [ ] Dificuldades encontradas

### Uso
- Identificar alunos em dificuldade
- Ajustar ritmo do curso
- Feedback individual

---

## 3. Summarizer and Homeworks Assessment

### Contexto
Duas apresentações diárias por alunos:
- **Summarizer:** Resumo do dia anterior
- **Homework:** Apresentação do trabalho de casa

### Critérios de Avaliação

#### 1. Clarity (Clareza)
- Organização do conteúdo
- Linguagem clara
- Fluxo lógico da apresentação

#### 2. Creativity (Criatividade)
- Descrições imaginativas
- Histórias e analogias
- Formas únicas de apresentar

#### 3. Storytelling (Narrativa)
- Estrutura clara (início, meio, fim)
- Engajamento da audiência
- Coerência narrativa

#### 4. Interaction (Interação)
- Encoraja participação
- Perguntas e discussões
- Polls quando aplicável

#### 5. Technical Understanding
- Profundidade de conhecimento
- Precisão técnica
- Capacidade de explicar conceitos

#### 6. Code Readability
- Estrutura organizada
- Convenções de nomenclatura
- Comentários claros

### Escala de Avaliação
1. **Poor** (Fraco)
2. **Average** (Médio)
3. **Good** (Bom)
4. **Excellent** (Excelente)

---

## 4. One-on-Ones Documentation

### Objetivo
Documentar conversas individuais entre professores e alunos.

### Quando Documentar
**Sempre que:**
- Conversa longa (não apenas dúvida rápida)
- Discussão sobre progresso
- Feedback individual
- A menos que seja a 5ª vez sobre o mesmo problema

### Abordagem Proativa
Master Coders devem:
- Ir aos alunos (não esperar que venham)
- Perguntar como estão
- O que estão a fazer
- O que vão fazer a seguir

### Template de Documentação

```
Data: [DD/MM/AAAA]
Exercício: [Nome do exercício]
Aluno: [Nome do Code Cadet]
Professor: [Nome do MC]
Comentário: [Resumo da conversa]
```

### Critérios Opcionais (quantificáveis)
- Nível de confiança (1-4)
- Clareza de objetivos (1-4)
- Necessidade de suporte (1-4)

---

## 5. Exercise Checkpoints

### Objetivo
Avaliações mais formais periódicas.

### Frequência
A cada 2 semanas (aproximadamente)

### Natureza
Quase como um teste, mas formativo.

### Processo
1. Selecionar exercício significativo
2. Master Coder faz review detalhada
3. Um-a-um com cada aluno
4. Documentar observações

### Exemplos de Exercícios
- Hotel/Money in The Bank
- Map Editor
- Chat Server
- MVC application

### O que Avaliar
- Qualidade do código
- Compreensão dos conceitos
- Resolução de problemas
- Boas práticas
- Documentação

### Template de Review
```
Data: [DD/MM/AAAA]
Exercício: [Nome]
Aluno: [Nome]
Avaliação Geral: [1-4]
Pontos Fortes:
- [Ponto 1]
- [Ponto 2]
Áreas de Melhoria:
- [Área 1]
- [Área 2]
Próximos Passos: [Recomendações]
```

---

## Implementação Tecnológica

### Requisitos
- Centralização de dados
- Múltiplas visualizações:
  - Por aluno
  - Por exercício
  - Por critério
  - Por turma

### Ferramentas Sugeridas
- **Notion:** Bases de dados relacionadas
- **Google Drive:** Pasta estruturada
- **Airtable:** Bases de dados avançadas
- **Sistema próprio:** Desenvolvimento interno

### Objetivo
> "Assess how we are doing, and what could be improved with the smallest amount of inertia and entropy."

---

**Fonte original:** [[bootcamp/evaluation]]
