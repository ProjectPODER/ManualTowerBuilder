# Editar los textos

Los archivos de texto que se pueden editar, están en formato MarkDown (.md).

Markdown es una sintaxis liviana y fácil de usar para dar estilo a los textos en la web. Tú controlas la visualización del documento; formatear palabras en negrita o cursiva, agregar imágenes y crear listas son solo algunas de las cosas que podemos hacer con Markdown. En general, Markdown es solo texto regular con algunos caracteres no alfabéticos, como `#` o `*`.

Te recomendamos la [guía de Markdown de Github](https://guides.github.com/features/mastering-markdown/) para aprender más al respecto.

## Textos principales

Los textos principales están conformados por las secciones que aparecen en el menú principal.

A continuación, mostramos la lista de documentos que se pueden editar:

Para editar los textos de la página principal:
  - **1-home.md**

Para editar los textos de la página Acerca:
  - **4-about.md**

Para editar los textos de cada slide del slider:
  - **sliders/_first-slider/slide-1.md**
  - **sliders/_first-slider/slide-2.md**
  - **sliders/_first-slider/slide-3.md**

Para añadir o quitar un slide, sólo debes añadir o quitar un archivo **.md** dentro de la carpeta **_first-slider**.


Para cambiar o añadir una imagen (_.jpg_, _png_ o _.svg_) dentro del slider, debes agregar la imagen dentro de la carpeta **assets/img/** y agregar el nombre del archivo dentro del archivo correspondiente al slide en el que aparecerá la imagen.

Para editar los textos del slider con la visualización:
  - **sliders/_visualization-slider/slide-1.md**
  - **sliders/_visualization-slider/slide-2.md**
  - **sliders/_visualization-slider/slide-3.md**


### Nombre de páginas y permalinks

Puedes editar el nombre y el permalink de cada sección del menú principal.

Para eso, debes ubicar en cada archivo editable, el área donde se encuentra esta información, por ejemplo:

```
---
layout: home
title: Home
permalink: /
---
```
Para cambiar el nombre de la página, edita:

```
---
title: Nombre de la página
---
```

Para cambiar el permalink, edita:
```
---
permalink: /link-de-la-pagina/
---
```

## Artículos

Los artículos son notas que analizan contratos, y aparecen vinculados a estos en el gráfico.

Para que se puedan vincular, debes saber el identificador del contrato OCID y agregarlo en el archivo, de la siguiente manera:

```
person: Juan Carlos Dueño
```