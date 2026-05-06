# III Simposio de Divulgación Matemática · Sitio web

Landing estática del Tercer Simposio de Divulgación Matemática.
29, 30 y 31 de julio de 2026 · Santiago de Chile.

## Estructura

```
dimat-web/
├── index.html
├── CNAME                       # dominio dimatchile.cl
├── README.md
└── assets/
    ├── css/style.css
    ├── js/main.js
    └── images/
        ├── favicon.svg
        ├── cafure.jpg          # FALTA: foto del invitado
        ├── og-banner.jpg       # FALTA: imagen para compartir en redes
        └── logos/              # FALTA: logos institucionales
```

## Recursos a reemplazar

Estos archivos hay que subirlos antes de publicar:

| Archivo | Qué es | Tamaño sugerido |
|---|---|---|
| `assets/images/cafure.jpg` | Foto de Antonio Cafure | 800 × 1000 px (4:5) |
| `assets/images/og-banner.jpg` | Imagen social (al compartir el link) | 1200 × 630 px |
| `assets/images/logos/puc.svg` | Logo PUC | SVG o PNG transparente |
| `assets/images/logos/ulagos.svg` | Logo ULAGOS | SVG o PNG transparente |
| `assets/images/logos/dimat.svg` | Logo Red DIMAT | SVG o PNG transparente |
| `assets/images/logos/somachi.svg` | Logo SOMACHI | SVG o PNG transparente |
| `assets/images/logos/sochiem.svg` | Logo SOCHIEM | SVG o PNG transparente |
| `assets/images/logos/cuech.svg` | Logo Red VCM CUECH | SVG o PNG transparente |

Mientras no estén, el sitio muestra placeholders elegantes con el texto del nombre.

## Cómo se ven los placeholders

El HTML está pensado para que los logos y la foto se carguen *si existen*, y en caso contrario se vea un cuadro punteado con el nombre escrito. Esto permite publicar el sitio incluso sin los archivos finales. Para reemplazar, basta dejar el archivo en la ruta correcta.

## Personalización rápida

- **Colores**: variables CSS al inicio de `assets/css/style.css` bajo `:root`.
- **Tipografías**: `Fraunces` (display, serif editorial) e `Inter Tight` (sans).
  Cargadas desde Google Fonts en `index.html`.
- **Texto**: todo el contenido vive en `index.html`. Marcado semántico, sin
  frameworks ni build steps.

## Despliegue (ver instrucciones detalladas más abajo)

1. Crear repositorio en GitHub.
2. Subir estos archivos.
3. Activar GitHub Pages.
4. Configurar el dominio `dimatchile.cl`.
