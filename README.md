# 🛒 Análisis Exploratorio de Datos (EDA) - ComercioYA

*Autor:* Nicolás Pérez Cerda  
*Rol:* Analista de Datos

## 📝 Descripción del Proyecto
Este proyecto es un Análisis Exploratorio de Datos (EDA) desarrollado para "ComercioYA", una empresa de e-commerce. El objetivo principal fue procesar, limpiar y analizar una base de datos histórica de clientes para encontrar patrones de comportamiento, identificar segmentos de alto valor y proveer recomendaciones estratégicas basadas en evidencia matemática.

## 🛠️ Tecnologías y Herramientas Utilizadas
* *Lenguaje:* Python 3
* *Manipulación de Datos:* Pandas, NumPy
* *Visualización:* Matplotlib, Seaborn
* *Entorno:* Jupyter Notebook / Google Colab

## 📊 Hallazgos Clave (Insights)
1. *Segmentación VIP:* Mediante gráficos de dispersión y diagramas de caja (Boxplots), se logró identificar de manera matemática un segmento de valores atípicos (outliers) superiores. Estos no representaban errores del sistema, sino "Clientes de Alto Valor" o compras mayoristas críticas para la facturación.
2. *Análisis de Correlación:* Al evaluar la matriz de Pearson, se detectó una ausencia de correlación lineal fuerte entre las visitas mensuales y el monto de compra. Esto impulsó la recomendación estratégica de integrar nuevas variables (como métricas de navegación y marketing) para futuros modelos predictivos.

## 📁 Estructura del Repositorio
* ABP_Modulo_5_Nicolás_Pérez.ipynb: Cuaderno fuente con el código documentado paso a paso.
* Informe_Tecnico_ComercioYA.pdf: Reporte ejecutivo final con las conclusiones de negocio.
* /graficos: Graficos de visualizaciones exportadas (Heatmap, Pairplot, Jointplot, etc.).
