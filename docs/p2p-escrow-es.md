# P2P y Escrow

Paybrok Local es la capa P2P que conecta usuarios con proveedores aprobados para necesidades de pago local.

## Por Que Importa El Escrow

El escrow da a ambas partes un proceso de pago acordado: los fondos quedan bloqueados durante la entrega y se liberan conforme a las reglas aceptadas. Confirma el estado protegido antes de empezar y revisa la entrega antes de liberar.

## Flujo Basico

1. El usuario crea o toma una orden P2P.
2. La orden define monto, activo, pais, metodo y condiciones.
3. Los fondos se bloquean en escrow.
4. La contraparte completa la accion local acordada.
5. Los fondos se liberan cuando la orden se completa.
6. Si algo sale mal, se puede abrir disputa.

## Disputas

Una disputa debe incluir evidencia como:

- Capturas.
- Referencias de pago.
- Conversaciones.
- Confirmaciones bancarias o de pago.
- Prueba de entrega.
- Hashes de transaccion.

Soporte Paybrok puede revisar evidencia y decidir si libera, reembolsa o mantiene la disputa abierta para mas informacion.

## Escrow Soroban

Donde este habilitado, Paybrok puede usar escrow Soroban para flujos on-chain mas transparentes. La disponibilidad depende del activo, configuracion y preparacion operativa.

## Disponibilidad Y Condiciones De Operación

- Una orden se concreta cuando un proveedor acepta su monto, método y condiciones con liquidez disponible.
- La disponibilidad depende de pais, metodo, limites, liquidez, compliance y riesgo.
- El escrow regula los fondos; verificar entregas, conservar evidencia y cumplir los requisitos aplicables sigue formando parte de cada operación. Consulta los [términos](https://paybrok.com/terms) y el [proceso de disputas](https://paybrok.com/disputes).

