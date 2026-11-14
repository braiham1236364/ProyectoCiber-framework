# Especificación de las Fases del Framework

El ciclo de vida operativo de `ProyectoCiber-framework` se estructura en seis fases secuenciales e iterativas. Cada fase define objetivos, actividades clave, entradas y entregables obligatorios.

## Fase 01: Preparación
* **Objetivo:** Establecer el marco legal, técnico y operativo antes de iniciar cualquier prueba.
* **Actividades:** Definición de activos dentro del alcance, firma de autorización escrita, establecimiento de reglas de compromiso (RoE) y preparación del entorno en Kali Linux.
* **Entregables:** Acta de alcance y autorización, matriz de activos autorizados.

## Fase 02: Prevención
* **Objetivo:** Evaluar la postura defensiva inicial y documentar los controles existentes.
* **Actividades:** Revisión de configuraciones base, verificación de políticas de endurecimiento (hardening) y levantamiento de línea base de red y servicios.
* **Entregables:** Inventario de controles preventivos y línea base del sistema.

## Fase 03: Identificación
* **Objetivo:** Descubrir superficie de exposición, vulnerabilidades y vectores de ataque mediante técnicas controladas.
* **Actividades:** Ejecución de laboratorios técnicos (reconocimiento pasivo/activo, enumeración DNS, análisis web, OSINT y factor humano).
* **Entregables:** Bitácoras de comandos ejecutados, capturas de tráfico y hallazgos preliminares (`FC-LAB-XXX`).

## Fase 04: Análisis
* **Objetivo:** Validar los hallazgos técnicos, descartar falsos positivos y calcular el nivel de riesgo.
* **Actividades:** Correlación de evidencias, mapeo con MITRE ATT&CK / OWASP y valoración de impacto y probabilidad.
* **Entregables:** Matriz de riesgos priorizada y reporte técnico de vulnerabilidades confirmadas.

## Fase 05: Mitigación
* **Objetivo:** Aplicar controles correctivos para remediar o reducir los riesgos identificados.
* **Actividades:** Desarrollo de recomendaciones accionables, aplicación de parches, reconfiguración de servicios y capacitación en concienciación.
* **Entregables:** Plan de remediación ejecutado y registro de cambios aplicados.

## Fase 06: Verificación
* **Objetivo:** Comprobar que las mitigaciones cerraron efectivamente las brechas sin afectar la operación normal.
* **Actividades:** Reejecución controlada de las pruebas de la Fase 03 (re-testing) y validación de ausencia de regresiones.
* **Entregables:** Informe final de cierre y certificación de estado de seguridad.
