# Arquitectura del Proceso

Este proyecto implementa una arquitectura de automatización para mantener actualizado un dashboard de monitoreo de proyectos.

## Flujo general

Fiix genera actualizaciones de proyectos y envía un correo automático a Outlook con el asunto "Proyectos Actualizados".

Power Automate detecta la llegada del correo y ejecuta un flujo que actualiza un archivo de Excel almacenado en OneDrive.

Power BI consume este archivo como fuente de datos para mostrar un dashboard actualizado.

## Arquitectura

```text
Fiix → Outlook → Power Automate → OneDrive → Excel → Power BI
