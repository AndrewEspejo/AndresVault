---
{"dg-publish":true,"permalink":"/software-engineer-learning/node-js/modulos/","tags":"gardenEntry"}
---

Un módulo no es nada más que una unidad de código organizado en archivos o directorios, la cual puede ser exportada con facilidad para poder reutilizarse en otras partes de la aplicación.

## Tipos de módulos

Hay 3 tipos de módulos. Todos funcionan de una manera similar pero difieren en el origen.

-   Built-in modules: Son los módulos nativos de la API de Node.js. No hace falta que se instalen, ya que vienen incluidos por defecto con Node.js. Algunos ejemplos son los módulos [[Software Engineer learning/Node Js/File system\|File system]], [[Software Engineer learning/Node Js/HTTP\|HTTP]] o `stream`. Estos paquetes solo son actualizados si cambias la versión de Node.js. ^09d1d3
-   Local modules: Son los módulos escritos por los desarrolladores y forman en su conjunto gran parte de la aplicación. Como ya has leído, se estructuran así con la finalidad de poder ser un código reutilizable.
-   External modules: Son, en esencia, los paquetes de terceros distribuidos a través de npm (aunque pueden provenir de otros repositorios). Estos paquetes se instalan como dependencias y, aunque aportan funcionalidad a la aplicación, no deben incluirse en el repositorio ya que no son parte de la misma.Un módulo no es nada más que una unidad de código organizado en archivos o directorios, la cual puede ser exportada con facilidad para poder reutilizarse en otras partes de la aplicación.

