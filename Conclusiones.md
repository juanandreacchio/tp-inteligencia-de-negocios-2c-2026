# Vestir S.A. — Conclusiones y decisiones de modelado

Trabajo Práctico Power BI · Inteligencia de Negocios · UTN FRBA · 2C 2026

Las cifras corresponden a los ejercicios fiscales 2024/25 y 2025/26 (julio a junio), en pesos argentinos, considerando solo ventas efectivas (sin pedidos cancelados ni devueltos).

## Resumen

| Indicador | Valor |
|---|---|
| Venta neta (dos ejercicios) | $ 3.455 M |
| Objetivo de venta | $ 3.424 M |
| Cumplimiento del objetivo | 100,9 % |
| Crecimiento 2025/26 vs 2024/25 (nominal) | 33,9 % |
| Margen bruto | 51,9 % |
| Clientes activos | 1.736 |
| Clientes nuevos | 690 |
| Ticket promedio | $ 178.746 |
| Rating de satisfacción (1 a 5) | 4,05 |
| Tasa de devolución | 4,7 % |

## Conclusiones

### Ventas y objetivos

#### 1. La empresa cumple su objetivo, pero con poco margen

En los dos ejercicios la venta neta fue de $ 3.455 M contra un objetivo de $ 3.424 M: un cumplimiento del 100,9 %, $ 31,4 M por encima. Por ejercicio, el cumplimiento fue de 101,3 % en 2024/25 y de 100,6 % en 2025/26.

Ese resultado total esconde un patrón que se repite mes a mes: en la primera mitad de cada ejercicio la venta supera holgadamente al objetivo (alrededor del 107 % entre julio y octubre de ambos ejercicios), y en la segunda mitad queda por debajo (entre 94 % y 96 % de marzo a junio). El exceso del segundo semestre calendario compensa el faltante del primero.

**Recomendación:** revisar cómo se reparte el objetivo anual entre los meses: hoy es poco exigente de julio a diciembre y demasiado exigente de marzo a junio. También conviene agregar una meta de crecimiento sobre el ejercicio anterior.

#### 2. Crecimiento fuerte sin perder rentabilidad

El ejercicio 2025/26 vendió un 33,9 % más que el 2024/25: $ 1.978 M contra $ 1.477 M. El margen bruto se mantuvo estable (51,9 % en 2024/25 y 51,8 % en 2025/26), de modo que el crecimiento no se apoyó en descuentos que erosionen la rentabilidad.

Dos aclaraciones para leer bien ese crecimiento:

- Es un crecimiento **nominal**: las listas de precios se actualizan todos los meses por inflación, así que el crecimiento en volumen real es menor.
- Cerca del 40 % del aumento ($ 197 M de $ 501 M) lo explican las dos sucursales abiertas en 2025, Alto Comahue y Paseo Aldrey. Las sucursales que ya operaban en el ejercicio 2024/25 crecieron un 21 %.

#### 3. Estacionalidad marcada

La venta tiene picos en diciembre y en mayo-junio, y valles en enero y febrero, que se repiten en ambos ejercicios. Junio de 2026 fue el mejor mes de la serie ($ 256 M) y febrero de 2025 el más flojo ($ 87 M). Agosto fue un mes bajo en 2024/25, pero no en 2025/26.

**Recomendación:** planificar stock, dotación en tiendas y campañas según este calendario, y repartir el objetivo anual por mes en proporción a la estacionalidad.

#### 4. La tienda física lidera, pero lo digital ya representa el 45 %

| Canal | Venta neta | Participación |
|---|---|---|
| Tienda Física | $ 1.907 M | 55 % |
| E-Commerce | $ 1.105 M | 32 % |
| App Móvil | $ 443 M | 13 % |

Entre las zonas comerciales, Digital es la de mayor venta ($ 1.548 M), seguida por AMBA ($ 885 M); Centro ($ 584 M) e Interior ($ 438 M) quedan bastante atrás. Cada zona comercial corresponde al equipo de un gerente zonal, por lo que la comparación por zona coincide con la de gerentes de la conclusión 9.

**Recomendación:** la App Móvil es el canal con más espacio para crecer, con beneficios exclusivos y notificaciones de campañas estacionales.

#### 5. Calzado e Indumentaria explican el 94 % de la venta

| Categoría | Venta neta | Participación |
|---|---|---|
| Calzado | $ 1.658 M | 48 % |
| Indumentaria | $ 1.602 M | 46 % |
| Accesorios | $ 195 M | 6 % |

**Recomendación:** usar Accesorios como venta cruzada (combos en caja, recomendaciones en e-commerce y app) para subir el ticket promedio, hoy de $ 178.746.

### Clientes

#### 6. Muchos clientes Persona, pocos clientes corporativos que pesan mucho

| Segmento | Venta neta | Participación |
|---|---|---|
| Persona | $ 2.150 M | 62 % |
| Corporativo | $ 1.305 M | 38 % |

Los 10 clientes con mayor venta son todos corporativos y suman $ 631 M: el 18 % de la venta total y casi la mitad (48 %) de la venta corporativa. El principal, Constructora Aconcagua S.A., compró $ 119 M. Los clientes se concentran en Buenos Aires, y en los dos ejercicios se sumaron 690 clientes nuevos.

**Recomendación:** cuidar la relación con las grandes cuentas corporativas (atención dedicada, condiciones comerciales), porque perder una sola tendría un impacto visible en la venta. En paralelo, ampliar la base corporativa para reducir esa dependencia.

#### 7. Se paga sobre todo con tarjeta de crédito, pero casi siempre en una cuota

| Medio de pago | Venta neta | Participación |
|---|---|---|
| Tarjeta de crédito | $ 1.182 M | 34 % |
| Transferencia bancaria | $ 988 M | 29 % |
| Tarjeta de débito | $ 558 M | 16 % |
| Billetera virtual (QR) | $ 346 M | 10 % |
| E-Cheq | $ 200 M | 6 % |
| Efectivo | $ 181 M | 5 % |

El 82 % de la venta ($ 2.839 M) se cobra en una sola cuota. Las ventas en 3, 6 y 12 cuotas suman solo el 18 %. El efectivo es marginal y los medios digitales (transferencia, QR, E-Cheq) ya superan a la tarjeta de débito.

**Recomendación:** la financiación en cuotas tiene poco uso. Antes de sostener su costo financiero, conviene evaluar si promoverla en temporada alta (diciembre, junio) y en productos de mayor precio aumenta el ticket.

#### 8. Clientes satisfechos, con el calzado como foco de devoluciones

El rating promedio es de 4,05 sobre 5 y la tasa de devolución, del 4,7 %. Las cuatro subcategorías de calzado (Zapatillas, Zapatos, Sandalias y Ojotas, y Botas y Botinetas) tienen las tasas de devolución más altas, entre 5,1 % y 6,6 %; el calzado en conjunto se devuelve un 6,1 %. Gorras es la de menor devolución (3,0 %), seguida por Buzos, Medias, Marroquinería y Camperas, cerca del 3,7 %.

**Recomendación:** el calzado es la categoría que más vende y la que más se devuelve, probablemente por talle. Una guía de talles más clara en e-commerce y app, y la prueba en tienda, reducirían devoluciones y costos logísticos.

### Equipo comercial

#### 9. Desempeño comercial parejo entre gerentes, con un equipo a seguir

| Gerente (zona) | Venta neta | Cumplimiento | 2024/25 | 2025/26 |
|---|---|---|---|---|
| Agustina Sol Gómez (Digital) | $ 1.548 M | 101,4 % | 101,4 % | 101,4 % |
| Facundo Navarro (AMBA) | $ 885 M | 100,3 % | 100,7 % | 100,0 % |
| Lucía Ponce (Centro) | $ 584 M | 99,6 % | 101,7 % | 98,2 % |
| Santiago Ruiz (Interior) | $ 438 M | 102,1 % | 101,5 % | 102,4 % |

En el total de los dos ejercicios, tres de los cuatro equipos superan el objetivo y el de Lucía Ponce queda apenas por debajo. Pero mirando cada ejercicio por separado, ese equipo fue el de mejor cumplimiento en 2024/25 y cayó al 98,2 % en 2025/26: la brecha es reciente. En el ranking individual se destaca Germán Pereyra, con 113,6 % de cumplimiento (115,6 % en 2025/26).

**Recomendación:** analizar con la página de detalle a los vendedores que explican la caída del equipo de Lucía Ponce en 2025/26, y replicar las prácticas de los vendedores con mayor cumplimiento.

#### 10. La experiencia pesa más en el volumen que en el cumplimiento

| Clasificación | Venta neta | Cumplimiento | 2024/25 | 2025/26 |
|---|---|---|---|---|
| Senior | $ 1.638 M | 102,5 % | 100,0 % | 104,8 % |
| Semi Senior | $ 1.369 M | 99,3 % | 103,4 % | 96,2 % |
| Junior | $ 449 M | 100,3 % | 98,7 % | 100,7 % |

En el total, los Senior concentran la mayor venta y el mejor cumplimiento, los Junior venden bastante menos pero cumplen su objetivo y los Semi Senior quedan apenas por debajo del 100 %. Por ejercicio el cuadro cambia: en 2024/25 los Semi Senior fueron los de mejor cumplimiento y en 2025/26 los de peor, mientras que los Senior mejoraron.

**Recomendación:** las diferencias en el total son chicas, lo que indica objetivos bien ajustados a cada nivel. Conviene revisar qué cambió en 2025/26 para los Semi Senior y enfocar en ellos la capacitación.

#### 11. Pocas sucursales concentran la venta

Alto Palermo ($ 518 M), Abasto Shopping ($ 426 M) y Unicenter ($ 368 M), todas en AMBA, encabezan la venta y suman el 38 % del total. Entre las sucursales que operaron los dos ejercicios completos, las de menor venta son Alto NOA Shopping ($ 120 M) y Portal Tucumán ($ 152 M), ambas en el Noroeste.

Paseo Aldrey (abierta el 03/11/2025) y Alto Comahue (abierta el 03/03/2025) tienen totales bajos porque operaron solo una parte del período, no por bajo desempeño. Alto Comahue vendió $ 157 M en su primer ejercicio completo, por encima de Mendoza Plaza Shopping.

**Recomendación:** usar el mapa de sucursales para decidir dónde reforzar la presencia física y dónde atender la demanda con los canales digitales.

## Decisiones de modelado

### Esquema en estrella

- `factVentas` es la tabla de hechos, rodeada por las dimensiones Cliente, Producto, Sucursal, Vendedor, Canal, MedioPago, EstadoPedido y Promocion, más la dimensión Tiempo.
- Todas las relaciones son de uno a varios, con filtro en una sola dirección, sin relaciones varios a varios ni bidireccionales.

### Objetivos como segunda tabla de hechos

- Se unieron las planillas de objetivos de ambos ejercicios y se pasaron los meses de columnas a filas (unpivot), para obtener una fila por vendedor y mes.
- Cada objetivo se asigna al día 1 de su mes, respetando el ejercicio fiscal: de julio a diciembre corresponden al año de inicio del ejercicio. Se descartaron los objetivos en cero.
- La tabla Objetivo se relaciona solo con Vendedor y Tiempo, porque es el nivel al que la empresa fija sus metas. Por eso los filtros de sucursal, canal, segmento y categoría afectan a la venta pero no al objetivo. Se optó por no inventar un reparto del objetivo por esas dimensiones y aclararlo en el tablero.

### Dimensión de tiempo con ejercicio fiscal

- Tiempo es una tabla calculada con el ejercicio fiscal de julio a junio.
- Los meses se ordenan por su número dentro del ejercicio y se muestran en español.
- Tiene la jerarquía Ejercicio > Mes > Fecha.
- Es la única tabla con columnas calculadas, como admite el enunciado.
- La fecha de entrega se relaciona con Tiempo mediante una relación inactiva, que se activa con `USERELATIONSHIP` solo en la medida "Venta Neta por Fecha Entrega". Así se evita la ambigüedad entre fecha de venta y fecha de entrega.

### Medidas DAX

- Solo medidas explícitas, reunidas en la tabla exclusiva `Medidas` y organizadas en carpetas: Ventas, Clientes, Objetivos, Comparativos y Auxiliares.
- Formatos: pesos sin decimales y porcentajes con un decimal.
- Las medidas de venta, margen, unidades y comprobantes consideran solo pedidos con `Es_Venta_Efectiva = "Sí"`.
- Los acumulados del ejercicio usan `TOTALYTD` con cierre al 30 de junio.
- La variación contra el ejercicio anterior se calcula solo cuando hay un único ejercicio en contexto, para no comparar dos ejercicios sumados contra uno solo.
- Los clientes nuevos se calculan con `TREATAS` sobre la fecha de alta, sin agregar una relación física adicional.
- El ranking de cumplimiento usa `RANKX` y considera solo a los vendedores con objetivo asignado.

### Jerarquías y mapas

- Jerarquías:
  - Fiscal (Ejercicio > Mes > Fecha).
  - Comercial (Gerente > Vendedor).
  - Geográfica (Región > Provincia > Sucursal).
  - De producto (Categoría > Subcategoría > Producto).
- Latitud y longitud de las sucursales tienen asignada su categoría de datos. El mapa de sucursales usa los pares de coordenadas sin agregarlos y muestra el nombre de cada sucursal mediante una medida auxiliar.

### Tablero

- Páginas:
  - Análisis por Cliente.
  - Análisis por Vendedor.
  - Detalle del Vendedor, a la que se llega con "Obtener detalles" desde cualquier vendedor.
  - Una página de información sobre herramientas (tooltip) con la evolución mensual de cada sucursal.
- Los segmentadores de Tiempo, Segmento de cliente, Categoría y Zona comercial están sincronizados entre todas las páginas.
- La navegación se hace con botones en el encabezado.
- El cumplimiento usa un semáforo común en todo el informe: rojo por debajo del 90 %, amarillo entre 90 % y 100 % y verde desde el 100 %.
