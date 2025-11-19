# 📊 Estudio inferencial sobre el gasto en viajes realizados en Julio de 2024: Perspectivas desde los datos del I.N.E.  
## Trabajo grupal — 30 de abril de 2025  
**Equipo ε**  
Universidad de Oviedo — Facultad de Ciencias.  
Asignatura: *Inferencia Estadística*.

Este proyecto analiza los patrones de gasto en viajes realizados durante julio de 2024 por residentes en España, utilizando datos del Instituto Nacional de Estadística (INE). Se estudian relaciones entre variables como:

- gasto total por día.  
- tipo de acompañamiento.  
- ingresos del hogar.  
- género.  
- destino del viaje.  
- método de reserva del alojamiento.  

El estudio combina análisis descriptivos y contrastes de hipótesis mediante métodos como:

- Tests de normalidad: **Shapiro–Wilk**, **Kolmogorov–Smirnov**, **Lilliefors**.  
- Test de igualdad de varianzas: **Levene**.  
- Tests no paramétricos: **Kruskal–Wallis**, **Dunn** (post-hoc con corrección de Holm), **Mann–Whitney/Wilcoxon** para dos grupos.  
- Test de proporciones: **prueba de igualdad de proporciones**
- Correlación de **Spearman**.  
- Visualizaciones: histogramas, boxplots, gráficos de violín, Q–Q plots y tablas resumen.  

---

## 📁 Contenido del repositorio

### **1. Informe principal**  
Incluye el desarrollo completo del análisis, la metodología empleada y las conclusiones finales.  

📄 `Informe-Estudio-Inferencial-INE-2024.pdf`.

### **2. Anexo**  
Documento complementario que recoge el **código en R** utilizado en el proyecto, incluyendo el filtrado de datos, los distintos contrastes (acompañante, ingresos, destino, género y modo de reserva), así como el análisis del gasto por día y por persona. También incorpora la construcción de **intervalos de confianza** para la media del gasto en alojamiento según el modo de reserva y un **análisis univariable** con tablas, resúmenes y visualizaciones.

📄 `Anexo-Estudio-Inferencial-INE-2024.pdf`.

---

## 👥 Mi contribución personal en el proyecto  
Soy **Pablo Llorian González**, integrante del **Equipo ε**, responsable del:

### 🔹 *Análisis de la relación entre el destino de viaje y el gasto total por día*  
Mi participación incluyó:

- Clasificación de los viajes según **tipo de destino**.  
- Preparación, filtrado y exploración del subconjunto de datos correspondiente.  
- Estudio comparativo del **gasto total por día** entre los distintos destinos.  
- Aplicación de contrastes de hipótesis adecuados (normalidad, homogeneidad de varianzas, pruebas no paramétricas).  
- Elaboración de visualizaciones (boxplots, violines, gráficos comparativos).  
- Interpretación detallada de los resultados del análisis.  
- Redacción de conclusiones e integración del apartado dentro del informe global.  

---

## 🛠️ Tecnologías utilizadas

- **R** (tidyverse, ggplot2…).  
- **LaTeX** para la elaboración del informe.  
- **GitHub** para documentar y organizar el proyecto.  

---

## 📅 Fecha  
30 de abril de 2025.
