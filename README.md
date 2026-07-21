# Automatización de Reportes de Proyectos con Power Automate y Power BI

Este proyecto consiste en el desarrollo de una solución automatizada para el monitoreo de proyectos utilizando Power Automate, Outlook, OneDrive, Excel, Power BI y Fiix.

El objetivo principal es mantener un dashboard actualizado con información sobre proyectos activos, proyectos finalizados, nuevos proyectos, direcciones y porcentaje de avance de cada proyecto.

## Objetivo

Automatizar la actualización de información de proyectos para reducir intervención manual, mejorar la disponibilidad de datos y facilitar el monitoreo mediante un dashboard en Power BI.

## Tecnologías utilizadas

- Fiix
- Outlook
- Power Automate
- OneDrive
- Excel
- Power BI
- Microsoft 365

## Funcionamiento de la solución

El flujo automatizado inicia cuando Fiix envía un correo automático a Outlook con el asunto "Proyectos Actualizados".

Power Automate monitorea la llegada de este correo y, cuando detecta el asunto configurado, ejecuta un proceso que reemplaza automáticamente el contenido de un archivo de Excel almacenado en OneDrive.

Este archivo de Excel funciona como fuente de datos para Power BI. De esta manera, el dashboard se mantiene sincronizado con la información más reciente de los proyectos.

## Flujo del proceso

```text
Fiix
  ↓
Outlook
  ↓
Power Automate
  ↓
OneDrive
  ↓
Excel
  ↓
Power BI
  ↓
Dashboard de Proyectos
