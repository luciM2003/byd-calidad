# El Portal de Calidad se mudó

Ahora vive adentro de la app de BYD Yacopini, para que sea una sola y no haya
que acordarse de dos direcciones:

**https://byd-yacopini.github.io/byd-yacopini-hub/portal/**

Acá quedan sólo dos cosas, y es a propósito:

- `index.html`, que redirige a la dirección nueva. Sirve para que sigan
  funcionando el ícono que la gente ya tiene en el celular, el QR de la guía
  impresa y los enlaces que se mandaron por WhatsApp.
- `guia.pdf`, que es a donde apunta el segundo QR de esa guía.

No borrar ninguno de los dos hasta estar seguros de que nadie los usa.

El código fuente sigue en el repositorio privado `byd-portal-calidad`, y se
publica con `npm run publicar`.
