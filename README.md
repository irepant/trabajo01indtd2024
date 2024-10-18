# Presentación
 ## Introducción
 Bienvenidos a mi primer trabajo individual de la asignatura Teoría de la Decisión, en el que se han planteado dos problemas de teoría de la decisión bajo incertidumbre que resolveremos con la ayuda de códigos de R.
 ## Metodología
 Las **funciones** que se han utilizado para la resolución de los mismos se encuentran dentro del archivo **teoriadecision_funciones_incertidumbre.R**, incluido dentro de este repositorio. 
 Los problemas se han resuelto para los casos _favorable_ y _desfavorable_, y al final de los mismos se ha especificado la conclusión que obtenemos con cada uno de los métodos utilizados.
 Los métodos empleados han sido los siguientes:

**Wald (Criterio del Pesimista)**: Se elige la opción que maximiza el peor resultado posible, es decir, la que minimiza el riesgo. Es un enfoque conservador.

**Optimista (Criterio de Maximax)**: Se selecciona la opción con el mejor resultado posible, es decir, la que maximiza el mejor resultado. Es el criterio del "mejor de los casos".

**Hurwicz**: Este criterio es un compromiso entre los enfoques pesimista y optimista. Se usa un coeficiente de optimismo para ponderar los mejores y peores resultados de cada opción.

**Savage (Criterio del Minimax)**: Aquí se trata de minimizar el "arrepentimiento", es decir, la diferencia entre lo que se podría haber ganado y lo que realmente se ganó. Se selecciona la opción que minimiza el máximo arrepentimiento. Laplace: Este criterio asume que todas las situaciones son equiprobables y se elige la opción con el mejor promedio de resultados.

**Punto Ideal**: Consiste en seleccionar la opción cuya distancia a un punto ideal (el mejor resultado posible en cada criterio) sea la mínima.
 
