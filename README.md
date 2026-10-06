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
| 🎵 Sonido | Cambia de instrumento: Clásico 🎵, Piano 🎹, Campanas 🔔, Marimba 🪵 y Voz 🎤. |
| 🎶 Canción | Modo canción para los más pequeños: cada toque o trazo, en cualquier parte, toca la siguiente nota de *Estrellita*, *Martinillo* u *Oda a la alegría*. No hay forma de equivocarse; al terminar hay fiesta y vuelve a empezar. Tócalo otra vez para cambiar de canción, y una vez más para volver a pintar libre. |
| 🧽 Limpiar | Borra el lienzo. |
| ⛶ Pantalla | Pantalla completa, sin distracciones (si el navegador lo permite). |

## Más opciones (🔒)

La app empieza **bloqueada**: solo se ven los botones grandes. Para ver las demás opciones, **mantén presionado 🔒 durante 3 segundos**. Para volver a bloquear, toca 🔓 una vez.

| Botón | Qué hace |
| --- | --- |
| Escala | Cambia entre Pentatónica (China), Mayor, Menor, Japonesa, Blues, Francesa (Debussy) y Árabe. |
| Eco | Activa o desactiva el eco (delay). |
| ● Grabar | Graba lo que suena y descarga el audio (`.webm`, `.ogg` o `.m4a`, según el navegador) al detener. |
| 🎯 Retos | Juegos de música (ver abajo). |
| 🔬 Ciencia | Muestra la onda del sonido en vivo, el nombre de la nota (español e inglés), su frecuencia en Hz y datos curiosos de física del sonido. |
| 📷 Guardar dibujo | Descarga el dibujo del lienzo como imagen `.png`. |

El modo calma, el instrumento, el modo ciencia, el bloqueo y el récord se recuerdan en cada dispositivo.

### 🎯 Retos de música

La pantalla se divide en 7 franjas de colores, una por nota: Do, Re, Mi, Fa, Sol, La y Si (de abajo hacia arriba).

- **🎯 Simón musical:** escucha la secuencia y repítela tocando las franjas. Cada acierto agrega una nota más. Si te equivocas, no pasa nada: se repite la misma secuencia. Guarda tu récord.
- **🎵 Canciones guiadas:** *Estrellita*, *Martinillo* (Frère Jacques) y *Oda a la alegría*. La franja que sigue brilla; tócala para avanzar.
- **✖ Salir** vuelve al lienzo.

**Tip para tableta o celular:** para que no puedan salir de la app, usa el bloqueo del sistema: *Acceso guiado* en iPhone/iPad (Ajustes → Accesibilidad) o *Fijar pantalla* en Android (Ajustes → Seguridad).

## Tecnología

Un solo archivo HTML con Canvas 2D, Web Audio API (osciladores, filtros y analizador) y MediaRecorder. Sin dependencias.
