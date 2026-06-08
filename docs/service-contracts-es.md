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

1. El cliente entra a Pagar un servicio.
2. Elige categoria como Arquitectura.
3. Define monto, activo, titulo, detalles, hitos y reglas del acuerdo.
4. Un prestador acepta o se conecta segun disponibilidad.
5. Los fondos se bloquean en escrow.
6. El prestador entrega cada hito y marca el servicio como listo.
7. El cliente revisa la entrega y libera el pago correspondiente si esta conforme.
8. Si el trabajo no se entrega, el cliente abre disputa con evidencia.

## Reglas Del Acuerdo

Los acuerdos de servicio pueden incluir reglas predefinidas visibles antes de aceptar:

- Fecha limite de entrega.
- Periodo de revision o inspeccion.
- Autoliberacion si el cliente no responde dentro del periodo acordado.
- Opciones de penalidad por retraso.
- Montos o porcentajes por hito.

Las penalidades se acuerdan antes de aceptar y no deben superar el valor del hito donde aplican. Asi el acuerdo queda claro y se evita que una penalidad sea mayor que el pago revisado.

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

