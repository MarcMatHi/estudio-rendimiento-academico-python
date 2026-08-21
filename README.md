# 📚 Estudio del Rendimiento Académico: Análisis Estadístico en Python

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Status](https://img.shields.io/badge/Status-Completado-success.svg)]()

> **Portafolio de Análisis de Datos** | Análisis de factores que impactan el rendimiento de los estudiantes mediante técnicas de estadística inferencial.

## 📌 Resumen del Proyecto

El objetivo de este proyecto es analizar datos relacionados con los hábitos y el entorno de los estudiantes para descubrir qué factores tienen un impacto real y estadísticamente significativo en su rendimiento académico. 

En lugar de basarnos en la intuición, aplicamos **estadística inferencial** para responder a dos preguntas de negocio (o de investigación) fundamentales:

1. ¿Es mejor estudiar más o dormir mejor para sacar buenas notas?
2. ¿Afecta tener un trabajo a tiempo parcial a la nota final?

---

## 🔍 Análisis y Preguntas de Negocio

Este repositorio está dividido en dos análisis principales, cada uno documentado en su propio Jupyter Notebook.

### 1. Estudio vs. Descanso: ¿Qué pesa más? 🛌📚
**Notebook:** [`Estudiar_vs_Descansar.ipynb`](./Estudiar_vs_Descansar.ipynb)

En esta primera fase, exploramos la relación entre las horas dedicadas al estudio, las horas de sueño y las calificaciones obtenidas. 
* **Metodología:** Análisis de correlación de Pearson, pruebas de hipótesis (Test T / ANOVA) para comparar grupos con diferentes hábitos de sueño/estudio.
* **Hallazgos Principales:** 
  * *[Añade aquí tu conclusión 1: ej. "Se descubrió que dormir menos de 6 horas anula los beneficios de estudiar más de 4 horas diarias..."]*
  * *[Añade aquí tu conclusión 2]*
* **Recomendación de Negocio/Educativa:** *[Ej. "Las instituciones educativas deberían fomentar campañas de higiene del sueño, ya que optimiza el tiempo de estudio..."]*

### 2. El Impacto del Trabajo a Tiempo Parcial 💼🎓
**Notebook:** [`Trabajo_efecto_NotaFinal.ipynb`](./Trabajo_efecto_NotaFinal.ipynb)

Muchos estudiantes compaginan sus estudios con trabajos a media jornada. ¿Tiene esto un costo penalizador en sus notas finales?
* **Metodología:** Pruebas de hipótesis comparando las medias poblacionales de estudiantes que trabajan vs. los que no trabajan, controlando variables como las horas de estudio.
* **Hallazgos Principales:**
  * *[Añade aquí tu conclusión 1: ej. "Contrario a lo esperado, los estudiantes con trabajos de menos de 15 horas semanales mostraron un rendimiento un 5% superior..."]*
  * *[Añade aquí tu conclusión 2]*
* **Recomendación de Negocio/Educativa:** *[Ej. "Fomentar programas de trabajo en el campus con horarios limitados puede ser beneficioso para la gestión del tiempo del estudiante..."]*

---

## 🛠️ Herramientas y Tecnologías Utilizadas

* **Lenguaje:** Python 3
* **Manipulación y Limpieza de Datos:** `pandas`, `numpy`
* **Visualización de Datos:** `matplotlib`, `seaborn`
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

**[Tu Nombre/MarcMatHi]**
* Data Analyst 
* [Enlace a tu LinkedIn]
* [Enlace a tu Portafolio/Web personal]

*Si tienes alguna pregunta o sugerencia sobre este análisis, ¡no dudes en contactarme o abrir una issue!*
