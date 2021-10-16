# Leitfragen zum Thema Internetservices

**Ausgangslage**
***
Ein Unternehmen hat einen veralteten Internetzugang mit einer Übertragungsrate von 50 Mbit/s im Download und 5 Mbit/s im Upload mit ADSL. Die Firma produziert Kaffeemaschinen in einer städtischen Gegend in der Schweiz. Das Marketing benutzt moderne Webapplikationen mit viel Multimediaanwendungen und ein Shop für Endkunden ist ebenfalls vorhanden. Alle Mitarbeiten-den benutzen Mail und Browserapplikationen. Die Firma hat 90 Internetnutzer.

Eine Firewall ist nicht vorhanden und die Server stehen alle beim Provider.


# **Aufgabe** 
Vergleichen sie folgenden Möglichkeiten die Internetservices zu betreiben: 

• eigene Server „inhouse“ 
• dedizierte Server (Root-Server) bei Provider 
• Services beim Provider (Shared hosting) 

Nehmen Sie dafür für 2 Fälle einige Eckdaten an (z.B. Speicherplatz, Traffic, Dienste, …). 
Erstens eine einfache Webpräsenz zu Werbezwecken und Mail, zweitens eine komplexe 
Datenbankanwendung mit PHP für den Kundenzugriff.  

Welche Vergleichskriterien finden Sie, welche sind wie wichtig? 

Konstruieren Sie „typische Fälle“ und vergleichen Sie.

  
## **1 Vergleich**

**eigene Server „inhouse“ bzw. On-Premise** 
  
Die Serverinfrastruktur inhouse bzw. On-Premise zu betreiben war lange die einfachste Möglichkeit. 


Den Server Inhouse zu hosten hat den Vorteil das es günstiger ist, man Muss keinen Host monatlich bezahlen, es ist individueller und mn kann alles selbst entscheiden. Jedoch hat man hohe Anschafungskossten für die Hardware und Kosten für die Techniker welche die Server warten. Die Verbindung zum Server ist schneller, da der Server vor Ort ist. Man kann selbst Ausfällen mit eigenen Masnahmen vorbeugen.

- Hohe Anschaffungskosten
- Niedrige Betriebskosten 
- Es braucht lange, um die Anzahl Ressourcen zu erhöhen 



**dedizierte Server (Root-Server) bei Provider**

Beim dedizierten Hosting, auch Root-Server Hosting, geannnt, hat man vollen Zugriff auf den Server. Der Host kümmert sich je nach Vertrag um die Wartung und die Beschaffung der Hardware. Die Anschafungskosten sind viel niedriger. Es kann jedoch sein das der Host seinen Verpflichtungen nich nachkommt, und Farmeware Updates nicht macht, oder die Reaktionszeit auf Supportanfragen serh lange ist.

- Anschaffungskosten gerring
- Geringe Betriebskosten 
- Man hat freien Zugriff auf den Server 
- Man ist sehr flexibel

**Services beim Provider (Shared hosting)**
  
Shared hosting ist die günstigste der drei Alternativen, da man sich die Kosten mit anderen Leuten oder Firmen teilt. Der Nachteil man hat weder einen dedizierten Kontakt noch bessondere Auswahl mit dmn maintanance Windows. Man muss sich mit allen andern absprechen wann der Webserver gewartet werden darf. Man ist weniger flexiebel als bei den anderen Methoden.

- Leistung der Website kann durch andere eingeschränkt werden
- Zugriffs und Verwaltungsmöglichkeiten eher gerring 
- Keine individuelle Installation von Services 
- Anschaffungskosten gerring
- Günstige Betriebskosten 
- Wartung und Anschaffung Hardware wird von Provider übernommen 
- Die Sicherheit ist zu einem gewissen Grad vom Provider professionell gemanged

**Welche Vergleichskriterien finden Sie, welche sind wie wichtig?**

Das wichtigste Kriterium abgesehen von Availability ist Sicherheit. Falls mit einer SQL Injection  von schädlichem Code die gesamte User Datenbank ausgelesen werden kann, wirft ein äusserst schlechtes lich auf die Webseiten Betreiber. 

- Compute Ressourcen
- Speicherplatz 
- Traffic
- Dienste 

Nehmen Sie dafür für 2 Fälle einige Eckdaten an (z.B. Speicherplatz, Traffic, Dienste, …) Erstens eine einfache Webpräsenz zu Werbezwecken und Mail, zweitens eine komplexe Datenbankanwendung mit PHP für den Kundenzugriff.

# **2 Typische Fälle**
Konstruieren Sie „typische Fälle“ und vergleichen Sie.

## **Interner Service**
Ein interner Service soll nur vom lokalen Netzwerk aus erreichbar sein. Hier braucht es entweder einen Server der inhouse steht oder einen dedizierten Root-Server, auf welchem man einen VPN-Tunnel installieren kann. 

## **Externer Service**
Ein externer Service soll im Internet erreichbar sein. Dies kann z.B. die Firmenwebseite sein. Hier eignet sich vor allem ein dedizierter Server oder ein shared Server. 



