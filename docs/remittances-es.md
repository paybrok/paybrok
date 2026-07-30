# Remesas

Los flujos de remesa de Paybrok estan pensados para usuarios que quieren enviar valor entre paises usando dolares digitales y proveedores locales.

## Flujo

1. El remitente indica origen, destino, monto, activo y wallet del beneficiario.
2. La solicitud aun no retiene fondos.
3. El beneficiario elige transferencia bancaria o efectivo y un Punto disponible.
4. El Punto cotiza; las partes revisan tasa, monto local, costos y vigencia.
5. El remitente firma Proteger fondos.
6. El Punto transfiere o entrega efectivo y adjunta comprobante.
7. El beneficiario confirma solo despues de recibir el total.
8. El Punto cobra cuando el contrato lo permite; versiones anteriores pueden requerir liberacion del remitente.
9. Si falla la entrega, se reporta desde Mis remesas con evidencia y se resuelve mediante acuerdo, reembolso o disputa.

## Ejemplos

- Enviar dolares digitales a alguien que necesita moneda local.
- Pagar a un destinatario por banco, wallet local o metodo local.
- Usar proveedores aprobados en vez de enviar a ciegas.

## Limitaciones

- La disponibilidad depende de pais, ruta, liquidez, metodo, compliance y limites.
- Paybrok no garantiza que una ruta este siempre disponible.
- Antes de proteger no hay nada que reembolsar. La recuperacion tecnica solo busca bloqueos antiguos no registrados.

