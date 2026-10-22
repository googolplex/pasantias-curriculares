# Misión: Cierre de Pasantía

**Proyecto:** Pasantías Curriculares — FP-UNA  
**Inicio:** 2026-10-22  
**Estado:** EN CURSO — criterios de auditoría iniciales aprobados.

## Objetivo
Controlar preliminarmente el expediente de cierre de pasantía curricular y emitir un informe para WhatsApp. No equivale a aprobación institucional.

## Tres controles requeridos
1. **Existencia y nomenclatura:** comprobar F1, F2, F3, F4, F5; registrar faltantes y comprobar exactamente `nombre_completo_normalizado_fN.pdf` sin sufijos adicionales. Identificar tickets adjuntos. El último prompt menciona `nombre_del_alumno_ticket_cierre.pdf` como nomenclatura de ticket de cierre, pero la obligatoriedad del ticket de cierre aún requiere confirmación.
2. **Cronología:** verificar orden inicio ≤ fin y coincidencia de estas fechas en F2, F4 y F5 cuando existan; examinar fechas de tramitación, seguimientos y actividades, sin declarar irregularidad por diferencias administrativas admisibles.
3. **Horas:** extraer horas declaradas, contar las jornadas con actividades documentadas, detectar fechas omitidas/feriados y calcular el promedio diario necesario o totales cuando existan horarios suficientes. Distinguir siempre (a) horas declaradas, (b) horas aritméticamente compatibles bajo supuestos, (c) horas efectivamente verificadas. No certificar (c) solo por la existencia de (a).

## Regla aprobada — tolerancia cronológica del Formulario F2 (2026-10-22)
- Comparar «Respuesta de la Organización» con la **fecha de finalización de la pasantía**, no asumir que debe preceder al inicio.
- Puede ser ligeramente anterior o posterior a la finalización, sin generar observación automática.
- **Caso aceptado:** respuesta el 01/10/2026 y finalización el 06/10/2026: cinco días de diferencia **CONFORME** para este criterio.
- **No existe máximo numérico general aprobado**. No inventarlo. Separaciones ostensiblemente grandes requieren juicio/revisión del tutor, no rechazo automático.
- Esta tolerancia NO exime de comprobar secuencia inicio/fin ni de conciliar horas.

## Caso de prueba histórico — anonimizado
Se recibieron seis PDF: F1–F5 y ticket de apertura. Se confirmó existencia de 5/5 y denominación correcta de 2/5; tres archivos llevaban sufijos adicionales. Inicio 01/09/2026, finalización 06/10/2026, respuesta de organización 01/10/2026. Se declararon 240 horas y se describieron 30 jornadas de actividad; 240/30 = ocho horas por jornada como **promedio necesario**, no como horas verificadas. Un seguimiento de 240 h fechado 01/10, anterior a actividades registradas hasta 06/10, requiere conciliación documental sin presuponer fraude ni error cierto.

## Salida
Mensaje único, breve, listo para copiar a WhatsApp; sin saludos/prólogos, PDF de informe ni datos personales innecesarios. Estados: APROBADO / REQUIERE REVISIÓN. Indicar nombres correctos, fechas comparadas, horas declaradas/calculadas/verificadas y correcciones que deben reenviarse al mismo tutor.

## Pendientes de definición
- Requisitos institucionales definitivos y obligatoriedad del ticket de cierre.
- Evidencia necesaria para acreditar las horas efectivamente trabajadas.
- Valor de tolerancia general (si el tutor opta por fijarlo).
- Matriz final de aprobación documental de cierre.

## Privacidad
No publicar expedientes, C.I., contactos ni PDF de estudiantes en GitHub.

## Reglas aprobadas — firmas y extensión del informe (2026-10-22)
- **Firmas del profesor:** en la auditoría de **cierre** se debe comprobar visualmente que **F2 y F5 estén firmados por el profesor tutor**, Roger Armoa en el caso de prueba actual. No basta con que aparezca su nombre escrito; verificar evidencia de firma. No asumir que cualquier firma pertenece al profesor si no puede identificarse su autor. Si falta o no es verificable, indicar **REQUIERE REVISIÓN**, especificando cuál formulario requiere firma o confirmación.
- La firma docente obligatoria en **F2 y F5** es una regla específica del **cierre de pasantía**. No modifica automáticamente la exclusión de datos/firma del Tutor Orientador en la misión preliminar `controlF1`.
- **Extensión del informe final del estudiante:** se prefiere **como máximo una página**. Si supera una página, emitir un **AVISO no bloqueante**, indicando el número de páginas observado. Exceder una página **no es grave y no basta por sí solo** para asignar REQUIERE REVISIÓN o RECHAZADO.
- Para esta regla, «informe final» significa el **informe del pasante presentado como F5**, no el mensaje breve de auditoría enviado por WhatsApp; este último también debe mantenerse conciso.
- Si el PDF contiene formularios u hojas administrativas además del informe, no confundir la cantidad de páginas del archivo con la extensión de la parte narrativa. Ante ambigüedad, describir lo verificado sin emitir aviso injustificado.

## Reglas aprobadas — evaluación empresarial F4 y consistencia entre F2/F4/F5 (2026-10-22)
- **F4: evaluación y firma de la empresa obligatorias.** Verificar visualmente que el formulario F4 contiene una evaluación efectuada por la organización receptora y una firma atribuible a su representante autorizado. Si la evaluación o la firma faltan, o no se pueden verificar, el cierre **REQUIERE REVISIÓN**; no confundir un nombre impreso con una firma.
- **Preferencia de identidad:** de preferencia, la persona que evalúa y firma F4 será el mismo contacto o responsable de la organización declarado por el alumno en F1. Comparar los nombres cuando consten en ambos documentos. **Una persona diferente no constituye por sí sola un incumplimiento**: emitir observación informativa o pedir aclaración si la identidad/capacidad de quien firmó no es comprobable. No rechazar únicamente porque no coincide con el contacto F1.
- **Concordancia temporal obligatoria:** extraer y comparar fechas de **inicio** y **finalización** consignadas en F2, F4 y F5. Las fechas deben coincidir entre los tres formularios y respetar inicio ≤ fin. Ante discrepancia comprobada o dato ilegible, marcar **REQUIERE REVISIÓN**, indicando documento, campo, fechas encontradas y corrección o aclaración requerida; jamás inventar una fecha faltante.
- **Separación de reglas:** la tolerancia previamente aprobada de la fecha «Respuesta de la Organización» en F2 se mantiene, pero **no se aplica a las fechas de inicio/fin** que deben concordar entre F2, F4 y F5.

## Reglas aprobadas — identificación del informe, escala y situación laboral (2026-10-22)
- **Título explícito:** la salida al tutor/estudiante debe identificarse claramente como **«INFORME DE AUDITORÍA DE CIERRE DE PASANTÍA»**. No confundir con la auditoría preliminar F1 ni con el informe narrativo final del estudiante. El mensaje seguirá siendo breve y copiable a WhatsApp.
- **Escala de calificación:** comunicar y usar exactamente la siguiente correspondencia cuando se audite o informe una calificación: **E = Excelente; MB = Muy Bueno; B = Bueno; A = Aceptable**. No inventar una nota o calificación si no figura en la documentación. No convertir esta escala en el dictamen administrativo «APROBADO / REQUIERE REVISIÓN»: son conceptos distintos.
- **Alumno empleado en la organización:** determinarlo a partir de una declaración explícita en el **escrito del informe final del propio estudiante (F5)**. Si declara que **ya es empleado de la empresa receptora**, debe adjuntar/presentar **certificado de trabajo**. Verificar la presencia del certificado; si no se presenta, marcar **REQUIERE REVISIÓN** por documento faltante. Si el estudiante declara que no es empleado, no exigir certificado por esta regla. Si el informe final no informa su situación laboral, **no asumir** que es empleado: registrar «situación laboral no determinada en el informe final» y solicitar aclaración antes de decidir si corresponde certificado; no inventar un vínculo laboral a partir de actividades realizadas o del nombre de la empresa.
- El certificado de trabajo es un requisito **condicional**, no un documento universalmente obligatorio para todos los estudiantes.

## Regla aprobada — consistencia de identidad F1–F5 (2026-10-22)
- Verificar que **el número de cédula de identidad y el nombre completo del alumno sean consistentes en F1, F2, F3, F4 y F5**. La enumeración original repetía F4; se interpreta el último como F5.
- Normalizar únicamente para comparar: permitir diferencias de mayúsculas/minúsculas, tildes, espacios repetidos y separadores de la cédula (puntos/espacios). **No aceptar cambios de dígitos ni nombres/apellidos distintos** como equivalentes.
- Comparar con el dato escrito **dentro de cada formulario**, no inferirlo del nombre de archivo. Una divergencia comprobada o un dato no verificable en un formulario obligatorio implica **REQUIERE REVISIÓN**, detallando el formulario afectado sin divulgar el número completo de cédula en el mensaje para WhatsApp.
