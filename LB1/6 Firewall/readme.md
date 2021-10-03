# Leitfragen zum Thema Firewall

## **Ausgangslage**

Ein Unternehmen hat einen veralteten Internetzugang mit einer Übertragungsrate von 50 Mbit/s im Download und 5 Mbit/s im Upload mit ADSL. Die Firma produziert Kaffeemaschinen in einer städtischen Gegend in der Schweiz. Das Marketing benutzt moderne Webapplikationen mit viel Multimediaanwendungen und ein Shop für Endkunden ist ebenfalls vorhanden. Alle Mitarbeiten-den benutzen Mail und Browserapplikationen. Die Firma hat 90 Internetnutzer.

Eine Firewall ist nicht vorhanden und die Server stehen alle beim Provider.

## **Aufgabe**

Vergleichen Sie für einen Internetanschluss folgende Firewall-Lösungen:  

• Günstige Hardware-Firewalls (Cisco-ASA, Zyxel Zywall oder ähnliche) 
• PC-Lösung mit Linux 
• Firewall-Service des Providers. 

Welche Vergleichskriterien finden Sie, welche sind für welche Einsatzfälle wie wichtig? 

Ich finde sehr viele Kriterien, welche wichtig sind. Firewalls werden für die unterschiedlichsten Zwecke eingesetzt und somit gibt es auch für viele verschiedene Lösungen. 

- Form
- Kosten
- VPN
- VPN Durchsatz
- Pakete pro Sekunde
- Gleichzeitige Verbindungen
- Durchsatz
- IPS-Durchsatz
- SSL-Inspection Durchsatz

Nun habe ich verschiedene "Typische Fälle" angeschaut und dafür eine mögliche Lösung angeschaut.

**Heimnetzwerk**
Gesuchte Firewall
- Unkompliziert 
- Durchsatz von bis zu 1 Gbit/s


**Firmennetzwerk**
Ein Firmennetzwerk bedeutet für mich 


Gesuchte Firewall
- Unkompliziert 
- Durchsatz von bis zu 1 Gbit/s


**Verbindung mit dem Firmennetz von Zuhhause aus**

**Kleiner Bürostandort ohne On-Premise Serverinfrastruktur**

**Distaster Recovery Site**

Ein Rechenzentrum benötigt vor allem eines: Site-To-Site VPN. 


Gesuchte Firewall
- Viele Rules
- IDS 
- IPS 
- Durchsatz von bis zu 1 Gbit/s