# Capacidades de Paybrok

Este documento resume las capacidades publicas de Paybrok sin exponer codigo fuente, infraestructura privada, secretos, llaves ni detalles internos de seguridad.

## 1. Wallet No Custodial

Paybrok permite crear o restaurar una wallet Stellar.

Capacidades:

- Crear wallet.
- Restaurar wallet con 12 palabras o clave secreta Stellar.
- Ver balances.
- Ver direccion publica.
- Enviar activos compatibles.
- Recibir activos compatibles.
- Escanear codigos QR.
- Generar QR y enlaces de pago.
- Ver historial de movimientos.
- Mantener las credenciales de wallet bajo control local del usuario.

Principio de seguridad:

Paybrok no pide ni guarda la seed phrase del usuario en servidores de Paybrok.

## 2. Wallet Web

Paybrok incluye modo wallet web.

Capacidades:

- Crear wallet web Paybrok.
- Cifrar la seed localmente en el navegador con una contrasena creada por el usuario.
- Desbloquear localmente operaciones sensibles.
- Recuperar la sesion si se pierde metadata del navegador pero la boveda cifrada sigue existiendo.
- Usar Freighter como firmador externo avanzado cuando este disponible.

Limitaciones:

- Si el navegador borra todo el almacenamiento del sitio, incluyendo la boveda cifrada, el usuario debe restaurar con sus 12 palabras.
- Navegadores diferentes en el mismo dispositivo pueden no compartir la misma boveda local.

## 3. QR y Enlaces de Pago

Paybrok permite cobrar y pagar usando QR.

Capacidades:

- Generar QR de cobro.
- Generar enlaces de pago.
- Escanear QR.
- Detectar informacion de pago cuando este disponible.
- Procesar QR locales cuando incluyan enlace, comercio, monto, referencia o metodo.

## 4. Paybrok Local P2P

Paybrok Local conecta usuarios que necesitan dolares digitales o pagos locales con proveedores aprobados.

Capacidades:

- Crear ordenes de compra/venta local.
- Filtrar por pais, activo, monto y metodo.
- Conectar con proveedores.
- Usar escrow.
- Seguir estado de la orden.
- Abrir disputa si hace falta.
- Notificar eventos importantes.

## 5. Escrow

El escrow reduce el riesgo entre desconocidos.

Capacidades:

- Bloquear fondos durante una orden.
- Liberar fondos cuando se cumple lo acordado.
- Mantener fondos bloqueados durante una disputa.
- Soportar pagos parciales o por hitos donde este habilitado.
- Usar escrow Soroban donde este configurado.

## 6. Pagos Protegidos por Servicios

Paybrok puede usarse para pagar servicios por hitos.

Ejemplos:

- Arquitectura.
- Diseno.
- Reparaciones.
- Construccion.
- Consultoria.
- Servicios tecnologicos.

Capacidades:

- Definir categoria del servicio.
- Definir titulo y detalle.
- Definir monto total.
- Dividir el pago por hitos.
- Bloquear fondos en escrow.
- Liberar fondos segun entregas.
- Abrir disputa con evidencia si algo sale mal.

## 7. Remesas

Paybrok soporta flujos tipo remesa mediante proveedores o puentes locales aprobados.

Capacidades:

- Elegir ruta de origen y destino.
- Elegir activo y monto.
- Elegir metodo de entrega cuando exista.
- Bloquear fondos en escrow.
- Permitir entrega local por proveedor.
- Liberar o disputar segun entrega.

## 8. Proveedores y Comercios

Los proveedores aprobados pueden ayudar con liquidez local, pagos locales o servicios.

Capacidades:

- Solicitud y revision de proveedor.
- Perfil y datos operativos.
- Metodos de pago locales.
- Liquidez por pais y metodo.
- Reputacion e historial operativo.
- Panel de proveedor donde este habilitado.

## 9. Notificaciones

Paybrok puede notificar eventos importantes.

Capacidades:

- Actualizaciones de ordenes.
- Eventos de disputa.
- Cambios de estado.
- Avisos de wallet.
- Registro de dispositivo web.
- Push movil donde este disponible.

## 10. Compliance y Seguridad

Paybrok mantiene controles publicos y operativos para uso responsable.

Capacidades:

- Terminos de Servicio.
- Politica de Privacidad.
- Politica AML/CTF.
- Aviso de arbitraje.
- Controles de sanciones y riesgo.
- Monitoreo antiabuso.
- Documentacion de disputas.
- Revision de proveedores.
- Flujos de soporte/admin.

