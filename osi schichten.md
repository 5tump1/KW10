### DAS OSI MODELL

> Wenn der User etwas nicht hinbekommt, spricht man con einem Layer 8 Problem.

## 1 Physical Layer
Netzwerkkarte
Start und Stop-Signale
DEfiniert die elektrische, mechanische und funktionelle schnittstelle zum Übertragungsmedium
PRotokolle unterscheiden sich nach Medium (Kabel, Wireless...)
MEdium selber ist nicht Teil der Schicht 1
Hardware: Repeater, Hubs, 


## 2 Data Link

Datenflusskontrolle, Fehlerkorrektur, Fehlerbehebung
Physikalische Adressierung von Datenpaketen
Protokolle:
- MAc (MEdia Access Control)
- ARP ( Adresss Resolution Protocol)
- LLC (Logical Link Control) IEEE 802.2
- IEEE 802.1 (WLAN)

## 3 Network / Vermittlungsschicht
Datentransfer - das gesamte Netzwerk
Datenflusskontrolle
zeitlich und logische Kommunikation
Erstmalig die logische ADressierung der Endgeräte.
Wegfindung -/ Routing / Netzwerkknoten / Routingtabellen
Protokolle:
- IP (Internet PRotokoll)
- IPSec (Internet Protocol Security)
- ICMP (Internet Control Message Protocol)

## 4 Transport Layer
Logische End-to-End
Transportschicht ist die Verbindung zwischen transportorientiert und anwendungsorientierten Schichten.
Datenpakete werden Applikationen/Anwendungen zugeordnet.
Sicherstellung der fehlerfreien Übertragung - Segmentierung des Datastreams / Datenstroms

Protokolle:
- TCP (Transmission Control Protocol)
- UDP (User Datagram Protocol)

## 5 Session Layer / Kommunikationsschicht
Prozess zu Prozess
Dienste für den organisierten und synchronisierten Datenaustausch
Checkpoint Prinzip
Organisation zwischen den Endsystemen - Steuerungs und KOntrollechanismen für Datenaustausch.

Prtokolle:
- HTTP (Hypertext Transfer Protocol)
- HTTPS (Hypertext Transfer Protocol Secure)
- SMTP (SImple Mail Transport Protocol)
- FTP (File Transport Protocol)

## 6 Darstellungsschicht / Presentation Layer
Dienste, ANwednungen und Netzmanagement.
Wandelt Daten in Codec und Formate um.
Daten werden von oder zu der Anwendungsschicht in ein geeignetes Format umgewandelt.
Datenkompression / Verschlüsselung

Protokolle:
- SSL (Secure Socket Layer)
- SSH (Secure Shell)
- IMAP (Internet Message Access PRotocol)
- (S)FTP ((Secure)File Transport Protocol)
- 

## 7 Applicaion Layer / Anwednungsschicht
I/O Schicht (Input und Output)
Stellt funktionen für die Anwedungenn zur verfügung.
Verbindung zu den unteren Schichten
Applikatinen selbst gehören nicht zu der Schicht
- Browser
- Chat
- Mailprogramm
- etc....