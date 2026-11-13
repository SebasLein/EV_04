Markdown

# Proyecto de Análisis de Datos - Instacart

**Autor:** Sebastian Lein Castro Grajales  
**Programa:** Análisis y Desarrollo de Software (ADSO) - SENA CTMA  
**Materia:** Ciencia de Datos con Python

## Descripción del Proyecto

Este repositorio contiene un análisis de datos transaccionales de la plataforma de supermercado Instacart. El objetivo principal es explorar millones de registros para descubrir patrones de compra, limpiar los datos crudos, segmentar a los clientes y consolidar una tabla maestra de análisis.

El proyecto está dividido en dos grandes entregas:

1. **Exploración Inicial (EV04):** Importación, inspección de calidad, filtros lógicos y estadísticas básicas.
2. **Procesamiento de Datos (EV05/06):** Pipeline automatizado de limpieza, análisis de hábitos de compra (segmentación de clientes en ocasionales, regulares y frecuentes) y combinación de datasets mediante joins (`merge`).

## Estructura del Repositorio

El proyecto sigue una estructura profesional de ciencia de datos:

```text
instacart-analisis/
├── README.md                 # Documentación del proyecto
├── .gitignore                # Archivos excluidos de Git (ej. .venv, *.csv)
├── requirements.txt          # Dependencias de Python
├── data/
│   ├── raw/                  # Datasets originales de Instacart (CSV)
│   └── processed/            # Tablas limpias, consolidadas y exportadas
├── notebooks/
│   ├── Exploracion_Instacart.ipynb  # Cuaderno de la exploración inicial
│   └── pandas_labs.ipynb            # Cuaderno del pipeline, lecciones y retos
└── reports/                  # Informes de hallazgos
Instrucciones de Ejecución
Para reproducir este análisis en una máquina local, sigue estos pasos:

1. Clonar el repositorio y preparar el entorno:

Bash
git clone <URL_DE_TU_REPOSITORIO>
cd instacart-analisis
python -m venv .venv
2. Activar el entorno virtual:

En Windows: .venv\Scripts\activate

En Mac/Linux: source .venv/bin/activate

3. Instalar dependencias:

Bash
pip install -r requirements.txt
4. Descargar los datos:
Asegúrate de colocar los 5 archivos CSV originales (instacart_orders.csv, products.csv, order_products.csv, aisles.csv, departments.csv) dentro de la carpeta data/raw/.

5. Ejecutar JupyterLab:

Bash
jupyter lab
```
