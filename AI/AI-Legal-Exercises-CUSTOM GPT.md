## Step-by-Step: Criação de CustomGPT para Imigração

### **Fase 1: Preparação e Planeamento (5-10 minutos)**

**1. Escolha do tema específico**

- Foca-te nas **mudanças recentes** na legislação portuguesa (muito relevante agora!)
- Sugestão: "**Assistente de Imigração Portugal 2024-2025**"

**2. Recolha de documentação essencial:**

- Nova Regulamentação da Lei de Estrangeiros (Decreto Regulamentar n.º 1/2024) [AIMA](https://aima.gov.pt/pt/decreto-regulamentar-da-lei-de-estrangeiros-alteracoes)[Portugal](https://www.portugal.gov.pt/pt/gc25/comunicacao/noticia?i=governo-reforma-exigencia-nas-leis-de-nacionalidade-e-residencia)
- Novas regras aprovadas em junho 2025: aumento do prazo para nacionalidade (10 anos gerais, 7 anos para CPLP) [RTP](https://www.rtp.pt/noticias/politica/reforco-da-exigencia-novas-regras-para-a-imigracao-incluem-aumento-do-prazo-para-atribuicao-de-nacionalidade_n1664187)[DN](https://www.dn.pt/sociedade/imigrante-terá-de-morar-10-anos-no-país-para-o-pedido-de-nacionalidade-e-7-para-falantes-de-língua-portuguesa)
- Decreto-Lei n.º 41-A/2024 sobre prorrogação de documentos [Prorrogação da validade dos documentos e vistos de permanência em Portugal - Pessoas](https://pessoas2030.gov.pt/2024/07/18/prorrogacao-da-validade-dos-documentos-e-vistos-de-permanencia-em-portugal/)
- Formulários da AIMA mais comuns
- FAQ sobre reagrupamento familiar
- Guias sobre vistos de trabalho

### **Fase 2: Criação do CustomGPT (10-15 minutos)**

**3. Acesso ao GPT Builder**

- Vai a ChatGPT → "Explore GPTs" → "Create a GPT"
- Escolhe "Create" para começar do zero

**4. Configuração inicial**

```
Nome: "Assistente Imigração Portugal 2025"
Descrição: "Especialista em legislação portuguesa de imigração com foco nas mudanças de 2024-2025. Ajuda com pedidos de residência, nacionalidade, reagrupamento familiar e vistos."
```

**5. Instruções detalhadas para o GPT:**

```
Tu és um assistente especializado em legislação portuguesa de imigração, atualizado com as alterações de 2024-2025. 

PRIORIDADES:
- Usa SEMPRE a documentação carregada como fonte principal
- Menciona as mudanças recentes quando relevante
- Fornece respostas práticas e acionáveis
- Indica sempre prazos e procedimentos específicos
- Alerta para documentos necessários

TEMAS PRINCIPAIS:
- Pedidos de residência e renovações 
- Nacionalidade (novos prazos: 10 anos/7 anos CPLP)
- Reagrupamento familiar (novas regras 2 anos)
- Vistos de trabalho e procura
- Procedimentos na AIMA
- Prorrogações até junho 2025

ESTILO:
- Linguagem clara e acessível
- Estrutura as respostas por tópicos
- Indica sempre "próximos passos"
- Quando não tiveres certeza, recomenda contactar a AIMA ou advogado especializado
```

**6. Upload da documentação**

- Carrega os PDFs/documentos recolhidos
- Certifica-te que inclui os decretos mais recentes
- Adiciona formulários tipo da AIMA

### **Fase 3: Teste e Demonstração (10-15 minutos)**

**7. Perguntas de teste para demonstrar:**

- "Quanto tempo preciso de residir em Portugal para pedir nacionalidade sendo brasileiro?"
- "Como posso fazer reagrupamento familiar do meu cônjuge?"
	- "O meu documento de residência expira em março 2025, está prorrogado?"
- "Que documentos preciso para renovar a minha autorização de residência?"

**8. Refinamento:**

- Ajusta as instruções baseado nos resultados
- Adiciona mais contexto específico se necessário

### **Fase 4: Partilha e Implementação**

**9. Disponibilização:**

- Torna público ou partilha link específico
- Cria instruções simples para os clientes usarem