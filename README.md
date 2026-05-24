# K34-Superviviente

Un videojuego de acción frenética y supervivencia desarrollado en equipo durante una **Game Jam**. El proyecto destaca por la gestión de físicas en tiempo real para oleadas masivas de enemigos y un sistema dinámico de *power-ups*.

👉 **[¡Juega en Itch.io!](https://k34dev.itch.io/k34-superviviente)** 👉 **[Ver perfil del proyecto en Conduit Gaming](https://conduitgaming.com/games/0874c44d-fb20-42f1-835a-95eeada77457)**

👉 **[⬇️ Descarga para Windows (.zip)](https://github.com/RubenClon/K34-Superviviente/releases/download/v1.0/k34survivor.zip)** 
👉 **[⬇️ Descarga para Android (.apk)](https://github.com/RubenClon/K34-Superviviente/releases/download/v1.0/k34survivor.apk)**  
---

## 👥 Desarrollo en Equipo y Colaboración

Este proyecto fue desarrollado en colaboración directa con una **diseñadora gráfica**, lo que me permitió aplicar metodologías ágiles para la integración continua de assets artísticos, animaciones y diseño de interfaz (UI) dentro del motor de juego, manteniendo un flujo de trabajo coordinado bajo las estrictas restricciones de tiempo de una Game Jam.

---

## 🚀 Desafíos Técnicos e Implementación

- **Optimización de Rendimiento (Manejo de Multitudes):** Programación y optimización del motor para gestionar **oleadas masivas de hasta 200 enemigos simultáneos** en pantalla sin caídas de frames, asegurando la fluidez en el renderizado y las colisiones.
- **Sistema de Progresión y Power-Ups:** Implementación de una arquitectura escalable para la subida de niveles y la modificación en tiempo real de los atributos del jugador:
  - *Disparo Circular:* Algoritmo para calcular trayectorias de proyectiles en 8 direcciones simultáneas.
  - *Bala Perforadora:* Lógica de colisiones avanzadas que permite al proyectil atravesar múltiples enemigos sin destruirse.
  - *Bomba de Área:* Sistema de limpieza de pantalla mediante triggers globales.
- **Persistencia de Datos (Ranking):** Creación de un sistema para grabar y persistir el nombre y puntuación de los jugadores en una tabla de clasificación local.
- **Dificultad Escalable:** Implementación de modificadores de daño dinámicos que alteran la curva de dificultad según la elección del usuario.

## 🛠️ Tecnologías y Herramientas

- **Motor:** Godot Engine / [Indica si usaste otro motor].
- **Control de Versiones:** Git / GitHub para la coordinación del código y la integración de assets.
- **Plataformas de Despliegue:** Itch.io y Conduit Gaming.

## 🎮 Controles del Juego

- **Movimiento:** ⬆️⬇️⬅️➡️ (Flechas del teclado)
- **Pausa:** `ESC`
- **Disparo:** Automático (basado en temporizadores y cadencia variable).
