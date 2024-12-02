# Windows-Http-Server
Windows-Server

Dieses Projekt implementiert einen einfachen HTTP-Server, der Anfragen auf einem lokalen Host entgegennimmt und beantwortet. Der Server wird mit `HttpListener` in VB.NET betrieben und kann auf verschiedenen Ports laufen.

## Funktionen
- Startet einen HTTP-Listener auf einem freien Port (standardmäßig Port 80 oder 8080).
- Stoppt einen laufenden Server, wenn der Listener bereits aktiv ist.
- Verarbeitet HTTP-Anfragen und gibt benutzerdefinierte Fehlerseiten zurück.
- Bei 404-Fehler kommt eine Fehlerseite.

## Web-Befehle
- http://localhost:8080/server-off
- http://localhost:8080/server-info
- http://localhost:8080/server-reboot

## Installation

1. Klone das Repository:
   ```bash
   git clone https://github.com/xeonios-studio/server/Server.git
