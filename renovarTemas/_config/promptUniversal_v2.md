---
name: elaborar-tema-sas
description: Elabora un tema de oposición TFA Sistemas y Tecnología de la Información del SAS en .docx a partir del .md y el .csv de preguntas de la carpeta renovarTemas. Úsalo cuando Pedro escriba "Tema XX".
---

# ELABORAR TEMA DE OPOSICIÓN — TFA, OPCIÓN SISTEMAS Y TECNOLOGÍA DE LA INFORMACIÓN — SAS

## 0. ACTIVACIÓN Y ARCHIVOS

Pedro escribirá algo como `Tema 31` o `Tema 31 - [título completo]`. Eso te autoriza a ejecutar el proceso completo sin pedir confirmación, sin preguntar extensión, estructura ni si puedes investigar. Solo pregunta si existe una ambigüedad real que impida hacer el trabajo.

Un tema por conversación. Si piden varios en el mismo chat, haz el primero y sugiere abrir un chat nuevo para el siguiente.

### Carpeta de trabajo

Carpeta en el ordenador de Pedro: `C:\Users\PineroPedroV76S\Documents\ope2027\renovarTemas` (en el shell del dispositivo: `$HOME/mnt/renovarTemas`). Si no está conectada, solicita acceso a esa ruta con la herramienta de acceso a carpetas.

```
renovarTemas/
├── _config/
│   ├── programa_oficial.md       ← títulos oficiales del temario (fuente del título exacto)
│   ├── normativa_verificada.md   ← registro compartido de normas ya comprobadas
│   ├── ejemplos/                 ← temas de referencia bien elaborados por Pedro (.docx)
│   └── promptUniversal.txt       ← prompt original (referencia)
├── temas_base/     "NN. Título.md"            ← contenido previo de Pedro
├── preguntas/      preguntasTemaNN.csv        ← preguntas OFICIALES de examen, UTF-8 (fuente: _general/preguntasGeneral.csv)
├── docx_anteriores/                           ← versiones Word previas (solo referencia)
├── salida/         "NN. Título.docx"          ← AQUÍ va el resultado
├── informes/       NN_informe.md              ← informe de cada tema
└── estado.csv      (separador ;)              ← seguimiento de todos los temas
```

Localiza los archivos por el número de tema. Si falta el .md, dilo y pídelo. Si falta el CSV, avisa y continúa usando solo el .md y las preguntas que contenga. Si hay un .docx anterior, puedes consultarlo, pero la base es el .md.

### Formato del CSV

Columnas: `ID, TEXTO, RESPUESTA_A..D, CORRECTA_A..D, ORIGEN, AVISO`.
- Todas las preguntas son de **exámenes oficiales** (`ORIGEN = OFICIAL`): cobertura obligatoria. El tema debe permitir responderlas todas.
- `CORRECTA_*` vale `S` (correcta) o `N`. Si las cuatro valen **`A`**, la pregunta fue **ANULADA** (respuestas confusas, erróneas o varias ciertas) y el campo `AVISO` lo indica.
- Si no existe CSV para el tema, no hay preguntas oficiales de ese tema: desarrolla el tema a partir del título y el .md.

**Preguntas anuladas:** no tienen clave válida, pero sí cuentan para la cobertura. Desarrolla en el tema el conocimiento necesario para entenderlas, incluido el matiz que pudo provocar la anulación (por ejemplo, dos opciones válidas). En el informe, indica por qué es probable que se anulara.

No des por buena la respuesta del CSV. Verifícala: si es errónea, ambigua o la normativa ha cambiado desde el examen, enseña lo correcto y anótalo en el informe.

### Temas de referencia (`_config/ejemplos/`)

Antes de diseñar la estructura, abre uno o dos ejemplos, eligiendo los más parecidos en tipo al tema que vas a elaborar (jurídico o normativo, tecnológico o sistemas del SAS). Úsalos como patrón de:
- profundidad y extensión por apartado;
- equilibrio entre texto desarrollado, tablas y esquemas;
- recursos de estudio (cuadros comparativos, recuadros de claves, resúmenes);
- maquetación del Word: estilos, portada, índice, encabezados, tablas. Si son .docx, inspecciona sus estilos (fuentes, tamaños, colores de títulos y tablas) y replícalos.

No copies su contenido ni les des valor de fuente: son un modelo de forma y nivel, no de datos. Si la carpeta está vacía, aplica los criterios de este documento.

---

## 1. MISIÓN Y PRINCIPIO

Elabora un tema de estudio completo, riguroso, actualizado y orientado a examen tipo test para la oposición de **Técnico/a de Función Administrativa, opción Sistemas y Tecnología de la Información, del SAS**.

No te limites a corregir, resumir o convertir el Markdown, ni a responder las preguntas. El proceso es:

**ANÁLISIS → INVESTIGACIÓN → CONTRASTE → ESTRUCTURACIÓN → REDACCIÓN → CONTROL DE COBERTURA → REVISIÓN → MAQUETACIÓN → AUDITORÍA → ENTREGA**

Objetivo: **MEJORAR + AMPLIAR + ACTUALIZAR + ESTRUCTURAR** el trabajo de Pedro, no sustituirlo. Conserva los conceptos, terminología, ejemplos, estructura e información del SAS que sean válidos.

## 2. EL TÍTULO MANDA

Toma el título literal de `_config/programa_oficial.md`. Si no está, usa el que dé Pedro o el del .md, e indícalo en el informe. Analiza el título: materias principales y secundarias, conceptos, organismos, normativa, tecnologías, estándares, sistemas del SAS y procesos. Determina de qué tipo es el tema (tecnológico, jurídico, organizativo, datos, seguridad, etc.) y adapta la estructura. No hay plantilla fija.

Consulta en `programa_oficial.md` los títulos de los temas vecinos. Lo que tenga tema propio se trata aquí solo en lo necesario y con remisión ("se desarrolla en el Tema NN"), para no duplicar contenido.

## 3. TRATAMIENTO DEL .MD

Léelo entero, incluidas las tablas y las preguntas que contenga (también cuentan como preguntas de control). Clasifica su contenido: correcto (se conserva), insuficiente (se amplía), desactualizado (se actualiza), dudoso (se investiga), incorrecto (se corrige si la evidencia lo demuestra) y no verificable (no se presenta como hecho). Integra las correcciones con naturalidad en el tema y regístralas en el informe.

## 4. INVESTIGACIÓN Y FUENTES

Investiga siempre, y a fondo cuando haya normativa, organismos, sistemas del SAS, planes, estrategias, cifras, fechas, estándares o versiones.

Jerarquía de fuentes:
1. Oficiales: BOE, BOJA, EUR-Lex, Junta de Andalucía, SAS, ministerios.
2. Institucionales y técnicas: normalización, reguladores, documentación primaria de proyectos o fabricantes.
3. Académicas y especializadas.
4. Secundarias: solo como complemento y atribuidas como tales.

**Antes de investigar normativa, lee `_config/normativa_verificada.md`.** Si una norma ya está comprobada hace menos de 3 meses, reutiliza ese resultado. Al terminar, añade las normas nuevas que hayas comprobado: norma, objeto, vigencia y modificaciones, fecha de comprobación, URL y temas en los que aparece.

## 5. NO INVENTAR

No inventes sistemas, plataformas, proyectos, fechas, leyes, artículos, órganos, competencias, cifras, versiones, estándares ni relaciones entre sistemas. Distingue entre:
- hecho documentado: se afirma;
- fuente secundaria: se atribuye;
- análisis técnico: se presenta como análisis;
- inferencia: nunca se presenta como dato oficial. No escribas "El SAS utiliza X" si solo lo deduces; escribe "Esta arquitectura permite…".

Los ejemplos hipotéticos se marcan como tales ("Por ejemplo, hipotéticamente…"). Para datos que cambian con el tiempo, usa "A fecha de elaboración del tema…". Si dos fuentes discrepan, prevalece la de mayor autoridad y más reciente. Si no se puede resolver, refleja la incertidumbre.

## 6. NORMATIVA Y SAS

- Normativa: identifica las normas relevantes y comprueba vigencia, modificaciones y ámbito territorial. Explica solo lo relacionado con el tema. Las normas derogadas solo aparecen como contexto histórico.
- SAS: investiga la aplicación concreta en el SAS, la Junta de Andalucía y el SSPA (sistemas, planes y estrategias vigentes). Distingue entre teoría general, normativa estatal, normativa autonómica y aplicación en el SAS.

## 7. PREGUNTAS: ANÁLISIS Y COBERTURA

Analiza todas las preguntas (CSV más las del .md). Para cada una: qué concepto evalúa, qué conocimiento necesita, cuál es la respuesta correcta y por qué, por qué fallan las alternativas cuando sea útil, y en qué apartado del tema se cubre.

Construye internamente la matriz: pregunta → concepto → apartado → ¿cobertura suficiente? Las preguntas detectan contenido examinable, pero no definen el tema: desarrolla todo lo que exija el título aunque no haya salido nunca en un examen.

**Auditoría final pregunta a pregunta:** ¿podría un opositor responderla estudiando solo este tema? Si no, amplía el apartado correspondiente y vuelve a comprobarlo.

**Auditoría de trampas:** cuando una pregunta dependa de un matiz (términos parecidos, excepciones, fases, competencias, respuestas parcialmente correctas), asegúrate de que ese matiz está explicado.

Si hay muchas preguntas (más de 80), trabájalas por lotes y agrúpalas por concepto. Si es útil, apóyate en código para agruparlas, pero el análisis de cada una lo haces tú.

## 8. CONTENIDO Y REDACCIÓN

- Nivel técnico, administrativo y jurídico cuando corresponda, orientado a examen. Ni resumen superficial ni manual universitario.
- La extensión la marcan la complejidad y el temario. Sin relleno.
- Para conceptos confundibles, explica diferencias, similitudes, finalidad y ámbito. Presta especial atención a definiciones, clasificaciones, fases, acrónimos, plazos, fechas y competencias.
- Equilibrio entre explicación desarrollada y elementos memorizables: tablas comparativas, esquemas, fases y listas, solo cuando aporten.
- Incluye tecnologías o estándares solo si son pertinentes, y explica siempre su relación con el tema.
- Español de España, registro formal, párrafos cortos, sin marketing ni frases vacías.
- Al final, "Fuentes y referencias" con las fuentes realmente consultadas (organismo, título, fecha, URL). No inventes URLs. La información normativa, institucional o estadística debe poder trazarse a una fuente.
- No incluyas en el Word una batería de preguntas con clave si no la verificas. Opcionalmente, añade un anexo breve de "Claves para el test" con los matices más preguntados.

## 9. CONTROL DE CALIDAD ANTES DEL WORD

Comprueba: título cubierto · .md leído entero · todas las preguntas analizadas · cobertura completa · investigación hecha · información temporal actualizada · vigencia de la normativa · contexto SAS · sin contradicciones · terminología correcta · ninguna afirmación sin respaldo.

## 10. DOCX

Lee el skill `docx` antes de generarlo. Documento sobrio y pensado para estudiar e imprimir: portada, índice, títulos numerados y jerarquizados, encabezado, pie con número de página, tablas legibles, estilos coherentes, saltos de página adecuados y sin títulos huérfanos.

Guárdalo en `salida/NN. Título.docx`. Después, ábrelo o conviértelo para revisarlo: que el contenido esté completo y que títulos, tablas, encabezados y pies estén bien. Corrige y regenera si hace falta.

## 11. INFORME, REGISTROS Y ENTREGA

1. Escribe `informes/NN_informe.md` con:
   - preguntas con respuesta del CSV incorrecta o discutible (ID, motivo, fuente);
   - preguntas anuladas: motivo probable de la anulación y dónde se cubre en el tema;
   - correcciones y actualizaciones importantes respecto al .md original;
   - datos que no se han podido verificar;
   - remisiones a otros temas.
2. Actualiza `_config/normativa_verificada.md`.
3. Actualiza la fila del tema en `estado.csv`: ESTADO=ELABORADO, FECHA y OBSERVACIONES breves. Edita el archivo con un script que lo lea y lo reescriba; nunca lo reconstruyas de memoria.
4. Respuesta final breve: tema elaborado, que se ha investigado y contrastado, cuántas preguntas se han cubierto y cuántas se han marcado en el informe, limitaciones relevantes y ubicación del .docx. No pegues el tema en el chat.

## 12. REGLA DE ORO

El documento tiene que ser correcto, actualizado, verificable, completo respecto al programa y útil para aprobar el test. No basta con que parezca completo. La calidad prima sobre la velocidad.