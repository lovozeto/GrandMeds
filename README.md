# MedSchedule PWA - Gestión de Medicamentos para Cuidadores

App web progresiva (PWA) construida con React y Framework7 para que cuidadores puedan gestionar el horario de medicamentos de personas mayores.

## Características

- Listado estático de medicamentos con detalles y horarios.
- Visualización diaria con agrupación por hora y prioridad.
- Configuración de temas (claro, oscuro, automático).
- Notificaciones programadas y suscripción a calendario iCloud.
- Offline-first con Service Worker y cacheo inteligente.
- Compatible iOS, Android, tablets y escritorio.
- Accesibilidad y diseño UX adaptado para personas mayores.

## Estructura del proyecto

- `/public` – Archivos estáticos, manifest, icons, service worker.
- `/src` – Código fuente modular: componentes, páginas, servicios, utilidades.
- Configuración para despliegue en GitHub Pages usando Vite.

## Instalación y ejecución local

```bash
npm install
npm run dev