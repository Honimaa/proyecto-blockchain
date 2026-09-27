# Propuesta individual

**Nombre:** Santiago Pinto Galeano

**Usuario de GitHub:** SantiagoP67

---

## El problema

> El problema en una sola frase, sin mencionar blockchain.

Una familia que contrata a un maestro de obra independiente para una remodelación tiene que entregar un anticipo sin ninguna garantía de que la obra se termine, y el maestro, a su vez, trabaja semanas sin garantía de que le paguen el saldo.

## ¿Quién lo sufre?

> Quién tiene el problema y en qué situación lo vive.

Lo sufre principalmente el hogar que contrata: una familia que va a remodelar un baño o una cocina, arreglar una fachada o levantar un segundo piso, y que contrata a un maestro de obra independiente porque una constructora formal es demasiado costosa para una obra pequeña.

La situación típica: el acuerdo se hace de palabra o por WhatsApp, y el maestro pide un anticipo para comprar materiales y pagar ayudantes. Con frecuencia la obra avanza lento, se detiene o se abandona, los materiales no llegan y el maestro deja de contestar. La familia queda con la obra a medias y sin su anticipo.

El problema también lo vive el maestro de obra: cuando termina, el cliente cambia condiciones, pone quejas para no pagar o retiene el último pago, y el maestro no tiene cómo demostrar qué se pactó.

## ¿Cómo se resuelve hoy y qué cuesta?

> Cómo lo resuelven hoy las personas afectadas y qué les cuesta en dinero, tiempo o esfuerzo.

Hoy se resuelve con:

- **Referidos y confianza:** se contrata a quien recomendó un vecino o un familiar.
- **Pagos por avance en efectivo o transferencia:** negociados en el momento, sin un registro claro de qué se entregó y qué se pagó.
- **Contratos impresos informales:** que rara vez se hacen valer, porque demandar cuesta más que el monto en disputa.
- **Alternativa formal:** contratar a una empresa con póliza de cumplimiento o usar una fiducia, lo que resulta desproporcionado para obras pequeñas.

Lo que cuesta:

- **Dinero:** la familia puede perder el anticipo completo y pagar de nuevo a otro maestro para terminar o rehacer lo mal hecho. El maestro pierde el saldo final y su margen.
- **Tiempo:** meses de obra detenida, búsqueda de un nuevo contratista y, si se reclama, procesos largos.
- **Esfuerzo:** discusiones constantes sobre qué se acordó, qué se entregó y cuánto falta por pagar.

## ¿Por qué creo que blockchain podría aportar?

> Hipótesis personal, no certeza, apoyada en al menos un criterio de la Sesión 1: partes que no confían entre sí comparten un registro, histórico inalterable, o eliminar un intermediario que concentra la confianza.

Mi hipótesis se apoya en dos criterios de la Sesión 1:

- **Criterio 1 – Partes que no confían entre sí necesitan un mismo registro:** cliente y maestro no se conocen, pero los dos necesitan ponerse de acuerdo sobre qué se pactó, qué etapa se entregó y qué se pagó.
- **Criterio 3 – Intermediario que concentra la confianza:** la póliza o la fiducia existen solo para garantizar que el dinero se entregue cuando se cumpla lo pactado; para una obra pequeña ese intermediario es inaccesible, así que hoy simplemente no existe.

Cómo lo imagino: usar el concepto de **pago condicionado** visto en la Sesión 2. El cliente deposita el dinero de cada etapa (o de toda la obra) en un contrato en Soroban, en una moneda estable. El dinero queda retenido y se libera al maestro cuando se confirma cada hito (demolición, instalación, acabados). En la red solo iría la huella (hash) de la evidencia del avance, como fotos o el acta de entrega; los archivos quedan fuera de la red. Si hay desacuerdo, un tercero elegido por ambos al inicio decide a quién se libera.

Lo que cambiaría para el usuario: la familia ya no entrega su dinero a ciegas, porque solo sale cuando la etapa se cumple; y el maestro puede ver, antes de empezar, que el dinero de su trabajo ya está depositado y no depende de la buena voluntad del cliente.
