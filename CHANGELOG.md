# Changelog

## 2.0.1 (2026-11)
- Los precios de terceros que estaban sin impuesto ahora lo incluyen, igual que Colombia: portales de México (IVA 16%), Chile (IVA 19%), Perú (IGV 18%) y Honduras (ISV 15%), y examen médico de Perú. El total de México, nivel Profesional, pasa de $33,385 a $33,859.

## 2.0.0 (2026-11)
- La calculadora pasa a ser una app instalable que abre sin conexión (`manifest.webmanifest`, `sw.js`, iconos).
- Los supuestos se integran en `index.html` (objeto `C`); se elimina `data/paises.json`.
- Sin fuentes externas: la página ya no hace ninguna solicitud a otros dominios.
- Curva de aprendizaje: campo opcional de valor mensual generado, mostrado aparte del total.

## 1.1.2 (2026-11)
- Jefe directo: el salario por defecto pasa del nivel del propio puesto al nivel inmediato superior (en Gerente/Dir., el mismo nivel). El total sube entre 2 y 5% según el país.

## 1.1.1 (2026-11)
- Colombia: el multiplicador de carga social excluye vacaciones, igual que los demás países (1,35 con exoneración de la Ley 1607; 1,48 sin ella).

## 1.1.0 (2026-11)
- Nuevos países: Perú, Costa Rica, Panamá, Ecuador y Honduras.
- Perú usa el régimen general; en pequeña empresa y microempresa la carga social es menor.
- Ecuador y Honduras: el multiplicador de carga social cambia por nivel (montos fijos y techos de cotización).
- Chile: sueldo mínimo de $553.553 y precio de Trabajando.com (fuente débil).
- Argentina: carga social con seguro de vida obligatorio; la ART queda fuera.

## 1.0.2 (2026-11)
- La página ya no se indexa en buscadores (`noindex`).

## 1.0.1 (2026-10)
- Colombia: Gerente en job boards pasa de $450,000 a $260,000 COP (Computrabajo Premium con IVA, igual que Senior).

## 1.0.0 (2026-10)
- Primera versión: México, Colombia, Chile, Argentina y Guatemala.
- Rampa de productividad separada del costo total.
- Selector de canal (agencia / portales / ambos).
- Supuestos separados en `data/paises.json`.
