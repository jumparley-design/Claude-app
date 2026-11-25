# Barbería Agenda (app de prueba)

App web de un solo archivo (`index.html`) para gestionar una barbería. No requiere instalación ni servidor: ábrela en cualquier navegador (computadora o teléfono).

## Funciones
- **Agenda**: vista por día con tira semanal, filtro por barbero, huecos libres, estados (pendiente, confirmada, completada, cancelada, no asistió).
- **Citas**: alta y edición con cliente nuevo o existente, servicio (duración y precio), barbero, fecha, hora y notas. Valida horario de apertura y avisa de choques de horario.
- **Recordatorios**: por cita (15 min a 1 día antes). Con la app abierta muestra un aviso en pantalla con sonido y, si das permiso, una notificación del sistema. Botón "Mensaje" con texto listo para WhatsApp.
- **Alertas**: citas próximas, sin confirmar, sin cerrar, choques de horario y clientes que no vuelven hace 30+ días. Historial de eventos.
- **Clientes**: búsqueda, teléfono, preferencias, visitas, total gastado, última y próxima cita.
- **Ajustes**: servicios, barberos (con color), horario y nombre del negocio.
- **Almacenamiento**: los datos se guardan en el navegador (localStorage). Exporta/importa respaldos en JSON.

Incluye datos de ejemplo; "Restablecer datos" en Ajustes los vuelve a cargar.

## Limitaciones de esta versión de prueba
- Los datos viven en un solo dispositivo/navegador (no se comparten entre barberos).
- Los recordatorios solo suenan mientras la app está abierta; no se envían SMS/WhatsApp automáticos.
