# Proyecto 4 · Módulo 6 · Ana (ventas) — Distribuidora Solmar

## 1. Mi flujo con las cinco piezas de la plantilla (lectura 6.1)

- Disparador (¿cuándo arranca?): todos los lunes a las 9:05, una vez que los tres vendedores enviaron sus reportes (deben llegar antes de las 9:00). Si el lunes es festivo, arranca el primer día hábil siguiente a la misma hora. No es "cuando se pueda": es un horario escrito.
- Registro (¿dónde queda?): una hoja de cálculo compartida con tres pestañas fijas, una por vendedor. Lo que reciben por correo o chat se pega ahí como texto crudo y la IA trabaja sobre esa hoja; el crudo nunca se edita, queda como evidencia.
- Decisión (¿qué regla corrige?): el criterio de venta: cuenta solo lo facturado dentro de la semana que se reporta (lunes a domingo anterior); NO cuentan pedidos cancelados, cotizaciones ni folios repetidos. La IA debe marcar en una columna extra: "cuenta / no cuenta + motivo". Casos que no se resuelven solos y pasan a Ana: folios con estatus ambiguo (por ejemplo "proceso de cierre" que podría facturar antes del reporte), cifras que no cuadren entre total y detalles, y cualquier dato faltante del vendedor.
- Respuesta (¿qué entrega?): un borrador del reporte para el Director Comercial que llega a Ana a las 10:15. Ana lo revisa y lo manda con su visto bueno antes de las 11:00. La IA nunca manda al director directamente: Ana aprueba porque si la IA se equivoca en una cifra sería un error ante dirección y el criterio de negocio es de Ana.
- Evidencia (¿qué queda guardado?): la hoja con el texto crudo, la columna de decisión "cuenta / no cuenta" con motivo, y el borrador final enviado. Cada domingo revisa la evidencia Ana: compara muestras de 2 folios por vendedor contra el sistema de facturación una vez por semana y el mes completo al cierre del mes.

## 2. Lo que no delegaría y por qué

- La decisión final de qué entra al reporte frente a casos raros: los ambigüedades pidon criterio de negocio.
- El mensaje al director: una cifra malconvocada ahí tiene costo alto ypolitico; solo Ana comunica y explica.
- Hablar con los vendedores cuando el reporte no llega a las 9:00: pedir y hacer seguimiento es responsabilidad de Ana y así evita que la IA dispara correos solos "presionando" al equipo.
- Lo que delego con gusto: extraer y ordenar los datos, detectar duplicados, calcular porcentajes y preparar el borrador con la nota de exclusión.

## 3. Mi prueba con los datos de este lunes

Criterio dado a la IA: cuenta solo lo "Facturado"; excluye cancelados, cotizaciones y folios repetidos; si el vendedor envía dos veces el mismo folio, cuenta una; las cifras "en proceso de cierre" no cuentan si no están facturadas.

Lo que entregó la IA:
- Beto Ríos: cuenta F-1041 (12,400), F-1042 (18,900) y F-1045 (27,300). Excluye F-1044 por estar Cancelado. Ventas facturadas: $58,600 = 97.7% de su meta de $60,000. (El total que escribió Beto, $68,100, era sumando el pedido cancelado). ✔ correcto
- Carla Núñez: cuenta F-2210 (31,000), F-2211 (22,500, capturado dos veces: cuenta una) y F-2213 (15,800). Excluye la copia repetida de F-2211. Ventas facturadas: $69,300 = 115.5% de la meta. (El total de Carla, $91,800, era sumando el duplicado por $22,500). ✔ correcto
- Mauricio Pérez: cuenta lo facturado: Papelería Central 24.5 + Cafetería Roma 17.2 = $41,700 = 69.5% de la meta. Excluye Hoteles del Valle (33.0) porque está "en proceso de cierre": la regla sin factura no cuenta; si factura antes del domingo, entra la semana que viene. ✔ correcto
- Equipo: 58,600 + 69,300 + 41,700 = $169,600 = 94.2% de la meta de $180,000.

## 4. ¿Qué comparar y qué corregí?

Comparé cada folio con el criterio de facturación y encontré un problema en mis instrucciones oriiginles y otro en los reportes: (1) mi primer prompt a la IA decía "súmate los totales que trae cada vendedor", la IA con esa instrucción repetía los totales mal con los que ya servíamos; corregí y ahora se calcula desde folio por folio. (2) el total de Beto sumaba un pedido cancelado y el de Carla sumaba su folio duplicado: ambos quedan notados en la nota de exclusiones del reporte, y con eso el reporte queda listo para revisión de Ana antes de las 11:00.
