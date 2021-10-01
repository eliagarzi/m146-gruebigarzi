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

**VPN für die Verbindung mehrerer Standorte**
Beispielsweise die Verbindung zwischen einer Cloud wie Azure und dem On-Premise Netzwerk oder eine Verbindung mehrerer kleiner Standorte. 

Site-To-Site



**VPN für das Umgehen von Geo-Blocking oder das täuschen der eigenen IP-Adresse**
Um Dienste aus anderen Ländern zu nutzen oder aus anderen Gründen

Point-To-Site und Public VPN-Provider / eigenen VPN-Server 



**VPN für die Verbindung in ein bestimmtes Netzwerk über eine gesicherte Verbindung** 
Ein Systemadministrator oder ein Benutzer braucht eine Sichere Verbindung zum Firmennetzwerk, um dieses auch von überall aus zu erreichen. 

**Hier braucht es eine Point-To-Site VPN mit privatem VPN-Server**. Beispielweise IPsec oder Wireguard. 


Begriffserklärung

- **Site-To-Site**: Site-To-Site bedeutet im Bezug auf VPNs, dass zwei damit zwei Netzwer