# Definición del Perfil de Jugador y Estructura de Juego: Vectra-Shift

**Proyecto:** Vectra-Shift  
**Documento:** Análisis de Audiencia y Estructura (Rev. 01)  
**Fecha:** Febrero 2026  

---

## 1. Perfil del Jugador Objetivo

El jugador de *Vectra-Shift* busca la **maestría técnica** por encima de la narrativa profunda. Es un perfil que encuentra placer en la repetición y la optimización de procesos.

* **Tipo de Jugador (Motivaciones):** Basado en la taxonomía de Bartle, se define como un **Achiever (Triunfador)**. Su motivación principal es la competencia (consigo mismo y otros) y el perfeccionamiento de habilidades motoras finas.
* **Plataforma Objetivo:** **PC y Consolas de sobremesa**. La mecánica de *Vector-Chaining* requiere una tasa de refresco alta (60+ FPS) y la precisión de periféricos con baja latencia (mando o teclado) para evitar la frustración por "input lag".
* **Tipo de Sesiones:** **Micro-sesiones de alta intensidad**. El diseño facilita sesiones cortas de 10 a 20 minutos, caracterizadas por el ciclo de "un intento más" (Trial & Error).
* **Nivel de Experiencia:** **Intermedio / Avanzado**. Jugadores familiarizados con el género de plataformas que buscan un reto mecánico superior al estándar.

---

## 2. Estructura General del Videojuego

### A. Loop Principal de Juego (Core Loop)
El bucle se define como: **Impulso ➔ Optimización de Trayectoria ➔ Feedback de Velocidad ➔ Meta/Reinicio**.
Cada acción exitosa alimenta el sistema de partículas y el ritmo de la música, validando la habilidad del jugador en tiempo real.

### B. Estructura de Niveles y Progresión
* **Niveles de "Ruta Múltiple":** No es un mundo abierto, sino niveles lineales con arquitectura vertical. Existen rutas "seguras" para terminar el nivel y rutas "de flujo" que requieren encadenar vectores para mantener la calificación S.
* **Progresión Basada en Habilidad:** La progresión no es numérica (stats), sino de contenido. Al dominar mecánicas básicas, se desbloquean niveles con "Gravedad Alterada" o "Modos Espejo".

### C. Ritmo y Dificultad
El ritmo es frenético y constante. La dificultad es **punitiva pero justa**: el fallo reinicia el nivel instantáneamente, eliminando los tiempos de carga para mantener la adrenalina.

---

## 3. Justificación Teórica

Las decisiones de diseño se fundamentan en los siguientes pilares:

### I. El Canal del Flow (Jesse Schell)
Según **Schell**, el diseño debe evitar que el jugador caiga en el aburrimiento (reto bajo) o la ansiedad (reto demasiado alto). *Vectra-Shift* soluciona esto mediante el **Rango Dinámico**: el nivel es fácil de completar (para evitar ansiedad), pero extremadamente difícil de "maestrear" con Rango S (para evitar aburrimiento), manteniendo al jugador siempre en el "Canal del Flow".

### II. El Contrato de Control (Scott Rogers)
**Rogers** afirma que en juegos de alta velocidad, la cámara y el control son sagrados. Se ha optado por un **FOV (Campo de Visión) Dinámico** que se expande según la velocidad. Esto es coherente con la plataforma elegida (PC/Consolas), permitiendo que el jugador tenga suficiente "tiempo de reacción" al ver los obstáculos con antelación en pantallas de gran formato.

### III. Dinámicas de Maestría (Dobrowolski)
**Dobrowolski** destaca que la motivación intrínseca nace del sentimiento de competencia. La estructura de niveles de *Vectra-Shift* incluye **Ghost Runs** (sombras de otros jugadores). Ver la trayectoria de un experto motiva al jugador a experimentar con la mecánica de *Vector-Chaining*, transformando el aprendizaje en una dinámica competitiva natural.

---
> **Nota de Diseño:** La coherencia entre el perfil "Achiever" y la estructura de "Micro-sesiones" garantiza que el jugador sienta progreso constante incluso en periodos cortos de juego.
