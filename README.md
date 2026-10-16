# PreciosYa — versión de prueba

Prototipo para **recibir opiniones**. Compará precios de supermercados de **Salta** con datos abiertos de SEPA: cargá tu
lista de compras del mes y la app te dice en qué súper conviene comprar y cuánto ahorrás.

👉 **Probala acá:** https://antonioyurquina.github.io/precios-sepa-demo/

## Qué es esta versión

- Es una **captura congelada del 15/10/2026**, con datos reales de 6 cadenas y 43 sucursales de Salta (39.930 productos).
  Los precios **no se actualizan**.
- No hay servidor: la búsqueda y la comparación corren en tu navegador. La búsqueda por texto es una versión simplificada
  y la lista que armes se guarda solo en tu navegador.
- La sección de administración no está disponible acá.
- Son **precios de góndola** que las cadenas informan a SEPA: la tienda online puede mostrar otros. Confirmá el total antes de comprar.
- «PreciosYa» es un nombre provisorio, sin vínculo ni aval del Gobierno Nacional ni de las cadenas.

## Cómo probarla (2 minutos)

1. Entrá a **Mi lista** y tocá **«Probar con una lista de ejemplo»** (14 productos), o armá la tuya buscando productos.
2. Tocá **Comparar**: te muestra en qué súper conviene comprar todo junto y una **mejor combinación** repartiendo la compra
   entre cadenas, con las promociones y su vencimiento.
3. Probá el interruptor **«Incluir promociones»**.

## Dejar una opinión

[Dejar una opinión](https://github.com/AntonioYurquina/precios-sepa-demo/issues/new?template=opinion.yml) (necesita una cuenta de GitHub
y tu comentario queda **público**: no escribas datos personales). También podés responder por el mismo medio por el que te llegó el enlace.

## Fuente de los datos

Precios Claros – Base SEPA, Secretaría de Comercio ([datos.produccion.gob.ar](https://datos.produccion.gob.ar/dataset/sepa-precios)),
licencia [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.es). Los datos fueron procesados y modificados (normalizados,
filtrados por provincia y recalculados). Este repositorio contiene solo el sitio ya compilado; el código del proyecto es privado por ahora.
