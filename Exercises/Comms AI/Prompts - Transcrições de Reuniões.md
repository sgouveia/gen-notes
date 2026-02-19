# Prompts - Transcrições de Reuniões

## Estruturação de Informação

### Template de Extração

**Prompt:**
```
Tens à tua frente a transcrição de uma reunião. 
Extrai a informação de forma estruturada nos seguintes campos:

- **Data da reunião**
- **Lista de participantes** (nome e cargo, se disponível)
- **Tema principal da reunião** (resumo em 1 frase)
- **Tópicos discutidos** (lista de tópicos principais)
- **Ações finais** (cada uma com: responsável, tarefa, e deadline, se existir)
- **Emoção dominante da reunião** (opcional: neutra, positiva, tensa, urgente, etc.)
```

---

## Exemplo 1: Lançamento de Campanha

**Reunião:** Lançamento de Nova Campanha de Comunicação Interna

**Transcrição:**
```
Data: 3 de maio de 2025  
Participantes:
- Ana Martins (Diretora de Comunicação Interna)
- João Costa (Designer)
- Beatriz Lopes (RH)
- Miguel Franco (Copywriter)

Ana Martins: Obrigada a todos por estarem aqui. Como sabem, vamos lançar a campanha 
"Somos Todos Voz da Empresa", focada na valorização das equipas internas.

Beatriz Lopes: Sim, acho essencial reforçarmos o sentimento de pertença. 
Sugiro envolver os team leaders no processo.

João Costa: Concordo. A nível visual, pensei em usar fotos reais dos colaboradores, 
sem banco de imagem.

Miguel Franco: E em termos de tom, usamos uma abordagem mais emocional, certo? 
Tipo storytelling?

Ana Martins: Sim, exatamente. Vamos partilhar histórias reais no Workplace 
e fazer vídeos curtos semanais.

Beatriz Lopes: Lembrar também que temos o Dia da Empresa a 25 de maio. 
Pode ser o ponto de arranque da campanha.

Ações Finais:
- Miguel cria proposta de storytelling até dia 6
- João apresenta rascunhos visuais no dia 7
- Ana coordena alinhamento com diretores
```

**Output Estruturado:**

| Campo | Valor |
|-------|-------|
| Data | 3 de maio de 2025 |
| Participantes | Ana Martins (Dir. Com. Interna), João Costa (Designer), Beatriz Lopes (RH), Miguel Franco (Copywriter) |
| Tema | Lançamento campanha "Somos Todos Voz da Empresa" |
| Tópicos | Valorização equipas, envolvimento team leaders, storytelling, Dia da Empresa |
| Ações | Miguel: proposta storytelling até dia 6; João: rascunhos visuais dia 7; Ana: alinhamento diretores |
| Emoção | Positiva, colaborativa |

---

## Exemplo 2: Avaliação de Crise

**Reunião:** Avaliação de Crise nas Redes Sociais

**Contexto:**
Publicação no Instagram sobre embalagem com defeito gerando comentários negativos.

**Ações Extraídas:**
- Catarina: levantamento de comentários prioritários
- Sofia: cria post oficial até final do dia
- Hugo: aprova mensagem final

---

## Exemplo 3: Planeamento de Evento

**Reunião:** Planeamento da Comunicação de Evento Corporativo

**Contexto:**
Evento confirmado para 18 de março, no Convento do Beato.

**Fases de Comunicação:**
1. Teaser
2. Anúncio oficial
3. Contagem decrescente
4. Cobertura ao vivo

---

## Exercícios Práticos

### Exercício 1
Transcrever uma reunião real e aplicar o template.

### Exercício 2
Comparar 3 transcrições e identificar padrões.

### Exercício 3
Criar resumo executivo a partir de 5 reuniões.

---

**Fonte original:** [[AI/Prompt Engineering for Comunicação]]
