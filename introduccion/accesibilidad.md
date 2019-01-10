# Accesibilidad

**EEEto** dispone una referencia accesible para todos los usuarios, sirviendo de guía y asegurando unos estándares de accesibilidad durante el diseño y desarrollo del producto. 

#### Accesibilidad

La accesibilidad del producto asegura que personas con discapacidad puedan **percibir**, **comprender**, **navegar**, **interactuar** y **contribuir** a la aplicación creada. Esto significa el producto es [perceptible, operacional, entendible y sólido](https://www.w3.org/TR/WCAG20/). Incluye interacciones con el teclado para las acciones del ratón, formularios y botones identificados, texto alternativos en imágenes, videos, iconos, o colores definidos bajo un estándar de contraste.

El sistema de diseño permite un desarrollo accesible disponiendo un conjunto de componentes semánticamente correctos, con su etiqueta [ARIA](https://www.w3.org/TR/wai-aria/), por lo que pueden ser identificados correctamente por los usuarios de tecnologías asistidas

#### Herramientas

* [High Contrast Chrome plugin](https://chrome.google.com/webstore/detail/high-contrast/djcfdncoelnlbldjfhinnjlhdjlikmph/related?hl=en) - Revisión de contraste en Chrome
* [Stark Sketch Plugin](http://www.getstark.co/) - Plugin para Sketch app.
* [NoCoffee vision simulator](https://chrome.google.com/webstore/detail/nocoffee/jjeeggmbnhckmgdhmgdckeigabjfbddl) - Simulador de baja visión
* [Color contrast checker](https://marijohannessen.github.io/color-contrast-checker/)
* [Color contrast](http://www.aremycoloursaccessible.com/) 

#### Recursos

* [World Wide Web Consortium](https://www.w3.org/WAI/) \(W3C\) se hace cargo de investigar y mejorar la accesibilidad de los sitios web para personas con discapacidad.
* Web Accessibility Initiative \(WAI\) contribuye a la creación y mantenimiento de [Web Content Accessibility Guidelines](https://www.w3.org/TR/WCAG21/) \(WCAG\) que dicta los estándares de accesibilidad.
* [Artículos relacionados y test de buenas prácticas.](https://a11yproject.com/)
* 
### Color

El sistema de diseño **EEEto** tiene nivel de de accesibilidad WCAG AA en todo el producto, incluido los ratios de contraste de color. 

La combinación de texto y colores de fondo no debe caer de lo recomendado en [WCAG](https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-contrast.html) para el umbral de 4.5:1 para los estándares o el texto pequeño y 3:1 para los textos largos.

### Teclado

La accesibilidad de teclado es necesaria y es una ayuda para quien utilizan eel teclado para navegar por la distintas opciones de la interfaz. Las interacciones más comunes utilizan la tecla `Tab` para seleccionar distintos elementos interactivos en de la interfaz, y la tecla `Enter` o `Spacebar` para activar un elemento seleccionado \(_focus_\).

### Desarrolladores

#### HTML

Permitir la navegación con TAB en un orden lógico y predecible estructurando el contenido para mantener una experiencia comparable a la experiencia de los usuarios de ratón u otros dispositivos de navegación.

Utilizar elementos HTML nativos y etiquetas de texto que permitan su utilización con un propósito correcto. Permite la fácil comprensión, desarrollo y mantenimiento, así como beneficiar las tareas de SEO.

Toda imagen debe ir acompañada de su texto alternativo.

Utilizar ARIA para facilitar la navegación independientemente de la tecnología que se utilice. Las marcas \(landmarks\) en el código para identificar regiones o señales \(Signpost\) para describir el funcionamiento del sitio, describir la funcionalidad o reforzar la semática del producto.

#### CSS

Añade estilo para los `:hover` y `:focus` de los elementos.



