# Informe – Tema 37

**Título oficial:** Gestión de proyectos TIC. Principales estándares, guías de buenas prácticas y metodologías: Gestión de alcance, coste y tiempo de los proyectos. Gestión de la calidad, gestión de los recursos, gestión de las comunicaciones, gestión de riesgos. Gestión de adquisiciones del proyecto, gestión de interesados (stakeholders). Modelo Corporativo Marco de Implantaciones (MCMI) del Servicio Andaluz de Salud.
**Fecha de elaboración:** 02/10/2026 · **Salida:** `salida/37. Gestión de proyectos TIC.docx` (42 páginas)

## 1. Preguntas oficiales (CSV)

31 preguntas, ninguna anulada. Todas cubiertas. **Ninguna clave errónea**; **3 discutibles o con matiz**.

| ID | Clave CSV | Verificación | Apartado |
|---|---|---|---|
| **1289** | C PRINCE2 | **Discutible.** PMBOK también sería defendible como marco. Se acepta la clave (PRINCE2 es método con roles, fases y productos; encaja con gobierno y normativa) y se explica el matiz | 3.9 |
| **6327 / 7133** | A (7 fases) | **Matiz.** El MCMI oficial tiene **8 fases** (falta «Paso a N3»). La clave habla de fases «principales» y es la única opción coherente | 13.4 |
| **902** | A PDM | **Matiz.** PDM en PMBOK es *Precedence Diagramming Method* (sí es técnica de planificación). La pregunta lo desarrolla como «Proyect Data Management», que no lo es; la clave es correcta por el desarrollo dado | 5.2 |
| 6611 | B | Correcta: el MCMI admite más de un R (recomienda subdividir); solo un A | 13.6 |
| 6538 | B | Correcta: INTE05 es Plan de pruebas **funcionales**, no «técnicas» (confirmado en Confluence SAS) | 13.7 |
| 6528, 6537, 6613, 6882 | A / B / C / B | Correctas (contrastadas con la página oficial del MCMI) | 13.4-13.5 |
| 6618 | C | Correcta (Gantt clásico; herramientas actuales sí pueden mostrar el camino crítico) | 5.4 |
| Resto (23, 139, 162, 172, 299, 519, 862, 1039, 1074, 1207, 1287, 1290, 1291, 6391, 6532, 6534, 6788, 7104, 9553, 9592) | — | Correctas. 6327/7133 son prácticamente repetidas; 299/862/23/1207 preguntan el camino crítico | 2-12 |

## 2. Correcciones y actualizaciones respecto al .md

- **Numeración:** el .md se titulaba «TEMA 31» (numeración antigua); corregido a Tema 37 según el programa oficial.
- **PMBOK actualizado:** el .md solo citaba «diez áreas». Añadidas 6.ª ed. (5 grupos, 10 áreas, 49 procesos), 7.ª (12 principios, 8 dominios) y **8.ª ed. (nov. 2025: 6 principios, 7 dominios, 5 áreas de enfoque, 40 procesos)**.
- **PRINCE2 7 (2023):** 5 elementos integrados (con «personas»), 7 principios, prácticas (antes temas), 7 procesos, sostenibilidad como 7.º objetivo; propiedad de PeopleCert.
- **ISO 21500:** añadida la familia (21500:2012 → 21500:2021 + 21502:2020; UNE-ISO 2022; 21508 EVM, 21511 EDT). Añadidos PM², IPMA ICB4 e interfaz GP de Métrica v3.
- **Ciclo de vida vs grupos de procesos:** el .md presentaba inicio-planificación-ejecución-control-cierre como «ciclo de vida»; aclarado que son grupos de procesos.
- **Contratación:** el .md hablaba de «licitación pública, concurso o adjudicación directa» (terminología anterior a la LCSP). Corregido con los procedimientos vigentes de la Ley 9/2017.
- **Riesgos:** añadida la estrategia «evitar» (faltaba) y las de oportunidades; análisis cuantitativo; riesgo vs incidencia.
- **ITIL:** se elimina como «estándar de gestión de proyectos»; se explica que es gestión de servicios (Tema 36).
- **MCMI:** fase 1 corregida a «Análisis **Preliminar** de Situación» (el .md decía «Previo» en una tabla). Definición literal y 8 fases contrastadas con la página oficial (Confluence SSPA, espacio DGTIC). Añadidas tablas de actividades por fase, subfases del arranque, catálogo completo de entregables y entradas externas.
- **Denominación del órgano TIC:** el .md citaba «DGSIC»; se usa la denominación vigente (DG de Salud Digital e Infraestructuras Tecnológicas, Decreto 189/2026) y se explica que el MCMI usa «STIC».
- **Añadido:** EDT/WBS, PDM y tipos de dependencia, estimación PERT (fórmulas y ejemplo), cálculo de holguras con ejemplo, red de ejemplo con dos caminos críticos, compresión del cronograma, cadena crítica, fórmulas completas de valor ganado con ejemplo, reservas, calidad (QA/QC, herramientas), Tuckman, canales de comunicación, matriz poder/interés corregida (Mendelow), modelo de prominencia, AHP detallado, tabla final de claves.

## 3. Datos no verificados o tratados con cautela

- **Bloque «Factoría de Implantaciones / MCMI 2.0»** del .md (fases Recepcionar-Modelar-Implantar, Transformar y Capacitar, pack de nivelación, cuadro de control, IA): **no localizado en fuentes oficiales públicas**. Se mantiene resumido y marcado como no contrastado (13.10). Sí verificado: expediente 2114/2023 (acuerdo del Consejo de Gobierno de 09/07/2024; 2 lotes; propuesta de adjudicación de la mesa de 27/12/2024 a la UTE Indra (Minsait)-Ayesa; cinco objetivos del contrato; valoración de mejoras al MCMI). No se ha comprobado la formalización del contrato.
- **Criterios de «resolución de conflictos» del .md** (quién media, quién lidera ante ENS/RGPD, A del N3 en migración, etc.): no figuran en el texto oficial del MCMI; parecen proceder de preguntas de práctica. Se conservan solo los razonables, como «criterios orientativos» (13.8). Se retiran los más arriesgados (p. ej., que FUNC lidere las correcciones del RGPD o que el N3 sustituido sea A en la migración).
- **PMBOK 8:** detalles tomados de fuentes secundarias (no de la guía). El 6.º principio aparece como «build an empowered culture» o «… teams» según la fuente.
- **PM² 3.1:** año (2023) deducido de la referencia del documento publicado.
- **«MCI»** (presentación del MCI, GEST03): el MCMI dice que nace del «MCI específico» de Diraya AH; no se ha encontrado el desarrollo de la sigla.
- Índice paginado con LibreOffice; en Word puede variar una página.

## 4. Remisiones

Tema 28 (gestión del cambio) · Tema 29 (planificación) · Tema 30 (porfolio) · Tema 31 (calidad, PDCA) · Tema 32 (contratación TIC, LCSP, ADA) · Tema 36 (ITIL, ISO 20000, COBIT) · Tema 38 (herramientas: MS Project, JIRA…) · Tema 39 (Métrica v3) · Tema 41 (Scrum, Kanban, Lean) · Tema 44 (CMMI, calidad del software) · Temas 76-77 (ENS, MAGERIT).
