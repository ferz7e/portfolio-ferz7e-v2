# portfolio-ferz7e-v2

Landing personal minimalista construida con HTML y CSS puro.

La página funciona como una tarjeta de presentación rápida para rutear a perfiles clave:

- GitHub
- LinkedIn
- Curriculum Vitae

## Stack

- HTML5
- CSS3
- Google Fonts: `Quicksand`

## Estructura

```text
portfolio-ferz7e-v2/
├── assets/
│   └── favicon.png
├── index.html
├── styles.css
└── README.md
```

## Qué incluye

- Hero centrado en pantalla
- Nombre, ubicación y rol profesional
- Enlaces principales a redes y CV
- Favicon enlazado desde `assets/favicon.png`
- Responsive design para desktop, tablet y mobile
- Nomenclatura BEM en clases del hero

## Cómo abrir el proyecto

Podés abrir `index.html` directamente en el navegador o levantar un servidor local.

Opción simple:

```bash
python3 -m http.server 8000
```

Después abrí:

```text
http://localhost:8000
```

## Personalización rápida

Contenido principal en [index.html](/Users/fernandozarate/Desktop/Código/portfolio-ferz7e-v2/index.html):

- ubicación: `.hero__location`
- nombre: `.hero__title`
- rol: `.hero__subtitle`
- enlaces: `.hero__button`

Estilos principales en [styles.css](/Users/fernandozarate/Desktop/Código/portfolio-ferz7e-v2/styles.css):

- colores base en `:root`
- escalas tipográficas del hero
- breakpoints de tablet y mobile

## Enlaces actuales

- GitHub: `https://github.com/ferz7e`
- LinkedIn: `https://www.linkedin.com/in/ferz7e/`
- CV: pendiente

## Próximos pasos sugeridos

- Reemplazar `href="#"` del CV por el archivo o enlace final
- Ajustar metadata del `<head>` para SEO y social preview
- Agregar una sección extra si más adelante querés mostrar proyectos
