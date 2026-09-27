# 🛡️ Escudo Sónico - Repelente Ultrasónico Offline (PWA)

Aplicación web progresiva (PWA) de ultra-alta frecuencia diseñada para ahuyentar y disuadir amenazas biológicas (**perros agresivos, zancudos/mosquitos y murciélagos**) utilizando **ondas senoidales puras** sintetizadas en tiempo real mediante la Web Audio API.

🌐 **Enlace directo a la aplicación:**  
👉 **[https://gmph2007.github.io/escudo-sonico-repelente/](https://gmph2007.github.io/escudo-sonico-repelente/)**

---

## ⚡ 100% Funcional Sin Internet (Modo Offline)
Esta aplicación está programada con arquitectura **PWA (Progressive Web App)** con Service Worker de última generación:
1. Una vez abierta por primera vez, el sistema guarda en caché todos los componentes (`index.html`, `manifest.json`, iconos y audio-engine).
2. Puedes apagar tus datos móviles, apagar el Wi-Fi o activar el **Modo Avión**, y la aplicación seguirá funcionando exactamente igual de potente.
3. No requiere descargar archivos pesados de audio MP3 externos: genera las ondas matemáticas directamente en el chip de sonido de tu dispositivo.

---

## 🐕 Modos de Protección Calibrados

### 1. 🐕 Defensa Canina (Perros Agresivos y Ladridos)
* **Silbato Canino (23,500 Hz):** Tono de ultra-alta frecuencia 100% inaudible para el oído humano adulto, pero sumamente agudo y molesto para el sistema auditivo canino.
* **Pulso de Choque (22 - 25 kHz):** Alternancia periódica ultrasónica para frenar ladridos continuos o disuadir aproximaciones agresivas.

### 2. 🦟 Defensa Anti-Zancudos y Mosquitos
* **Frecuencia Pura (17,400 Hz):** Onda senoidal limpia en el umbral acústico que perturba las antenas sensoriales de los mosquitos sin generar ruidos de motor ni zumbidos molestos en la habitación.
* **Barrido Dinámico (16,000 - 18,500 Hz):** Oscilación ascendente y descendente continua para evitar la habituación de los insectos.

### 3. 🦇 Inhibidor de Murciélagos
* **Interferencia de Ecolocalización (22,500 Hz):** Frecuencia ultrasónica sintonizada para dificultar la orientación y navegación espacial de murciélagos en techos y exteriores.

---

## 📲 Cómo Instalar en tu Celular (Android / Redmi / iPhone)

### En Android / Xiaomi / Redmi (Google Chrome):
1. Abre [https://gmph2007.github.io/escudo-sonico-repelente/](https://gmph2007.github.io/escudo-sonico-repelente/).
2. Toca el botón azul **"📲 Instalar en Celular"** en la pantalla, o abre los tres puntos `⋮` del navegador y presiona **"Instalar aplicación"** o **"Agregar a pantalla principal"**.
3. ¡Listo! Se creará un ícono en la pantalla de inicio de tu celular que abre la app a pantalla completa y sin conexión a internet.

### En iPhone / iPad (Safari):
1. Abre el enlace en Safari.
2. Toca el botón de Compartir (icono de caja con flecha hacia arriba).
3. Selecciona **"Agregar a pantalla de inicio"**.

---

## 🛠️ Tecnologías Utilizadas
* **HTML5 / CSS3 Moderno** (Diseño oscuro espacial responsive con efectos Glassmorphism).
* **Web Audio API** (Oscillators, GainNodes, Analysers en tiempo real sin latencia).
* **Canvas 2D** (Visualizador espectral en vivo de la frecuencia emitida).
* **Screen WakeLock API** (Mantiene la pantalla activa para evitar que el teléfono corte el audio por reposo).
* **Service Worker Cache-First** (Garantía de ejecución 100% offline).

---

Desarrollado y optimizado por [GMPH2007](https://github.com/GMPH2007).
