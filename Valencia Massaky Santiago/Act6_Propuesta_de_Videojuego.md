# Propuesta Conceptual: Vectra-Shift
**Categoría:** Plataformas de Alta Velocidad / Precision Runner  
**Estado:** Propuesta Inicial (GDD Rev. 0)

---

## 1. Visión General
**Vectra-Shift** es un videojuego de plataformas en 2D donde el suelo es un obstáculo y el impulso es el único recurso vital. El diseño se centra en la **gestión de la inercia** y la optimización de trayectorias, transformando el movimiento en una danza rítmica de alta precisión.

---

## 2. Elementos Formales

### A. Mecánica Principal: *Vector-Chaining* (Encadenamiento de Vectores)
El personaje no corre mediante una aceleración lineal estándar. La velocidad se acumula de forma exponencial al encadenar acciones acrobáticas sin tocar superficies horizontales planas:
* **Wall-kick:** Rebotes en paredes que multiplican el vector de movimiento.
* **Grapple-swing:** Uso de un gancho para convertir la caída en aceleración centrípeta.
* **Sliding:** Deslizamiento en rampas que convierte la gravedad en velocidad horizontal.

### B. Objetivo del Jugador
Transportar el "Vectra-Core" hasta el final del nivel en el menor tiempo posible. El sistema de progresión se basa en **Ranks (D a S)**, donde el rango más alto requiere mantener el "Estado de Flujo" durante casi la totalidad del trayecto.

### C. Reglas Básicas
1.  **Ley de Inercia:** La velocidad solo se conserva mediante acciones activas. Quedarse quieto o caminar normalmente drena el Medidor de Flujo.
2.  **Fricción Selectiva:** * *Zonas de Impulso (Verdes):* Incrementan la velocidad máxima.
    * *Zonas de Fricción (Rojas):* Detienen al jugador en seco y reinician el contador de combo.
3.  **Límite de Estabilidad:** Si el jugador se detiene por completo, el "Vectra-Core" se sobrecarga (game over), obligando a mantener un ritmo mínimo constante.

---

## 3. Experiencia Buscada (Aesthetics)
El objetivo primordial es inducir el **"Estado de Flujo" (Flow)**.

* **Sensación:** El jugador debe sentir una mezcla de euforia y control absoluto. Al eliminar la fricción mental entre la intención y la ejecución, el nivel deja de ser un mapa y se convierte en una "partitura" visual.
* **Por qué funciona:** La mecánica de *Vector-Chaining* genera una gratificación inmediata. Cada acción exitosa se traduce en un aumento visual de la velocidad (efecto de túnel, rastro de luz), validando constantemente la habilidad técnica del usuario.

---

## 4. Coherencia de Diseño (Marco MDA)

| Componente | Definición | Relación de Coherencia |
| :--- | :--- | :--- |
| **Mechanics** | Aceleración exponencial y física de vectores. | Provee las herramientas necesarias para alcanzar la velocidad deseada. |
| **Dynamics** | Optimización de rutas y "atajos aéreos". | El jugador deja de buscar el camino fácil y busca el camino más rápido para evitar la pérdida de inercia. |
| **Aesthetics** | Desafío, Sensación y Maestría. | La música y los efectos visuales escalan con la velocidad, recompensando la ejecución perfecta de las mecánicas. |

> **Justificación:** La coherencia reside en que el **castigo** (perder velocidad al tocar zonas rojas) no es arbitrario, sino que refuerza el **objetivo** (llegar rápido). Sin la amenaza de perder el impulso, el sentimiento de maestría al conservar la velocidad máxima desaparecería.

---
*Documento generado para el Repositorio de Proyectos - 2026*
