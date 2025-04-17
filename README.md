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

- **Categorías más Vendidas**: agrupar por categoría y contar ventas.  
- **Reseñas de Clientes**: promedio de calificaciones y análisis de comentarios.  
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