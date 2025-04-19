# Presentación del Proyecto: Alura Store – Análisis de Eficiencia de Tiendas

##  Contexto y Objetivo  
La cadena **Alura Store** cuenta con cuatro sucursales y el Sr. Juan desea decidir cuál de ellas vender para lanzar un nuevo emprendimiento.  
**Objetivo:** identificar, con base en datos de ventas y reseñas, la tienda menos eficiente y fundamentar una recomendación clara.

##  Metodología  
1. **Carga y preparación de datos**  
   - Se importaron los archivos CSV de cada tienda usando **Pandas**.  
   - Se validó integridad, consistencia de tipos y ausencia de valores faltantes.

2. **Cálculo de métricas clave**  
   - **Ingresos totales** por tienda.  
   - **Número de ventas** agrupado por categoría.  
   - **Promedio de calificaciones** de clientes.  
   - **Top y bottom** de productos según volumen de ventas.  
   - **Costo promedio de envío**.

3. **Visualización**  
   - Al menos tres gráficos (barras, pastel, dispersión) implementados con **Matplotlib** para ilustrar comparaciones y tendencias.

##  Análisis Exploratorio de Datos

Como paso inicial se confirmó que los cuatro conjuntos de datos reúnen las condiciones mínimas de calidad para su procesamiento. En particular:

- **Integridad de la información:** no se detectaron valores faltantes ni registros duplicados.  
- **Consistencia de formato y topología:** las columnas presentan el mismo esquema y carecen de inconsistencias (por ejemplo, números almacenados como texto o fechas mal formateadas).  
- **Tipos de datos apropiados:** cada variable (numérica, categórica, fecha) está declarada con el tipo correcto, lo que garantiza operaciones y transformaciones sin errores.  
- **Estandarización estructural:** todos los archivos comparten la misma disposición de columnas, lo que facilita la unificación y el análisis conjunto.

---

### Estructura de los datos

- **Producto y Categoría:** artículos vendidos y su clasificación en categorías.  
- **Precio y Envío:** valor de venta de cada producto y costos asociados de transporte.  
- **Fecha y ubicación de compra:** marca temporal de la transacción y ciudad o región de origen.  
- **Evaluación de compra:** calificaciones y comentarios proporcionados por los clientes.  
- **Tipo de Pago y Cuotas:** método de pago utilizado y número de cuotas seleccionadas.  
- **Coordenadas Geográficas:** latitud y longitud donde se realizó cada transacción.

### 1.1 Principales hallazgos del analisis 
- **Ingresos Totales**: 
Los ingresos totales por cada tienda en el periodo de 2020-01-31 al 2023-03-31 fueron
   - **Tienda 1: $1,150,880,400.00**
   - **Tienda 2: $1,116,343,500.00**
   - **Tienda 3: $1,098,019,600.00**
   - **Tienda 4: $1,038,375,700.00**

- **Categorías más Vendidas**: 
 La cadena de sucursales ofrece una variedad de productos, los cuales  están agrupados por las siguientes  categorías:  Artículos para el hogar, Deportes y diversión, Electrodomésticos, Electrónicos, Intrumentos musicales,  Juguetes, Libros y Muebles.
 Las  tres categorías con más ventas  en todas las tiendas fueron Muebles, Eectrónicos y Juguetes. A acontinuación se presentan el número de ventos y los ingresos:

   -**Tienda 1:**
      - **Muebles**, con un total de 465 de productos vendidos e ingresos de $187,633,700.
      - **Electrónicos**, con un total de 448 productos vendidos e ingresos de $429,493,500.
      -**Jueguetes**, con un total de 324 productos vendidos e ingresos de $17,995,700.

   -**Tienda 2:**  
      - **Muebles**, con un total de 442 de productos vendidos e ingresos de $176,426,300.
      - **Electrónicos**, con un total de 422 productos vendidos e ingresos de $410,831,100.
      -**Jueguetes**, con un total de 313 productos vendidos e ingresos de $15,945,400.

   -**Tienda 3:**  
      - **Muebles**, con un total de 499 de productos vendidos e ingresos de $201,072,100.
      - **Electrónicos**, con un total de 451 productos vendidos e ingresos de $410,775,800.
      -**Jueguetes**, con un total de 315 productos vendidos e ingresos de $19,401,100.

   -**Tienda 4:**  
      - **Muebles**, con un total de 480 de productos vendidos e ingresos de $192,528,900.
      - **Electrónicos**, con un total de 451 productos vendidos e ingresos de $409,476,100.
      -**Jueguetes**, con un total de 338 productos vendidos e ingresos de $20,262,200.

En los resultados se destaca que apaesar de ser a Tienda 1 es la que más ingresos ha tenido en el perido de tres años, la Tienda 4 es quién más ingresos tiene en cada una de las categorías más vendidas

- **Reseñas de Clientes**:  
Con el objetivo,  de conocer la satisfacción del cliente con los productos vendidos, se calculó de manera global las calificaciones  promedio de los clientes para cada tienda. Los resultados fueros los siguientes

   - La calificación promedio de los productos en la **Tienda 1** fue de: **3.98**
   - La calificación promedio de los productos en la **Tienda 2** fue de: **4.04**
   - La calificación promedio de los productos en la **Tienda 3** fue de: **4.05**
   - La calificación promedio de los productos en la **Tienda 4**  fue de: **4.00**



- **Productos Más/Menos Vendidos**: identificar los top y bottom por volumen.  
- **Costo Promedio de Envío**: calcular el envío medio por transacción.



###  Gráficos para Visualización
- Diseña **mínimo 3** gráficas diferentes para mostrar:
  - Comparación de ingresos entre tiendas.  
  - Distribución de ventas por categoría.  
  - Relación precio–reseñas o costo de envío.  
- Puede incluir:  
  - Gráficos de barras  
  - Gráficos circulares (pie charts)  
  - Diagramas de dispersión  
  - Mapas de calor, histogramas, etc.

##  Recomendación final
Innforme breve donde  se indique **qué tienda** debe vender el Sr. Juan y **por qué**, fundamentando tu decisión en cinco aspectos clave:
1. Facturación total de cada tienda.  
2. Categorías más populares en cada sucursal.  
3. Promedio de evaluación de clientes.  
4. Productos más y menos vendidos.  
5. Costo promedio de envío.