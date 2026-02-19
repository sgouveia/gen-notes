# LEGAL - Como estruturar um prompt

## **Proposta 1:**

### 1.a. Explicar conceitos legais para audiências diferentes:

- Explica o conceito de "contrato" em termos gerais.
- Explica o conceito de "contrato" para uma criança de 5 anos.
- Explica o conceito de "contrato" para um Juiz do Supremo Tribunal.

### 1.b. Aplicar few-shot learning em classificação de risco jurídico:

Classifica o nível de risco jurídico (0 - baixo risco; 10 - risco muito elevado) das seguintes situações, com base nestes exemplos:

- “Assinatura de contrato com uma empresa insolvente” – 9
- “Formalização de contrato verbal sem testemunhas” – 7
- “Contrato escrito e devidamente assinado por ambas as partes” – 1

Situações a classificar:

- “Contrato assinado por procuração não autenticada”
- “Contrato por email com confirmação escrita das partes”
- “Contrato de fornecimento com cláusulas pouco claras sobre indemnizações”

### 1.c. Adicionar formato e papel:

Agora, refaz a classificação acima em formato tabela.  
Assumindo que és Diretor Jurídico da empresa, sugere as ações corretivas que devem ser implementadas para mitigar os riscos jurídicos identificados.

---

## **Proposta 2:**

### 2.a. Explicar conceitos jurídicos complexos:

- Explica o que é RGPD (Regulamento Geral sobre a Proteção de Dados).
- Explica o RGPD para uma criança de 5 anos.
- Explica o RGPD para um advogado especialista em proteção de dados.

### 2.b. Aplicar few-shot learning na análise de cláusulas contratuais:

Classifica as cláusulas contratuais segundo o risco de nulidade jurídica (0 - sem risco; 10 - risco elevado):

- “Cláusula que viola explicitamente legislação laboral vigente” – 10
- “Cláusula de confidencialidade genérica mas clara” – 2
- “Cláusula discriminatória quanto à idade dos funcionários” – 9

Cláusulas a classificar:

- “Cláusula que limita direitos básicos garantidos constitucionalmente”
- “Cláusula clara sobre condições de rescisão contratual”
- “Cláusula com linguagem ambígua sobre deveres das partes”

### 2.c. Adicionar formato e papel:

Em formato de tabela, indica, enquanto Diretor de Compliance Jurídico, que medidas sugeres implementar para garantir conformidade e evitar a nulidade das cláusulas.

---

## **Proposta 3:**

### 3.a. Explicar conceitos processuais para audiências diversas:

- Explica o conceito de "litígio".
- Explica o conceito de "litígio" para uma criança de 5 anos.
- Explica o conceito de "litígio" para um advogado especializado em arbitragem internacional.

### 3.b. Aplicar few-shot learning em classificação de gravidade jurídica:

Classifica o grau de gravidade (0 - leve; 10 - grave) dos seguintes casos, usando estes exemplos:

- “Processo por incumprimento contratual reiterado” – 8
- “Ação judicial por pagamento atrasado de pequeno valor” – 3
- “Litígio sobre direitos fundamentais constitucionais” – 9

Casos a classificar:

- “Disputa por propriedade intelectual registada”
- “Cobrança extrajudicial amigável”
- “Ação por incumprimento de prazos numa entrega crítica”

### 3.c. Adicionar formato e papel:

Como Diretor Jurídico responsável pela Gestão de Risco, organiza os casos numa tabela indicando claramente as ações imediatas necessárias para reduzir o risco associado a cada caso.