# Pagos Protegidos Por Servicios

Paybrok puede usarse para pagar servicios con proteccion por escrow y liberaciones por hitos.

## Ejemplo: Arquitectura Por 100 USDC

Un cliente quiere contratar a un arquitecto por un proyecto de 100 USDC. En vez de enviar todo por adelantado, crea un pago protegido por servicio.

Ejemplo de hitos:

- 30 USDC por concepto o boceto inicial.
- 40 USDC por borrador revisado.
- 30 USDC por entrega final.

## Roles

- Cliente: persona que paga el servicio.
- Prestador del servicio: profesional que entrega el trabajo, como arquitecto, disenador, contratista, consultor o tecnico.
- Paybrok: plataforma que estructura la orden y el flujo de escrow.

## Flujo

1. Cualquiera abre Pago protegido y elige Quiero cobrar si entregara o Quiero pagar si financiara.
2. Define contraparte, entregable, evidencia, minimo 50 USDC, entre uno y seis hitos, fechas, revision y penalidad opcional.
3. Crea el enlace y usa Compartir o Copiar enlace.
4. La contraparte revisa y acepta.
5. Quien paga firma Proteger fondos. Crear o aceptar el enlace no bloquea dinero.
6. Ambas partes comprueban Fondos protegidos en Mis acuerdos.
7. El prestador entrega cada hito y adjunta evidencia.
8. El cliente revisa y libera en orden. Una liberacion confirmada es final.
9. Ante incumplimiento, cualquiera abre disputa antes de liberar.

## Reglas Del Acuerdo

Los acuerdos de servicio pueden incluir reglas predefinidas visibles antes de aceptar:

- Fecha limite de entrega.
- Periodo de revision o inspeccion.
- Autoliberacion si el cliente no responde dentro del periodo acordado.
- Opciones de penalidad por retraso.
- Montos o porcentajes por hito.

La penalidad puede expresarse en porcentaje o monto fijo. Es una clausula, no un descuento unilateral automatico: se aplica por acuerdo o resolucion de disputa.

## Hitos

Los hitos permiten liberar dinero por etapas en vez de pagar todo de una vez. Un proyecto de 900 USDC en 90 dias, por ejemplo, puede dividirse en tres hitos de 300 USDC. Paybrok mantiene visible la estructura para que ambas partes vean que esta bloqueado, que se libero y que queda pendiente.

## Buen Acuerdo De Servicio

Una orden debe definir:

- Que se debe entregar.
- Formato de entrega.
- Plazos.
- Periodo de revision.
- Regla de retraso, si se usa.
- Numero de revisiones.
- Hitos de pago.
- Que cuenta como entrega valida.
- Como se documentara comunicacion y evidencia.

## Limite

Paybrok no reemplaza un contrato legal formal para proyectos complejos. Para trabajos de alto valor, los usuarios deben tener tambien un acuerdo escrito fuera de la app.

