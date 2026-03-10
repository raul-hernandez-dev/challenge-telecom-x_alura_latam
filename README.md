# challenge-telecom-x_alura_latam

# TelecomX LATAM — Análisis de Evasión de Clientes (Churn)

Análisis exploratorio de datos para identificar los factores que llevan a la cancelación del servicio en TelecomX LATAM, con el objetivo de proponer estrategias de retención basadas en evidencia.

---

##  Estructura del repositorio

```
├── TelecomX_LATAM.ipynb   # Notebook principal con el análisis completo
├── README.md              # Este archivo
```

---

##  Fuente de datos

Los datos fueron obtenidos de el siguiente repositorio:

```
https://raw.githubusercontent.com/ingridcristh/challenge2-data-science-LATAM/main/TelecomX_Data.json
```

El dataset contiene información demográfica, de servicios contratados y de facturación de los clientes de TelecomX.

---

##  Fases del análisis

| Fase | Descripción |
|------|-------------|
|  Extracción | Carga de datos desde la API y conversión a DataFrame |
|  Transformación | Limpieza, corrección de tipos, creación de variables y estandarización |
|  Carga y Análisis | Análisis exploratorio con visualizaciones |
|  Informe Final | Conclusiones, insights y recomendaciones estratégicas |

---

##  Tecnologías utilizadas

- **Python 3**
- `pandas` — manipulación de datos
- `numpy` — operaciones numéricas
- `matplotlib` / `seaborn` — visualizaciones
- `requests` — consumo de API

---

##  Cómo ejecutar

1. Abre el archivo `TelecomX_LATAM.ipynb` en [Google Colab](https://colab.research.google.com/)
2. Ejecuta las celdas en orden (`Runtime > Run all`)
3. No se requiere instalación adicional; todas las librerías están disponibles en Colab por defecto

---

##  Principales hallazgos

- La tasa de evasión general es de aproximadamente el **26%**
- Los clientes con **contrato mensual** presentan la mayor propensión a cancelar (>40%)
- Los **primeros 12 meses** son el período crítico de retención
- La ausencia de **servicios adicionales** (seguridad, soporte técnico) aumenta el riesgo de churn
- Los usuarios de **Fiber Optic** tienen tasas de evasión más altas que otros segmentos

