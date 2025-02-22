# 🎮 Recreando clásicos: Arkanoid - Unity

Este proyecto es una recreación del clásico *Arkanoid* de Taito usando Unity. Se ha diseñado para ser fiel al juego original, manteniendo su jugabilidad simple pero desafiante.
Este proyecto forma parte de una serie de recreaciones de videojuegos clásicos, diseñados para aprender, experimentar y mejorar habilidades en desarrollo de juegos con Unity.

> **Objetivo**: Reproducir la experiencia del *Arkanoid* original con mecánicas fieles y código optimizado.

---

## 🎥 Referencias al juego original

Estos videos ayudan a comprender los detalles del diseño y la jugabilidad original para lograr una recreación fiel.
Para entender mejor la jugabilidad y el diseño original, puedes revisar los siguientes videos:

1. [Arkanoid © 1986 Taito - Arcade Gameplay](https://www.youtube.com/watch?v=k1kKf8AdRac)  
2. [Arcade Longplay [270] Arkanoid](https://www.youtube.com/watch?v=Th-Z6QQ5AOQ)  
3. [Wikipedia](https://es.wikipedia.org/wiki/Arkanoid)

---

## 📌 Game design

Entorno:
- Pantalla fija con paredes en los bordes y una área de juego limitada.

Entidades:
- **Paleta**: controlada por el jugador, se mueve de izquierda a derecha.
- **Bola**: se desplaza rebotando en la pantalla y destruye ladrillos al impactarlos.
- **Ladrillos**: bloques destructibles que pueden requerir uno o más impactos para ser eliminados.
- **Power-ups** (opcionales): modificadores que alteran la jugabilidad (ej. expandir la paleta, disparar, multiplicar la bola).

Comportamientos:
- La bola rebota en los bordes y en la paleta.
- Al eliminar todos los ladrillos, se pasa al siguiente nivel.
- Si la bola cae por la parte inferior, el jugador pierde una vida.
- El juego termina cuando el jugador pierde todas sus vidas.

Interfaz:
- Se muestra la puntuación en la parte superior.
- Indica la cantidad de vidas restantes.
- Opción de iniciar una nueva partida al perder todas las vidas.

---

## 🛠️ Requisitos

- **Unity**: Versión **60000.0.32f1** o superior (recomendado).  
- **.NET 6** o superior.  
- **Editor de código** compatible con Unity (Visual Studio o VS Code).  
- **Git** (opcional, para clonar el repositorio).  

---

## 🎮 Controles del juego

| Acción         | Tecla |
|---------------|----|
| Mover izquierda  | `A` o `←` |
| Mover derecha   | `D` o `→` |
| Lanzar bola / Start | `Espacio` |

---

## 🐟 Licencia

Este proyecto se distribuye bajo la licencia **MIT**.  
Puedes usarlo, modificarlo y distribuirlo libremente.

---

¡Diviértete desarrollando *Arkanoid* y recreando clásicos! 🌐

