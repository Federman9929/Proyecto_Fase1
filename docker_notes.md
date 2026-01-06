## Qué es Docker?

Docker es una plataforma que permite empaquetar una aplicación + sus dependencias + su configuración en una unidad aislada llamada contenedor.

## Diferencias entre contenedor y VM

Las máquinas virtuales (VMs) virtualizan hardware, incluyendo su propio SO completo, ofreciendo aislamiento total y más recursos, pero son pesadas y lentas de iniciar; mientras que los contenedores virtualizan el SO, compartiendo el kernel del host, son ligeros, portátiles, rápidos de iniciar y usan menos recursos, ideales para microservicios, aunque con menos aislamiento

## Comandos usados

sudo docker run hello-world
sudo docker run -d -p 8080:80 nginx
docker ps            # contenedores activos
docker ps -a         # todos
docker images        # imágenes
docker stop <id>     # detener contenedor
docker rm <id>       # eliminar contenedor
docker rmi <id>      # eliminar imagen


