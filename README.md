#  Cybersecurity Learning Portfolio | Deniz Saliev

Bienvenido a mi portfolio técnico de ciberseguridad y operaciones de seguridad defensiva (Blue Team). Este repositorio funciona como índice central de los proyectos, prácticas de laboratorio y análisis técnicos desarrollados como preparación práctica previa a mi especialización de posgrado.

---

##  Sobre Mí
* **Perfil:** Estudiante de Administración de Sistemas Informáticos en Red (ASIR) con experiencia práctica previa como técnico de sistemas.
* **Objetivo Profesional:** Orientar mi carrera hacia perfiles de **Junior SOC Analyst / Blue Team**, aprovechando una base sólida en administración de sistemas, redes y automatización de procesos.
* **Enfoque Técnico:** Detección de amenazas, análisis e interpretación de logs (`Security.evtx`, `auth.log`), endurecimiento de sistemas (*hardening*), monitorización de eventos y reducción de superficie de exposición.

---

##  Proyectos y Repositorios Técnicos

A continuación se detallan los módulos técnicos desarrollados, acompañados de sus respectivos repositorios y evidencias de laboratorio:

### 1. [Bash Scripting & Automatización de Seguridad](https://github.com/DenizSaliev/bash-cybersecurity-basics)
* **Repositorio:** `bash-cybersecurity-basics`
* **Foco Técnico:** Shell scripting en entornos Linux (Ubuntu), automatización de tareas administrativas, parseo de logs del sistema (`/var/log/auth.log`) e identificación básica de anomalías operativas.
* **Evidencias Clave:** Scripts modulares para filtrado de direcciones IP, control de flujo y tratamiento de datos defensivo.

### 2. [Reconocimiento de Redes y Enumeración con Nmap](https://github.com/DenizSaliev/nmap-network-enumeration-basics)
* **Repositorio:** `nmap-network-enumeration-basics`
* **Foco Técnico:** Auditoría de red en segmento local controlado, análisis de puertos abiertos (TCP SYN vs. exhaustivo) e identificación de versiones de servicios (HTTP, SSH, FTP).
* **Evidencias Clave:** Tabla forense de riesgos por servicio expuesto, análisis de impacto defensivo y correlación con logs locales del host analizado.

### 3. [Seguridad en Windows Server y Active Directory](https://github.com/DenizSaliev/windows-security-basics)
* **Repositorio:** `windows-security-basics`
* **Foco Técnico:** Arquitectura de identidades en AD DS, gestión de Unidades Organizativas (OUs), despliegue de directivas de bloqueo de cuentas mediante GPO y auditoría granular en el Visor de Eventos (`eventvwr.msc`).
* **Evidencias Clave:** Trazabilidad completa de sesiones y ataques de autenticación mediante eventos clave (`4624`, `4625`, `4740`, `4647`), análisis de códigos NTSTATUS y verificación de la arquitectura cliente-servidor en la generación de telemetría.

### 4. [Fundamentos y Metodología SOC Junior](https://github.com/DenizSaliev/soc-junior-learning-path)
* **Repositorio:** `soc-junior-learning-path`
* **Foco Técnico:** Mentalidad operativa de analista Nivel 1 (Tier 1), diferenciación técnica entre Evento, Alerta e Incidente, análisis de causas raíz y descarte estructurado de falsos positivos comunes.
* **Evidencias Clave:** Desarrollo y triaje de 5 casos prácticos simulados (ataques de contraseña, persistencia mediante usuarios y servicios anómalos, sockets a la escucha y balizamiento DNS saliente).

---

## 🎯 Preparación Previa y Objetivos en el Máster

### Qué he preparado antes de iniciar el Máster:
* **Entornos de prueba locales:** Despliegue de infraestructuras virtualizadas compuestas por controladores de dominio Windows Server, clientes Windows 11 y máquinas Linux interconectadas en subredes privadas aisladas.
* **Metodología analítica:** Transición desde la mera ejecución de herramientas hacia la interpretación metódica de telemetría, lectura de códigos de subestado y documentación estructurada sin asunciones categóricas.
* **Consistencia técnica:** Documentación de cada hallazgo con justificación defensiva, rutas absolutas de ficheros de registro y procedimientos de escalado hacia niveles superiores.

### Qué busco aprender y desarrollar durante el Máster:
* **Especialización en Redes + IA:** Profundizar en arquitecturas seguras de red empresarial e integrar modelos de Inteligencia Artificial para el análisis masivo de anomalías y optimización de detección.
* **Ingesta y Correlación en SIEM:** Despliegue avanzado de herramientas como Splunk, Microsoft Sentinel o Elastic Security para reglas de detección en tiempo real y automatización de respuesta (SOAR).
* **Threat Hunting y DFIR:** Técnicas avanzadas de búsqueda proactiva de amenazas en endpoints y metodologías forenses para el análisis de incidentes complejos.

---

## 📬 Contacto y Perfiles Profesionales
* **GitHub:** [github.com/DenizSaliev](https://github.com/DenizSaliev)
* **LinkedIn:** [Perfil de Deniz Saliev](https://www.linkedin.com/in/deniz-saliev-a106a72b7/)
