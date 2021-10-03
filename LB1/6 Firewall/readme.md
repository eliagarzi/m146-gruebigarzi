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


## **1 Vergleich**

### **Vergleich verschiedener Firewall-Lösungen**

Ich habe mir vier völlig verschiedene Firewall-Lösungen angeschaut. 

**Opnsense**

Opnsense ist eine Open-Source Firewall, die ebenfalls Routing Funktionen unterstützt. Opnsense ist kostenlos, nur der Support kostet. 

**Azure Firewall**

Die Azure Firewall ist ein "Firewall-as-a-Service" von Microsoft. Diese Firewall läuft nur auf der Azure Cloud. 
Azure Firewall wird dazu gebraucht um Azure Netzwerkressourcen zu schützen. 


**Fortigate 80F**

Die Foritgate 80F ist einer der kostengünstigsten Fortigate Firewalls. Sie richtet sich an KMU, welche volle Kontrolle über ihre Firewall haben möchten. 


**Managed Security von Swisscom**

Managed Security von Swisscom ist eine "Firewall-as-a-Service". Managed Security ist cloud-basiert und richtet sich in erster Linie an KMU mit kleinem Budget. 

In der nachstehenden Grafik habe ich mir die verschiedenen Firewall-Lösungen von oben angeschaut und dabei festgehalten, welche Kriterien wichtig sind. 

![grafik](https://user-images.githubusercontent.com/62818267/135764327-db83e5b3-5ba0-44d6-b573-50f37db269c5.png)


### **Kriterien**
Aus der Grafik von oben habe ich folgende Kriterien mitgenommen. Ich fand eine sehr schwierige Aufgabe, da es so viele verschiedene Firewalls gibt und diese auch an den verschiedensten Orten zu verschiedensten Zwecken eingesetzt werden. Ich habe dennoch bestmöglichst versucht, sinnvolle Kriterien herauszufiltern. 

- Form
- Standort
- Einsatzbereich
- Anschaffungskosten
- Laufende Kosten
- Support 
- VPN
- VPN Durchsatz (Gbit Max)
- Durchsatz (Gbit Max)
- Antivirus
 

## **2 Typische Fälle**
Nun habe ich verschiedene "Typische Fälle" angeschaut und dafür eine mögliche Lösung angeschaut.

### **Heimnetzwerk**
Im Heimnetzwerk braucht es ebenfalls eine Firewall. Hier ist die Firewall oftmals bereits im Router vom Provider verbaut. 

Im Heimnetzwerk ist es vorallem wichtig, dass die Firewall möglichst autonom arbeiten kann und ohne Wartung auskommt, da sich ein Heimnetzrouter an alle Leute richten und somit auch an Leute, die keine IT-Kentnisse haben. 

Ebenfalls ist es wichtig, dass die Anschaffungskosten möglichst gerring sind, da die meisten nicht so viel für eine Firewall für Zuhause zahlen möchten. 

Wichtig:
- Autonom

### **Firmennetzwerk**
In einem Firmennetzwerk braucht man bereits deutlich mehr. Hier braucht es eine grosse Firewall mit grossem Durchsatz, guten Filterfunkionen und guter Zuverlässigkeit. 



Gesuchte Firewall
- Unkompliziert 
- System das High Availability unterstützt. 

### **Kleiner Standort ohne On-Premise Serverinfrastruktur**
Hier kommt es darauf an, wo der Internet-Breakout im Firmennetzwerk ist. 


### **Distaster Recovery Site**
Oftmals ist für eine DR-Site gar keine Firewall nötig, da diese z.B. per direktem Leased-Line Glasfaserkabel oder Express Route angeschlossen ist. 



Gesuchte Firewall
- Viele Rules
- IDS 
- IPS 
- Durchsatz von bis zu 1 Gbit/s
