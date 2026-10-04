# Modelado y Balance Térmico de Caldera GLP

Este repositorio contiene el código de simulación y el informe técnico asociado a la evaluación de una caldera pirotubular diseñada para la generación de vapor saturado a 10 barg, alimentada con Gas Licuado de Petróleo (GLP). 

## 📌 Descripción del Proyecto
El estudio abarca el estado estacionario de la caldera bajo 4 regímenes de carga distintos durante un día de operación[cite: 35]. Se analizó la demanda térmica neta considerando las purgas continuas del sistema (control de STD), las pérdidas de calor hacia el entorno y la eficiencia térmica global mediante balances estequiométricos de combustión.

## 🛠️ Metodología y Herramientas
* **Engineering Equation Solver (EES):** Programación del modelo termodinámico iterativo.
* **Norma ASME PTC 4-2008:** Cálculo detallado de las pérdidas térmicas por convección y radiación a través de la carcasa aislada.
* **Correlación de Rohsenow:** Determinación de la transferencia de calor por ebullición nucleada y evolución de la temperatura superficial de los tubos.
* **Análisis de Combustión:** Balance estequiométrico del GLP (70% propano, 30% butano) con 15% de exceso de aire para determinar el flujo másico de combustible y las pérdidas en gases de escape.
* **LaTeX:** Maquetación profesional del reporte técnico y ecuaciones.

## 📂 Archivos del Repositorio
* `Tarea_1_EMT_Felipe_Campos.EES`: Script de cálculo con la resolución de los sistemas de ecuaciones, propiedades del agua/vapor e iteraciones de los regímenes de carga.
* `Tarea_1_EMT_Felipe_Campos.pdf`: Informe técnico detallado con el desarrollo matemático y análisis de resultados.

**Autor:** Felipe Campos Calderón.
