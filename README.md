# constitucion_chile

*Constitución de Chile y sus cambios como un repositorio git*

## Objetivos del proyecto

Crear una fuente de información completa, certera, fácilmente reutilizable y abierta sobre los contenidos de la Constitución de Chile y los cambios que ha tenido durante el tiempo. De esta manera facilitamos la creación de software que permita analizar, compartir y educar sobre estos cambios.

## Por qué Git

Porque permite:

 - Comparar versiones: [Diferencias entre 1999 y 2003](https://github.com/opensourcechile/constitucion_chile/compare/d333d20e19bab5dc6c8dc6bf0bb350a6e241decb...6ef6094d6614a5bfa4b183f7e3fc63d3558794ab)
 - Conocer cuál fue la última ley que [modificó un texto](https://github.com/opensourcechile/constitucion_chile/blame/master/03-Cap%C3%ADtulo_III.md)
 - Crear herramientas para visualizar los cambios a lo [largo del tiempo](https://github.githistory.xyz/opensourcechile/constitucion_chile/blob/master/03-Cap%C3%ADtulo_III.md)
 - Compartir links a secciones y versiones específicas de un texto: [Artículo 2, 1997](https://github.com/opensourcechile/constitucion_chile/blob/c7e4900a42508080bbd7e3be404a021d67c2a09a/06-Cap%C3%ADtulo_VI.md#art%C3%ADculo-74).
 - Sugerir [cambios](https://github.com/opensourcechile/constitucion_chile/pull/1/files#diff-b74538cd3c3c2646650645d19f6a700b) en forma estructurada

## Método

Este proyecto esquematiza, a través de [Git](https://es.wikipedia.org/wiki/Git), la Constitución de Chile y los cambios que ha tenido durante el tiempo.

Cada ley o decreto con el que se ha modificado la Constitución es representado por un [commit](https://git-scm.com/book/es/v1/Fundamentos-de-Git-Guardando-cambios-en-el-repositorio) con las siguientes modificaciones:

- *Date*: Fecha de publicación de la ley o decreto.
- *Author*: Presidente o representante que firma la ley o decreto.
- *Message*: Transcripción completa de la ley referida, con la numeración de la ley como título.


## Cómo colaborar

Dado que los commits deben ser sobreescritos para modificar su metadata (Date, author, message), la mejor forma de colaborar es a través de la sección *Issues* como en el siguiente [ejemplo](https://github.com/opensourcechile/constitucion_chile/issues/2) de este repositorio.

