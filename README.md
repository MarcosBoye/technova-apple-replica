# TechNova - Réplica de Interfaz de Apple

## Descripción del Proyecto
Este proyecto es una réplica exacta de la estructura visual de Apple, adaptada para la marca ficticia **TechNova**. Desarrollado con HTML5 semántico y CSS3 puro para demostrar habilidades avanzadas de maquetación limpia y diseño adaptativo.

## Secciones Replicadas
1. Barra de navegación superior fija (estilo translúcido blur).
2. Sección Hero de Evento Principal (Fondo oscuro).
3. Secciones destacadas de productos individuales (iPhone Premium y Pro Laptop).
4. Cuadrícula secundaria de productos en dos columnas (CSS Grid).
5. Banner promocional de transmisión de video con contenido superpuesto.
6. Notas legales y de pie de página numeradas.
7. Footer estructurado en 5 columnas con enlaces de navegación.

## Conceptos HTML Utilizados
* **Semántica Estricta:** Uso de `<header>`, `<nav>`, `<main>`, `<section>`, `<article>` y `<footer>`.
* **Enlaces y multimedia:** Gestión de rutas relativas eficaces para imágenes limpias.

## Conceptos CSS Utilizados
* **Alineación Moderna:** Flexbox y CSS Grid.
* **Efectos visuales:** `backdrop-filter: blur()` para el menú de navegación y `linear-gradient` para las superposiciones oscuras en las imágenes.

## Aplicación de Layouts y Responsive Design
* **Flexbox:** Implementado en la barra de navegación para distribuir los ítems, en los contenedores de botones (`.cta-links`) y en la tarjeta interna para empujar las imágenes al fondo.
* **CSS Grid:** Utilizado en `.products-grid` para renderizar el formato en dos columnas simétricas con `repeat(2, 1fr)` y en las 5 columnas del footer.
* **Responsive Design:** Controlado mediante Media Queries `@media (max-width: 768px)`. En pantallas móviles la cuadrícula colapsa a una sola columna (`1fr`), la navegación envuelve sus elementos de forma fluida y el footer reduce sus columnas a dos para evitar desbordamientos horizontales.

## Dificultades Encontradas
* **Ajuste del banner promocional:** Se resolvió el comportamiento adaptativo de la imagen de fondo utilizando `background-size: contain` combinado con un color de fondo negro sólido para evitar recortes severos en rostros de personajes en pantallas ultra anchas.
