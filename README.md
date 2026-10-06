# Envío de OC · Project Agenda

Maqueta interactiva del envío automático de órdenes de compra (OC) al proveedor desde Project Agenda.

Es un prototipo en un solo archivo (`index.html`): no tiene backend, base de datos, SAP ni envío real de correos, y todos los datos son de ejemplo.

## Cómo verla

Abra `index.html` en el navegador (doble clic). No requiere instalación.

## Qué muestra

- **Suppliers:** proveedores y sus contactos (ventana *Contact Information*).
- **Purchasing › Settings › Email Body:** asunto y cuerpo del correo por tipo de compra e idioma, con variables `{{…}}` y el condicional compartido por Delivery Location.
- **Purchasing › Settings › Monthly Closing Date:** fecha de cierre de cada mes, usada como fecha límite de recepción en el correo.
- **Requests → Purchase ID:**
  1. Número de OC por ítem (flecha en ACTION) y archivo de la OC en ORDERS.
  2. IN TRANSIT → *Select Purchase Order to Send*.
  3. *Send Purchase Order* (To, Cc, Subject, Message, Purchase Order).
  4. Confirmación y cambio de estado a In Transit.
