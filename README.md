# psehgaft.org

Sitio personal estático de Heber Romero Téllez: arquitectura tecnológica,
open source, proyectos y escritos. Publicado en https://psehgaft.org
mediante GitHub Pages con dominio personalizado (ver `CNAME`).

## Contenido

- `index.html` — página personal de una sola página, en español, con
  secciones de perfil, arquitectura tecnológica, proyectos open source y
  escritos.
- `CNAME` — dominio personalizado del sitio (`psehgaft.org`).
- Diseño sin herramientas de compilación: HTML y CSS en línea, con modo
  claro y oscuro, tipografías DM Sans, IBM Plex Mono y Noto Sans SC.

## Vista previa local

Desde la raíz del repositorio:

```bash
python3 -m http.server 8000
```

Luego abre http://localhost:8000/ en el navegador.

## Publicación

Settings → Pages → Deploy from a branch → `main` → `/ (root)`.
El archivo `CNAME` mantiene el dominio personalizado en cada despliegue.
