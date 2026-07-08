# Proyecto: Detección Temprana de Riesgo Académico en UNCAus

## Descripción
Este proyecto tiene como objetivo desarrollar modelos predictivos de aprendizaje automático para identificar tempranamente situaciones de desaprobación y deserción escolar en las asignaturas **Algoritmos y Estructuras de Datos** y **Sistemas y Organizaciones** de la carrera de Ingeniería en Sistemas de la Universidad Nacional del Chaco Austral (UNCAus).

## Objetivo General
Desarrollar modelos capaces de anticipar el desempeño académico a partir de variables académicas, socioeconómicas, tecnológicas y motivacionales obtenidas del sistema SIU-Guaraní (cohortes 2024-2025).

## Estructura del Repositorio
- `/data`: Conjuntos de datos (archivos CSV). *Nota: Contenido excluido del control de versiones.*
- `/notebooks`: Libreta Jupyter con el flujo completo de análisis, preprocesamiento y modelado.
- `requirements.txt`: Dependencias del proyecto.

## Metodología
1. **Adquisición e Integración:** Consolidación de datos de 4 cohortes.
2. **EDA:** Análisis exploratorio de datos y correlación de variables.
3. **Preprocesamiento:** Tratamiento de nulos y codificación de variables.
4. **Modelado:** Implementación de algoritmos de clasificación (ej. Random Forest, Regresión Logística).
5. **Evaluación:** Medición de métricas de desempeño (Accuracy, F1-Score, Matriz de Confusión).

## Requisitos de Instalación
Para replicar el entorno virtual, asegúrate de tener Python 3.12+ y ejecuta:
```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
