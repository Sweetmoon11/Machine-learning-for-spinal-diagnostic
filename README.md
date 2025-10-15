# Machine-learning-for-spinal-diagnostic
Proyecto de clasificación ortopédica usando aprendizaje automático. Se analizan seis variables biomecánicas para predecir si un paciente presenta una anomalía espinal. Incluye exploración de datos, visualización, correlaciones y preparación para modelado supervisado.
# 🧠 Clasificación de anomalías ortopédicas mediante aprendizaje automático

Este proyecto forma parte de un laboratorio práctico del Módulo 3, enfocado en aplicar técnicas de aprendizaje automático para mejorar la detección de anomalías en pacientes ortopédicos. Utiliza un conjunto de datos biomédicos que contiene seis características biomecánicas derivadas de la forma y orientación de la pelvis y la columna lumbar.

## 🏥 Escenario empresarial

Como analista de datos en una institución de atención médica, tu objetivo es desarrollar un modelo capaz de predecir si un paciente presenta una condición ortopédica anormal. Esto permitirá mejorar la eficiencia diagnóstica y apoyar la toma de decisiones clínicas.

---

## 📦 Acerca del conjunto de datos

El conjunto de datos fue creado por el Dr. Henrique da Mota durante su residencia médica en el Grupo de Investigación Aplicada en Ortopedia (GARO), en Lyon, Francia. Está disponible públicamente en el [Repositorio de aprendizaje automático de la UCI](http://archive.ics.uci.edu/ml/datasets/Vertebral+Column).

### 🔢 Atributos biomecánicos

Cada paciente está representado por seis variables numéricas:

- `pelvic_incidence` – Incidencia pélvica  
- `pelvic_tilt` – Inclinación pélvica  
- `lumbar_lordosis_angle` – Ángulo de lordosis lumbar  
- `sacral_slope` – Inclinación del sacro  
- `pelvic_radius` – Radio pélvico  
- `degree_spondylolisthesis` – Grado de espondilolistesis

### 🎯 Etiquetas de clase

El conjunto de datos se organiza en dos tareas de clasificación:

- **Tarea 1 (Multiclase)**:
  - Normal (NO) – 100 pacientes
  - Hernia de disco (HD) – 60 pacientes
  - Espondilolistesis (EL) – 150 pacientes

- **Tarea 2 (Binaria)**:
  - Normal (NO) – 100 pacientes
  - Anormal (AN = HD + EL) – 210 pacientes

---

## 🔍 Exploración inicial

El análisis comienza con la inspección de la forma del conjunto de datos, seguido de:

- Estadísticas descriptivas por variable
- Visualización de distribuciones y outliers
- Comparación de medias por clase
- Matrices de correlación y gráficos de dispersión
- Boxplots por clase para evaluar diferencias significativas

---

## 🧪 Objetivo del laboratorio

Desarrollar un modelo de clasificación supervisado que prediga si un paciente pertenece a la clase **Normal** o **Anormal**, utilizando las características biomecánicas como variables predictoras.

---

## 🛠️ Herramientas utilizadas

- Python (pandas, numpy, matplotlib, seaborn)
- Jupyter Notebook
- Scikit-learn (para modelado en etapas posteriores)

---

## 📈 Próximos pasos

- Preprocesamiento de datos (normalización, tratamiento de outliers)
- Selección de características relevantes
- Entrenamiento de modelos (Logistic Regression, Random Forest, etc.)
- Evaluación de desempeño (accuracy, precision, recall, F1-score)

---

## 📚 Créditos

Este conjunto de datos fue obtenido de:  
**Dua, D. y Graff, C. (2019).** Repositorio de aprendizaje automático de la UCI.  
[Vertebral Column Data Set](http://archive.ics.uci.edu/ml/datasets/Vertebral+Column)

---
