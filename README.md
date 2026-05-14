# Zafepay · Editor de carruseles

Editor visual de plantillas para producir carruseles de Instagram/LinkedIn del sistema visual Zafepay 2026.

## ¿Qué es esto?

Una herramienta web (un solo archivo HTML) que permite:

- Editar los textos de las 3 plantillas del carrusel mensual haciendo clic.
- Reemplazar la foto del protagonista subiendo una imagen desde el computador.
- Cambiar los colores de la paleta de marca en vivo.
- Reemplazar el logo Zafepay por el archivo oficial.
- Exportar cada slide como PNG a 1080×1350 (formato vertical 4:5 de Instagram).
- Exportar las 3 slides juntas con un solo click.

## Estructura del carrusel

1. **Slide 01 · Portada** — titular + silueta de persona recortada.
2. **Slide 02 · Lista de errores** — 4 cards con números mint y palabras clave resaltadas.
3. **Slide 03 · Cierre con producto** — mockup del dashboard de Zafepay + CTA pill.

## Sistema visual

- **Paleta:** azul Zafepay `#4F4FE8`, azul profundo `#2E2EBF`, mint `#34D8A3`, amarillo highlight `#FFD84D`, ink `#0F1037`.
- **Tipografía:** Inter (sans-serif geométrica moderna).
- **Formato:** 1080×1350 (Instagram 4:5 vertical) o adaptable a 1080×1080 cuadrado.

## Cómo usar

1. Abrir `zafepay_editor_semana.html` en un navegador (Chrome o Safari).
2. Click en cualquier texto para editarlo (los textos editables se resaltan en mint al pasar el mouse encima).
3. Cambiar foto: panel derecho → "Foto (slide 1)" → subir archivo o pegar URL.
4. Cambiar logo: panel derecho → "Logo Zafepay" → subir archivo PNG/SVG.
5. Cambiar colores: panel derecho → selectores de color en vivo.
6. Exportar: botón azul arriba a la derecha (PNG individual) o botón mint (los 3 PNG de una).

## Sugerencias

- Para mejor resultado en el slide 1, usa una foto del protagonista con fondo transparente (procesada con [remove.bg](https://www.remove.bg)).
- Si la foto viene de una URL externa y al exportar te tira error, sube la imagen desde tu computador para evitar bloqueo CORS.
- Los archivos PNG exportados están a 2x resolución (~2160×2700 internos), ideal para preservar calidad.

## Publicar como página web gratuita

### Con GitHub Pages

1. Crear un repositorio nuevo en GitHub.
2. Subir este archivo `zafepay_editor_semana.html` y este `README.md`.
3. Renombrar el HTML a `index.html` (para que se abra por defecto).
4. En el repo, ir a **Settings → Pages → Source: main branch → Save**.
5. En 1-2 minutos tendrás tu editor publicado en `https://tu-usuario.github.io/nombre-del-repo/`.

### Con Netlify (más rápido)

1. Ir a [app.netlify.com/drop](https://app.netlify.com/drop).
2. Arrastrar el archivo HTML al recuadro.
3. URL pública lista en segundos.

## Equipo

CMO: María Paz Labbé — mariapaz@zafepay.com
