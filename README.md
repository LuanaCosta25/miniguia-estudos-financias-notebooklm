# Miniguia de Estudos: Estratégias para a Construção da Reserva de Emergência

Projeto prático desenvolvido para a plataforma [DIO](https://dio.me) com o objetivo de demonstrar o uso da Inteligência Artificial como uma ferramenta de aprendizagem ativa. Este repositório funciona como um "Segundo Cérebro" focado em soberania e segurança financeira.

---

## 1. Contexto e Objetivos
* **Assunto Escolhido:** Organização Financeira e Reserva de Emergência.
* **Objetivo de Estudo:** Criar um guia metodológico e estruturado utilizando o **NotebookLM** para entender a importância, o cálculo técnico e os melhores veículos de investimento para proteger o patrimônio contra imprevistos.

---

## 2. Curadoria de Fontes
Para alimentar o NotebookLM com informações de alta credibilidade e formar nossa base de conhecimento, foram utilizadas as seguintes fontes abertas:
* [Santander Blog - Como fazer uma reserva de emergência](https://www.santander.com.br/blog/como-fazer-uma-reserva-de-emergencia)
* [XP Conteúdos - Relatório de Reserva de Emergência](https://conteudos.xpi.com.br/aprenda-a-investir/relatorios/reserva-de-emergencia/)
* [Riconnect - Como construir e onde investir a reserva](https://riconnect.rico.com.vc/analises/reserva-de-emergencia-como-construir-e-onde-investir/)
* [Riconnect Blog - Reserva de Emergência](https://riconnect.rico.com.vc/blog/reserva-de-emergencia/)
* [Blog do BB - Reserva de Emergência e Renda Variável](https://blog.bb.com.br/reserva-emergencia-renda-variavel/)

---

## 3. Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Durante a interação com o NotebookLM, foram validados os seguintes prompts para extração do conhecimento:

### ❓ Perguntas Diretas Testadas:
1. *O que é reserva de emergência?*
2. *Qual a porcentagem adequada deve ser destinada para a formação de uma reserva de emergência?*
3. *Qual o valor exato para a formação da reserva de emergência?*
4. *Eu só posso aplicar meu dinheiro em outros tipos de investimentos após a criação da reserva de emergência?*
5. *A reserva de emergência deve ser sempre alimentada?*
6. *Qual o melhor banco para criar a reserva de emergência?*

### 💡 Aprendizados de Engenharia de Prompt (Troubleshooting)
* **Contexto Localizado:** Ao perguntar sobre "o melhor banco", a IA tende a ser neutra ou genérica. O aprendizado foi refinar a pergunta focando nos **atributos do produto** (como liquidez diária e garantia do FGC) em vez de focar na marca do banco.
* **Cálculo Baseado em Despesas:** A IA ajudou a corrigir um erro comum de conceito: a reserva não deve ser calculada sobre o salário/renda total, mas sim baseada estritamente no custo de vida (despesas mensais).

---

## 4. Miniguia de Estudo (Entrega Final)

###  Resumo Estruturado do Assunto

#### 1. Fundamentos e Importância Estratégica
A reserva de emergência transcende a mera acumulação de capital; ela é um instrumento de soberania financeira e um pilar de sustentação para a saúde mental. Sua aplicação visa mitigar os impactos de cinco categorias principais: **Interrupção de renda**, **Emergências de saúde**, **Danos patrimoniais**, **Sinistros de mobilidade** e **Crises sistêmicas**. Sem ela, o indivíduo recorre a dívidas caras (como cartão rotativo ou cheque especial); com ela, financia-se a própria crise a "juro zero".

#### 2. Metodologia de Cálculo e Personalização
O alvo deve refletir o tempo necessário para a reestruturação financeira de acordo com o perfil profissional:
* **CLT com alta estabilidade:** 3 a 6 meses de despesas (Média liquidez devido ao FGTS).
* **Autônomo / Profissional Liberal:** 6 a 12 meses de despesas (Máxima liquidez pela volatilidade de renda).
* **Áreas de nicho (baixa demanda):** 9 a 12 meses de despesas.

#### 3. Veículos de Investimento Recomendados
A reserva exige o sacrifício do retorno em favor da **segurança** e **disponibilidade**:
* **Tesouro Selic:** Risco mais baixo do mercado, garantia soberana do Tesouro Nacional.
* **CDB com Liquidez Diária:** Rentabilidade atrelada ao CDI e proteção do FGC até R$ 250 mil.
* **Fundos DI:** Acompanham o CDI, mas não possuem FGC e sofrem com a antecipação de imposto (Come-cotas).
* *Nota Técnica:* O uso de Renda Variável (Ações) é tecnicamente contraindicado para este fim devido à volatilidade.

---

### Glossário de Conceitos-Chave
* **Liquidez Diária:** Capacidade de transformar o ativo em dinheiro no mesmo dia ou no dia útil seguinte (D+0 ou D+1).
* **Taxa Selic / CDI:** Referenciais de juros da economia brasileira. O CDI costuma flutuar levemente abaixo da taxa Selic.
* **FGC (Fundo Garantidor de Créditos):** Mecanismo de proteção que garante depósitos bancários até o limite de R$ 250 mil por CPF/instituição em caso de falência do banco.
* **Come-cotas:** Antecipação tributária que ocorre em fundos de investimento nos meses de maio e novembro, reduzindo a eficiência em relação a títulos diretos.
* **Rating (Pontuação de Risco):** Avaliação feita por agências sobre a saúde financeira do emissor do título. Crucial para avaliar Fundos DI.
* **Tabela Regressiva de IR:** Alíquotas de Imposto de Renda que diminuem conforme o tempo de aplicação (22,5% até 180 dias; indo até 15% após 720 dias).

---

### Toolkit de Revisão: Prompts Reutilizáveis
Copie e utilize estes prompts em modelos de linguagem para recalibrar sua estratégia sempre que seu cenário de vida mudar:

1. **Prompt de Diagnóstico:**
   > *"Com base nas diretrizes de planejamento financeiro, ajude-me a calcular minha reserva. Meu perfil profissional é [CLT/Autônomo], meus gastos mensais fixos somam R$ [Valor] e atuo em uma área de [Alta/Baixa] demanda. Qual deve ser minha meta total e o tempo de cobertura ideal?"*

2. **Prompt de Comparação de Produtos:**
   > *"Meu banco ofereceu um [Nome do Produto] com [Valor]% do CDI e carência de [Prazo]. Compare este produto com o Tesouro Selic e um CDB de liquidez diária clássico em termos de risco (FGC/Rating), liquidez e tributação para fins de reserva de emergência."*

3. **Prompt de Engajamento Familiar:**
   > *"Minha meta de reserva é R$ [Valor] e posso poupar R$ [Valor] por mês. Crie um cronograma de acúmulo e sugira uma abordagem pedagógica para envolver minha família na redução de despesas sem gerar atritos."*

---

## Tecnologias Utilizadas
* [NotebookLM (Google)](https://notebooklm.google) - Ferramenta de IA para curadoria e análise de fontes.
* [GitHub](https://github.com) - Hospedagem de código, documentação e portfólio profissional.
