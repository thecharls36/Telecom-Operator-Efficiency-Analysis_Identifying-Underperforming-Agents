# Telecom Operator Efficiency Analysis: Identifying Underperforming Agents

## Descripción del Proyecto
Análisis integral del desempeño de operadores en el servicio de telefonía virtual CallMeMaybe, enfocado en identificar agentes ineficaces mediante el análisis de métricas clave como llamadas perdidas, tiempos de espera y volumen de llamadas. El proyecto utiliza técnicas de data science para desarrollar un sistema de clasificación que permita a los supervisores priorizar intervenciones y optimizar la gestión de recursos humanos.

## Objetivo General
Desarrollar un sistema analítico integral para identificar y clasificar operadores ineficaces en el servicio de telefonía virtual CallMeMaybe, mediante el análisis de métrices clave como llamadas perdidas, tiempos de espera y volumen de llamadas salientes, utilizando técnicas de análisis exploratorio, clustering y pruebas estadísticas para validar hipótesis de negocio y generar recomendaciones accionables que optimicen la gestión de recursos humanos y mejoren la experiencia del cliente.

## Datasets Utilizados

### **telecom_dataset_new.csv** (41,491 registros después de limpieza)
- `user_id`: ID de la cuenta de cliente
- `date`: Fecha de las estadísticas
- `direction`: Dirección de llamada (`in`/`out`)
- `internal`: Si la llamada fue interna (True/False)
- `operator_id`: Identificador del operador (1,092 únicos)
- `is_missed_call`: Si fue llamada perdida
- `calls_count`: Número de llamadas
- `call_duration`: Duración de la llamada (sin tiempo de espera)
- `total_call_duration`: Duración total (con tiempo de espera)

### **telecom_clients.csv** (732 registros)
- `user_id`: ID de usuario
- `tariff_plan`: Plan tarifario (A, B, C)
- `date_start`: Fecha de registro

## Contenido del Repositorio

| Ruta / Archivo                | Tipo        | Descripción                                                   |
|------------------------------|-------------|---------------------------------------------------------------|
| `Dashboard/`                 | Carpeta     | Recursos para el dashboard en Tableau                         |
| `Dashboard/dash_data_tableau.csv` | CSV   | Datos procesados para visualizaciones (exportados desde Python) |
| `Dashboard/Dashboard.twbx`   | Tableau     | Dashboard interactivo de análisis de operadores               |
| `Dashboard/Link dashboard.txt` | TXT       | Enlace público al dashboard en Tableau Public                 |
| `Informe Técnico.pdf`        | PDF         | Informe técnico con análisis detallado y conclusiones         |
| `ProyectoFinal.ipynb`        | Notebook    | Desarrollo completo del proyecto en Jupyter Notebook          |
| `README.md`                  | Markdown    | Descripción general del proyecto y guía de uso                |
| `telecom_clients.csv`        | CSV         | Datos de clientes y planes tarifarios                         |
| `telecom_dataset_new.csv`    | CSV         | Registros de llamadas y métricas de operadores                |
