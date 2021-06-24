# homebridge-installer
Dieser schlanke Installer installiert [https://homebridge.io/](Homebridge) auf einem Raspberry Pi. 
**Es wird die Standardinstallation ausgeführt, nur automatisiert.**

Es **muss** ein Raspian Betriebssystem auf dem Pi laufen, ein Ubuntu habe ich noch nicht getestet.

[https://makesmart.net/makesmart-server-installieren/](Anleitung zum Installieren eines passenden Betriebssystems) 

Um Homebridge zu installieren setze nacheinander folgende Befehle in der Konsole ab:

### 1. Installer herunterladen
```shell
wget https://raw.githubusercontent.com/makesmartnet/homebridge-installer/master/start.sh
```

### 2. Installer ausführen
```shell
bash start.sh
```

#### Nach der erfolgreichen Installation kann der Installer wieder gelöscht werden:
```shell
rm start.sh
```

Start with your makesmart Home!
