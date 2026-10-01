# Informe – Tema 36

**Título oficial:** Buenas prácticas y certificaciones en la gestión de servicios de tecnologías de la información. El enfoque hacia procesos integrados. ITIL, y su ciclo de vida del servicio: estrategia del servicio, diseño del servicio, transición del servicio, operación del servicio. ISO 20000. La mejora continua basada en el modelo PDCA. COBIT: objetivos de control y métricas.
**Fecha de elaboración:** 01/10/2026 · **Salida:** `salida/36. Buenas prácticas en la gestión de servicios TI. ITIL, ISO 20000, PDCA y COBIT.docx` (39 páginas)

## 1. Preguntas oficiales (CSV)

56 preguntas, ninguna anulada. Todas cubiertas (además de las 9 del .md y las 5 de las imágenes del Word). **1 clave probablemente errónea** y **1 discutible**.

| ID | Clave CSV | Verificación | Apartado |
|---|---|---|---|
| **7021** | A («documento que define todos los aspectos de un servicio y sus requisitos en cada etapa de su ciclo de vida») | **Probablemente errónea.** Esa es, literalmente, la definición del glosario ITIL v3 del **paquete de diseño del servicio (SDP)**. El catálogo de servicios es «base de datos o documento estructurado con información sobre todos los servicios de TI en producción», que encaja con la opción **C**. Se enseñan ambas definiciones y se avisa de la clave oficial | 4.4.1 (recuadro) |
| **6325** | D Mejora continua (medidas correctivas y preventivas basadas en incidentes) | **Discutible.** La gestión de problemas (fase de Operación) también actúa reactiva y proactivamente sobre incidencias. Se explica la lógica de la clave (la «fase» de mejora) y el matiz | 4.8 (recuadro) |
| 903 | C (fases desordenadas: Operación antes que Transición) | Correcta por eliminación: única opción con las cinco fases. Se advierte del orden | 4.3 |
| 973 | B Planificación | Correcta; matiz: «Plan» sí es actividad de la cadena de valor, no componente del SVS | 4.10.1 |
| 6800 | B componente de un proceso de negocio | Correcta según el glosario ITIL v2; se explica la evolución en v3 e ITIL 4 | 4.2 |
| 1196 | C | Correcta. A confunde «Service Delivery» con «Software Delivery»; D: el cambio era de Service Support | 4.1 |
| 6610 | A 3 años | Correcta (ciclo de certificación ISO/IEC 17021-1, seguimiento anual) | 2.4 |
| 140 | D Ninguna | Correcta (ISACA: lo que COBIT no es) | 7.1 |
| 163, 730, 1288 | B / C / B | Correctas (trampas sobre la redacción de los principios de COBIT 5) | 7.4 |
| Resto (24, 25, 141, 142, 164, 165, 336, 447, 460, 461, 517, 518, 584, 589, 661, 731, 815, 919, 923, 1044, 1065, 1195, 1197, 1198, 1216, 1244, 6324, 6326, 6396, 6397, 6527, 6536, 6617, 6752, 6768, 6784, 6863, 7013, 7020, 7022, 7026, 7130, 7131, 9554, 9555) | — | Correctas. 6752/6863/7026 y 6324/7130 y 460/7131 son repetidas | 2-8 |

Nota sobre 25: la redacción («incluyendo el diseño, la transición, la entrega y la mejora») procede de la edición 2011 de ISO/IEC 20000-1; la de 2018 habla de «planificación, diseño, transición, entrega y mejora». La clave sigue siendo válida.

## 2. Correcciones y actualizaciones respecto al .md

- **Novedades 2026:** ITIL (Version 5) presentada por PeopleCert a comienzos de 2026 (ciclo de vida de producto y servicio de 8 actividades, IA); ISO/IEC 20000-1:2018 confirmada en 2023 y con Amd 1:2024 (acción climática); COBIT 2019 vigente con actualización anunciada por ISACA para finales de 2026; CMMI V3.0 (2023); ISO 9001:2026.
- **Problema / error conocido:** el .md decía «causa raíz desconocida de incidencias repetitivas»; corregido a la definición ITIL (causa o causa potencial de una o más incidencias; no exige repetición).
- **Escalado funcional/jerárquico:** redefinidos según ITIL (el jerárquico no es «no sé de quién es», sino implicar a la jerarquía por gravedad/SLA/decisiones).
- **Métrica v3:** el .md hablaba de «tres procesos: planificación; análisis, diseño y construcción; mantenimiento»; corregido a PSI, DSI (EVS, ASI, DSI, CSI, IAS) y MSI más cuatro interfaces.
- **ISO 20000 «basada en ITIL»:** matizado (nació de BS 15000 alineada con ITIL v2, pero es independiente de marcos). Partes de la serie actualizadas (2, 3, 5, 6, 7, 10, 11, 15-17); el .md decía «parte 3 y siguientes: auditoría y pymes».
- **Certificaciones de personas:** ordenadas por esquema (ITIL v3 vs ITIL 4 vs Version 5; ISACA para COBIT; CMMI evalúa, no certifica).
- **Añadido:** ITIL v2 (módulos), tipos de proveedor, utilidad/garantía, 4P y SDP, SLA/OLA/UC/SLR, disponibilidad (MTBF/MTRS), DIKW/SKMS, ECAB, funciones de operación, enfoque CSI y siete pasos, roles (process manager/practitioner), cadena de valor ITIL 4, modelo de mejora ITIL 4, estructura de cláusulas de ISO/IEC 20000-1:2018 (cláusula 8 completa), plan de gestión del servicio, COBIT 4.1 (criterios de información, recursos, KGI/KPI, madurez), COBIT 5 (37 procesos por dominio), COBIT 2019 (factores de diseño, componentes, cascada de metas 13/13, CPM), ciclo de implantación de COBIT, Kaizen, DMAIC, art. 93 LCSP, tabla final de claves.
- **Eliminado o reducido:** títulos vacíos, beneficios repetidos con emojis, conclusiones redundantes, listas de «certificaciones ISO 20000 para profesionales» (no son de la norma).
- **Imágenes:** 18 en el Word original. 1 decorativa (línea horizontal) descartada. Revisadas 17: se insertan 2 (ciclo de vida, cartera de servicios); 7 se convierten en tablas o texto (mapa de marcos, objetivo de ITIL, ITIL-Lean, ITIL-DevOps, función vs proceso, RACI, catálogo negocio/técnico); 8 eran preguntas o ejercicios (características del proceso, términos de estrategia, PBA, garantía, gestión de la capacidad, términos de operación, «qué hemos aprendido») y su contenido se ha integrado en los apartados correspondientes.

## 3. Datos no verificados o retirados

- **«Monitoring 360»** como herramienta de monitorización del SAS: no localizado en fuentes públicas; retirado del texto.
- **Teléfonos de ayudaDIGITAL** (317000/317100 en el .md): la nota oficial de 2023 da 31700/955017000; al ser un dato cambiante y propio del Tema 91, se ha omitido.
- **«Hora básica de servicio» (HBS)** como unidad de estimación en el SAS: no verificado; se menciona solo como ejemplo genérico.
- **Alineamiento de ayudaDIGITAL con ITIL/ISO 20000** citado en escapa.es (fuente secundaria, alude a pliegos del SAS): no se ha consultado el pliego; el texto se limita a lo publicado por la Junta y el SAS.
- **ITIL (Version 5):** detalles (8 actividades, IA, 34 prácticas sin cambios) contrastados en la web de ITIL/PeopleCert y en fuentes de formación; la fecha exacta de lanzamiento se cita como «comienzos de 2026».
- Relación de partes 5, 7, 11, 15-17 de ISO/IEC 20000 tomada de fuente secundaria (Wikipedia).
- Índice paginado con LibreOffice; en Word puede variar una página.

## 4. Remisiones

Tema 10 y Tema 91 (ayudaDIGITAL) · Tema 31 (calidad, EFQM, ISO 9001, gestión por procesos) · Tema 32 (contratación TIC) · Tema 37 (PMBOK, PRINCE2) · Tema 38 (herramientas ITSM) · Tema 39 (Métrica v3) · Tema 41 (Agile, Lean, DevOps) · Tema 44 (CMMI, calidad del software) · Temas 76-77 (seguridad, continuidad, ENS) · Tema 80 (auditoría, COBIT).
