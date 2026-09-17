# ¡Hola! Soy Javier Blanco 👋
### Analista SOC Level 1 / Ciberseguridad Junior

📍 Las Heras, Mendoza, Argentina | ✉️ adrian.blanco04012001@gmail.com | 📱 +54 261 755 6539
🔗 [LinkedIn](https://linkedin.com/in/javier-blanco-ab8114259) | 💻 [GitHub](https://github.com/javierblanco-code1)

---

## 👨‍💻 Sobre Mí

Postulante en formación activa enfocado en iniciar su carrera en Ciberseguridad como **Analista SOC L1 / Jr.** Poseo sólidos conocimientos en fundamentos de seguridad de la información, redes y programación en Python, respaldados por certificaciones de Cisco Networking Academy, Coursera, Fundación YPF y Edutin Academy. Construí un home-lab de SOC (Wazuh + Sysmon + Atomic Red Team) para practicar detección de amenazas de punta a punta, documentando cada caso como lo haría en un entorno real. Cuento además con experiencia laboral previa en atención al cliente y soporte operativo, destacándome por mi capacidad de resolución de problemas, trabajo en equipo y aprendizaje autodidacta constante.

---

## ⚙️ Habilidades Técnicas

* **Ciberseguridad:** Fundamentos de seguridad informática, identificación de amenazas, triaje de alertas, monitoreo con SIEM (Wazuh), detección basada en MITRE ATT&CK y principios de respuesta a incidentes.
* **Redes:** Protocolos esenciales, modelos OSI y TCP/IP, inspección de paquetes con Wireshark/TShark.
* **Herramientas SOC:** Wazuh, Sysmon, Atomic Red Team, VirtualBox (laboratorios aislados y segmentados).
* **Programación & Automatización:** Python básico, consumo de APIs REST, automatización de scripts e integración de modelos de Inteligencia Artificial para optimización de procesos.
* **Soft Skills:** Orientación al detalle, resolución de problemas bajo presión, comunicación efectiva y aprendizaje autodidacta.

---

## 🚀 Proyectos de Ciberseguridad (SOC L1)

### 1. Home-Lab SOC: Detección de Amenazas con Wazuh, Sysmon y Atomic Red Team
* **Descripción:** Laboratorio propio de SOC armado en VirtualBox sobre una red aislada, con un manager Wazuh 4.9 (Ubuntu Server) monitoreando un endpoint Windows 11 con Sysmon (configuración SwiftOnSecurity). Se emularon técnicas reales del framework MITRE ATT&CK con Atomic Red Team (por ejemplo, T1057 - Process Discovery) y se documentó la cadena de ejecución completa hasta la detección en el dashboard.
* **Tecnologías:** Wazuh, Sysmon, Atomic Red Team, VirtualBox, PowerShell, MITRE ATT&CK.
* **Impacto:** Demuestra el ciclo completo de un SOC L1 —despliegue de SIEM, ingesta de logs, emulación de adversarios y triaje de alertas—, validando en la práctica la detección de actividad sospechosa (cadena powershell.exe → cmd.exe → tasklist) con evidencia real de reglas disparadas.
* **Repo:** [github.com/javierblanco-code1/soc-l1-home-lab](https://github.com/javierblanco-code1/soc-l1-home-lab)

### 2. SOC L1: Automation for Log Analysis and AI-Driven Triage
* **Descripción:** Herramienta de automatización para la fase de triaje en un SOC. Lee archivos de registro del sistema (`syslog`), aísla patrones de eventos sospechosos (intentos fallidos de SSH, accesos 403 Forbidden) y genera un informe técnico de triaje estructurado mediante la API de Google Gemini.
* **Tecnologías:** Python, `google-genai`, `tenacity`, RegEx.
* **Impacto:** Reduce el tiempo de respuesta inicial (MTTR) al estructurar la severidad, IoCs y recomendaciones de mitigación para L2 de forma automatizada.

### 3. SOC L1: Threat Intelligence & IoC Enrichment with VirusTotal API
* **Descripción:** Script de inteligencia de amenazas diseñado para consultar la API REST v3 de VirusTotal y extraer la reputación en tiempo real de direcciones IP detectadas en alertas de red.
* **Tecnologías:** Python, API REST v3, `requests`, JSON.
* **Impacto:** Automatiza la verificación de Indicadores de Compromiso (IoCs) para acelerar la toma de decisiones sobre bloqueo o descarte de eventos en el firewall.

### 4. SOC L1: Network Traffic Analysis & Incident Reporting with Wireshark
* **Descripción:** Investigación de capturas de tráfico de red (`.pcap`) orientada a la detección de escaneos de puertos (TCP SYN) y exfiltración de tráfico inseguro (HTTP POST), complementada con la redacción estandarizada de un Ticket de Incidente SOC.
* **Tecnologías:** Wireshark, TShark, Display Filters, Markdown.
* **Impacto:** Demuestra capacidad analítica en la inspección profunda de paquetes (*Deep Packet Inspection*) y redacción técnica profesional para la escalada de incidentes.

---

## 📜 Certificaciones & Formación

* **Introduction to Cybersecurity** — Cisco Networking Academy (Ago 2026)
* **Conceptos básicos de redes (Networking Basics)** — Cisco Networking Academy (Sep 2026)
* **Python** — Coursera (8 hs, Jul 2026)
* **Ciberseguridad** — Fundación YPF (3 hs, Jul 2026)
* **Inteligencia Artificial para Desarrollo de Software** — Edutin Academy (120 hs, Jul 2026)
* **Domina la IA con Gemini** — Santander Open Academy (2 hs, Ago 2026)

---

## 💼 Experiencia Laboral
**Atención al Cliente y Soporte Operativo** | *Cooperativa Dalvian, Sanitarios López, Coseno Construcción en Seco, Minimarket Ideal, Mackenzie*
* Desarrollo de competencias clave transversales: trabajo en equipo bajo presión, comunicación efectiva, atención al público y capacidad analítica para la resolución de problemas en entornos operativos.
