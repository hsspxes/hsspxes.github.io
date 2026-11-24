# Espejo del Ordo (respaldo de la app Calendario HSSPX España)

Fuente: **Ordo FSSPX** · https://ordo.fsspx.org — Fraternidad Sacerdotal San Pío X.

Estos ficheros son la exportación anual de la API pública de Ordo, sin modificar, guardada como
respaldo por si el servicio no está disponible. Según su aviso legal
(https://ordo.fsspx.org/es/legal), reutilizar los datos del calendario mediante la API pública
está permitido citando la fuente. En caso de diferencia, prevalece el ordo impreso del distrito
o de la diócesis.

## Contenido

`hispania-fsspx/<año>.json` (1900–2200), obtenidos con:

```
https://ordo.fsspx.org/api/v1/export/json?year=<año>&lang=es&source=hispania&congregation=fsspx&mode=civil&marianBlue=1
```

Año civil (1 de enero – 31 de diciembre), en español, propio de España y de la FSSPX.

La app los pide en `https://hsspxes.github.io/ordo/hispania-fsspx/<año>.json` cuando la API
de Ordo no responde.
