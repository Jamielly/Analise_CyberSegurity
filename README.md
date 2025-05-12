# 📊 Análise de Dados - 5.12 Cybersecurity Detail

Este projeto tem como foco a análise de dados públicos relacionados à **cibersegurança** no âmbito governamental dos EUA. A base utilizada foi retirada do portal oficial [DATA.GOV](https://data.gov), mais precisamente do seguinte conjunto de dados:

🔗 [5.12 Cybersecurity Detail - City of Tempe, Arizona](https://data.tempe.gov/datasets/5-12-cybersecurity-detail)

## 🧠 Objetivo do Projeto

A proposta central deste repositório é:

* Investigar o estado de conformidade cibernética de diferentes áreas administrativas.
* Identificar padrões e possíveis vulnerabilidades com base no **Compliance Score**.
* Explorar a distribuição temporal das avaliações para entender tendências e evolução.
* Gerar visualizações claras para apoiar tomadas de decisão baseadas em dados.

## 🧾 Sobre a Base de Dados

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

## 📊 Exemplos de Análises Feitas

* Evolução dos Compliance Scores ao longo dos anos
* Áreas mais críticas (com scores baixos)
* Tendência de melhora ou piora na segurança digital
* Correlações entre variáveis relevantes

## 📎 Arquivos no Repositório

* `cybersecurity_analysis.ipynb`: Notebook com todo o processo de análise.
* `banner_cybersecurity.pptx`: Banner em PowerPoint com visual final do projeto.
* `qr_code_github.png`: QR Code com link para o repositório.
* `README.md`: Este arquivo.

## 🚀 Como Reproduzir

1. Clone este repositório:

   ```bash
   git clone https://github.com/Jamielly/CV.git
   cd CV
   ```
2. Instale as dependências:

   ```bash
   pip install pandas matplotlib seaborn qrcode pillow
   ```
3. Execute o notebook:

   ```bash
   jupyter notebook cybersecurity_analysis.ipynb
   ```

---
<p align="center">Made with :heart:</p>
