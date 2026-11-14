# Parte I y II: Fundamentación y Diseño Metodológico

## 1. Introducción y Propósito
El presente framework proporciona una ruta estructurada para planificar evaluaciones de seguridad autorizadas, identificar debilidades técnicas o humanas, analizar riesgos bajo criterios reproducibles y verificar la efectividad de las mitigaciones implementadas.

## 2. Referentes Técnicos y Normativos
| Referente | Aplicación en el Framework |
| :--- | :--- |
| **NIST CSF 2.0** | Organización de funciones de gobernanza y gestión de riesgos. |
| **NIST SP 800-115** | Guía técnica para ejecución de pruebas y evaluaciones de seguridad. |
| **MITRE ATT&CK** | Taxonomía de tácticas, técnicas y procedimientos (TTPs) adversarios. |
| **OWASP Top 10 / WSTG** | Estándar de pruebas y riesgos en aplicaciones web y APIs. |
| **ISO/IEC 27001 y 27005** | Contexto de gestión de seguridad de la información y tratamiento de riesgos. |

## 3. Arquitectura Metodológica Iterativa
El ciclo de evaluación opera de manera iterativa, donde los hallazgos verificados retroalimentan la preparación y los controles preventivos:

```mermaid
flowchart LR
    F1[01. Preparación] --> F2[02. Prevención]
    F2 --> F3[03. Identificación]
    F3 --> F4[04. Análisis]
    F4 --> F5[05. Mitigación]
    F5 --> F6[06. Verificación]
    F6 -. Retroalimentación .-> F1
    F6 -. Ajuste de Línea Base .-> F2
```

## 4. Actores y Responsabilidades (Enfoque Purple Team)
```mermaid
sequenceDiagram
    participant RS as Responsable del Sistema
    participant CE as Coordinador Evaluación
    participant AO as Analista Ofensivo (Red)
    participant AD as Analista Defensivo (Blue)
    participant CU as Custodio de Evidencias

    RS->>CE: Autoriza alcance y accesos
    CE->>AO: Asigna protocolos de prueba
    AO->>CU: Entrega bitácoras y evidencias técnicas
    AO->>AD: Comparte hallazgos (Purple Team)
    AD->>RS: Implementa controles y mitigaciones
    AO->>AD: Reejecuta pruebas de verificación
```
