# Programa de método de relajación para resolución de la ecuación de Laplace
Programa diseñado en python para resolver la ecuación de Laplace en una caja bidimensional con potencial conocido en la frontera de la región.

## Descripción
Este programa hace uso del método de relajación para dar una solución númerica a la ecuación de Laplace para el caso 2D en coordenadas cartesianas, la cual describe el comportamiento del potencial eléctrico en un electrostático sin cargas. 

## Instalación
Será necesario realizar la instalaciónd de las librerias matplotlib.pyplot y numpy. Esto se puede hacer en la terminal con el comando pip install y el nombre de la libreria, como se presenta en el ejemplo:

pip install numpy matplotlib

## Uso
Ejecutar cada bloque de código con ctrl+enter o por medio de el botón en la interfaz de jupiternotebook. No será necesario introducir ningún valor, pues todo se encuentra desntro del código. Además, el código esta documentado de forma que se entienda la utilidad de cada función. 

## Ejemplos
Aquí se presentan ejemplos de los resultados para el programa. 

1. Para el potencial que se obtiene, se espera un array.
[[-1.          0.          0.         ...  0.          0.
   1.        ]
 [-1.         -0.49808095 -0.29853765 ...  0.29851527  0.49808095
   1.        ]
 [-1.         -0.69383107 -0.49241319 ...  0.49236879  0.69383107
   1.        ]
 ...
 [-1.         -0.6941385  -0.49302024 ...  0.49298085  0.6941385
   1.        ]
 [-1.         -0.4982452  -0.29886194 ...  0.2988423   0.4982452
   1.        ]
 [-1.          0.          0.         ...  0.          0.
   1.        ]]

