# HTML Tags

The following links are important to search html tags and its meanings

1. [HTML5 Doctor](http://html5doctor.com/)
2. [Mozilla Developer Elementos HTML](https://developer.mozilla.org/es/docs/HTML/HTML5/HTML5_lista_elementos)

- **H1** Solo debe existir una etiqueta en la página, esto representa que lo que contenga esa etiqueta es lo más importante
- **Section**: Etiqueta para dividir diferentes secciones de la página 
- **Article**: Cuando un elemento puede vivir por si solo se utiliza ésta imagen.
- **h1 a h6**: son etiquetas para indicar títulos con un estilo que destaca del resto.
- p: define el texto de un párrafo.
small: aplica una apariencia de texto reducido en tamaño.
- strong: aplica al texto un formato de negritas.
- a: corresponde a un ancla o enlace a una url interna o externa del documento.
- img: con esta etiqueta podemos enlazar imágenes en el documento.
- figure: le da un contexto semántico a las imágenes.

# Atributos HTML

Para **img**:

- **src**: específica la ruta de la imagen que será mostrada a través de esta etiqueta. La ruta puede ser absoluta (cunado especifica una dirección exacta, incluyendo el prefijo http(s) ) o relativa (cuando la referencia a la ubicación de la imagen parte de la ubicación del archivo actual).
- **alt**: indica un texto alternativo que será mostrado en lugar de la imagen cuando ésta no pueda ser mostrada.
- **width**: ancho de la imagen en pixeles.
- **height**: alto de la imagen en pixeles.

Para **link**, en la cabecera head del documento:

- **rel**: indica la relación del recurso con el contenido.
- **type**: indica el tipo de recurso / formato.
- **href**: indica la ubicación (url) del recurso enlazado.

Para **meta**, también en la cabecera head del documento:

charset: indica la tabla de caracteres (utf-8 para caracteres latinos) usada en el documento.

Para **a**:
- href: la ubicación o ruta a la que enlaza esta etiqueta de ancla. En el caso de querer enlazar a elementos que se encuentran dentro del mismo documento, este atributo debe indicar el valor del atributo ““id”” de ese elemento destino del enlace.

# Agregar Estilos a HTML

Hay tres opciones para incluir estilos que definan la apariencia de tu html:

- **Estilos en línea**: se definen directamente en el elemento html que quieres estilizar, se agregan con el atributo style.
- **Estilos con el tag Style**: regularmente este tag se incluye dentro de la etiqueta head del html.
- **Estilos enlazados desde un archivo css externo**: utilizando la etiqueta link que nos permite enlazar recursos externos.
  
A CSS, se le llama hojas de estilos en cascada porque los estilos que se definen para una página, se van aplicando de arriba hacia abajo, y de lo más general a lo más particular, teniendo prioridad lo más particular. Esto es, los estilos que prevalecen son los que han sido definidos en línea, luego los que fueron definidos mediante la etiqueta style en la cabeza o cuerpo del html, y por último los estilos definidos en archivos externos enlazados con la etiqueta link. Esta prioridad se puede alterar al usar el modificador **!important"" en la definición de algún estilo en particular, aunque esto no es recomendado.