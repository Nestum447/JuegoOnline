# JuegoOnline
Ver juego
https://nestum447.github.io/JuegoOnline/
# MiniJuegoJS - Juego con Sprites Animados y Fondo Transparente

MiniJuegoJS es un juego interactivo en **HTML, CSS y JavaScript** que permite:

- Mover un personaje con **joystick táctil** (compatible con celulares y tablets).  
- Usar **spritesheets** para el jugador y enemigos con **fondo transparente**, mostrando animaciones fluidas.  
- Obstáculos y enemigos en movimiento que aumentan la dificultad.  
- Puntaje y niveles que progresan mientras juegas.  
- Sonidos de fondo y efectos al perder puntos.  

Esta versión viene con **sprites incluidos** para que puedas jugar directamente sin seleccionar archivos externos.

---

## 📂 Archivos del repositorio

- `index.html` → Archivo principal del juego.  
- `README.md` → Este archivo con instrucciones.  
- `assets/player.png` → Sprite incluido del jugador (6 frames).  
- `assets/enemy.png` → Sprite incluido del enemigo (6 frames).  

---

## 🚀 Cómo usar

1. Clona o descarga el repositorio:

```bash
git clone https://github.com/nestum447/MiniJuegoJS.git
Abre index.html en cualquier navegador moderno (Chrome, Edge, Firefox) o despliega en GitHub Pages.

Usa el joystick táctil para mover al jugador en la pantalla.

Evita obstáculos, esquiva enemigos y acumula puntos.

El juego reproduce sonido de fondo y un efecto al perder puntos.

🎨 Requisitos para las imágenes (si quieres reemplazarlas)

Formato: PNG con fondo transparente.

Sprite horizontal: todos los frames deben estar en una misma fila.

Tamaño recomendado: aproximadamente 50x50 píxeles por frame.

⚡ Funcionalidades

Animación por spritesheet para jugador y enemigos.

Colisiones por bounding boxes ajustadas.

Obstáculos estáticos en el mapa.

Puntaje y niveles que aumentan con el tiempo.

Totalmente responsive en móviles y tablets.

👨‍💻 Personalización

Puedes cambiar fácilmente:

Velocidad del jugador y enemigos (jugador.velocidad, enemigos[].velocidad).

Tamaño de los sprites (jugador.size, enemigos[].size).

Sonidos (sonidoFondo, sonidoPerder).

Obstáculos (obstaculos array).

Sprites: reemplaza assets/player.png o assets/enemy.png por tus propios PNGs.

📌 Nota

Para mejores resultados, asegúrate de usar sprites con transparencia y frames alineados horizontalmente.

El juego funciona mejor en navegadores modernos y dispositivos con buena capacidad gráfica.

📄 Licencia

Este proyecto es libre de usar y modificar. No requiere dependencias externas más allá de un navegador moderno.


---
