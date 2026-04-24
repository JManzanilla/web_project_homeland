# Homeland

Sitio web estático y responsivo que presenta una galería de lugares emblemáticos del mundo, desarrollado como parte del programa de Desarrollo Web en TripleTen.

## Descripción

Homeland es una landing page que muestra una colección de fotografías de distintos lugares del mundo junto con descripciones de sus habitantes. El diseño prioriza la experiencia visual con una galería de imágenes, secciones descriptivas y una presentación de lugares con tipografía editorial cuidada.

## Tecnologías utilizadas

- HTML5 semántico
- CSS3 — Flexbox y CSS Grid para layouts complejos
- Metodología BEM para nomenclatura de clases CSS
- Diseño Mobile First y responsive (móvil, tablet y escritorio)
- Fuentes Inter (Black, Medium, Regular) en formato `.woff2`
- Normalize.css para consistencia entre navegadores

## Características

- Galería de imágenes responsiva con CSS Grid
- Sección descriptiva con tipografía editorial
- Bloque de "lugares" con tarjetas de ciudad y botón de acción
- Header con logo y navegación
- Footer con enlaces y redes sociales
- Efectos hover en elementos interactivos
- Optimización de fuentes con carga local (`@font-face`)

## Estructura del proyecto

```
web_project_homeland/
├── index.html
├── blocks/              # Estilos BEM por bloque
│   ├── content.css
│   ├── description.css
│   ├── footer.css
│   ├── gallery.css
│   ├── header.css
│   ├── page.css
│   └── places.css
├── pages/
│   └── index.css        # Importa todos los bloques
├── images/              # Fotografías y recursos gráficos
└── vendor/
    ├── fonts.css
    ├── normalize.css
    └── fonts/           # Fuentes Inter en .woff2
```

## Instalación y uso

```bash
git clone git@github.com:JManzanilla/web_project_homeland.git
cd web_project_homeland
```

Abre `index.html` directamente en el navegador. No requiere instalación de dependencias ni servidor.

## Autor

Jesus Manzanilla — [GitHub](https://github.com/JManzanilla)
