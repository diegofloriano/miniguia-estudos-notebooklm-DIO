# 🧠 Meu Segundo Cérebro: Metodologia de Investimentos de Benjamin Graham

Este repositório foi criado para o Desafio de Projeto "Treinando uma IA de Aprendizagem" no Bootcamp Bradesco da DIO. A ideia aqui foi usar o NotebookLM como um assistente de estudos para centralizar, cruzar e fixar os conceitos de Value Investing (Investimento de Valor) criados por Benjamin Graham.

## 🎯 Contexto e Objetivos de Estudo
O objetivo principal deste caderno temático é entender como filtrar ações de forma segura, focando em empresas reais e sólidas, e não em especulação ou momentos de euforia do mercado. 

Com este material, busquei responder a três perguntas principais:
1. O que diferencia um investidor de um especulador segundo Graham?
2. Como aplicar o conceito de "Margem de Segurança" na prática?
3. Como funciona a famosa fórmula de valuation de Graham para encontrar o valor justo de uma ação?

---

## 📚 Curadoria de Fontes
Para alimentar o NotebookLM, utilizei uma mistura de vídeos explicativos e artigos técnicos de referência:

### 🎥 Conteúdo em Vídeo (Análise Visual e Prática)
* **Passo a Passo Empreendedor:** O Mentor de Warren Buffett - A História de Benjamin Graham - https://www.youtube.com/watch?v=9fZ3H1yHb_E
* **José Kobori:** O Método mais Simples para Comprar Ações Baratas - Benjamin Graham - https://www.youtube.com/watch?v=ZxYEKaAeBew
* **MindSet:** O Investidor Inteligente Benjamin Graham Audiobook - https://www.youtube.com/watch?v=fMo_xntieUo
* **Investidor Sardinha:** 8 Lições que Eu Aprendi com o Benjamin Graham, O Investidor Inteligente! - https://www.youtube.com/watch?v=cWNqf1gifR8
* **Arata Academy:** O Investidor Inteligente, de Benjamin Graham | Resumo Arata Academy 30 - https://www.youtube.com/watch?v=qjCpA8n7M2A

### 📰 Conteúdo em Texto (Teoria e Fórmulas)
* **Investopedia:** Guia sobre o método de Benjamin Graham (https://www.investopedia.com/terms/b/benjamin-method.asp)
* **Investing.com Academy:** Destrinchando a fórmula de Benjamin Graham (https://br.investing.com/academy/analysis/formula-benjamin-graham/)

---

## 🛠️ Engenharia de Prompts e "Cicatrizes" (O que deu certo e errado)
Aqui está o registro de como tive que ajustar minhas conversas com o NotebookLM para sair do básico e conseguir respostas que realmente ajudam a estudar.

### ❌ Tentativa 1: O Prompt Superficial
* **O que perguntei:** *"Como o Benjamin Graham investia?"*
* **O que a IA respondeu:** Deu uma resposta genérica dizendo que ele comprava ações baratas e era professor do Warren Buffett. Não usou os dados dos links que enviei.
* **Minha "Cicatriz":** Percebi que perguntas abertas demais fazem a IA agir como o ChatGPT padrão, ignorando a base de dados que eu mesmo montei.

### 🎯 Tentativa 2: O Prompt Preciso (A Solução)
* **O que perguntei:** *"Com base estritamente nos artigos da Investopedia e Investing.com que forneci, explique as variáveis da fórmula de valor intrínseco de Graham e liste quais são os 3 critérios principais que ele usava para avaliar se uma empresa é segura."*
* **O que a IA respondeu:** Destrinchou a fórmula $V = \text{LPA} \times (8.5 + 2g)$, explicando o peso do crescimento esperado ($g$) e listou os critérios de segurança (dívida sob controle, liquidez e histórico de lucros) citando em qual das fontes encontrou a informação.
* **Aprendizado:** Para o NotebookLM funcionar bem como um segundo cérebro, preciso amarrar a resposta dele às fontes enviadas e pedir a estrutura exata que eu quero.

---

## 📖 Miniguia de Estudo (Resultado Consolidado)

### 📌 Resumos Estruturados dos Conceitos-Chave

1. **O Investidor Inteligente vs. Especulador:** O investidor enxerga a ação como uma parte de um negócio real e busca segurança mais um retorno adequado. O especulador tenta adivinhar o movimento dos preços no curto prazo com base em boatos ou gráficos.
2. **O Sr. Mercado (Mr. Market):** Uma metáfora criada por Graham. O mercado é como um sócio meio maluco que todo dia te oferece um preço para comprar a sua parte ou te vender a dele. Às vezes ele está eufórico e pede muito caro; às vezes está deprimido e vende muito barato. O investidor inteligente aproveita a depressão dele para comprar e a euforia para vender ou ignorar.
3. **Margem de Segurança:** Comprar uma ação por um valor consideravelmente menor do que ela realmente vale (seu valor intrínseco). Se você calcula que uma empresa vale R$ 50,00 e a compra por R$ 30,00, você tem uma margem de segurança de R$ 20,00 para o caso de o seu cálculo ou o mercado errarem.

### 🗂️ Glossário do Investimento de Valor
* **Valor Intrínseco:** O valor real e justo de uma empresa com base nos seus fundamentos (lucro, patrimônio, crescimento), independente do preço atual na bolsa.
* **LPA (Lucro Por Ação):** Indicador que mostra a parcela do lucro líquido correspondente a cada ação da empresa.
* **P/L (Preço sobre Lucro):** Indicador que mostra quantos anos levaria para reaver o dinheiro investido na empresa através dos lucros atuais.

### 🔄 Prompts Reutilizáveis para Revisão rápida
Copie e cole estes comandos no NotebookLM para revisar a matéria antes de testar na prática:
* *Para simular o método:* "Escreva um resumo de 2 parágrafos explicando como Benjamin Graham reagiria a uma queda de 30% na bolsa de valores em uma semana, usando a lógica do Sr. Mercado."
* *Para aplicar a filtros:* "Quais são os limites máximos aceitáveis de P/L (Preço/Lucro) e P/VP (Preço/Valor Patrimonial) que Graham defendia para evitar comprar ações caras?"
