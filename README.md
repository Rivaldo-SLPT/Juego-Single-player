# Pingüino Aventurero

Un pequeño juego de plataformas estilo arcade creado en HTML5, CSS y JavaScript puro.

El jugador controla a un pingüino que debe recorrer distintos niveles, recoger peces, evitar enemigos y llegar a la bandera final.

## 🎮 Controles

- Flechas o A / D: mover al personaje
- Espacio o W: saltar
- Shift: correr
- Enter: continuar tras completar un nivel o reiniciar tras perder

## 🧩 Objetivo del juego

- Recoger peces para ganar puntos
- Conseguir el pez dorado para activar un impulso de velocidad
- Evitar a los enemigos o saltar sobre ellos para derrotarlos
- Llega a la bandera final para completar cada nivel

## 🕹️ Mecánicas incluidas

- Movimiento lateral con aceleración y freno suave
- Salto con control clásico de plataforma
- Coyote time y buffer de salto
- Sprint con velocidad adicional al pulsar Shift
- Sistema de vidas y puntuación
- Dos niveles con plataformas, huecos, enemigos y objetos

## 🏗️ Estructura

El proyecto consta de un único archivo HTML:

- `pinguino_platformer.html`: contiene toda la lógica del juego, el dibujo del canvas y la interfaz.

## ▶️ Cómo ejecutarlo

1. Abre la carpeta del proyecto en tu navegador.
2. Puedes abrir directamente el archivo `pinguino_platformer.html`.
3. O bien, si prefieres servirlo localmente, ejecuta desde la carpeta del proyecto:

```bash
python -m http.server 8000
```

Luego entra en:

```text
http://localhost:8000/pinguino_platformer.html
```

## 🎨 Tecnologías usadas

- HTML5
- CSS3
- JavaScript
- Canvas 2D

## 📌 Nota

Este proyecto es una demo ligera de juego de plataformas, ideal para aprender lógica de física, colisiones, cámara y rendering con canvas.
