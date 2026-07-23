# Pipeline End-to-End para Análisis de Mercados Financieros

## Descripción

Este proyecto consiste en el diseño e implementación de un **pipeline de datos End-to-End** para la ingesta, almacenamiento, procesamiento y visualización de precios de acciones bursátiles, combinados con indicadores económicos geoespaciales por región o país.

El sistema permite analizar el comportamiento de los mercados financieros en correlación con métricas macroeconómicas georreferenciadas, habilitando consultas espaciales sobre indicadores como el **PIB**, la **inflación**, la **tasa de desempleo** y los **índices bursátiles** de distintos países.

## Tecnologías utilizadas

- Docker
- Mage AI
- FastAPI
- Streamlit
- PostgreSQL + PostGIS

## APIs utilizadas

- Alpha Vantage
- Yahoo Finance
- World Bank API (Banco Mundial)

## Función de cada tecnología

- **Docker:** Permite ejecutar el proyecto en cualquier equipo manteniendo el mismo entorno y evitando problemas de compatibilidad entre versiones.
- **Mage AI:** Implementa los pipelines de extracción, transformación y carga (ETL), además de la integración con la base de datos.
- **FastAPI:** Expone una API REST para realizar consultas de manera rápida y eficiente.
- **Streamlit:** Proporciona una interfaz interactiva para la visualización de dashboards y consultas.
- **PostgreSQL + PostGIS:** Almacena la información financiera y geoespacial, permitiendo realizar consultas espaciales.

##  Ejecución del proyecto

1. Descargar o clonar el repositorio.
2. Ubicarse en la carpeta del proyecto.
3. Ejecutar el siguiente comando:

```
docker compose up 
```

4. Una vez iniciados los servicios, acceder a las siguientes direcciones desde el navegador:

- **Mage AI:** http://localhost:6789
- **FastAPI (Documentación Swagger):** http://localhost:8000/docs
- **Streamlit:** http://localhost:8501

## Autores

Proyecto elaborado por:

- **Georgett Vásquez**
- **Tómas Jaramillo**
