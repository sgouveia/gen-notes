# Caso 3: Criação e Visualização de Dados

## Contexto

A empresa quer motivar equipas a participarem melhor na separação de resíduos e reciclagem.

---

## Parte I: Criação de Prompt Básico

### Objetivo
Criar dataset e visualização sobre reciclagem por equipa.

### Prompt

```
Sou gestor de operações de uma B Corp. 
Cria um pequeno dataset fictício e visualmente interessante com os dados de reciclagem por equipa ao longo do último trimestre. 
O objetivo é criar um gráfico para partilhar com a empresa.
```

### Elementos do Prompt

**Persona:** Gestor de operações  
**Tema:** Reciclagem e separação de resíduos  
**Output:** Dataset + Visualização  
**Período:** Último trimestre  
**Objetivo:** Motivar participação  
**Audiência:** Toda a empresa

---

## Parte II: Desenvolvimento de Prompts Mais Complexos

### Tarefa 1: Formato CSV

**Objetivo:** Dados estruturados para Excel/análise

**Prompt:**
```
Converte os dados de reciclagem para formato CSV com colunas: 
Equipa, Mês, Quantidade (kg), Tipo de Resíduo, Taxa de Reciclagem (%). 
Inclui etiquetas claras para fácil visualização em Excel.
```

### Tarefa 2: Sugestões de Gráficos

**Objetivo:** Diferentes formas de visualizar os mesmos dados

**Prompt:**
```
Sugere diferentes tipos de gráficos para comunicar os dados de reciclagem:
1. Gráfico de barras - para comparar equipas
2. Gráfico de pizza - para mostrar composição
3. Gráfico de linha temporal - para mostrar evolução
Para cada um, explica quando usar e vantagens.
```

### Tarefa 3: Email Motivacional

**Objetivo:** Comunicar resultados e incentivar participação

**Prompt:**
```
Redige um email motivacional para partilhar os resultados de reciclagem com as equipas, incluindo:
- Reconhecimento das equipas com melhor desempenho
- Dados do trimestre apresentados de forma positiva
- Metas para o próximo trimestre
- Call-to-action para continuar o esforço
Tom: Celebrativo mas descontraído
```

---

## Exercício Prático

### Desafio
Criar campanha completa de engajamento:

1. **Dataset**
   - Criar dados fictícios realistas
   - 5 equipas, 3 meses
   - Métricas: quantidade, taxa, tipos

2. **Visualização**
   - Escolher melhor tipo de gráfico
   - Criar versão para apresentação
   - Criar versão para email

3. **Comunicação**
   - Email motivacional
   - Post interno (Slack/Teams)
   - Slide para reunião

### Template de Dataset

```csv
Equipa,Jan (kg),Fev (kg),Mar (kg),Taxa Reciclagem,Destaque
Marketing,45,52,58,85%,Melhoria consistente
Operações,120,118,125,78%,Volume maior
IT,25,28,32,92%,Taxa mais alta
Vendas,60,65,70,82%,Bom equilíbrio
RH,15,18,20,88%,Crescimento rápido
```

### Discussão
- Que tipo de visualização é mais motivadora?
- Como equilibrar reconhecimento e incentivo?
- Que gamificação poderia ser adicionada?

---

**Tipo:** Sustentabilidade / Engajamento  
**Nível:** Intermédio  
**Foco:** Dados e visualização para impacto comportamental

**Próximo:** [[Caso 4 - Refinar Prompts para Ética e Clareza]]

**Fonte original:** [[b-corp-exercises]]
