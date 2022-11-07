---
theme: gaia
marp: true
size: 4:3
author: Equipo 5

---
# Tutorial MarkDown en Marp
 Para hacer uso de la herramienta Markdown es necesario descargar la extensión **Markmap** en el IDE *VSCode* el cual se muestra en la imagen

<style>
img[alt~="center"] {
  display: block;
  margin: 0 auto;
}
</style>

![markmap center  w:500px ](/assets/markmap.png)

---
Tras haber descargado la extensión podrás trabajar en conjunto con **Marp for VSCode** para crear una presentación, al tenerla desarrollada podrás hacer de la siguiente del siguiente botón que convertirá tu presentación en un mapa via **Markdown**, este botón es el siguiente.

![MarkmapButton center w:200](/assets/MarkdownButton.png)

---
Al presionarlo se creará el mapa acorde a la presentación, la sintaxis es la siguiente

# #Usar llave para llaves principales

## ##Al agregar un simbolo de llave extra se creará una subllave

#### ####Mientras mayor sea la cantidad de llaves, la posición de la subllave irá cambiando
---

Al crear nuestro mapa obtendremos el siguiente resultado acorde a lo colocado.

![mapa center w:800](/assets/mapa.png)

---
# Como hacer comentarios en Marp

Al igual que en HTML podemos escribir comentarios al hacer uso de la siguiente nomenclatura perteneciente a dicha sintaxis
es decir, haciendo uso del **<!--asasd!- agregar un guión más>**

---
# Centrar imágenes en Marp
Para centrar una imagen en las presentaciones de Marp podemos ocupar distintos métodos. El más factible sin duda, es creando un elemento *Style* en el código, dónde se permitirá agregar una etiqueta llamada **center** a nuestro elemento **img** de la siguiente manera.

![centrarImagen center w:600 h:200](/assets/centrarImg.png)