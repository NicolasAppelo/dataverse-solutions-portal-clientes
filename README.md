# Dataverse Solutions — Portal Clientes

Dashboard de seguimiento de proyectos para Dataverse Solutions.

## Funcionalidades

- **Login por contraseña**: acceso de administrador (vista completa + edición) y acceso por cliente (solo lectura del proyecto asignado).
- **Vista del proyecto**: progreso total, hitos completados, número de módulos y avance por módulo.
- **Línea de tiempo**: desde firma de contrato hasta entrega estimada, con marcador "Hoy", hitos posicionados por fecha y código de colores por responsable (Dataverse Solutions / Cliente). Indica automáticamente si el proyecto está a tiempo o con retraso y desglosa los hitos vencidos por responsabilidad.
- **Panel de administración**: alta/edición/eliminación de módulos y milestones, asignación de responsable por milestone, edición de fechas de contrato y entrega, y creación de nuevos clientes/proyectos con contraseña propia.

## Uso

Abre `index.html` en cualquier navegador moderno. Credenciales por defecto (se pueden cambiar editando el objeto `CONFIG` dentro del archivo):

- Admin DVS: `dvs2025`
- Cliente NULAB: `nulab2025`
- Cliente Escuela del Amor: `amor2025`

## Publicación

Este repositorio está configurado para servirse vía GitHub Pages desde la rama `main`.

---

© Dataverse Solutions SL · dvs.ai
