# 📊 Power BI – Dashboard de Ventas y Rentabilidad

**Proyecto Final – Informatorio**

Dashboard interactivo desarrollado en **Power BI** para analizar el desempeño de **ventas, rentabilidad y transacciones**, aplicando buenas prácticas de **modelado de datos, ETL y DAX**.


## 🎯 Objetivo del Proyecto

Centralizar múltiples fuentes de datos en un **modelo analítico limpio y eficiente**, permitiendo:

- Analizar tendencias de ventas en el tiempo  
- Comparar rendimiento entre tiendas  
- Evaluar rentabilidad e impuestos  
- Visualizar la distribución geográfica de las ventas  



## 🧩 Fuentes de Datos

El proyecto integra las siguientes fuentes:

- Ventas  
- Clientes  
- Tiendas  
- Empleados  
- Calendario  

Todas las fuentes fueron procesadas y estandarizadas antes de construir el modelo final.



## 🔄 Proceso ETL (Power Query)

Todo el trabajo de preparación se realizó en el **Editor de Power Query**, aplicando:

- Renombrado de columnas  
- Ajuste de tipos de datos  
- Eliminación de campos irrelevantes  
- Limpieza de valores nulos  
- Unificación de formatos de fecha  
- Normalización de claves (*Tienda*, *Locación*)  
- Creación de una tabla calendario personalizada  

📌 El modelo definitivo se cargó **solo cuando los datos estuvieron completamente estandarizados**, garantizando consistencia y buen rendimiento.



## 🧠 Modelado de Datos

Se diseñó un **modelo estrella** optimizado:

- **Tabla de hechos:** Ventas  
- **Dimensiones:**  
  - DIM_Tienda  
  - Clientes  
  - Empleados  
  - Calendario  

Relaciones **1:\*** bien definidas, evitando ambigüedades y relaciones circulares.

🔹 La tabla **DIM_Tienda** actúa como nexo entre *Ventas, Empleados y Clientes*, permitiendo filtros cruzados correctos.  
🔹 La tabla **Calendario** fue marcada como **tabla de fechas**, habilitando cálculos de inteligencia temporal.



## 📐 Medidas DAX

Se crearon **medidas explícitas** para los principales KPI:

- 💰 Ganancia Total  
- 💵 Ganancia Neta Total  
- 🧾 Impuestos Totales  
- 🛒 Transacciones Totales  
- 📅 Medidas temporales (mensuales, acumuladas y comparativas)  

Estas medidas son la base de todas las visualizaciones del informe.



## 📊 Visualizaciones y Análisis

El dashboard incluye:

- 📈 Análisis de tendencias mensuales  
- 🏪 Comparación de rendimiento entre tiendas  
- 🌍 Distribución geográfica mediante mapas de burbujas  
- 🎛️ Segmentadores interactivos para análisis exploratorio  

El enfoque interactivo permite explorar los datos de forma dinámica y clara.



## ⚙️ Herramientas Utilizadas

- Power BI Desktop  
- Power Query (ETL)  
- DAX


## 👥 Autor

• **Bravo Juan Pablo**


## 📞 Contacto

Si tienes preguntas o sugerencias, no dudes en contactar a través de:

- GitHub: [BJuanP](https://github.com/BJuanP)

---

⭐ Si este proyecto te ha sido útil, ¡no olvides darle una estrella!
