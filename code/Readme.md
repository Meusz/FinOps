# FinOps: Optimización de Costos en la Computación en la Nube para Big Data e IA
### Mateusz 2024

## Introducción

En la última década, la **computación en la nube** se ha convertido en una plataforma clave para las organizaciones, ofreciendo flexibilidad y reducción de costos en tecnología de la información (TI). Hoy en día, la nube no solo sirve para mejorar la agilidad empresarial sino también para acceder a capacidades avanzadas de infraestructura que de otro modo serían difíciles de desarrollar internamente. 

En este contexto, el presente **Trabajo de Fin de Máster (TFM)** explora la implementación y gestión de grandes volúmenes de datos y modelos de inteligencia artificial (IA) en entornos de nube a través de la técnica emergente conocida como **FinOps**. 

**FinOps** integra conocimientos técnicos, financieros y operativos para optimizar los costos de infraestructura en la nube mientras se mantiene un alto rendimiento. El objetivo principal de este estudio fue diseñar e implementar una arquitectura de **big data** basada en **Apache Spark** y en **Python**, capaz de cargar, almacenar, procesar y analizar datos, evaluando su eficacia mediante configuraciones variadas de Spark Pools en **Azure Synapse Analytics** y comparándolas con una máquina virtual local.

## Estructura del Repositorio

Este repositorio está organizado en dos directorios principales:

- **[data](https://github.com/Meusz/FinOps/tree/main/data)**: Contiene el dataset utilizado en el estudio. Este conjunto de datos es fundamental para las pruebas y análisis realizados en el trabajo.

- **[code](https://github.com/Meusz/FinOps/tree/main/code)**: Incluye los códigos y scripts desarrollados para la implementación de la arquitectura de big data y los modelos de IA en Python. Aquí encontrarás el código fuente, los scripts de procesamiento de datos y los análisis realizados.

## Objetivos del TFM

1. **Diseñar e Implementar una Arquitectura de Big Data**: Crear una infraestructura basada en Apache Spark para manejar grandes volúmenes de datos.
2. **Evaluar Configuraciones de Spark Pools**: Comparar el rendimiento y costo de diferentes configuraciones en **Azure Synapse Analytics** frente a una máquina virtual local.
3. **Desarrollar Modelos de Inteligencia Artificial**: Implementar y probar modelos de IA en Python para el análisis de datos.
4. **Optimización de Costos mediante FinOps**: Investigar cómo las prácticas FinOps pueden equilibrar la innovación tecnológica con la eficiencia financiera en la nube.

## Resultados

El estudio demostró que la arquitectura diseñada es:

- **Altamente adaptable** a diferentes entornos.
- **Escalable** para manejar grandes volúmenes de datos.
- **Eficiente** con tiempos de procesamiento aceptables que mejoran con la adición de nodos.

Las pruebas de rendimiento confirmaron que las configuraciones de nodos en Azure Synapse Analytics ofrecen un **balance** entre costo y rendimiento, proporcionando insights valiosos sobre el comportamiento del sistema.

## Futuro Trabajo

A partir de los resultados obtenidos, se proponen varias líneas de trabajo futuro, que incluyen:

- **Optimización Avanzada de Costos**: Explorar prácticas FinOps para mejorar aún más la eficiencia financiera.
- **Exploración de Proveedores de Nube Alternativos**: Evaluar otras opciones de infraestructura en la nube.
- **Ampliación de Conjuntos de Datos y Modelos**: Extender los datos y modelos utilizados en el estudio.
- **Evaluación del Impacto Ambiental**: Estudiar las implicaciones medioambientales de las soluciones en la nube.
- **Desarrollo de Herramientas de Gestión FinOps**: Crear herramientas para la gestión efectiva de FinOps en las organizaciones.

## Cómo Empezar

Para comenzar a trabajar con este proyecto, sigue estos pasos:

1. **Clona el Repositorio:**
   ```bash
   git clone https://github.com/Meusz/FinOps.git

