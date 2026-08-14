<div align="center">

# Glioma Grading Clinical and Mutation Features - Visualización de Datos 2026
**Optimización del Diagnóstico de Gliomas mediante Ciencia de Datos y Aprendizaje Automático**
<br>

**Autores**

Alejandro Cantillo  
Joshua Hincapie

<br>

---

</div>

## Introducción

Los gliomas representan el tumor cerebral primario más común en adultos y se clasifican principalmente en Gliomas de Bajo Grado (LGG) y Glioblastoma Multiforme (GBM). Si bien los criterios histológicos e imagenológicos tradicionales han sido la base del diagnóstico, la caracterización biomolecular y clínica se ha vuelto imprescindible para determinar el pronóstico y el tratamiento idóneo. Sin embargo, las pruebas de secuenciación genética completa suponen un coste económico elevado para los sistemas de salud y los pacientes.

Este proyecto aborda este desafío analítico y médico mediante la integración de Análisis Exploratorio de Datos (EDA), aprendizaje automático y visualización interactiva. Utilizando datos recopilados de los proyectos TCGA-LGG y TCGA-GBM de *The Cancer Genome Atlas*, el objetivo central es construir una solución analítica integral que identifique el subconjunto óptimo de factores clínicos y mutaciones genéticas para clasificar con precisión la severidad del glioma, reduciendo los costos asociados a pruebas moleculares innecesarias.



## Objetivo

El objetivo principal es realizar un análisis exploratorio de
las variables clínicas y genéticas disponibles y estudiar su
relación con la variable objetivo `Grade`.

A través del análisis exploratorio y la visualización de datos,
se buscará identificar patrones, distribuciones y relaciones que
permitan comprender mejor las características de los pacientes
y su posible asociación con el grado del glioma.

> **Pregunta:** ¿Qué patrones y relaciones pueden
> identificarse en las características clínicas y genéticas
> de los pacientes según el grado del glioma (`Grade`)?

## Datos

Para el análisis se utilizarán dos archivos:

- `TCGA_GBM_LGG_Mutations_all.csv`
- `TCGA_InfoWithGrade.csv`

Los datos utilizados en este proyecto proceden de información clínica 
y molecular asociada al estudio de gliomas dentro de The Cancer Genome 
Atlas (TCGA).

Estos archivos contienen información clínica y características
relacionadas con mutaciones genéticas de pacientes con glioma. 
El análisis de ambos conjuntos de datos permitirá explorar sus
estructuras, características y variables disponibles antes de
realizar análisis más específicos.

## Metodología

El proyecto se desarrollará mediante las siguientes etapas:

1. Análisis Exploratorio de Datos (EDA)


**Ficha Técnica del Dataset**

* **Muestra:** 839 registros de pacientes.
* **Atributos (23):** 20 genes con alta frecuencia de mutación y 3 variables clínicas relevantes.
* **Variable Objetivo:** Clasificación binaria entre **LGG** (Lower-Grade Glioma) y **GBM** (Glioblastoma Multiforme).
* **Naturaleza de datos:** Tabular, multivariada (numérica y categórica)

## Estructura

El Jupyter Book está organizado en diferentes secciones para
presentar de manera progresiva el análisis exploratorio,
el procesamiento de los datos y las visualizaciones obtenidas.


```{tableofcontents}
```
