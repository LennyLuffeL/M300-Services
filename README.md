# M300-Services
## LB02
### K1
Ich habe nach Anleitung Virtualbox, Vagrant, Visual Studio Code und Git-Client installiert.

VSCode und Git-Client mit SSH-Paar waren schon vorhanden

### K2
Github Account ist erstellt und Repository mit Herr Calisto geteilt.

Als Markdown-Editor wollte ich zuerst Sublime verwenden, aber es war schwierig die richtigen Add-ons zu finden.

### K3
Ich habe nach Anleitung einen Webserver erstellt und am schluss wieder zerstört.

Hier sind die wichtigsten Befehle:
| Befehl                    | Beschreibung                                                      |
| ------------------------- | ----------------------------------------------------------------- | 
| `vagrant init`            | Initialisiert im aktuellen Verzeichnis eine Vagrant-Umgebung und erstellt, falls nicht vorhanden, ein Vagrantfile |
| `vagrant up`              |  Erzeugt und Konfiguriert eine neue Virtuelle Maschine, basierend auf dem Vagrantfile |
| `vagrant ssh`             | Baut eine SSH-Verbindung zur gewünschten VM auf                   |
| `vagrant status`          | Zeigt den aktuellen Status der VM an                              |
| `vagrant port`            | Zeigt die Weitergeleiteten Ports der VM an                        |
| `vagrant halt`            | Stoppt die laufende Virtuelle Maschine                            |
| `vagrant destroy`         | Stoppt die Virtuelle Maschine und zerstört sie.                   |
