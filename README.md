# CalculadoraRapida

Este projeto consiste em uma **calculadora web simples e eficiente**, desenvolvida em **HTML** e estilizada com **Tailwind CSS (Dark Mode)**, projetada especialmente para **empreendedores que trabalham com caixas surpresa (loot boxes)** ou **kits de produtos de valor variável a um preço fixo**.

---

## 📌 Descrição do Projeto

O objetivo principal é **determinar um preço de venda médio** que garanta:

✔ A cobertura de todos os custos do inventário  
✔ A obtenção de uma **margem de lucro predefinida**

---

## ⚙️ Como Funciona

A calculadora utiliza o conceito de **Custo Médio**, distribuindo o custo total do estoque entre todas as caixas, já que neste modelo não é possível precificar cada caixa individualmente.

### 📐 Fórmulas Aplicadas

- **Custo Médio por Caixa (Break-even):**  
  `Custo Total do Inventário ÷ Número Total de Caixas`

- **Preço de Venda Sugerido:**  
  `Custo Médio por Caixa + Margem de Lucro (%)`

---

## 🧾 Entradas Necessárias

A ferramenta precisa de apenas **três campos** para realizar os cálculos:

| Campo | Descrição |
|-------|-----------|
| **Custo Total de Todos os Produtos (R$)** | Soma do valor de compra de todo o estoque (incluindo embalagem, frete, etc.) |
| **Número Total de Caixas a Vender** | Quantidade total de caixas que serão montadas |
| **Margem de Lucro Desejada (%)** | Percentual de lucro aplicado sobre o custo médio |

---

## 📊 Resultados Gerados

A aplicação exibe automaticamente os seguintes valores:

- **Custo Médio por Caixa:** valor mínimo para cobrir os custos (ponto de equilíbrio)  
- **Preço de Venda Sugerido:** valor de venda com a margem de lucro aplicada  
- **Lucro Total Estimado:** lucro bruto caso todas as caixas sejam vendidas  
- **Valor Total Estimado de Ven**
