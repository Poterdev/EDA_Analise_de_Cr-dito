# 📊 Análise de Inadimplência em Cartões de Crédito

![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-1.0+-green.svg)
![Seaborn](https://img.shields.io/badge/Seaborn-0.11+-red.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.0+-yellow.svg)

## 📌 Sobre o Projeto

Este projeto realiza uma análise exploratória detalhada de dados de cartão de crédito, focando na identificação de padrões de comportamento e fatores de risco para inadimplência. O estudo abrange seis meses de dados de transações, incluindo informações demográficas e histórico de pagamentos dos clientes.

## 🎯 Objetivos

- Analisar padrões de comportamento de pagamento
- Identificar fatores de risco para inadimplência
- Avaliar a relação entre limite de crédito e comportamento do cliente
- Desenvolver insights para gestão de risco de crédito

## 📂 Estrutura do Projeto

```
📁 credit-card-analysis/
│
├── 📁 data/
│   └── credit_card_clean_3.csv
│
├── 📁 notebooks/
│   └── EDA_Analise_de_cartao.ipynb
│
├── 📁 images/
│   ├── boxplot_analysis.png
│   ├── correlation_matrix.png
│   └── violin_plots.png
│
└── 📄 README.md
```

## 🛠️ Requisitos

Para executar este projeto, você precisará das seguintes bibliotecas Python:

```python
pandas==1.3.0
numpy==1.21.0
seaborn==0.11.1
matplotlib==3.4.2
```


## 📊 Conjunto de Dados

O dataset contém as seguintes variáveis principais:

### Variáveis Numéricas:
- `LIMIT_BAL`: Limite de crédito
- `AGE`: Idade do cliente
- `PAY_AMT1`-`PAY_AMT6`: Valores pagos mensalmente
- `BILL_AMT1`-`BILL_AMT6`: Valores das faturas mensais

### Variáveis Categóricas:
- `SEX`: Gênero do cliente
- `EDUCATION`: Nível educacional
- `MARRIAGE`: Estado civil
- `PAY_1`-`PAY_6`: Status de pagamento mensal
- `default payment next month`: Indicador de inadimplência

## 🔍 Principais Descobertas

1. **Segmentação de Clientes**:
   - Nível básico: Até 200.000
   - Nível intermediário: 200.000 a 550.000
   - Nível premium: 550.000 a 800.000

2. **Padrões de Risco**:
   - Maior concentração de atrasos em limites até 300.000
   - Tendência de aumento nos atrasos ao longo do período
   - Relação não linear entre pagamentos em dia e risco futuro

3. **Comportamento de Gastos**:
   - Gastos frequentemente excedem 800.000
   - Pagamentos tipicamente abaixo de 500.000
   - Forte indicação de uso de parcelamentos


## ✉️ Contato

[Erickson Santos] - [erickson1.dev@gmail.com]
