# 📑 AXIOM SYSTEMS // CYBER-CHRONO ⌚✨

Un desarrollo frontend premium de una **landing page interactiva e inmersiva** en 3D inspirada en la estética Cyberpunk Neo-Tokio, el lujo callejero y el diseño técnico de alto impacto. 

Este proyecto ha sido concebido bajo la arquitectura de desarrollo **monolítico**, concentrando todo el renderizado gráfico, la coreografía de animaciones y la capa de contenido en un único archivo de ejecución.

---

## 🚀 Características Clave

* **Renderizado 3D Procedimental (Three.js):** El reloj inteligente transparente y sus componentes mecánicos internos se generan en tiempo real mediante geometrías puras. Evita la carga de archivos `.gltf` o `.obj` pesados, optimizando el tiempo de carga al instante.
* **Materiales de Alta Fidelidad Física (PBR):** Uso de `MeshPhysicalMaterial` con propiedades avanzadas de transmisión de luz, refracción (`ior`) y rugosidad para simular un chasis de cristal y grafeno translúcido hiperrealista.
* **Coreografía Scroll-Driven (GSAP + ScrollTrigger):** Orquestación fluida y matemática de cada tramo de la página. Al hacer scroll, los componentes del reloj sufren un despiece explosivo (*X-Ray*), mutan de color y modifican la posición de la cámara de manera sincronizada.
* **Interacción Inercial con el Ratón:** Implementación de un algoritmo de interpolación lineal (*Lerp*) que calcula la posición del puntero para inclinar y rotar levemente el modelo 3D, reflejando de forma dinámica las luces de neón en el cristal.
* **Modo Crítico de Sobrecarga ("Overload"):** Sistema interactivo mediante el botón clandestino *"DO NOT PRESS"*. Al activarse, la web ejecuta una línea de tiempo secundaria que simula un hackeo visual: inversión de color por CSS (`mix-blend-mode: difference`), aceleración extrema de engranajes y mutación lumínica a alerta roja.

---

## 🛠️ Arquitectura Técnica y Stack

La web está construida de manera autocontenida sin frameworks (`React`, `Next.js` o `Vue`), garantizando un rendimiento óptimo en navegadores de escritorio y dispositivos móviles:

* **Estructura & Estilos:** HTML5 Semántico + CSS3 (Variables nativas, animaciones `@keyframes` y filtros de distorsión).
* **Motor 3D:** [Three.js (r128)](https://threejs.org/)
* **Motor de Animación:** [GSAP 3.12.2 + ScrollTrigger Plugin](https://greensock.com/gsap/)

---
