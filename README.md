# 📞 Call Me Maybe: Telecom Operator Efficiency Analysis
## Análisis de Eficiencia de Operadores - Identificación de Ineficacia Operativa

---
## English

### 🚀 Project Overview
This project performs a comprehensive analysis of the **CallMeMaybe** virtual telephony service to identify inefficient operators. Instead of focusing on customer churn, this study centers on operational performance by analyzing missed calls, excessive waiting times, and outbound call volumes.

### 🔍 Key Features of the Analysis
* **Data Wrangling:** Comprehensive cleaning of telecom datasets, including handling unassigned calls (operator 0) and data type optimization.
* **Efficiency Metrics:** Calculation of **Total Waiting Time** using the logic:
    $$waiting\_time = total\_duration - call\_duration$$
* **Statistical Validation:** Application of the **Shapiro-Wilk** test for normality and **Mann-Whitney U** tests to prove that operators with high wait times also have significantly higher missed calls and lower proactivity.
* **Advanced Visualization:** Use of Boxplots and Scatter plots to identify performance outliers and "saturation" zones.

### 🛠️ Tech Stack
* **Python** (Pandas, NumPy)
* **Statistics:** Scipy (Stats)
* **Visualization:** Seaborn & Matplotlib, Tableau

### 📈 Key Findings
* Statistical evidence confirms that operators with wait times > 2,000 units are significantly less efficient in call retention.
* High-volume operators sometimes hit a "saturation point" where wait times grow disproportionately, affecting service quality.

---
## Español

### 📌 Resumen del Proyecto
Este proyecto realiza un análisis integral del servicio de telefonía virtual **CallMeMaybe** para identificar operadores ineficaces. El estudio se centra en el rendimiento operativo mediante el análisis de llamadas perdidas, tiempos de espera excesivos y volumen de llamadas salientes.

### 🔍 Características Clave del Análisis
* **Preparación de Datos:** Limpieza profunda de datasets de telecomunicaciones, incluyendo el manejo de llamadas no asignadas (operador 0) y optimización de tipos de datos.
* **Métricas de Eficiencia:** Cálculo del **Tiempo de Espera Total** mediante la fórmula:
    $$waiting\_time = total\_duration - call\_duration$$
* **Validación Estadística:** Uso de la prueba de **Shapiro-Wilk** para normalidad y pruebas **Mann-Whitney U** para demostrar que los operadores con altas esperas tienen significativamente más llamadas perdidas y menor proactividad.
* **Visualización Avanzada:** Implementación de Boxplots y Scatter plots para identificar valores atípicos (outliers) de rendimiento y zonas de saturación.

### 🧰 Tecnologías Utilizadas
* **Python** (Pandas, NumPy)
* **Estadística:** Scipy (Stats)
* **Visualización:** Seaborn y Matplotlib, Tableau

### 📊 Conclusiones Principales
* Existe evidencia estadística de que los operadores con tiempos de espera superiores a 2,000 unidades fallan significativamente en la retención de llamadas.
* Se identificaron operadores de alta productividad que alcanzan un "punto de saturación" donde el tiempo de espera crece de forma desproporcionada.

---

### 📂 Repository Structure / Estructura
* `EDA_TELECOM.ipynb`: Main analysis notebook / Notebook principal de análisis.
* `telecom_dataset_new.csv`: Call logs data / Registros de llamadas.
* `telecom_clients.csv`: Client and tariff plan information / Información de clientes y tarifas.

**Author:** [CIEL-9511](https://github.com/CIEL-9511)

**Dashboard Tableau:** https://public.tableau.com/views/Telecom-CallMeMaybe-ProyectoFinalDA/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link 
