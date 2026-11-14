# Centre — : Misión Lunar y Marciana 🚀🌕🔴

**Centre (Esferas 19)** es un simulador educativo interactivo basado en navegador, diseñado para que niños de **7 a 12 años** (junto a docentes y familias) administren un puesto avanzado en la Luna y Marte, experimentando las compensaciones reales de ingeniería (*trade-offs*) detrás de la supervivencia en el espacio profundo.

🔗 **Demo Jugable en Vivo:** https://maxieme-netizen.github.io/centre/

---

## 🎯 ¿Qué problema resuelve?
La divulgación espacial para niños suele quedarse en carteles abstractos o asumir conocimientos técnicos avanzados. **Centre** traduce las restricciones reales que enfrentan los planificadores de misiones de la NASA en mecánicas táctiles y decisiones donde **ninguna opción es gratuita**: reforzar el escudo contra una tormenta solar o operar sensores consume energía que luego puede faltar para el soporte vital o la ciencia.

---

## 🧩 Las 5 Etapas Interactivas del Simulador
1. **Esfera 1 — Academia Espacial:** 5 sectores guiados por relator de voz en español sobre captación solar en Zigzag a 70° (medida en *qums*), bancos de baterías para la noche lunar de 14 días, regolito 3D e hidroponía.
2. **Esfera 2 — Plastilina Electrónica 60×60 (3.600 Sensores):** Matriz táctil 3D en `Three.js` sincronizada con un radar LED 2D sobre 5 sitios reales (*Cráter Shackleton*, *Vallis Schröteri*, *Rima Hadley*, *Mare Tranquillitatis* en la Luna y *Cráter Jezero* en Marte):
   - **Modo Puente Rover:** Nivelar grietas para que un vehículo autónomo cruce con éxito.
   - **Modo Muro Escudo Anti-Radiación:** Levantar bermas de regolito alrededor de la cápsula equilibrando la reducción de dosis de radiación (`NASA RadLab` / `OSDR`) frente a la pérdida de energía por sombra sobre los paneles solares.
3. **Esfera 3 — Taller de Hábitats con Compensaciones Reales:** Cada mejora (paneles en Zigzag 70°, domo de regolito impreso en 3D, bio-huerta hidropónica) aporta beneficios claros a cambio de costos reales de energía y despliegue.
4. **Esfera 4 — Simulador de Misión por 3 Soles:** Gestión de recursos en competencia (**Energía**, **Soporte Vital** y **Salud/Escudo**) frente a erupciones solares reales de **NASA DONKI**, desgaste biológico (`NASA OSDR`) y retrasos de comunicación Tierra–Marte.
5. **Esfera 5 — Simulador de Órbita y Acoplamiento:** Maniobra orbital con propulsores RCS, física *Clohessy-Wiltshire* y sonar acústico de proximidad hasta lograr el acoplamiento (*Hard Dock*).

---

## 📡 Fuentes de Datos Abiertos (NASA & CSA)
* **NASA Open APIs — DONKI:** Erupciones solares y clima espacial (`https://api.nasa.gov/`), con respaldo de conjunto de datos reales archivados para operación offline.
* **NASA OSDR & RadLab:** Dosimetría de radiación y biología espacial (`https://osdr.nasa.gov/bio/` y `https://osdr.nasa.gov/bio/radlab`).
* **NASA Mars Trek & LRO:** Elevación y sitios reales en Marte y la Luna (`https://trek.nasa.gov/mars/` y `https://science.nasa.gov/moon/`).
* **Canadian Space Agency (CSA):** Recursos educativos sobre producción de alimentos en la Luna y zonas remotas (`https://www.asc-csa.gc.ca/eng/youth-educators/toolkits/food-production/`).

---

## 🛠️ Stack Tecnológico
* **Frontend & Gráficos 3D:** HTML5, Tailwind CSS, JavaScript (ES6+), Three.js (r128 WebGL) y HTML5 Canvas 2D.
* **Accesibilidad & Audio:** Web Speech API (`SpeechSynthesis` en español) y Web Audio API.

---

## 🤖 Declaración de Transparencia (Súper Inteligencia / SI)
Se utilizaron herramientas de asistencia de IA para acelerar la estructuración de código JavaScript/Three.js y la redacción pedagógica. La arquitectura, mecánicas de juego, integración de datos científicos y validación final fueron diseñadas y verificadas por el equipo sin utilizar marcas ni logotipos de la NASA.
