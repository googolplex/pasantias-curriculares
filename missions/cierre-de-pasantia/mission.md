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

## Reglas aprobadas — F1 opcional y ticket de cierre (2026-10-22)
- **F1 es optativo en la documentación del cierre de pasantía.** Habitualmente se entrega durante la **apertura**. Su ausencia en el paquete de cierre **no constituye incumplimiento**, no modifica por sí sola el dictamen a REQUIERE REVISIÓN y no debe solicitarse como requisito de cierre.
- Mantener el control de presencia y nomenclatura de los documentos **F2, F3, F4 y F5**. Si F1 se adjunta voluntariamente, verificar también su nomenclatura e identidad; si no está, comparar nombre y cédula entre los formularios de cierre disponibles F2–F5 sin exigir F1.
- **Ticket de cierre:** una vez completada la presentación del expediente **por correo electrónico a Mesa de Entrada**, el alumno debe **enviar al mismo tutor de pasantía su ticket de cierre**. Incluir este paso como **recordatorio explícito** en el informe/mensaje de WhatsApp, especialmente cuando aún no conste el ticket. No presumir que el ticket ya existe antes de que Mesa de Entrada procese la presentación ni tratar automáticamente su ausencia durante la revisión previa como incumplimiento.
- El ticket de cierre debe usar el patrón `nombre_del_alumno_ticket_cierre.pdf` cuando se adjunte. Distinguirlo del ticket de apertura, que corresponde a otro trámite.
- Estas reglas reemplazan en esta misión toda referencia anterior a F1 como obligatorio para cierre o a la comparación de identidad F1–F5 como requisito incondicional.

## Regla aprobada — correo institucional del alumno (2026-10-22)
- **Observación notable obligatoria:** en los trámites de pasantía el alumno **no debe utilizar su correo electrónico personal**; debe emplear su **correo institucional**.
- Comprobar los correos que figuren como dirección del estudiante en los formularios disponibles y, cuando exista evidencia, el remitente de los trámites enviados por correo. No confundir correos de contacto de la empresa o de funcionarios con el correo del alumno.
- Si se detecta una dirección personal usada por el alumno, incluir expresamente una **OBSERVACIÓN NOTABLE** en el informe de auditoría de cierre y solicitar que emplee su correo institucional en las gestiones posteriores. No divulgar la dirección personal completa en el mensaje destinado a WhatsApp.
- Si no hay evidencia suficiente para identificar si el correo es personal o institucional, no inventar una conclusión: indicar **NO VERIFICABLE** si corresponde. No inferir que el trámite fue remitido desde una cuenta concreta por el solo hecho de que la dirección aparezca en un formulario.
- La observación sobre correo personal es un **aviso destacado**; no convertirla por sí sola en rechazo automático ni alterar los demás controles aprobados sin una instrucción expresa del tutor.

## Corrección aprobada — sufijos de archivos permitidos (2026-10-22)
- El tutor confirmó que estos sufijos **son correctos y se aceptan en el cierre**: `_firmado_EM` para F1 y `_ra` para F2 y F5.
- Ejemplos explícitamente conformes: `nombre_completo_f1_firmado_EM.pdf`, `nombre_completo_f2_ra.pdf`, `nombre_completo_f5_ra.pdf`.
- **No marcar estos tres nombres como nomenclatura incorrecta ni pedir renombrarlos**, siempre que correspondan al alumno y formulario correctos.
- Esta decisión **rectifica** las instrucciones anteriores que prohibían incondicionalmente cualquier sufijo adicional, al menos para los casos aprobados aquí. No extrapolar la aceptación a otros sufijos sin autorización.
- F1 sigue siendo optativo para la etapa de cierre.

## Regla aprobada — consistencia obligatoria del correo institucional (2026-10-22)
- El correo electrónico **del alumno** debe ser **institucional y consistente** entre todos los formularios de cierre en los que figure (F2, F3, F4 y F5; también F1 si se adjunta, aunque F1 es optativo).
- Comparar las direcciones del estudiante, normalizando únicamente espacios incidentales y diferencias de mayúsculas/minúsculas. **Diferentes direcciones institucionales no se consideran consistentes automáticamente**: solicitar aclaración o corrección.
- Si un formulario registra correo personal del alumno, emitir **OBSERVACIÓN NOTABLE** y dictamen **REQUIERE REVISIÓN** hasta que se rectifique o aclare. Esta regla sustituye la disposición anterior que consideraba el correo personal solo un aviso no bloqueante.
- No confundir los correos de la organización o de funcionarios con el del estudiante. Si un formulario no contiene un campo de correo del alumno, no inventar una ausencia ni exigir añadir un campo inexistente. Identificar los formularios comparados y los que no cuentan con este dato.
- Si el correo aparece ilegible o no es posible determinar si es institucional, consignar **NO VERIFICABLE** y solicitar aclaración. Evitar publicar la dirección completa del estudiante en WhatsApp.

## Precisión aprobada — campo de e-mail del pasante en F4 (2026-10-22)
- **El Formulario F4 sí incluye el campo E-mail entre los datos del pasante.** Es un campo que debe verificarse explícitamente en la auditoría de cierre.
- Comprobar que el correo consignado en F4 sea **institucional** y que **coincida con el correo institucional del alumno en los otros formularios que lo registren** (F2 y, cuando se adjunte, F1; también otros si contienen el campo).
- Correo personal, dirección distinta o campo obligatorio ilegible/vacío en F4: señalar específicamente **F4** en una **OBSERVACIÓN NOTABLE** y asignar **REQUIERE REVISIÓN** hasta corregir o aclarar.
- Esta precisión sustituye cualquier instrucción anterior que tratara la presencia de correo en F4 como meramente hipotética.

## Precisión aprobada — correo institucional en F1 (2026-10-22)
- **F1 también contiene el campo E-mail del pasante**: cuando se presenta, comprobar que esté completado, que sea una dirección **institucional** y que coincida con la del alumno en F2 y F4 y en cualquier otro formulario que la consigne.
- **F1 sigue siendo optativo para el cierre**: si no se adjunta, su ausencia nunca genera observación. Si se adjunta, sí se audita su correo.
- Si el correo del alumno en F1 es personal, ilegible, vacío o diferente del correo institucional presente en los demás formularios, incluir **OBSERVACIÓN NOTABLE** que identifique F1 y asignar **REQUIERE REVISIÓN** hasta corregir o aclarar.

## Regla aprobada — identificar explícitamente formularios comparados (2026-10-22)
- En el **INFORME DE AUDITORÍA DE CIERRE DE PASANTÍA**, toda conclusión de «CONSISTENTE», «COINCIDENTE» o «CONFORME» derivada de una comparación entre documentos debe **nombrar explícitamente los formularios efectivamente comparados**; nunca escribir solo «Nombre: consistente» o «Cédula: consistente».
- Para identidad, cuando están disponibles los cinco documentos: «Nombre completo: consistente entre F1, F2, F3, F4 y F5» y «Cédula de identidad: consistente entre F1, F2, F3, F4 y F5» **solo después de comprobar cada uno**.
- Como F1 es **optativo para cierre**, si no está adjunto indicar «consistente entre F2, F3, F4 y F5», sin simular que fue evaluado. Si falta o es ilegible un dato en cualquier documento, no declarar coincidencia total: informar la limitación o discrepancia y el formulario afectado.
- En fechas, especificar «fechas de inicio y finalización coincidentes entre F2, F4 y F5», siempre que estén comprobadas. En correo, citar exclusivamente los formularios que contienen un e-mail verificable, identificando faltantes o inconsistencias individualmente.
