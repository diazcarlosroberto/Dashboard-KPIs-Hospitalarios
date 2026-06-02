# Hospital KPI Dashboard 🏥

## Description
Simulation and analysis of operational KPIs of a Mexican general hospital 
with 10,000 synthetically generated patient records. The objective is to 
demonstrate how data analysis can support clinical and administrative 
decision-making in healthcare institutions.

## KPIs Analyzed
- **Bed occupancy** by area (ICU, Emergency Department, General Hospitalization)
- **Average length of stay** by diagnosis
- **30-day readmission rate** by diagnosis

# Dashboard de KPIs Hospitalarios 🏥

## Descripción
Simulación y análisis de KPIs operativos de un hospital general mexicano 
con 10,000 registros de pacientes generados sintéticamente. El objetivo es 
demostrar cómo el análisis de datos puede apoyar la toma de decisiones 
clínicas y administrativas en instituciones de salud.

## 📊 Dashboard Interactivo
👉 [Ver dashboard en Looker Studio](https://datastudio.google.com/reporting/5518b4cd-d060-4c12-a1a6-6a0f8c6e19c5)

## KPIs Analizados
- **Ocupación de camas** por área (UCI, Urgencias, Hospitalización General)
- **Promedio de días de estancia** por diagnóstico
- **Tasa de readmisión a 30 días** por diagnóstico

## Hallazgos Principales
- El Infarto tiene la estancia más larga con 13.9 días promedio
- La Apendicitis tiene la estancia más corta con 3.1 días
- El Infarto también lidera la tasa de readmisión con 16.8%
- La ocupación está distribuida equitativamente entre las 3 áreas (~33% cada una)

## Herramientas
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black)
![Looker Studio](https://img.shields.io/badge/Looker_Studio-4285F4?style=flat&logo=google&logoColor=white)

## Estructura del Repositorio
dashboard-kpis-hospitalarios/
├── notebook.ipynb         ← generación de datos y análisis
├── Data
  ├── kpi_ocupacion.csv
  ├── kpi_estancia.csv
  ├── kpi_readmision.csv
└── README.md

## Autor
**Carlos Roberto Díaz** — [LinkedIn](https://www.linkedin.com/in/carlosrobertod)
