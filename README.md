# Mapa de convocatorias

Web estática (un solo `index.html`) con el mapa temporal, las tarjetas y la tabla comparativa de convocatorias de colaboración universidad-empresa, con sus fichas y documentos.

## Contenido

- `index.html`: la web (no necesita instalación ni servidor).
- `data.json`: los datos de las convocatorias. Es lo que se actualiza para publicar cambios.
- `docs/cdti/`, `docs/aei/`: los documentos originales (resúmenes .pptx y fichas .docx).
- `img/`: imágenes de los resúmenes visuales.

## Publicar en GitHub Pages

1. Crea un repositorio en GitHub y sube todo el contenido de esta carpeta (`index.html`, `data.json`, `docs/`, `img/`).
2. En el repositorio: Settings, Pages, Build and deployment, Source: «Deploy from a branch».
3. Elige la rama `main` y la carpeta `/ (root)`. Guarda.
4. En un minuto aproximadamente la web queda en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/`.

Las páginas de GitHub Pages son públicas. Revisa que los documentos de `docs/` se puedan publicar.

## Añadir o editar convocatorias y documentos

1. Abre la web y pulsa **Editar**.
2. **Añadir convocatoria** abre un formulario (nombre, organismo, fechas, condiciones, datos clave y ficha completa). Para la AEI, escribe `AEI` como organismo y aparecerá su propio filtro y color.
3. En la ficha de cada convocatoria, pestaña **Documentos**, puedes añadir, editar o quitar documentos (con un archivo o con una ruta como `docs/aei/Ficha_AEI_PID2025.docx`).
4. Tus cambios se guardan en tu navegador. Para que los vea todo el mundo, pulsa **Exportar datos**, descarga `data.json` y sustituye el del repositorio. Sube también a `docs/aei/` los documentos nuevos.

Quien visite la web puede abrir el modo edición, pero sus cambios solo quedan en su navegador y no alteran la web publicada.

## Consejo para los documentos nuevos

Un archivo adjuntado desde el ordenador queda guardado solo en tu navegador. Para publicarlo, súbelo a `docs/` en el repositorio y pon su ruta en el documento (botón **Editar** junto al documento).
