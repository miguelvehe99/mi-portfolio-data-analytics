# Proyecto Análisis de Datos: Ventas en una cafetería

En este repositorio se incluyen:
- La tabla original de datos (sin limpiar)
- La tabla de datos limpia
- El código Python utilizado para la limpieza y análisis
- El archivo de Power BI con el dashboard final

## Objetivo del proyecto

El objetivo principal del proyecto es analizar las ventas de productos de una cafetería para detectar:
- Patrones de consumo según el producto.
- Tendencias de facturación mensual y semanal.
- Evaluar si hay productos que no son rentables y podrían eliminarse del catálogo.

### Lista de productos y precios:

| Producto   | Precio (€) |
|------------|------------|
| Galleta    | 1          |
| Té         | 1.5        |
| Café       | 2          |
| Tarta      | 3          |
| Zumo       | 3          |
| Batido     | 4          |
| Bocadillo  | 4          |
| Ensalada   | 5          |

## Proceso de trabajo

### 1. Limpieza de datos
- Herramientas utilizadas: **Python (Pandas, NumPy)**
- Análisis de columnas, detección de valores nulos y duplicados.
- Sustitución de valores nulos por valores similares en otras columnas.
- Eliminación de valores innecesarios o imposibles de calcular.

### 2. Análisis exploratorio 
- Herramientas utilizadas: **Seaborn**
- Análisis de patrones y tendencias por producto y fecha.
- Visualización mediante gráficos para identificar insights clave para el negocio.

### 3. Creación de dashboard en Power BI
- Herramienta utilizada: **Power BI**
- Desarrollo de un dashboard interactivo con:
  - Ventas y facturación por producto
  - Ventas y facturación mensual y semanal
  - Comparativa de productos
- 📸 Se incluye una captura de pantalla del dashboard final.

## Conclusiones
![Dashboard Power BI](Dashboard%20Cafeter%C3%ADa.png)

- Se han vendido **más de 3000 unidades por producto**, con un total de **25.908 unidades**.
- La facturación total fue de **76.605 €**, siendo la **ensalada** el producto que más facturó y las **galletas** el que menos.
- Las ventas mensuales se mantienen relativamente constantes, con un **máximo en octubre** y un **mínimo en febrero**.
- La facturación es mayor en **octubre** y también se observa un pico durante el verano (**junio**).
- Las ventas y la facturación aumentan al final de la semana, especialmente en **viernes y domingo**, siendo **miércoles** el día más bajo.
- No se eliminaría ningún producto del catálogo, ya que todos mantienen un volumen de ventas significativo.

### Conclusión adicional:
- La variedad de productos parece contribuir a mantener el flujo de clientes regular a lo largo de la semana y del año, por lo que mantener un catálogo amplio favorece la estabilidad del negocio.

## Tecnologías y librerías utilizadas

- **Python**: `Pandas`, `NumPy`, `Seaborn`
- **Power BI**
- **Jupiter Notebook**

---

Si tienes alguna duda o sugerencia sobre el proyecto, puedes contactar conmigo a través de:  
📧 [miguelvehe@hotmail.es](mailto:miguelvehe@hotmail.es)
🔗 [LinkedIn](https://www.linkedin.com/in/miguel-velasco-hernando/)

