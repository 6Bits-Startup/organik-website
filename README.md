# OrganiK Frontend v2

Landing page estática de OrganiK, el sistema de control de inventario para minimarkets.
Está construida con HTML, CSS y JavaScript nativo: sin frameworks, sin librerías y sin paso de build.

## Estructura

```
public/
  index.html          landing principal (hero, funciones, video del equipo, video del producto, equipo, testimonios, planes por segmento y llamada final al login)
  terminos.html       términos y condiciones
  privacidad.html     política de privacidad
  404.html            página de error con la identidad de la marca
  assets/
    styles/           styles.css: sistema de diseño, estilos, animaciones y responsive
    scripts/          main.js (animaciones, interacciones y cambio de idioma), plans.js (selector de planes por segmento) y translations.js (traducciones ES / EN)
    images/           favicon.svg y team/ (fotos del equipo; ver team/LEEME.md para reemplazar los placeholders)
    videos/           videos del sitio (vacía por ahora)
    fonts/            fuentes locales (vacía por ahora; las fuentes vienen de Google Fonts)
```

Firebase Hosting publica solo la carpeta `public/` (ver `firebase.json`).

## Ejecutar localmente

Abre `public/index.html` directamente en el navegador.

Si prefieres servirla por HTTP, usa cualquier servidor estático apuntando a la carpeta `public/`.

## Características

- Diseño oscuro con acento lima, tipografía Fraunces + Geist.
- Animaciones con CSS, Web Animations API y `IntersectionObserver`.
- Respeta `prefers-reduced-motion`.
- Idioma ES / EN persistente entre páginas.

## Flujo de trabajo

El repositorio sigue **Gitflow** y **Conventional Commits**. Revisa [CONTRIBUTING.md](CONTRIBUTING.md)
antes de abrir una rama o un pull request, y el historial de cambios en [CHANGELOG.md](CHANGELOG.md).
