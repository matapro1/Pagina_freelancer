# Página Web de Diseño y Desarrollo Web Freelancer

## Descripción del Proyecto

Este proyecto es una página web profesional que ofrece servicios de desarrollo de páginas web por parte de un freelancer. Proporciona información detallada sobre los servicios ofrecidos, ejemplos de trabajos anteriores y una forma fácil de contacto.

## Capturas de Pantalla

![Captura de Pantalla 1](/screenshots/screenshot1.png)
_Breve descripción de la captura de pantalla._

![Captura de Pantalla 2](/screenshots/screenshot2.png)
_Breve descripción de la captura de pantalla._

## Características Principales

- **Portafolio Detallado:** Muestra ejemplos de trabajos anteriores con descripciones detalladas y tecnologías utilizadas.
- **Información de Servicios:** Detalles sobre los servicios ofrecidos, precios y términos, presentados de manera clara y estructurada.
- **Formulario de Contacto Seguro:** Implementé un formulario de contacto seguro con validación de datos y confirmación de envío.

## Tecnologías Utilizadas

- HTML5
- CSS3
- JavaScript (ES6+)

## Paleta de Colores

- **Azul Oscuro (#002244):** Utilizado para encabezados y elementos importantes.
- **Azul Claro (#007BFF):** Resalta enlaces y llamadas a la acción.
- **Gris Oscuro (#333333):** Texto principal para una buena legibilidad.
- **Gris Claro (#CCCCCC):** Fondo de secciones.
- **Blanco (#FFFFFF):** Fondo alternativo.
- **Naranja (#FFA500):** Acento para resaltar elementos específicos.

## Fuentes

- **Encabezados:** [Nombre de la Fuente] (enlazar a la fuente)
- **Cuerpo de Texto:** [Nombre de la Fuente] (enlazar a la fuente)

## Estructura de Carpetas

- `/img`: Almacena imágenes y otros recursos.
- `/css`: Contiene los estilos, divididos por componentes.
- `/js`: Archivos JavaScript, organizados por funcionalidad.
- `/screenshots`: Capturas de pantalla del proyecto.


## Estilos para escribir código css

- Módulos
- Utilidades


## Cómo Empezar

1. Clona este repositorio: `git clone https://github.com/tuusuario/tuproject.git`
2. Abre el archivo `index.html` en tu navegador.

## Personalizaciones

- **Cambiar Colores:** Modifica el archivo CSS en `/css/style.css`.
- **Actualizar Contenido:** Edita el HTML en `/index.html` para reflejar tus servicios y detalles de contacto.
- **Agregar Proyectos al Portafolio:** Actualiza la carpeta `/assets/portfolio` y el archivo `index.html`.

## Desarrollo del Proyecto

### Conceptualización y Diseño

- Uno de mis primeros proyectos.
- Seleccioné la paleta de colores y fuentes para lograr una identidad visual coherente.

### Implementación de la Interfaz HTML

1. Creación de textos con HTML para las distintas secciones del sitio.
2. Estructura del contenido.

#### 🔎 ¿Cuándo utilizar `<section>` o `<main>`?

> Si el primer elemento hijo de la etiqueta es un `<h>`, deberías utilizar `<section>`. No obstante, existe una excepción: si este contenido es el principal, entonces debes utilizar `<main>`.

3. Creación de enlaces y navegación.

> El menu es de un solo nivel, por tal motivo utilice la etiqueta `<nav>` y directamente los enlaces.

4. Anadiendo iconos.

   > Puedes encontrar una amplia colección de iconos en [Tabler Icons](https://tablericons.com/). Estos iconos son proporcionados por Tabler Icons y pueden mejorar la apariencia de tu página web.

5. Formulario

- En la sección de contacto de mi página web, he implementado un formulario que permite a los usuarios comunicarse con nosotros de manera sencilla. La estructura HTML de este formulario está diseñada para ser clara y fácil de entender, y se compone de los siguientes elementos:

    `<section>:`
        Utilizo el elemento `<section>` para encapsular toda la sección de contacto, proporcionando una organización semántica al contenido.

    `<h2>` - Encabezado de la Sección:
        El encabezado `<h2>` se utiliza para proporcionar un título descriptivo a la sección de contacto. En este caso, he etiquetado la sección como "Contacto".

    `<form>` - Formulario:
        La etiqueta `<form>` encapsula todo el contenido del formulario. Esto incluye todos los campos de entrada y botones relacionados con la información de contacto.

    `<fieldset> y <legend>:`
        He utilizado el elemento `<fieldset>` para agrupar lógicamente los elementos del formulario, y <legend> para proporcionar una leyenda descriptiva. Esto mejora la accesibilidad y la comprensión del propósito del formulario.

    Campos del formulario `(<label>, <input>, <textarea>):`
        Cada campo del formulario está compuesto por un par `<label> y <input>` o `<textarea>`. Las etiquetas `<label>` mejoran la accesibilidad y la usabilidad, vinculando el texto descriptivo con el campo correspondiente.

    Atributos type en los campos de entrada:
        Utilizo atributos type específicos en los campos de entrada para indicar el tipo de datos que se espera. Por ejemplo, type="text" para el nombre, type="tel" para el teléfono, y type="email" para la dirección de correo electrónico.

    Botón de Enviar `(<input type="submit">):`
        La etiqueta `<input> con type="submit"` representa el botón de envío del formulario. Este botón permite a los usuarios enviar la información ingresada en el formulario.

Estos elementos y su organización siguen las mejores prácticas de HTML y están diseñados para mejorar la legibilidad del código y la experiencia del usuario. La estructura HTML proporciona una base sólida para la implementación de la funcionalidad de contacto en mi página web.

### Fase de diseño usando CSS

#### 1.Enlaces de Estilo CSS en tu Página Web:

`<link rel="preload" href="css/style.css" as="style" />:`

Esta línea se utiliza para precargar la hoja de estilo principal de tu página web antes de que el navegador comience a renderizar la página. Al usar rel="preload" con as="style", estás indicando al navegador que este recurso es crítico y debe cargarse anticipadamente. Esto ayuda a mejorar la velocidad de carga al asegurar que la hoja de estilo esté disponible cuando se necesite.

    `<link rel="stylesheet" href="css/style.css" />:`

Este enlace carga la hoja de estilo principal para tu página web. Después de la precarga mencionada anteriormente, esta línea garantiza que la hoja de estilo se aplique correctamente al contenido de tu página. El atributo href especifica la ubicación de la hoja de estilo en el directorio "css".

**Propósito y Beneficios:**

Optimización de Carga:

El uso de rel="preload" optimiza la carga de tu hoja de estilo, mejorando la experiencia del usuario al acelerar el tiempo de renderizado de la página.

Separación de Responsabilidades:

Separar la precarga (rel="preload") de la carga estándar (rel="stylesheet") permite que el navegador gestione de manera más eficiente los recursos críticos para la presentación inicial de la página.

Organización del Código:

Mantener la hoja de estilo en un archivo separado y enlazarla desde todas las páginas ayuda a organizar y mantener tu código de manera más efectiva.

Cache del Navegador:

El navegador puede cachear la hoja de estilo después de la primera carga, lo que significa que en visitas subsiguientes, la página puede cargarse más rápidamente ya que el recurso está almacenado localmente en la máquina del usuario.

En resumen, estas líneas de código contribuyen a una carga eficiente y una presentación estilizada de tu página web al precargar y aplicar la hoja de estilo principal.

#### 2. Tamaños de Fuente con Unidades "rem" en CSS:

En el código CSS, se utiliza el sistema de unidades "rem" para establecer tamaños de fuente escalables. Aquí está una explicación detallada:

**html - Tamaño de Fuente Base:**

font-size: 62.5%;: Establece un tamaño de fuente base del 62.5% en el elemento html. Esto facilita los cálculos, haciendo que 1rem sea equivalente a 10px.

**body - Tamaño de Fuente Base:**

font-size: 16px;: Establece el tamaño de fuente base para el elemento body en 16 píxeles. Con el tamaño de fuente base del html configurado, esto resulta en un tamaño de fuente efectivo de 10px.

**h1 - Tamaño de Fuente:**

font-size: 3.8rem;: Define el tamaño de fuente para los elementos h1 en 3.8rem. Dado que 1rem equivale a 10px en este contexto, el tamaño de fuente efectivo para h1 es de 38px.

**span - Tamaño de Fuente:**

font-size: 2rem;: Establece el tamaño de fuente para los elementos span en 2rem. Con la configuración de tamaño de fuente base, esto resulta en un tamaño de fuente efectivo de 20px.

Estos tamaños de fuente relativos proporcionan una estructura escalable y facilitan el diseño responsivo. La unidad "rem" permite que los tamaños de fuente se ajusten proporcionalmente en relación con el tamaño de fuente base del html. Esto mejora la consistencia y la flexibilidad en el diseño de la página web.

#### 3. Selectores



### Optimización y Pruebas

- Optimicé imágenes para una carga más rápida.
- Realicé pruebas exhaustivas en diferentes dispositivos y navegadores.

### Despliegue

- Subí el proyecto a un servidor o plataforma de alojamiento web.

## Contribuciones

¡Las contribuciones son bienvenidas! Si encuentras errores o mejoras, por favor abre un issue o envía un pull request.

## Licencia

Este proyecto está bajo la Licencia [Nombre de la Licencia] - consulta el archivo [LICENSE.md](LICENSE.md) para más detalles.
