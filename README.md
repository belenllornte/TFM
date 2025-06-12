**Interpretabilidad de Redes Neuronales**

Este repositorio contiene el Trabajo de Fin de Máster (TFM) titulado "Interpretabilidad de Redes Neuronales", centrado en el análisis y evaluación de modelos de machine learning aplicados a un problema de riesgo crediticio.

📁 **Estructura del repositorio***
credit_risk_dataset.csv: Dataset utilizado para entrenar y evaluar los modelos. Contiene información relacionada con el riesgo crediticio de distintos individuos.
mejor_modelo_mlp.pkl: Modelo MLP (Perceptrón Multicapa) previamente entrenado y guardado. Fue seleccionado como el mejor modelo tras una comparativa basada en la métrica F1 Score.
notebooks/: Contiene el notebook utilizado durante el desarrollo del TFM, incluyendo la exploración de datos, entrenamiento de modelos y análisis de interpretabilidad.

🧠 **Objetivo**
El objetivo principal de este proyecto es explorar técnicas de interpretabilidad en redes neuronales, especialmente en contextos donde la transparencia del modelo es crítica, como en la evaluación del riesgo crediticio.

⚙️ **Modelado**
Se compararon distintos modelos de clasificación (árboles de decisión, random forest, SVM, MLP, etc.) utilizando validación cruzada y métricas como precisión, recall y F1 Score. El modelo MLP con mejor F1 Score fue seleccionado y guardado como mejor_modelo_mlp.pkl para evitar repetir el proceso de entrenamiento en cada ejecución.

🧪 **Interpretabilidad**
Se aplicó una técnica local: LIME(Local Interpretable Model-agnostic Explanations).
