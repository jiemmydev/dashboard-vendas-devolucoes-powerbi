# 📦 Sales & Returns Performance Analytics | Power BI


## 📌 Sobre o Projeto

Dashboard executivo no **Power BI** para análise consolidada de vendas e devoluções (2020–2022). 

Contempla integração de bases históricas, modelagem relacional *Star Schema* e métricas em DAX para monitorar faturamento, volume de pedidos, top SKUs e causas-raiz de devoluções por região.

---

## 🎯 Principais Indicadores (KPIs)

- **Quantidade Vendida:** 43 Mil unidades
- **Total de Pedidos:** 25,1 Mil pedidos
- **Total de Clientes:** 17,4 Mil clientes
- **Quantidade Devolvida:** 2 Mil unidades
- **Taxa de Devolução:** 4,22%

---

## 📊 Visualizações & Análises

1. **Evolução Temporal:** Acompanhamento mensal da quantidade sold de 2020 a 2022.
2. **Distribuição Geográfica:** Mapeamento de vendas por continente (América do Norte, Ásia, Europa e Oceania).
3. **Top 5 SKUs:** Ranking dos produtos com maior volume de vendas (`HL164`, `HL167`, etc.).
4. **Causa-Raiz de Devoluções:** Mapeamento dos principais motivos de devolução para suporte à tomada de decisão operacional.

---

## 🛠️ Modelagem de Dados

Estruturação relacional em **Star Schema**:
- **Tabelas Fato:** `Base Vendas (2020-2022)` e `Base Devoluções`.
- **Tabelas Dimensão:** `Cadastro Clientes`, `Cadastro Produtos`, `Cadastro Lojas`, `Cadastro Localidades` e `dCalendario`.

---

## 📂 Estrutura do Repositório

```text
├── Material Postagem/              # Recursos de mídia/imagens
├── Base Devoluções.xlsx            # Histórico de devoluções
├── Base Vendas 2020-2021-2022.xlsx # Base de vendas consolidada
├── Cadastro Clientes.xlsx          # Dimensão Clientes
├── Cadastro Localidades.xlsx       # Dimensão Localidades
├── Cadastro Lojas.xlsx             # Dimensão Lojas
├── Cadastro Produtos.xlsx          # Dimensão Produtos
├── Dashboard Vendas.pbix           # Relatório do Power BI
└── README.md                       # Documentação do projeto
