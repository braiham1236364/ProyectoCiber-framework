# Matrices de Evaluación y Valoración de Riesgos

Este documento estandariza los criterios cuantitativos y cualitativos para clasificar hallazgos técnicos y priorizar acciones de remediación en la Fase 04 (Análisis).

## 1. Matriz de Probabilidad e Impacto
El nivel de riesgo inherente se calcula cruzando la probabilidad de explotación con el impacto técnico y operativo sobre el activo:

| Probabilidad \ Impacto | Bajo (1) | Medio (2) | Alto (3) | Crítico (4) |
| :--- | :--- | :--- | :--- | :--- |
| **Muy Alta (4)** | Medio (4) | Alto (8) | Crítico (12) | Crítico (16) |
| **Alta (3)** | Bajo (3) | Medio (6) | Alto (9) | Crítico (12) |
| **Media (2)** | Bajo (2) | Medio (4) | Medio (6) | Alto (8) |
| **Baja (1)** | Bajo (1) | Bajo (2) | Bajo (3) | Medio (4) |

## 2. Tiempos Máximos de Remediación (SLA)
De acuerdo con el puntaje obtenido en la matriz, el equipo defensivo (Blue Team) debe aplicar las mitigaciones dentro de los siguientes plazos:

* **Crítico (12 - 16):** Contención inmediata (menos de 24 horas) y parcheo definitivo en un máximo de 72 horas.
* **Alto (8 - 9):** Remediación planificada en un plazo máximo de 7 días calendario.
* **Medio (4 - 6):** Mitigación en el siguiente ciclo de mantenimiento (máximo 30 días).
* **Bajo (1 - 3):** Monitoreo continuo y tratamiento mediante buenas prácticas ordinarias.

## 3. Dominios de Evaluación del Framework
Cada laboratorio técnico y prueba ejecutada se clasifica dentro de uno o más de los siguientes dominios:

* **D01 - Gestión de Entornos y Sistemas:** Endurecimiento, permisos y administración segura en Linux.
* **D02 - Reconocimiento e Inteligencia (OSINT / DNS):** Exposición de infraestructura, registros públicos y huella digital.
* **D03 - Seguridad en Aplicaciones Web:** Análisis de superficie web, clonación y control de acceso.
* **D04 - Seguridad en APIs y Tráfico HTTP:** Interceptación, manipulación de peticiones y validación de sesiones.
* **D05 - Factor Humano e Ingeniería Social:** Resiliencia organizacional frente a vectores de persuasión y phishing.
* **D06 - Análisis Forense y Esteganografía:** Detección de información oculta e integridad de archivos.
