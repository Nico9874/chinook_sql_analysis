# Ejercicio de Query Dinámicas en Python con Base de Datos Chinook

## Descripción  
Este proyecto se centra en el desarrollo de consultas dinámicas en Python para el análisis de la base de datos **Chinook**. Se han implementado funciones que permiten filtrar y analizar datos en tres ámbitos principales:  

- **Análisis de Ventas:** Filtrado por año, país y monto mínimo, con agrupación por mes para evaluar la tendencia de ventas.  
- **Búsqueda de Canciones:** Consultas dinámicas que permiten buscar canciones según género, duración y nombre del artista.  
- **Análisis de Géneros Musicales:** Evaluación de la distribución de tracks, duración promedio y precio promedio por género, con filtros opcionales para identificar géneros destacados.  

## Tecnologías utilizadas  
- **Lenguaje / Framework:** Python  
- **Librerías o paquetes clave:**  
  - `pandas`: Manipulación y análisis de datos  
  - `sqlite3`: Conexión con la base de datos Chinook  
  - `matplotlib`, `seaborn`: Visualización de datos  
- **Algoritmos o modelos utilizados:**  
  - Consultas dinámicas para filtrar datos  
  - Agrupación y agregación de datos  
  - Generación de visualizaciones y estadísticas descriptivas  

## Resultados clave  

### **Análisis de Ventas**  
- **Consultas SQL dinámicas:** Se implementaron filtros flexibles para consultar ventas por **año, país y monto mínimo**.  
- **Generación de gráficos:** Se crearon visualizaciones de la tendencia de ventas mensuales y distribución de ventas por país.  
- **Estadísticas extraídas:** Se calcularon métricas como total de ventas y número de transacciones sin necesidad de definir valores específicos en el código.  

### **Búsqueda de Canciones**  
- **Implementación de una query flexible:** Se desarrollaron funciones en Python para buscar canciones por **género, duración y artista** sin necesidad de modificar la estructura de la base de datos.  
- **Visualizaciones generadas:** Histogramas de distribución de duraciones, gráficos de top artistas y análisis de precios por género.  
- **Estadísticas extraídas:** Se calcularon métricas como cantidad total de canciones y promedio de duración de cada género.  

### **Análisis de Géneros Musicales**  
- **Consultas estructuradas:** Se analizaron los géneros musicales en términos de número de tracks, duración y precios.  
- **Gráficos clave:** Se visualizaron comparaciones entre géneros para detectar tendencias.  
- **Insights obtenidos:** Se identificaron los géneros con más canciones, mayor duración promedio y mayor precio sin necesidad de definir valores manualmente.  

## Conclusión  
✅ **El proyecto permitió desarrollar consultas dinámicas en SQL dentro de Python para analizar la base de datos Chinook sin requerir valores fijos en el código. Se logró flexibilidad en la extracción de datos y generación de gráficos clave.**  

📌 **Se recomienda explorar la optimización de consultas y ampliar la visualización con dashboards interactivos para una mejor exploración de los datos.**  
