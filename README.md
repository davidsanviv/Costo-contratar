# Calculadora de costo de contratar (PyMEs de 20 a 200 personas, Latinoamérica)

App web instalable de solo consulta. Toda la calculadora (interfaz, cálculo y supuestos) está en un solo archivo (`index.html`). No guarda ni envía datos, no usa analítica ni recursos de terceros.

Los resultados son estimaciones con fines ilustrativos. Cada supuesto indica su nivel de fuente (con fuente, fuente débil, estimado o sin dato).

## Actualizar supuestos
Los supuestos de cada país están en el objeto `C` al inicio del script de `index.html`.

## Probar en local
Abre `index.html` en el navegador; no necesita servidor.

## Archivos
- `index.html`: la calculadora completa.
- `manifest.webmanifest` e `icon*.png` / `icon.svg`: nombre e iconos para instalarla en el teléfono o la computadora.
- `sw.js`: permite abrirla sin conexión. Guarda en caché solo los archivos de la app, nunca lo que escribe el usuario; con conexión siempre sirve la versión publicada más reciente.

## Instalar
Requiere estar publicada en HTTPS. En Android y en computadora (Chrome, Edge): menú del navegador → «Instalar app». En iPhone y iPad (Safari): Compartir → «Agregar a inicio».

Abierta desde `file://` funciona como página normal, sin instalación ni modo sin conexión.
