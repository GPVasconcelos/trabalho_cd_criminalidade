# 📊 Projeto de Ciência de Dados — Criminalidade no Paraná (2018–2024)

Este repositório contém o trabalho final da disciplina **Ciência de Dados**, do Centro Universitário FAG (2025).  
O projeto consiste em uma **análise exploratória completa (Data Science)** sobre os dados de criminalidade do IPARDES, cobrindo os anos de **2018 a 2024**, incluindo:

- limpeza e padronização dos dados brutos  
- transformação para formato longo  
- criação de variáveis analíticas  
- consultas, agregações e agrupamentos  
- visualização gráfica  
- conclusões sobre padrões criminais

---

## 🏗 Estrutura do projeto

📂 data
┣ 📂 raw # dados brutos originais (IPARDES)
┗ 📂 processed # base tratada: base_criminalidade_pr_limpa.csv

📂 notebooks
┣ 📓 01_limpeza_preparacao.ipynb
┗ 📓 02_analise_exploratoria.ipynb
📄 README.md
📄 apresentacao.pp


---

## 🔎 01 – Limpeza e preparação dos dados

Notebook responsável por:

- leitura das bases brutas
- padronização de municípios e regiões
- tratamento de valores vazios e conversões numéricas
- reconstrução do cabeçalho duplo (tipo_crime × ano)
- transformação dos dados para formato **longo**
- unificação das tabelas de crimes gerais e mortes violentas

Arquivo gerado:  
`data/processed/base_criminalidade_pr_limpa.csv`

---

## 📈 02 – Análise exploratória da criminalidade

Principais análises realizadas:

### ✔ Visão geral
- total de ocorrências por ano  
- tipos de crime mais comuns  
- fontes e estrutura da base  

### ✔ Criação da variável `grupo_crime`
Agrupamento em:
- crimes contra o patrimônio  
- crimes contra a pessoa  
- drogas  
- mortes violentas intencionais  
- armas apreendidas  

### ✔ Visões estaduais e municipais  
Separação entre:
- **Estado do Paraná**
- **municipalidades individuais**

### ✔ Análises principais
- evolução temporal (2018–2024)
- distribuição dos grupos de crimes
- participação percentual anual
- rankings por tipo de crime
- mapa de calor dos tipos de crime
- homicídios dolosos (top 10 municípios)
- mortes violentas intencionais (pós-2020)
- estelionato e sua evolução pós-2020

---

## 📌 Conclusões principais

- Há uma **queda significativa em 2020**, compatível com restrições da pandemia.  
- Em **2021–2022** ocorre aumento acentuado dos crimes — especialmente **contra o patrimônio**.  
- **Estelionato cresce de forma intensa pós-2020**, possivelmente associado a golpes digitais.  
- **Mortes violentas intencionais** representam pequena fração dos registros, mas são relevantes socialmente.  
- Grandes centros urbanos concentram os maiores volumes de crimes em números absolutos.  

---

## 🛠 Tecnologias utilizadas

- Python 3.10  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## Referências

- IPARDES — Instituto Paranaense de Desenvolvimento Econômico e Social  
-  Dados oficiais de criminalidade: https://www.ipardes.pr.gov.br  
- Documentação oficial Pandas: https://pandas.pydata.org  
- Documentação Matplotlib: https://matplotlib.org  
- Documentação Seaborn: https://seaborn.pydata.org  

---

## 👥 Autores

- Nathan Mariotto  
- Gustavo Oliveira
- Guilherme Vasconcelos 
- Leonardo Dias

