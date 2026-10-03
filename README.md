# 📊 Desafio Power BI — Atualização de Relatório Financeiro

Este repositório contém a entrega do desafio prático de construção e estilização de um relatório financeiro de duas páginas no Power BI, utilizando a base de dados `financials`.

## 📌 Visão Geral do Relatório

O projeto foi desenvolvido focando em boas práticas de UX/UI, mantendo a consistência visual, hierarquia clara de informações e facilidade de leitura dos dados.

### 🖼️ Páginas do Dashboard

#### 1. Página 1 — Detalhes de Vendas
- **Visual:** Layout escuro (*Dark Mode*).
- **Conteúdo:** Análise de vendas por semestre, matriz detalhada de dados e distribuição visual de vendas por produto e país.
- **Recursos:** Filtro de ano e navegação interativa.

![Página 1](pagina1.png)

---

#### 2. Página 2 — TOP N & Outliers
- **Visual:** Layout claro (*Light Mode*).
- **Conteúdo:** 
  - Gráfico de colunas por país e produto.
  - Gráfico de dispersão (*Scatter Chart*) para identificar relação e *outliers* entre Vendas, Unidades Vendidas e Lucro por Mês/Produto.
  - Gráfico de barras horizontais com filtro aplicado de **TOP 3 Produtos** (N Superior por Vendas).

![Página 2](pagina2.png)

---

## 🛠️ Tecnologias e Ferramentas
- **Power BI Desktop**
- **DAX / Linguagem M**
- **Git & GitHub**

---

## 📂 Ficheiros Incluídos
- `Relatorio_Financeiro.pbix`: Ficheiro editável do Power BI.
- `Relatorio_Financeiro.pdf`: Exportação do relatório em PDF.
- `pagina1.png` e `pagina2.png`: Capturas de ecrã para demonstração no README.
