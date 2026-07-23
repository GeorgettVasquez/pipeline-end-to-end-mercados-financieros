# Dise-o-e-implementaci-n-de-un-pipeline-de-precios-de-acciones-y-datos-macroeconomicos
El proyecto consiste en el diseño e implementación de un pipeline de datos End-to-End para
la ingesta, almacenamiento, procesamiento y visualización de precios de acciones bursátiles
combinados con indicadores económicos geoespaciales por región o país. El sistema
permitirá analizar el comportamiento de los mercados financieros en correlación con
métricas macroeconómicas georeferenciadas, habilitando consultas espaciales sobre la
distribución global de indicadores como PIB, inflación, tasa de desempleo e índices
bursátiles por país.

**Tecnologías utilizadas: Docker, Mage AI, FastApi, Streamlit**
Apis utilizadas: Alpha vantage, yahoo finance y banco mundial

_1. docker para poder compartirlo sin que existan daños en las versiones con otras personas_
_2. Mage Ai para los pipelines y conexión de la base de datos_
_3. fastApi para extraer las consultas importantes de una manera más rapida y fácil_
_4. Streamlit para la visualización de dashboard y las consultas_


Para ver la creación descargan el, archivo, lo corren con Docker compose up 
y corren estas url

Mage AI: http://localhost:6789
FastAPI (docs): http://localhost:8000/docs
Streamlit: http://localhost:8501

Proyecto elaborado en conjunto con Tómas Jaramillo y Georgett Vásquez.
