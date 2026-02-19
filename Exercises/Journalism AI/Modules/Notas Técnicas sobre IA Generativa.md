# Notas Técnicas sobre IA Generativa

## Notas Técnicas e Conceituais

### Timeline da IA Generativa

#### Antes de 2017: Estatística vs AI
- **Abordagem estatística tradicional:** Regras fixas e probabilidades
- **Limitações:** Não aprende com dados, precisa de programação explícita

#### 2017: O Marco do Google Translate
**A Revolução do Mecanismo de Atenção**

> "Attention Google Translate 2017"

**Problema anterior:**
- Traduções iniciais eram más
- Falta de contexto
- Erros semânticos

**Solução - Mecanismo de Atenção:**
> "Mecanismo de atenção - para traduzir algo é necessário relacionar"

**Como funciona:**
- Ao traduzir uma frase, o modelo percebe o sentido das palavras pelo contexto
- Começa a prever a próxima palavra baseado em todo o contexto anterior
- Transformação revolucionária em processamento de linguagem

---

## Conceitos Fundamentais

### Predictive vs Generative

#### AI Preditiva
**Características:**
- Analisa dados históricos
- Faz previsões sobre futuro
- Classifica e categoriza
- **Exemplos:** Prever vendas, detetar fraude, recomendar produtos

#### AI Generativa
**Características:**
- Cria conteúdo novo
- Gera a partir de padrões aprendidos
- Transforma input em output criativo
- **Exemplos:** Texto, imagens, música, código

**Diferença chave:**
> "Pegar em conhecimento existente em novo conteúdo"

---

## Modelos de Linguagem (LLMs)

### ChatGPT: General Pre-trained Transformer

**Nome:**
- **G**eneral
- **P**re-trained
- **T**ransformer

**Princípio de Funcionamento:**
> "Quando estou numa frase estou a perceber o sentido da palavra pelo contexto. E começou a prever a próxima palavra"

**Processo:**
1. **Tokenização:** Palavras são convertidas em números
2. **Embeddings:** Números representam significado em múltiplas dimensões
3. **Atenção:** Modelo relaciona cada palavra com todas as outras
4. **Previsão:** Calcula probabilidade da próxima palavra
5. **Geração:** Constroi texto palavra por palavra

### Palavras → Números → Dimensões

**Analogia:**
> "Bebé aprende por exposição aos dados/a realidade"

**Embeddings:**
- Cada palavra é um vetor num espaço multidimensional
- Palavras semanticamente próximas estão próximas no espaço
- Exemplo: "rei" - "homem" + "mulher" ≈ "rainha"

---

## Geração de Imagem: Diffusion Models

### Como Funcionam

**Processo de Difusão:**
1. **Adicionar ruído:** Começa com imagem real, adiciona gradualmente ruído
2. **Treino:** Modelo aprende a reverter o processo
3. **Geração:** Começa com ruído puro, remove gradualmente para criar imagem

**Base:**
> "Criar ruído na imagem - tudo com imagens reais"

### Contexto Visual

**Compreensão de imagem:**
> "Um copo ao lado de uma bola"

**Deteção de elementos:**
- Padrões de uma imagem
- Detecção de elementos
- Relações espaciais
- Características visuais

**Repetitividade:**
> "Muito repetitivos" — padrões estatísticos em imagens

---

## Ferramentas e Plataformas

### Adobe Firefly
> "Adobe tem uma espécie de copilot"

**Integração:**
- Photoshop
- Illustrator
- Premiere
- Uso comercial seguro (treino em dados próprios)

### Gemini
> "Gemini - ferramenta"

**Modelos:**
> "Modelos - pagar a palavra não subscrição"

**Pricing diferente:**
- Alguns modelos cobram por token/palavra
- Outros por subscrição mensal
- Importante entender modelo de preços

---

## Critérios de Seleção de Modelos

### 1. Que Input/Output Quero?

**Pergunta:**
> "Que input output quero"

**Exemplo:**
> "Cria um artigo sobre arquitetura moderna baseada neste edifício"

**Considerações:**
- Tipo de conteúdo (texto, imagem, código)
- Qualidade requerida
- Comprimento/extensão
- Formato de output

### 2. Quão Rápido Quero Resultados?

**Pergunta:**
> "Quão rápido quero resultados"

**Nota:**
> "(Há empresas que precisam disto)"

**Trade-offs:**
- Modelos mais rápidos vs. mais precisos
- Latência em aplicações em tempo real
- Custo de processamento

### 3. Quanta Precisão?

**Pergunta:**
> "Quanta precisão"

**Níveis:**
- Rascunhos rápidos (menor precisão aceitável)
- Conteúdo profissional (alta precisão)
- Crítico/médico (precisão máxima)

### 4. Preço

**Fator:**
> "Preço - um milhão de utilizadores"

**Modelos:**
- **Por uso:** Pagamento por token/chamada
- **Subscrição:** Mensal/anual ilimitado
- **Enterprise:** Contratos personalizados

**Escalabilidade:**
Custo × 1.000.000 utilizadores = impacto financeiro significativo

---

## Análise de Modelos

### Leaderboard Analysis
> "Leaderboard analysis - o que conseguem fazer"

**Benchmarks:**
- MMLU (conhecimento geral)
- HumanEval (programação)
- HellaSwag (raciocínio)
- Comparativos entre modelos

### Technical Analysis
> "Technical analysis - quantos parâmetros"

**Métricas:**
- Número de parâmetros (bilhões)
- Tamanho do dataset de treino
- Arquitetura do modelo
- Recursos computacionais necessários

**Relação:**
Mais parâmetros ≠ necessariamente melhor
- Eficiência importa
- Qualidade dos dados importa
- Fine-tuning específico importa

---

## Porque Falamos Tanto de AI?

### Fatores Convergentes

**1. Google Transformer (2017)**
> "Porque falamos tanto de ai - google transformer"

- Arquitetura revolucionária
- Permitiu modelos mais grandes e eficazes
- Base de todos os LLMs modernos

**2. Evolução de Dados**
> "Evolução de dados"

- Internet proporciona quantidade massiva de dados de treino
- Dados diversos e multilingues
- Crescimento exponencial

**3. Evolução de Algoritmos**
> "Evolução de algoritmos"

- Otimizações computacionais
- Técnicas de treino mais eficientes
- Hardware especializado (GPUs, TPUs)

---

## Resumo: O Que é AI?

### AI vs Machine Learning

**Distinção:**
> "AI vs ml - ml existe fator inteligência detetar padrões"

**AI:** Campo amplo de sistemas inteligentes
**ML:** Sub-campo onde sistemas aprendem a detetar padrões

### Para Que São Usadas Redes Neuronais?

**Versatilidade:**
> "Tudo desde que haja dados"

**Aplicações:**
- Distinguir imagens
- Carro autónomo
- Padrões em dados complexos
- Processamento de linguagem
- Reconhecimento de voz
- Análise preditiva

**Condição:**
Disponibilidade de dados de qualidade para treino.

---

**Tipo:** Fundamentos técnicos  
**Nível:** Intermédio  
**Foco:** Como funciona por baixo

**Relacionado:** [[Definições de AI]] | [[Módulo 1 - Introdução à IA]]

**Fonte original:** [[Journo]]
