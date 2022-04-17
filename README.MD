# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

Underline 1
-----------

Underline 2
===========

# Formatos de énfasis
- formato *itálica* de la primera forma.
- formato _itálica_ de la segunda forma.
- formato **bold o strong** de la primera forma
- formato __bold o strong__ de la segunda forma
- formato ~~tachado~~, formato normal.
- Aqui podemos usar formato *italica*, formato **bold** y también ~~tachado~~

# Listas
1. Esto es un item de lista ordenada.
2. Esto es un item de lista ordenada.
3. Esto es un item de lista ordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.

# Links
- <a href="http://www.google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://wwww.google.com)
- [Esto es un link al fichero index](index.html)

# Imagenes
![Logo GitHub](https://cdn.pixabay.com/photo/2017/08/05/11/24/logo-2582757_960_720.png)

# Code Snippets

Código en JSON
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

Código en Javascript
```JavaScript
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

Código en Pascal

```Pascal
procedure MiProcedure()
var
a:String;
begin
end;
```

# Tablas
| Nombre | Apellido  | Documento |
| ------ | --------  | --------- |
| Maxi   | Burgos    | 123456    |
| Tomas  | Que Tomas | 512514    |

# Citas

Esto es un texto referente a una cita que pondremos debajo:

> Esto es una cita

Esto es otro texto que no se relaciona con la cita anterior.

> Ésta es otra cita distinta.

# Líneas divisorias

Ésto es un texto que será dividido por guiones.

---
Ésto es otro texto dividido por asteriscos.

***

Ésto es otro texto dividido por guiones bajos.

___

# Saltos de línea

Ésto es nuestro primer párrafo.

Este es nuestro segundo párrafo.

Este es nuestro tercer párrafo.