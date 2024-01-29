# Proyecto HTML - CSS

El presente proyecto es la creación de una página web para aplicar los conceptos básicos de HTML y CSS.



### Objetivo

Practicar los conceptos de HTML y CSS para aprobar el filtro de habilidades de desarrollo de software en CampusLands.



#### Índice

1. Creación de la estructura inicial de carpetas, ficheros, paleta de colores y temas del Proyecto
2. Estructura Html de la página web
3. Diseño de las dos primeras secciones de la página web





##### 1. Estructura inicial del proyecto

​	Se crea la estructura de repositorio y ficheros y se agregan las siguientes fuentes:

​	@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

​	font-family: 'Poppins', sans-serif;



##### 2. Estructura Html de la página web

​	Se realiza todo el maquetado html de la página web, la cuál se divide en: 1 Header, 5 Etiquetas section y 1 Footer.



##### 3. Creación de la barra de navegación

Se crea la barra de navegación utilizando Flex para ordenar el nombre de la empresa a la izquierda y los enlaces o navs a la derecha. También se emplea el modelo de caja, específicamente la propiedad position con su valores relative y absolute para generar un efecto de animación al pasar el mouse con el pseudoselector :hover. Por último se establece el color del fondo del body y el header.



##### 4. Diseño de las dos primeras secciones de la página web

Primero, se agrega un div con clase ".rowsContainer" en el html para comprimir el contenido verticalmente en el centro de la página dándole un height del 50% del div padre. Luego, se le asigna un width de 100% al main y se convierte en display tipo flex para centrar todas las secciones dentro de este. Todas las secciones tienen la misma clase y se les da un ancho de 80% centradas horizontalmente.

Se utiliza flex para dividir cada sección en dos mitades: una imagen a un lado y un contenedor con título, párrafo y botón al otro lado de la sección. Finalmente, se le da un formato inicial a cada botón con clase ".buttonLinks" de la página.





























