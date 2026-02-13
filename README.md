# mattermost
Mattermost - Colaboración segura para equipos técnicos - Docker compose

## Ejecutar estos comandos antes de instalar la app:
```
mkdir -p /opt/docker/mattermost && cd /opt/docker/mattermost
```
```
 mkdir -p /opt/docker/docker_data/postgresql/data && mkdir -p /opt/docker/docker_data/mattermost/{config,data,logs,plugins,client/plugins,bleve-indexes}
```
```
chmod -R 777 /opt/docker/docker_data/mattermost/config
```
```
exit
```
## Instalamos la app con estos comandos:
```
git clone https://github.com/mclitos/mattermost
```
```
cd mattermost
```
## Editamos el .env si es para produccion cambiamos variables de seguridad y ip del servidor si es necesario 
```
nano .env
```

```
docker-compose up -d
```

