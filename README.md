# 🎨 Lienzo Musical

Pinta sonido con el ratón o el dedo. Cada trazo genera notas y partículas de colores en tiempo real.

## Cómo usarlo

Abre `index.html` en un navegador moderno. No necesita instalación ni servidor.

- **Arrastra** sobre el lienzo para pintar sonido.
  - Arriba = agudo · Abajo = grave (3 octavas).
  - Izquierda = onda senoidal · Derecha = onda triangular; el sonido también se panea de izquierda a derecha.
  - Más rápido = más fuerte.
- **Barra espaciadora**: explosión de notas en posiciones aleatorias.

## Controles

| Botón | Qué hace |
| --- | --- |
| Escala | Cambia entre Pentatónica, Menor, Japonesa y Blues. |
| Eco | Activa o desactiva el eco (delay). |
| Limpiar | Borra el lienzo. |
| ● Grabar | Graba lo que suena y descarga el audio (`.webm`, `.ogg` o `.m4a`, según el navegador) al detener. |

## Tecnología

Un solo archivo HTML con Canvas 2D, Web Audio API y MediaRecorder. Sin dependencias.
