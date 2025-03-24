# Tornados en Estados Unidos (1950–2022)

<p align="center">
  <img src="_static/Portada_Tornado.png" alt="Portada Tornado" width="600">
</p>

Desde 1950 hasta 2022, Estados Unidos ha sido escenario de miles de tornados, convirtiéndose en uno de los países más afectados por este tipo de fenómenos meteorológicos extremos. A lo largo de estas más de siete décadas, los tornados han causado estragos tanto en vidas humanas como en la infraestructura económica, dejando una profunda huella en comunidades vulnerables, especialmente en regiones como el llamado "Tornado Alley".

Uno de los aspectos más alarmantes de estos eventos es el impacto económico. De acuerdo con los registros históricos, las pérdidas económicas asociadas a los tornados se cuentan en millones de dólares, con años particularmente devastadores como 2011 y 1974, donde los daños fueron catastróficos tanto por la cantidad de tornados como por su intensidad.

La intensidad de los tornados suele medirse mediante la escala Fujita (F0 a F5), que clasifica los tornados en función de la velocidad del viento y la severidad del daño. En este período, se han documentado tornados de magnitudes extremas (como F4 y F5), capaces de arrasar ciudades enteras, derribar estructuras reforzadas y generar pérdidas humanas y económicas de gran magnitud.

Este contexto justifica la necesidad de aplicar herramientas modernas, como los algoritmos de Machine Learning, para anticipar el impacto de futuros tornados, evaluar su intensidad potencial y estimar los posibles daños económicos, contribuyendo a una mejor gestión del riesgo y preparación ante desastres.

## Aplicación de Machine Learning: CatBoost Regressor para la Predicción de Daños por Tornados

Dado el alto impacto económico y social que los tornados han causado en Estados Unidos desde 1950, surge la necesidad de desarrollar herramientas que permitan predecir con mayor precisión los daños esperados ante futuros eventos. Con el avance de la ciencia de datos y el aprendizaje automático (Machine Learning), es posible construir modelos que analicen patrones históricos para estimar de forma inteligente las consecuencias económicas de los tornados.

En este estudio se implementa el modelo **CatBoost Regressor**, una técnica avanzada de gradient boosting desarrollada por Yandex, diseñada especialmente para trabajar eficientemente con datos tabulares y variables categóricas, sin necesidad de transformaciones complejas. A diferencia de modelos más conocidos como Random Forest o XGBoost, CatBoost ha sido poco explorado en la predicción de daños por tornados, lo que ofrece una oportunidad única para evaluar su desempeño en este tipo de fenómenos meteorológicos.

CatBoost destaca por su capacidad para:

- Manejar automáticamente variables categóricas sin codificación manual,

- Controlar el sobreajuste mediante técnicas de ordenamiento y regularización internas,

- Ofrecer interpretabilidad al mostrar la **importancia relativa de cada variable** en la predicción,

- Y lograr una alta precisión en tareas de regresión, incluso con datos heterogéneos y variables faltantes.

Utilizando como variable objetivo el valor económico de las pérdidas (**loss**), y excluyendo todas las variables de tiempo para evitar sesgos temporales, el modelo se entrena con información estructurada sobre la localización, intensidad (**mag**), y características físicas de los tornados. El objetivo es construir un sistema que permita estimar, con base en los datos iniciales de un tornado, cuál podría ser su impacto económico, ayudando a las autoridades a tomar decisiones proactivas en situaciones de emergencia.

Este enfoque representa un paso adelante hacia la combinación de ciencia climática y analítica predictiva, en busca de soluciones más precisas y basadas en evidencia para la gestión de desastres naturales.

Check out the content pages bundled with this sample book to see more.

```{tableofcontents}
```
