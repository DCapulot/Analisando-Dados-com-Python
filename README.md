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

```
Analisando-Dados-com-Python/
├── Projeto.ipynb        # Notebook com todo o código, análises e simulações
├── cancelamentos.csv    # Base de dados com o histórico dos clientes
└── README.md
```

> ⚠️ O arquivo `cancelamentos.csv` precisa estar na **mesma pasta** do `Projeto.ipynb` para que os comandos de leitura de dados (`pd.read_csv(...)`) funcionem corretamente.

---

## 🚀 Como Executar o Projeto

### 1. Clone o repositório

```bash
git clone https://github.com/DCapulot/Analisando-Dados-com-Python.git
```

### 2. Entre na pasta do projeto

```bash
cd Analisando-Dados-com-Python
```

### 3. Instale as bibliotecas necessárias

```bash
pip install pandas plotly openpyxl nbformat notebook
```

### 4. Abra o notebook

Você pode abrir o `Projeto.ipynb` de duas formas:

**Opção A — Jupyter Notebook:**
```bash
jupyter notebook Projeto.ipynb
```

**Opção B — VS Code:**
Abra a pasta no VS Code, instale a extensão "Jupyter" (se ainda não tiver) e abra o arquivo `Projeto.ipynb`.

### 5. Execute as células

Rode as células do notebook **em ordem**, de cima para baixo, para reproduzir todo o tratamento de dados, os gráficos e as simulações.

---

## 📚 Fonte / Créditos

Este projeto foi desenvolvido com base nos ensinamentos do **[Grupo Hashtag Treinamentos](https://www.hashtagtreinamentos.com/)**, referência em cursos de Python, Excel e Análise de Dados no Brasil.

---

## 👤 Autor

**David Capulot Corrêa**

Projeto desenvolvido para fins de estudo e prática de Análise de Dados com Python.
