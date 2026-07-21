# Flujo de Automatización

Este documento describe el flujo automatizado desarrollado con Power Automate.

## 1. Generación del correo

Fiix envía automáticamente un correo a Outlook cuando ocurre una modificación en el registro de proyectos.

## 2. Detección del correo

Power Automate monitorea la bandeja de entrada de Outlook y valida si el asunto del correo contiene:

```text
Proyectos Actualizados
