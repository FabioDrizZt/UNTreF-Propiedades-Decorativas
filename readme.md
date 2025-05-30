# ✨ Propiedades Decorativas y Filtros en CSS 🎨

## Descripción del Repositorio 📁

Este repositorio contiene ejemplos prácticos sobre el uso de **propiedades decorativas** y **filtros** en CSS, aplicados a listas y tarjetas visuales. El objetivo es mostrar cómo embellecer y personalizar elementos HTML utilizando distintas propiedades de estilo, haciendo énfasis en la creatividad y el diseño visual.

## Propiedades Decorativas en CSS 🖌️

Las propiedades decorativas permiten modificar la apariencia de los elementos HTML para hacerlos más atractivos y funcionales. En este proyecto se utilizan principalmente en:

### 1. Fondos y Opacidad 🌄
- **background-image**: Permite colocar imágenes de fondo en elementos como el `body` o las tarjetas (`.card`).
- **background-repeat, background-attachment, background-size, background-position**: Controlan cómo se muestra la imagen de fondo (si se repite, si es fija, su tamaño y posición).
- **opacity**: Ajusta la transparencia de un elemento, permitiendo efectos visuales sutiles.

### 2. Listas Decoradas 📋
- **list-style-type**: Cambia el tipo de viñeta de las listas (`square`, `disc`, `circle`, `upper-roman`, `lower-alpha`, etc.), permitiendo una gran variedad de estilos.
- **list-style-image**: Permite usar una imagen personalizada (como un ícono SVG) en lugar de las viñetas tradicionales.
- **list-style-position**: Define si la viñeta está dentro o fuera del contenido de la lista.

### 3. Tarjetas Visuales 🃏
- Las tarjetas (`.card`) combinan imágenes de fondo, opacidad y dimensiones fijas para crear bloques visuales destacados.

## Filtros en CSS 🧪

Los **filtros** permiten aplicar efectos visuales a los elementos, modificando su apariencia sin alterar la imagen original. Algunos filtros que se pueden usar (comentados en el código para experimentar) son:

- `blur(10px)`: Desenfoca la imagen.
- `sepia(100%)`: Aplica un tono sepia.
- `grayscale(100%)`: Convierte la imagen a escala de grises.
- `contrast(150%)`: Aumenta el contraste.
- `brightness(150%)`: Aumenta el brillo.
- `hue-rotate(100deg)`: Rota los colores.
- `invert(100%)`: Invierte los colores.
- `opacity(10%)`: Cambia la opacidad.
- `saturate(3)`: Aumenta la saturación.

Estos filtros pueden activarse, por ejemplo, al pasar el mouse sobre una tarjeta usando la pseudo-clase `:hover`.

## Ejemplo de Uso 👀

```css
.card:hover {
  /* filter: blur(10px); */
  /* filter: grayscale(100%); */
  transition: all 2.5s ease-in-out;
}
```

## Íconos Personalizados 🏷️

Se utiliza un ícono SVG personalizado (`bookmark-check-fill.svg`) como viñeta en las listas de músicos, mostrando cómo se pueden personalizar aún más los elementos de lista.

## Conclusión 🏁

Este repositorio es ideal para experimentar y aprender sobre las posibilidades decorativas de CSS, tanto en listas como en tarjetas visuales, y sobre cómo los filtros pueden transformar la experiencia visual de una página web.

---

¡Explora, prueba y diviértete diseñando! 🚀
