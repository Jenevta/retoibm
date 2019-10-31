# retoibm
Implementacion de una prueba técnica sobre devops

Se desplego mediante docker-compose 2 contenedores, uno referente a un API REST que ejecuta una suma y el otro contenedor con 
nginx que actua como reverse proxy exponiendo en este caso la direccion de 127.0.0.1/app como conexion al API. 
Se coloco un healthcheck dentro de este docker compose para monitorear al API Rest. 



