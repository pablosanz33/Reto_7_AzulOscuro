# Proyecto Azul Oscuro - Reto 07

## Introducción

Este documento detalla los pasos necesarios para llevar a cabo el proyecto desarrollado por el equipo **Azul Oscuro** en el **Reto 07**.  
El desafío planteado por **Seguros Lagun Aro** consiste en diseñar una propuesta de seguro de jubilación para los empleados de **EMBALAJES DEL NORTE S.A.**, tomando en cuenta análisis actuariales y escenarios financieros.

## Objetivos del Proyecto

El reto busca ofrecer una solución basada en datos que permita calcular y optimizar las primas de jubilación.  
Para ello, se han definido los siguientes objetivos principales:

- **Análisis de datos:** Procesamiento y exploración de la base de datos de los empleados para obtener información clave.
- **Predicción de jubilación:** Desarrollo de un modelo que estime los años hasta la jubilación de cada trabajador.
- **Cálculo financiero:** Determinación de las primas o capitales necesarios en función de diferentes escenarios económicos.
- **Simulación de flujos de caja:** Evaluación de la sostenibilidad de las propuestas y su impacto en los resultados de la aseguradora.
- **Escenarios alternativos:** Análisis de variaciones económicas para medir riesgos y oportunidades.
- **Aplicación web:** Desarrollo de una herramienta en Flask para facilitar la consulta de los cálculos y resultados.

## Requisitos para la Ejecución

Para llevar a cabo el proyecto, es necesario contar con un entorno de trabajo adecuado. Se recomienda seguir estos pasos:

### Configuración del entorno

Importar el archivo `entorno_AZUL_OSCURO_RETO_7.yml` con el siguiente comando en **Anaconda Prompt**:

```bash
conda env create --name RETO_07 --file entorno_AZUL_OSCURO_RETO_7.yml
```
### Descripción de los Scripts

#El proyecto se compone de varios scripts y notebooks organizados para llevar a cabo el análisis de datos, modelado y visualización de resultados. A continuación, se describe el propósito de cada uno:

Preprocesamiento.py

Limpieza y transformación de los datos.

Manejo de valores nulos y atípicos.

Generación de variables derivadas necesarias para el análisis.

**Analisis_descriptivo2025.ipynb**

- Exploración de los datos con estadísticas descriptivas.

- Visualización de distribuciones y relaciones entre variables.

- Identificación de tendencias clave para el modelo de predicción.

**Entrenamiento.py**

- Construcción y entrenamiento del modelo de predicción de jubilación.

- División de los datos en conjuntos de entrenamiento y prueba.

- Evaluación del rendimiento del modelo con métricas relevantes.

**Pediccion.py **

-Aplicación del modelo entrenado sobre nuevos datos.

-Generación de predicciones sobre el tiempo estimado hasta la jubilación.

-Almacenamiento de resultados en un formato adecuado para su análisis.

**Visualizacion.py**

-Creación de gráficos para representar los resultados del análisis y predicciones.

-Comparación de diferentes escenarios mediante visualizaciones interactivas.

-Generación de reportes gráficos para su interpretación.

**Finanzas.ipynb**

-Cálculo de primas y capitales necesarios para las propuestas de seguros.

-Simulación de escenarios financieros con diferentes tasas de interés y rentabilidad.

-Evaluación de la sostenibilidad del modelo de seguro propuesto.

**Mes_a_mes.ipynb**

- Análisis detallado de la evolución mensual de los flujos financieros.

**Mes_a_mes_Noruega.ipynb**

- Extensión del análisis mes a mes, considerando un caso específico en Noruega.

**Mes_a_mes_sp500.ipynb**

- Comparación del análisis mensual con el comportamiento del índice S&P 500.

Estos scripts y notebooks trabajan en conjunto para garantizar un análisis completo y fundamentado en datos sólidos, permitiendo la toma de decisiones basada en modelos predictivos y escenarios financieros detallados.


