# Análisis de Ventas y Factores de Éxito en Videojuegos

## 📌 Descripción del proyecto
Este proyecto analiza datos históricos de ventas de videojuegos de la tienda online **Ice**, con el objetivo de identificar los factores que influyen en el éxito comercial de un juego.  
El análisis considera variables como plataforma, género, región, reseñas de usuarios y críticos, y clasificación ESRB, tomando como referencia datos disponibles hasta el año 2016 para apoyar la planificación de campañas publicitarias futuras.

---

## 🎯 Objetivos
- Identificar patrones que determinan el éxito comercial de un videojuego.
- Analizar la evolución de ventas por plataforma y género.
- Evaluar el impacto de las reseñas de usuarios y críticos en las ventas.
- Comparar preferencias de consumo entre regiones (NA, UE y JP).
- Validar hipótesis estadísticas relacionadas con calificaciones de usuarios.

---

## 🗂️ Descripción de los datos
El proyecto utiliza un conjunto de datos con información histórica de videojuegos lanzados hasta 2016.

### Columnas principales
- `name`: nombre del videojuego.
- `platform`: plataforma de lanzamiento.
- `year_of_release`: año de lanzamiento.
- `genre`: género del videojuego.
- `na_sales`: ventas en Norteamérica (millones de USD).
- `eu_sales`: ventas en Europa (millones de USD).
- `jp_sales`: ventas en Japón (millones de USD).
- `other_sales`: ventas en otras regiones (millones de USD).
- `critic_score`: calificación de críticos (0–100).
- `user_score`: calificación de usuarios (0–10).
- `rating`: clasificación ESRB.

> Nota: Los datos correspondientes al año 2016 pueden estar incompletos.

---

## 🧪 Metodología

### 1. Exploración inicial
- Revisión de la estructura del dataset.
- Análisis de tipos de datos y valores ausentes.

### 2. Preparación de datos
- Normalización de nombres de columnas.
- Conversión de tipos de datos.
- Tratamiento de valores ausentes y casos especiales como `TBD`.
- Cálculo de las ventas globales por videojuego.

### 3. Análisis exploratorio
- Análisis del número de lanzamientos por año.
- Evaluación del ciclo de vida de las plataformas.
- Identificación de plataformas y géneros líderes en ventas.
- Visualización de distribuciones mediante diagramas de caja.
- Análisis de la relación entre reseñas y ventas usando correlación y gráficos de dispersión.

### 4. Análisis regional
- Identificación de las plataformas más populares por región (NA, UE, JP).
- Análisis de los géneros predominantes en cada región.
- Evaluación del impacto de la clasificación ESRB en las ventas regionales.

### 5. Pruebas de hipótesis
- Comparación de las calificaciones promedio de usuarios entre Xbox One y PC.
- Comparación de las calificaciones promedio entre los géneros Acción y Deportes.
- Definición de hipótesis nula y alternativa.
- Selección y justificación del nivel de significancia (α).

---

## 🛠️ Herramientas utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

---

## 📊 Resultados y conclusiones
El análisis permite identificar plataformas y géneros con mayor potencial comercial, así como diferencias claras en las preferencias de los usuarios según la región.  
Las pruebas estadísticas y el análisis exploratorio proporcionan evidencia sólida para respaldar decisiones estratégicas en campañas de marketing y selección de proyectos prometedores.

---

## 📁 Estructura del repositorio
- `games.csv`: conjunto de datos original.
- `Proyecto - Sprint 6.ipynb`: notebook con el análisis completo.
- `README.md`: documentación del proyecto.

---

## 👤 Autor
Analista de Datos