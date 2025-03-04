Descargar el proyecto entero
Una vex descargado ubicarse donde el archivo docker-compose.yaml se ubique ejecutar el comando 
docker-compose up -d --build este empezará la instalación de todo el docker-compose
Para conectarse a la consola de psql
Paso 1 encontrar el docker-compose que contiene la BBDD
ejecutamos docker-compose ps -a y buscamos el que tenga postgres
Paso 2 entrar al contenedor usando docker-compose exec -it nombre_dc_bbdd bash
para poder interactuarcon la BBDD
Paso 3 entrar a la BBDD mediante el comando psql -U postgres -d torneigdb
y accederá si pidese pw sería postgres
acceder por ssh a developer
deberemos acceder por ssh dentro del mismo contenedor
