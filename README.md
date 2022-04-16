# ejercicio-ss

To Do List, este pequeño servicio web permite agregar tareas en las cuales deberemos indicar los siguientes parámetros: nombre, descripción,  prioridad, tipo y su estado (pendiente, finalizado, en proceso, etc), también es posible modificar una tarea, mostrar todas las tareas, eliminar alguna tarea y obtener el total de tareas registradas.

***
### comando para descargar la imagen de Docker Hub: 
docker pull jairvr/ejercicio-ss
### La imagén esta configurada para iniciar el servicio al ejecutar la imagen, de igual forma adjunto el comando para ejecutar el servicio web: 
docker run -it --rm -p 8080:8080 jairvr/ejercicio-ss
