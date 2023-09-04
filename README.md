<h1> SUPERSTORE </h1>

Un responsable de ventas quiere tener un seguimiento general de la empresa, especialmente del funcionamiento de las ventas y saber detectar si ocurre alguna situación anómala. Para ello, hemos creado un dashboard genérico con tres componentes principales: las ventas, la cuantía y el beneficio.

<p align="center">
  <img src="https://github.com/RHCarrasco/Superstore/assets/122986919/b3722898-0fcb-459d-90f7-1c7bd8b410a1">
</p>

Cada uno de estos tres componentes lo hemos dividido en cuatro secciones. La primera nos indica el valor total actual, la segunda es una tendencia del componente desde que existen datos hasta la actualidad, tras esto nos encontramos un gráfico de barras que muestra el valor total para cada región y por último nos encontramos un mapa coroplético para conocer la distribución de los valores.

Para explicarlos individualmente, nos centraremos en las ventas, pero el uso es idéntico para la cuantía y los beneficios.

Para la tendencia de ventas decidimos usar un gráfico de líneas, puesto que con él se ve bastante claro la tendencia en los datos a intervalos iguales. Además de esto, el tooltip muestra el mes y el año, los ingresos generados por las ventas en ese momento y el crecimiento porcentual respecto al mes anterior.

<p align="center">
  <img src="https://github.com/RHCarrasco/Superstore/assets/122986919/6b647ca1-c5c5-46de-93d5-417fa2d46f1b">
</p>

Para poder comparar las ventas por regiones se decidió hacer uso de un gráfico de barras, que es muy útil a la hora de comparar elementos individuales. De un vistazo podemos ver cuál de las 4 regiones es la que más ingresos genera y cuál es la que menos.

<p align="center">
  <img src="https://github.com/RHCarrasco/Superstore/assets/122986919/dd879e2f-447b-4ad7-9fa9-021d2e45e2b5">
</p>

Como queríamos conocer el funcionamiento de nuestra tienda a lo largo del país, pensamos que sería buena idea no solo fijarnos en las regiones, si no también hacer una comparativa por estados. Para esto hemos utilizado un mapa de coropletas, que muestra los distintos estados coloreados en relación con los ingresos generados por las ventas.

Buscando dar algo más de información a nuestro director, se ha modificado el tooltip para que muestre el nombre del estado, los ingresos generados por las ventas en este y las 5 ciudades con mayores ingresos en dicho estado. Con esto esperamos que se pueda ver en qué lugares funcionan mejor las tiendas y quizá abrir nuevos establecimientos basados en estos datos.

<p align="center">
  <img src="https://github.com/RHCarrasco/Superstore/assets/122986919/b86eaddc-b7ee-4291-8ffe-b370e31e23c3">
</p>

Mediante los datos mostrados en este dashboard esperamos cubrir elementos básicos que todo responsable de ventas debe conocer, como por ejemplo las ventas realizadas, los ingresos, los beneficios, en qué lugares se ha obtenido más o menos beneficio, dónde se ha vendido más y dónde menos o si existe alguna anomalía en la evolución de estas ventas. Pero aun así opinamos que hay datos que también son relevantes y no se muestran, o que tal vez, en algunos casos deberían tener un mayor grado de detalle y por ello decidimos realizar una segundo dashboard con un nivel más de detalle.

<p align="center">
  <img src="https://github.com/RHCarrasco/Superstore/assets/122986919/10af56d4-b9d7-4277-b799-6152b96dcf28">
</p>

En este segundo dashboard podemos ver que hay un diagrama de barras con información relativa a las ventas por subcategorías. De nuevo, podemos ver de un simple vistazo cuáles son las subcategorías que mejor funcionan en el negocio. Como hemos mencionado anteriormente creemos que el director de ventas también debe saber cuáles son los productos que más ingresos generan y por ello hemos incluido en el tooltip de esta grafica el top 10 de estos productos.

<p align="center">
  <img src="https://github.com/RHCarrasco/Superstore/assets/122986919/078c8a3e-b6d6-4fa4-a3a7-8c2c9f42329a">
</p>

Buscando ese mayor grado de detalle del que hablábamos anteriormente, realizamos el siguiente diagrama de tendencia. En él se muestra la variación mensual de las ventas para el año actual. Creemos que resultaría interesante poder estudiar de este modo como se esta desarrollando nuestra empresa este año. Además, hemos mostrado con distintos colores el pico y el valle de estas ventas, para poder reconocerlas con rapidez y como sucedía en la grafica de tendencias del dashboard principal, también mostramos en el tooltip la evolución porcentual respecto al mes anterior.

<p align="center">
  <img src="https://github.com/RHCarrasco/Superstore/assets/122986919/f7f00e07-cba2-43bb-97b6-d62ebf89d72c">
</p>

Por último, se incluye un gráfico de barras para que el director pueda estudiar los beneficios y las perdidas existentes. Para ello se muestran las ventas por categoría y subcategoría, acompañadas de los valores de los descuentos y del beneficio.
Opinamos que era importante mostrar los valores de los descuentos en esta tabla puesto que, por ejemplo, para el caso de las mesas, los ingresos por ventas son muy elevados y sin embargo se muestra un beneficio negativo. Esto es debido a que existe un descuento muy grande aplicado y si no vemos ese dato, podría dar lugar a confusiones.

Con estos datos, el director de ventas debería ser capaz de tomar distintas decisiones estratégicas para el negocio. Cabe destacar como último detalle antes de concluir, que todas las gráficas actúan como filtro ante el resto de graficas de su mismo dashboard, por lo que podremos tener más información en muchos casos.


