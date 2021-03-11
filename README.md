# M300-Services

## M300 - 10 Toolumgebung 

In diesem Kapitel haben wir unsere Umgebung eingerichtet. Dabei mussten vor allem Tools installiert und konfiguriert werden. Folgende Schritte wurden bei diesem Kapitel durchgeführt: 
* Github Account und Repository erstellt
* SSH Key erstellt
```Shell
      $  ssh-keygen -t rsa -b 4096 -C "moseryanick@gmail.com"
```
* SSH Key dem SSH-Agent hinzugefügt
* Git Cient installiert und repository auf lokalen PC geklont
* Ununtu VM eingerichtet
* Vagrant installieren
* VM mit Vagrant erstellen
* Apache Webserver automatisch aufgesetzt mit Vagrant
* Visual Studio Code und Extensions installiert
* Repository hinzugefügt und gepusht


## M300 - 20 Infrastruktur-Automatisierung

In diesem Kapitel ging es vor allem um die Theorie. Als ich die Theorie fertig hatte habe ich mit der Dokumentation im MD format angefangen.

## Vagrant VM

### Konfiguration

* Vagrant Box: ubuntu/xenial64
* VM Provider: Virtual Box
* Hostname: ubuntu-xenial
* CPU Cores: 2
* Ram: 512MB
* Massenspeicher: 40GB
* Installierte Programme: Apache2
* IP Adresse: 10.0.2.2

### Netzwerkplan 

![Netzwerkplan](https://user-images.githubusercontent.com/78543849/110806039-f653a100-8281-11eb-946c-d3cadadc01b0.png)


## Testing der Vagrant VM


### Apache2 Web Server mit anderem Port
![Screenshot Apache2](https://github.com/Yaniqueee/M300-Services/blob/main/Screenshot%202021-03-11%20142645.png)

### Apache2 Web Server änderungen im index.html
![Screenshot änderung Apache2](https://github.com/Yaniqueee/M300-Services/blob/main/Screenshot%202021-03-11%20152331.png)

### Portforwarding
![Screenshot Portforwarding](https://github.com/Yaniqueee/M300-Services/blob/main/Screenshot%202021-03-11%20152723.png)


