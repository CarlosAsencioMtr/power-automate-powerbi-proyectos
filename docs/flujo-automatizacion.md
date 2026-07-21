# Flujo de Automatización

Este documento describe el flujo automatizado desarrollado con Power Automate.

## 1. Generación del correo

Fiix envía automáticamente un correo a Outlook cuando ocurre una modificación en el registro de proyectos.

## 2. Detección del correo

Power Automate monitorea la bandeja de entrada de Outlook y valida si el asunto del correo contiene:

```text
Proyectos Actualizados

## 3. Actualización del archivo

Cuando se detecta el correo, Power Automate reemplaza o actualiza el contenido del archivo Excel almacenado en OneDrive.

## 4. Actualización de fuente de datos

El archivo Excel queda actualizado con los proyectos vigentes, nuevos registros y proyectos que continúan activos.

## 5. Visualización en Power BI

Power BI utiliza el archivo de Excel como fuente de datos para actualizar el dashboard de monitoreo de proyectos.

 ## Resultado

El proceso permite que la información del dashboard se mantenga sincronizada con los cambios provenientes de Fiix.
