# Sitio de información UTN

Portal de información y proyectos de la UTN, hecho con [MkDocs Material](https://squidfunk.github.io/mkdocs-material/)
y publicado en GitHub Pages.

## Editar contenido

Todo el contenido está en `docs/` como archivos Markdown. Editar un `.md` y hacer
push a `main` publica automáticamente (vía GitHub Actions).

- Nueva página: crear el `.md` en `docs/` y agregarla a `nav:` en `mkdocs.yml`.
- Página con clave: agregar al inicio del archivo:

  ```yaml
  ---
  level: interno
  ---
  ```

  La clave del nivel `interno` **no vive en el repo**: se define como secret del
  repositorio en GitHub (`UTN_CLAVE_INTERNO`) y se inyecta al publicar. Para
  cambiarla: `gh secret set UTN_CLAVE_INTERNO` y re-ejecutar el workflow.
  Para agregar otro nivel con otra clave, sumarlo en `password_inventory`
  (`mkdocs.yml`) con su propia variable de entorno / secret.

## Ver localmente

```bash
pip install -r requirements.txt
mkdocs serve
```

Abre http://127.0.0.1:8000 con recarga automática al editar.

## Publicación

El workflow `.github/workflows/deploy.yml` construye y publica el sitio en la rama
`gh-pages` en cada push a `main`. En GitHub: **Settings → Pages → Source: rama
`gh-pages`** (solo la primera vez).
