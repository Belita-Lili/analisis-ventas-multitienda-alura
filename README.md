# analisis-ventas-multitienda-alura
![image](https://github.com/user-attachments/assets/a8b53e77-ab35-4ace-8ad3-6507808e77ee)


# Análisis de Facturación por Tienda

Este proyecto realiza un análisis básico de facturación a partir de archivos CSV que contienen ventas realizadas por cuatro tiendas. Cada archivo representa una tienda distinta y contiene columnas comunes como `Producto`, `Precio`, `Costo de envío`, entre otras.

## 📁 Estructura de los Datos
```bash
.
├── dashboard-tienda-alura/
│   └── analisis/ # Imagenes png de la paleta de colores.
│       ├── tiendas_dc_alura.py
│       └── Tiendas_DC_Alura.ipynb
│   └── colores/
│       └──paleta de colores...
│   └──graficas/
│       └──graficas...
└── README.md
```

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
## 🎨 Personalización
Puedes cambiar los colores directamente en el script con tus variables personalizadas, por ejemplo:
```bash
Blanco_1 = "#ffffff"
Turquesa_1 = "#40e0d0"
Verde_1 = "#2e8b57"
Negro_Carbón = "#333333"
```
## 📊 Resultado

El gráfico final permite identificar visualmente qué tienda generó más ingresos totales.
![Ciecia de Datos Linkedin (1)](https://github.com/user-attachments/assets/4b16ec10-f032-41b4-b61e-de7d691d9496)


## 🧪 Requisitos

- Python 3.7+
- Pandas
- Matplotlib

Instalación recomendada:
```bash
pip install pandas matplotlib
```
