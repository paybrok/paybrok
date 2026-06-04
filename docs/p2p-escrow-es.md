# P2P y Escrow

Paybrok Local es la capa P2P que conecta usuarios con proveedores aprobados para necesidades de pago local.

## Por Que Importa El Escrow

Sin escrow, un usuario puede depender demasiado de confiar en una contraparte desconocida. El escrow reduce ese riesgo bloqueando fondos hasta que se cumpla la accion esperada.

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

## Limitaciones

- Paybrok no garantiza que toda orden encuentre proveedor.
- La disponibilidad depende de pais, metodo, limites, liquidez, compliance y riesgo.
- El escrow reduce riesgo, pero no elimina todo riesgo operativo, fraude o riesgo legal.

