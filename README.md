# Showz Marketing Funnel Analysis

Este proyecto analiza el rendimiento del embudo de marketing de **Showz**, una plataforma de venta de entradas para eventos. Utilizando datos de visitas, pedidos y costos publicitarios, se construyen métricas clave de adquisición, conversión y rentabilidad que permiten evaluar la eficiencia de las campañas y el comportamiento del usuario a lo largo del funnel.

---

## 📌 Objetivo
- Evaluar el desempeño del funnel de marketing (visita → pedido → compra).
- Analizar el comportamiento diario, semanal y mensual de los usuarios.
- Calcular y monitorear métricas clave: **Conversión**, **CAC**, **ROI**, **ARPU**, **Revenue**, **Retention**.
- Comparar la eficiencia de distintas fuentes de adquisición.
- Identificar áreas de oportunidad para mejorar el rendimiento comercial.

---

## 🧹 Preparación de los Datos
Se trabajó con tres datasets:

- **visits_log_us.csv** – visitas al sitio con marca temporal, dispositivo y fuente.
- **orders_log_us.csv** – pedidos completados con ingresos y fecha.
- **costs_us.csv** – costos publicitarios por día y fuente.

El preprocesamiento incluyó:
- Conversión y normalización de fechas.
- Unificación de claves para merges entre tablas.
- Verificación de valores faltantes y duplicados.
- Creación de columnas derivadas como mes, semana, ingresos, etc.

---

## 📊 Análisis Realizado
- Flujo de usuarios desde visita → pedido → compra.
- Conteos diarios, semanales y mensuales de actividad.
- Costos por fuente y rendimiento de cada canal.
- Conversión por etapas del funnel.
- Ingresos por cliente y por periodo.
- Identificación de canales más rentables.
- Tendencias estacionales y comportamiento temporal.

---

## 📈 Métricas Calculadas
- **Daily Active Users (DAU)**  
- **Weekly Active Users (WAU)**  
- **Monthly Active Users (MAU)**  
- **Conversion Rate (CR)**  
- **Customer Acquisition Cost (CAC)**  
- **Return on Investment (ROI)**  
- **Average Revenue per User (ARPU)**  
- **Customer Lifetime Value (LTV)** *(si aplica)*  

Estas métricas permiten entender qué tan rentable es cada campaña de marketing y si los ingresos cubren los costos de adquisición.

---

## 🛠 Tecnologías Utilizadas
- **Python**
- **Pandas**
- **Matplotlib / Seaborn**
- **Jupyter Notebook**

---

## 📁 Archivos del Proyecto
- `showz-marketing-funnel-analysis.ipynb` — Notebook principal con el análisis.
- `visits_log_us.csv`, `orders_log_us.csv`, `costs_us.csv` – Datos utilizados en el proyecto.

---

## 📬 Contacto
Proyecto desarrollado como parte del portafolio analítico de **Monica Baca**.
