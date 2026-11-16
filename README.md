# Almacén

Buscador del almacén: escribe el nombre o la referencia de un producto y se ilumina su sitio en el plano.

- App de una sola página (`index.html`), sin dependencias ni compilación. Funciona sin conexión (`sw.js`) y se puede instalar en el móvil (`manifest.json`).
- **Añadir o mover productos:** edita la lista `PRODUCTOS` en `index.html`.
  - `n` nombre · `r` referencia · `a` referencia alternativa · `d` texto de ubicación · `k` palabras clave extra.
  - `t` lista de `id` del plano que se iluminan (estanterías `p1-A`, `B3-5`…, pinchos `pk-…`, pasillos `pas-1`…`pas-6`, zonas `zone-B3`). Déjala vacía (`[]`) si la ubicación está pendiente.
- Si cambias iconos o tipos de letra, sube el número de `CACHE` en `sw.js`. Los cambios en `index.html` llegan solos (se ven en la siguiente apertura).
