# Leitfragen zum Thema Übertragungsrate, Verfügbarkeit

**Ausgangslage**
***
Ein Unternehmen hat einen veralteten Internetzugang mit einer Übertragungsrate von 50 Mbit/s im Download und 5 Mbit/s im Upload mit ADSL. Die Firma produziert Kaffeemaschinen in einer städtischen Gegend in der Schweiz. Das Marketing benutzt moderne Webapplikationen mit viel Multimediaanwendungen und ein Shop für Endkunden ist ebenfalls vorhanden. Alle Mitarbeiten-den benutzen Mail und Browserapplikationen. Die Firma hat 90 Internetnutzer.

Eine Firewall ist nicht vorhanden und die Server stehen alle beim Provider.

## Welche Übertragungsrate wäre für diese Anwendungen geeignet?
Für E-Mail wird eine Übvertragungsrate von 1-5 Mbit/s benötigt. Beim Videostreaming/Surfen und Webseiten benutzen wird eine Übertragungsrate von 6-15 Mbit/s benötigt. Geeignet für WebApps sind etwa10 15 Mbit/s. Wenn 90 Mitarbeiter im Unternehmen tätig sind heisst das man braucht mindestens 1000 Mbit/s


## Welcher Verfügbarkeit müsste Ihre Anbindung ans Internet haben?
Ausfall von 10 Stunden:
Wenn ein Ausfall von 10h tolerier bar wäre weisst das darauf hin, dass die online Anwendung entweder am Wochenende noicht benutzt wird. Ein anderer grund könnet sein, es ist keine Bussines kritische Applikation und wird von niemandem so häufig genutzt. z.B. kleine Privater Mailserver

Ausfall von 4 Stunden:
Falls ein Ausfall von 4 Stunden im SLA als untolerierbar definiert wird, handelt es sich höchst wahrscheinlich um sehr Wichtige Services ndie dem Core Bussines angehören. Falls dieser Service 4 Stunden nicht erreichbar ist verletzt das nicht nur den SLA sondern bedeutet auch hohe Geldverluste. <br>Gute Beispiele wären 
z.B. Google, Netflix, Server der SIX (Zahlungsverkehr)

## Geeigneter Provider:
Um die gewährleistund der Anforderungen zu erfüllen ist nicht nur die Kostenfrage entscheidend sondern auch die Grösse des Providers, zu kleine Provider könnten die Anforderungen an Availability und Support garnicht erfüllen.
