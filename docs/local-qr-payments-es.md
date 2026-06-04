# Pagos QR Locales

Paybrok soporta flujos de pago QR local cuando un usuario quiere pagar a un comercio o persona usando un metodo especifico de pais.

## Proposito

Muchos paises tienen sistemas QR o links de pago que no exponen todos los datos bancarios. Paybrok intenta detectar pais, metodo, monto, comercio, referencia o link del proveedor cuando sea posible.

## Datos Que Puede Usar

Paybrok puede trabajar con:

- Links de pago.
- Referencias de comercio.
- Montos.
- Codigos de pais.
- Nombres de metodo.
- Contenido original del QR.

## Ejemplos De Metodos

La disponibilidad depende de configuracion y proveedores. Paybrok puede soportar flujos relacionados con:

- DeUna.
- Nequi.
- Bancolombia.
- Daviplata.
- Wompi.
- Mercado Pago.
- Transfiya.
- Pago Movil.
- CoDi/SPEI.
- QR Simple.

## Limitacion Importante

Algunos QR solo incluyen un link propietario. Si el link no expone datos bancarios, Paybrok no puede inventarlos. En ese caso conserva el link o referencia y lo comparte con proveedores compatibles para completar el pago local desde la app correspondiente.

