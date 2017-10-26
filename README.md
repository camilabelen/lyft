# Lyft

* **Track:** _Common Core_
* **Curso:** _Creando tu primer sitio web interactivo_
* **Unidad:** _Maquetado web con HTML & CSS_

***

Para completar este reto, hemos creado este repositorio boilerplate (plantilla
inicial) con todos los recursos que necesitas. Esto incluye imágenes y
estructura de carpetas y archivos donde colocarás tu código.

## Flujo de trabajo

1. Debes realizar un [**fork**](https://gist.github.com/ivandevp/1de47ae69a5e139a6622d78c882e1f74)
   de este repositorio.

2. Luego deberás **clonar** tu fork en tu máquina. Recuerda que el comando a usar
   es `git clone` y su estructura normalmente se ve así:

   ```bash
   git clone https://github.com/<nombre-de-usuario>/lyft.git
   ```

## Objetivo

El reto consiste en replicar el sitio de **Lyft**, este será el resultado
a lograr:

![Lyft Website](docs/fullpage.png)

## Consideraciones

* Encontrarás un archivo base `index.html` en el cual deberás escribir la
  estructura de tu proyecto y enlazar tus archivos de estilos (CSS).

* En la carpeta `css` tendrás un archivo base `main.css` donde agregarás los
  estilos necesarios para tu proyecto:

* Dentro de la carpeta `assets` se encuentra la carpeta `images` donde
  encontrarás todas las imágenes necesarias para completar tu proyecto.

* Deberás **actualizar el archivo `README.md`** explicando el contenido de tu
  repositorio.

* Esta web utiliza la tipografía `Montserrat`.

* La paleta de colores puedes obtenerla inspeccionado el sitio original, pero
  para ganar tiempo, puedes usar los siguientes:

  - Botones, hover: `#FF00BF`
  - Fondo de `footer`: `#333447`
  - Título del formulario: `#352384`
  - Texto del formulario: `#728099`
  - Gradiente morado: `linear-gradient(#76278F, #2B1E66);`

* Para el footer, deberás tomar en cuenta que tiene un hover y se ve como en la
  siguiente imagen:

  ![Lyft - Footer](docs/footer.gif)

  Además, los íconos deberás obtenerlo de `Icomoon`.

* Para este reto, encontrarás ciertas cosas que probablemente aun no has visto
  en clase (formularios, videos de Youtube). No te preocupes, estamos seguros
  que los afrontarás con éxito, de igual forma aquí unos tips:

  - Estos son los videos de Youtube:
    * https://www.youtube.com/watch?v=fLSmUWOYpKw
    * https://www.youtube.com/watch?v=V7j8Aqxmbs8
    * https://www.youtube.com/watch?v=xj2VWLV0xCU
  - Para agregar los videos, averigua sobre la etiqueta `iframe`.
  - Para el formulario, revisa las etiquetas como `form` e `input`.

* Puedes ver el [sitio original](https://www.lyft.com/), sin embargo, su diseño
  ya ha cambiado en ciertas partes, así que tu fuente de verdad es la imagen que
  muestra el objetivo de este reto.

  > Nota: El sitio original tiene ciertos efectos y funcionalidades que
están fuera del alcance de este reto. Enfócate en obtener la maquetación
lo más parecido posible, usando lo aprendido en clase ;)

## A tener en cuenta

Este reto será evaluado sobre lo siguiente:

* Pixel perfect (replicar el diseño con exactitud)
* Estructura de carpetas y archivos
* Nombramiento de clases, id, etc
* Indentación
* Archivo `README.md` actualizado y correctamente redactado
* Uso de comentarios para hacer tu código más legible


# Mi repositorio

El repositorio cuenta con el archivo index.html, una carpeta css con main.css, imagenes e iconos.

Para desarrollar el maquetado de la página Lyft usé la etiqueta _nav_ para definir el menú con posición fija y para las demás secciones de la página usé la etiqueta _section_ y para el pie de página _footer_.

1. En la etiqueta _nav_ hice uso de una lista desordenada con _ul_ y _li_ para los botones con texto.

2. La primera _section_ con clase _home_ contiene una etiqueta _div_ con clase _sign-up_ que a su vez es contenedor de todos los elementos presentes en el formulario.
  * Esta _section_ tiene definido un _background-image_.

3. La segunda _section_ contiene dos _div_: el primero en el que está el texto con las etiquetas _h2_, _h3_ y _p_; Mientras que el segundo _div_ contiene la imagen.
  * _Estos elementos, tanto como los anteriores y los siguientes fueron modificados en su posición con la propiedad float y su valor left._

4. La siguiente _section_ contiene tres _div_ que a su vez cada uno contiene dos _div_ uno para el texto y otro para el video, ordenados según el orden en la página (de izquierda a derecha).

5. La ultima sección de la página, etiqueta _footer_ contiene un div por cada columna (4 _div_) y además el _div_ contenedor de los iconos de redes sociales.