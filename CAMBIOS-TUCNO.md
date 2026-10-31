# Cambios sobre ranuts/document

Esta copia parte del commit e975654 de https://github.com/ranuts/document y se publica bajo la misma
licencia AGPL-3.0. Los componentes de ONLYOFFICE conservan sus avisos y su autoría.

Cambios (31/10/2026):

- `public/sdkjs/cell/sdk-all.js`: conserva el alto de fila por defecto del archivo original.
- `lib/onlyoffice-editor.ts`: formato regional es-PE.
- `vite.config.ts`: compila desde el código fuente sin construir antes los paquetes internos.
- `public/web-apps/apps/spreadsheeteditor/main/app.js`: la pestaña Inicio de la barra sigue el orden de Excel
  (Fuente, Alineación, Número, Estilos, Celdas, Edición); «Formato condicional» y «Dar formato como tabla»
  son botones grandes con su nombre, «Insertar» y «Eliminar» llevan su nombre y la galería de estilos de
  celda queda más angosta. El cambio se aplica con `scripts/reordenar-cinta-inicio.py` del portal (31/10/2026).
