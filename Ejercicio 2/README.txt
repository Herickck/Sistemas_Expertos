Venta de Libros

El codigo llamdo "ventaslibros" identifica las ventas en un periodo de 24 horas de los diferentes libros que tiene la empresa por lo cual existe dos bases de datos con la lista de los IDs en una se encuentran los libros vendidos en un periodo de 24 horas y en otra se encuentra el catalogo completo de los libros en existencia que la empresa tiene.

Para el correcto funcionamiento del codigo se debe tomar en cuenta:

1- Importar la libreria de TIME, la cual funcionara como cronometro para determinar que codigo es el mas optimo de todos.
2- Importar la libreria de PANDAS, la cual nos puede funcinar para cargar la data o facilitar algunas operaciones.
3- Importar la libreria de NUMPY, la cual nos puede funcinar para cargar la data o facilitar algunas operaciones.

En el presente codigo se muestran:

1- La primera solucion utilizando solamente la codificación de python en el cual se utiliza un FOR para que cada uno de los libros almacenados dentro de la base de datos llamada "libros_24_meses.txt" se comparen con los libros que se encuentra dentro de la base de datos llamada "catalogo_libros.txt" y asi poder obtener la cantidad de los libros que se han vendido en 24 horas.

2- Se muestra una segunda solución en la cual se utiliza la libreria NUMPY y un comando de la propia liberiaria que facilita la comparación de las dos bases de datos.

3- Y una tercera solución en la cual es necesario cargar leer las bases de datos con la libreria PANDAS para su correcto funcionamiento.