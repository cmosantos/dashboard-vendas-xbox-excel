# Dashboard de Vendas do Xbox com Excel (Layout Alternativo)

Este projeto entrega um **dashboard de vendas/receita** para assinaturas do **Xbox Game Pass**, transformando dados brutos em indicadores e gráficos para apoiar análise e tomada de decisão.

## 📦 Arquivos do projeto

- `data/base.xlsx` → base de dados original do desafio (fonte).
- `dashboard/dashboard_xbox_diferente.xlsx` → dashboard concluído (proposta **diferente** do modelo de referência).

## 🧾 Dados utilizados

A planilha de base contém, por assinante:

- Plano (Core / Standard / Ultimate)
- Data de início
- Renovação automática (Yes/No)
- Tipo de assinatura (Monthly / Quarterly / Annual)
- Preços da assinatura e add-ons (EA Play / Minecraft)
- Valor de cupom e valor total

### Regra de cálculo usada (métrica principal)
No dashboard, a **Receita líquida (Net)** é calculada como:

**Net = (Subscription Price + EA Price + Minecraft Price) – Coupon Value**

> Essa regra bate com a coluna **Total Value** da base.

## ✅ O que foi feito

- Organização dos dados em uma aba **Dados** (com colunas derivadas como Mês, Gross e Net)
- Aba **Resumo** para alimentar o painel
- Aba **Dashboard** com um **layout alternativo**, contendo:
  - KPIs (Receita líquida, Assinantes, ARPU, Renovação automática, Cupons, Aderência Minecraft)
  - Gráfico de linha (tendência mensal)
  - Gráfico de rosca (mix de receita por plano)
  - Gráfico de colunas (receita por tipo de assinatura)
  - Gráfico de rosca (participação de renovação automática)

## ▶️ Como reproduzir

1. Baixe/clonar o repositório
2. Abra `data/base.xlsx` para visualizar a base
3. Abra `dashboard/dashboard_xbox_diferente.xlsx`
4. (Opcional) Substitua a aba **Dados** pelos dados mais recentes e o dashboard será atualizado.

## 📌 Observações

- Este dashboard foi feito para ficar **diferente do arquivo de referência** do curso, mantendo a mesma base e a mesma lógica de negócio.
=======
# dashboard-vendas-xbox-excel

