# 🍲 El Sabor de la Abuela

Proyecto de práctica de la asignatura **Lenguajes de Marcas**. Es la web de un restaurante ficticio de cocina tradicional, creada solo con **HTML5 y CSS3**, para aplicar los contenidos vistos en clase.

## 🎯 Objetivo

Practicar la creación de páginas web estáticas usando etiquetas semánticas, tablas, formularios y hojas de estilo, manteniendo el código ordenado y organizado en varios archivos.

## 📄 Páginas

| Página | Archivo | Contenido |
|--------|---------|-----------|
| Inicio | `index.html` | Imagen de portada, tabla de especialidades y formulario de reservas |
| Nuestra Carta | `menu.html` | Carta completa dividida en entrantes, platos principales y postres |

## 📚 Conceptos practicados

### HTML
- Estructura básica de un documento HTML5 (`<!DOCTYPE>`, `<head>`, `<body>`, `lang`, `meta charset`).
- Etiquetas semánticas: `header`, `nav`, `main`, `section`, `article`, `footer`.
- Listas para el menú de navegación (`ul`, `li`).
- Enlaces entre páginas y a secciones concretas con anclas (`index.html#reservas`).
- Imágenes con el atributo `alt` para accesibilidad.
- Tablas (`table`, `thead`, `tbody`, `tr`, `th`, `td`).
- Formularios (`form`, `label`, `input` de tipo texto, fecha y número, `button`).
- Uso de `id` y `class`.

### CSS
- Enlazado de una hoja de estilos externa (`estilos.css`).
- Selectores de etiqueta, clase, id y descendientes.
- Pseudoclases `:hover` y `:focus`, y selector `:nth-child(even)` para filas alternas.
- Modelo de caja: `margin`, `padding`, `border`, `border-radius`.
- Maquetación con **Flexbox** (`display: flex`, `align-items`, `justify-content`, `gap`).
- Transiciones y sombras (`transition`, `box-shadow`).
- Imágenes ajustables con `object-fit`.

## 📁 Estructura del proyecto

```
.
├── index.html
├── menu.html
├── estilos.css
├── imagenes/
│   ├── mesa.jpg
│   ├── croquetas.jpg
│   ├── ensaladilla.jpg
│   ├── bacalao.jpg
│   ├── ternera.jpg
│   ├── cocido.jpg
│   ├── paella.jpg
│   ├── tortilla.jpg
│   ├── tarta.jpg
│   └── arrozleche.jpg
└── README.md
```

## 📌 Posibles mejoras

- Hacer el diseño responsive con `@media` queries.
- Validar y enviar el formulario con JavaScript.
- Añadir más páginas (contacto, galería...)

> Proyecto con fines educativos. Los datos del restaurante (dirección, teléfono, etc.) son ficticios.
