# Informe – Tema 38

**Título oficial:** Herramientas de gestión de TIC: gestión de proyectos, de la operación, del conocimiento y gestión interna para la función de tecnologías de la información y comunicaciones en el Servicio Andaluz de Salud.
**Fecha de elaboración:** 02/10/2026 · **Salida:** `salida/38. Herramientas de Gestión TIC.docx` (28 páginas)

**Fuente principal:** documentación pública del SAS en Confluence (espacio «Servicios de Gestión interna de la DGTIC»: página «Herramientas de gestión TIC», procesos «Gestión de Proyectos» y «Gestión del Conocimiento», manuales JIRA, «Proceso integración Altiris - CMS», «Reglas de negocio CMS», módulos de MiGestorServicios) y catálogo «Gestión TIC» del portal ayudaDIGITAL.

## 1. Preguntas oficiales (CSV)

22 preguntas, ninguna anulada. Todas cubiertas. **Ninguna clave errónea**; **2 con matiz no verificable** en fuentes públicas.

| ID | Clave CSV | Verificación | Apartado |
|---|---|---|---|
| **6898** | C (máx. 30 tareas programadas) | **No verificable**: la guía de tareas programadas de Confluence no es pública (404). Se acepta la clave. A y B son incorrectas por el estado inicial: tarea general/con validación nace en ABIERTA; de soporte provincial en PDTE. CALENDARIZAR (confirmado en el manual oficial) | 3.7 |
| **6899** | D | Correcta. La página «lecciones aprendidas» en «Datos básicos/Información relevante» y el espacio transversal «Lecciones aprendidas» constan en Confluence; el registro «desde JIRA» no se ha visto en documentación pública, pero es coherente con la integración Jira→Confluence | 3.11 |
| 525 | D | Correcta. Restricciones de clave confirmadas (máx. 9, no empieza por número, mayúsculas, sin guiones). Lo de las «dos iniciales de la provincia» solo consta en la pregunta | 3.4 |
| 132 | C AGESCON | Correcta. A describe **Estructura** (no MACO); B: idenTIC es gestor de identidad, no SSO (fichas oficiales) | 6.3 |
| 667 | C UNIFICA | Correcta. UNIFICA existe (ws001…/unifica/web/gobernanza, acceso restringido). La misma fórmula se usa hoy para los espacios públicos de Confluence | 5.3 |
| 1405 | A COSMOS | Correcta (definición literal en ayudaDIGITAL) | 4.10 |
| 388 | B Centreon | Correcta según material base y pregunta; no se ha encontrado ficha pública de Centreon en el SAS | 4.10 |
| 6643 | B Scrum y Kanban | Correcta; «Business y Software» son tipos de proyecto de Jira (trampa) | 3.9 |
| 6881 | A | Correcta (definición literal en Confluence) | 6.1 |
| 6900 | A tipos de tarea | Correcta (proceso Gestión de Proyectos) | 3.5 |
| 526 | D | Correcta | 3.7 |
| 251, 522, 523, 524, 6328, 7129, 7179, 6751, 6862, 9565, 9593 | — | Correctas. 6328/7129/7179 y 6751/6862 son repetidas | 3-5 |

## 2. Correcciones y actualizaciones respecto al .md

- **Categorías de proyecto en Jira:** el .md inventaba cuatro tipos genéricos («gestión de aplicaciones», «soporte técnico», «gestión de procesos», «innovación»). Sustituidos por las categorías oficiales: Gestión de proyectos, Aplicación y Plataforma (RFP, SVE, PL, OT…), Programa, Gestión de área (ágil), Soporte provincial (PST), Consultoría (SVT).
- **Estados de tareas Jira:** el .md daba un ciclo genérico (en revisión, resuelta, escalada…). Sustituido por los flujos oficiales (ABIERTA, EN RESOLUCIÓN, PARALIZADA, PDTE. VALIDAR, PDTE. CALENDARIZAR, CALENDARIZADA, PDTE. REVISIÓN TÉCNICA, NO ACEPTADA…). Añadidos tipos de tarea (general, con validación, MCMI con sus fases/áreas, historia de usuario, soporte provincial con tarificación basal/valor añadido, seguridad, expedientes, épicas, integración), enlaces «Se desarrolla en/Se gestiona en», estados del proyecto (En estudio, En cartera, En ejecución, Paralizado, Cerrado), plantillas simple/compleja y archivo de proyectos.
- **Roles de Jira del .md** (administrador, gestor de tareas, colaborador, observador; 2FA, LDAP): no figuran en la documentación del SAS; se sustituyen por los grupos reales (gestión conjunta Jira/Confluence, licencia por herramienta, proveedores con usuarios genéricos).
- **Integración Altiris–CMS:** el .md decía que los equipos no registrados se insertan «con estado Desconocido»; según el proceso oficial es el **expediente de compra** el que se marca «desconocido». Añadida la carga administrativa en PRERREGISTRO y búsqueda por S/N, MAC e ID Altiris.
- **Criticidad de instancias de BBDD:** el .md decía que se hereda de la plataforma; la regla oficial es la **criticidad más alta de sus tripletas** (valor calculado).
- **Estados de activos CMS:** el .md los dejaba en blanco; añadida la tabla oficial (10 estados).
- **Gestión del conocimiento:** añadido el proceso oficial (cuatro contenedores: portal ayudaDIGITAL, Confluence, suite CA-SDM/KDB/CMDB, MTI-DWH; KI; «el SAS es dueño del conocimiento»). Web Técnica funciona sobre CA Service Desk Manager.
- **Confluence:** categorías de espacios oficiales (DG-nivel1/2, Aplicación, Aplicación no Jira, Programa, Plataformas, Gestión, Factoría, Ayuda…) en lugar de la lista del .md; grupos y permisos (herencia solo de visualización); acceso publicado en Internet.
- **Panel de centralita (MiGestorServicios):** el .md asignaba colores a estados de agente; oficialmente el color del nombre indica la **función** del agente y el código verde-amarillo-rojo se aplica al tiempo en cola frente al ANS.
- **Altiris:** añadido que hoy es producto de **Broadcom** (ITMS 8.8, mayo 2025). Retirado como requisito actual «IE9 + Silverlight» (productos retirados en 2021-2022). Fin de soporte de Windows 10 (14/10/2025).
- **MicroStrategy** renombrada **Strategy** (feb. 2025). «SSHH» = Servicios Horizontales (trampa con RR. HH. en la pregunta 6881).
- **Atlassian Data Center:** fin de vida anunciado para el 28/03/2029.
- **ayudaDIGITAL:** datos contrastados (WhatsApp desde nov. 2022; 784.052 solicitudes en el primer año; IA generativa AYDI desde 2024). El detalle del servicio se remite al Tema 91.
- **Denominación del órgano TIC:** DG de Salud Digital e Infraestructuras Tecnológicas (Decreto 189/2026); explicadas las siglas DGSIC/DGTIC/STIC/STI/CGES.
- **Omitidos** por no ser materia de examen y por prudencia: IP internas, nombres de servidores de Altiris, puertos, URL internas de Servicios CGES y ejemplo de clave pública.

## 3. Datos no verificados o tratados con cautela

- Límite de **30 tareas programadas** (solo en la pregunta 6898) y clave de proyectos provinciales con **dos iniciales de provincia** (solo en la pregunta 525).
- **Centreon** como herramienta de monitorización de plataformas: sin ficha pública localizada; se apoya en la pregunta 388 y el .md.
- **UNIFICA:** existe el portal, pero no se ha podido leer (403); la definición se toma de la pregunta 667.
- **Servicios CGES** (tokens JWT de 10/30 min y refresco de 48 h): el detalle está en espacios no públicos; en el tema solo se describe el mecanismo, sin duraciones.
- **Telémaco** (cifrado ECDHE del .md), **NetControl** (RADIUS/NPS, VLAN), **LeTSAS** (versión 6/Fedora 33, anillos D/D+7/D+14, botón de pánico, bloqueo/apagado) y **cuadros de mando de MTI**: proceden del .md (material interno); se mantienen atribuidos al material base. Puede haber versiones posteriores de LeTSAS.
- No consta qué hará el SAS ante el fin de Atlassian Data Center.
- Imágenes: el Word original no contiene imágenes (`word/media` vacío); el .md solo traía texto OCR de una matriz RACI y de un modelo E-R ilegible.
- Índice paginado con LibreOffice; en Word puede variar una página.

## 4. Remisiones

Tema 10 (TIC en el SAS, ayudaDIGITAL) · Tema 34 (órganos y política informática) · Tema 36 (ITIL: incidencia, problema, CMDB, ANS) · Tema 37 (gestión de proyectos y MCMI) · Tema 41 (Scrum, Kanban) · Temas 52-53 (sistemas operativos, Linux) · Tema 91 (CSU ayudaDIGITAL: catálogo, incidencias, problemas, configuración) · Tema 92 (puesto de trabajo, puestos ligeros) · Tema 94 (trabajo colaborativo, gestión documental) · Temas 76-77 (seguridad, ENS).
