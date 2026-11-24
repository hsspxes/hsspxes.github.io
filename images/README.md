# Espejo de imágenes de Ordo (respaldo de la app)

Fuente: **Ordo FSSPX** · https://ordo.fsspx.org. Cada iluminación procede de un manuscrito
antiguo y nombra la institución que la conserva (campo `credit`), que la app muestra siempre.

> ⚠️ El aviso legal de Ordo permite reutilizar los *datos del calendario* citando la fuente,
> pero «cualquier otra reproducción requiere el acuerdo del editor». Antes de publicar estas
> imágenes, pedir permiso por el formulario de contacto de ordo.fsspx.org.

## Contenido

- `celebration/<id>.json`: imagen de cada celebración (`celebration.id` del ordo), con el mismo
  formato que `https://ordo.fsspx.org/api/v1/calendar/<a>/<m>/<d>/images` pero solo con la
  primera imagen (la que usa la app) y con `url` y `src` apuntando a este espejo
  (`originalUrl` guarda la de Ordo).
- `<hash>/<ancho>.webp`: los archivos, en los anchos que indica `widths` de la ficha
  (el más cercano a 320 para la tarjeta y el mayor para el visor).

La app los pide en `https://hsspxes.github.io/images/celebration/<id>.json` cuando la API de
Ordo no responde.
