# 🧠 E-Commerce Analytics Project (Olist Dataset)

## 🇬🇧 English Version

### Overview

This project explores the Olist Brazilian E-Commerce Dataset, a comprehensive dataset from the largest multi-vendor marketplace in Brazil. The goal is to analyze customer satisfaction, logistics performance, and geographical consumption patterns, while identifying key factors that influence the e-commerce experience.

### 🎯 1. Project Objectives

- Understand customer, seller, and product behavior.
- Identify factors affecting customer satisfaction (review_score).
- Explore the relationship between delivery time, order value, and review ratings.
- Map the geographical distribution of sales and delivery performance.
- Propose insights and recommendations for e-commerce optimization.

### 📊 2. Main Results

| Metric | Value |
|--------|-------|
| Total Orders | 99,441 |
| Unique Customers | 96,096 |
| Sellers | 3,095 |
| Product Categories | 71 |
| Average Order Value | R$161.99 |
| Average Review Score | 4.06 / 5 |
| Average Delivery Time | 12 days |
| Difference (Estimated vs. Real) | -11.4 days |
| Correlation Delivery Time–Satisfaction | -0.32 |

*The longer the delivery time, the lower the satisfaction.*

### 🌍 3. Key Insights

- **Delivery time is the most critical driver of satisfaction.** Orders with 1-star reviews take ~20 days to deliver, while 5-star orders arrive in ~10 days on average.
- **Regional concentration:** Over 60% of orders come from the Southeast (São Paulo & Minas Gerais), where deliveries are faster and satisfaction higher.
- **Shipping cost has little effect on satisfaction** — speed and reliability matter more.
- **Overall satisfaction:** 55% of reviews are 5 stars, but negative reviews are tightly linked to delivery delays.

### 📈 4. Featured Visualizations

- Review score distribution
- Relationship between delivery time and rating
- Geographic density map (Folium)
- Correlation heatmap
- Monthly trend of order volume

### 🧩 5. Conclusions

The analysis shows that delivery performance is the principal determinant of customer satisfaction. Customers prioritize reliability and delivery speed over shipping cost. Improving delivery accuracy and reducing delays could increase overall satisfaction by ~10–15% in slower regions.

**Recommendations summary:**
- Monitor delivery_time by seller and region; add SLA alerts for late deliveries.
- Improve the accuracy of estimated delivery dates.
- Prioritize operational/logistics improvements (routing, fulfillment SLA) over price adjustments when the objective is to raise review scores.
- Next steps: build predictive models for delivery time and review score; create an interactive dashboard (Streamlit/Power BI).

### 🚀 6. Future Extensions

- Predictive model for customer satisfaction (classification).
- Regression model for real delivery time prediction.
- Interactive dashboard using Plotly Dash or Streamlit.
- Deep-dive segmentation by category or regional performance.

### ✍️ Author

**Adrian Galvan**  
📍 Developed in Python (Jupyter Notebook)  
📆 2025  
📚 Dataset: Olist Brazilian E-Commerce Dataset on Kaggle — https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

---

## 🇪🇸 Versión en Español

### Descripción General

Este proyecto analiza el conjunto de datos público de Olist, el mayor marketplace multivendedor de Brasil. El objetivo es comprender la satisfacción del cliente, el rendimiento logístico y los patrones de consumo geográfico, identificando los factores más importantes que influyen en la experiencia de compra.

### 🎯 1. Objetivos del Proyecto

- Analizar el comportamiento de clientes, vendedores y productos.
- Identificar los factores que influyen en la satisfacción (review_score).
- Explorar la relación entre tiempos de entrega, valor del pedido y calificación.
- Mapear la distribución geográfica de ventas y desempeño logístico.
- Proponer conclusiones y recomendaciones para optimizar el e-commerce.

### 📊 2. Resultados Principales

| Métrica | Valor |
|---------|-------|
| Órdenes Totales | 99,441 |
| Clientes Únicos | 96,096 |
| Vendedores | 3,095 |
| Categorías de Producto | 71 |
| Valor Promedio por Pedido | R$161.99 |
| Calificación Promedio | 4.06 / 5 |
| Tiempo Promedio de Entrega | 12 días |
| Diferencia (Estimado vs Real) | -11.4 días |
| Correlación Entrega–Satisfacción | -0.32 |

*A mayor tiempo de entrega, menor calificación.*

### 🌍 3. Hallazgos Clave

- **Retrasos de entrega:** el factor más determinante en la insatisfacción. Los pedidos con 1 estrella tardan alrededor de 20 días, mientras que los de 5 estrellas llegan en 10 días.
- **Concentración regional:** Más del 60% de las ventas proviene del Sudeste (São Paulo y Minas Gerais), con mejores tiempos y puntuaciones.
- **Costo de envío:** No influye significativamente; lo que importa es la rapidez y la confiabilidad.
- **Satisfacción general:** 55% de las reseñas son de 5 estrellas; las negativas están ligadas a demoras logísticas.

### 📈 4. Visualizaciones Destacadas

- Distribución de calificaciones
- Relación entre tiempo de entrega y satisfacción
- Mapa geográfico (Folium)
- Mapa de calor de correlaciones
- Evolución mensual del volumen de pedidos

### 🧩 5. Conclusiones

El análisis revela que el tiempo de entrega es el principal determinante de la satisfacción. Los clientes priorizan la rapidez y confiabilidad por encima del costo del envío. Optimizar la logística y mejorar la precisión de los tiempos estimados podría elevar la satisfacción en un 10–15% en las regiones más lentas.

**Recomendaciones principales:**
- Monitorear delivery_time por vendedor y región; generar alertas por retrasos.
- Mejorar la precisión de las fechas de entrega estimadas.
- Enfocar mejoras operativas antes que cambios de precio si se busca elevar calificaciones.
- Próximos pasos: desarrollar modelos predictivos y dashboard interactivo.

### 🚀 6. Extensiones Futuras

- Modelo predictivo de satisfacción (clasificación).
- Modelo de regresión para tiempo real de entrega.
- Dashboard interactivo con Plotly Dash o Streamlit.
- Análisis comparativo por categoría o región.

### ✍️ Autor

**Adrian Galvan**  
📍 Proyecto desarrollado en Python con Jupyter Notebook  
📆 2025  
📚 Datos públicos: Olist Brazilian E-Commerce Dataset — https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce
