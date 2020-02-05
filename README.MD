# Versión del curso
Versión Actual: v1.2.2

# Cabeceras

# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6


# Underlines

Underline 1
---------

Underline 2
========


# Formatos de énfasis

- Formato *italica* de la primera forma.
- Formato _italica_ de la segunda forma.
- Formato **bold** o __strong__.
- Formato ~~tachado~~.(Alt126).
- aquie podemos usar *formato italico*, pero tambien **bold** y ~~tachado~~.

# Listas
## Ordenadas
1. Esto es un item de lista ordenada
2. Esto es un item de lista ordenada
3. Esto es un item de lista ordenada
## Desordenadas
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada

# Links
- <a href="http://www.google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link al index](index.html)

# Imágenes
![Logo Github](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png)

# Code Snippets
Código Json
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```
Código en Java Script
```Javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;

```
# Tablas
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Maxi | Burgos | 213165413
| Jose Carlos | Garcia | 456313158

# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita.

Esto es otro texto que no se relaciona con la cita, hay que dar 2 enter
> Esto es otra cita


# Líneas Divisoras
Esto es un texto que será dividido por guiones

---
Esto es otro texto divivido `por astericos.

***

Esto es otro texto dividido por guines bajos-

___

# Saltos de línea

Esto es nuestro primer párrafo.

Esto es nuestro segundo párrafo.

Esto es nuestro tercer párrafo.