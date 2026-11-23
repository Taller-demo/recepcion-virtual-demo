# Recepción virtual para talleres · demo

Página de demostración de una recepcionista virtual para talleres mecánicos. Cuando el taller está cerrado, una asistente de voz coge la llamada y apunta los datos del cliente. A las 7:00 el taller recibe un correo con todas las llamadas de la tarde, las urgentes primero.

**Verla:** https://borisdevops.com/recepcion-virtual-demo/

## Qué hay en la página

- Cinco llamadas de ejemplo con voz sintética. Mientras suenan, la ficha del aviso se rellena sola.
- Las reglas que deciden si una llamada es urgente.
- El resumen de la mañana en tres formatos: correo, Excel y WhatsApp.

El taller, los clientes y los teléfonos son inventados. El correo funciona en el sistema real; el Excel y el WhatsApp están diseñados pero no montados.

## Ejecutarla en local

Es un único `index.html`, sin dependencias. Abre el archivo con doble clic, o:

```bash
python3 -m http.server 8000
```

y entra en http://localhost:8000.
