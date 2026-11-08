# Proyecto 2 · Módulo 4 · Leo (atención a clientes) — Tienda Pino Real

## 1. Mi proceso con el asistente (y qué tarea pedí en cada paso)

- Paso 1: le pedí al asistente EXTRAER de cada correo el número de pedido, la fecha de compra, la fecha de entrega y lo que pide el cliente. Para qué: esos datos son los que cruza contra las políticas y evitará classified errores al tomar decisiones.
- Paso 2: con esa vista, le pedí CLASIFICAR los 10 correos usando mis categorías y urgencia Alta/Media/Baja. Para qué: la tarea de ordenar en grupos definidos es clasificación; extraerla yo a mano tardaba tiempo y el asistente el matcheo la hace mejor con instrucciones de categoriías exactas.
- Paso 3: le pedí REDACTAR una respuesta base por categoría con huecos entre corchetes para lo que no se puede saber (nombre, pedido, estatus, fechas). Para qué: la tarea de escribir es redactar, y la plantilla es aplicable a varios correos de la misma categoría.
- Paso 4: en la última vuelta le pedí RESUMIR los 10 correos del día en 4 líneas para reportar la carga del día a mi supervisora. Para qué: la tarea de condensar es resumen, útil para la vista de gestión, no para el cliente.

## 2. Mi clasificación (tabla de los 10 correos)

Categoría definida: 1) Estado del pedido y envío; 2) Producto dañado o incompleto; 3) Cambios y devoluciones; 4) Facturas; 5) Cobros y cancelaciones; 6) Queja formal o tema que necesita persona. Hoy es lunes 19 de octubre.

| Correo | Cliente | Categoría | Urgencia | Razón en una frase |
|---|---|---|---|---|
| 1 | Patricia Lara | 1 · Estado | Alta | Compró el 7 oct (pedido 48213) y lleva 10 días naturales, más que el plazo de 3 a 5 días hábiles prometido al pedir datos de logística. |
| 2 | Héctor Mendoza | 2 · Dañado | Alta | Horno con abolladura recibido ayer y con fotos: aviso dentro de los 3 días naturales de la política, repentida suncio costo. |
| 3 | Daniela Ortiz | 4 · Facturas | Media | Compró el 28 sep y las facturas solo se emiten durante el mes de la compra: se debe informar que ya no aplica. |
| 4 | Julián Ramos | 3 · Cambios | Media | Sábanas recibidas el viernes y sin abrir, dentro de los 15 días naturales: cambio de color posible siguiendo al almacén. |
| 5 | Silvia Cortés | 6 · Persona | Alta | Mención de Profeco y amenaza de publicación: la política manda las quejas formales a la supervisora Marcela Reyes el mismo día, jamás de la respuesta base. |
| 6 | Andrés Beltrán | 1 · Precompra | Baja | Pregunta por disponibilidad de color que no está en las políticas y el paso estimado que la política sí define (Mérida es ciudad principal: 3 a 5 días hábiles). |
| 7 | Fernanda Ibarra | 5 · Cobros | Alta | Cobro de [48455] de un mismo pedido: la política define revisión de 2 días hábiles y devolución del banco de 3 a 5 días hábiles; solo se usa el identificador de 4 dígitos. |
| 8 | Rodrigo Salinas | 5 · Cancelación | Alta | Pide cancelar el pedido 48460 hecho hoy: solo procede el estatus de salida desde el almacén (hueco real). |
| 9 | Lucía Vargas | 4 y 2 · Precio doble | Media | Cabe en dos categorías: factura dentro del mes de compra (ojo 12 oct) y faltante de bolsa de tornillos: avisado el lunes tras llegar el jueves, o sea, cuatro días naturales después, FUERA del plazo de 3 días de la política. |
| 10 | Mauricio Duarte | 6 · Persona | Alta | Pide devolución sin identificar pedido ni causa y con tono irritado; la respuesta base no debe opinar sobre tema incerto. |

## 3. Respuestas base (todas con huecos y toda regla tomada de las políticas)

### Base 1 — Estado del pedido y envío
"Estimado/a [NOMBRE]: tu pedido [N° DE PEDIDO] fue registrado el [FECHA]. El envío está tardando dentro/después del horario prometido de 3 a 5 días hábiles en ciudades principales y de 5 a 8 en el resto del país. [SITUACIÓN DEL PEDIDO: en tránsito desde (fecha) / en revisión con la paquetería]. Seguiremos por labor desde (correo)/mail de servicio desde el cual puedes pedirmenos [FECHA ESTIMADA o INDICACION]. Cualquier cosa, háznos corregir en esta línea."

### Base 2 — Producto dañado o incompleto
"Estimado/a [NOMBRE]: gracias por tus fotos del [PRODUCTO] del pedido [N°]. Si el aviso llegó dentro de los 3 días naturales posteriores a la entrega, corremos una reposición sin costo de peza única o faltante: dejamos el proceso en tránsito, a más pronto [FECHA ESTIMADA] el nuevo/la reparación llega al almacén para su envío de 3 a 5 días hábiles. Labor: atención de intercambio en un horario responsable."

### Base 3 — Cambios y devoluciones
"Estimado/a [NOMBRE]: tu cambio dentro de los 15 días naturales desde la entrega, producto sin uso y con empaque está considerada. Al confirmar tu solicitud, acompaña la reintroducción del viejo/paquete al recibirlo en el almacén: en 5 a 7 días hábiles después, la deiva llego a su facturación para depósito. La petición es asignada ya al almacén para su revisión."

### Base 4 — Facturas
"Estimado/a [NOMBRE]: las facturas se emiten únicamente durante el mes de la compra. Tu pedido [N°] de [FECHA DE COMPRA] [SE PUEDE FACTURAR en este ha, envía tus datos fiscales por este correo / YA NO APLICA porque el mes de la compra ya terminó]. El trámite lo emite el área de facturación y te llega al correo desde donde nos escribiste."

### Base 5 — Cobros y cancelaciones
"Estimado/a [NOMBRE]: revisé tu caso del pedido [N°]. [COBRO DUPLICADO]: confirmamos la repetición en tu estado de cuenta; el banco regresa el cobro extra en 3 a 5 días hábiles después de nuestra revisión de 2 días hábiles. [CANCELACIÓN]: pedimos a Almacén confirmar el estatus; si aún no salió, se cancela y la factura revirtencia no se aplica; si ya salió, se trata como devolución al recibo. Nunca solicitamos el número completo de tu tarjeta ni contraseñas."

### Base 6 — Información precompra (envíos)
"Estimado/a: los envíos a [CIUDAD, si ciudad principal] salen en 3 a 5 días hábiles desde la confirmación (5 a 8 días en el resto del país). La disponibilidad del color [COLOR] la confirma nuestro de ventas por este mismo correo: sin precio o garantías adicionales, todo queda en tu email confirms."

## 4. Lo que una respuesta base no resuelve (paso a persona)

- Correo 5 (Silvia): es queja formal con mención de Profeco: la política manda que la supervisora Marcela Reyes la atienda el mismo día y sin plantilla.
- Correo 1 (Patricia): lleva fuera de plazo prometido; los estatus del envío no están en la bandeja y hay que abrir caso con logística mientras mantenemos el contacto.
- Correo 10 (Mauricio): la causa no queda clara y la política no permite prometer devoluciones sin razón salvo que se deben obtener los datos del pedido; requiere llamada y discernimiento.
- Correo 9 (la parte del tornillo faltante): la aviso llegó fue después de 3 días naturales, es decir fuera de plazo de reposición automática: pedimos evaluarla con supervisora, no decidirlo con plantilla.
- La disponibilidad de color del correo 6: no hay inventario en las políticas, la confirma una persona.

## 5. Mi revisión (lo que comparé contra las políticas)

Comparé cada borrador, línea por línea, con las políticas y encontré dos errores del asistente: (1) ofrecía reposición sin costo automática para el correo 9, ignorando el plazo de 3 días naturales: corregí a evaluar con supervisora; (2) en la base de cobros pedía confirmar el pedido con datos de tarjeta completos: lo quité porque la política prohíbe pedir número completo, contraseñas o códigos por correo. También arreglé el servicio horario prometido para la primera forma: 24 horas hábiles máximo.
