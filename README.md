# Investigación sobre las propiedades Box-Shadow y Text-Shadow en CSS

## Introducción

CSS (Cascading Style Sheets) es un lenguaje utilizado para dar estilo y mejorar la apariencia visual de las páginas web. Entre sus múltiples herramientas se encuentran las propiedades **box-shadow** y **text-shadow**, las cuales permiten agregar sombras a elementos y textos, haciendo que el diseño sea más atractivo y profesional.


## Propiedad Box-Shadow

La propiedad **box-shadow** se utiliza para agregar una sombra alrededor de un elemento HTML, como formularios, imágenes, botones o contenedores.

### Sintaxis

css
box-shadow: desplazamiento-x desplazamiento-y desenfoque expansión color;

### Componentes

* **desplazamiento-x:** Mueve la sombra horizontalmente.
* **desplazamiento-y:** Mueve la sombra verticalmente.
* **desenfoque (blur):** Define qué tan difusa será la sombra.
* **expansión (spread):** Aumenta o reduce el tamaño de la sombra.
* **color:** Determina el color de la sombra.

### Ejemplo

css
box-shadow: 5px 5px 10px gray;

### Ventajas

* Mejora la apariencia visual de los elementos.
* Ayuda a destacar secciones importantes.
* Genera sensación de profundidad.
* Hace que los formularios y botones sean más atractivos.


## Propiedad Text-Shadow

La propiedad **text-shadow** permite agregar sombras a los textos de una página web.

### Sintaxis

css
text-shadow: desplazamiento-x desplazamiento-y desenfoque color;

### Componentes

* **desplazamiento-x:** Posición horizontal de la sombra.
* **desplazamiento-y:** Posición vertical de la sombra.
* **desenfoque:** Nivel de suavidad de la sombra.
* **color:** Color de la sombra.

### Ejemplo
text-shadow: 2px 2px 4px black;

### Ventajas

* Resalta títulos y encabezados.
* Mejora la legibilidad del texto.
* Proporciona un diseño más moderno y llamativo.
* Permite crear efectos visuales atractivos.

## Aplicación en el Proyecto

En la página de modificación de alumnos se aplicaron estas propiedades para mejorar la presentación visual:

* Se utilizó **text-shadow** en el título principal y en las etiquetas del formulario.
* Se utilizó **box-shadow** en el formulario, los campos de entrada y los botones.
* También se agregaron efectos al pasar el cursor sobre los elementos para mejorar la experiencia del usuario.

## Conclusión

Las propiedades **box-shadow** y **text-shadow** son herramientas muy útiles dentro de CSS para mejorar la apariencia de una página web. Su uso permite crear diseños más modernos, atractivos y profesionales, además de facilitar la organización visual de la información. Gracias a estas propiedades, es posible destacar elementos importantes y ofrecer una mejor experiencia a los usuarios.

# Comentario

Se utilizó **text-shadow** en el título y las etiquetas para que el texto resaltara más. También se aplicó **box-shadow** al formulario, botones y campos de texto para darles una apariencia más moderna.

Como ejemplo de desbordamiento, se organizó el contenido dentro del formulario para que no se salga de la página y se vea ordenado.

Como parte del diseño, se eligió un fondo verde, un formulario blanco con sombras y efectos al pasar el cursor sobre algunos elementos para hacerlo más atractivo visualmente.

3. W3Schools. CSS Shadow Effects. https://www.w3schools.com/css/css3_shadows.asp

