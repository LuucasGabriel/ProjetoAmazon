# 🛒 Dashboard Amazon - Análise de Dados

Este repositório contém um **Dashboard interativo em Power BI**, desenvolvido a partir de dados de classificação de produtos da **Amazon**, disponíveis no [Kaggle](https://www.kaggle.com/). O objetivo principal foi praticar **DAX**, tratamento de dados e técnicas de **Business Intelligence**.

---

## 🎯 Objetivo

- Analisar preços e descontos praticados nos produtos.
- Identificar o produto com maior desconto e o produto mais barato.
- Avaliar a reputação dos produtos por meio das avaliações dos usuários.
- Praticar modelagem de dados, filtros e criação de medidas no Power BI.

---

## 📸 Dashboard

Abaixo, um exemplo do dashboard desenvolvido:

![Dashboard Amazon](./img/dashboard-amazon.png)

> 💡 **Dica:** Suba um print do seu `.pbix` na pasta `img` e atualize o caminho acima.

---

## ⚙️ Principais Medidas Criadas

As principais medidas DAX criadas foram:

- **Preço Total e Descontos (SUM)**: Soma dos preços e descontos.
- **Quantidade de Usuários (COUNT)**: Total de IDs únicos.
- **Quantidade de Produtos (COUNTX)**: Contagem de produtos.
- **Delta de Desconto**: Diferença entre o preço original e o com desconto.
- **Maior Desconto (MAX)**: Maior percentual de desconto registrado.
- **Produto Mais Barato**: Nome do produto com o menor preço com desconto.
- **Percentual de Desconto Aplicado**: Percentual de desconto por produto.
- **Produto com Maior Desconto**: Nome do produto com maior desconto percentual.
- **Ranking de Usuários**: Ranking de usuários com base na quantidade de reviews.
- **Média de Avaliação (Rating)**: Média ajustada das avaliações.
- **Reviews Negativos e Positivos**: Total de reviews bons ou ruins com base no título.
- **Percentual de Reviews Positivos**: Relação de reviews bons sobre o total.
- **Total de Ratings e Reviews**: Soma geral de avaliações e reviews classificados.

---

## 🚀 Como Abrir o Projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
