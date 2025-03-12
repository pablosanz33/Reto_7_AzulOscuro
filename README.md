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
