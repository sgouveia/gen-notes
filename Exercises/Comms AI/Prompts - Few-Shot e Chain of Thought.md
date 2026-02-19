# Prompts - Few-Shot e Chain of Thought

## Few-Shot Prompting

### Conceito
Fornecer exemplos de input-output para guiar o modelo.

### Exemplo: Encaminhamento de Casos

**Contexto:**
Sistema para encaminhar casos ao responsável correto.

**Perfis:**
- **Rita Moreira** – Comunicação Institucional, Imprensa, Gestão de Crise
- **Tiago Almeida** – Marketing Digital, Influencers, Redes Sociais, Campanhas

**Exemplos:**

```
Caso: Um jornalista contactou a empresa a pedir esclarecimentos sobre um artigo polémico publicado ontem.  
Encaminhar para: Rita Moreira

Caso: Um cliente fez um comentário negativo nas redes sociais e tornou-se viral.  
Encaminhar para: Tiago Almeida

Caso: Um influenciador quer fazer uma parceria para promover o novo produto da marca.  
Encaminhar para: Tiago Almeida

Caso: Um sindicato de trabalhadores quer enviar um comunicado para publicação no site interno.  
Encaminhar para: Rita Moreira

Caso: Um utilizador está a ameaçar a empresa com um processo judicial devido a publicidade enganosa.  
Encaminhar para: Rita Moreira

Caso: A equipa de vendas quer lançar uma campanha de email marketing na próxima semana.  
Encaminhar para: Tiago Almeida

Caso: Um jornalista da CNN quer entrevistar o CEO da empresa para uma peça sobre inovação.  
Encaminhar para:
```

**Resposta esperada:** Rita Moreira

---

## Chain of Thought (Cadeia de Pensamento)

### Conceito
Guiar o modelo a mostrar o raciocínio passo a passo.

### Exemplo: Cálculo de IRS

**Prompt:**
```
João é residente fiscal em Portugal e obteve os seguintes rendimentos em 2023:

Trabalho dependente (Categoria A): 25.000 euros brutos anuais. 
Despesas gerais e familiares e outras: 750 euros 
Rendimentos prediais (Categoria F): 7.500€ de rendas recebidas. 
Despesas comprovadas: 1500 euros 

Quero determinar quanto terá a pagar de IRS, considerando que não tem dependentes 
e optou pelo regime de tributação autónoma para os rendimentos prediais. 

Utiliza a seguinte linha de raciocínio: 
1. Determinar os rendimentos brutos sujeitos a IRS 
2. Apurar as deduções específicas para cada categoria 
3. Aplicar a tributação autónoma aos rendimentos prediais 
4. Calcular o IRS sobre os rendimentos da categoria A 
5. Somar os impostos apurados 
6. Verificar deduções à colecta
```

**Vantagens:**
- Maior transparência
- Fácil verificação
- Melhor para cálculos complexos

---

## Combinação de Técnicas

### Few-Shot + Chain of Thought

**Prompt:**
```
Aqui estão exemplos de análise de reuniões com estruturação de informação:

[Exemplo 1 - few-shot]

Agora analisa esta nova reunião seguindo a mesma estrutura passo a passo:
[Chain of thought]
1. Identificar participantes
2. Extrair data
3. Identificar tema principal
4. Listar tópicos
5. Extrair ações
6. Determinar sentimento
```

---

## Exercícios Práticos

### Exercício 1: Classificação
Criar 5 exemplos few-shot para classificar emails por prioridade.

### Exercício 2: Resolução de Problemas
Usar chain of thought para analisar uma crise de comunicação.

### Exercício 3: Combinação
Criar um prompt que combine ambas as técnicas para triagem de leads.

---

**Fonte original:** [[AI/Prompt Engineering for Comunicação]]
