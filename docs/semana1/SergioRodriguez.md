# Propuesta individual

**Nombre:** Sergio Rodriguez Castro

**Usuario de GitHub:** SergioRodrii

---

## El problema

> El problema en una sola frase, sin mencionar blockchain.

Un freelancer colombiano que trabaja para clientes en el exterior pierde parte de cada pago en comisiones y conversión, espera días para tener el dinero en pesos y, si trabaja sin una plataforma de por medio, corre el riesgo de que el cliente simplemente no le pague.

## ¿Quién lo sufre?

> Quién tiene el problema y en qué situación lo vive.

Lo sufre el trabajador independiente que presta servicios digitales desde Colombia a clientes de otros países: desarrolladores, diseñadores, traductores, editores de video, redactores. Cobra en dólares y vive en pesos.

La situación típica aparece en dos momentos:

1. **Antes de empezar:** con un cliente nuevo, contactado por redes o referidos, no sabe si al final le van a pagar. Pedir el 100 % por adelantado espanta al cliente; no pedir nada lo deja expuesto.
2. **Al cobrar:** cuando por fin le pagan, el dinero pasa por varias manos (plataforma de freelance, pasarela de pagos, banco colombiano) y lo que llega a su cuenta en pesos es menos de lo facturado y llega días después.

## ¿Cómo se resuelve hoy y qué cuesta?

> Cómo lo resuelven hoy las personas afectadas y qué les cuesta en dinero, tiempo o esfuerzo.

Hoy se resuelve de dos formas:

- **A través de plataformas de freelance:** la plataforma retiene el pago del cliente y lo libera cuando se aprueba la entrega. A cambio cobra una comisión sobre cada trabajo. Luego el freelancer retira a una pasarela de pagos internacional, y de ahí a su banco en Colombia.
- **Trabajando directo con el cliente:** se ahorra la comisión de la plataforma, pero asume todo el riesgo de impago y aun así depende de pasarelas o de transferencias internacionales por banca corresponsal para recibir el dinero.

Lo que cuesta:

- **Dinero:** cada capa cobra su parte (comisión de la plataforma, comisión de retiro, diferencial en la tasa de cambio y, en transferencias bancarias, cargos de bancos intermediarios). El monto exacto varía por proveedor y se validaría con casos reales en la Fase 2.
- **Tiempo:** entre la retención de la plataforma, el retiro y la acreditación en el banco local pueden pasar varios días hábiles.
- **Esfuerzo y riesgo:** perseguir a clientes que no pagan, sin herramientas reales para exigir el cobro a alguien que está en otro país.

## ¿Por qué creo que blockchain podría aportar?

> Hipótesis personal, no certeza, apoyada en al menos un criterio de la Sesión 1: partes que no confían entre sí comparten un registro, histórico inalterable, o eliminar un intermediario que concentra la confianza.

Mi hipótesis se apoya en dos criterios de la Sesión 1:

- **Criterio 1 – Partes que no confían entre sí necesitan un mismo registro:** freelancer y cliente están en países distintos, no se conocen y ninguno tiene un recurso práctico contra el otro. Ambos necesitan ver el mismo registro del acuerdo y del pago.
- **Criterio 3 – Intermediario que concentra la confianza:** la plataforma de freelance cobra, en buena parte, por hacer de garante: guardar el dinero del cliente hasta que se apruebe el trabajo.

Cómo lo imagino: el cliente deposita el pago en una moneda estable (por ejemplo USDC en Stellar) en un contrato en Soroban al aceptar la propuesta, como un **pago condicionado**. El freelancer ve que el dinero ya está bloqueado antes de empezar. Al entregar, el pago se libera cuando el cliente aprueba, o automáticamente si pasa un plazo acordado sin objeciones. Stellar está pensada para mover monedas entre países en segundos, y un ancla local podría convertir a pesos.

Lo que cambiaría para el freelancer: empezar a trabajar sabiendo que el dinero existe y está comprometido, recibirlo en segundos en lugar de días y con menos capas cobrando comisión entre el cliente y su bolsillo.
