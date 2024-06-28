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
- [Licencia](#licencia)

## Descripción

Este proyecto realiza predicciones sobre la morosidad de créditos utilizando múltiples modelos de machine learning. Además de entrenar y evaluar los modelos, se generan varias visualizaciones para entender mejor las predicciones y la importancia de las características.

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



