# Evaluación 2 - Big Data

![Logo de DuocUC](img/Logo_DuocUC.svg.png)

## En esta página se muestran las imágenes de evidencia de la Evaluación 2 de Big Data

### Integrantes:
- Jordy Bazan  
- Benjamin Zuñiga  

**Sección:** 001-D, Grupo 11  
**Fecha:** 29/05/2025  
**Profesor:** Fernando Esteban Fuentes Gallegos

---

## Pasos realizados del laboratorio GSP 823 de Google Cloud

### 1. Creación de bucket
Creamos un bucket y le proporcionamos un nombre para poder identificarlo.  
![Paso 1](img/parte_uno.jpg)

### 2. Selección de Alteryx Designer Granging
Seleccionamos el apartado de Analytics y luego la opción **Alteryx Designer Granging**.  
![Paso 2](img/paso_2.jpeg)

### 3. Creación de Flow en Dataprep
Creamos un nuevo flow y le damos un nombre.  
![Paso 3.1](img/paso_3.1.jpeg)  
![Paso 3](img/Paso_3.jpeg)

### 4. Carga del Dataset
Cargamos el dataset `ufo_sighting.xlsx`.  
![Paso 4](img/paso_4.jpeg)

### 5. Edición del Dataset
Seleccionamos **Edit recipe** para visualizar y editar los datos.  
![Paso 5](img/paso_5.jpeg)  
![Paso 6](img/paso_6.jpeg)

### 6. Limpieza de Datos
Eliminamos datos nulos e inexistentes.  
![Paso 6.4](img/paso_6.4.jpeg)  
![Paso 6.5](img/paso_6.5.jpeg)

### 7. Ejecución del Flujo
Hacemos clic en **Run** y seleccionamos **Create-CSV**.  
![Paso 7](img/paso_7.jpeg)

### 8. Configuración del Output
Seleccionamos **Truncate the table every run**, hacemos clic en **Update** y luego en **Run**.  
![Paso 8](img/paso_8.jpeg)  
![Paso 9](img/paso_9.jpeg)  
![Paso 10](img/paso_10.jpeg)

### 9. Visualización en BigQuery
Hacemos clic en **View on BigQuery**.  
![Paso 11](img/paso_11.jpeg)

### 10. Ejecución de Consultas SQL
Accedemos a la lupa **Query** para ejecutar las consultas.  
![Paso 12](img/paso_12.jpeg)  
![Paso 13](img/paso_13.jpeg)

---

## Visualización en Looker Studio

Luego de ejecutar las consultas SQL, accedemos a **Looker Studio** para visualizar los resultados como gráficos.

### Gráfico de Torta
Cantidad de avistamientos de las 5 formas de objetos más vistas.  
![Gráfico de Torta](img/Mapa_Torta.jpeg)

### Gráfico de Barras
Cantidad de avistamientos por año.  
![Gráfico de Barras](img/Grafico_Barras.jpeg)

### Mapa Global
Cantidad de avistamientos por estado dentro de Estados Unidos.

> **Nota:** Se cambió el dato "State" de tipo texto a tipo "Geo", seleccionando "Country" para que el mapa se limitara a EE.UU.  
![Mapa Global](img/Mapa_Mundo.png)

---

## ¡Gracias por su tiempo!
