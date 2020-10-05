# Serviio

**NOTES:** Works only in GNU/Linux operating system.

## Install

* Download the latest release [serviio-2.1-linux.tar.gz](https://download.serviio.org/releases/serviio-2.1-linux.tar.gz);
* Extract to ``docker/volumes/serviio`` folder;

## Run Serviio

Run command:
```
docker-compose up -d --build
```

## Configure

### Network settings

* Navigate to ``http://<computer ip address or host>:23423/console/#/app/status``;
* Setup Network *Settings > Bound IP address* to host/computer IP address;
* Save settings;
* Stop and Start server.

## Shared folders

* Add media files to ``docker/volumes/media`` directory;
* Navigate to ``http://<computer ip address or host>:23423/console/#/app/library/local`` and select folders that you want to share and monitor for media files.

## Links

* https://serviio.org/
* https://docs.docker.com/engine/install/ubuntu/
* https://wiki.serviio.org/doku.php?id=howto:linux:install:ubuntu18-04
