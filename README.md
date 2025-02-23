🎨 Proyecto SCSS Modular

Este proyecto utiliza SCSS para estructurar y organizar el código CSS de manera modular, siguiendo una arquitectura basada en base, layout, state y theme.

📂 Estructura de archivos

/scss
│── base/
│   ├── _reset.scss
│   ├── _typography.scss
│   ├── _variables.scss
│
│── layout/
│   ├── _navbar.scss
│   ├── _promo.scss
│   ├── _footer.scss
│
│── state/
│   ├── _animations.scss
│   ├── _utilities.scss
│
│── theme/
│   ├── _colors.scss
│   ├── _buttons.scss
│
│── styles.scss

📌 Descripción de cada carpeta

🔹 base/

Contiene los estilos globales del proyecto, como la normalización de estilos, tipografías y variables globales.

_reset.scss → Normaliza los estilos.

_typography.scss → Define la tipografía global.

_variables.scss → Contiene las variables de colores, fuentes y estilos generales.

🔹 layout/

Define la estructura de los principales elementos de la interfaz.

_navbar.scss → Estilos de la barra de navegación.

_promo.scss → Sección promocional.

_footer.scss → Pie de página.

🔹 state/

Define estados y utilidades reutilizables.

_animations.scss → Animaciones y transiciones.

_utilities.scss → Clases de utilidad como .hidden, .centered, etc.

🔹 theme/

Define estilos específicos de la temática del sitio.

_colors.scss → Diferentes combinaciones de colores.

_buttons.scss → Estilos de botones y elementos interactivos.

