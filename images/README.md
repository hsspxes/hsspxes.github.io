# Espejo de imágenes de Ordo (respaldo de la app)

Fuente: **Ordo FSSPX** · https://ordo.fsspx.org. Cada iluminación procede de un manuscrito
antiguo y nombra la institución que la conserva (campo `credit`), que la app muestra siempre.

> ⚠️ El aviso legal de Ordo permite reutilizar los *datos del calendario* citando la fuente,
> pero «cualquier otra reproducción requiere el acuerdo del editor». Antes de publicar estas
> imágenes, pedir permiso por el formulario de contacto de ordo.fsspx.org.

## Contenido

- `celebration/<id>.json`: imagen de cada celebración (`celebration.id` del ordo), con el mismo
  formato que `https://ordo.fsspx.org/api/v1/calendar/<a>/<m>/<d>/images`, pero con `url` y `src`
  apuntando a este espejo (`originalUrl` guarda la de Ordo).
- `<hash>/320.webp` y `<hash>/640.webp`: los archivos (miniatura de la tarjeta y visor).

La app los pide en `https://hsspxes.github.io/images/celebration/<id>.json` cuando la API de
Ordo no responde.
