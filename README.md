# 📊 Análise de Cancelamento de Clientes (Churn Analysis)

> 🎓 **Projeto desenvolvido 100% com os ensinamentos e metodologia do Grupo Hashtag Treinamentos!**

Este projeto de Análise de Dados foi desenvolvido aplicando na prática os conceitos ensinados pela **Hashtag Treinamentos** (Python Insights). O objetivo foi analisar uma base com centenas de milhares de clientes para entender os motivos de cancelamento e propor ações estratégicas para reduzir a taxa de churn.

---

## 🎯 O que aprendi com o Grupo Hashtag Treinamentos

Neste projeto, apliquei as metodologias ensinadas pela Hashtag para:
- **Tratamento e Limpeza de Dados:** Eliminação de colunas irrelevantes e remoção de valores ausentes (`dropna()`) utilizando a biblioteca `pandas`.
- **Análise Exploratória:** Diagnóstico do percentual de cancelamento da base com `value_counts(normalize=True)`.
- **Data Visualization Interativa:** Criação de gráficos e histogramas com `plotly.express` para identificar visualmente padrões de comportamento.
- **Geração de Insights de Negócio:** Tradução de dados em ações práticas para tomada de decisão comercial e operacional.
- **Simulação de Resultados:** Filtragem da base para calcular o impacto direto das soluções propostas na redução do cancelamento.

---

## 💡 Principais Insights e Soluções Identificadas

A análise revelou 3 grandes gargalos responsáveis pela maioria dos cancelamentos:

1. **Duração do Contrato:** Todos os clientes do plano mensal cancelavam o serviço.
   - 💡 **Ação:** Incentivar a migração para planos anuais e trimestrais com descontos especiais.
2. **Atendimento (Call Center):** Clientes com mais de 4 ligações para o suporte cancelavam.
   - 💡 **Ação:** Criar um alerta/alocação prioritária para resolver chamados em no máximo 3 interações.
3. **Inadimplência:** Clientes com mais de 20 dias de atraso no pagamento cancelavam.
   - 💡 **Ação:** Implementar régua de cobrança preventiva para negociação até o 10º dia de atraso.

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

- **[Python](https://www.python.org/)**
- **[Pandas](https://pandas.pydata.org/):** Manipulação, filtragem e tratamento da base de dados.
- **[Plotly Express](https://plotly.com/python/):** Criação de gráficos interativos.
- **[Jupyter Notebook](https://jupyter.org/):** Ambiente de desenvolvimento e execução passo a passo.

---

## 📂 Estrutura de Arquivos

- `Projeto.ipynb`: Notebook Jupyter contendo todo o código, análises e simulações do projeto.
- `cancelamentos.csv`: Base de dados contendo o histórico e informações dos clientes.

---

## 🚀 Como Executar o Projeto

1. **Instale as bibliotecas necessárias:**
   ```bash
   pip install pandas plotly openpyxl nbformat
