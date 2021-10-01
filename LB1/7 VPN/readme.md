# Leitfragen zum Thema VPN

**Ausgangslage**
***
Ein Unternehmen hat einen veralteten Internetzugang mit einer Übertragungsrate von 50 Mbit/s im Download und 5 Mbit/s im Upload mit ADSL. Die Firma produziert Kaffeemaschinen in einer städtischen Gegend in der Schweiz. Das Marketing benutzt moderne Webapplikationen mit viel Multimediaanwendungen und ein Shop für Endkunden ist ebenfalls vorhanden. Alle Mitarbeiten-den benutzen Mail und Browserapplikationen. Die Firma hat 90 Internetnutzer.

Eine Firewall ist nicht vorhanden und die Server stehen alle beim Provider.


## **Aufgabe**

Vergleichen Sie folgende VPN-Lösungen für ihren Internetanschluss:  

• Hardwarelösung (Cisco-ASA oder Ähnliches) 
• VPN-Service des Providers 
• PC-Lösung mit Windows und Linux.  

Welche Vergleichskriterien finden Sie, welche sind für welche Einsatzfälle wie wichtig? 

Diskutieren Sie einige „typische Fälle“ und vergleichen Sie. 

Vergleichskriterien
- Kosten
- Durchsatz
- IPS-Durchsatz
- Ports
- Bauform


## **Typische Fälle**

Anschliessend habe ich mir Gedanken über "Typische Fälle" bei VPN-Verbindungen gemacht. 


**VPN für die Verbindung mehrerer Standorte**
Beispielsweise die Verbindung zwischen einer Cloud wie Azure und dem On-Premise Netzwerk oder eine Verbindung mehrerer kleiner Standorte. 

Wichtig für diesen Fall:
- Site-To-Site VPN 
- Hoher Durchsatz

Für solch eine Verbindung braucht es eine Site-To-Site VPN. Man braucht dafür zwei Endpunkte, welche eine Site-To-Site VPN zulassen. Z.B. einen Azure VPN Gateway mit einer physischen Firewall. 



**VPN für das Umgehen von Geo-Blocking oder das täuschen der eigenen IP-Adresse**
Um Dienste aus anderen Ländern zu nutzen oder aus anderen Gründen

Point-To-Site und Public VPN-Provider / eigenen VPN-Server 



**VPN für die Verbindung in ein bestimmtes Netzwerk über eine gesicherte Verbindung** 
Ein Systemadministrator oder ein Benutzer braucht eine Sichere Verbindung zum Firmennetzwerk, um dieses auch von überall aus zu erreichen. 

**Hier braucht es eine Point-To-Site VPN mit privatem VPN-Server**. Beispielweise IPsec oder Wireguard. 


Begriffserklärung

- **Site-To-Site**: Site-To-Site bedeutet im Bezug auf VPNs, dass damit zwei Netzwerke verbunden werden können. So kann ein externes Rechenzentrum oder ein externer Standort mit dem Firmennetzwerk verbunden werden. Die wird über den Router/die Firewall realisiert. 

- **Point-To-Site / Client-To-Site**: Bei einer Client-To-Site VPN wird nur ein Client mit dem VPN-Netzwerk verbunden. Hierfür wird ein VPN-Client auf Z.B. Windows installiert. 

- **VPN-Peers**: Ein VPN-Peer ist ein "Client". Die maximale Anzahl Peers bestimmt also, wieviele  Clients gleichzeitig mit dem VPN verbunden sein können. 