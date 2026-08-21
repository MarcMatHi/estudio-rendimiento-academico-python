# 📚 Estudio del Rendimiento Académico: Análisis Estadístico en Python

[![Python](https://img.shields.io/badge/Python-3.14-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Status](https://img.shields.io/badge/Status-Completado-success.svg)]()

> **Portafolio de Análisis de Datos** | Análisis de factores que impactan el rendimiento de los estudiantes mediante técnicas de estadística inferencial.

## 📌 Resumen del Proyecto

El objetivo de este proyecto es **analizar datos relacionados con los hábitos y el entorno de los estudiantes** para descubrir qué factores tienen un impacto real y estadísticamente significativo en su rendimiento académico. 

En lugar de basarnos en la intuición, aplicamos **estadística inferencial** para responder a dos preguntas de investigación fundamentales:

1. ¿Es mejor estudiar más o dormir mejor para sacar buenas notas?
2. ¿Afecta tener un trabajo a tiempo parcial a la nota final?

---

## 🔍 Análisis y Preguntas de Investigación

Este repositorio está dividido en dos análisis principales, cada uno documentado en su propio Jupyter Notebook.

### 1. Estudio vs. Descanso: ¿Qué pesa más? 🛌📚
**Notebook:** [`Estudiar_vs_Descansar.ipynb`](./Estudiar_vs_Descansar.ipynb)

En esta primera fase, exploramos la relación entre las horas dedicadas al estudio, las horas de sueño y las calificaciones obtenidas. 
* **Metodología:** Análisis de correlación Bivariante y Regresión Lineal para comprobar la relación entre los diferentes parámetros y cuál es su influencia en la nota final.
* **Hallazgos Principales:** 
  * *Se descubrió que el efecto de ambas variables está relacionado con una mejor nota final.*
  * *Estudiar más horas mostró una mejoría en la nota final respecto a descansar mejor.*
* **Recomendación de Educativa:** *La clave para sacar mejores notas consiste en estudiar las horas necesarias y dormir bien.*

### 2. El Impacto del Trabajo a Tiempo Parcial 💼🎓
**Notebook:** [`Trabajo_efecto_NotaFinal.ipynb`](./Trabajo_efecto_NotaFinal.ipynb)

Muchos estudiantes compaginan sus estudios con trabajos a media jornada. ¿Tiene esto un costo penalizador en sus notas finales?
* **Metodología:** Pruebas de hipótesis (T-test, tamño del efecto) comparando las medias poblacionales de estudiantes que trabajan vs. los que no trabajan.
* **Hallazgos Principales:**
  * *Los estudiantes con trabajo mostraron un rendimiento académico menor en comparación a los estudiantes que no trabajan*
  * *El tamaño del efecto medio-bajo nos indica que, si bien influye, el efecto de compaginar trabajo con estudios es pequeño*
* **Recomendación de Educativa:** *Fomentar programas de gestión del tiempo podría ser beneficioso para los estudiantes con trabajo.*

---

## 🛠️ Herramientas y Tecnologías Utilizadas

* **Lenguaje:** Python 3
* **Manipulación y Limpieza de Datos:** `pandas`, `numpy`
* **Análisis Estadístico:** `scipy.stats`, `statsmodels`
* **Entorno:** Jupyter Notebook

---

## 🚀 Cómo ejecutar este proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/MarcMatHi/estudio-rendimiento-academico-python.git
   ```
2. Instala las dependencias necesarias:
   ```bash
   pip install pandas numpy matplotlib seaborn scipy statsmodels
   ```
3. Abre los notebooks utilizando Jupyter:
   ```bash
   jupyter notebook
   ```

---

## 👨‍💻 Autor

**[Marc Mateu Higueras**
* Data Analyst 
* https://www.linkedin.com/in/marc-mateu-higueras-2814a7390/
