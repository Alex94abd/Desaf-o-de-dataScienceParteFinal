# Desaf-o-de-dataScienceParteFinal
Corresponde al desafío challeger Telecom X II Alura latam 
Telecom X – Predicción de Abandono de Clientes (Churn)

📌 Resumen del Proyecto

Este proyecto analiza el comportamiento de abandono de los clientes de Telecom X y desarrolla modelos predictivos para identificar a aquellos usuarios que están en riesgo de cancelar su servicio.

El objetivo principal es transformar datos brutos en estrategias de retención e insights de negocio accionables.

🛠 Tecnologías Utilizadas

Python: El lenguaje de programación principal para el análisis.

Pandas: Para la manipulación y limpieza de estructuras de datos.

NumPy: Para el soporte de cálculos numéricos y operaciones con matrices.

Matplotlib: Para la creación de visualizaciones estáticas.

Seaborn: Para visualizaciones de datos estadísticos más avanzadas y estéticas.

Scikit-learn: La librería fundamental para implementar los algoritmos de Machine Learning.

Imbalanced-learn (SMOTE): Herramienta especializada en el manejo de datos desequilibrados (crucial para balancear los casos de clientes que se van frente a los que se quedan).

🔎 Flujo de Trabajo del Proyecto
Limpieza y Normalización de Datos: Tratamiento de valores nulos y escalado de variables.

Ingeniería de Características (Feature Engineering): Creación y transformación de variables para mejorar el modelo.

Manejo de Desequilibrio de Clases: Ajuste de los datos para que el modelo aprenda a identificar correctamente la minoría (los que cancelan).

División de Entrenamiento y Prueba (Train/Test Split): Separación de datos para validar el rendimiento.

Entrenamiento del Modelo: Aplicación de algoritmos de aprendizaje automático.

Evaluación del Modelo: Medición del éxito mediante métricas estadísticas.

Insights de Negocio y Estrategia de Retención: Traducción de resultados en decisiones comerciales.

🤖 Modelos Implementados

Regresión Logística: Para establecer una línea base de clasificación.

Random Forest (Bosque Aleatorio): Para capturar relaciones complejas y mejorar la precisión.

📈 Métricas de Evaluación

Exactitud (Accuracy): Porcentaje total de predicciones correctas.

Precisión (Precision): Calidad de las predicciones positivas.

Sensibilidad (Recall): Capacidad del modelo para encontrar a todos los clientes en riesgo.

Puntuación F1 (F1-score): El equilibrio entre Precisión y Recall.

Matriz de Confusión: Visualización de los aciertos y errores del modelo.

🔥 Hallazgos Clave

Los contratos mensuales aumentan significativamente el riesgo de abandono.

Los clientes con baja antigüedad (tenure) tienen más probabilidades de cancelar.

Los cargos mensuales elevados guardan una correlación directa con el churn.

La contratación de servicios adicionales reduce la probabilidad de cancelación.

💡 Impacto en el Negocio

Este modelo permite ejecutar estrategias proactivas de prevención de abandono, tales como:

Campañas de intervención temprana: Identificar al cliente antes de que decida irse.

Ofertas de retención personalizadas: Descuentos o beneficios basados en el perfil del usuario.

Estrategias de optimización de contratos: Incentivos para migrar a clientes de planes mensuales a planes anuales.

🎯 Resultado Final

Este proyecto demuestra:

✅ Limpieza de datos reales

✅ Feature engineering

✅ Manejo de desbalance

✅ Modelado comparativo

✅ Evaluación rigurosa

✅ Interpretabilidad

✅ Traducción de resultados a estrategia de negocio

✅ Preparación profesional para entrevista
