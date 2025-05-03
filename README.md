# Proyecto de Análisis de Alura Store

##  Propósito del Análisis

Este proyecto tiene como objetivo ayudar al Sr. Juan a identificar cuál de las cuatro tiendas de Alura Store (Bogotá, Medellín, Cali y Valledupar) presenta el peor desempeño, de modo que pueda venderla e invertir los recursos en un nuevo negocio con mayor potencial. Para ello, se evaluaron cinco métricas clave:

1. **Facturación total**
2. **Ventas por categoría**
3. **Calificación promedio de la tienda**
4. **Productos más y menos vendidos**
5. **Costo promedio de envío**

---

##  Estructura del Proyecto

```
alura-store/
│
├── data/                      # Carpeta con los archivos CSV de cada tienda
│   ├── tienda_1.csv           # Datos de la tienda de Bogotá
│   ├── tienda_2.csv           # Datos de la tienda de Medellín
│   ├── tienda_3.csv           # Datos de la tienda de Cali
│   └── tienda_4.csv           # Datos de la tienda de Valledupar
│
├── notebooks/                 # Carpeta con notebooks de análisis
│   └── Informe_Alura_Store.ipynb  # Notebook principal para Colab
│
├── images/                    # Carpeta con gráficos generados
│   ├── facturacion.png        # Facturación total por tienda
│   └── envio_promedio.png     # Costo promedio de envío por tienda
│
└── README.md                  # Documentación de este proyecto
```

---



1. **Facturación Total por Tienda**
   !![facturacion](https://github.com/user-attachments/assets/83a896d5-cde1-4ee6-95ea-582fd981d562)

   *Insight:* Bogotá lidera con > \$460 millones; Valledupar reporta < \$2 millones.

3. **Costo Promedio de Envío por Tienda**

   ![envio_promedio](https://github.com/user-attachments/assets/58f0dd7f-63cc-4015-a8bc-12ca684c7518)

   *Insight:* Bucaramanga y Pasto tienen los envíos más caros; Valledupar y Pereira son más económicos.

5. **Calificación Promedio**

   * Valledupar: 2.67 estrellas
   * Bucaramanga: 4.39 estrellas
     *Insight:* Valledupar muestra la menor satisfacción de clientes.

6. **Productos Más y Menos Vendidos**

   * **Bogotá:** Vaso térmico (30 ventas) vs. Auriculares con micrófono (8 ventas)

---

##  Instrucciones para Ejecutar el Notebook

1. **Clonar repositorio**

   ```bash
   git clone  https://github.com/OliviaBurgosBlanco08/challenge1-data-science-latam-main.git
   ```

2. **Abrir en Google Colab**

   * Ve a [Google Colab](https://colab.research.google.com/)
   * Archivo > Cargar notebook > selecciona `notebooks/Informe_Alura_Store.ipynb`

3. **Instalar dependencias**

   ```python
   !pip install pandas matplotlib seaborn
   ```

4. **Ejecutar todas las celdas**

   * Ejecuta cada bloque de código en orden para generar análisis y gráficos.

5. **Interpretar resultados**

   * Revisa la sección de **Conclusiones** al final del notebook para conocer la recomendación: vender la tienda con peor desempeño (Valledupar).

---

> **Contacto:** Para comentarios o dudas, escribir a Olivia Burgos ([oliviaburgosblanco@gmail.com)).
