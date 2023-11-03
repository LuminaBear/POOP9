---
marp: false
author: Isaac Martinez
size: 4:3
theme: gaia
---

# Bienvenidos al Tutorial

En este tutorial vamos a explicar el uso de marp, markmap y uml:

**Uso de Marp**

Esta extension esta basada en Markdown
Esta presentacion esta creada en Marp

*Sintaxis Basica*

---

Primero se le debe asiganar formato usando

marp: false (Esto asigna si queremos usar marp)

author: Isaac Martinez (Indica el autor del codigo)

size: 4:3 (Indica el aspecto de la presentacion)

theme: gaia (Indica los colores que se usaran en la presentacion)

---

Tipos de formato de letra

- Se usan "**" para poner la letra en **negrita**
- Se usan "*" para poner la letra en *italica*
- Se usan "~~" para poner la letra en ~~tachado~~
- Se usan "´" para poner la letra en `codigo`

---

Para los titulos se usan "#", mientras mas "#" tenga el titulo sera mas chico

# Titulo 1
## Titulo 2
### Titulo 3
#### Titulo 4

---

Para insertar imagenes se usa "![width:800px]" que es lo que establece el tamaño de la imagen, y "(imagen.jpg)" que es el nombre de la imagen que queremos insertar

Ejemplo
![width:800px](imagen.jpg)

---

Para las tablas se usan | para delimitar celdas

# Tabla

|Titulo 1|Titulo 2|
|---|---|
|Celda 1|Celda 2|
|Celda 3|Celda 4|

---

Los comentarios se escriben de la siguiente forma:
"[comment]:" Para especificar que se trata de un comentario y  "<> (Esto es un comentario XD)" donde se pone el comentario

---

Tambien se pueden agregar enlaces de la siguiente forma
"[Enlace]" para asignar el nombre que se mostrara del enlace y "(https://google.com)" para asignar la direccion web

Ejemplo

[YouTube](https://www.youtube.com/watch?v=dQw4w9WgXcQ)

---

Tambien se pueden agregar listas numeradas con 1., 2., 3., y asi sucesivamente
1. Uno
2. Dos
3. Tres

y listas no numeradas con elementos como -, +, *.
+ Uno
- Dos
* Tres

---

Por ultimo para explicar las referencias se deben de poner "[Referencia]" y el numero de referencia "["1"]"

Despues se debe escribir "["1"]" que es el numero de referencia, "https://google.com" que es el enlace a la web y " "Google" " que es el titulo de esta

Por ejemplo, para realizar este tutorial nos apoyamos de  [este texto][1]

[1]: https://tutorialmarkdown.com/sintaxis "Sintaxis básica de Markdown"

---

#Uso de MarkMap
Para crear un mapa usando markmap es muy facil, lo mas importante es comprender el uso de #

Los signos de almohadilla (#) se utilizan para crear títulos. Cuantas más se pongan, más pequeño será el título. Un solo # es el título principal, y más # indican títulos de nivel inferior.

---

"# Mapa mental"
"## Rama 1"
"### Subrama 1.1"
"### Subrama 1.2"
"#### Subrama 1.2.1"
"## Rama 2"
"### Subrama 2.1"
"### Subrama 2.2"

--- 

En este caso, ## se utiliza para crear un título de nivel 2 bajo el título principal "Mapa mental". Esto representa la "Rama 1".

Se usan tres almohadillas para crear títulos de nivel 3. Por ejemplo, "Subrama 1.1" es un título de nivel 3 bajo "Rama 1".
Cuatro almohadillas se usan para títulos de nivel 4, como "Subrama 1.2.1" bajo "Subrama 1.2".

Este formato es muy útil para organizar información y crear una estructura visual que refleje la jerarquía de las ideas.

---

Todo esto da el resultado siguiente

![width:800px](imagen1.jpg)

---

# Uso de UML

