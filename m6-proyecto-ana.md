# Proyecto 4 · Módulo 6 · Ana (ventas) — Distribuidora Solmar

## 1. Mi flujo con las cinco piezas de la plantilla (lectura 6.1)

- Disparador: todos los lunes a las 9:05, una vez que los tres vendedores enviaron su reporte (deben llegar antes de las 9:00). Si el lunes es festivo, arranca el primer día hábil siguiente a la misma hora. No es "cuando se pueda": es un horario escrito.
- Registro: una hoja de cálculo compartida con tres pestañas, una por vendedor. Lo que llega por correo o chat se pega ahí como texto crudo y la IA trabaja sobre esa hoja; el texto crudo nunca se edita, queda como evidencia.
- Decisión: la regla de qué cuenta es una venta: solo lo FACTURADO dentro de la semana que se reporta (lunes a domingo anterior); no cuentan pedidos cancelados, cotizaciones ni folios repetidos. La IA marca en una columna extra "cuenta / no cuenta" con motivo. Los casos que no se resuelven solos y suben a Ana: estatus ambiguos (por ejemplo un "proceso de cierre" que podría facturar antes del domingo), cifras donde el total no cuadra con el detalle, y datos faltantes del vendedor.
- Respuesta: un borrador del reporte para el Director Comercial que la IA entrega a Ana a las 10:15; Ana lo revisa y lo envía antes de las 11:00 con su nombre. La IA nunca escribe al director directamente: una cifra mal en dirección cuesta caro y el criterio final es de Ana.
- Evidencia: la hoja con el texto crudo, la decisión folio por folio con su motivo y el borrador aprobado. La revisa Ana: 2 folios al azar por vendedor cada semana (5 minutos) y el mes completo al cierre de mes.

## 2. Lo que no delegaría y por qué

- La decisión final del reporte y la comunicación con el director: ahí el costo del error es alto y es un mensaje con el nombre de Ana.
- La creación de criterios (qué entra y qué no) cuando hay casos raros: eso es negocio, no cálculo.
- El seguimiento a los vendedores si un reporte no llega a las 9:00: pedirlos es responsabilidad de Ana y evita que un bot mande correos de presión por su cuenta.

## 3. Mi prueba con los datos de este lunes

Instrucción dada a la IA: cuenta solo lo facturado en la semana; excluye cancelados, cotizaciones y folios repetidos (cuenta una vez aunque esté pegado dos veces); lo que no esté facturado no entra; calcula todo folio por folio, no desde el total del vendedor.

El borrador que entregó la IA:
- Beto Ríos: cuentan F-1041 ($12,400), F-1042 ($18,900) y F-1045 ($27,300). No cuenta F-1044 por estar Cancelado. Total facturado: $58,600 = 97.7% de su meta de $60,000. (El total que envió Beto, $68,100, sumaba el pedido cancelado.)
- Carla Núñez: cuentan F-2210 ($31,000), F-2211 ($22,500, capturado dos veces: cuenta una) y F-2213 ($15,800). Total facturado: $69,300 = 115.5% de la meta. (El total de Carla, $91,800, sumaba el duplicado.)
- Mauricio Pérez: cuentan lo facturado: Papelería Central $24.5k + Cafetería Roma $17.2k = $41,700 = 69.5% de la meta. No cuenta Hoteles del Valle ($33.0k) porque está "en proceso de cierre" y aún no está facturado; si se factura antes del domingo, entra a la semana siguiente.
- Equipo: $58,600 + $69,300 + $41,700 = $169,600 = 94.2% de la meta del equipo de $180,000.
- Nota de exclusiones (el reporte debe llevarla): cancelado (F-1044), folio duplicado (copia de F-2211) y facturación pendiente (Hoteles del Valle).

## 4. Mi revisión (qué comparé y qué corregí)

Comparé folio por folio contra el criterio y encontré dos cosas concretas: (1) mi primera instrucción a la IA decía "súmale los totales que traen los vendedores" y con eso la IA repetía los totales malos de Beto y de Carla: lo corregí a calcular folio por folio; (2) el total de Beto incluía un pedido cancelado y el de Carla su folio duplicado: ambos quedaron documentados en la nota de exclusiones, que es lo que pide el formato del reporte. Con el borrador marcado como "aprobado por Ana", queda listo para las 11:00.
