# Informe – Tema 41

**Título oficial:** Desarrollo ágil de software. Filosofía y principios del desarrollo ágil. El manifiesto ágil. Métodos de desarrollo ágil: SCRUM, KANBAN. LEAN. DevOps, DevSecOps
**Fecha de elaboración:** 02/10/2026 · **Salida:** `salida/41. Desarrollo ágil de software.docx` (30 páginas)

**Fuentes principales:** traducción oficial del Manifiesto Ágil y sus 12 principios (agilemanifesto.org), Scrum Guide 2020 (scrumguides.org; versión vigente) y Scrum Guide Expansion Pack 2025 (complemento), Kanban Guide de mayo de 2025 (ProKanban), métricas DORA (dora.dev), ISO/IEC/IEEE 32675:2022, NIST SP 800-218 SSDF, RD 311/2022 (ENS), Reglamento (UE) 2024/2847 (CRA), Portal de Desarrollo de Servicios Digitales de la Junta (áreas DevSecOps y Calidad) y Confluence del SSPA, espacio AGIL (Marco de Gestión Ágil en el SAS: responsabilidades, ceremonias, DoR, DoD, gestión de la demanda y métricas).

## 1. Preguntas oficiales (CSV)

59 preguntas, ninguna anulada y todas cubiertas. **Ninguna clave es claramente errónea**, pero **5 son discutibles o tienen matices** que el tema explica.

| ID | Clave CSV | Verificación | Apartado |
|---|---|---|---|
| **6722** | C (el PO «es el único perfil que habla constantemente con el cliente») | **Discutible.** No es una formulación de la Scrum Guide. Además, con la guía de 2017 la opción B («no forma parte del equipo de desarrollo») también es **cierta**: el PO era del Scrum Team, pero no del Development Team. Se acepta C como la formulación del manual de origen y en el tema se explican ambos matices | 6.3 |
| **6720** | D (Product Burndown = días pendientes para completar los requisitos del producto) | **Discutible por imprecisa.** Las unidades no son estándar: el product/release burndown suele medirse en puntos o en días ideales, y el sprint burndown en horas. La distinción que busca la pregunta (producto/requisitos frente a iteración/tareas) es correcta. Los burndown no forman parte de la Scrum Guide 2020 | 6.7.2 |
| **1049** | A (el Sprint Backlog «no debe ser modificado a no ser que comprometa el éxito del proyecto») | **Matiz.** Es la mejor opción, pero según la Scrum Guide 2020 los Developers actualizan el Sprint Backlog durante el Sprint y el alcance puede renegociarse con el PO. Lo que no se cambia es el **Objetivo del Sprint**. B invierte los papeles y es la incorrecta | 6.5 |
| **308** | A (manual de usuario como entregable del Sprint según la DoD) | **Correcta en el contexto SAS.** El estándar DoD de la STIC (v01r02, 30/07/2021) incluye el criterio 13 «Manual de usuario (según aplique, nuevo desarrollo)». Las historias de usuario y la detección de requisitos corresponden a la DoR. Sin conocer el marco del SAS, la pregunta resulta difícil | 6.6, 11.2.3 |
| **6588** | C («Canary Development») | Correcta en el fondo, pero el término es incorrecto: es *canary release/deployment*. Las demás opciones son patrones de diseño (Prototype, Observer) o de seguridad (Honeypot) | 9.5 |
| 438 | D (todas: muda, mura, muri) | Correcta. La definición de *mura* de la opción B («recursos empleados porque la calidad es impredecible») es poco ortodoxa (mura = variabilidad o irregularidad), pero no invalida la clave | 8.2 |
| 1199 / 6872 / 6901 | C (Kanban «como mínimo») | Correctas. El límite de WIP es un **máximo**. A (burndown de requisitos pendientes al inicio de cada Sprint) describe el release/product burndown y se acepta como correcta | 7.4, 6.7.2 |
| 1208 / 6756 / 6865 | B («decidir lo antes posible») | Correctas. El principio Lean es **decidir lo más tarde posible** (Poppendieck). **El .md original contenía este error** | 8.4 |
| 6837 / 6902 / 7012 | A (Sprint) | Correctas (definición literal de la Scrum Guide 2013) | 6.4.1 |
| 49 / 6921 | C (Waterfall) | Correctas | 5.2 |
| 22, 137, 138, 192, 194, 195, 228, 334, 335, 520, 521, 587, 761, 762, 832, 845, 966, 969, 972, 1059, 1296, 1297, 1399, 1400, 1401, 6331, 6332, 6392, 6393, 6394, 6395, 6498, 6721, 6792, 6797, 7011, 7040, 7041, 7106, 7108, 7109, 9564 | — | Correctas | 2-11 |

Grupos de preguntas repetidas: 1208/6756/6865 · 1199/6872/6901 · 6837/6902/7012 · 49/6921.

Auditoría de cobertura: cada pregunta se ha contrastado con el apartado indicado y todas se pueden responder estudiando solo el tema. Los distractores con nombres inventados (Scream, Gkambu, Katan…) y las técnicas no ágiles (Gantt, PERT, CPM, CORBA, Honeypot) se citan de forma expresa.

## 2. Preguntas anuladas

Ninguna.

## 3. Correcciones y actualizaciones respecto al .md

- **Valores de Scrum:** el .md incluía la «Transparencia» como valor. Es uno de los **3 pilares** del empirismo. Los valores son 5: compromiso, foco, apertura, respeto y coraje.
- **Principios Lean:** el .md decía «decidir lo antes posible». Corregido a **decidir lo más tarde posible**. Se añaden las dos formulaciones de Poppendieck (2003 y 2006), las 3M (muda, mura, muri) y la equivalencia de los desperdicios en software.
- **Métricas Kanban:** el .md definía mal el *lead time* (desde el inicio de la tarea) y el *cycle time* (por fase). Corregidos: lead time = desde la petición hasta la entrega; cycle time = desde el inicio hasta el fin. Se añaden WIP, throughput, work item age, la Ley de Little y el CFD.
- **Scrum actualizado a la Scrum Guide 2020:** *Developers* en lugar de Development Team, equipo autogestionado, compromisos de los artefactos (Objetivo del Producto, Objetivo del Sprint y DoD), duraciones máximas de los eventos, reglas del Sprint (cancelación solo por el PO) y nota sobre el Expansion Pack de 2025, que complementa la guía y no la sustituye.
- **5S:** el .md listaba los términos desordenados y mezclados. Se sustituyen por la secuencia correcta (seiri, seiton, seiso, seiketsu, shitsuke).
- **Tabla comparativa:** la tabla del .md estaba vacía (`|---|`). Rehecha en el apartado 12.
- **Contenido nuevo:** texto oficial de los valores y de los 12 principios, origen y firmantes del Manifiesto, comparación tradicional/ágil, XP (valores y prácticas), otros métodos (DSDM, FDD, Crystal, ASD, Scrumban, marcos de escalado), DoR/DoD, prácticas complementarias (historias, puntos, velocidad, burndown/burnup), Kanban Method y Kanban Guide 2025, CALMS y Tres Vías, CI frente a entrega continua y despliegue continuo, estrategias de despliegue (canary, blue/green…), métricas DORA (5, según dora.dev), ISO/IEC/IEEE 32675:2022, DevSecOps (SAST/DAST/IAST/SCA/RASP, SBOM, SSDF, OWASP SAMM/DSOMM), marco normativo (ENS arts. 20-21 y mp.sw.1-2, RGPD art. 25, CRA) y contexto de la Junta y del SAS.
- **Contexto SAS (nuevo):** Marco de Gestión Ágil de la STIC (PO funcional, **Proxy PO**, SM de la factoría, interesados OCA/OTI/Arquitectura), DoR de 9 criterios, DoD de 15 criterios, gestión de la demanda no planificable y métricas (cobertura ≥ 65 % en Sonar). Portal de Desarrollo de la Junta (plataforma CI/CD corporativa, área DevSecOps).

## 4. Datos no verificados o con limitaciones

- Del Confluence del SSPA se han leído las páginas de los estándares 2.1, 2.3, 2.4, 2.5 y 2.7, y el índice de normativa y de documentación de apoyo. El estándar 2.2 (ceremonias) muestra un diagrama no legible en texto: solo se ha podido comprobar en su histórico el cambio de la retrospectiva de 1 a 1,5 h, no la duración de los demás eventos ni la duración del Sprint del SAS. No se ha leído el contenido de las normativas OCA, Git y de entregas.
- El marco del SAS usa la denominación «STIC». La estructura vigente (Decreto 189/2026) atribuye las competencias TIC a la DG de Salud Digital e Infraestructuras Tecnológicas. No se ha comprobado si el marco ágil ha cambiado de denominación.
- Las herramientas concretas del Portal de la Junta (salvo SonarQube y la «plataforma CI/CD corporativa») no figuran en las páginas consultadas, por lo que no se citan.
- Datos de autoría y fechas históricas (Takeuchi-Nonaka 1986, OOPSLA 1995, XP 1999, Poppendieck 2003/2006, Anderson 2004-2010, DevOpsDays 2009, Scrumban 2008) proceden de obras de referencia conocidas. No se han contrastado una a una en fuente primaria durante esta elaboración.

## 5. Remisiones a otros temas

Tema 31 y 36 (PDCA, kaizen) · Tema 37 (gestión de proyectos predictiva/ágil/híbrida, MCMI) · Tema 38 (Jira, Confluence) · Tema 39 (modelos de ciclo de vida, prototipos, MVP, ISO 12207:2026) · Tema 40 (historias de usuario) · Tema 42 (pruebas) · Tema 43 (Git, Gitflow, gestión de la configuración) · Tema 44 (SQA, métricas de calidad) · Tema 45 (TDD) · Temas 76-78 (seguridad, ENS, MAGERIT).
