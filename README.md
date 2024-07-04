# Proyecto-Final-Samsung-Innovation-camp

# Proyecto de Predicción de Morosidad en la Cartera de Créditos

Este proyecto tiene como objetivo predecir la morosidad en una cartera de créditos utilizando diversos modelos de aprendizaje automático. Los modelos utilizados incluyen Random Forest, Redes Neuronales, SVM, Gradient Boosting y KNN. El análisis se basa en datos relacionados con la clasificación del crédito por riesgo, género, localidad y sectores económicos.

## Contenido

- [Descripción](#descripción)
- [Instalación](#instalación)
- [Uso](#uso)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Visualizaciones](#visualizaciones)
- [Contribuciones](#contribuciones)

## Descripción

Este proyecto realiza predicciones sobre la morosidad de créditos utilizando múltiples modelos de machine learning. Además de entrenar y evaluar los modelos, se generan varias visualizaciones para entender mejor las predicciones y la importancia de las características.

## Integrantes del Equipo y Roles
###  Milton García

Papel: Cargar los datos en Pandas DataFrames. Asegurarse de que los datos estén correctamente importados y estructurados para su análisis posterior. Verificar la coherencia y calidad de los datos, especialmente en términos de captaciones y créditos por localidad y género.
### Erick Cuesto

Papel: Explorar los datos para determinar el formato y los atributos necesarios. Evaluar el comportamiento de las captaciones y créditos en diferentes localidades y entre diferentes géneros a lo largo del tiempo, identificando patrones de crecimiento y decrecimiento.
### Haroldy Martínez

Papel: Crear visualizaciones efectivas para representar los datos de inclusión financiera. Graficar captaciones, créditos y operaciones de subagentes bancarios en diferentes localidades, utilizando subplots para comparar múltiples métricas en una sola figura.
### Sebastián Espinal

Papel: Realizar el preprocesado de datos. Identificar y corregir valores faltantes o nulos, asegurándose de que todos los datos estén en el formato correcto para el análisis. Normalizar y estandarizar los datos según sea necesario.
### Madeline Pérez

Papel: Analizar y evaluar las métricas clave de inclusión financiera. Determinar las localidades con mayor y menor acceso a servicios financieros, así como identificar diferencias significativas entre géneros. Evaluar y comparar las métricas de inclusión financiera para hacer recomendaciones específicas.
### TODO EL EQUIPO - Modelado y Análisis Avanzado con IA

Papel: Implementar técnicas de inteligencia artificial para realizar un análisis avanzado de los datos. Utilizar algoritmos de clustering para segmentar localidades según su nivel de inclusión financiera, y técnicas de regresión para identificar factores clave que afectan la inclusión financiera. Desarrollar modelos predictivos para proponer intervenciones específicas.
Tecnología y Herramientas Utilizadas
Lenguaje de Programación: Python
Bibliotecas: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
Frameworks: TensorFlow (para análisis avanzado de IA)
Herramientas de Visualización: Matplotlib, Seaborn
Plataforma de Desarrollo: Jupyter Notebook

## Instalación

1. Clona el repositorio:
    ```sh
    git clone https://github.com/MiltonGarciaP/Proyecto-Final-Samsung-Innovation-camp.git
    ```

2. Navega al directorio del proyecto:
    ```sh
    cd tu-proyecto
    ```

3. Crea y activa un entorno virtual (opcional pero recomendado):
    ```sh
    python -m venv env
    source env/bin/activate  # En Windows usa `env\Scripts\activate`
    ```

4. Instala las dependencias:
    ```sh
    pip install -r requirements.txt
    ```

## Uso

1. Prepara los datos de entrada. Debes tener archivos CSV con la clasificación del crédito por riesgo, género, localidad y sectores económicos.

2. Ejecuta el script principal para entrenar los modelos y generar las visualizaciones:
 

## Estructura del Proyecto

```plaintext
tu-proyecto/
│
├── data/                    # Directorio para los datos de entrada
│   ├── riesgo.csv
│   ├── genero.csv
│   ├── localidad.csv
│   └── sectores.csv
│
├── visualizations/          # Directorio para guardar las visualizaciones generadas
│
├── main.py                  # Script principal para entrenar los modelos y generar visualizaciones
│
├── utils.py                 # Funciones auxiliares para cargar y preprocesar los datos
│
├── models.py                # Definición de los modelos de machine learning
│
├── requirements.txt         # Archivo de dependencias
│
└── README.md                # Este archivo
```

## Visualizaciones

El proyecto genera diversas visualizaciones para entender mejor las predicciones y la importancia de las características. Algunas de las visualizaciones incluyen:

- **Distribución de Predicciones:** Muestra la frecuencia de las predicciones para cada clase.
- **Comparación entre Real y Predicción:** Compara los valores reales con las predicciones.
- **Curva ROC:** Evalúa la tasa de verdaderos positivos frente a la tasa de falsos positivos.
- **Curva de Precisión-Recall:** Muestra la relación entre precisión y recall.
- **Distribución de Probabilidades Predichas:** Visualiza la confiabilidad de las predicciones.
- **Predicciones Correctas e Incorrectas:** Identifica los errores del modelo.
- **Matriz de Confusión:** Ayuda a visualizar los errores de clasificación.
- **Importancia de Características:** Muestra qué características son más importantes para los modelos.

## Contribuciones

¡Las contribuciones son bienvenidas! Si tienes ideas para mejorar el proyecto o encuentras algún error, por favor abre un issue o crea un pull request.

1. Fork el repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commit (`git commit -am 'Añadir nueva funcionalidad'`).
4. Empuja tus cambios a la rama (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request.



