# 💰 Dashboard de Controle de Pagamentos – Power BI

Este projeto apresenta a construção de um painel interativo no Power BI para controle de faturas e recebimentos. O objetivo é monitorar o faturamento, pagamentos realizados e inadimplência de clientes, oferecendo uma visão clara e estratégica para tomada de decisões financeiras.

---

## 🎯 Objetivos

* Monitorar o total faturado e recebido ao longo do tempo
* Identificar clientes inadimplentes e valores em aberto
* Avaliar a evolução de pagamentos mensalmente
* Permitir filtros dinâmicos para facilitar a análise por cliente, status e período

---

## 🛠️ Tecnologias Utilizadas

* Power BI Desktop
* Linguagem DAX para medidas e KPIs
* Power Query para tratamento de dados
* PostgreSQL (armazenamento de dados)
* Visualizações interativas (colunas, linhas, pizza, tabelas e filtros)

---

## 🖼️ Layout do Painel

🔹 Página 1 – Visão Geral

* KPIs principais: Total Faturado, Total Recebido, % Inadimplência
* Gráfico de linha: Evolução dos recebimentos
* Gráfico de pizza: Distribuição das faturas por status
* Top 5 clientes com maior valor em aberto
* Botão de reset de filtros

🔹 Página 2 – Análise Detalhada

* Filtros por cliente, status e período
* Tabela com faturas: data, valor, valor pago, status
* Gráficos auxiliares para análise individual

🔹 Página 3 – Comparativo Mensal

* Tabela com colunas:

  * Mês
  * Total Faturado
  * Total Pago
  * Inadimplência
  * Diferença (medida DAX)
* Gráfico de colunas comparando faturamento e pagamentos mês a mês

---

## 🗂️ Dataset

A base de dados foi gerada artificialmente com apoio do ChatGPT, simulando registros realistas de faturas e pagamentos.
Posteriormente, os dados foram inseridos em um banco de dados PostgreSQL e conectados ao Power BI via conexão direta.


---

## 👤 Autor

Guilherme Paes – https://www.linkedin.com/in/paesgui


