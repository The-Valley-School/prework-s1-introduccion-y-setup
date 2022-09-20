[Diapositivas](/resources)
***

Antes de ponernos a programar, vamos a hacer una pequeña introducción para entender bien cómo funciona una web y a su vez, ir viendo unos conceptos generales que nos van servir para ir cogiendo el vocabulario y jerga de este mundillo.

No os asustéis viéndome usar una presentación, a lo largo del curso vamos a tener las mínimas posibles, siempre estaremos trabajando en nuestro entorno de desarrollo, pero creo que es importante, y sobre todo en esta lección, dejar claros los conceptos.

**CLIENTE / SERVIDOR**

Quiero explicaros primero como funciona una web a muy alto nivel. ¿Qué es eso de cliente / servidor? 

Imaginaos que queremos entrar en en una página web, por ejemplo, thevalley.es.

- Tenemos por un lado el **cliente**  que es el usuario que querrá acceder a esa página web, y por otro, el **servidor web** donde se aloje. Cuando accedemos a una web, esa web tiene imágenes, vídeos y demás recursos, que tienen que estar guardados en algún lado. Y es así, están guardados en otro ordenador, que es el que hace de servidor web. Esos ordenadores tienen muchas características y están personalizados, pero no dejan de ser ordenadores.

- Entonces, nos encontramos con un **cliente** que tiene que pedir al servidor una web para poder visualizar el contenido. Esta dirección web o dominio, se traduce en una dirección IP (una dirección IP es un código único para identificar la web) la cual nos sirve para identificar nuestra web dentro del servidor.

- Es decir, un cliente, a la hora de entrar a una web, lo que hace es una petición a un servidor para recibir la información necesaria.

- Esta información se agrupa. Muchas veces es necesario que el servidor consulte datos, como puede ser un listado de clientes, que estarán en una base de datos.

- Una vez agrupada, se envía al **cliente.** A través de un protocolo HTTP/HTTPS, un protocolo para la comunicación de esa información en páginas web.

- Ya solo quedaría que el navegador de la parte cliente, procesase esa información para poder visualizarla. Por lo general, recibiremos archivos HTML, CSS y JAVASCRIPT.
    - Archivos HTML son los archivos de estructura de la web
    - Archivos CSS son archivos de estilo que utilizamos para dar formato a las webs
    - Archivos JS que son utilizados para todo lo que tiene que ver con la lógica e interacción en la web.

**FRONT-END / BACK-END / FULL-STACK**

Una vez entendido como funciona a alto nivel una web y con este diagrama que tenemos, podemos resolver las preguntas de , ¿qué significa Front-end? ¿Back-End? y ¿Full-Stack?. Seguro que a lo largo de la búsqueda de este Máster, te has topado con estas palabras infinidad de veces. Vamos a resumir su significado y nos va ayudar a dar paso a entender que es una web:

- Un **desarrollador Front-End** es el encargado, mediante el desarrollo de código interpretado por el navegador ( HTML, CSS, JS), de crear la parte visual de una web, la parte **cliente**. No confundir con un diseñador, estamos hablando de desarrollar el código de ese diseño. Las bases de cada uno de estos lenguajes de programación las veremos en el prework. Front-End por lo tanto, es el encargado de realizar esa petición y procesar la respuesta.

- Un **desarrollador Back-End** es el encargado de procesar esa respuesta y devolver la información que necesita la parte cliente.

- Un **desarrollador Full-Stack** sería el desarrollador que podría cubrir ambos lados.
