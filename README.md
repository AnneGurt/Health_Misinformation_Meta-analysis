# Meta-analysis of Online Health-related Misinformation

## 🇬🇧

This repository contains all the code, data processing, and analysis developed for the Final Degree Project titled “Meta-analysis of Online Health-related Misinformation”. The objective of this project is to explore whether the characteristics of medical search queries can predict the risk of retrieving harmful or helpful content in search engines.

The project is based on data from the TREC Health Misinformation Track (editions 2020, 2021, and 2022). It includes:

- Exploratory Data Analysis (EDA)
- Document distribution analysis (helpful vs. harmful)
- Development of three misinformation predictors:
  - Lexical frequency analysis
  - Bias classifier
  - Large Language Model (LLM) controversy estimation

## Technologies Used
- Python
- Jupyter Notebook
- pandas, numpy
- matplotlib, seaborn
- Hugging Face Transformers
- Ollama (Mistral model for LLM-based estimation)

## 📊 Data Source

The datasets used in this project were extracted from the TREC Health Misinformation Track official repositories:
- [TREC 2020](https://pages.nist.gov/trec-browser/trec29/misinfo/data/)
- [TREC 2021](https://pages.nist.gov/trec-browser/trec30/misinfo/data/)
- [TREC 2022](https://pages.nist.gov/trec-browser/trec31/misinfo/data/)

These datasets contain the queries (topics) and manual relevance judgments (qrels) used for evaluation in the competition.
_______________________________________________________________

# Metaestudio de desinformación online relacionada con la salud

## 🇪🇸

Este repositorio contiene el código, el procesamiento de datos y los análisis realizados para el Trabajo de Fin de Grado titulado “Metaestudio de desinformación online relacionada con la salud”. El objetivo del proyecto es explorar si las características de las consultas médicas permiten predecir el riesgo de recuperar desinformación o contenido útil en buscadores.

El proyecto se basa en los datos del TREC Health Misinformation Track (ediciones 2020, 2021 y 2022). Incluye:
- Análisis exploratorio de datos (EDA)
- Análisis de distribución de documentos (útiles vs. perjudiciales)
- Desarrollo de tres predictores de desinformación:
  - Análisis de frecuencia léxica
  - Clasificador de sesgo
  - Estimación de controversia mediante Modelos de Lenguaje (LLM)

## Tecnologías Utilizadas
- Python
- Jupyter Notebook
- pandas, numpy
- matplotlib, seaborn
- Hugging Face Transformers
- Ollama (modelo Mistral para estimación con LLM)

 ## 📊 Fuente de Datos

Los datos utilizados en este proyecto fueron extraídos de los repositorios oficiales del TREC Health Misinformation Track:
- [TREC 2020](https://pages.nist.gov/trec-browser/trec29/misinfo/data/)
- [TREC 2021](https://pages.nist.gov/trec-browser/trec30/misinfo/data/)
- [TREC 2022](https://pages.nist.gov/trec-browser/trec31/misinfo/data/)

Estos datasets contienen las consultas (topics) y las anotaciones manuales de relevancia (qrels) usadas para la evaluación en la competición.
