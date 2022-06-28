# nginx-nextcloud

Despliegue de servicios nginx-proxy-manager, nginx, nextcloud y mariadb

## Instalar dependencias
```bash 
# apt update
# apt install docker.io docker-compose
``` 

## Cloná el repo y hace deploy
```bash 
# git clone https://github.com/agora-informatica/nginx-nextcloud
# cd nginx-nextcloud
# docker-compose up -d
``` 
- Ir a **http://<server_ip>:81** para gestión de virtual host.
- user: admin@example.com
- pass: changeme
- Done 🎉