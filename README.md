# analisis-ventas-multitienda-alura
# Análisis de Facturación por Tienda

Este proyecto realiza un análisis básico de facturación a partir de archivos CSV que contienen ventas realizadas por cuatro tiendas. Cada archivo representa una tienda distinta y contiene columnas comunes como `Producto`, `Precio`, `Costo de envío`, entre otras.

## 📁 Estructura de los Datos

Cada archivo CSV tiene las siguientes columnas:

- `Producto`
- `Categoría del Producto`
- `Precio`
- `Costo de envío`
- `Fecha de Compra`
- `Vendedor`
- `Lugar de Compra`
- `Calificación`
- `Método de pago`
- `Cantidad de cuotas`
- `lat`
- `lon`

## ⚙️ Funcionalidad

El script hace lo siguiente:

1. Lee los datos desde cuatro URLs (una por tienda).
2. Agrega una columna `"Tienda"` a cada DataFrame.
3. Calcula la facturación por venta como:
Facturación = Precio + Costo de envío

4. Suma la facturación total por tienda.
5. Genera un gráfico de barras que compara las tiendas:
- El color rojo indica la tienda con mayor facturación.
- Cada barra tiene el valor total encima.

## 📊 Resultado

El gráfico final permite identificar visualmente qué tienda generó más ingresos totales.

## 🧪 Requisitos

- Python 3.7+
- Pandas
- Matplotlib

Instalación recomendada:
```bash
pip install pandas matplotlib
