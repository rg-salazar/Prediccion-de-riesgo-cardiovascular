# Predicción de riesgo cardiovascular
Aplicar herramientas de explicabilidad de modelos, específicamente LIME y SHAP, para analizar y justificar el comportamiento de un modelo de clasificación.



# Interpretabilidad de Modelos Predictivos con LIME y SHAP

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge&logo=xgboost&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-29B6F6?style=for-the-badge)
![LIME](https://img.shields.io/badge/LIME-76B041?style=for-the-badge)

## 🎯 Objetivo
Aplicar herramientas de explicabilidad de modelos para analizar y justificar el comportamiento de un modelo de clasificación, garantizando que las decisiones puedan ser comprendidas por personas no técnicas (clientes, médicos, auditores, usuarios finales).

## 📚 Contexto
Este proyecto simula ser parte de un equipo de ciencia de datos que utiliza inteligencia artificial para decisiones críticas. La prioridad no es solo construir un modelo preciso, sino también explicable, ético y responsable.


## 🔹 Pasos realizados

### 1. Carga y exploración del dataset
- Limpieza mínima de datos: eliminación de valores nulos, corrección de tipos de datos.
- Exploración de variables relevantes.
- Identificación de posibles variables sensibles (ej. género, edad, etnia).

### 2. Construcción del modelo predictivo
- División del dataset en entrenamiento y prueba.
- Entrenamiento de modelo de clasificación (Random Forest, XGBoost o Logistic Regression).
- Evaluación del modelo usando métricas: Accuracy y F1-score.

### 3. Aplicación de SHAP
- Explicaciones individuales de 3 casos seleccionados.
- Gráficos globales: Summary plot, Bar plot y Waterfall plot.
- Interpretación de la influencia de cada variable y patrones emergentes.

### 4. Aplicación de LIME
- Explicaciones locales para los mismos 3 casos analizados con SHAP.
- Comparación de similitudes y diferencias con SHAP.

### 5. Análisis de sesgo y ética
- Identificación de variables sensibles con posible peso injustificado.
- Propuestas para mitigar sesgos detectados.
- Evaluación de riesgos si no se aplicara interpretabilidad.

### 6. Propuesta de mejora
- Ajustes en el modelo o preprocesamiento para decisiones más responsables.
- Consideraciones de cambio de algoritmo, limpieza de variables o nuevas estrategias de feature engineering.

## 📈 Resultados esperados
- Modelo de clasificación preciso y explicable.
- Casos individuales interpretables mediante LIME y SHAP.
- Reporte sobre posibles sesgos y decisiones éticas críticas.

## ⚡ Uso
1. Clonar el repositorio:

git clone https://github.com/usuario/interpretabilidad-modelos.git


