# Challenge-Telecom-X2

Este proyecto analiza datos de clientes para predecir la **cancelación del servicio** usando distintos modelos de Machine Learning.

##  Objetivo
Identificar factores clave que influyen en la cancelación y construir modelos predictivos que permitan implementar **estrategias de retención**.

##  Tecnologías utilizadas
- Python 3.x
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- imbalanced-learn (SMOTE)


**Preprocesamiento de datos**
   - Eliminación de columnas irrelevantes.
   - Codificación One-Hot para variables categóricas.
   - Balanceo de clases con SMOTE.
   - División train/test (70/30).

2. **Modelos entrenados**
   - Regresión Logística (con normalización)
   - Random Forest (sin normalización)

3. **Evaluación**
   - Accuracy, Precisión, Recall, F1-score
   - Matriz de confusión
   - Importancia de variables (coeficientes y feature_importances_)

4. **Principales hallazgos**
   - Mayor riesgo en clientes con:
     - Contrato mensual
     - Cargos mensuales altos
     - Poco tiempo de antigüedad
     - Pago con Electronic check
     - Sin servicios de soporte o seguridad

5. **Estrategias de retención**
   - Migrar clientes a contratos más largos
   - Ofrecer beneficios iniciales a nuevos clientes
   - Incluir servicios de valor añadido
   - Mejorar experiencia de pago
