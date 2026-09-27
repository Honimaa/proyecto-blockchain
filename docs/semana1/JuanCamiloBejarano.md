# Propuesta individual

**Nombre:** Juan Camilo Bejarano Chacon

**Usuario de GitHub:** Honimaa

---

## El problema

> El problema en una sola frase, sin mencionar blockchain.

Una persona que junta plata con otras en una cadena de ahorro colectivo, ya sea para repartir a fin de año, para recibir el pozo por turnos o para pagar una meta común como un viaje con amigos, no tiene cómo comprobar que su aporte sigue ahí y depende por completo de que quien guarda la plata no la gaste, no la use para otra cosa o no desaparezca.

## ¿Quién lo sufre?

> Quién tiene el problema y en qué situación lo vive.

La sufre quien aporta a una cadena de ahorro colectivo. Es una persona de ingresos bajos o medios, estudiante, empleado o independiente, que ahorra en grupo porque solo no lo logra. En la cadena encuentra disciplina, cero trámites y un compromiso con gente conocida.

Estas cadenas toman varias formas en Colombia:

- **Ahorro anual o natillera:** cada miembro aporta una cuota fija todo el año y en diciembre se reparte lo ahorrado más los intereses de préstamos internos.
- **Cadena por turnos:** cada periodo todos aportan y uno de los miembros recibe el pozo completo, hasta que a todos les llega su turno. En Bogotá se le conoce simplemente como "cadena".
- **Ahorro con un objetivo común:** un grupo de amigos, un curso de colegio o universidad o una familia junta plata durante meses para un viaje, una fiesta de grado, un regalo o un evento.

En todas pasa lo mismo: alguien del grupo recibe los aportes en efectivo o en su cuenta personal, y el resto solo sabe lo que esa persona le cuenta. El problema se descubre tarde: cuando llega el turno, la fecha del reparto o el momento de pagar el viaje y la plata no está completa, se usó para otra cosa o quien la tenía ya no responde. En las cadenas por turnos aparece un riesgo más: quien ya recibió el pozo deja de aportar.

## ¿Cómo se resuelve hoy y qué cuesta?

> Cómo lo resuelven hoy las personas afectadas y qué les cuesta en dinero, tiempo o esfuerzo.

Hoy se resuelve solo con confianza personal:

- Una persona (tesorero, organizador o "el que maneja la cadena") guarda el dinero en efectivo o en su propia cuenta de banco o billetera digital, mezclado con su plata personal.
- El control de aportes se lleva en un cuaderno, una hoja de Excel o fotos de comprobantes en el grupo de WhatsApp, y el organizador puede corregirlo cuando quiera.
- Las decisiones sobre la plata (préstamos internos, orden de los turnos, pagos a la agencia de viaje o al hotel, devoluciones a quien se retira) las toma el organizador, muchas veces sin que el resto sepa exactamente qué se hizo.

Lo que cuesta:

- **Dinero:** si el organizador se va, gasta la plata o un miembro deja de aportar después de recibir su turno, los demás pueden perder todo lo aportado sin una forma práctica de recuperarlo.
- **Tiempo y esfuerzo:** el organizador dedica horas a cobrar, cuadrar cuentas y responder dudas; los demás, a reclamar cuando algo no cuadra. Las diferencias terminan en peleas entre amigos, compañeros o familiares.
- **Alternativa formal:** una cuenta de ahorro programado o un fondo formal quedan a nombre de una sola persona, así que no resuelven el problema de confianza. Constituir una cooperativa o un fondo de empleados es desproporcionado para un grupo pequeño o para una meta de pocos meses.

## ¿Por qué creo que blockchain podría aportar?

> Hipótesis personal, no certeza, apoyada en al menos un criterio de la Sesión 1: partes que no confían entre sí comparten un registro, histórico inalterable, o eliminar un intermediario que concentra la confianza.

Mi hipótesis se apoya en dos criterios de la Sesión 1:

- **Criterio 3 – Intermediario que concentra la confianza:** el organizador existe solo porque alguien tiene que guardar la plata y llevar la cuenta. Si las reglas de la cadena quedan en un contrato inteligente, el dinero ya no depende de que una sola persona se comporte bien. Esas reglas son cuánto aporta cada uno, cuándo y a quién se entrega, en qué se puede gastar y qué pasa si alguien se retira.
- **Criterio 2 – Histórico que no puede alterarse:** cada aporte quedaría anotado en un registro que ni siquiera quien organiza el grupo puede editar, y que cualquier miembro puede revisar en cualquier momento.

Cómo lo imagino: los aportes se hacen en una moneda estable (por ejemplo USDC u otra ligada al peso, emitida en Stellar) hacia una cuenta controlada por un contrato en Soroban. Según el tipo de cadena, el contrato aplica una regla distinta de **pago condicionado**:

- **Ahorro anual:** el dinero solo sale en la fecha de reparto pactada. Un préstamo interno necesita la aprobación de la mayoría (multifirma).
- **Cadena por turnos:** el pozo se entrega automáticamente a quien le corresponde según el orden acordado, y queda a la vista quién está al día y quién no.
- **Objetivo común:** el dinero solo puede salir hacia el pago de la meta (por ejemplo, la agencia o el hotel del viaje) o con la aprobación de la mayoría. Si la meta no se cumple, cada uno recupera lo que aportó.

Los nombres y teléfonos de los miembros no irían en la red, solo los aportes y las reglas.

Lo que cambiaría para quien aporta: en vez de esperar al final para saber si su plata está, podría verificar en cualquier momento cuánto ha aportado y cuánto hay en total, con la tranquilidad de que nadie puede usar el dinero por su cuenta ni para algo distinto a lo que el grupo acordó.
