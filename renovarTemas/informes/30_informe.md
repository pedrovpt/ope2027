# Informe – Tema 30

**Título oficial:** Gestión del Porfolio de Sistemas de Información. Mapa de soluciones digitales. Sistemas de información transversales del Servicio Andaluz de Salud.
**Fecha de elaboración:** 01/10/2026 · **Salida:** `salida/30. Gestión del Porfolio.docx` (33 páginas)

## 1. Preguntas oficiales (CSV)

| ID | Clave CSV | Verificación | Apartado |
|---|---|---|---|
| 6523 | A (@sas/ + wc-stic- + descripción) | **Correcta.** Confirmado en los anuncios de versiones del catálogo de componentes web del Confluence del SAS (1.0.15, 1.0.36, 1.35.0): @sas/wc-stic-autocomplete, -input, -table, etc. | 6.11.2 y 9.1 |

- Preguntas anuladas: ninguna.
- Preguntas con clave incorrecta o discutible: ninguna en el CSV.

## 2. Preguntas del .md original (no oficiales)
Las 25 preguntas del .md quedan cubiertas (apartados 3, 4, 5, 7 y 9.2). No se incluyen en el Word.
- **P24** (mayor riesgo al migrar un data warehouse a la nube, clave A «latencia»): **discutible**. Seguridad, protección de datos de salud, soberanía y cumplimiento normativo son al menos tan defendibles como la latencia. No conviene memorizar esa clave.
- **P1–P20**: preguntas de sentido común con distractores absurdos; todas con clave B correcta.
- **P21–P23, P25**: claves razonables (integración gradual con middleware, explicabilidad de la IA, HL7 FHIR/SNOMED CT, auditoría de accesos).

## 3. Correcciones y mejoras respecto al .md
- El .md era genérico, sin ninguna referencia concreta al SAS salvo el catálogo de componentes. Se han añadido: catálogo de aplicaciones de ayudaDIGITAL (152 aplicaciones, 6 categorías), Diraya y sus módulos estructurales (documento SAS de 2004), BDU/GADU/NUHSA, Estructura, MACO, DMSAS/idenTIC/AGESCON, Certificado de Empleado Público, Citación, TurnoSAS+, Buzón Profesional, AviSAS+, Mercurio, BandeJA, Port@firmas, eCO, @ries, BPS (Resolución 0068/18), OTI, OCA, componentes corporativos de integración (MACO, DMSAS, Estructura, BDU, profesionales/adscripción, callejero) y el catálogo de componentes web con ejemplos reales y versiones.
- Se ha añadido la base teórica que faltaba: proyecto/programa/porfolio/operaciones, tipos de porfolio (proyectos, APM, servicios ITIL), inventario vs. catálogo vs. CMDB vs. mapa, modelos McFarlan/Ward-Peppard y TIME, marcos (PMI 4.ª ed., ISO 21504:2022, MoP, COBIT 2019 APO05, ITIL, TOGAF/ArchiMate), gobernanza, indicadores, gestión ágil.
- Se ha añadido el marco normativo de la reutilización (Ley 40/2015 arts. 157-158, ENI cap. VIII, CTT), el inventario de activos del ENS (op.exp.1) y el art. 30 RGPD.
- El apartado «Marco estratégico de transformación digital» del .md (fases 1–7) mezclaba fases del porfolio con los otros dos conceptos y presentaba «relevancia para el profesional» como fase; se ha reorganizado.
- El cuadro comparativo del apartado 8 del .md estaba vacío (también en el Word original); se ha rellenado (apartado 8).
- El .md citaba fuentes genéricas sin URL; se han sustituido por fuentes trazables.
- Imágenes: el Word original no contenía ninguna imagen (0 revisadas).

## 4. Datos no verificados o con limitaciones
- **«Mapa de soluciones digitales»:** no se ha localizado ningún documento público del SAS con ese título. El tema lo explica como concepto de arquitectura empresarial y construye una representación por capas **didáctica** a partir del catálogo oficial (marcada como tal en el Word).
- La correspondencia entre las soluciones y los programas de la ESDA es interpretación didáctica (marcada).
- El significado de «stic» en el prefijo se asocia a los servicios TIC del SAS (STIC); ninguna fuente lo desarrolla expresamente.
- Las cifras del catálogo de ayudaDIGITAL (152 apps) y de la BDU (>8 millones de registros) son instantáneas.
- PMI: se cita la 4.ª edición (2017) del *Standard for Portfolio Management*. No se ha confirmado si hay una edición posterior.
- La denominación vigente de la DG TIC del SAS (DG de Salud Digital e Infraestructuras Tecnológicas) se toma del Tema 34 elaborado; no se ha vuelto a comprobar en BOJA en esta sesión.
- El documento de Diraya de 2004 está alojado en un blog (no oficial); se usa solo como contexto histórico.

## 5. Remisiones
Temas 10, 27, 28, 29, 33, 34, 36, 37, 38, 42, 45, 55, 56, 57, 66, 69, 74, 83, 87, 88, 89 y 90.
