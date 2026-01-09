# Detección de Transacciones Fraudulentas

## Descripción del proyecto
Este proyecto tiene como objetivo desarrollar un modelo predictivo para la detección de transacciones fraudulentas en el contexto de una institución financiera. El fraude representa un problema crítico debido a su bajo nivel de ocurrencia y alto impacto económico.

## Objetivo
Desarrollar y comparar modelos de machine learning para la detección de transacciones fraudulentas, abordando el problema como una tarea de clasificación desbalanceada.

## Metodología
Se realizó un análisis exploratorio de los datos y un proceso de limpieza y preparación, incluyendo el tratamiento del desbalance de clases. Posteriormente, se entrenaron y compararon distintos modelos de machine learning, entre ellos Logistic Regression, SVM, Decision Tree, Random Forest, XGBoost, LightGBM y Red Neuronal (MLPClassifier).

## Evaluación
Los modelos fueron evaluados utilizando métricas adecuadas para problemas desbalanceados, tales como AUPRC, Precision, Recall y F1-score.

## Resultados
El modelo con mejor desempeño fue Random Forest, alcanzando un AUPRC de 0.84, una precisión de 94.8% y un recall de 77.7%, evidenciando un equilibrio robusto entre detección de fraudes y control de falsos positivos.

## Tecnologías utilizadas
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib/Seaborn

## Estructura del repositorio
- `informe/`: análisis exploratorio, modelado y predicción, mencionando el porqué se tomaron aquellas decisiones
- `code/`: funciones y scripts principales  
- `README.md`: documentación del proyecto

## Conclusiones
Este proyecto demuestra la aplicación de técnicas de machine learning para la detección de fraude, destacando la importancia de seleccionar métricas adecuadas y modelos robustos en escenarios con clases altamente desbalanceadas.
