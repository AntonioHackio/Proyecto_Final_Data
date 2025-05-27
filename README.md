# 📊 Proyecto de Análisis de Datos - Sistema de Gestión de Leads y Cursos

## 🎯 Descripción del Proyecto

Este proyecto tiene como objetivo analizar el embudo de conversión de leads educativos desde el primer contacto hasta la matrícula final. Los datos procesados serán cargados en una base de datos SQL para posteriormente crear dashboards interactivos en Tableau que permitan optimizar las estrategias comerciales y mejorar las tasas de conversión.

---

## ✨ Componentes Clave

1. **Pipeline ETL (Extracción, Transformación, Carga):**
   - Desarrollado en **Python (Pandas)** para limpiar, normalizar y estructurar datos provenientes de diversas fuentes.
   - Asegura la calidad y consistencia de la información para un análisis fiable.

2. **Análisis Exploratorio de Datos (EDA):**
   - Realizado en **Python (Matplotlib, Seaborn, Plotly)** para descubrir patrones, tendencias y relaciones ocultas en los datos limpios.
   - Genera insights clave sobre el comportamiento de los leads y el rendimiento de los cursos.

3. **Dashboard Interactivo en Tableau:**
   - Consolida los Indicadores Clave de Rendimiento (KPIs) más relevantes en una interfaz visual e intuitiva.
   - Facilita la monitorización continua y la exploración dinámica de los datos por parte de los usuarios de negocio.

# Estructura del Proyecto

```
📦 Proyecto
│
├── 📁 .venv/
│
├── 📁 dashboard/
│
├── 📁 data/
│   ├── 📄 Cursos.csv
│   ├── 📄 Leads.csv
│   ├── 📄 Primer contacto.csv
│   └── 📄 Seguimiento.csv
│
├── 📁 data_clean/
│   ├── 📄 cursos_final.csv
│   ├── 📄 cursos_limpio.csv
│   ├── 📄 leads_final.csv
│   ├── 📄 leads_limpio.csv
│   ├── 📄 primer_contacto_final.csv
│   ├── 📄 primer_contacto_limpio.csv
│   ├── 📄 seguimiento_final.csv
│   ├── 📄 seguimiento_limpio.csv
│   └── 📄 tecnologias_final.csv
│
├── 📁 documentacion/
│
├── 📁 entregables/
│   └── 📄 Memoria_Proyecto_Final.docx
│
├── 📁 notebooks/
│   ├── 📓 conexion_bbdd.ipynb
│   ├── 📓 EDA.ipynb
│   └── 📓 Transformacion.ipynb
│
├── 📁 src/
│   ├── 📁 eda/
│   │   ├── 🐍 explore.py
│   │   ├── 🐍 init.py
│   │   └── 🐍 main.py
│   │
│   ├── 📁 etl/
│   │   ├── 🐍 extract.py
│   │   ├── 🐍 init.py
│   │   ├── 🐍 load.py
│   │   ├── 🐍 main.py
│   │   └── 🐍 transform.py
│   │
│   └── 🐍 init.py
│
├── 📁 Tableau/
│   └── 📊 Proyecto_Final.twb
│
├── 📄 .gitignore
├── 📄 credenciales.json
├── 📄 README.md
└── 📄 requirements.txt
```

## 💻 Tecnologías y Librerías

- **Python:**
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `plotly`
- **Tableau Desktop**

## 📈 Métricas Clave (KPIs)

El dashboard de Tableau visualiza métricas esenciales, incluyendo:

- **Tasa de Conversión:** General y por fuente de lead.
- **Ingresos Generados:** Totales y desglosados por fuente y curso.
- **Duración del Ciclo de Venta:** Tiempo promedio hasta la matrícula y duración del proceso de seguimiento.
- **Distribución de Leads:** Por fuente, estado, edad y ubicación geográfica.
- **Rendimiento de Cursos:** Popularidad, rentabilidad, rating y empleabilidad.
- **Análisis del Embudo:** Identificación de puntos de abandono en el proceso de lead.

## 💡 Próximos Pasos

- **Automatización del ETL:** Integración con bases de datos o APIs para actualizaciones de datos en tiempo real.
- **Análisis Predictivo:** Implementación de modelos de Machine Learning para la predicción de la conversión de leads o la demanda de cursos.
- **Integración de Costos:** Añadir datos de inversión en marketing para calcular el ROI y el CAC.