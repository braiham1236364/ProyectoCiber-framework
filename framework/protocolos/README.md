# Protocolos Operativos del Framework

Los protocolos operativos establecen las directrices obligatorias de seguridad, manejo de evidencia y restricción de alcance durante la ejecución del framework.

## 1. Protocolo de Autorización y Alcance
* Ninguna prueba técnica o de reconocimiento activo puede ejecutarse sin un documento de autorización firmado por el propietario del activo.
* El alcance debe delimitarse explícitamente mediante direcciones IP, rangos de red, nombres de dominio o rutas de aplicaciones autorizadas.

## 2. Protocolo de Ejecución Segura en Kali Linux
* Las herramientas utilizadas (escáneres, frameworks de explotación o simuladores) deben configurarse para limitar la tasa de peticiones y evitar la denegación de servicios involuntaria en entornos de producción.
* Toda actividad ofensiva debe registrarse mediante bitácoras de terminal o herramientas de captura para garantizar la trazabilidad forense.

## 3. Protocolo de Manejo de Hallazgos y Evidencias
* Las evidencias recopiladas (capturas de pantalla, hashes, volcados de memoria o registros de tráfico) deben almacenarse de forma segura y anonimizada en la carpeta `resultados/`.
* Los hallazgos críticos deben reportarse inmediatamente al coordinador del equipo defensivo (Purple Team) para su contención prioritaria.
