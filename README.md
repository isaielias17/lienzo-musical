# 🎨 Lienzo Musical

Pinta sonido con el ratón o el dedo. Cada trazo genera notas y partículas de colores en tiempo real.

## Cómo usarlo

Abre `index.html` en un navegador moderno. No necesita instalación ni servidor.

- **Arrastra** sobre el lienzo para pintar sonido.
  - Arriba = agudo · Abajo = grave (3 octavas).
  - Izquierda = onda senoidal · Derecha = onda triangular; el sonido también se panea de izquierda a derecha.
  - Más rápido = más fuerte.
- **Barra espaciadora** o botón **✨ Explosión**: explosión de notas en posiciones aleatorias.
- Funciona con varios dedos a la vez en pantallas táctiles.

## Botones grandes (para los niños)

| Botón | Qué hace |
| --- | --- |
| 🌙 Calma | Modo tranquilo: notas suaves que se apagan despacio, colores pastel, menos partículas y movimiento más lento. |
| ✨ Explosión | Lanza una ráfaga de notas (igual que la barra espaciadora). |
| 🧽 Limpiar | Borra el lienzo. |
| ⛶ Pantalla | Pantalla completa, sin distracciones (si el navegador lo permite). |

## Opciones para adultos (🔒)

La app empieza **bloqueada**: solo se ven los botones grandes. Para ver las demás opciones, **mantén presionado 🔒 durante 3 segundos**. Para volver a bloquear, toca 🔓 una vez.

| Botón | Qué hace |
| --- | --- |
| Escala | Cambia entre Pentatónica, Menor, Japonesa y Blues. |
| Eco | Activa o desactiva el eco (delay). |
| ● Grabar | Graba lo que suena y descarga el audio (`.webm`, `.ogg` o `.m4a`, según el navegador) al detener. |

El modo calma y el bloqueo se recuerdan en cada dispositivo.

**Tip para tableta o celular:** para que no puedan salir de la app, usa el bloqueo del sistema: *Acceso guiado* en iPhone/iPad (Ajustes → Accesibilidad) o *Fijar pantalla* en Android (Ajustes → Seguridad).

## Tecnología

Un solo archivo HTML con Canvas 2D, Web Audio API y MediaRecorder. Sin dependencias.
