<div id="header" align="center">
  <img decoding="async" src="https://github.com/user-attachments/assets/35c54477-66c5-4222-8eff-53aec2ab719a"
    <img width="800" height="503" alt="image"/>
</div>

## Proyectos de Ciencia de Datos del Bootcamp Tripleten 🎓

✨ ¡Hola! Qué gusto tenerte por aquí explorando mi portafolio de proyectos en ciencia de datos. 🚀
Este espacio reúne el trabajo que he realizado durante mi formación en el bootcamp de data science, donde me sumergí en distintos retos y casos prácticos. Cada proyecto refleja mi entusiasmo por descubrir patrones, aplicar técnicas de machine learning y contar historias a través de visualizaciones claras. ¡Espero que disfrutes el recorrido tanto como yo disfruté construirlo!

## 📂 Lista de Proyectos

---

1. [🎮 Análisis de Ventas de Videojuegos – Tienda Online Ice](https://github.com/SucoJavi/Desarrollo-de-Software-tripleten/blob/main/Proyecto_Tienda_Online_Ice_Videojuegos.ipynb)

  Este proyecto analiza datos históricos de ventas de videojuegos de la tienda online **Ice**, con el objetivo de identificar patrones de éxito que permitan predecir qué juegos tienen mayor probabilidad de triunfar en el mercado. El análisis se basa en reseñas de usuarios y expertos, plataformas, géneros y ventas regionales.

## 🎯 Objetivo

Analizar datos históricos de videojuegos para:
- Identificar factores que influyen en el éxito comercial de un juego.
- Comparar el desempeño de plataformas y géneros.
- Evaluar la relación entre calificaciones y ventas.
- Apoyar la toma de decisiones para campañas publicitarias y planificación de lanzamientos.

## ❓ Problema a Resolver

La tienda Ice necesita anticipar qué videojuegos tendrán mayor demanda para optimizar sus inversiones en marketing.  
El reto consiste en trabajar con datos históricos incompletos y heterogéneos para extraer conclusiones confiables sobre:
- Plataformas más rentables
- Géneros con mejor desempeño
- Impacto de las reseñas en las ventas
- Diferencias regionales en el mercado de videojuegos

## 🧰 Herramientas y Tecnologías Utilizadas

- **Lenguaje:** Python  
- **Entorno:** Jupyter Notebook  
- **Librerías:**
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scipy.stats

## 🔍 Metodología y Enfoque

1. Carga y exploración inicial de los datos
2. Limpieza y preparación del dataset:
   - Corrección de nombres de columnas
   - Conversión de tipos de datos
   - Tratamiento de valores ausentes
3. Análisis exploratorio de datos (EDA):
   - Distribución de ventas por año
   - Comparación de plataformas y géneros
   - Análisis de reseñas de usuarios y críticos
4. Análisis estadístico:
   - Pruebas de hipótesis para comparar plataformas
5. Visualización de resultados para facilitar la interpretación

## ⚙️ Desarrollo de la Solución

Se utilizó un enfoque exploratorio apoyado en visualizaciones y estadísticas descriptivas para identificar tendencias clave.  
Posteriormente, se aplicaron pruebas estadísticas para validar hipótesis relacionadas con:
- Diferencias en calificaciones entre plataformas
- Relación entre reseñas y volumen de ventas

Este enfoque permitió transformar datos históricos en información accionable para el negocio.

## 📈 Resultados y Conclusiones

- Se identificaron plataformas y géneros dominantes en distintos períodos.
- Las reseñas de expertos muestran mayor correlación con las ventas que las reseñas de usuarios.
- Existen diferencias estadísticamente significativas entre plataformas en cuanto a calificaciones.
- El análisis confirma que los datos históricos pueden utilizarse para mejorar decisiones comerciales.

## 🚀 Posibles Mejoras Futuras

- Incorporar modelos predictivos de Machine Learning.
- Analizar datos más recientes o en tiempo real.
- Considerar variables adicionales como presupuesto de marketing.
- Crear un dashboard interactivo para seguimiento continuo.

---

2. [🚖 Análisis de Viajes en Taxi y Efecto del Clima – Zuber (Chicago)]((https://github.com/SucoJavi/Desarrollo-de-Software-tripleten/blob/main/Proyecto_Comparaci%C3%B3n_Musical.ipynb)

Este proyecto analiza datos históricos de viajes en taxi en la ciudad de Chicago para identificar patrones de comportamiento de los pasajeros y evaluar el impacto de factores externos, como el clima, en la duración de los viajes. El estudio se realiza como apoyo analítico para **Zuber**, una nueva empresa de viajes compartidos que busca ingresar al mercado.


## 🎯 Objetivo

- Analizar el comportamiento de los viajes en taxi en Chicago.
- Identificar las empresas y barrios con mayor volumen de viajes.
- Evaluar si las condiciones climáticas influyen significativamente en la duración de los viajes.
- Validar hipótesis mediante métodos estadísticos.


## ❓ Problema a Resolver

Zuber necesita comprender cómo se comporta el mercado de taxis antes de su lanzamiento, especialmente:
- Qué compañías concentran mayor número de viajes.
- En qué barrios se registran más finalizaciones.
- Si el clima afecta de forma significativa la experiencia del viaje.

El desafío principal consiste en integrar múltiples fuentes de datos y aplicar análisis estadístico para obtener conclusiones confiables.


## 🧰 Herramientas y Tecnologías Utilizadas

- **Lenguaje:** Python  
- **Entorno:** Jupyter Notebook  
- **Librerías:**
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scipy.stats


## 🔍 Metodología y Enfoque

1. Exploración inicial de los datos provenientes de consultas SQL.
2. Limpieza y validación de tipos de datos.
3. Análisis exploratorio (EDA):
   - Comparación de compañías de taxi según número de viajes.
   - Identificación de los 10 barrios con mayor número de viajes finalizados.
4. Visualización de datos para facilitar la interpretación.
5. Prueba de hipótesis estadística para evaluar el impacto del clima.


## ⚙️ Desarrollo de la Solución

Se realizó un análisis exploratorio apoyado en gráficos para identificar patrones clave en los datos.  
Posteriormente, se formuló una hipótesis sobre la diferencia en la duración de los viajes bajo condiciones climáticas lluviosas versus buen clima.

Para validar esta hipótesis:
- Se evaluó la igualdad de varianzas utilizando la prueba de **Levene**.
- Se aplicó una prueba estadística para determinar si las diferencias observadas eran significativas.


## 📈 Resultados y Conclusiones

- Se identificaron compañías y barrios con mayor volumen de viajes.
- El análisis estadístico mostró que **existen diferencias significativas en la duración de los viajes cuando el clima es lluvioso en comparación con cuando el clima es favorable**.
- El clima es un factor externo relevante que debe considerarse en la planificación operativa y estratégica.


## 🚀 Posibles Mejoras Futuras

- Incorporar modelos predictivos para estimar la duración de viajes.
- Analizar datos en diferentes estaciones del año.
- Integrar variables adicionales como tráfico o eventos urbanos.
- Crear dashboards interactivos para monitoreo en tiempo real.

---


2. [Comparación Musical: Análisis de Hábitos de Escucha](https://github.com/SucoJavi/Desarrollo-de-Software-tripleten/blob/main/Proyecto_Comparaci%C3%B3n_Musical.ipynb)

  **Descripción:** Análisis comparativo de preferencias musicales entre diferentes grupos de usuarios.

  **Tecnologías:** Python, Pandas.

3. [Instacart: Predicción de Compras Futuras](https://github.com/SucoJavi/Desarrollo-de-Software-tripleten/blob/main/Proyecto_Instacart_Llena_ese_Carrito.ipynb)

  **Descripción:** Modelo predictivo para recomendar productos en función de compras pasadas.

  **Tecnologías:** Python, Pandas, TensorFlow.

4. [Megaline: Análisis de Rentabilidad](https://github.com/SucoJavi/Desarrollo-de-Software-tripleten/blob/main/Proyecto_Mejor_Tarifa_Megaline.ipynb)

  **Descripción:** Estudio de rentabilidad de servicios de telecomunicaciones basados en datos históricos de clientes.

  **Tecnologías:** Python, Seaborn, Pandas.


5. [Film Junky Union: Clasificación de Sentimiento](https://github.com/SucoJavi/Desarrollo-de-Software-tripleten/blob/main/Proyecto_Film_Junky_Union_clasificacion_de_sentimiento.ipynb)

  **Descripción:** Desarrollo de un sistema para filtrar y categorizar reseñas de películas mediante técnicas de procesamiento de lenguaje natural (NLP).

  **Tecnologías:** Python, Pandas, Scikit-learn, NLP.



