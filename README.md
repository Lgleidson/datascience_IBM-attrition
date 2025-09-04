# 📊 IBM HR Analytics – Employee Attrition & Performance

![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![Conda](https://img.shields.io/badge/environment-conda-green.svg)
![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![Visão geral do Attrition](relatorios/imagens/attrition_overview.png)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

Este projeto utiliza o dataset público **IBM HR Analytics Employee Attrition & Performance**, disponível no [Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset/data), para analisar fatores que influenciam o **atrito (attrition)** de colaboradores e desenvolver modelos de Machine Learning que possam prever a **probabilidade de um funcionário deixar a empresa**. Aula de aprendizado ensinado pela instituição [https://portalhashtag.com], [Luis Gleidson](https://github.com/Lgleidson),
instrutor [Francisco Bustamante], [https://github.com/chicolucio], para alunos iniciantes em ciência de dados de meus cursos e mentorias.

---

Inspiração: [Cookiecutter Data Science](https://drivendata.github.io/cookiecutter-data-science/)

---

## 🎯 Objetivo do Projeto

- Explorar os dados de colaboradores (idade, gênero, satisfação, cargo, salário, etc.)  
- Entender os fatores que mais impactam o **turnover**  
- Criar e comparar **modelos de machine learning** para prever attrition  
- Gerar insights que auxiliem o RH a reduzir a rotatividade de funcionários  

Clique no botão **Use this template** para criar um novo repositório com base neste modelo.

## 📂 Organização do Projeto

```bash
├── .gitignore
├── LICENSE
├── README.md
├── ambiente.yml          <- Arquivo de dependências do projeto
│
├── dados/                <- Dados brutos e processados (não versionados no GitHub)
│
├── notebooks/            <- Jupyter Notebooks
│   ├── 01-eda.ipynb       <- Análise Exploratória dos Dados (EDA)
│   └── 02-modelos-machine.ipynb <- Treinamento e avaliação de modelos
│
├── referencias/          <- Documentos auxiliares
│   ├── 01-sobre-a-base.md
│   ├── 01-dicionario-de-dados.md
│   └── 02-dicionario-de-dados.md
│
├── modelos/              <- Modelos treinados (pickle, joblib, etc.)
│
├── relatorios/           <- Relatórios finais
│   └── imagens/          <- Gráficos e figuras
│
└── src/                  <- Scripts auxiliares em Python
    ├── __init__.py
    ├── config.py
    └── graficos.py
```

---

## ⚙️ Configuração do Ambiente

### 1. Clone o repositório:
```bash
git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
cd SEU_REPOSITORIO
```

### 2. Crie o ambiente virtual com Conda:
```bash
conda env create -f ambiente.yml
conda activate projeto-hr-analytics
```

*(ou use `requirements.txt` se preferir pip)*

---

## 📊 Dataset

- Nome: **IBM HR Analytics Employee Attrition & Performance**  
- Fonte: [Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset/data)  
- Descrição: Contém informações sobre colaboradores, incluindo dados demográficos, função, salário, satisfação no trabalho e status de attrition (Sim/Não).  

---

## 🚀 Resultados Esperados

- Identificação dos fatores que mais influenciam o attrition  
- Comparação entre algoritmos de classificação (ex.: **Logistic Regression, Random Forest, XGBoost, LightGBM**)  
- Relatório final com insights e recomendações para o setor de RH  

---

## 📜 Licença

Este projeto é distribuído sob a licença [MIT](LICENSE).  
