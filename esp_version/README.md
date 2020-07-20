> # Como Crear tu README
---
![Readme](https://img.shields.io/badge/readme-OK-green.svg?colorB=00C106) ![commits](https://img.shields.io/badge/commits-53-blue.svg)

---
![README](https://bulldogjob.com/system/readables/covers/000/001/455/max_res/8-10-2018.png)
---
> ## Tabla de Contenido

* [que es Markdown](#que-es-Markdown)
* [Para qué sirve](#Para-qué-sirve)
* [Estructura de un archivo readme](#Estructura-de-un-archivo-readme)
  * [Introduccion](#Introduccion)
  * [Información del proyecto](#Información-del-proyecto)
  * [Documentación](#Documentacion)
  * [Información extra](#Información-extra)
* [Escritura básica y sintaxis de formato](#Escritura-básica-y-sintaxis-de-formato)
  * [Encabezados](#Encabezados)
  * [Estilo del texto](#Estilo-del-texto)
  * [Citando texto](#Citando-texto)
  * [Citando codigo](#Citando-codigo)
  * [Enlaces](#Enlaces) 
  * [Tablas](#Tablas)
  * [Listas](#Listas)
  * [Listas Anidadas](#Listas-Anidadas)
  * [Imagenes](#Imagenes)
    * [Local](Local)
    * [Externas](#Externas)
  * [Formato](#Formato)
---

Un archivo Léame es mucho más que texto simple, un archivo Léame es lo que los visitantes observan por primera vez en un repositorio, por lo que debemos tener un poco de atención al crearlo para poder captar la atención de los visitantes, además de ser colorido, causará una buena impresión , y le dará confianza. Lo que sugiere que es más probable que el código preste atención a los detalles y al mantenimiento.

Ahora comencemos por saber un poco sobre lo que es **md**, `md` o **marckdown** , qué es y para qué sirve.  
 
### Que es Markdown

Markdown es una manera fácil de agregar formato a los textos web. Con el formato nos referimos a cursiva, negrita, listas y más, en texto plano, por ejemplo, el texto que encontramos en el visor HTML de los editores de blogs, o en el Bloc de notas de Windows, para hacer que el concepto sea más asequible. Markdown fue creado originalmente por **John Gruber** , con la ayuda de **Aaron Swartz**, con el propósito de crear un texto simple que sea fácil de escribir y fácil de leer, y que se pueda convertir de manera fácil y válida a XHTML.

### Para qué sirve
Ahora que hemos hablado sobre qué es Markdown, tenemos que ver para qué sirve. El énfasis que pondremos es claramente web, pero hay otras cosas que se pueden hacer con Markdown. Por ejemplo, listas de tareas pendientes.

> ## Estructura de un archivo Léame

### Introduccion
En esta sección debemos ofrecer un resumen de en qué consiste el proyecto, es decir, debemos dar una idea resumida, clara y concisa de en qué consiste el proyecto.
 
### Información del proyecto
Aquí debemos ofrecer la información del estado técnico del proyecto. La versión en la que se encuentra, los errores, la última compilación, las tecnologías utilizadas, etc.

### Documentacion
Esta es la parte más importante. Aquí es donde debemos especificar todo lo que debemos hacer para lanzar el proyecto. Qué archivos descargar, cómo construir la base de datos si es necesario, configuración de rutas de inicio, etc.

### Información extra
En esta sección debemos agregar información adicional que los usuarios pueden usar para aclarar detalles que no han entendido en el resto del archivo Léame o información de contacto, como redes sociales, correo electrónico, etc.

> ## Escritura básica y sintaxis de formato

### Encabezados
Para crear un encabezado, agregue de uno a seis símbolos **#** antes del texto del encabezado. El número de **#** que use determinará el tamaño del encabezado.

```
# The largest heading
## The second largest heading
###### The smallest heading

```
# The largest heading
## The second largest heading
###### The smallest heading

### Estilo del texto
Puede indicar énfasis con texto en negrita, cursiva o tachado.

| estilo               | sintaxis        | keyboard            | ejemplo                   | salida             |
| ---------------------|-----------------|---------------------|---------------------------|--------------------|
| bold                 | ** ** or __ __  | command/control + b |  ```**This is bold text**```| **bold**               |
| italic               | * * or _ _      | command/control + i |  ```* italicized *```     | *italicized*         |
|Strikethrough         |  ~~ ~~          |                     |   ```~~mistaken~~ ```      | ~~mistaken~~           |
|Bold and nested italic| ** ** and _ _   |                     | ```**_extremely_ important**``` | **_extremely important_**|
|All bold and italic   | *** ***         |                     |  ```***text is important*** ```| ***text is important***  |

### Citando texto
Puede citar texto con un `>`.
```
En palabras de Abraham Lincoln:

> Perdona mi francés
```
En palabras de Abraham Lincoln:

> Perdona mi francés

### Citando codigo
Puede citar un código o un comando dentro de una oración con retrocesos simples. El texto dentro de los backticks no se formateará.
```
Úse `git status` para enumerar todos los archivos nuevos o modificados que aún no se han confirmado.
```
Úse `git status` para enumerar todos los archivos nuevos o modificados que aún no se han confirmado.

### Enlaces
Puede crear un enlace en línea ajustando el texto del enlace entre corchetes [ ] y luego ajustando la URL entre paréntesis ( ). También puede usar el método abreviado de teclado + k para crear un enlace.
```
Este sitio fue construido usando [páginas de GitHub](https://pages.github.com/).
```
Este sitio fue construido usando [páginas de GitHub](https://pages.github.com/)

* También puede crear enlaces a los archivos en su carpeta

```
[archivo](./archivo)
```
[archivo](./archivo)

* También puede crear enlaces a otros lugares en su archivo README
```
[tablas](#tablas)
```
[tablas](#tablas)

### Tablas

`puedes crear tablas:`
```
|col1|col2|col3|
|----|----|----|
|row |    |    |
|row2|    |    |
|row3|    |    |
```
|col1|col2|col3|
|----|----|----|
|row |    |    |
|row2|    |    |
|row3|    |    |

### Listas
Puede hacer una lista desordenada precediendo una o más líneas de texto con `-` o `*`.

```
- George Washington
- John Adams
- Thomas Jefferson
```
- George Washington
- John Adams
- Thomas Jefferson

Para ordenar su lista, preceda cada línea con un número

```
1. James Madison
2. James Monroe
3. John Quincy Adams
```
1. James Madison
2. James Monroe
3. John Quincy Adams

### Listas Anidadas
Puede crear una lista anidada sangrando uno o más elementos de la lista debajo de otro elemento.

```
1. Primer elemento de la lista
   - segundo elemento de la lista anidada
     - tercer elemento de la lista anidada
```	 

1. Primer elemento de la lista
   - segundo elemento de la lista anidada
     - tercer elemento de la lista anidada

### Images
puedes agregar imágenes alojadas local y externamente
 * Local

 Para vincular una imagen de nuestro repositorio, debe cargar la imagen en el repositorio donde desea alojar la imagen y copiar la URL asignada.

 Las etiquetas `HTML` se pueden usar para manipular la imagen, ajustando así el `ancho` y el `alto`.

 `texto alternativo` + `url`
 ```html
 <a href="texto alternativo"><img src="url" align="middle" width="desired width" height="desired heigh"></a>
 ```
 ```html
 <a href="logo github"><img src="https://github.com/ricardo1470/README/blob/master/img/logo_github.png" align="middle" width="100" height="50"></a>
 ```
 <a href="logo github"><img src="https://github.com/ricardo1470/README/blob/master/img/logo_github.png" align="middle" width="100" height="50"></a>

 * Externas

 de la misma manera que las imágenes se agregan localmente, se puede hacer con imágenes alojadas en servidores externos a `github`.
 ```html
 <a href="texto alternativo"><img src="url" align="middle" width="desired width" height="desired heigh"></a>
 ```
 ```html
 <a href="logo github"><img src="https://e7.pngegg.com/pngimages/93/461/png-clipart-github-computer-icons-logo-readme-github-logo-monochrome.png" align="middle" width="100" height="50"></a>
 ```
 <a href="logo github"><img src="https://e7.pngegg.com/pngimages/93/461/png-clipart-github-computer-icons-logo-readme-github-logo-monochrome.png" align="middle" width="100" height="50"></a>

### formato

puede formatear fragmentos de código, de acuerdo al lenguaje en el que este trabajando o al que quiere referirse.

Para agregar formato al código, debemos agregar el nombre del lenguaje después de crear el bloque de código con  \``` (lenguaje de referencia) ```, de esta manera el código se formateará con ese lenguaje.

\```lenguaje de referencia

codigo

\```

\```python

codigo

\```

\```ruby

codigo

\```

por ejemplo: 

> codigo en lenguaje `Python`:

código sin formato:
 ```
#!/usr/bin/python3
def fizzbuzz():
    for i in range(1, 101):
        if (i % 3 == 0 and i % 5 == 0):
            print("FizzBuzz", end=" ")
        elif (i % 3 == 0):
            print("Fizz", end=" ")
        elif (i % 5 == 0):
            print("Buzz", end=" ")
        else:
            print("{:d}".format(i), end=" ")

 ```
 codigo con formato:
 \```python
 ```python
#!/usr/bin/python3
def fizzbuzz():
    for i in range(1, 101):
        if (i % 3 == 0 and i % 5 == 0):
            print("FizzBuzz", end=" ")
        elif (i % 3 == 0):
            print("Fizz", end=" ")
        elif (i % 5 == 0):
            print("Buzz", end=" ")
        else:
            print("{:d}".format(i), end=" ")
 ```
 > codigo en `ruby`:

 código sin formato:
 ```
#!/usr/bin/env ruby
puts ARGV[0].scan(/^\d{10}$/)
```
código con formato:
\```ruby
 ```ruby
#!/usr/bin/env ruby
puts ARGV[0].scan(/^\d{10}$/)
```
> codigo en `bash`:

código sin formato:
 ```
#!/bin/bash
rm *[~]
```
código con formato:
\```bash
 ```bash
#!/bin/bash
rm *[~]
```
> codigo en `c`:

código sin formato:
 ```
int main(void)
{
	puts("\"Programming is like building a multilingual puzzle");
	return (0);
}
```
código con formato:
\```c
 ```c
int main(void)
{
	puts("\"Programming is like building a multilingual puzzle");
	return (0);
}
``` 
 
---

> ## contacto 💬

| [twitter](https://twitter.com/RICARDO1470) | [linkedin](https://www.linkedin.com/in/ricardo-alfonso-camayo/) | [mail](1466@holbertonschool.com) | [github](https://github.com/ricardo1470/README/blob/master/README.md) |
|---|---|---|---|

---

---

## License
*`Como Crear tu README` is open source and therefore free to download and use without permission.*

<a href="url"><img src="https://www.holbertonschool.com/holberton-logo.png" align="middle" width="100" height="30"></a>

---

