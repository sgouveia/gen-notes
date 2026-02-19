# AI and Causality: Correlation vs Causation

## The Core Problem

AI systems excel at identifying **patterns and correlations** in data but struggle to infer **causal relationships**. 

### Example: O isqueiro e o cancro
Uma AI treinada para prever cancro do pulmão pode notar que **possuir um isqueiro** está correlacionado com cancro. Mas não entende que é o **acto de fumar** — não o isqueiro — que causa a doença.

**Impacto nocivo:** A AI poderia propor a proibição de venda de isqueiros ou sugerir "não compre isqueiros" como prevenção, falhando completamente a cadeia causal verdadeira: `fumar → carcinógenos → cancro`

## Porque é que a AI falha?

### 1. Padrões Estatísticos vs Mecanismos Causais
Modelos de AI, incluindo LLMs como ChatGPT, aprendem **padrões estatísticos**, não mecanismos de causalidade.

### 2. Dificuldade com Contrafactuais
AI tem dificuldade com questões do tipo:
- "Será que esta pessoa ainda teria cancro se não fumasse?"
- "Como é que deixar de fumar afecta o outcome?"

### 3. O Problema do "Atalho Causal"
AI frequentemente toma atalhos baseados em padrões superficiais ou enviesados:

**Exemplo do hospital:**
Uma AI poderia detectar que doentes com asma têm índices de mortalidade por COVID inferiores. Porquê? Porque doentes de asma recebem tratamentos mais agressivos (confounder escondido). A AI poderia concluir erroneamente que ter asma é protetor e sugerir "não se preocupe com COVID se tiver asma" — conselho perigoso.

## Implicações no Mundo Real

| Domínio | Problema | Consequência |
|---------|----------|--------------|
| **Medicina** | AI associa pressão alta a doenças cardíacas, mas não entende que doenças podem causar pressão alta (reversa causalidade) | Diagnósticos incorrectos, tratamentos inadequados |
| **Policiamento preditivo** | AI identifica correlação entre bairros de baixa renda e criminalidade, mas não entende que a pobreza é a causa raiz | Policiamento enviesado, desigualdades reforçadas |
| **Mudanças climáticas** | AI prevê que emissões correlacionam com temperaturas, mas pode não captar feedback loops (albedo) | Políticas climáticas ineficazes |

## A Vantagem Humana

Humanos usam **conhecimento de domínio** (biologia, contexto social) para desembaraçar estas relações. AI carece desta compreensão inata.

## Causal AI: O Futuro?

Pesquisadores estão a trabalhar em técnicas como:
- **Causal graphs**: Modelar explicitamente relações causa-efeito
- **Counterfactual reasoning**: "O que aconteceria se X não tivesse ocorrido?"
- **Interventional data**: Treinar AI em experiências (ensaios randomizados) vs apenas dados observacionais

**Limitação:** Estes métodos requerem **frameworks desenhados por humanos** para guiar a AI. Treino puramente data-driven, mesmo com datasets massivos, frequentemente falha.

---

**Relacionado:**
- [[AI and Empathy]]
- [[Heuristics and Human Automation]]
- [[Teaching as Love]]
- [[Causa e Efeito]] (nota resumida em português)

**Origem:** [[Cause and Effect First Notes]] (conversa original completa)
