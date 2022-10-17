
>[DIAPOSITIVAS](S1-recursos/setup-macos.pdf)

---

Antes de comenzar a desarrollar, es necesario preparar nuestro entorno de trabajo con las herramientas que vamos a necesitar. Para poder realizar el prework con éxito va a ser necesario:

- Instalar Chrome
- Instalar Visual Studio Code
- Instalar GIT
- Crear una cuenta en GitHub y configurar la clave SSH

 

## INSTALACIÓN CHROME

La primera instalación dentro de este Setup para Mac va a ser el navegador web, en este caso chrome. Os recomendamos usar chrome a lo largo del curso ya que es con el que nosotros trabajamos en los videos.

Antes de empezar a instalar nuestro navegador tenemos que tener bien claro que es:

 


> Un navegador web es un sw, aplicación o programa que nos va a permitir 
acceder a una web, interpretando la información de distintos tipos de 
archivos para que puedan ser vistios.

  

Seguramente ya estés trabajando con Chrome, y es que más del 65% de los usuarios lo utilizan a la hora de navegar por sus sitios web preferidos, si no es así, sigue estos pasos para instalarlo.

Lo primero que haremos será acceder al siguiente enlace a través de nuestro navegador por defecto, que seguramente sea Safari:

 


https://www.google.com/intl/es_es/chrome/


 

Una vez accedamos tenemos un botón bien grande que pone **Descargar Chrome.** Directamente nos reconoce la versión que tiene que descargar sobre nuestro ordenador así que le damos directamente al botón descarga.

Una vez se descargue, tendréis que acceder a la carpeta de descargas de vuestro ordenador (en caso de que hayáis cambiado la ruta en la cual se descarga, ir a esa)

Pulsamos dos veces sobre el archivo y seguimos los pasos de instalación, una vez terminado ya tenemos instalado nuestro navegador.

Más allá de ser el navegador más usado a nivel mundial, chrome nos va a permitir instalar una serie de extensiones que permitirán agregar funcionalidades muy interesantes que iremos viendo e instalando a lo largo del curso.

## INSTALACIÓN VISUAL STUDIO CODE

Vamos ahora a instalar Visual Studio Code, que va a ser nuestro entorno de trabajo.

 


>Un IDE es un entorno de trabajo donde vamos a poder escribir 
y desarrollar nuestro código. Cuenta con una interfaz gráfica que nos 
facilitará la tarea

   

IDEs de desarrollo hay muchos, y más si hablamos de los diferentes lenguajes de programación. En nuestro caso, el que más se adapta a los lenguajes que vamos a utilizar, como es JS,  es Visual Studio Code.

Para instalarlo en Mac iremos paso a paso. 

Lo primero es abrir nuestro navegador Chrome que acabamos de instalar e ir al enlace siguiente:

 


https://code.visualstudio.com/

   

Descargaremos la última versión estable, pulsando sobre el botón de descarga. Existen también versiones Insiders con las últimas novedades, una versión beta con los nuevos desarrollos que van introduciendo. Estas versiones todavía no son estables así que nosotros en todos los programas que utilicemos iremos siempre a descargar las versiones estables.

Una vez descargada seguimos todos los pasos de instalación y ya lo tendríamos.

Quedaría meter la aplicación dentro de la carpeta aplicaciones.

Vamos ahora a instalar una serie de extensiones que nos van a hacer la vida más fácil a la hora de trabajar con VSC. Van a permitir formatear código, mostrarnos ayudas y un montón de cosas más.

- La primera extensión nos va a ayudar a poner el idioma de VSC en español, para ello pulsamos el icono de extensiones (uno que parece una pieza de tetris).  Buscamos Spanish language Pack y la instalamos. Nos pedirá reiniciar el navegador.

 


https://marketplace.visualstudio.com/items?itemName=MS-CEINTL.vscode-language-pack-es


   

- La segunda es Material Icon Theme que va a permitirnos poner iconos a todos los archivos y carpetas que creemos lo que nos facilitará de manera visual dividir nuestro proyecto.

 


https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme


   

Hay un montón de extensiones más que iremos utilizando a lo largo del Máster, conforme las necesitemos las iremos instalando.

## INSTALACIÓN DE GIT

El siguiente paso del setup es la instalación de GIT. GIT va a ser el controlador de versiones de nuestros proyectos.

Imagina que estás trabajando en un equipo de trabajo con varios desarrolladores y cada uno de ellos tiene el código de proyecto en su ordenador. A la hora de unificar esos códigos sería un quebradero de cabeza y daría muchos problemas. Cada desarrollador tendría versiones diferentes del mismo fichero, diferentes estructuras, vamos, un caos.

GIT surge para poder trabajar de manera unificada. A lo largo del prework tendremos sesiones en las que explicaremos como trabajar con GIT, de momento vamos a instalarlo.

La instalación en mac es muy sencilla.

Accedemos a la terminal. La terminal es una interfaz gráfica que lo que va a hacer es permitirnos ,a través de diferentes comandos, decirle al sistema que ejecute diferentes acciones.

Para instalar git tenemos que poner el comando:

 

```bash
git --version
```

  

El objetivo de este comando es que el sistema nos diga la versión que tenemos instalada de GIT, al no tener ninguna nos recomienda instalarlo. Pulsamos en instalar, seguimos los pasos y ya lo tendríamos.

Tras la instalación, verificamos si se ha instalado bien poniendo otra vez el comando:

 

```bash
git --version
```

  

Quedaría únicamente configurar el **usuario** y la **dirección de correo electrónico,** esto es importante porque nos va a servir para identificar el usuario que realizó los cambios en el documento cuando trabajemos en equipo. 

 

```bash
git config --global user.name "Edu Cuadrado"
git config --global user.email "ecuadradoruiz@gmail.com"
```

  

No te asustes si te está sonando a chino todo, ya verás como cuando vaya avanzando el curso empezará todo a tener sentido.

## CUENTA GITHUB

Para finalizar el setup ya solo nos quedaría abrir una cuenta en GitHub y crear nuestra clave SSH.

GitHub tiene como objetivo el poder guardar nuestro código desarrollado, de esta forma podremos compartirlo con nuestros compañeros y profesores. A su vez, nos servirá cuando estemos trabajando con otras personas en un mismo proyecto.

Para crearnos una cuenta, lo primero que tendremos que hacer es acceder a la web, pulsar sobre registro y rellenar el formulario:

 

```bash
https://github.com/
```

  

Iremos completando las opciones que nos indican, seleccionando el plan free y terminando el registro.

Una vez completado el registro lo que vamos a hacer es crear nuestra clave ssh que va a permitir una conexión segura entre el GitHub y nuestro ordenador.

Abrimos GIT Bash e introducimos el siguiente comando:

 

```bash
ssh-keygen -t ed25519 -C "email@example.com"
```

 

Una vez generado, lo copiamos en el portapapeles con el siguiente comando.:

  

```bash
pbcopy < ~/.ssh/id_ed25519.pub
```

 

Nos vamos ahora a nuestro GitHub, pulsamos sobre nuestro perfil, SSH and GPC Keys y añadimos una nueva ssh key con el título de nuestro dispositivo y pegamos la clave.

Ya nos quedaría únicamente probar la conexión, para ello seguimos la guía de GitHub Docs

  

```bash
https://docs.github.com/es/authentication/connecting-to-github-with-ssh/testing-your-ssh-connection
```

 

Abrimos Git Bash e introducimos el siguiente comando

   

```bash
$ ssh -T git@github.com
```

  

Tras ello escribimos   yes  y si está bien configurada nos tendría que salir el siguiente mensaje:

```bash
Hi *username*! You've successfully authenticated, but GitHub does not provide 
shell access.  
```

  

¡Con esto ya tendríamos preparado nuestro entorno preparado para el prework!
