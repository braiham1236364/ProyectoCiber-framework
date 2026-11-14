# ProyectoCiber-framework (NOMBRE_FW v0.1)

**Framework Metodológico para la Evaluación, Análisis y Fortalecimiento de la Ciberseguridad**

## Descripción General
`ProyectoCiber-framework` es un marco metodológico diseñado para organizar, estandarizar y ejecutar evaluaciones de ciberseguridad de forma controlada y reproducible. Integra enfoques **Red Team**, **Blue Team** y **Purple Team**, abarcando seguridad en aplicaciones, OSINT, análisis forense, factor humano y entornos de inteligencia artificial.

## Ciclo de Vida Metodológico (6 Fases)
1. **01 Preparación:** Definición de alcance, activos, reglas de compromiso y autorización.
2. **02 Prevención:** Revisión de controles existentes y establecimiento de línea base.
3. **03 Identificación:** Ejecución de reconocimiento y pruebas técnicas controladas en Kali Linux.
4. **04 Análisis:** Validación de evidencias, estimación de impacto y matriz de riesgos.
5. **05 Mitigación:** Implementación de controles y medidas correctivas.
6. **06 Verificación:** Reejecución de pruebas para comprobar efectividad y ausencia de regresiones.

## Estructura del Repositorio
* `docs/`: Documentación teórica, arquitectura, metodología y glosario técnico.
* `framework/`: Especificación de fases, protocolos operativos y matrices de evaluación.
* `laboratorios/`: Catálogo práctico de laboratorios ejecutados en Kali Linux (`FC-LAB-001` a `FC-LAB-007`).
* `scripts/`: Utilidades y automatizaciones desarrolladas para las pruebas.
* `plantillas/`: Formatos estandarizados para fichas de laboratorio y reportes.
* `casos-estudio/`: Escenarios autorizados de validación empírica.
* `resultados/`: Métricas, indicadores y evidencias anonimizadas.

## Catálogo de Laboratorios (Kali Linux)
* `FC-LAB-001`: Comandos Shell y gestión de entornos en Kali Linux (`D01`).
* `FC-LAB-002`: DNS Footprinting con `nslookup` y `dig` (`D02`).
* `FC-LAB-003`: Clonación controlada de sitios web con `HTTrack` (`D03`).
* `FC-LAB-004`: Análisis forense y esteganografía con `Steghide` (`D06`).
* `FC-LAB-005`: Ingeniería social y concienciación organizacional (`D05`).
* `FC-LAB-006`: Reconocimiento OSINT con `Maltego` (`D02`).
* `FC-LAB-007`: Pruebas de seguridad web y APIs con `Burp Suite` (`D03/D04`).
