# Projeto: Streamlit 2025 – Gestão Financeira Pessoal

Este aplicativo em Python usa a biblioteca **Streamlit** para criar uma interface interativa de controle financeiro pessoal.

## Funcionalidades

- Upload de planilhas de despesas/receitas
- Cálculo automático de saldo, média de gastos, gráficos mensais
- Visualização dinâmica com filtros por categoria e período

## Tecnologias
- Python
- Streamlit
- Pandas / Matplotlib

## Exemplo de uso

```python
df["saldo"] = df["receita"] - df["despesa"]
st.line_chart(df["saldo"])
```