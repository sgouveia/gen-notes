# PE Legal - Few-Shot e Chain of Thought

## Few-Shot: Encaminhamento de Casos

### Sistema de Triagem

**Contexto:**
Distribuição de casos entre dois advogados especializados.

**Advogados:**
- **Sérgio Gouveia** – Direito do Trabalho
- **Joana Romeu** – Direito Fiscal

### Exemplos de Treino

```
Caso: Um trabalhador foi despedido sem justa causa e quer impugnar o despedimento. 
Encaminhar para: Sérgio Gouveia 

Caso: Um funcionário alega discriminação salarial e pretende avançar com uma queixa. 
Encaminhar para: Sérgio Gouveia 

Caso: Um contribuinte quer regularizar dívidas fiscais antigas com a Autoridade Tributária. 
Encaminhar para: Joana Romeu 

Caso: Um trabalhador pretende reclamar o pagamento de horas extraordinárias não remuneradas. 
Encaminhar para: Sérgio Gouveia 

Caso: Uma sociedade quer reestruturar a atividade para reduzir a carga fiscal de forma legal. 
Encaminhar para: Joana Romeu 

Caso: Uma empresa recebeu uma notificação de inspeção fiscal e precisa de assessoria. 
Encaminhar para: Joana Romeu 

Caso: Um empregador deseja implementar um regime de teletrabalho e precisa de orientação jurídica. 
Encaminhar para:
```

**Resposta:** Sérgio Gouveia (Direito do Trabalho)

---

## Chain of Thought: Cálculo de IRS

### Cenário
Determinar imposto a pagar com múltiplas fontes de rendimento.

### Prompt com Raciocínio

```
João é residente fiscal em Portugal e obteve os seguintes rendimentos em 2024:

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
- Transparência do cálculo
- Fácil verificação de cada passo
- Redução de erros
- Documentação do raciocínio

---

## Combinação: Few-Shot + Chain of Thought

### Exemplo Complexo

```
Aqui estão exemplos de análise de contratos com classificação de risco:

[Exemplo 1 - Contrato de trabalho: Risco médio]
[Exemplo 2 - Contrato de arrendamento: Risco baixo]
[Exemplo 3 - Contrato internacional: Risco alto]

Agora analisa este novo contrato seguindo o mesmo raciocínio passo a passo:
1. Identificar tipo de contrato
2. Analisar cláusulas críticas
3. Identificar riscos potenciais
4. Classificar nível de risco
5. Sugerir salvaguardas
```

---

**Fonte original:** [[AI/Prompt Engineering for Legal]]
