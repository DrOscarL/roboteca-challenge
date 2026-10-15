# Roboteca Challenge — RoboRescate

Aplicación web para complementar el **Soft Robot Challenge** dentro del taller de 40 minutos para niñas y niños de 7–12 años.

## Enlaces
- **Juego**: https://droscarl.github.io/roboteca-challenge/
- **AprilTags imprimibles**: https://droscarl.github.io/roboteca-challenge/tags.html

## Mecánica
- Tres baterías, 60 segundos, recoger y depositar en el reactor.
- Modo **manual**: mover el robot con mouse o controles deslizantes. «Agarrar / Soltar».
- Modo **AprilTags**: ubicar tres tags sobre la ropa (0 hombro, 1 codo, 2 muñeca), encender cámara, esperar 3/3, calibrar postura y jugar. Mantener la pinza durante un segundo sobre la batería y otro sobre el reactor.
- Modo opcional **pierna**: 0 cadera, 1 rodilla, 2 tobillo. Solo exploración con movimientos suaves y apoyo estable.

## Publicación
En **Settings → Pages → Build and deployment**, seleccionar **Deploy from a branch**, rama `main`, carpeta `/(root)`. GitHub Pages entrega HTTPS, necesario para el permiso de cámara.

## Taller (40 minutos)
5 min introducción · 18 min experimentación con Soft Robot · 14 min RoboRescate · 3 min cierre.

## Tecnología y privacidad
HTML, JavaScript, CSS y Canvas. Detector tag36h11 WebAssembly desde `arenaxr/apriltag-js-standalone` a través de jsDelivr, requiere Internet. Frames de cámara procesados localmente, sin grabación ni transmisión al servidor. La geometría es bidimensional. No se controla un robot físico.

## Precauciones / validación pendiente
- Imprimir la hoja de `tags.html` en blanco y negro **al 100 %**.
- **La detección con una webcam real todavía no ha sido validada**. Probarla antes del taller.
- Si falla el detector o la cámara, utilizar el modo manual.
- No pegar marcadores sobre la piel.
