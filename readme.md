# 🧠 Análisis de Datos: ¿Qué Tienda Debería Vender Juan?

## 📌 Propósito

El objetivo de este análisis es determinar cuál de las tiendas del señor Juan debería ser vendida. Para responder a esta pregunta, se realizó un análisis exploratorio de datos basado en:

- Los productos vendidos por cada tienda.
- Las coordenadas geográficas de cada tienda.
- Los ingresos generados por cada tienda.
- Las calificaciones otorgadas por los clientes.
- Datos adicionales de rendimiento por categoría de producto.

---

## 🗂️ Estructura del Proyecto

El análisis se desarrolló en un archivo de **Google Colab**, y se compone de las siguientes etapas:

1. **Importación de datos**  
   Se cargan los DataFrames de cada tienda desde archivos CSV públicos.

2. **Limpieza de datos**  
   Se verifica la existencia de valores nulos que puedan afectar los resultados.

3. **Cálculo de ingresos por tienda**  
   Se determina el ingreso total de cada tienda y se visualiza en un gráfico.

4. **Análisis por categoría de producto**  
   Se agrupan los productos por categoría y se calculan las ventas totales por cada una.

5. **Calificación promedio de los clientes**  
   Se obtiene el promedio de puntuación otorgada a cada tienda.

6. **Productos más y menos vendidos por tienda**  
   Se identifican las tendencias de consumo.

7. **Costo promedio de envío**  
   Se analiza el gasto promedio por tienda en costos de envío.

8. **Rendimiento económico por categoría**  
   Se calcula el ingreso por categoría de producto en cada tienda.

9. **Visualización geográfica**  
   Se crean mapas interactivos para mostrar:
   - Ubicación de las tiendas.
   - Distribución de ventas por zona y categoría.

10. **Conclusión final**  
    Basado en los análisis anteriores, se entrega una recomendación sobre cuál tienda vender.

---

## 🛠️ Cómo abrir el proyecto

Puedes abrir el archivo `.ipynb` (cuadernillo de Jupyter) de dos maneras:

- 📂 **Google Drive + Google Colab**:  
  Sube el archivo a tu Drive y ábrelo con Google Colab.

- 💻 **Visual Studio Code**:  
  Instala la extensión de Jupyter para VSCode y abre directamente el archivo.

---

## 📄 Licencia

Este proyecto está bajo la licencia [MIT](https://opensource.org/licenses/MIT).  
Puedes usarlo, modificarlo y distribuirlo libremente.