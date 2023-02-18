# Docker-Electiva2
A continuación están realizadas las primeras practicas asignadas por el maestro Elvys Cruz de la materia Electiva 2.

Instituto Tecnológico de las Americas ITLA

* Luis Manuel Orozco 2019-8854


Clase 2.- Introduccion a aplicaciones con Docker

1.- Instalar docker 

2.- Ejecutar Hello-World

// ejecutar
$ docker run hello-world

// descargar un app desde docker hub
$ docker pull httpd

// ver contenedores ejecutando
$ docker ps 
$ docker ps -a
 1
// iniciar un contenedor ya creado
$ docker start <nombre>

// detener contendor
$ docker stop <nombre>

## Crear siempre archivo docker-compose.yml 

// Para subir aplicaciones
docker compose up 

// Para bajar aplicaciones
docker compose down
 
Practica1:

Crear un archivo docker-compose.yaml para correr las siguientes aplicaciones en docker:

Una aplicación python
Una base de datos posgtres
