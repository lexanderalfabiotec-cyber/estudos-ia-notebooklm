# 📚 Miniguia de Estudos: Finanças Pessoais com NotebookLM

> Projeto prático do desafio DIO — "Acelere sua Aprendizagem com IA: Explore o Poder do NotebookLM"

---

## 🎯 Contexto e Objetivos

**Assunto escolhido:** Finanças Pessoais para Iniciantes

**Por que esse tema?**
Educação financeira é uma habilidade essencial, porém pouco ensinada nas escolas brasileiras. Usar IA para consolidar fontes e criar um guia de estudos personalizado potencializa muito o aprendizado.

**Objetivos de estudo:**
- Compreender os fundamentos de orçamento pessoal e controle de gastos
- Entender conceitos de investimentos básicos (Tesouro Direto, CDB, Fundos)
- Aprender sobre reserva de emergência e planejamento financeiro
- Dominar termos do mercado financeiro para iniciantes
- Criar um material de revisão reutilizável com apoio de IA

---

## 📎 Curadoria de Fontes (3–5 fontes abertas)

As fontes abaixo foram selecionadas, baixadas/salvas e inseridas no NotebookLM:

| # | Fonte | Tipo | Link |
|---|-------|------|------|
| 1 | Guia de Educação Financeira — Banco Central do Brasil | PDF | [bcb.gov.br](https://www.bcb.gov.br/content/cidadaniafinanceira/documentos_cidadania/Cuidando_do_seu_dinheiro_Gestao_de_Financas_Pessoais/cartilha_cidadania_financeira.pdf) |
| 2 | Como se Tornar Independente Financeiramente — CVM Investidor | Texto/PDF | [investidor.gov.br](https://www.investidor.gov.br/publicacao/Livros/livro_Como_se_tornar_independente_financeiramente.pdf) |
| 3 | Tesouro Direto — Guia do Investidor Iniciante | PDF | [tesourodireto.com.br](https://www.tesourodireto.com.br/data/files/7E/51/0E/FD/6D5B8710F4FBF5B6D8A80AC2/Guia%20do%20Investidor%20-%20Tesouro%20Direto.pdf) |
| 4 | Caderno de Educação Financeira — ENEF | PDF | [vidaedinheiro.gov.br](http://www.vidaedinheiro.gov.br/wp-content/uploads/2017/08/Caderno-Educacao-Financeira-Gestao-de-Financas-Pessoais1.pdf) |
| 5 | Guia de Finanças Pessoais — CONEF | Texto | [conef.gov.br](https://www.conef.gov.br/) |

---

## 🧠 Engenharia de Prompts e "Cicatrizes"

### Perguntas estratégicas formuladas no NotebookLM

**Prompt 1 — Visão geral:**
> "Com base nas fontes carregadas, quais são os 5 princípios fundamentais de finanças pessoais para quem está começando do zero?"

*Resposta obtida:* O NotebookLM listou: (1) controle de gastos, (2) criação de orçamento, (3) formação de reserva de emergência, (4) eliminação de dívidas antes de investir, (5) início precoce nos investimentos. Referenciou trechos do Guia do Banco Central e da ENEF.

*Observação:* A resposta foi muito genérica na primeira tentativa. Precisei refinar.

---

**Prompt 2 — Refinamento (troubleshooting):**
> "Explique de forma simples, como se eu tivesse 18 anos, o que é reserva de emergência e como calculá-la com base nas fontes."

*Resposta obtida:* Muito mais didática. Citou que a reserva deve cobrir de 3 a 6 meses de despesas fixas e indicou o trecho exato do Caderno ENEF com exemplos práticos.

*Dificuldade encontrada:* O NotebookLM às vezes mistura informações de fontes diferentes sem deixar claro qual fonte usou. Resolvi pedindo explicitamente: "Cite a fonte específica para cada ponto."

---

**Prompt 3 — Glossário:**
> "Crie um glossário com os 10 termos financeiros mais importantes presentes nas fontes, com definição em linguagem simples."

*Resposta obtida:* Gerou um glossário claro com termos como: CDI, SELIC, Tesouro Direto, Rentabilidade, Liquidez, Diversificação, Taxa de Administração, IOF, IPCA, Patrimônio Líquido.

---

**Prompt 4 — Prompts reutilizáveis:**
> "Com base no conteúdo das fontes, sugira 5 perguntas que eu poderia usar para revisar esse material no futuro."

*Resposta obtida:* Excelente. O NotebookLM gerou perguntas de revisão que cobriram todos os objetivos definidos inicialmente.

---

**Prompt 5 — Teste de limite (cicatriz):**
> "Faça uma comparação entre CDB e Tesouro Direto explicando qual é melhor."

*Dificuldade encontrada:* O NotebookLM se recusou a dar uma recomendação definitiva ("qual é melhor") por não ter fontes com comparações diretas. Aprendi que é preciso formular perguntas descritivas, não prescritivas. Reformulei para: "Quais são as diferenças entre CDB e Tesouro Direto segundo as fontes?" — funcionou perfeitamente.

---

## 📖 Miniguia de Estudo (Entrega Final)

### Resumos Estruturados

**1. Controle Financeiro e Orçamento**
Toda jornada financeira começa pelo diagnóstico: saber exatamente quanto entra e quanto sai. O método 50-30-20 divide a renda em necessidades (50%), desejos (30%) e poupança/investimentos (20%). O registro diário de gastos é a ferramenta mais simples e eficaz para identificar desperdícios.

**2. Reserva de Emergência**
Antes de qualquer investimento, é fundamental ter uma reserva equivalente a 3 a 6 meses de despesas fixas, aplicada em produto de alta liquidez (ex: Tesouro Selic ou CDB com liquidez diária). Ela protege o investidor de imprevistos sem precisar resgatar investimentos de longo prazo.

**3. Dívidas e Juros**
O crédito rotativo do cartão e o cheque especial são os maiores vilões das finanças pessoais brasileiras, com juros que podem ultrapassar 300% ao ano. A estratégia recomendada é priorizar o pagamento das dívidas com maiores juros antes de iniciar qualquer investimento.

**4. Investimentos para Iniciantes**
- **Tesouro Direto:** Títulos públicos federais, segurança máxima, ideal para iniciantes
- **CDB:** Certificado de Depósito Bancário, emitido por bancos, coberto pelo FGC até R$ 250 mil
- **Fundos de Investimento:** Gestão coletiva e profissional, boa opção para quem não quer escolher ativos

**5. Juros Compostos — O Poder do Tempo**
Investir cedo é mais importante do que investir muito. Graças aos juros compostos, R$ 200/mês durante 30 anos gera muito mais patrimônio do que R$ 1.000/mês durante 5 anos.

---

### 📚 Glossário de Conceitos

| Termo | Definição Simples |
|-------|-------------------|
| **SELIC** | Taxa básica de juros da economia brasileira, definida pelo Banco Central |
| **CDI** | Certificado de Depósito Interbancário — referência de rentabilidade para renda fixa |
| **IPCA** | Índice de inflação oficial do Brasil |
| **Tesouro Direto** | Plataforma do governo para compra de títulos públicos |
| **CDB** | Título emitido por bancos para captação de recursos |
| **FGC** | Fundo Garantidor de Créditos — garante até R$ 250 mil por CPF por banco |
| **Liquidez** | Facilidade de converter um investimento em dinheiro |
| **Rentabilidade** | Ganho gerado por um investimento em determinado período |
| **Diversificação** | Estratégia de distribuir investimentos em diferentes ativos |
| **IOF** | Imposto sobre Operações Financeiras, cobrado em resgates antecipados |

---

### 🔁 Prompts Reutilizáveis para Revisão Futura

Use estes prompts no NotebookLM (com as mesmas fontes) para revisões futuras:

1. `"Resuma em 5 pontos os principais ensinamentos sobre orçamento pessoal das fontes."`
2. `"Quais são os erros mais comuns de finanças pessoais mencionados nas fontes e como evitá-los?"`
3. `"Crie 10 questões de múltipla escolha sobre investimentos para iniciantes baseadas nas fontes."`
4. `"Explique a diferença entre renda fixa e renda variável com exemplos das fontes."`
5. `"Com base nas fontes, qual seria um plano de 12 meses para sair do zero financeiro?"`
6. `"Quais estratégias as fontes recomendam para pessoas com renda irregular ou autônomos?"`

---

## ✅ Como foi feita a Entrega

1. Repositório criado no GitHub com nome descritivo
2. README.md estruturado com todos os itens solicitados
3. Link do repositório submetido na plataforma DIO
4. Projeto adicionado ao portfólio público

---

*Projeto desenvolvido como parte da trilha **CI&T — Do Prompt ao Agente** na plataforma [DIO](https://web.dio.me)*
