[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/yonathanmontenegro/)
[![GitHub](https://img.shields.io/badge/GitHub-Repo-181717?logo=github&logoColor=white)](https://github.com/yomod290/End_to_End_Adventureworks)
[![Notion Project](https://img.shields.io/badge/Notion-Project-black?logo=notion&logoColor=white)](https://yonathan-montenegro.notion.site/AdventureWorks-Azure-Lakehouse-DEV-PROD-ETL-End-to-End-2fcc4265055380a4832cd26f9ea11821)
[![Notion Portafolio](https://img.shields.io/badge/Notion-Portafolio-black?logo=notion&logoColor=white)](https://yonathan-montenegro.notion.site/portafolio-data-engineer)
[![Azure](https://img.shields.io/badge/Azure-Cloud-0078D4?logo=microsoftazure&logoColor=white)](https://azure.microsoft.com/)
[![Databricks](https://img.shields.io/badge/Databricks-Lakehouse-EF3D2C?logo=databricks&logoColor=white)](https://www.databricks.com/)
[![PySpark](https://img.shields.io/badge/PySpark-Data%20Processing-E25A1C?logo=apachespark&logoColor=white)](https://spark.apache.org/docs/latest/api/python/)




# 🚀 Proyecto End-to-End AdventureWorks Lakehouse (DEV / PROD)

> Arquitectura moderna de Data Engineering en Azure con separación de ambientes, procesamiento incremental, SCD Tipo 2 y CI/CD automatizado.

---
<img width="1266" height="700" alt="image" src="https://github.com/user-attachments/assets/8c49be71-82ca-4e4a-addf-4647327d861a" />

---

# 📌 1. Descripción General

Este proyecto implementa una arquitectura completa de **Azure Lakehouse empresarial**, simulando un entorno real de Data Engineering con:

- Separación de ambientes (DEV / PROD)
- Arquitectura en capas (Bronze / Silver / Gold)
- Gobierno de datos con Unity Catalog
- Seguridad empresarial
- CI/CD automatizado
- Consumo analítico en Power BI

El objetivo es demostrar un flujo **end-to-end**, desde la ingesta hasta la visualización, siguiendo estándares modernos de ingeniería de datos.

---

# 🏗️ 2. Arquitectura de la Solución

## 🔹 Componentes Utilizados

- Azure Data Factory
- Azure Data Lake Storage Gen2
- Azure Databricks
- Unity Catalog
- Delta Lake
- GitHub Actions
- Azure Key Vault
- Power BI

---

# 🗂️ 3. Fuentes de Datos

- 🗄️ SQL Server On-Premise (simulado)
- ☁️ Azure SQL Database

---

# 🥉 4. Ingesta de Datos – Capa Bronze

## 🔧 Servicio Utilizado
**Azure Data Factory**

### ✔ Características Implementadas

- Pipelines parametrizados
- Separación DEV / PROD
- Carga incremental
- Control dinámico por datasets
- Escritura en formato Delta

### 📦 Almacenamiento

Azure Data Lake Storage Gen2  
Capa Bronze (Tablas Delta)

---

# 🥈 5. Procesamiento y Transformación – Capa Silver

## ⚙️ Tecnología Utilizada

- PySpark
- Delta Lake
- Unity Catalog
- MERGE incremental

---

## 🧹 Procesos Aplicados

- Limpieza y estandarización
- Validación de tipos
- Eliminación de duplicados
- Reglas de negocio
- Procesamiento incremental

---

## 🔁 Implementación SCD Tipo 2

Se implementó Slowly Changing Dimension Tipo 2 en la dimensión **Product** con:

- Conservación del historial de cambios
- Columnas `EffectiveFrom`
- Columnas `EffectiveTo`
- Indicador `IsCurrent`
- Versionado automático mediante MERGE

### 🎯 Resultado

- Trazabilidad histórica completa
- Análisis temporal avanzado
- Diseño orientado a auditoría y reporting corporativo

---

# 🥇 6. Capa Gold – Modelo Analítico

En esta capa se construyen tablas optimizadas para consumo BI:

- Modelado analítico
- Optimización para consultas
- Preparación para Power BI
- Separación estricta de ambiente PROD

---

# 🔐 7. Seguridad y Gobierno

## 🛡️ Implementaciones

- Azure Key Vault (gestión de secretos)
- Managed Identity
- Access Connector
- RBAC
- Unity Catalog
- Separación DEV / PROD

---

# 🔄 8. CI/CD y Automatización

## 🔧 Herramientas

- GitHub Repositories
- GitHub Actions
- Autenticación OIDC
- ARM Templates
- Databricks Repos

## 🚀 Capacidades Logradas

- Versionamiento de notebooks
- Promoción controlada DEV → PROD
- Infraestructura como código
- Automatización de despliegues

---

# 📊 9. Consumo Analítico

Power BI consume exclusivamente datos del entorno PROD.

## ✔ Características

- Modelo analítico optimizado
- Arquitectura enterprise-ready
- Separación estricta de ambientes

---

# 🧠 10. Buenas Prácticas Aplicadas

- Arquitectura Medallion
- Procesamiento incremental
- Diseño idempotente
- Parametrización avanzada
- Gobierno de datos
- Seguridad basada en identidad
- Automatización CI/CD
- Enfoque enterprise-ready

---

# 🏁 11. Conclusión

Este proyecto representa una implementación completa de una plataforma moderna de datos en Azure, aplicando estándares empresariales de:

- Escalabilidad
- Seguridad
- Gobierno
- Automatización
- Trazabilidad histórica

Simula cómo se construye una solución de Data Engineering lista para producción en un entorno corporativo real.

---

👤 Autor
Yonathan Montenegro Martínez

---

📅 Fecha
Febrero 2026

---
