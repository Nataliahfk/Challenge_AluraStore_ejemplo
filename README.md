
# 📊 Análisis de Eficiencia de Tiendas - Alura Store

Este proyecto tiene como objetivo realizar un **análisis exploratorio de datos (EDA)** de las ventas y reseñas de las tiendas de la cadena **Alura Store**. El análisis se centra en identificar cuál es la tienda menos eficiente y ofrecer una recomendación para el Sr. Juan sobre cuál tienda debería vender para lanzar un nuevo emprendimiento.

## 📁 Estructura del Proyecto


```
challenge_store_one/
├── data/               # Conjunto de datos originales y procesados
├── notebooks/          # Notebooks de Jupyter con análisis y visualizaciones
├── reports/            # Informe generado y gráficos exportados
├── .gitignore          # Archivos ignorados por Git
└── README.md           # Documentación del proyecto
```

## 📊 Tecnologías y Herramientas

- **Lenguaje de programación:** Python
- **Librerías principales:**
  - `pandas` para procesamiento y análisis de datos
  - `matplotlib` para la visualización de datos
  - `numpy` para manipulaciones matemáticas

## 🚀 Instalación y Uso

### 1. Clonar el repositorio

```bash
git clone https://github.com/zai-zu/challenge_store_one.git
cd challenge_store_one
```
### 2. Crear y activar un entorno virtual (opcional pero recomendado)

```python
python -m venv env
source env/bin/activate  # Windows: env\Scripts\activate
```


### 3. Instalar dependencias

```bash
pip install -r requirements.txt
```
### 4. Expplorar Notebooks
Accede a la carpeta notebooks/ y abre los archivos .ipynb para revisar el análisis realizado.

# 📈Resultados destacados
- Cálculo de ingresos totales por tienda.

- Análisis de las categorías más vendidas.

- Evaluación de la eficiencia en función de ingresos, costos y satisfacción del cliente.

- Visualización de los datos con gráficos de barras, pastel y dispersión.

# 🤝 Cómo contribuir

Las contribuciones son siempre bienvenidas. Para contribuir:

1. Haz un fork del repositorio.

2. Crea una rama nueva (```git checkout -b nueva-funcionalidad```).

3. Realiza los cambios y confirma (```git commit -am 'Agregar nueva funcionalidad```).

4. Sube tus cambios (```git push origin nueva-funcionalidad```).

5. Abre un Pull Request en GitHub.



## 📌 Contexto y Objetivo  
La cadena **Alura Store** cuenta con cuatro sucursales y el Sr. Juan desea decidir cuál de ellas vender para lanzar un nuevo emprendimiento.  
**Objetivo:** identificar, con base en datos de ventas y reseñas, la tienda menos eficiente y fundamentar una recomendación clara.

##  📋 Metodología  
1. **Carga y preparación de datos**  
   - Se importaron los archivos CSV de cada tienda usando **Pandas**.  
   - Se validó integridad, consistencia de tipos y ausencia de valores faltantes.

2. **Cálculo de métricas clave**  
   - **Ingresos totales** por tienda.  
   - **Número de ventas** agrupado por categoría.  
   - **Promedio de calificaciones** de clientes.  
   - **Top y bottom** de productos según volumen de ventas. 
   - **Incremeneto y decremento de ingresos** a lo largo del tiempo. 
   - **Costo promedio de envío**.

3. **Visualización**  
   - Gráficos (barras, pastel, dispersión, mapas de densisidad) implementados con **Matplotlib** y **plotly** para ilustrar comparaciones y tendencias.

 [Informe completo](Reports/Analisis.md) 