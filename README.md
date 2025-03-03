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

### **Análisis Integrado de la Base de Datos Chinook**  

- **Explicación breve del análisis:**  
  Se implementaron consultas dinámicas para extraer información relevante en tres áreas: análisis de ventas, búsqueda de canciones y análisis de géneros musicales. Cada función permite ajustar los filtros de manera interactiva, lo que facilita obtener insights precisos y visualmente atractivos sobre la base de datos.  

- **Métricas relevantes o hallazgos:**  
  - **Ventas:** Se obtuvieron métricas como total de ventas, promedio por transacción, número de transacciones y top 5 países con mayores ingresos.  
  - **Canciones:** Se analizaron el total de canciones, duración y precio promedio, además de identificar el top 10 de artistas según el número de canciones.  
  - **Géneros Musicales:** Se evaluaron estadísticas por género, identificando el género con mayor número de tracks, mayor duración promedio y precio promedio más alto.  

- **Tablas o valores clave:**  

| Variable         | Métrica 1          | Métrica 2          |
|------------------|--------------------|--------------------|
| Ventas Totales   | XX.XX (monto)      | XX.XX (transacciones) |
| Canciones Totales| XX.XX (duración)   | XX.XX (precio promedio) |

## Conclusión  
✅ **El proyecto demuestra que la implementación de consultas dinámicas en Python facilita el análisis profundo y flexible de la base de datos Chinook, permitiendo extraer insights valiosos a través de filtros ajustables y visualizaciones interactivas.**  

📌 **Se recomienda explorar mejoras en la optimización de las consultas, ampliar las visualizaciones para incluir análisis en tiempo real y considerar la integración de técnicas avanzadas de análisis predictivo para futuras implementaciones.**  
