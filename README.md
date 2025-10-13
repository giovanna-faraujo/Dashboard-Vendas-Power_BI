# Dashboard de Performance de Vendas e Varejo

## Visão Geral

Este projeto é um Dashboard de Business Intelligence (BI) focado em **Vendas no Varejo**, desenvolvido para monitorar a performance de lojas e produtos. O objetivo é capacitar a gestão com uma visão holística da receita, permitindo a identificação de áreas geográficas de alto desempenho e a avaliação da eficiência gerencial.

---

## Destaques para Recrutadores

### O que foi avaliado e modelado?

O projeto exigiu a integração de múltiplas fontes de dados (pedidos, cadastro de lojas e calendário) em um modelo relacional (Star Schema) robusto, focado em três pilares:

1.  **Performance Financeira:** Faturamento total e Valor Médio da Venda.
2.  **Performance Operacional (Lojas/Geografia):** Distribuição da receita por `Cidade`, `Estado` e o impacto individual de cada `Gerente` na receita total.
3.  **Performance de Produto:** Vendas por `Produto`, identificando os *Top Sellers*.

### Problema de Negócio Identificado

A principal análise resolve o problema de **distribuição desigual de resultados e gestão de performance**.

O dashboard permite identificar de forma clara quais **Gerentes** e **Lojas** estão abaixo ou acima da média de desempenho. A capacidade de mapear a performance por **Latitude/Longitude** oferece *insights* estratégicos sobre a saturação de mercado e o potencial de expansão/otimização em diferentes regiões geográficas.

### Métricas (KPIs) Importantes

| Métrica | Relevância |
| :--- | :--- |
| **Valor Total de Vendas** (`valor_venda`) | Métrica financeira primária para medir o sucesso comercial. |
| **Vendas por Gerente/Loja** | Essencial para avaliar a eficiência gerencial e direcionar bônus e treinamentos. |
| **Vendas por Produto** | Identificação rápida do mix de produtos que geram mais receita e do giro de estoque. |
| **Distribuição Geográfica da Receita** | Suporta decisões estratégicas sobre logística, marketing e expansão de pontos de venda. |

---

## Detalhes Técnicos

* **Ferramenta:** Power BI (`Aula 3.pbix`)
* **Bases de Dados:** CSV/Excel (Pedidos, Lojas e Calendário)
* **Técnicas:** Modelagem de Dados Relacional, criação de Tabela Calendário e uso de DAX para cálculo de KPIs.

---

### Nota de Autoria

Material desenvolvido durante o **Curso de Power BI e Data Analytics da Empowerdata** com o objetivo exclusivo de demonstrar minhas habilidades e competências técnicas em meu portfólio.
