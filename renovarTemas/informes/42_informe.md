# Informe – Tema 42

**Título oficial:** Construcción de sistemas de información. Pruebas: tipologías. Formación. Conceptos, participantes, métodos y técnicas. Reutilización de componentes software.
**Fecha de elaboración:** 02/10/2026 · **Salida:** `salida/42. Construcción de sistemas de información.docx` (35 páginas)

**Fuentes principales:** Métrica v3 (procesos CSI e IAS, práctica de Pruebas y Participantes, en transcripción íntegra), SWEBOK V4.0, ISTQB CTFL v4.0.1, Pressman y Sommerville (obras de referencia), RD 311/2022 ENS (mp.sw.1, mp.sw.2, mp.per.4, comprobados en el BOE), Ley 40/2015 arts. 157-158, RD 4/2010 ENI arts. 16-17, Orden de 21/02/2005 de la Junta, MDN (Web Components) y el Confluence del SSPA: normativa front (Web Components, Paradigma Atomic Web Design, Normas de diseño estructural, Microfrontend, catálogo de componentes web 1.76.0), normativa de calidad y pruebas (Pruebas de carga v02r12, Automatización de pruebas funcionales, Requisitos y pruebas en proyectos ágiles, Procedimiento de documentación funcional y de pruebas v01r05, Guía Jira de pruebas, Verificación de la calidad del código v03r03, Evaluación de seguridad en aplicaciones web v01r01, Usabilidad v02r01), MCMI y procedimiento de manuales de ayudaDIGITAL.

## 1. Preguntas oficiales (CSV)

11 preguntas, 1 anulada. **Ninguna clave es errónea.** Todas se pueden responder estudiando solo el tema.

| ID | Clave CSV | Verificación | Apartado |
|---|---|---|---|
| **50** | A (preparación del entorno de generación y construcción) | Correcta. **Matiz:** según el detalle de tareas de Métrica, el Técnico de Sistemas también participa en CSI 2, pero solo en la tarea 2.2 (procedimientos de operación y seguridad). La opción B reproduce el título de la tarea CSI 2.1 «Generación del código de componentes», en la que solo participan programadores, así que sigue siendo incorrecta | 3.2 (recuadro), 10.1 |
| 72 | D (caja negra) | Correcta; definición literal de Pressman («también denominada prueba de comportamiento») | 6.3.2 |
| 196 | A (biblioteca de componentes reutilizables) | Correcta | 9.4 (recuadro), 9.5 |
| 197 | A (interacción y comunicación entre módulos) | Correcta; coincide con la definición de Métrica v3 | 6.2.2 |
| 198 | C (estrés) | Correcta. En Métrica v3 se llaman pruebas «de sobrecarga» | 6.2.3, 6.5 |
| 294 | A (Atomic Design) | Correcta: el SAS tiene normativa «Paradigma Atomic Web Design» y «Normas de diseño estructural» (v1.0.0, en vigor 01/06/2023, obligatoria desde 09/2023). «Mat Design» alude a Material Design (Google), «BS Design» probablemente a Bootstrap | 9.7 |
| 295 | B (reducción de costes y tiempos) | Correcta | 9.4 |
| 458 | A (mejora la productividad) | Correcta (Sommerville) | 9.4 |
| 6590 | A (reducción de tiempos y costes) | Correcta | 9.4 (recuadro) |
| 6592 | A (JMeter o equivalentes) | Correcta; además, JMeter es la herramienta lanzadora de la normativa de pruebas de carga del SAS | 6.5, 7.4 |

## 2. Preguntas anuladas

| ID | Pregunta | Motivo probable de la anulación | Apartado |
|---|---|---|---|
| **293** | Objetivo que **no** se consigue con Web Components (aislamiento, facilidad de uso, interoperabilidad, reutilización) | La norma «Web Components» de la STIC enumera **tres** objetivos: aislamiento, reutilización e interoperabilidad. La respuesta buscada era, previsiblemente, «facilidad de uso». Pero la facilidad de uso también puede defenderse como efecto de los Web Components (se usan como una etiqueta HTML y la propia norma habla de desarrollos «más ágiles»), por lo que había más de una lectura posible | 9.6.2 (recuadro) |

## 3. Correcciones y actualizaciones respecto al .md

- **Objetivos de Web Components:** el .md incluía «encapsulación» como cuarto objetivo y «ES Modules» como especificación. Según la norma del SAS los objetivos son tres (aislamiento, reutilización e interoperabilidad); el encapsulamiento es el mecanismo técnico (Shadow DOM). Las especificaciones de la norma y de MDN son Custom Elements, Shadow DOM y HTML Templates.
- **Atomic Design en el SAS:** el .md decía que la STIC lo recomienda frente a Material Design o BEM, sin fuente. Se sustituye por la normativa real (versiones, fechas, pautas P1-P6) y se aclaran los distractores de la pregunta 294.
- **Lista de actividades CSI:** correcta en el .md, pero sin participantes por tarea. Se añade la matriz completa a partir del detalle de tareas de Métrica v3. El .md decía que el Técnico de Sistemas no codifica, lo cual es correcto para los componentes, pero sí participa en los procedimientos de operación y seguridad (CSI 2.2). Se precisa.
- **Formación:** el .md la trataba de forma genérica (competencias del equipo). Se añade CSI 7 e IAS 2 con sus tareas, el matiz de que la impartición a usuarios finales queda fuera de Métrica v3, el Equipo de Formación, los métodos y técnicas formativas, la evaluación (Kirkpatrick, ENS mp.per.4) y el MCMI y ayudaDIGITAL del SAS.
- **Pruebas:** se añaden los 7 principios ISTQB, el proceso de pruebas, estáticas y dinámicas, la taxonomía de pruebas del sistema de Métrica (incluida la «sobrecarga»), las estrategias de integración (stubs y drivers), las pruebas de implantación y aceptación (alfa, beta, operacional), regresión frente a confirmación, las coberturas y el camino básico (V(G)), las técnicas de caja negra, los tipos de rendimiento (capacidad, sostenida, picos), la seguridad (SAST, DAST, IAST, SCA, OWASP Top 10 2021) y la automatización (pirámide, Page Object).
- **Contenido SAS nuevo:** normativa de la OCA (pruebas de carga con JMeter, Gherkin y Cucumber obligatorios, Jira Test Plan/Execution, SonarQube 9.9 LTS, OWASP ZAP y SPSD, usabilidad), catálogo de componentes web @sas/wc-stic en Storybook, microfrontends y ENS mp.sw.1 y mp.sw.2.
- **Reutilización:** se completa con niveles (Sommerville), definición de componente (Szyperski), CBSE (para y con reutilización) y marco normativo (Ley 40/2015 arts. 157-158, ENI, Orden de 2005, ENS mp.sw.1.r5).

## 4. Datos no verificados o con limitaciones

- La matriz resumen de participantes de Métrica v3 pierde las columnas en la transcripción consultada (el Técnico de Sistemas aparece con 5 marcas). El tema se basa en el **detalle de tareas**, que lo sitúa en 6 actividades (CSI 1, 2, 3, 4, 5 y 8). No se ha podido comprobar en el PDF oficial del PAe cuál de esas actividades omite la matriz resumen.
- La práctica de Pruebas de Métrica v3 se ha consultado en la transcripción de M. Cillero (la de pmgallardo solo tiene los títulos); la página de pruebas de implantación se leyó parcialmente.
- Pressman, Sommerville y Szyperski se citan como obras de referencia conocidas; no se han consultado en línea durante esta elaboración. También el modelo de Kirkpatrick, la pirámide de Cohn y la fecha del artículo de Brad Frost (2013).
- SWEBOK V4.0: computer.org indica publicación en 2024; existe una revisión 4.0a (2025) según una fuente secundaria.
- El cuerpo de la norma «Automatización de pruebas funcionales» muestra en el histórico la versión v01pr06 (18/11/2025) y en la cabecera v02r01; se cita la fecha de vigencia.
- Denominación del órgano: las normas del Confluence usan «STIC» y, las más recientes, «DGSIC». La cabecera de las páginas indica la DG de Salud Digital e Infraestructuras Tecnológicas (Decreto 189/2026).
- RD 1112/2018 (accesibilidad) y UNE-EN 301549 se citan sin comprobar de nuevo (se remiten al Tema 48).

## 5. Remisiones a otros temas

Tema 37 (MCMI) · Tema 39 (ciclo de vida, Métrica) · Tema 40 (casos de uso e historias de usuario) · Tema 41 (ágil, CI/CD, DevSecOps) · Tema 43 (Git, configuración) · Tema 44 (SQA, ISO/IEC/IEEE 29119, ISO/IEC 25010, pruebas tempranas) · Tema 45 (TDD, modularidad, generación de código) · Temas 47-48 (web, accesibilidad, usabilidad) · Temas 54 y 81 (software libre, licencias) · Temas 76-78 (seguridad, ENS) · Temas 91 y 95 (ayudaDIGITAL, e-learning).
