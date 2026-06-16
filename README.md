# PDP Suite — Design System

Biblioteca de componentes y estándares de UI de **PDP Suite**, basada en SAP Fiori / SAPUI5 (tema Horizon).

🔗 **Sitio en vivo:** https://pedroqueh.github.io/pdp-design-system/

## Contenido

El sitio es un único archivo **`index.html`** autocontenido (íconos SVG embebidos, logo inline, fuente SAP 72 desde CDN). No requiere build ni dependencias.

Incluye:

- **Fundaciones** — Colores (tokens) e Iconografía SAP
- **Componentes** — Filtros, Tablas, Formularios (más por venir: Botones, Mensajes)
- Cada componente documenta: demo interactivo, comportamiento y uso en SAPUI5

## Cómo actualizar

El archivo maestro se edita por separado; para publicar una versión nueva:

```bash
# copiar el HTML actualizado sobre index.html y luego:
git add index.html
git commit -m "Actualiza design system a vX.Y.Z"
git push
```

GitHub Pages republica automáticamente en ~1 minuto.

## Notas

- Repositorio **público** únicamente para habilitar GitHub Pages gratuito.
- No subir material confidencial (informes QA, PDFs de clientes, etc.); el `.gitignore` excluye esos formatos por seguridad.
