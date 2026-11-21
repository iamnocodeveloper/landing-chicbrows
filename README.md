# landing-chicbrows

Landing de demostración para **Chic Brows — estudio de belleza** (Cuenca, Ecuador).
Estudio de cejas y pestañas: laminado, diseño y perfilado, henna, micropigmentación,
extensiones de pestañas, lifting, depilación con cera y tratamientos faciales.

Sitio estático de una sola página (`index.html`, CSS y JS inline), mobile first, con:

- Portada elegante del estudio con la valoración pública real (4.8 de 5 con 108 reseñas en Google)
- Servicios con descripción y duración estimada de cada uno
- **Reserva de cita en línea interactiva**: servicio → día → horario → confirmación con
  duración, datos de la clienta y botón de WhatsApp con el resumen precargado
- Sección de WhatsApp con simulación de respuestas automáticas a las consultas más repetidas
- Recordatorios automáticos (al reservar, 24 h antes y el mismo día)
- Reseñas resumidas por temas recurrentes, sin citas ni nombres inventados
- Ubicación, mapa de referencia y accesos directos a WhatsApp (+593 98 739 4521)

## Enfoque de la propuesta

No se plantea reemplazar el sitio actual del estudio, sino sumar lo que hoy no tiene:
**reserva de citas en línea** y **atención automatizada por WhatsApp** (respuestas listas,
confirmaciones y recordatorios para reducir citas caídas).

## Despliegue

Se construye con un `Dockerfile` de dos líneas (`nginx:alpine` + copia de los archivos)
y se publica en EasyPanel desde este repositorio.

## Nota

Sitio de referencia hecho por Nocodeveloper. Los textos, duraciones y la disponibilidad
mostrada son de demostración; para la versión final se usan las fotos, precios y horarios
reales del estudio. Las imágenes son de Unsplash (uso libre).