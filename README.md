# ML Projects

Una colección de proyectos prácticos de Machine Learning que abarca desde conceptos fundamentales hasta técnicas intermedias. Este repositorio contiene laboratorios y ejercicios educativos que exploran diferentes aspectos del análisis de datos, regresión, redes neuronales y métodos de clasificación.

## Descripción General

El repositorio está estructurado como una secuencia de aprendizaje progresivo, comenzando con manipulación de datos usando pandas, continuando con técnicas de regresión (lineal y multivariada), y finalizando con arquitecturas más complejas como redes neuronales y máquinas de soporte vectorial (SVM). Cada proyecto incluye explicaciones teóricas, implementación práctica y visualización de resultados.

---

## 📁 Proyectos

### 0. 🐧 **Análisis Exploratorio - Dataset Penguins**
   - **Archivo:** `00_penguins_dataset.ipynb`
   - **Contenido:** Proyecto completo de análisis exploratorio de datos (EDA) y pruebas estadísticas
   - **Dataset:** Palmer Penguins (datos de 3 especies de pingüinos de la Antártida)
   - **Estructura del Proyecto:**
     1. **Exploración General:** Especies, características, valores faltantes
     2. **Limpieza de Datos:** Estrategias para manejar datos incompletos
     3. **Análisis Geográfico:** Distribución por islas y desbalance de clases
     4. **Análisis Descriptivo:** Medidas de tendencia central y dispersión por especie y sexo
     5. **Visualización:** Distribuciones, boxplots, gráficos de dispersión
     6. **Correlación:** Relaciones entre características (pico vs. masa corporal, etc.)
     7. **Hipótesis Estadísticas:** Tests formales para validar correlaciones observadas
   - **Habilidades Practicadas:**
     - Análisis descriptivo estadístico
     - Visualización de datos con múltiples dimensiones
     - Tests de correlación
     - Pruebas de hipótesis formales
   - **Enfoque:** Pedagógico y completo, guía paso a paso
   - **Complejidad:** Básica a Intermedia

---

### 1. 📈 **Uso de Pandas y Series de Tiempo**
   - **Archivo:** `01_pandas_time_series.ipynb`
   - **Contenido:** Caso de uso de la manipulación de datos con pandas usando un dataset de series de tiempo real
   - **Tema Específico:** Análisis de datos históricos EUR/USD con frecuencia horaria (05/07/2022 - 12/05/2023)
   - **Habilidades Practicadas:**
     - Carga de datos desde GitHub
     - Manipulación de índices (set_index)
     - Análisis descriptivo (info, describe)
     - Visualización de series de tiempo
     - Operaciones con DataFrames (filtrado, transformación)
   - **Dataset:** Precios EUR/USD con atributos de apertura, cierre, máximo, mínimo, volumen y spread
   - **Complejidad:** Básica

---

### 2. 📉 **Regresión Lineal y Descenso de Gradiente**
   - **Archivo:** `02_reg_lin_grad_desc.ipynb`
   - **Contenido:** Implementación desde cero de regresión lineal y optimización mediante descenso de gradiente
   - **Conceptos Teóricos:**
     - Función de coste (cost function)
     - Descenso de gradiente básico
     - Cálculo vectorizado de derivadas
     - Visualización de convergencia
   - **Habilidades Practicadas:**
     - Programación de algoritmos de optimización
     - Análisis gráfico de la optimización
     - Comparación de métodos numéricos
   - **Complejidad:** Básica a Intermedia

---

### 3. 📉 **Regresión Multivariada**
   - **Archivo:** `03_reg_multivariada.ipynb`
   - **Contenido:** Extensión de regresión lineal a múltiples variables con cálculos vectorizados
   - **Tema Específico:** Ajuste de planos multidimensionales en el espacio
   - **Conceptos Clave:**
     - Regresión con múltiples características (x₁, x₂, ..., xₙ)
     - Cálculos vectorizados con NumPy
     - Validación de parámetros optimizados
     - Visualización en 3D
   - **Objetivo de Aprendizaje:** Encontrar parámetros θ₀, θ₁, θ₂ que minimicen el error cuadrático medio
   - **Complejidad:** Intermedia

---

### 4. 🏠 **Análisis Predictivo - Housing California**
   - **Archivo:** `04_ABC_modelo.ipynb`
   - **Contenido:** Análisis completo de un modelo predictivo usando el dataset de casas de California
   - **Dataset:** California Housing (Censo de 1990)
   - **Características del Problema:**
     - **Objetivo:** Predicción del valor mediano de viviendas (median_house_value)
     - **Variables Predictoras:** Longitud, latitud, edad, habitaciones, dormitorios, población, hogares, ingreso medio
     - **Tamaño:** Datos a nivel de distritos de California
   - **Etapas del Proyecto:**
     - Exploración y limpieza de datos
     - Análisis descriptivo y visualización
     - Ingeniería de características
     - Entrenamiento y evaluación de modelos
     - Análisis de resultados
   - **Habilidades:** Análisis exploratorio (EDA), preprocesamiento, modelado predictivo
   - **Complejidad:** Intermedia

---

### 5. 🧠 **Redes Neuronales desde Cero**
   - **Archivo:** `05_nn_zero.ipynb`
   - **Contenido:** Implementación manual de redes neuronales sin librerías de ML avanzadas
   - **Conceptos Fundamentales:**
     - Arquitectura de redes neuronales (capas de entrada, ocultas, salida)
     - Propagación hacia adelante (forward propagation)
     - Propagación hacia atrás (backpropagation)
     - Funciones de activación
     - Cálculo vectorizado de operaciones de redes
   - **Teoría Matemática:**
     - Matrices de pesos (Θ) y sesgos (b)
     - Operaciones matriciales para m muestras de entrenamiento
     - Expresiones compactas de cálculo vectorizado
     - Dimensiones de matrices para cada capa
   - **Objetivo:** Comprender los mecanismos internos de las redes neuronales
   - **Complejidad:** Intermedia

---

### 6. ⚙️ **Redes Neuronales con Keras**
   - **Archivo:** `06_nn_keras.ipynb`
   - **Contenido:** Implementación práctica de redes neuronales usando la librería Keras de TensorFlow
   - **Dataset de Ejemplo:** Make Moons (problema de clasificación no lineal)
   - **Etapas del Proyecto:**
     - Generación y preparación de datos sintéticos
     - División train/test y escalado de características
     - Construcción de modelos secuenciales con Keras
     - Entrenamiento y validación de modelos
     - Análisis de matrices de confusión
   - **Técnicas Aplicadas:**
     - Normalización de datos (StandardScaler)
     - Arquitecturas multidimensionales
     - Métricas de evaluación (confusion matrix, accuracy)
   - **Librería:** TensorFlow/Keras
   - **Complejidad:** Intermedia

---

### 7. 🎪 **Máquinas de Soporte Vectorial (SVM)**
   - **Archivo:** `07_SVM.ipynb`
   - **Contenido:** Implementación y optimización de SVM para clasificación en múltiples escenarios
   - **Datasets Utilizados:**
     - **Make Moons:** Datos de dos medias lunas no lineales (300 muestras)
     - **Make Circles:** Datos circulares concéntricos (300 muestras)
     - **Make Blobs:** Cúmulos de puntos bien separados (300 muestras)
   - **Técnicas de Optimización:**
     - Grid Search para búsqueda de hiperparámetros
     - Ajuste de kernel (RBF, polinómico, sigmoide, lineal)
     - Optimización de parámetros C y gamma
   - **Análisis:** Comparación de desempeño en diferentes tipos de datos
   - **Complejidad:** Intermedia

---

## 🛠️ Tecnologías y Librerías Utilizadas

- **Lenguaje:** Python 3
- **Manipulación de Datos:** Pandas, NumPy
- **Visualización:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn, TensorFlow/Keras
- **Álgebra Lineal:** NumPy (operaciones matriciales)
- **Estadística:** SciPy, Seaborn

## 🎯 Objetivos Educativos

1. **Dominar técnicas fundamentales de ML:** desde manipulación de datos hasta modelado
2. **Comprender algoritmos desde cero:** implementaciones manuales sin dependencias ocultas
3. **Aplicar técnicas prácticas:** usando librerías modernas (Keras, Scikit-learn)
4. **Análisis de datos real:** proyectos con datasets del mundo real y sintéticos
5. **Validación estadística:** pruebas de hipótesis e interpretación de resultados




## 💡 Notas

- Algunos notebooks cargan datos directamente desde repositorios GitHub
- Se recomienda ejecutar los notebooks en orden para seguir la progresión de aprendizaje
- Cada proyecto es independiente, pero construyen sobre conceptos previos
- Los ejercicios están diseñados con propósitos educativos y pueden ser extendidos

---

**Última actualización:** Diciembre 2024