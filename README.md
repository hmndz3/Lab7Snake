# Snake con React

Implementación del juego clásico **Snake** usando React y Babel vía CDN, sin herramientas de build. Todo el código vive en un solo archivo `index.html`.

## Cómo jugar

1. Descarga o clona el repositorio.
2. Abre `index.html` en tu navegador.
3. Selecciona la dificultad y dale a **Jugar**.

### Controles

1. ↑ ↓ ← → - Mover la serpiente 
2. W A S D - Mover (otra opcion)
3. Espacio / Enter - Volver al menú (en Game Over) 

### Objetivo

Comer la comida roja para crecer y sumar puntos. Evita chocar contra las paredes o tu propio cuerpo.

## Dificultades

 - Nivel  Velocidad 

 - Fácil -Lenta 
 - Normal - media 
 - Difícil - rápida 

## Estructura del proyecto

- LAB7SNAKE/
- ├── index.html 
- └── README.md

### Componentes

- **App** — contenedor principal
- **Game** — maneja el estado y la lógica del juego
- **Board** — renderiza la cuadrícula
- **Snake** — representa la serpiente
- **Food** — representa la comida
- **Score** — muestra el puntaje y la dificultad
- **StartMenu** — pantalla de inicio con instrucciones y selector de dificultad
