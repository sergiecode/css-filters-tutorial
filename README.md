![Filtros en CSS](https://raw.githubusercontent.com/sergiecode/css-filters-tutorial/master/00%20Filters%20CSS.jpg)

![brillo css](https://raw.githubusercontent.com/sergiecode/css-filters-tutorial/master/Brillo.jpg)

![Cambio de tonalidad CSS](https://raw.githubusercontent.com/sergiecode/css-filters-tutorial/master/Cambio%20de%20tonalidad.jpg)

![Contraste css](https://raw.githubusercontent.com/sergiecode/css-filters-tutorial/master/Contraste.jpg)

![Desenfoque css](https://raw.githubusercontent.com/sergiecode/css-filters-tutorial/master/Desenfoque.jpg)

![Escala de grises CSS](https://raw.githubusercontent.com/sergiecode/css-filters-tutorial/master/Escala%20de%20Grises.jpg)

![Invertir negativo](https://raw.githubusercontent.com/sergiecode/css-filters-tutorial/master/Invertir%20negativo.jpg)

![Saturación css](https://raw.githubusercontent.com/sergiecode/css-filters-tutorial/master/Saturaci%C3%B3n.jpg)

![Sepia css](https://raw.githubusercontent.com/sergiecode/css-filters-tutorial/master/Sepia.jpg)

![Sombra CSS](https://raw.githubusercontent.com/sergiecode/css-filters-tutorial/master/Sombra.jpg)

# Tutorial de Filtros en CSS

Este tutorial te guiará a través del uso de filtros en CSS para manipular imágenes y elementos visuales en tu página web. Los filtros CSS te permiten aplicar efectos y transformaciones a elementos HTML, como imágenes, para lograr resultados visuales interesantes y creativos. En este tutorial, te explicaré cómo usar diferentes propiedades de filtros en combinación con el código proporcionado.

## Código Base

Antes de empezar, aquí tienes el código base que utilizaremos en este tutorial:

```
body {
    background-color: black;
    color: white;
}

.contenedor {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(3, 1fr);
    grid-column-gap: 0px;
    grid-row-gap: 0px;
    max-width: 500px;
    text-align: center;
    font-weight: bolder;
    font-family: 'Courier New', Courier, monospace;
}

img {
    max-width: 150px;
}

.poco {
    filter: invert(66%);
}

.mucho {
    filter: invert(100%);
}
```

## Explicación del Código

### Selector `body`

Este bloque define el estilo básico para el cuerpo de la página. Establece el fondo en negro y el color del texto en blanco.

### Selector `.contenedor`

Aquí se definen los estilos para un contenedor que utiliza la propiedad de cuadrícula (`grid`) para organizar su contenido. El contenedor tiene 3 columnas y 3 filas, con un ancho máximo de 500px. El texto se alinea al centro y se utiliza una fuente monoespaciada para mayor énfasis.

### Selector `img`

Este bloque establece un ancho máximo de 150px para todas las imágenes en la página. Esto asegura que las imágenes no superen este tamaño dentro del contenedor.

### Clase `.poco`

La clase `.poco` aplica un filtro de inversión del 66% a los elementos que la utilizan. La propiedad `filter: invert(66%)` invierte los colores de la imagen en un 66%, creando un efecto de negativo parcial.

### Clase `.mucho`

La clase `.mucho` aplica un filtro de inversión del 100% a los elementos correspondientes. La propiedad `filter: invert(100%)` invierte completamente los colores de la imagen, creando un efecto de negativo total.

## Manipulación de Imágenes

Ahora que hemos explicado el código base, puedes comenzar a experimentar con diferentes efectos de filtro en las imágenes. Para ello, modifica las clases `.poco` y `.mucho` y prueba las siguientes propiedades de filtro:

-   `brightness()`: Cambia el brillo de la imagen.
-   `contrast()`: Ajusta el contraste de la imagen.
-   `saturate()`: Controla la saturación de los colores en la imagen.
-   `blur()`: Agrega un efecto de desenfoque a la imagen.
-   `drop-shadow()`: Aplica una sombra a la imagen.
-   `grayscale()`: Convierte la imagen a escala de grises.
-   `sepia()`: Aplica un tono sepia a la imagen.
-   `invert()`: Invierte los colores de la imagen.

Modifica las clases `.poco` y `.mucho`, y experimenta con diferentes valores y combinaciones de estas propiedades para lograr efectos visuales únicos.
