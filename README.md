# Sistema de Reserva de Equipos — Laboratorio ProDevs - AMTC - Universidad de Chile

Sistema digital de gestión y disponibilidad de equipos analíticos, desarrollado sobre Google Workspace.

## ¿Cómo funciona?

Cada equipo del laboratorio cuenta con un código QR que dirige al usuario a un formulario de solicitud. Una vez enviada, el administrador aprueba o rechaza la solicitud. El solicitante es notificado automáticamente del resultado y, en caso de aprobación, el bloqueo horario queda registrado en el calendario compartido del laboratorio.

## Equipos registrados

| Equipo | Parámetro |
|--------|--------|
| MasterSizer | | 
| Microscópio Óptico | | 
| XRF | |

## Archivos

| Archivo | Descripción |
|---------|-------------|
| `index.html` | Página pública de disponibilidad semanal |
| `codigo_apps_script.gs` | Script de Google Apps Script (notificaciones y aprobaciones) |
| `etiquetas_qr.html` | Generador de etiquetas QR imprimibles por equipo |

