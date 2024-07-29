# Clasificando el Dataset Automobile con Distintos Modelos de Regresión 
El dataset Automobile es un conjunto de datos de Regresion clásico y muy sencillo. Creado por Jeffrey Schlimmer el 5/18/1987.
Este conjunto de datos consta de tres tipos de entidades: (a) la especificación de un automóvil en términos de diversas características, (b) su calificación de riesgo de seguro asignada, (c) sus pérdidas normalizadas en uso en comparación con otros automóviles. La segunda calificación corresponde al grado en que el auto es más riesgoso de lo que indica su precio. Inicialmente a los automóviles se les asigna un símbolo de factor de riesgo asociado con su precio. Luego, si es más arriesgado (o menos), este símbolo se ajusta moviéndolo hacia arriba (o hacia abajo) en la escala. Los actuarios llaman a este proceso "simbolización". Un valor de +3 indica que el automóvil es riesgoso, -3 que probablemente sea bastante seguro.

El tercer factor es el pago medio relativo por pérdida por año de vehículo asegurado. Este valor está normalizado para todos los automóviles dentro de una clasificación de tamaño particular (pequeños de dos puertas, camionetas, deportivos/especiales, etc.) y representa la pérdida promedio por automóvil por año.

Tras realizar un análisis exploratorio de datos para comprender mejor la información. En este notebook se construye un modelos de Regresión, que utiliza las características para clasificar el precio de los automobiles con un máximo de precisión.
***
Paquetes utilizados:
* Procesamiento de datos: Pandas.
* Procesamiento numérico: NumPy.
* Visualización de datos: Seaborn y Matplotlib.
* Desarrollo del Modelo: Scikit Learn
---
Realizado por:
Nicolás Pécora - Estudiante de la técnicatura de Ciencia de Datos e IA.

* GitHub: https://github.com/nicolasPecora
* LinkedIn: https://github.com/nicolasPecora
