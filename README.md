# Repositorio de HTML y CSS

Este repositorio cubre los conceptos esenciales y prácticos de HTML y CSS.

Usando Visual Studio Code, creé un archivo `index.html` con codificación UTF-8, en español. Implementé prácticas de optimización SEO, velocidad, escalabilidad y adaptabilidad según auditorías de Google Lighthouse y PageSpeed Insights.

## HTML

### Etiquetas
Las etiquetas son los elementos fundamentales para estructurar un documento HTML. Algunas de las etiquetas utilizadas incluyen:

- `<html>`, `<head>`, `<header>`, `<main>`, `<body>`, `<footer>`
- `<div>`, `<section>`, `<a>`, `<nav>`
- `<h1>`, `<h2>`, `<h3>`, `<p>`, `<link>`, `<img>`
- `<form>`, `<input>`, `<legend>`, `<textarea>`, `<fieldset>`, `<label>`

### Atributos
Los atributos son propiedades adicionales que se aplican a las etiquetas para definir o modificar su comportamiento. Algunos ejemplos incluyen:

- `lang="es"` en la etiqueta `<html>` para definir el idioma de la página.
- `rel="stylesheet"` en el atributo `<link>` para cargar una hoja de estilo.
- `href` en la etiqueta `<a>` para definir el enlace de destino.
- `src` en la etiqueta `<img>` para especificar la fuente de la imagen.
- `alt` en la etiqueta `<img>` para proporcionar una descripción alternativa de la imagen.

## CSS

- **Uso de custom properties en :root** para definir variables reutilizables.
  
- **Normalización con normalize.css**: Utilizamos `normalize.css` para garantizar que nuestro sitio se vea de manera consistente en diferentes navegadores, eliminando diferencias de estilo predeterminadas.

- **Diseño responsivo**: Implementamos `media queries` para asegurar que nuestro diseño se adapte a diferentes tamaños de pantalla y dispositivos. Realizamos chequeos de las vistas en múltiples dispositivos usando la herramienta [Responsively.app](https://responsively.app).

- **Flexbox y Grid**: Exploramos y utilizamos tanto `Flexbox` como `CSS Grid` para crear layouts dinámicos y flexibles que se ajustan a las necesidades de la interfaz de usuario.

  - **Flexbox**: Se utilizó para crear diseños flexibles en los cuales los elementos pueden crecer, encogerse y distribuirse de forma eficiente, sin importar el tamaño de la pantalla o el contenedor. Este enfoque se usó especialmente para alinear y distribuir elementos en una sola dirección (horizontal o vertical).
  
  - **Grid**: Utilizamos `CSS Grid` para diseños de más complejidad, donde se requieren varias filas y columnas. Grid permite posicionar elementos de manera más controlada dentro de un sistema de rejilla.

- **Uso de clases, propiedades, atributos y etiquetas**: Organizamos el código con clases bien definidas y utilizamos propiedades y atributos adecuados para lograr un diseño limpio y eficiente.

- **Atajos de teclado y comandos**: Mejoramos la productividad utilizando atajos de teclado y comandos dentro de Visual Studio Code, acelerando el flujo de trabajo.

- **Importancia del código alineado**: Mantuvimos un código alineado y organizado para asegurar su legibilidad y facilitar futuras modificaciones.

- **Comentarios en el código**: Comentamos adecuadamente el código, tanto para nuestro propio entendimiento como para aquellos usuarios que puedan tomar o modificar nuestro trabajo en el futuro. Los comentarios ayudan a explicar la lógica y los elementos clave del código.

- **Box Model**: Comprendimos y aplicamos correctamente el modelo de caja (box model) de CSS para manejar el espaciado y el tamaño de los elementos. Este modelo define cómo los márgenes, bordes, relleno y el contenido de los elementos se comportan y se calculan.

- **Box Shadow**: Usamos `box-shadow` para crear efectos visuales, como sombras, que mejoran la estética de los elementos en la interfaz.

- **Uso de unidades rem**: Implementamos `rem` (root em) como unidad de medida para una mayor escalabilidad y accesibilidad en el diseño. El uso de `rem` asegura que los elementos escalen de acuerdo al tamaño de fuente raíz, lo que facilita la creación de interfaces más adaptables.

- **Uso de Google Fonts**: Para mejorar la tipografía y la apariencia de nuestro sitio, implementamos fuentes web desde [Google Fonts](https://fonts.google.com). Esto nos permitió usar fuentes personalizadas de alta calidad, que son fácilmente accesibles y optimizadas para la web.

- **Uso de Tabler Icons**: Incorporamos [Tabler Icons](https://tablericons.com) para agregar íconos de alta calidad y fácilmente personalizables a nuestra interfaz. Estos íconos permiten una representación visual clara y atractiva de las acciones o conceptos representados en la página.

- **Especificidad en CSS**: Aplicamos correctamente el concepto de **especificidad** en CSS para asegurarnos de que los estilos se aplicaran correctamente. La especificidad es un sistema de prioridades que determina qué reglas de estilo se aplican cuando hay múltiples reglas que afectan el mismo elemento. Utilizamos selectores más específicos para asegurarnos de que nuestros estilos tuvieran la mayor prioridad cuando fuera necesario.

- **Publicación en línea**: Usamos servicios como [Netlify](https://www.netlify.com) y otros hosting como [Nuthost](https://www.nuthost.com) para poner nuestro sitio en línea y asegurarnos de que sea accesible globalmente.

- **Compatibilidad de navegadores**: Comprobamos el soporte de características CSS y HTML en diferentes navegadores mediante la herramienta [Can I Use](https://caniuse.com), asegurándonos de que nuestro sitio funcione correctamente en diversas plataformas.
