# AI4ENG
Intro to AI ENG

### Integrantes del grupo:

- Juan Diego Alvarez; `ID: 1003814249` ; *Ingeniería Mecánica*
- Julián David Martínez; `ID: 1152226090` ; *Ingeniería Mecánica*

`Enlace de vídeo 1:` https://youtu.be/VxL-ZoebWmQ

`Enlace de vídeo 2:` 

# Proyecto Final – Predicción de Rendimiento Académico

**(Competencia Kaggle)**

Este repositorio contiene el desarrollo completo del proyecto final, incluyendo la exploración del dataset, estrategias de preprocesamiento y las pruebas con diferentes modelos de Machine Learning.  
El objetivo fue generar una solución competitiva para la competencia publicada en Kaggle.

## Enfoque del Proyecto

Durante el proceso se realizaron:
- Se evaluaron algoritmos como regresiones, Gradient Boosting, Random Forest, TensorFlow, CatBoost, junto con diferentes configuraciones y tamaños de muestra.

- **Múltiples pipelines de preprocesamiento**  
  Se construyeron diversos métodos de limpieza y normalización de los datos, abordando:
  - valores faltantes,
  - estandarización de texto,
  - normalización del target,
  - imputación de variables categóricas,

**Para cada modelo se estudiaron métricas de accuracy y F1-macro con distintos tamaños del dataset, buscando estabilidad y buen rendimiento.**

## Modelo Seleccionado:

**CatBoost**

## Datasets preprocesados:
De manera alternativa, se pueden descargar todos los datasets usados en los modelos desde el siguiente enlace:

`https://fromsmash.com/datasets-IA4Eng`

## 📂 Estructura del Repositorio

── README.md<br>
├── 01 - exploración.ipynb<br>
├── 02 - preprocesado.ipynb<br>
├── 03 - preprocesado limpieza cualitativa.ipynb<br>
├── 04 - preprocesado test for catboost.ipynb<br>
├── 99 - modelo solución.ipynb<br>
└── catboost_model.cbm<br>

**01 - exploración.ipynb**  
Exploración inicial del dataset, análisis descriptivo y primeras observaciones.

**02 - preprocesado.ipynb**  
Pipeline principal de limpieza, tratamiento de NaN, normalización y estandarización.

**03 - preprocesado limpieza cualitativa.ipynb**  
Enfoque complementario basado en inspección manual y ajustes específicos.

**04 - preprocesado test for catboost.ipynb**  
Limpieza e imputación dedicada al dataset de test para CatBoost.

**99 - modelo solución.ipynb**  
Entrenamiento final del modelo, carga del modelo `.cbm`, evaluación interna y generación del submission file.

**catboost_model.cbm**  
Modelo entrenado final.




