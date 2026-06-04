# Seguridad

Paybrok esta disenado con enfoque de seguridad alrededor de custodia de wallet, pagos protegidos, riesgo de proveedores y documentacion de disputas.

## Principios

- Los usuarios controlan su wallet.
- Paybrok no guarda seed phrases en servidores de Paybrok.
- Las palabras de recuperacion deben protegerse por el usuario.
- Las acciones sensibles requieren desbloqueo local cuando aplica.
- El escrow ayuda a reducir riesgo entre contrapartes.
- La revision de proveedores y evidencia de disputas reduce riesgo de pagos informales.

## Reglas Para Usuarios

Los usuarios nunca deben compartir:

- 12 palabras de recuperacion.
- Clave secreta Stellar.
- Contrasena web.
- PIN.
- Credenciales privadas de wallet.

Paybrok no pedira estos datos por soporte, Telegram, email, telefono, redes sociales, chat de proveedor ni canales informales.

## Proteccion De Wallet Web

La wallet web usa una boveda local cifrada. El material sensible se cifra en el navegador con una contrasena creada por el usuario.

Importante:

- Si la boveda cifrada sigue existiendo, Paybrok puede restaurar la sesion local.
- Si el navegador borra todo el almacenamiento, el usuario debe restaurar con sus palabras.
- Navegadores diferentes pueden no compartir la misma boveda.
- La contrasena local no es la frase de recuperacion.

## Desbloqueo Local y Fuerza Bruta

Paybrok incluye protecciones de desbloqueo local para acciones sensibles. Estas protecciones buscan dificultar intentos repetidos y proteger al usuario cuando hay demasiados intentos incorrectos.

Conceptos publicos:

- Flujos sensibles requieren confirmacion local, contrasena o PIN segun plataforma y modo de wallet.
- Intentos incorrectos repetidos pueden activar comportamiento protector.
- El usuario debe usar contrasenas fuertes y guardar sus palabras offline.

Esta seccion describe el comportamiento publico, no detalles internos de implementacion.

## Diferenciadores De Seguridad

La ventaja de seguridad de Paybrok no es un solo control aislado. Combina varias capas para apoyar pagos reales:

- Modelo de wallet no custodial.
- Boveda web local cifrada.
- Desbloqueo local para acciones sensibles.
- Proteccion contra intentos repetidos.
- Escrow para P2P, remesas y pagos por servicios.
- Evidencia y revision de disputas.
- Revision de proveedores.
- Controles de sanciones y riesgo.
- Politica publica AML/CTF.

Estas capas ayudan a que Paybrok soporte pagos en dolares digitales sin depender solo de confianza ciega entre usuarios.

## Seguridad De Escrow

El escrow ayuda a reducir riesgo evitando liberar fondos antes de que se complete lo acordado.

Puede aplicar a:

- Ordenes P2P.
- Flujos de proveedores locales.
- Remesas.
- Pagos protegidos por servicios.
- Liberaciones por hitos.
- Escrow Soroban donde este configurado.

## Riesgo, Sanciones y Proveedores

Paybrok aplica controles operativos para apoyar uso mas seguro:

- Revision de proveedores.
- Restricciones por pais o metodo.
- Monitoreo basado en riesgo.
- Screening de sanciones.
- Deteccion de abuso.
- Documentacion de disputas.
- Restriccion de actividad sospechosa.
- Revision manual cuando corresponda.

Estos controles ayudan, pero no garantizan que toda contraparte sea segura ni que toda orden termine exitosamente.
