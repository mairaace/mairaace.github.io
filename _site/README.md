# Plantilla de sitio web (Jekyll + tema CS50)

Esta es una plantilla vacía para que construyas tu propio repo web web y lo puedas usar con  GitHub Pages.


## 1. ¿Cómo está organizado el sitio?

```
.
├── _config.yml               nombre y descripción del sitio
├── index.markdown            página de inicio
├── _includes/
│   ├── header.md                título que aparece arriba del menú
│   ├── nav.md                   MENÚ lateral (los links a cada página)
│   └── footer.md                texto al pie de la página
├── _posts/                      todas las demás páginas
│   ├── 2026-01-01-s1.md              /2026/s1
│   ├── 2026-01-01-contenido.md      /2026/s1/contenido
│   ├── ...
│   ├── 2026-01-10-resources.md      /2026/resources
│   └── 2026-01-10-acknowledgements.md  /2026/acknowledgements
├── assets/
│   ├── page.scss            colores y estilos 
│   └── images/              aquí van las imágenes 
└── .github/workflows/deploy.yml 
```

## 2. ¿Cómo se crea una página?

Cada página es un archivo `.md` dentro de `_posts/`. El nombre **tiene** que empezar con una fecha:
`AAAA-MM-DD-nombre.md`.   En cada página procura mantener el formato de configuración que aparece al principio,si se rompe algo, recuerda que siempre puedes volver atrás. Escribir páginas es muy sencillo: como escribirías cualquier archivo Markdown.


## 4. Cómo publicar tu sitio

1. Crea un repositorio en GitHub llamado `tu-usuario.github.io` y sube estos archivos.
2. En el repo ve a **Settings → Pages → Build and deployment → Source** y elige **GitHub Actions**.
3. Cada vez que hagas `push` a `main`, el sitio se actualiza solo en `https://tu-usuario.github.io/`.

## 5. Verlo en tu computador

También si quieres verlo en tu local, hay un tutorial para descargar la librería: https://jekyllrb.com/docs/step-by-step/01-setup/  pero puede ser un poquito más complicado.

## Créditos

Basado en el tema de [Jekyll de CS50](https://cs50.readthedocs.io/themes/jekyll/).
