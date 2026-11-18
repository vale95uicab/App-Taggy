# TAGGY App (dueños)
App independiente. Se publica con GitHub Pages en su propio repositorio.

1. En `index.html`, busca la línea `const WEB=...` (al inicio del script) y pon la dirección de tu página web TAGGY.
2. Crea un repositorio nuevo (ej. `taggy-app`), sube estos archivos a la raíz y activa Settings -> Pages (main, / root).


## Mejoras de rendimiento (versión optimizada)
- Se eliminaron animaciones infinitas y animaciones escalonadas de las pantallas.
- Se redujeron efectos de desenfoque que pueden ser costosos en algunos móviles.
- El mapa Leaflet ahora se reutiliza al volver a la pantalla principal, en lugar de destruirse y crearse de nuevo.
- Se ajustó la carga del mapa para reducir trabajo durante el zoom y el movimiento.
- Se añadió soporte de movimiento reducido (`prefers-reduced-motion`).
- Se mantuvieron las transiciones breves de interacción y la identidad visual de TAGGY.
