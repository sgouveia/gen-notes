# Workflows - Bringing It All Together

## Introdução

Nesta secção final, vamos demonstrar como todas as ferramentas se conectam num workflow integrado end-to-end — desde o primeiro email até ao projeto concluído.

---

## Workflow Completo: TechFlow Solutions

### Cenário
Receber email de potencial cliente → Fechar proposta → Gerir projeto

---

## Etapa 1: Captura do Lead (Gmail)

**Entrada:** Email de Maria Santos/TechFlow solicitando proposta

**Ações:**
1. **Ler e compreender** email com Gemini
2. **Gerar resposta** profissional e consultiva
3. **Identificar necessidades** e questões de esclarecimento
4. **Agendar** reunião de descoberta (Calendar)

**Prompts usados:**
```
Ajuda-me a redigir uma resposta profissional a este email, agradecendo o interesse...
```

```
Cria uma agenda para reunião de descoberta incluindo...
```

---

## Etapa 2: Preparação da Proposta (Docs + Sheets + Slides)

**Documentação:**
1. **Criar proposta completa** no Docs
   - Objetivos de aprendizagem
   - Estrutura do programa
   - Metodologia e exercícios práticos
   - Cronograma
   - ROI e métricas

2. **Orçamentar** no Sheets
   - Calcular custos baseados em valores base
   - Analisar ROI
   - Criar cenários alternativos

3. **Criar apresentação** no Slides
   - Transformar proposta em slides
   - Integrar dados do Sheets
   - Aplicar design profissional

**Prompts usados:**
```
Cria uma proposta abrangente de formação em IA para...
```

```
Cria uma tabela com análise de ROI para formação de 50 pessoas...
```

```
Cria uma apresentação de 6 slides para a reunião...
```

---

## Etapa 3: Reunião de Vendas (Meet + Calendar)

**Ações:**
1. **Agendar** reunião com buffers (Calendar)
2. **Preparar agenda** detalhada
3. **Conduzir reunião** com apresentação
4. **Capturar** tudo (Meet + transcrição)
5. **Extrair** action items e decisões

**Prompts usados:**
```
Baseado na proposta, cria uma agenda detalhada para esta reunião...
```

```
Resume os pontos principais discutidos nesta reunião...
```

```
Extrai todos os action items desta reunião...
```

---

## Etapa 4: Setup do Projeto (Spaces)

**Organização:**
1. **Criar Space** para projeto TechFlow
2. **Estruturar** com secções relevantes
3. **Importar** todos os documentos criados
4. **Definir** tarefas e milestones
5. **Conectar** com Calendar para deadlines

**Prompts usados:**
```
Organiza este espaço para gerir um projeto de formação...
```

```
Cria uma lista completa de tarefas com responsáveis...
```

```
Cria métricas automáticas para acompanhar progresso...
```

---

## Etapa 5: Execução e Acompanhamento (Workflow contínuo)

**Gestão contínua:**
1. **Reuniões de acompanhamento** (Meet + Calendar)
2. **Atualização de tarefas** (Spaces)
3. **Relatórios de progresso** (Docs + Gemini)
4. **Comunicação com cliente** (Gmail)
5. **Avaliação e feedback** (Sheets + Forms)

---

## Tempo Total Economizado

### Antes (modo tradicional)
- Responder email: 15 min
- Criar proposta: 3-4 horas
- Orçamentar: 1 hora
- Criar apresentação: 2 horas
- Preparar reunião: 30 min
- Documentar: 30 min
- **Total: ~8 horas**

### Depois (com Gemini)
- Responder email: 2 min
- Criar proposta: 15 min
- Orçamentar: 5 min
- Criar apresentação: 10 min
- Preparar reunião: 5 min
- Documentar: 5 min
- **Total: ~45 minutos**

**Economia: ~7 horas (87% redução)**

---

## Templates de Workflow

### Template: Resposta a Novo Lead

**1. Gmail:**
```
Ajuda-me a redigir uma resposta a [email], pedindo esclarecimentos sobre: [lista]
```

**2. Calendar:**
```
Agenda reunião de [duração] com [email] para [semana], preferência [manhã/tarde]
```

**3. Docs (preparação):**
```
Cria agenda de reunião incluindo: objetivos, perguntas a fazer, pontos a clarificar
```

---

### Template: Criação de Proposta

**1. Docs:**
```
Cria proposta de [tipo] para [cliente], incluindo: objetivos, estrutura, metodologia, cronograma, investimento
```

**2. Sheets:**
```
Cria orçamento para [projeto] com: custos, margens, ROI, cenários alternativos
```

**3. Slides:**
```
Cria apresentação de [N] slides baseada na proposta [doc], mantendo design do template
```

---

### Template: Setup de Projeto

**1. Spaces:**
```
Cria space para projeto [nome] com secções: [lista], e importa: [docs/sheets/slides]
```

**2. Tarefas:**
```
Baseado no cronograma, cria tarefas com: responsáveis, deadlines, dependências
```

**3. Tracking:**
```
Cria dashboard de progresso com: % conclusão, tarefas em risco, milestones
```

---

## Integrações-Chave

### Gmail → Calendar
- Email recebido → Evento criado automaticamente
- Agenda incluída na descrição

### Docs → Slides
- Proposta no Docs → Apresentação automática
- Conteúdo sincronizado

### Sheets → Slides
- Dados financeiros → Gráficos na apresentação
- ROI calculado automaticamente

### Calendar → Meet
- Evento agendado → Link Meet incluído
- Transcrição ativada

### Meet → Spaces
- Resumo da reunião → Documentação do projeto
- Action items → Tarefas no Space

### Spaces → Calendar
- Tarefas criadas → Time blocks no Calendar
- Deadlines → Lembretes automáticos

---

## Melhores Práticas

**1. Consistência de Cenário**
Manter o mesmo contexto (TechFlow) ao longo de todo o webinar demonstra continuidade real.

**2. Iteração e Refinamento**
Mostrar como melhorar prompts progressivamente (básico → refinado).

**3. Fallbacks**
Ter alternativas quando integrações automáticas não funcionam.

**4. Valor Mensurável**
Quantificar tempo economizado (8h → 45min = 87% redução).

**5. Aplicabilidade Imediata**
Espectadores devem conseguir aplicar no próprio dia.

---

## Exercício Prático para Audiência

**Desafio:** Pensar num workflow próprio que possa otimizar.

**Perguntas:**
1. Que tarefas repetitivas consomem mais tempo?
2. Que ferramentas já usa no Google Workspace?
3. Onde costuma haver perda de informação ou comunicação?
4. Que processo gostaria de automatizar primeiro?

**Tarefa:** Escrever 3 prompts que usaria no seu workflow.

---

**Tempo estimado:** 20 minutos  
**Demo ao vivo:** Sim, recapitulando workflow completo  
**Interatividade:** Exercício prático final

**Fonte original:** [[AI - Google Workspace Webinar]] (secção Workflow Automation)

**Próximo:** What's Next + Q&A (15 min)
