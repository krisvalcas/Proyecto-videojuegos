# 🎮 Análisis de Tendencias en la Industria de Videojuegos

## Resumen del Proyecto

Este proyecto analiza un conjunto de datos históricos de ventas de videojuegos para la tienda online "Ice". El objetivo es identificar patrones y factores que determinan el éxito de un videojuego. Los insights extraídos servirán para planificar campañas publicitarias y tomar decisiones estratégicas para el año siguiente.

---

### 🎯 Objetivos del Análisis

* Analizar la distribución de lanzamientos de juegos a lo largo de los años.
* Identificar las plataformas con mayores ventas históricas y las que son más prometedoras.
* Determinar los géneros de videojuegos más rentables a nivel global.
* Evaluar si las calificaciones de los usuarios y de la crítica profesional impactan en las ventas.
* Probar hipótesis sobre las diferencias en las calificaciones de usuarios entre distintas plataformas y géneros.

---

### 🔧 Metodología

1.  [cite_start]**Preparación de Datos:** Se estandarizaron los nombres de las columnas, se convirtieron tipos de datos, y se manejaron valores ausentes en columnas críticas como `critic_score` y `user_score`[cite: 3]. Se calculó una columna de ventas totales sumando las ventas de todas las regiones.
2.  **Análisis Exploratorio de Datos (EDA):** Se investigaron las ventas por plataforma, género y calificación, identificando las tendencias más significativas a lo largo del tiempo.
3.  **Análisis de Perfiles Regionales:** Se identificaron las 5 plataformas y géneros principales para cada región (Norteamérica, Europa y Japón) y se analizó el impacto de la clasificación ESRB en las ventas de cada una.
4.  **Pruebas de Hipótesis Estadísticas:** Se utilizaron pruebas t de muestras independientes para verificar dos hipótesis clave:
    * Las calificaciones promedio de los usuarios para las plataformas Xbox One y PC son iguales.
    * Las calificaciones promedio de los usuarios para los géneros Acción y Deportes son diferentes.

---

### 🛠️ Tecnologías Utilizadas

* **Lenguaje:** Python
* **Librerías:**
    * **Pandas:** Para la limpieza y análisis de datos.
    * **Matplotlib:** Para la creación de gráficos y visualizaciones.
    * **SciPy (stats):** Para realizar las pruebas de hipótesis estadísticas.
    * **Jupyter Notebook:** Como entorno de análisis.

---

### 💡 Resultados y Conclusiones Clave

* [cite_start]**Ciclo de Vida de las Plataformas:** Se observó que la vida útil promedio de una plataforma de videojuegos es de aproximadamente 10 años, con un pico de lanzamientos y ventas a mitad de su ciclo[cite: 3].
* **Plataformas Líderes:** Plataformas como PS2, Xbox 360, y PS3 dominaron las ventas históricas. [cite_start]Sin embargo, para el período más reciente, PS4 y Xbox One emergieron como las líderes del mercado[cite: 3].
* [cite_start]**Géneros más Rentables:** Los géneros de Acción, Deportes y Disparos (Shooter) son consistentemente los más vendidos a nivel global[cite: 3].
* **Impacto de las Calificaciones:** Se encontró una correlación positiva, aunque no muy fuerte, entre las calificaciones de la crítica y las ventas. La correlación con las calificaciones de los usuarios fue aún más débil.
* **Resultados de Hipótesis:**
    * [cite_start]No se pudo rechazar la hipótesis nula de que las calificaciones de usuarios de Xbox One y PC son iguales[cite: 3].
    * [cite_start]Se rechazó la hipótesis nula, concluyendo que las calificaciones de usuarios para los géneros de Acción y Deportes son estadísticamente diferentes[cite: 3].
