# SEW / PLF 1

## Stoffumfang

- Netzwerkprogrammierung mit Sockets
  - [Datenübertragung: Text, Binär, Objekte](Sockets_Datenuebertragung.md)
  - Protokollimplementierung (frei bzw. nach Vorlage)
  - Information auslesen über Socket (Lokal + Remote)

- Server
  - [mehrere, gleichzeitige Verbindungen](Server_Verbindungen.md)
  - Multithreading (inkl. Absicherung)
  - [zentrale Verwaltung von Ressourcen (Daten, Collections, Dateien, ...)](Server_Ressourcen.md)

- Client
  - Konsolenclient
  - JavaFX Client mit Mulithreading zur Kommunikation (sprich: Tasks,Services) und somit auch Properties und Bindings
  - Achtung bei Bindings: Properties können nicht serialisiert werden - da muss man sich selbst drum kümmern (vgl. Folien)

- [Properties](Properties.md)

## Projekte

- [Fileserver](https://github.com/crumpfhuber/htlw4-sew-plf1/tree/fileserver)
- [Socket-Chat](https://github.com/crumpfhuber/htlw4-sew-plf1/tree/socket-chat)
