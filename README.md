# SAP CPI / Integration Suite — Portfolio de Patrones de Integración

Bienvenido a mi repositorio de casos prácticos de integración desarrollados en **SAP Integration Suite (Cloud Integration / CPI)**. 

Este espacio reúne una serie de proyectos estructurados bajo la metodología Lean (Estudio → Ejercicios → Construcción → Troubleshooting → Documentación → Entrevista), diseñados para resolver problemas reales de integración empresarial en entornos híbridos y multi-sistema.

---

## 🗺️ Mapa de Casos de Uso

| # | Caso / Escenario | Nivel / Complejidad | Tecnologías & Adaptadores Clave | Estado |
|---|---|:---:|---|:---:|
| **01** | [Order Processing Hub (REST → REST)](./case-01-rest-to-rest) | 🟢 Básica | HTTPS Sender, HTTP Receiver, Content Modifier, JSON | 🚀 Completado |
| **02** | JSON → XML Converter | 🟢 Básica | Converter, Graphical Message Mapping | ⏳ En Progreso |
| **03** | SOAP → REST Bridge | 🟢 Básica | SOAP Adapter, WSDL, Conversion | 📅 Pendiente |
| **04** | SFTP File Polling to SAP | 🟡 Intermedia | SFTP Adapter, File Handling | 📅 Pendiente |
| **05** | SAP S/4HANA OData Integration | 🟡 Intermedia | OData V2/V4 Adapter, Security Material | 📅 Pendiente |
| **06** | Groovy Scripting for Payload Processing | 🟡 Intermedia | Custom Groovy Scripts, Header/Body Manipulation | 📅 Pendiente |
| **07** | Enterprise Error Handling Framework | 🟠 Avanzada | Exception Subprocess, Custom Alerts, Logging | 📅 Pendiente |
| **08** | Multi-system Order Router | 🟠 Avanzada | Content-Based Router, Splitter, Aggregator | 📅 Pendiente |
| **09** | SAP PI/PO to CPI Migration Pattern | 🔴 Experta | Dual-stack Mapping Migration, Dual Adapters | 📅 Pendiente |
| **10** | Event-Driven Async Architecture | 🔴 Experta | SAP Event Mesh, JMS Queues, Decoupling | 📅 Pendiente |

---

## 🛠️ Stack Tecnológico & Herramientas

- **Integration Platform:** SAP Integration Suite / Cloud Integration (CPI) [SAP BTP]
- **Protocolos & Formatos:** REST, SOAP, HTTP/S, JSON, XML, OData, SFTP
- **Lógica & Scripting:** Groovy Scripting, Message Mapping, Content Modifier
- **Seguridad:** OAuth 2.0, Basic Auth, Client Certificates, Security Material
- **Herramientas de Pruebas:** Postman, SAP BTP Message Processing Log (MPL)

---

## 📂 Estructura de Cada Caso

Cada caso en este repositorio sigue una estructura estándar:
- `/src`: Paquete de integración exportado (`.zip` / `.xml`) listo para importar en SAP BTP.
- `/scripts`: Archivos independientes de lógica (`.groovy` / `.js`).
- `/docs`: Diagrama de arquitectura, capturas de monitoreo en SAP BTP y colecciones de prueba (Postman).
- `README.md`: Explicación del problema de negocio, arquitectura, manejo de errores y lecciones aprendidas.

---
**Contacto & Autor:** Jheycob Ocares  
*Consultor de Sistemas & Especialista en Integraciones*
