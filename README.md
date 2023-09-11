# Análisis y Mejora de Modelo de Predicción de BMI
Este repositorio contiene un proyecto de análisis y mejora de un modelo de predicción de índice de masa corporal (BMI) utilizando técnicas de aprendizaje automático. El objetivo principal es evaluar el rendimiento de un modelo de red neuronal profunda en función de su complejidad y, posteriormente, aplicar técnicas de ajuste de hiperparámetros para mejorar su precisión.

## Descripción del Proyecto

El índice de masa corporal (BMI) es un indicador ampliamente utilizado de la salud y el bienestar de una persona. En este proyecto, utilizamos datos de altura, peso y género para predecir el BMI de una persona mediante el uso de redes neuronales profundas.

El proceso general del proyecto incluye:

1. **Preparación de Datos:** Cargamos y preparamos los datos desde un archivo CSV. Realizamos ingeniería de características, incluida la conversión de variables categóricas en variables ficticias.

2. **División de Datos:** Dividimos los datos en conjuntos de entrenamiento y prueba para evaluar el rendimiento del modelo en datos no vistos.

3. **Modelo de Red Neuronal:** Implementamos una red neuronal profunda utilizando TensorFlow y Keras. Experimentamos con diferentes configuraciones de capas y neuronas para comprender el impacto en el rendimiento del modelo.

4. **Diagnóstico de Sesgo y Varianza:** Evaluamos el sesgo y la varianza del modelo mediante gráficos informativos y análisis de errores en los conjuntos de entrenamiento y prueba.

5. **Optimización de Hiperparámetros:** Utilizamos GridSearchCV para encontrar la mejor configuración de hiperparámetros que evite el subajuste y el sobreajuste.

## Estructura del Repositorio
- `bmi.csv`: Conjunto de datos de altura, peso, género e índice de masa corporal.
- `ANN_for_BMI.py`: Cuaderno Jupyter con el código completo y comentarios detallados.

## Requisitos
- Python 3.x
- Bibliotecas de Python: NumPy, pandas, matplotlib, scikit-learn, TensorFlow, Keras.

## Instrucciones de Uso
1. Clona este repositorio en tu máquina local.
2. Ejecuta el cuaderno `ANN_for_BMI.py` para explorar el análisis y la mejora del modelo.

## Resultados
Después de implementar la técnica de GridSearch para el ajuste del modelo, encontramos la mejor configuración de la red neuronal que evita el subajuste y el sobreajuste. Esta configuración proporciona un error cuadrado medio de aproximadamente 59.765 en el conjunto de prueba.

## Licencia
Este proyecto está bajo la Licencia de Código Abierto CC0 1.0 Universal (CC0 1.0). Puedes utilizar, modificar y compartir este código libremente.

---

**Iván L. Hernández Buda**  
[LinkedIn](https://www.linkedin.com/in/ivanbuda) | [GitHub](https://github.com/IvanHBuda)
