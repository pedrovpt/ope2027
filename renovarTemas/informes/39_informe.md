# Informe – Tema 39

**Título oficial:** El ciclo de vida de los sistemas de información. Modelos de ciclo de vida. La elaboración de prototipos en el desarrollo de sistemas de información.
**Fecha de elaboración:** 02/10/2026 · **Salida:** `salida/39. El ciclo de vida de los sistemas de información.docx` (31 páginas)

**Fuentes principales:** texto de Métrica v3 (procesos, interfaces, técnicas, participantes; transcripción íntegra en pmgallardo.github.io/metrica-v3 y PDF oficial de EVS © MAP), ISO/IEC/IEEE 12207:2026 (iso.org, ANSI), ISO/IEC/IEEE 14764:2022 (muestra pública), Orden de 16/10/2024 (BOJA 205) y Portal de Desarrollo de Servicios Digitales, Confluence SAS (Marco de gestión ágil, Gobierno tecnológico–Calidad).

## 1. Preguntas oficiales (CSV)

42 preguntas, 1 anulada. Todas cubiertas. **Ninguna clave errónea**; **3 con matiz** que el tema explica.

| ID | Clave CSV | Verificación | Apartado |
|---|---|---|---|
| **1402** | C (perfectivo = mejoras/ampliaciones pedidas por usuarios) | **Discutible.** Correcta según la clasificación clásica (Swanson) e ISO/IEC/IEEE 14764 (perfectivo = «enhancements for users»). Pero en **Métrica v3** eso es mantenimiento **evolutivo**, y el perfectivo es la mejora de la calidad interna (código, rendimiento); además Métrica deja adaptativo y perfectivo fuera de MSI. El enunciado no cita Métrica, así que se acepta la clave y se explica la trampa | 2.5.1 |
| **1398** | C (ingeniería del software, análisis, diseño, codificación, pruebas, utilización, mantenimiento, sustitución) | Correcta como formulación de manual; no hay lista única de fases de la cascada (Royce 1970 y Pressman difieren). Se presentan las variantes | 4.4.2 |
| **1012** | C (EVS 2 y EVS 3 en paralelo) | Correcta. El texto de Métrica remite a un **diagrama** de actividades en paralelo; no se ha visto el diagrama en fuente oficial accesible, pero es la interpretación unánime | 3.3.5 |
| 6584 | ANULADA | Ver apartado 2 | 3.3.5 |
| 6795 | A (Perfil Jefe de Proyecto) | Correcta: el Responsable de Calidad está en el perfil Jefe de Proyecto (el Grupo de Aseguramiento de la Calidad, en Analista) | 3.3.12 |
| 145 | D | Correcta: entorno tecnológico se **identifica** en ASI 1.2 y se **especifica** en DSI 1.6 | 3.3.6 |
| 337 | C (regresión) | Correcta: las pruebas de regresión son de MSI 3.3/4.2 | 3.3.8 |
| 51 | C | Correcta; el enunciado llama «fase» a la actividad CSI 2 | 3.3.8 |
| 831 | D | Correcta: «Diseño de subsistemas de soporte» es DSI 2.1 | 3.3.7 |
| 1013 | D | Correcta: DSI 4 Diseño de clases solo en OO | 3.3.7 |
| 1223 | D | Correcta. Distractor C: en ITIL v2 la Gestión de la configuración era un proceso, no una función | 3.3.3 |
| 46 | A | Correcta; «estabilización»/«sincronización» proceden del modelo *synchronize-and-stabilize* (Microsoft) | 4.4.3, 4.13 |
| 6602 | A | Correcta: radial = coste acumulado; angular = progreso (Boehm) | 4.9.3 |
| 1403 | B | Correcta (texto de Métrica: «desarrollos máximos»). Distractor A describe métodos Jackson/Warnier | 3.3.1 |
| 45, 47, 53, 146, 333, 586, 588, 651, 901, 920, 961, 1011, 1014, 1015, 1075, 1099, 1122, 1213, 1214, 1286, 6330, 6441, 6517, 6765, 6857, 7033, 7034, 7121 | — | Correctas. 6330/7121 y 6857/7034 son repetidas | 2-5 |

Las 20 preguntas del .md (sin ORIGEN oficial) también están cubiertas; sus claves son coherentes con el tema.

## 2. Pregunta anulada

- **6584** (utilidad del EVS en un caso del SAS). B (primera estimación de alcance, coste y plazo que se refina) y C (reducir la incertidumbre y evaluar la capacidad real de la organización) son **ambas** ciertas; A (garantizar la alineación con PMBOK) no lo es, de modo que D («todas») tampoco. Al haber dos opciones válidas y ninguna «B y C», la anulación es lógica. El tema recoge las dos utilidades y aclara que el EVS no tiene por objeto alinearse con el PMBOK (3.3.5).

## 3. Correcciones y actualizaciones respecto al .md

- **ISO/IEC/IEEE 12207:** actualizada a la **edición de 2026** (abril de 2026; sustituye a la de 2017). Añadidas la estructura clásica de 1995 (5 principales, 8 de soporte, 4 organizativos) y la de 2017 (30 procesos en 4 grupos) y la idea clave: define procesos, no prescribe modelo.
- **Tipos de mantenimiento:** el .md seguía la clasificación de Métrica sin advertirlo; se añade la tabla Métrica vs ISO 14764:2022/Swanson (incluidos preventivo, aditivo y de emergencia) y que Métrica solo contempla correctivo y evolutivo.
- **Métrica v3:** el .md listaba sus procesos de forma incompleta (sin distinguir PSI/Desarrollo/MSI). Añadidos actividades y tareas de PSI, EVS, ASI, DSI, CSI, IAS y MSI, interfaces, participantes, técnicas y prácticas (prototipado como práctica), y recuadros de trampas.
- **Contexto Junta/SAS (nuevo):** MADEJA sustituido por el **Portal de Desarrollo de Servicios Digitales** (Orden 16/10/2024, BOJA 205; ADA); su metodología *Design Thinking* incluye la fase **Prototipar** (recomienda **Penpot**). Marco de gestión ágil del SAS, Oficina de Calidad y MCMI (remisiones).
- **Modelos:** añadidos modelo por etapas (Benington 1956), modelo en V, evolutivo, cuadrantes y dimensiones de la espiral, WinWin, RAD, sincronizar y estabilizar, Proceso Unificado; aclarado que la cascada pura no itera aunque Royce proponía realimentación; tabla de fases según autores.
- **Prototipos:** clasificación por destino (desechable/rápido, evolutivo, incremental), alcance (horizontal/vertical) y fidelidad (baja/media/alta); PoC, MVP, piloto; proceso (Sommerville/Pressman); riesgos.
- **Herramientas:** Adobe XD indicado como en modo mantenimiento (Adobe, 2024).
- Eliminado el bloque final desordenado del .md (fragmentos repetidos y marcas de resaltado).

## 4. Datos no verificados o tratados con cautela

- Diagrama de paralelismo EVS 2 ∥ EVS 3: no visto en fuente oficial (el texto lo remite al gráfico).
- Composición de perfiles de participantes: tomada de la transcripción íntegra de Métrica (no del PDF oficial del PAe, inaccesible).
- Normas de referencia de Métrica v3 (ISO 12207, ISO/IEC TR 15504, UNE-EN ISO 9001:2000): se citan «entre otras».
- Estructura interna detallada de la 12207:2026: solo se ha visto el resumen público; se afirma que mantiene el marco armonizado con 15288, sin detallar cambios en el número de procesos.
- Atribuciones históricas (Royce, Benington, Boehm, Cusumano y Selby, James Martin, Chikofsky y Cross) basadas en bibliografía clásica.
- Imágenes: el Word original no contiene imágenes (`word/media` inexistente) y el .md no tenía referencias a imágenes.
- Índice paginado con LibreOffice; en Word puede variar una página.

## 5. Remisiones

Tema 36 (CMMI, ISO 15504/330xx, ITIL) · Tema 37 (gestión de proyectos, PMBOK, MCMI) · Tema 38 (Jira/Confluence) · Tema 40 (análisis funcional, UML, casos de uso) · Tema 41 (ágil, Scrum, DevOps) · Tema 42 (pruebas, formación, reutilización de componentes) · Tema 43 (gestión de la configuración, Git).
