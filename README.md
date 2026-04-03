# 🏦Bank Marketing Intelligence: De los Insights a la Predicción de Conversión

## 📌Visión General
Este ecosistema analítico aborda el desafío de las campañas de marketing directo en una institución financiera. El proyecto integra Análisis Exploratorio de Datos (EDA) avanzado con Modelado Predictivo Híbrido (Machine Learning Clásico + Deep Learning) para maximizar la suscripción de depósitos a plazo fijo.

El problema: El marketing telefónico es costoso y tiene bajas tasas de conversión.
La solución: Un motor de segmentación que identifica clientes con alta propensión y define estrategias de contacto óptimas.

## 🛠️Stack Tecnológico y Metodología
El proyecto se divide en dos pilares fundamentales que cubren todo el ciclo de vida del dato:

- 1. Análisis Estratégico e Insights (EDA)
Identificación de variables críticas: Descubrimiento del umbral de 375 segundos en llamadas como predictor clave de éxito.
Segmentación de riqueza: Análisis de la relación entre el balance de cuenta, préstamos hipotecarios y la capacidad de ahorro.
Visualización: Uso de Seaborn y Matplotlib para detectar patrones de comportamiento demográfico.

- 2. Ingeniería de Machine Learning & Deep Learning
Tratamiento de Desbalanceo: Implementación de SMOTE (Synthetic Minority Over-sampling Technique) para manejar el sesgo natural de los datos bancarios.
Random Forest Optimizado: Ajuste de hiperparámetros mediante RandomizedSearchCV.
Redes Neuronales Artificiales (ANN): Arquitectura multicapa desarrollada en Keras/TensorFlow con optimizador Adamax para capturar relaciones no lineales complejas.

Hallazgo Técnico,Recomendación Estratégica,Impacto Esperado

Correlación Duración/Conversión,Implementar guiones dinámicos que superen los 6 min.,+25% en efectividad de cierre.
Perfil de Liquidez,Priorizar clientes con balance medio/alto sin deudas activas.,"Reducción de ""churn"" en llamadas."
Predicción del Modelo,Filtrar la base de contactos mediante el Score de la ANN.,Optimización del tiempo de los operadores en un 40%.


## 🔬Rigor Técnico: Evaluación del Modelo
A diferencia de enfoques básicos, este proyecto pone énfasis en la estabilidad del modelo:
- Validación: Uso de train_test_split con monitoreo de Accuracy vs Epochs para prevenir el sobreajuste (overfitting).
- Escalabilidad: Pipeline preparado para normalización de datos estadísticos (StandardScaler) antes del entrenamiento.

## 🚀Instalación y Ejecución
- Clonar el repositorio.
- Instalar dependencias: pip install pandas scikit-learn tensorflow imbalanced-learn seaborn.
- Ejecutar el pipeline de análisis: python MKTbancario2.py.
- Entrenar el motor predictivo: python MKTbancario1.py.

## 👤Sobre la autora
Flavia Hepp Data Scientist especializado en el sector financiero. 
Mi enfoque combina la precisión técnica de las redes neuronales con una visión estratégica orientada a resultados de negocio y eficiencia operativa.
