# Predicción de precios de acciones con analisis de sentimiento

# (MCD ITAM Primavera 2024)

## Autores 📚

| Nombre                     |  CU    | Correo Electrónico | Usuario Github |
|----------------------------|--------|--------------------|----------------|
| Blanca E. García Manjarrez | 118886 | bgarci11@itam.mx   |    BGARCIAMA   |
| Iván García Alba           | 214549 | rgarc199@itam.mx   |    GARCIA889   |
| Valeria Durán Rubio        | 124273 | vduranru@itam.mx   |    VDR90       |
| Gabriela Venegas Sánchez   | 214571 | gvenega2@itam.mx   | GabrielaVenegas|
| José Antonio Tapia Godinez | 214553 | jtapiago@itam.mx   |   AntonioIQ    |
| Yuneri Pérez Arellano      | 199813 | yperezar@itam.mx   |    YunPerez    |

# Contexto  🧠

En el ámbito cambiante de los mercados financieros, los pronósticos de precios de acciones representa un desafío significativo pero esencial para analistas e inversionistas. Los enfoques convencionales para pronosticar los precios de acciones se han centrado en analizar datos financieros históricos, ignorando cómo el sentimiento público expresado en noticias, redes sociales y otros medios textuales podría impactar estos mercados.

Este proyecto investiga una metodología innovadora para incrementar la precisión en las predicciones de precios de acciones incorporando el análisis de sentimiento a través de modelos de aprendizaje profundo, enfocándose en particular en las redes neuronales de memoria a corto plazo (LSTM).

La esencia de nuestro enfoque es utilizar datos de sentimiento obtenidos de varias fuentes, analizados por un modelo de procesamiento de lenguaje natural (NLP) especializado en finanzas, FinBERT, conocido por su capacidad para interpretar sentimientos en textos financieros. Integrando estas evaluaciones de sentimiento como características nuevas en los modelos LSTM, buscamos reflejar las emociones y opiniones que pueden afectar los precios de las acciones, ofreciendo una perspectiva más completa de la dinámica del mercado.

Nuestro análisis detalla el proceso técnico de este método integrado, desde la preparación y normalización de datos hasta la configuración y entrenamiento de los modelos LSTM, con y sin la integración del análisis de sentimiento del mercado. Evaluamos cuidadosamente el desempeño de estos modelos, comparando su capacidad de predicción usando varias métricas y técnicas de visualización. El propósito es determinar si la inclusión de datos de sentimiento mejora o deteriora la eficacia de los modelos LSTM tradicionales en el pronóstico de los precios de las acciones.

Con este estudio aspiramos a incorporar los indicadores cualitativos del sentimiento del mercado con los indicadores cuantitativos tradicionales de las acciones, proporcionando una herramienta analítica más robusta para la predicción y análisis del mercado.

# Objetivo del proyecto  🎯
Desarrollar un modelo que integre el uso de un modelo predictivo en Python para estimar el precio de una acción utilizando información historica y el análisis del sentimiento del mercado utilizando Deep Learning.

# Base de datos  ✍
* Información del mercado utilizando Alpha Vantage API
* Tweets para el análisis del sentimiento del mercado

# Infraestructura y Ejecución  ⚙

## Requerimientos de Software herramientas recomendadas

1. [Cuenta de Github](https://github.com)
2. [VSCodeIDE](https://code.visualstudio.com/)

## Fuentes

PRINCIPAL
- https://medium.com/@redeaddiscolll/integrating-sentiment-analysis-in-stock-price-forecasting-with-deep-learning-techniques-bb5f84fd59f6
- https://www.kaggle.com/datasets/omermetinn/tweets-about-the-top-companies-from-2015-to-2020?select=Tweet.csv

SECUNDARIAS
- https://medium.com/analytics-vidhya/using-sentiment-analysis-to-predict-the-stock-market-77100295d753
- https://medium.com/@chedy.smaoui/how-i-code-a-python-stock-screener-a-i-sentiment-analysis-to-pick-stocks-77059463f77a
- https://medium.com/@redeaddiscolll/advanced-machine-learning-and-deep-learning-techniques-for-stock-market-analysis-06e5b8c6b62c
- https://www.alphavantage.co/documentation/#daily
- https://github.com/RomelTorres/av_example/blob/master/Alpha%20vantage%20examples.ipynb


Notas:

Ocuparemos el modelo pre entrenado de FINBERT
https://github.com/ProsusAI/finBERT
