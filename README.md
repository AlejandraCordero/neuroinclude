# NEUROINCLUDE: Plataforma Neuroeducativa y de Tecnología Inclusiva 🧠✨

> *Discover your brain. Understand your strengths. Develop your potential.*

Prototipo desarrollado para el **Hacktoberfest Hack Day La Paz × NeuroTech UMSA 2026**.

---

## 📌 ¿Qué es NEUROINCLUDE?
**NEUROINCLUDE** es una aplicación web interactiva que conecta la neurociencia, la accesibilidad universal y la inteligencia artificial abierta para explorar perfiles cognitivos (atención y memoria) desde una **perspectiva de fortalezas**, rechazando visiones patologizantes o deficitarias en el ámbito educativo de Bolivia y la región.

---

## 🎯 Retos y Categorías del Hackathon
Este proyecto postula formalmente a las siguientes categorías oficiales del evento:
1. **Best Open-Source AI Project (DigitalOcean):** Uso de tecnologías de código abierto y arquitectura modular para democratizar herramientas de evaluación cognitiva educativa.
2. **Best Use of Gemma 4 (Google):** Integración conceptual de modelos de la familia Gemma / Gemini para estructurar perfiles de aprendizaje personalizados y orientaciones pedagógicas éticas.

---

## 🛠️ Arquitectura y Stack Tecnológico
El prototipo está construido como una **SPA (Single Page Application)** autocontenida y optimizada para ejecución inmediata:
* **Frontend:** HTML5, CSS3 (Diseño Accesible WCAG 2.1 AA) y JavaScript Nativo (Vanilla JS).
* **Motor Cognitivo (JS):** Tarea Go/No-Go con cronometría de alta precisión (`performance.now()`) y Memoria de Trabajo Secuencial visoespacial.
* **Laboratorio EEG (Simulación & Roadmap):** Visualizador dinámico de bandas de frecuencia (Delta, Theta, Alfa, Beta) diseñado para conectarse vía *Web Bluetooth API* a hardware abierto (ej. OpenBCI / Muse).
* **Gobernanza de Datos y Privacidad:** Almacenamiento efímero en memoria mediante identificadores cifrados (UUIDv4) con política de **Zero-Trace** (cero persistencia de datos sensibles sin consentimiento).

---

## ⚖️ Matriz de Honestidad Técnica (Lo Real vs. Lo Demostrativo)
Para cumplir con el rigor científico y ético requerido en el hackathon, distinguimos claramente las capacidades del prototipo:

| Módulo / Funcionalidad | Naturaleza | Descripción Técnica |
| :--- | :--- | :--- |
| **Atención Go/No-Go** | **100% REAL** | Medición de latencias en milisegundos, aciertos y registro de falsas alarmas. |
| **Memoria Visoespacial** | **100% REAL** | Generación estocástica de secuencias interactivas en cuadrícula. |
| **Trazo Temporal EEG** | **DEMOSTRATIVO / SINTÉTICO** | Renderizado en Canvas con modulación estocástica y funciones trigonométricas. |
| **Generador de Perfil** | **100% REAL (Reglas)** | Inferencia paramétrica local orientada a fortalezas, con **cero diagnósticos clínicos**. |

---

## 🚀 Guía de Instalación y Ejecución Local
No requiere instalación de dependencias, Node.js ni compilación previa.

1. Clona el repositorio o descarga el archivo fuente:
   ```bash
   git clone [https://github.com/AlejandraCordero/neuroinclude.git](https://github.com/AlejandraCordero/neuroinclude.git)
