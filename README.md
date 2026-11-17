# Hola, soy Lucila Pasquetta 👋

Psicóloga y doctoranda en Neurociencias (CONICET) en transición a **ciencia de datos**. Me gusta tomar datos desordenados, entender qué está pasando y convertirlo en algo que otros puedan usar.

- 🎓 Diplomatura en Ciencia de Datos, Aprendizaje Automático y sus Aplicaciones · FAMAF-UNC (Diplodatos)
- 🎓 Diplomatura en Data Science & Machine Learning · ICARO-UNC
- ☁️ [AWS Academy Machine Learning Foundations](https://www.credly.com/badges/ee7cc368-a5fa-4052-b05c-6eea1aaf3083)
- 🔬 Doctoranda en Neurociencias INIMEC-CONICET-UNC: diseño experimental, análisis estadístico y comunicación de resultados
- 📍 Córdoba, Argentina · buscando mi primer rol en datos

---

## 📂 Proyectos

### 🏨 Detector de ofertas hoteleras
Sistema que detecta precios inusualmente bajos en búsquedas de hoteles, con más de 5 millones de búsquedas reales de 2024 y 2025. Lo hicimos en equipo, en la mentoría de Diplodatos.
- Normalización de unos 26.000 nombres de ciudad a destinos únicos
- Detección de anomalías con estadística robusta (z robusto con mediana y MAD) por destino y mes
- Evaluación sin etiquetas, con descuentos simulados y separación temporal (2024 para entrenar, 2025 para testear)
- **F1 0,86 · precisión 99,6% · 0,3% de falsas alarmas**, mejor que Isolation Forest y que una regla de mediana
- Desplegado como API en Docker

`Python` `pandas` `NumPy` `scikit-learn` `Docker`

🔗 [Ver repositorio](LINK)

### 🐭 Tracker de comportamiento en video
Detecté que puntuar a mano los videos de una prueba de comportamiento nos llevaba semanas, así que armé una herramienta para automatizarlo.
- Tracking del animal por sustracción de fondo (visión por computadora clásica, hecha a medida)
- Zonas de la arena marcadas con clics y OCR del reloj impreso en el video para sincronizar los tiempos reales
- Calcula frecuencia, duración y porcentaje de permanencia en cada zona, y exporta a Excel con formato
- Procesa todos los videos en lote: **de semanas de trabajo manual a unas 4 horas de corrida**
- Hoy lo usa mi laboratorio

`Python` `OpenCV` `pytesseract` `pandas` `openpyxl`

🔗 [Ver repositorio](LINK)

### 🎵 Análisis y machine learning con datos de Spotify
Trabajo final de la diplomatura de ICARO: exploración, preparación de datos y modelado de canciones de Spotify.
- Clasificación con Random Forest y redes neuronales (MLP)
- Clustering con K-Means para encontrar grupos de canciones

`Python` `pandas` `scikit-learn` `Matplotlib`

🔗 [Ver repositorio](https://github.com/lucilapasquetta/spotify-explicit-ml)

### 👶 Natalidad en Córdoba y Chaco: 2019 vs. 2023
Análisis exploratorio de las estadísticas de nacimientos de Argentina, comparando Córdoba y Chaco antes y después de la pandemia.
- Control de calidad de los datos: duplicados, faltantes, registros "sin especificar" (<1%) y screening de outliers con IQR
- Indicadores construidos: % de madres adolescentes (<20 años), % de prematuros (<37 semanas) y % de bajo peso al nacer (<2.500 g)
- **Hallazgos:** los nacimientos cayeron alrededor del 25% en ambas provincias. La maternidad adolescente bajó (Chaco: 17,7% → 13,1%; Córdoba: 10,3% → 8,2%), pero el bajo peso al nacer subió, sobre todo en Chaco (8,2% → 9,3%). Chaco muestra mayor vulnerabilidad relativa en ambos años.

`Python` `pandas` `Matplotlib` `Seaborn`

🔗 [Ver repositorio](LINK)

---

## 🛠️ Herramientas

**Lenguajes y librerías:** Python · pandas · NumPy · scikit-learn · XGBoost · Matplotlib · Seaborn · OpenCV
**Machine learning:** clasificación · clustering · detección de anomalías · ajuste de hiperparámetros · clases desbalanceadas
**Estadística:** análisis exploratorio · inferencia paramétrica y no paramétrica · diseño experimental · Statistica · Jamovi
**Entornos:** Jupyter · Google Colab · VS Code
**Aprendiendo:** SQL

Trabajo con herramientas de IA como parte de mi flujo de desarrollo: me ayudan a escribir código más rápido, y la lógica, las decisiones y la validación de cada resultado las hago yo.

---

## 📫 Contacto

[LinkedIn](https://www.linkedin.com/in/lucilapasquetta/) · lucilam.pasquetta@gmail.com
