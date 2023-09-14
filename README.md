# Clasificación del Sueño con Modelos de Aprendizaje Automático 🌙

## Introducción

En este proyecto, exploramos y analizamos diferentes modelos de aprendizaje automático para clasificar el sueño entre las fases REM y noREM. Utilizamos datos de señales EEG y EMG para entrenar y evaluar nuestros modelos.

## Objetivo

El objetivo principal de este proyecto es desarrollar modelos de clasificación de sueño precisos y comprender qué variables influyen en la predicción de la fase del sueño.

## Técnicas Utilizadas

En este proyecto, nos centramos en el uso de modelos interpretables, es decir, modelos que se pueden comprender y explicar de manera clara. La elección de modelos interpretables es crucial en aplicaciones médicas, ya que permite a los profesionales de la salud entender el razonamiento detrás de las predicciones y tomar decisiones informadas.

## Resultados Clave

- Hemos utilizado tres tipos de modelos principales: Regresión Logística, Random Forest y Reglas (CBA).

- El modelo Random Forest alcanzó una precisión de aproximadamente 94% en la clasificación del sueño, con una sensibilidad alta (98.9%) pero una especificidad menor (66.4%).

- Identificamos que las variables relacionadas con la desviación estándar de los canales son cruciales en la clasificación, especialmente en el modelo Random Forest.

- Observamos interacciones interesantes entre las variables de desviación estándar del canal O1 y los electromiogramas.

- Utilizamos técnicas como LIME y Shapley para interpretar los modelos a nivel local y entender cómo afectan las variables a las predicciones.

## Conclusiones y Potencial Social

En este proyecto, hemos logrado desarrollar modelos de aprendizaje automático precisos para la clasificación del sueño. Estos modelos tienen el potencial de ser utilizados en aplicaciones médicas para ayudar en la evaluación de pacientes con trastornos del sueño.

Además, hemos demostrado la importancia de utilizar modelos interpretables en aplicaciones de salud, ya que permiten una toma de decisiones más informada y transparente.

En resumen, este proyecto representa un paso importante hacia la mejora de la clasificación del sueño y el apoyo a los profesionales de la salud en su trabajo diario.


