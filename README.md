# Template Portafolio Personal.

![Foto Portada](https://github.com/user-attachments/assets/01bb4d6e-1b46-4b89-8917-3e7326e695ec)



## Índice. :clipboard:

1. Descripción del proyecto.
2. Acceso al proyecto.
3. Demostración de funciones y aplicaciones.
4. Técnicas y tecnologías utilizadas.
5. Colaboradores del proyecto
6. Desarrollador del proyecto

## 1. Descripción del proyecto. :books:

Este proyecto consiste en el desarrollo de una página web personal con un diseño moderno, armonioso y completamente responsivo, garantizando una óptima experiencia de usuario en dispositivos móviles, tabletas y computadoras de escritorio.<br>

La estructura del sitio ha sido concebida como un prototipo flexible y personalizable, permitiendo a los usuarios modificar fácilmente la información y los enlaces a sus redes sociales. Su propósito es servir como una tarjeta de presentación digital, ideal para profesionales, freelancers o cualquier persona que desee compartir su perfil de manera elegante y accesible.<br>

Con una interfaz intuitiva y una estética cuidadosamente seleccionada, esta página web proporciona una plataforma eficiente para destacar la identidad digital del usuario, facilitando su conexión con potenciales contactos, clientes o colaboradores.

## 2. Acceso al proyecto. :open_file_folder:

Para acceder al proyecto puedes hacerlo de dos maneras sencillas:

- Opción 1: Clonar utilizando Git

  Desde tu linea de comandos puedes seleccionar el directorio donde deseas descargar el proyecto y ejecutar el siguiente comando:

  `git clone https://github.com/ignaciomajo/template-portafolio-web`

Este comando hará una copia de todos los archivos necesarios para utilizar el proyecto.

- Opción 2: Descargar ZIP

  Si no deseas usar la linea de comando, puedes dirigirte a la URL del proyecto: https://github.com/ignaciomajo/template-portafolio-web

  En la esquina superior derecha veras la sección `<> Code`, haz clic en dicho menu y veras la opción `Descargar ZIP`

Luego, dirígete al directorio donde has decidido clonar o descargar el archivo zip y deberías contar con los siguientes archivos:

![repositorio-template](https://github.com/user-attachments/assets/4877cc47-a655-434b-9061-b02edf4d8b1d)

Una vez realizado estos pasos, podras acceder a los archivos utilizando un editor de texto como **Visual Studio Code** para modificar el template y desarrollar tu proyecto personal.

## 3. Demostración de funciones y aplicaciones. :memo:

### Demostración de funciones.

Al abrir el archivo `index.html`, tu navegador te llevara a la siguiente pantalla:

![pantalla-inicial](https://github.com/user-attachments/assets/b535fb71-a544-4b66-9f03-ffa7b05be7b2)

En la imagen a continuación se muestran las distintas funcionalidades de la pantalla principal:

![presentación-proyecto](https://github.com/user-attachments/assets/e3eab74a-d24a-452a-9bd3-c8fd2d64e265)

Al presionar sobre el enlace `Sobre mí`, serás redireccionado a la siguiente pagina:

![sobre-mi](https://github.com/user-attachments/assets/c77568b2-7ddc-4556-bd58-e045ee3f2b87)

### Aplicaciones

Como se dijo anteriormente este proyecto es un template para que puedas desarrollar tu propia página web personal.

A continuación detallaré algunos pasos para que puedas completar tu información y utilice esta plantilla como proyecto propio.

#### - :arrow_down: REQUISITOS PREVIOS:

Para la demostración de dichos pasos, utilizaré `Visual Studio Code`.

Si aún no lo tienes instalado en tu ordenador puedes descargarlo desde: https://code.visualstudio.com/download

O si lo deseas, puedes utilizar un editor de texto con el que estés familiarizado/a.

**CONTENIDO PAGINA "HOME"**:

![index-html](https://github.com/user-attachments/assets/b438b917-0345-4bb4-80ac-f916f4ce8432)

Como puede verse a la izquierda de la imagen, cada línea de código tiene un número de referencia. Utilizaré esto para indicar las modificaciones a realizar:

**- Línea 6:** 

`<title> </title>` Aquí se puede ver el texto: "Portafolio - Home". Este texto es el nombre de la página, es decir, si vemos el navegador, el nombre de la pestaña.

Puedes modificarlo para que aparezca tu nombre (solo debes modificar el texto)

Ejemplo:

`<title> Portafolio de (Tu Nombre) </title>`

**- Línea 18 a 21:**

Todo lo que se encuentra entre `<h1> </h1>` es el encabezado de tu página principal. Dentro de la misma, lo que se encuentre entre `<strong> </strong>` será lo que cambie de color.

Aquí también solo debes modificar el texto.

Ejemplo:

`<h1 class="presentacion__contenido__titulo">
Este será el encabezado de
<strong class="titulo-destaque"> Mi Portafolio </strong>`

"Mi Portafolio" cambiará de color, el resto permanecerá en blanco.

**- Línea 22 a 25:**

Todo lo que se encuentre entre `<p> </p>` sera la breve descripción de la página principal.
Modifica solo el texto como se ha hecho anteriormente.

**- Línea 26 a 34:**

Esta sección corresponde a los enlaces a tus redes sociales.

Cada enlace está delimitado por `<a> </a>`.

* La propiedad `href="URL"` debe contener la dirección URL de la red social a la cual quieres que se dirija el usuario al presionar el enlace.

* La propiedad `src=./assets/nombre-imagen.png` hace referencia al logo de la red social a la que estarás direccionando al usuario. Dentro de la carpeta assets encontrarás algunos íconos que podrían serte útiles.

* Antes de `</a>` debes ingresar el nombre de la red social a la cual corresponde dicho enlace.

*Nota:*

Puedes agregar más enlaces o eliminar alguno si lo necesitas.

* Para agregar más enlaces copia un bloque completo `<a> </a>` (corresponde a dos lineas, por ejemplo: 28 y 29) y agrégalo debajo del último bloque de este estilo. Luego modifica las propiedades mencionadas anteriormente.

* Para eliminar un enlace, simplemente borra un bloque completo `<a> </a>`.

**- Línea 36:**

Esta línea corresponde a la imagen que quieras que aparezca en tu pagina web. Para esto, agrega la imagen a la carpeta assets:file_folder:.

* Modifica la propiedad `src="./assets/Imagen.png"` de la siguiente manera: `src=".assets/nombre-de-la-imagen.extension`

* La propiedad `alt=" "` es importante para la accesibilidad. Desarrolla una breve descripción de la imagen seleccionada.

**- Línea 39:**

Aquí puedes modificar el texto con tu nombre para denotar que has sido tú quien ha desarrollado tu página web. Puedes agregar otro tipo de información si así lo deseas.


**CONTENIDO PAGINA "SOBRE MI"**

![about-html](https://github.com/user-attachments/assets/360ce4dc-719f-4777-a538-480c334b4524)

Esta página corresponde a una descripción sobre ti, tu trayectoria y proyección a futuro, o cualquier información que quieras compartir con los visitantes de tu sitio web.

La distribución de la información está dividida en dos párrafos.

En ambos casos solo necesitas modificar lo que se encuentra entre `<p> </p>`

**- Línea 19 a 23:** Primer párrafo

**- Línea 24 a 31:** Segundo párrafo

**- Línea 34:** Aqui deberías copiar el mismo texto que has puesto en la **Línea 39** de la página principal.


## 4. Técnicas y tecnologías utilizadas. :hammer_and_wrench:

En este proyecto se utilizaron las siguientes tecnologías:

* `Visual Studio Code`
* `ChatGPT (generación de imagen de portada)`
* `HTML-5`
* `CSS-3`
* `Git y GitHub`

## 5. Colaboradores del proyecto. :building_construction:

Quiero agradecer a:

### Oracle
![oracle](https://github.com/user-attachments/assets/53352188-89c8-4a95-ae9b-2d3ee0e6042d)

### Alura LATAM
![alura-latam](https://github.com/user-attachments/assets/74c370e4-08c8-41d4-b352-93022125e5ba)

Este proyecto ha sido posible gracias a estás dos grandes empresas que juntas han desarrollado el programa **Orcale Next Education** con el objetivo de capacitar a los trabajadores del futuro.

![one](https://github.com/user-attachments/assets/a443b508-9c77-4f6b-a1e0-bbba3a6988d8)

## 6. Desarrollador del proyecto. :construction_worker:

![imagen-readme](https://github.com/user-attachments/assets/e73fef5a-4eac-4f3b-8c29-533bb15d4512)


**| Ignacio Majo | Data Scientist Jr. |**




