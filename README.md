# Reserva Estratégica de Activos Digitales para Colombia

Propuesta ciudadana de política pública: convertir parte del patrimonio de extinción de dominio
que administra la SAE (Sociedad de Activos Especiales) en una reserva soberana de activos
digitales bajo custodia fría multifirma del Estado — sin gasto público nuevo ni impuestos nuevos.

**Sitio en vivo:** [reserva-bitcoin-colombia.vercel.app](https://reserva-bitcoin-colombia.vercel.app)

---

## Qué contiene el documento

Once secciones, de la 00 a la 10:

| # | Sección | Contenido |
|---|---|---|
| 00 | El resumen | La propuesta completa en una pantalla |
| 01 | El problema | Qué cuesta hoy administrar los bienes incautados |
| 02 | La política monetaria | Limitancia electrónica y halving: por qué la escasez es predecible |
| 03 | La prueba retrospectiva | Simulador DCA con precios históricos reales por cuatrienio presidencial |
| 04 | La solución | Simulador del ciclo 2026–2030, con el halving de abril de 2028 |
| 05 | El precedente internacional | EE. UU., China, Reino Unido, Ucrania, Bután, Brasil y El Salvador |
| 06 | El contexto global | El Unified Ledger del BIS y la tokenización de activos |
| 07 | El activo | Por qué Bitcoin es el núcleo de la reserva |
| 08 | Riesgos y salvaguardas | Seis riesgos y la salvaguarda de diseño de cada uno |
| 09 | La ruta | De directiva administrativa a política de Estado, con fechas |
| 10 | El pedido | Tres decisiones de costo cero |

## Los dos simuladores

**Retrospectiva (sección 03)** — toma precios históricos diarios reales de Bitcoin y simula una
compra diaria durante cada cuatrienio presidencial. Aplica límites de absorción de mercado
(0,25% de la capitalización diaria, tenencia máxima del 4% de la oferta circulante) para que los
periodos tempranos sean materialmente realistas.

**Ciclo del mandato (sección 04)** — modela una trayectoria de precio para 2026–2030 con piso,
halving y techo editables, y simula la acumulación por compra diaria (DCA). Es una hipótesis de
trabajo, no un pronóstico.

Ambos son editables: cambia los supuestos y los resultados se recalculan.

## Qué NO propone

- No propone comprar con dinero del presupuesto: redirige recaudo ya existente de los remates
- No toca las reservas internacionales que administra el Banco de la República
- No incluye rendimientos DeFi en la fase inicial — se difieren a una fase posterior sujeta a
  validación de la mesa técnica (ver sección 08)

## Detalles técnicos

Sitio estático autocontenido: un solo `index.html`, sin dependencias ni proceso de build.
Precio de BTC y TRM en vivo vía CoinGecko, con valores de respaldo si la API no responde.
Gráficos en Canvas 2D y SVG inline.

```
index.html                  el documento completo
activos-invertibles.jpg      infografía de activos invertibles globales
andres-guzman.jpg            foto del bloque de liderazgo
```

## Registro

Obra registrada ante la Dirección Nacional de Derecho de Autor — radicado **1-2026-142867**.

## Contacto

Andrés Guzmán · [LinkedIn](https://www.linkedin.com/in/andrescrypto)

---

*Ejercicio ciudadano de análisis y simulación de política pública. Los cálculos son simulaciones
editables, no proyecciones ni asesoría financiera.*
