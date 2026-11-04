# Análisis Exploratorio de las Horas Extraordinarias en España

**Autor:** Miguel Ángel Bauset Guardado  
**Asignatura:** Ciencia de Datos

---

# 1. Introducción

Las horas extraordinarias constituyen un indicador relevante para comprender la evolución del mercado laboral español. Su análisis permite estudiar tanto la cantidad de trabajo adicional realizado por los trabajadores como las diferencias existentes entre sectores económicos y formas de remuneración.

En este proyecto se ha llevado a cabo un análisis exploratorio de datos (EDA) utilizando información procedente de la Encuesta de Población Activa (EPA) publicada por el Instituto Nacional de Estadística (INE). El objetivo ha sido identificar patrones temporales y sectoriales relacionados con las horas extraordinarias realizadas por la población asalariada en España.

---

# 2. Objetivos

Los objetivos principales del proyecto son:

- Analizar la evolución temporal de los asalariados que realizan horas extraordinarias.
- Comparar la evolución de las horas extraordinarias pagadas y no pagadas.
- Identificar los sectores económicos con mayor volumen de horas extraordinarias no remuneradas.
- Aplicar técnicas de limpieza y análisis exploratorio de datos mediante Python.

---

# 3. Hipótesis de trabajo

Antes de realizar el análisis se plantearon las siguientes hipótesis:

## Hipótesis 1

El número de trabajadores que realizan horas extraordinarias disminuyó tras la crisis económica de 2008 y posteriormente mostró una recuperación progresiva.

## Hipótesis 2

Una parte significativa de las horas extraordinarias realizadas en España continúa sin ser remunerada.

## Hipótesis 3

Existen diferencias significativas entre sectores económicos en relación con las horas extraordinarias no pagadas.

---

# 4. Fuente de datos

Los datos utilizados proceden de la Encuesta de Población Activa (EPA) publicada por el Instituto Nacional de Estadística (INE).

Se emplearon dos conjuntos de datos:

- Asalariados que realizan horas extraordinarias.
- Horas extraordinarias pagadas y no pagadas por rama de actividad económica.

Estos conjuntos contienen información trimestral y permiten analizar tanto la evolución temporal como las diferencias sectoriales en la realización de horas extraordinarias.

---

# 5. Preparación y limpieza de los datos

Antes de realizar el análisis fue necesario llevar a cabo un proceso de limpieza y preparación de los datos.

Las principales tareas realizadas fueron:

- Exploración inicial de las variables disponibles.
- Conversión de variables numéricas almacenadas como texto.
- Sustitución de valores especiales ("..") por valores nulos.
- Eliminación de registros vacíos o inconsistentes.
- Comprobación de valores perdidos.
- Verificación de posibles duplicados.

Estas tareas permitieron disponer de conjuntos de datos consistentes y preparados para el análisis posterior.

---

# 6. Análisis exploratorio

## 6.1 Evolución de los asalariados que realizan horas extraordinarias

La primera parte del análisis se centró en la evolución temporal del número de asalariados que realizan horas extraordinarias.

Los resultados muestran una disminución importante tras la crisis económica de 2008. Posteriormente puede observarse una recuperación gradual que se intensifica durante la década de 2020.

### Conclusiones

- Se observa una caída significativa tras la crisis económica de 2008.
- A partir de 2014 comienza una recuperación progresiva.
- Las horas extraordinarias continúan siendo una práctica habitual dentro del mercado laboral español.

---

## 6.2 Horas extraordinarias pagadas y no pagadas

La segunda visualización permitió comparar la evolución de las horas extraordinarias remuneradas y no remuneradas.

Los resultados muestran que las horas pagadas mantienen niveles superiores durante gran parte del periodo analizado. Sin embargo, las horas extraordinarias no remuneradas presentan una presencia constante durante toda la serie histórica.

### Conclusiones

- Las horas extraordinarias pagadas predominan durante la mayor parte del periodo estudiado.
- Las horas extraordinarias no remuneradas mantienen una presencia significativa.
- Una parte importante del trabajo extraordinario sigue realizándose sin compensación económica.

---

## 6.3 Análisis sectorial

Finalmente se estudió la distribución de las horas extraordinarias según actividad económica utilizando la media correspondiente a los cuatro trimestres de 2025.

Los resultados muestran una importante concentración de horas extraordinarias no remuneradas en determinados sectores.

### Conclusiones

- Educación, Transporte e Industria manufacturera registran los mayores volúmenes de horas extraordinarias no remuneradas.
- Existen diferencias significativas entre sectores económicos tanto en las horas pagadas como en las no pagadas.

---

# 7. Resultados obtenidos

Los principales hallazgos del análisis son:

- Descenso de las horas extraordinarias tras la crisis económica de 2008.
- Recuperación progresiva del número de trabajadores que realizan horas extra.
- Persistencia de las horas extraordinarias no remuneradas durante todo el periodo analizado.
- Concentración sectorial de las horas extraordinarias no pagadas.
- Importantes diferencias entre actividades económicas.

---

# 8. Verificación de hipótesis

Las hipótesis planteadas inicialmente quedan confirmadas por los resultados obtenidos.

### Hipótesis 1

Confirmada. El número de asalariados que realizan horas extraordinarias disminuyó tras la crisis económica de 2008 y posteriormente experimentó una recuperación progresiva.

### Hipótesis 2

Confirmada. Las horas extraordinarias no remuneradas mantienen una presencia constante a lo largo de toda la serie estudiada.

### Hipótesis 3

Confirmada. Existen diferencias significativas entre sectores económicos en relación con las horas extraordinarias no pagadas.

---

# 9. Limitaciones del análisis

Este estudio presenta algunas limitaciones.

En primer lugar, depende exclusivamente de los datos publicados por el Instituto Nacional de Estadística. Asimismo, algunas observaciones contienen valores ausentes que fueron tratados como datos no disponibles para evitar interpretaciones incorrectas.

Por último, el trabajo tiene un carácter descriptivo y exploratorio, por lo que no pretende establecer relaciones causales entre las variables analizadas.

---

# 10. Conclusiones

El análisis exploratorio realizado permite identificar patrones relevantes sobre la evolución de las horas extraordinarias en España.

Los resultados muestran que las horas extraordinarias siguen teniendo un peso importante dentro del mercado laboral español. Aunque la mayor parte de estas horas son remuneradas, continúa existiendo un volumen considerable de horas extraordinarias no pagadas.

Además, los datos reflejan diferencias significativas entre sectores económicos, destacando especialmente Educación, Transporte e Industria manufacturera como las actividades con mayor volumen de horas extraordinarias no remuneradas.

En conjunto, el proyecto demuestra la utilidad del análisis exploratorio de datos para estudiar fenómenos laborales a partir de fuentes estadísticas públicas y obtener conclusiones relevantes sobre la organización del trabajo en España.