
# 📊 Análise de Dados - 5.12 Cybersecurity Detail & Data_Breach_Notifications_Affecting_Washington_Residents

Este projeto tem como foco a análise de dados públicos relacionados à **cibersegurança** no âmbito governamental dos EUA. A base utilizada foi retirada do portal oficial [DATA.GOV](https://data.gov), mais precisamente do seguinte conjunto de dados:

🔗 [5.12 Cybersecurity Detail - City of Tempe, Arizona](https://data.tempe.gov/datasets/5-12-cybersecurity-detail)

##  Objetivo do Projeto

A proposta central deste repositório é:

* Investigar o estado de conformidade cibernética de diferentes áreas administrativas.
* Identificar padrões e possíveis vulnerabilidades com base no **Compliance Score**.
* Explorar a distribuição temporal das avaliações para entender tendências e evolução.
* Gerar visualizações claras para apoiar tomadas de decisão baseadas em dados.

##  Sobre a Base de Dados

A base traz registros periódicos de conformidade cibernética em departamentos públicos da cidade de Tempe, contendo colunas como:

* `Area`
* `Sub-Area`
* `Compliance_Score`
* `Score_Notes`
* `Reporting_Date`
* `Category`
* `Status`
* `Trend`

A análise foca principalmente em:

* Distribuição de **Compliance Scores** ao longo do tempo;
* Departamentos com maiores ou menores índices de conformidade;
* Categorias de status e tendências mais comuns;
* Anomalias e outliers.

## 🛠️ Ferramentas Utilizadas

* `Python`
* `Pandas`
* `Matplotlib`
* `Seaborn`
* `Jupyter Notebook`

## 📌 Etapas Realizadas

1. **Importação e tratamento da base de dados**
   * Conversão de datas (`Reporting_Date`)
   * Remoção/tratamento de valores nulos
2. **Exploração dos dados (EDA)**
   * `value_counts()`, `groupby()`, análise temporal
   * Visualizações com `matplotlib` e `seaborn`
3. **Criação de variáveis derivadas**
   * Extração de ano/mês
   * Categorização e agregação
4. **Visualizações e insights**
   * Gráficos de barras, linhas e heatmaps

## Exemplos de Análises Feitas

* Evolução dos Compliance Scores ao longo dos anos
* Áreas mais críticas (com scores baixos)
* Tendência de melhora ou piora na segurança digital
* Correlações entre variáveis relevantes

## 📎 Arquivos no Repositório

* `cybersecurity_analysis.ipynb`: Notebook com todo o processo de análise.

## Como Reproduzir

1. Clone este repositório:

   ```bash
   git clone https://github.com/Jamielly/Analise_CyberSecurity.git
   cd Analise_CyberSecurity
   ```
2. Instale as dependências:

   ```bash
   pip install pandas matplotlib seaborn pillow
   ```
3. Execute o notebook:

   ```bash
   jupyter notebook cybersecurity.ipynb
   ```

---

# 🛡️ Cybersecurity Data Analysis

Este repositório contém um notebook interativo para análise de dados de cibersegurança. O objetivo é realizar uma análise exploratória, limpeza de dados, clustering e regressão, aplicando conceitos de Machine Learning na prática.

## 🔥 Tecnologias Utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 🚀 Funcionalidades
- Limpeza de dados e transformação de variáveis
- Análise exploratória de dados (EDA)
- Análise de correlação
- Redução de dimensionalidade com PCA
- Agrupamento com KMeans
- Regressão Linear para previsão do Compliance Score

## 🏗️ Estrutura
- `Cybersecurity_Analysis.ipynb`: Notebook com toda a análise e modelos aplicados
- `cybersecurity.csv`: Dataset de entrada

## 🎯 Como Rodar
1. Clone este repositório
2. Instale as dependências:
```
pip install pandas numpy matplotlib seaborn scikit-learn
```
3. Execute o notebook no Jupyter ou no VSCode com Jupyter.

## 📊 Resultados
- Mapas de correlação
- Visualização dos clusters
- Métricas de regressão (MSE)

## 🤖 Próximos Passos
- Refinamento dos modelos
- Teste com algoritmos supervisionados e não supervisionados adicionais
- Deploy como API ou dashboard

## 📜 Licença
MIT License
