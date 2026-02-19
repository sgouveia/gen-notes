# Módulo 2 – Técnicas de Prompting

## O que é um prompt?
Um *prompt* é o input fornecido a um modelo de IA para gerar uma resposta. Pode ser uma pergunta, uma instrução, ou até um exemplo de tarefa. A forma como o prompt é escrito influencia diretamente a qualidade, relevância e utilidade da resposta gerada.

> **Exemplos de prompts simples:**
> - "Explica a fotossíntese em linguagem acessível."
> - "Resume este texto em três frases."
> - "Gera cinco ideias para o nome de uma marca de café."

No fundo, o prompt é o ponto de partida da conversa com a IA — quanto melhor for a pergunta, melhor será a resposta. A interação entre humano e IA depende da clareza, contexto e intenção com que se formula o pedido.

> **Exemplos mais elaborados:**
> - "Simula uma conversa entre um médico e um paciente com dúvidas sobre a vacina contra a gripe."
> - "Cria um resumo executivo de 150 palavras sobre os desafios da sustentabilidade no setor da moda."
> - "Gera três títulos alternativos para este artigo com diferentes tons: formal, criativo e provocador."

## Como construir bons prompts?
Prompts eficazes são claros, específicos e orientados para uma tarefa concreta. Um bom prompt dá contexto suficiente para o modelo compreender o objetivo do utilizador e responder de forma útil e alinhada com a expectativa.

### Boas práticas:
- **Especificar o formato esperado da resposta:** “responde em bullet points”, “usa uma tabela”, “escreve como um e-mail profissional”
- **Incluir contexto relevante:** por exemplo, indicar a audiência ou o tom pretendido
- **Dar instruções passo a passo:** dividir tarefas complexas em etapas
- **Usar linguagem simples e direta:** evitar ambiguidade
- **Testar e ajustar:** prompting é iterativo — pequenas alterações fazem grande diferença

> **Exemplo evolutivo:**
> 1. “Resume este artigo.”
> 2. “Resume este artigo em 5 bullet points.”
> 3. “Resume este artigo em 5 bullet points, para um público universitário da área da saúde, com foco em implicações práticas.”

## Tipos de prompting

### Zero-shot prompting
Neste tipo de prompt, o modelo recebe apenas a instrução, sem qualquer exemplo. É útil para tarefas simples ou quando se quer testar a capacidade de generalização do modelo.

> **Exemplo:** “Gera um título cativante para um artigo sobre energias renováveis.”
> **Variação:** “Gera um título cativante, com no máximo 10 palavras, para um artigo sobre energias renováveis dirigido a adolescentes.”

### Few-shot prompting
Inclui exemplos dentro do próprio prompt para ajudar o modelo a perceber o padrão desejado. Funciona bem quando se quer controlar o estilo, o tom ou o tipo de saída.

> **Exemplo:**
> “Traduz para inglês, mantendo o nível de formalidade:
> 1. Olá, como estás? → Hello, how are you?
> 2. Vamos almoçar amanhã? → Shall we have lunch tomorrow?
> 3. Posso ligar-te mais tarde? → Can I call you later?”

> **Outro exemplo:**
> “Corrige os erros ortográficos e reformula o texto de forma mais clara:
> Frase original: o carro tava indo pra oficina
> Resultado esperado: O carro estava a caminho da oficina.”

### Chain-of-thought prompting
Este tipo de prompting induz o modelo a explicar o seu raciocínio passo a passo. É especialmente útil para tarefas que envolvem lógica, cálculo ou decisões complexas.

> **Exemplo:** “Resolve este problema explicando cada passo: Um comboio parte de Lisboa às 14h a 120 km/h. Outro parte do Porto às 15h a 150 km/h. A que horas se cruzam?”

> **Exemplo aplicado à área jurídica:** “Avalia a legalidade desta cláusula com base na legislação portuguesa, explicando passo a passo.”

### Prompting iterativo
Envolve uma série de interações entre utilizador e modelo para refinar a resposta. É comum em contextos criativos ou quando se procura uma solução progressivamente melhor.

> **Exemplo:**
> 1. “Sugere uma ideia de negócio sustentável.”
> 2. “Desenvolve um pitch de 1 minuto para essa ideia.”
> 3. “Transforma o pitch numa apresentação de 3 slides.”
> 4. “Faz sugestões de melhoria com base num público de investidores.”

## Casos de uso comuns

- **Geração de texto:**
  - *Exemplo:* “Escreve um post para LinkedIn sobre as vantagens da energia solar, num tom informal.”
  - *Exemplo:* “Cria uma descrição de produto para um aspirador robô, destacando características técnicas.”

- **Reformulação e melhoria:**
  - *Exemplo:* “Reescreve este parágrafo para soar mais profissional.”
  - *Exemplo:* “Simplifica este texto para leitura de alunos do ensino básico.”

- **Explicações e tutoriais:**
  - *Exemplo:* “Explica o que é blockchain como se estivesse a falar com um aluno do 9.º ano.”
  - *Exemplo:* “Cria um guia passo a passo para instalar Python no Windows.”

- **Criação de sumários e bullets:**
  - *Exemplo:* “Resume este artigo de jornal em 5 bullet points informativos.”
  - *Exemplo:* “Gera um sumário executivo para este relatório técnico de 8 páginas.”

- **Extração de informação:**
  - *Exemplo:* “Extrai os nomes, datas e valores monetários deste comunicado.”
  - *Exemplo:* “Identifica as entidades mencionadas neste parecer jurídico.”

- **Comparação de opções:**
  - *Exemplo:* “Compara as vantagens de trabalhar remotamente vs. presencialmente, com base em produtividade, bem-estar e custos.”
  - *Exemplo:* “Cria uma tabela comparativa entre o iPhone 15 e o Samsung Galaxy S24.”

## Ferramentas populares

- **ChatGPT (OpenAI):** versátil, com interface acessível e suporte a GPTs personalizados
- **Claude (Anthropic):** respostas bem estruturadas e boa compreensão de contexto longo
- **Gemini (Google):** integrado com o ecossistema Google e forte em factos atualizados
- **Copilot (Microsoft):** embutido em produtos Office, focado em produtividade e código
- **DeepSeek, Grok (X):** emergentes, com foco em desenvolvimento de software ou integração com redes sociais

## Comparação entre ferramentas

| Ferramenta | Pontos fortes | Limitações |
|-----------|----------------|-------------|
| ChatGPT | Qualidade geral de linguagem, personalização com GPTs | Informação atualizada com limitações na versão gratuita |
| Claude | Rigor textual, bom em contexto longo e sumários | Menos opções de customização avançada |
| Gemini | Acesso direto à web e factos recentes | Interface e resultados menos previsíveis |
| Copilot | Integração com Word/Excel, bom para produtividade | Limitado fora do ecossistema Microsoft |
| DeepSeek | Geração de código, open source | Comunidade ainda pequena |

## Quiz – Escolha múltipla
1. O que é um "few-shot prompt"?
   - A) Um prompt usado para gerar imagens
   - B) Um prompt com vários exemplos incluídos
   - C) Um prompt com resposta imediata
   - D) Um prompt com erros propositados
   - ✅ **Resposta correta:** B

2. Quando se deve usar "chain-of-thought prompting"?
   - A) Para escrever e-mails curtos
   - B) Para pedir imagens
   - C) Para resolver problemas complexos passo a passo
   - D) Para pedir listas de compras
   - ✅ **Resposta correta:** C

3. Qual destas ferramentas se destaca pela integração com o Office?
   - A) Gemini
   - B) ChatGPT
   - C) Copilot
   - D) Claude
   - ✅ **Resposta correta:** C

4. Qual das seguintes tarefas é ideal para prompting iterativo?
   - A) Traduzir uma palavra
   - B) Gerar ideias de negócio e refinar o pitch
   - C) Converter ficheiros PDF
   - D) Calcular o IVA de uma compra
   - ✅ **Resposta correta:** B

5. Qual é uma boa prática ao escrever prompts?
   - A) Usar frases vagas para permitir liberdade ao modelo
   - B) Repetir a mesma instrução várias vezes
   - C) Especificar formato, contexto e tom desejado
   - D) Evitar palavras técnicas
   - ✅ **Resposta correta:** C

## Perguntas para reflexão
- Em que situações do teu contexto profissional poderias aplicar prompting avançado?
- A clareza do prompt influencia mais do que a ferramenta usada?
- Como podemos aprender com os erros dos modelos para melhorar os nossos pedidos?

## Leituras e recursos recomendados
### Livros
- *The Art of Prompt Engineering with ChatGPT* – Nathan Hunter
- *AI Crash Course* – Hadelin de Ponteves
- *Inteligência Artificial – Uma abordagem prática* – Arlindo Oliveira (ed. IST Press)  
  *(em português de Portugal)*

### Artigos e recursos online
- [Prompt Engineering Guide](https://www.promptingguide.ai/)
- [How to talk to ChatGPT](https://www.cs.princeton.edu/~chazelle/courses/BIB/prompting.pdf)
- [O impacto da inteligência artificial na escrita e leitura](https://www.publico.pt/2023/03/07/ciencia/noticia/inteligencia-artificial-vai-transformar-escrita-leitura-escola-2044563) – Público  
  *(artigo em português de Portugal)*
- [OpenAI Cookbook – Prompting](https://github.com/openai/openai-cookbook/tree/main/examples)

---

> 📌 Este módulo é prático e iterativo. Experimentar diferentes formas de escrever um prompt é a melhor maneira de aprender a explorar o potencial da GenAI.
