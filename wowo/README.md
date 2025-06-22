# Advanced Financial Intelligence Dashboard

Una plataforma web de código abierto para el análisis de datos financieros y macroeconómicos, construida con Python, Django y Docker.

## Sobre el Proyecto

El objetivo de este dashboard es proporcionar una herramienta interactiva y potente para visualizar y analizar la relación entre los mercados de acciones y los indicadores macroeconómicos. El proyecto está diseñado para ser modular, escalable y fácil de usar.

## Objetivos del MVP (Producto Mínimo Viable)

La primera versión funcional del proyecto se centrará en las siguientes características clave:

-   ✅ **Visualización de Activos:** Buscar un ticker de acción (vía Yahoo Finance) y mostrar su serie de precios histórica en un gráfico interactivo.
-   ✅ **Visualización de Indicadores Macro:** Seleccionar un indicador macroeconómico clave (vía FRED) y visualizar su serie histórica.
-   ✅ **Backend Robusto:** Implementar un backend con Django que sirva los datos a través de una API RESTful.
-   ✅ **Base de Datos Persistente:** Almacenar los datos extraídos en una base de datos PostgreSQL.
-   ✅ **Entorno Contenerizado:** Toda la aplicación funcionará dentro de contenedores Docker para un desarrollo y despliegue consistentes.

## Tech Stack

Para más detalles sobre las tecnologías utilizadas y el porqué de su elección, por favor consulta el archivo [`TECH_STACK.md`](./TECH_STACK.md).

## Puesta en Marcha (Próximamente)

_Esta sección contendrá las instrucciones detalladas para levantar el entorno de desarrollo localmente._

## Hoja de Ruta (Roadmap)

-   [ ] **Fase 0-5:** Desarrollo y lanzamiento del MVP.
-   [ ] **Post-MVP:**
    -   Análisis econométrico (tests de estacionariedad, ACF/PACF).
    -   Módulo de gestión de portafolios personales.
    -   Sistema de alertas.
    -   Integración con IA para consultas en lenguaje natural.
