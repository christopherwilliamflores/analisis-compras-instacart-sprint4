# 🛒 Análisis de compras en Instacart – Sprint 4

**Bootcamp de Ciencia de Datos | TripleTen**  
**Autor:** Christopher William Flores Rimac

---

## 📌 Descripción del proyecto

Este estudio de caso se centra en el análisis de hábitos de compra en la plataforma de entregas de comestibles **Instacart**. A partir de un conjunto de datos modificado, se realiza un proceso completo de preprocesamiento y análisis exploratorio de datos para identificar patrones de consumo, productos más populares y comportamientos de recompra.

---

## 🎯 Objetivos

- Limpiar los datos eliminando duplicados y gestionando valores ausentes.
- Verificar distribuciones en variables clave como día y hora de pedido.
- Identificar los productos más comprados y reordenados.
- Analizar la recurrencia y comportamiento de los clientes en sus compras.
- Visualizar los hallazgos mediante gráficos claros y anotados.

---

## 🧰 Herramientas utilizadas

- **Python 3**
- **Pandas**
- **Matplotlib**
- **Jupyter Notebook**
- **Gráficos y visualización básica**

---

## 🗃️ Datasets utilizados

| Archivo | Descripción |
|--------|-------------|
| `instacart_orders.csv` | Información de cada pedido y cliente. |
| `products.csv` | Detalles de productos únicos. |
| `order_products.csv` | Registros de cada producto incluido en los pedidos. |
| `aisles.csv` | Categorías de pasillos de víveres. |
| `departments.csv` | Departamentos a los que pertenecen los productos. |

---

## 📑 Diccionario de datos resumido

### instacart_orders.csv

- `order_id`, `user_id`, `order_number`, `order_dow`, `order_hour_of_day`, `days_since_prior_order`

### products.csv

- `product_id`, `product_name`, `aisle_id`, `department_id`

### order_products.csv

- `order_id`, `product_id`, `add_to_cart_order`, `reordered`

---

## 🔍 Etapas del proyecto

### 1. Preprocesamiento

- Verificación de tipos de datos
- Manejo de valores ausentes
- Eliminación de duplicados

### 2. Análisis exploratorio

#### A. Comportamiento general

- Distribución de pedidos por hora (`order_hour_of_day`)
- Distribución por día de la semana (`order_dow`)
- Análisis de frecuencia entre pedidos (`days_since_prior_order`)

#### B. Comportamientos específicos

- Comparación de pedidos entre miércoles y sábados
- Distribución de número de pedidos por cliente
- Top 20 productos más pedidos

#### C. Análisis de recompra

- Distribución de número de productos por pedido
- Productos más reordenados
- Proporción de recompra por producto y por cliente
- Productos más frecuentes como primer ítem en carrito

---

## 📊 Ejemplo de visualizaciones

Incluye gráficos con:

- Título
- Ejes correctamente etiquetados
- Leyendas cuando es necesario
- `plt.show()` aplicado

---

## 📌 Conclusiones

El análisis revela tendencias clave en los hábitos de consumo en Instacart:

- Las compras se concentran entre las 10 a.m. y 4 p.m.
- El domingo es uno de los días más activos.
- Algunos productos como bananas y leche tienen alta tasa de recompra.
- Existe una clara preferencia por ciertos productos al iniciar la compra.

---

## 🧠 Aprendizajes clave

- Dominio de preprocesamiento con Pandas.
- Habilidad para generar visualizaciones claras y efectivas.
- Aplicación de lógica para comparar comportamientos entre subgrupos.
