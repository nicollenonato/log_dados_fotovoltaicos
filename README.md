# 📊 Análise de Desempenho Fotovoltaico

Este repositório contém um conjunto de dados e um script para análise do desempenho de sistemas fotovoltaicos.

## 📂 Estrutura do Repositório
- `data/log_dados_fotovoltaicos.csv` → Arquivo de log de dados de desempenho fotovoltaico.
- `script_analise.py` → Script Python para processar os dados e gerar métricas.

## 🚀 Como Usar os Dados

### 🔹 Baixar os Dados
Os dados estão disponíveis no seguinte link:
🔗 [Baixar `log_dados_fotovoltaicos.csv`](https://github.com/seu-usuario/analise_fotovoltaica/blob/main/data/log_dados_fotovoltaicos.csv)

### 🔹 Exemplo de Código para Carregar os Dados
```python
import pandas as pd

# Carregar os dados
df = pd.read_csv('data/log_dados_fotovoltaicos.csv')

# Exibir as primeiras linhas
print(df.head())
