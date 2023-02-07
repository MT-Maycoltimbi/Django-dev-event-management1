pasos para crear el contenedor

1. crear red si no existe:
   docker network create network-docker-proyect

ejecute los siguientes comando:
--Crear el la imagen--

        docker-compose build --no-cache

--Levantar el servicio--

        docker compose up
