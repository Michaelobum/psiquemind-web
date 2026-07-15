# 07 — TECHNICAL

Arquitectura y decisiones técnicas.

## Stack
## Arquitectura
## Integraciones

### Analítica — Google Analytics 4

- Script `gtag.js` cargado async en el `<head>` de `public/index.html`.
- ID de medición: `G-194N0YPB5L`.
- Evento personalizado `whatsapp_click` con parámetro `cta_location` en cada link a WhatsApp (`data-cta`: `nav`, `hero`, `cta_final`, `footer`, `flotante`).
- La medición mejorada de GA4 (activada por defecto en la propiedad) cubre page views, scroll al 90% y clicks salientes.
## Deploy / infraestructura
