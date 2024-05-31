# Dokumentation für DokuWiki (SchoolLab)

Die Dokumentation vom Projekt [SchoolLab](https://webapp.schoollab.duckdns.org) läuft auf der Plattform [Vikis Wiki](http://10.76.31.241/doku.php?id=schoollab:welcome). Diese Plattform wird mithilfe docker-compose auf der internen Infrastruktur der Rudolf-Diesel-Fachschule in Nürnberg bereitgestellt.

## Setup

Damit man die Dokumentation loakl lesen kann, benötigt man zuerst folgende Pakete die installiert werden müssen.

### Linux

Befolge dazu dieses Tutorial um [Docker Engine](https://docs.docker.com/engine/install/ubuntu/)  und [Docker Compose](https://docs.docker.com/compose/install/linux/) erfolgreich zu installieren

- docker
- docker-compose

###  Windows

Unter Windows empfehlen Wir die Docker Desktop zu installieren, befolge das [diese Tutorial](https://docs.docker.com/desktop/install/windows-install/). 

## Docker Compose  Run

Mit diesem Befehl kann die Dokumentation mithilfe der Container-Technologie **docker** und **docker-compose** auf dem Server oder Lokal gestartet werden.

```Docker
docker-compose -f docker-compose.yaml up -d
```

## Docker Image

Das Docker [Image zu DokuWiki](https://hub.docker.com/r/linuxserver/dokuwiki) ist für jeden im Internet unter Docker Hub frei verfügbar.

