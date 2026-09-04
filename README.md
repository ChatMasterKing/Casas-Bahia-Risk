# 📊 Casas Bahia: Retail Risk Management and Financial Recovery Analysis

> **Desafio de Projeto DIO:** Aprendizagem Ativa e Organização do Conhecimento com NotebookLM  
> **Autor:** Marcelo Ferreira de Sousa  
> **Tema:** Gestão de Riscos corporativos, Crédito, Liquidez e Governança no Varejo Brasileiro  
> **Ferramentas Utilizadas:** NotebookLM, GitHub, Markdown  

---

## 🎯 1. Contexto e Objetivos

### Contexto
A transformação de grandes varejistas brasileiras em *fintechs* alterou profundamente a exposição dessas companhias ao risco de crédito e de liquidez. A expansão comercial sem o devido acompanhamento de estruturas rigorosas de governança e controles internos gerou descasamentos entre o ciclo financeiro e o custo da dívida em cenários de juros altos, levando companhias tradicionais à insuficiência de capital de giro e à necessidade de reestruturação.

### Objetivos de Estudo
- **Analisar a transição das varejistas para o setor de serviços financeiros** e os impactos na exposição a riscos de crédito e liquidez.
- **Comparar modelos de mitigação de risco operacional**, tomando como referência o modelo de *Joint Venture* (Luizacred - Magalu/Itaú) frente à assunção de risco integral no balanço (Casas Bahia).
- **Substituir métricas de vaidade por Key Risk Indicators (KRIs) preditivos** para estruturar sistemas de alerta precoce e garantir a continuidade operacional.
- **Utilizar o NotebookLM como ferramenta de aprendizagem ativa**, aplicando engenharia de prompts para síntese e extração de inteligência de negócios.

---

## 🔍 2. Curadoria de Fontes

O caderno no **NotebookLM** foi alimentado com 3 fontes analíticas focadas no setor de varejo e mercado financeiro corporativo:

1. **Análise de Transformação do Varejo em Fintechs e Exposição a Risco**
   - *Escopo:* Avaliação dos impactos da concessão de crédito próprio no balanço corporativo e requisitos de controles internos.
2. **Estudo Comparativo de Casos: Casas Bahia, Americanas e Magazine Luiza**
   - *Escopo:* Análise de descasamento de ciclo financeiro, estruturas de endividamento (CDI vs. margem) e alocação de provisão para perdas de crédito.
3. **Framework de Indicadores Chave de Risco (KRIs) e Sistemas de Alerta Precoce**
   - *Escopo:* Substituição de métricas puramente comerciais por KRIs preditivos para monitoramento da saúde financeira e solvência.

---

## 🧪 3. Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Documentação das perguntas estratégicas testadas no NotebookLM para extração do conhecimento técnico e análise comparativa de governança:

### 📌 Teste 1: Correlação entre Casos e Prevenção de Colapso
* **Prompt Aplicado:**  
  > *"Quais são as ligações dos casos enviados e como garantir que isso não ocorra em uma grande empresa, como ocorreu na Casas Bahia?"*
* **Desafio de Extração:** Evitar respostas genéricas e focar nos mecanismos concretos de governança, exigindo que a IA correlacionasse o custo do capital com a estrutura de capital de giro.
* **Resultado Obtido:** Mapeamento da necessidade de alinhar o crescimento da carteira de crédito a limites de tolerância a risco (Risk Appetite Statement) e implementação de KRIs operacionais.

---

### 📌 Teste 2: Modelo de Mitigação via Joint Venture (Magalu / Luizacred)
* **Prompt Aplicado:**  
  > *"Como funciona o modelo de joint venture do Magalu?"*
* **Resultado Obtido:** A IA identificou a estrutura de compartilhamento 50/50 com o Itaú Unibanco, demonstrando como o modelo descentraliza o risco de crédito do balanço da holding varejista e garante funding bancário a taxas competitivas.

---

### 📌 Teste 3: Controle e Mitigação do Risco Operacional
* **Prompt Aplicado:**  
  > *"Como o Magalu controla seu risco operacional?"*
* **Resultado Obtido:** Aprofundamento na governança compartilhada: a parceria estratégica não apenas divide a exposição a perdas de crédito, mas traz a expertise de *underwriting* e modelagem de risco do parceiro bancário, funcionando como um blindagem para a liquidez corporativa.

---

## 📖 4. Miniguia de Estudo (Entrega Final)

### 4.1 Resumo Estruturado do Assunto

#### A. O Dilema Varejo vs. Fintech e Risco de Crédito
A migração de grandes varejistas para o ecossistema de serviços financeiros promete aumento de margem, mas insere riscos bancários típicos no balanço corporativo. Quando a concessão de crediário/crédito ocorre sem respaldo de um parceiro bancário ou sem provisões adequadas, o aumento da taxa de juros (Selic/CDI) eleva a inadimplência e o custo do financiamento do capital de giro, comprimindo a liquidez.

#### B. Modelos de Estruturação: Assunção Direta vs. Joint Venture
- **Assunção Direta (Ex: Casas Bahia):** O risco de crédito recai totalmente sobre a estrutura de caixa do varejista. Em cenários macroeconômicos adversos, a necessidade de elevar a PDD (Provisão para Devedores Duvidosos) drena o caixa operacional.
- **Modelo de Joint Venture (Ex: Magalu / Luizacred):** Parceria 50/50 com uma instituição financeira de grande porte (Itaú). Divide o risco de inadimplência, aproveita a régua de crédito e sistemas de risco do banco e assegura custo de captação (*funding*) mais barato.

#### C. KRIs (Key Risk Indicators) vs. Métricas de Vaidade
Para evitar crises de liquidez, a gestão deve migrar do acompanhamento exclusivo de **métricas de vaidade** (GMV, volume de vendas, faturamento bruto) para **KRIs preditivos**:
1. *Índice de Cobertura do Crediário / PDD sobre Carteira Bruta.*
2. *Prazo Médio de Recebimento vs. Prazo Médio de Pagamento (Descasamento do Ciclo Financeiro).*
3. *Custo Médio da Dívida atrelado ao CDI vs. Margem Operacional EBTIDA.*

---

### 4.2 Glossário de Conceitos Aprendidos

| Conceito | Definição Prática |
| :--- | :--- |
| **Joint Venture (JV)** | Associação estratégica entre duas empresas para explorar uma atividade econômica, partilhando riscos, custos e lucros (ex: Luizacred). |
| **KRI (Key Risk Indicator)** | Indicador-chave utilizado para sinalizar alterações no perfil de risco de uma organização antes que o evento adverso se concretize. |
| **Descasamento de Prazos (Asset-Liability Mismatch)** | Desequilíbrio entre o prazo de vencimento dos ativos (recebíveis do crediário) e dos passivos (dívidas corporativas e fornecedores). |
| **Funding Bancário** | Acesso a recursos financeiros e captação de capital para sustentação da oferta de crédito a custos competitivos. |
| **PDD (Provisão para Devedores Duvidosos)** | Reserva contábil destinada a cobrir eventuais perdas decorrentes do não pagamento de débitos por clientes. |

---

### 4.3 Kit de Prompts Reutilizáveis para Análise de Riscos Corporativos

1. **Análise Comparativa de Estrutura de Capital:**
   > `"Com base nos documentos, elabore uma matriz comparativa destacando as vantagens e desvantagens operacionais entre ter uma financeira própria vs. atuar via Joint Venture bancária."`

2. **Mapeamento de KRIs e Governança:**
   > `"Extraia das fontes uma lista de 5 KRIs (Key Risk Indicators) financeiros e operacionais cruciais para monitorar a saúde de uma varejista em cenário de juros altos."`

3. **Simulador de Turnaround e Recuperação:**
   > `"Atue como um Especialista em Reestruturação Financeira. Liste 3 medidas imediatas de governança e renegociação de dívidas recomendadas para recompor o caixa de uma grande empresa em crise de liquidez."`

---

## 🚀 5. Entrega DIO

- **Repositório GitHub:** [ChatMasterKing/Management](https://github.com/ChatMasterKing/Management)
- **Status:** Desafio concluído com foco em Governança, Compliance e Gestão de Riscos no Varejo.
