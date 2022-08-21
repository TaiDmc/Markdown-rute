# Aprendiendo _Markdown_

## Indice

- [Parrafos](#parrafos)
- [Letras](#letras)
- [Encabezados](#encabezados)
- [Enlaces](#enlaces)
- [Imagenes](#imagenes)
- [Divisiones en _Markdown_](#divisiones)
- [Listas](#listas)
- [Citas](#citas)
- [Tablas](#tablas)
- [Codigo](#codigo)
- [Comentarios en _Markdown_](#comentarios-en-markdown)
- [Escape de Caracteres Especiales](#escape-de-caracteres-especiales)

---

## Parrafos

Esto es un parrafo

```md
Esto es un parrafo.

No se necesita de ninguna palabra especial
```

Lorem ipsum dolor sit amet consectetur, adipisicing elit. Debitis eligendi, nulla quisquam tempore delectus eaque beatae
nisi maiores. Iure possimus ex quasi ad exercitationem autem natus, omnis tempora qui nesciunt!

[⤴](#indice)

---

## Letras

_Aplicando cursiva_

```md
_Aplicando cursiva_
```

**Aplicando negritas**

```md
**Aplicando negritas**
```

**_Aplicando ambas_**

```md
**_Aplicando ambas_**
```

[⤴](#indice)

---

## Encabezados

# Encabezado 1

## Encabezado 2

### Encabezado 3

#### Encabezado 4

##### Encabezado 5

###### Encabezado 6

## Otro encabezado

```md
# Encabezado 1

## Encabezado 2

### Encabezado 3

#### Encabezado 4

##### Encabezado 5

###### Encabezado 6

## Otro encabezado
```

[⤴](#indice)

---

## Enlaces

[GitHub](https://github.com/taidmc)

```md
[GitHub](https://github.com/taidmc)
```

### Enlaces Internos

[Aprendiendo _Markdown_](#aprendiendo-markdown)

[Cabe a aclarar que los Enlaces Internos solo funcionaran con Encabezados](#otro-encabezado)

```md
[Aprendiendo _Markdown_](#aprendiendo-markdown)

[Cabe a aclarar que los Enlaces Internos solo funcionaran con Encabezados](#otro-encabezado)
```

---

## Imagenes

<!-- ![name](src) -->

![This is JavaScript](https://jonmircha.com/img/blog/this-is-javascript.jpg)

```md
![This is JavaScript](https://jonmircha.com/img/blog/this-is-javascript.jpg)
```

[⤴](#indice)

---

## Divisiones

Estas las haremos en todo nuestro documento _Markdown_, bueno esto se hace con `---`, `***`, `___`.
(Cualquier manera funciona)

[⤴](#indice)

---

## Listas

### Listas Ordenadas

<!-- Lo correcto seria hacer la numeracion con solo 1nos y que mark se encargue de la numeracion -->

1. Primavera
1. Verano
1. Otonio
1. Invierno

```md
1. Primavera
1. Verano
1. Otonio
1. Invierno
```

### Listas Desordenadas

- Primavera
- Verano
- Otonio
- Invierno

```md
- Primavera
- Verano
- Otonio
- Invierno
```

#### Listas Desordenadas con Sublista

<!-- Estas las haremos con indentacion -->

- Primavera
  - Abril
  - Mayo
    - Cumple de Jon 🎂
    - Cumple de Carlos 🖤
  - Junio
- Verano
  - Julio
  - Agosto
    - Cumple de mi futura novia 🖤
  - Septiembre
- Otonio
  - Octubre
    - no.
  - Noviembre
  - Diciembre
- Invierno
  - Enero
  - Febrero
  - Marzo

```md
- Primavera
  - Abril
  - Mayo
    - Cumple de Jon 🎂
    - Cumple de Carlos 🖤
  - Junio
- Verano
  - Julio
  - Agosto
    - Cumple de mi futura novia 🖤
  - Septiembre
- Otonio
  - Octubre
    - no.
  - Noviembre
  - Diciembre
- Invierno
  - Enero
  - Febrero
  - Marzo
```

[⤴](#indice)

---

## Citas

### Citas en Linea

<!-- Citas en linea, se hacen con > -->

> Siempre tienes opción de no tener opinión. - _Marco Aurelio_

```md
> Siempre tienes opción de no tener opinión. - _Marco Aurelio_
```

### Citas de Bloque

<!-- Citas de bloque, todas las lineas deben de tener un > -->

> Todo lo que escuchamos es una opinión, no un hecho.
>
> Todo lo que vemos es una perspectiva, no la verdad.
>
> _Marco Aurelio_

```md
> Todo lo que escuchamos es una opinión, no un hecho.
>
> Todo lo que vemos es una perspectiva, no la verdad.
>
> _Marco Aurelio_
```

[⤴](#indice)

---

## Tablas

<!-- Te vas a apoyar mucho con pipe |
Ademas va a ser fundamental hacer la segunda linea para crear la tabla
 -->

| Nombre          | Edad | Correo                            |
| --------------- | ---- | --------------------------------- |
| Carlos Cabi     | 15   | carlangascamachobrigido@gmail.com |
| Jon             | 38   | jonmircha@gmail.com               |
| kEnAi           | 9    | kenai@jonmircha.com               |
| Chanchito Feliz | 2    | chanchitofeliz@gmail.com          |

```md
| Nombre          | Edad | Correo                            |
| --------------- | ---- | --------------------------------- |
| Carlos Cabi     | 15   | carlangascamachobrigido@gmail.com |
| Jon             | 38   | jonmircha@gmail.com               |
| kEnAi           | 9    | kenai@jonmircha.com               |
| Chanchito Feliz | 2    | chanchitofeliz@gmail.com          |
```

[⤴](#indice)

---

## Codigo

<!-- Para destacar algo, por ejemplo una palabra reservada de JS, pues lo hacemos con nuestras gloriosas Template Strings `` -->

### Codigo en "Linea"

Lorem ipsum dolor sit amet consectetur, `let` adipisicing elit. `const` Debitis eligendi, nulla quisquam tempore delectus eaque beatae
nisi maiores. `[1, 2, 3]` Iure possimus ex quasi ad exercitationem autem natus, omnis tempora qui nesciunt!

```md
Lorem ipsum dolor sit amet consectetur, `let` adipisicing elit. `const` Debitis eligendi, nulla quisquam tempore delectus eaque beatae
nisi maiores. `[1, 2, 3]` Iure possimus ex quasi ad exercitationem autem natus, omnis tempora qui nesciunt!
```

### Codigo en Bloque

<!-- Lo haremos con ```
para instancia y cierre, y ademas podemos poner el tipo de lenguaje (su extension)pegado a los templates
 -->

#### JavaScript

```js
let $form;
let load = fetch("src", {
  method: "POST",
  headers: "application/json",
  body: JSON.stringify({
    name: $form.name.value,
    email: $form.email.value,
  }),
});

function getAll() {
  document.addEventListener("DOMContentLoaded", load);
}
```

`````

````md
```js
let $form;
let load = fetch("src", {
  method: "POST",
  headers: "application/json",
  body: JSON.stringify({
    name: $form.name.value,
    email: $form.email.value,
  }),
});

function getAll() {
  document.addEventListener("DOMContentLoaded", load);
}
```
`````

````

### PHP

```php
<?php
echo "Hola Mundo";
>
````

### Phyton

```py
num = 11
if num > 10:
  print("Hi")
```

<!-- Tambien puede tomar codigo HTML de forma nativa -->
<form>
<label for="q">Buscar:</label>
<input type="search" name="q" id="q">
</form>

```
<form>
<label for="q">Buscar:</label>
<input type="search" name="q" id="q">
</form>
```

---

[⤴](#indice)

## Comentarios en _Markdown_

Estos se hacen de la misma manera que en HTML `<!-- -->`
Ya existen varios en nuestro documento _Markdown_

---

## Escape de Caracteres Especiales

\*\*Negrita\*\* y \_Cursiva\_

```md
\*\*Negrita\*\* y \_Cursiva\_
```

[⤴](#indice)
