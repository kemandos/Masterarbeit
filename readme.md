
# Analyse von Stellenausschreibungen hinsichtlich des Anforderungsprofils für datengetriebene Berufsfelder

## 1. Einleitung

Ziel der Arbeit ist es, ein Profil der Anforderungen an Kandidaten für datengetriebene Berufsfelder zu erstellen. Dazu werden Stellenausschreibungen ausgewertet und die Anforderungen an Kandidaten identifiziert.

## 2. Vorgehensweise

### 2.1 Datenbeschaffung

Die Daten wurden aus dem Angebot verschiedener Job Portale entnommen. Die Suche wurde auf die Berufsfelder "Data Scientist, Data Analyst, Data Engineer und Business Analyst" eingeschränkt. Insgesamt wurden 3097 Stellenausschreibungen gefunden und heruntergeladen. Nach manueller Prüfung und Enfernung der Duplikate, blieben insgesamt 2311 Stellenauschreibungen.

### 2.2 Datenaufbereitung

Die heruntergeladenen Stellenanzeigen wurden mit Hilfe der Python-Bibliothek BeautifulSoup in ein strukturiertes Format umgewandelt.

### 2.3 Datenanalyse

Die  Daten wurden mit Hilfe der Python-Bibliothek pandas analysiert. Zunächst wurden die Anforderungen an Kandidaten in verschiedene Kategorien eingeteilt. Anschließend wurden die Häufigkeiten der einzelnen Anforderungen ermittelt und in Tableau Desktop dargestellt.
<img width="1517" alt="Bildschirmfoto 2022-07-09 um 13 18 52" src="https://user-images.githubusercontent.com/77071620/178103407-c15a5a5d-8d2a-45b0-96b8-32c7bf023d7b.png">

## 3. Ergebnisse

### 3.1. EDA

<img width="1512" alt="Bildschirmfoto 2022-07-09 um 13 11 28" src="https://user-images.githubusercontent.com/77071620/178103183-63ac916f-8138-48bd-a87b-90cf5b6bbf7e.png">

#### Ungefiltert liefert das Dashboard folgende Ergebnisse:

 - Bei der graphischen Darstellung der Daten wird es deutlich, dass von 2311 einzigartigen Stellen, welche in dem Datensatz vorhanden sind, die meistgesuchte Berufsbezeichnung mit 938 Ergebnissen - Data Analyst ist. Die Interpretation der Ergebnisse lässt vermuteten, dass viele Unternehmen – Generalisten suchen, die von allen ein wenig können.
 - Die Ergebnisse der Analyse von Erfahrungsstufen zeigt, dass nur geringer Anteil an Junior Stellen verfügbar ist und meistens Menschen mit einer Berufserfahrung gesucht werden. Dieser Sachverhalt besteht bei allen Berufsbezeichnungen.
 - In West- und Süd-Deutschland werden die meisten Daten Spezialisten gesucht. Der Osten wird durch Berlin repräsentiert und der Norden durch Hamburg.
 - Die Top 3 Orte nach Anzahl der Stellenausschreibungen sind Berlin, München und Hamburg
 - Der Anteil an remote Stellen mit 6,53 % ist ziemlich klein. Was auf eine Konservativität der deutschen Unternehmen zurückzuführen ist.
 - Manche Stellenanzeigen befinden sich außerhalb von Deutschland, wurden jedoch auf einem deutschen Stellenportal veröffentlicht
 - Die Top 3 Branchen, wo die meisten Spezialisten gesucht werden, stellen keine große Überraschung dar. Beratungsunternehmen suchen nach Mitarbeitern, um die Digitalisierung des Kundenunternehmens voranzubringen. IT-Unternehmen brauchen zwingend Datenspezialisten, da deren Geschäftsmodell meistens auf den Daten basiert. Retail ist einer der wenigen Branchen, welche ‚data-driven‘ Ansatz verfolgen, um den Einkauf, Logistik, Marketing etc. zu verbessern.
 - Der durchschnittliche Gehalt für alle analysierten Berufe, unabhängig von Ort, Erfahrungsstufe und Branche liegt bei ca. 73 Tausend Euro. 
### 3.1. Anallyse der Anforderungen
Wie man aus der Abbildung entnehmen kann, wird bei 61 % (1416 Einträge) aller Stellenanzeigen (2311 Einträge) ein Abschluss vorausgesetzt. In 43 % der Fälle (1257 Einträge) setzen die Unternehmen einen Bachelor-Abschluss voraus, gefolgt von Master-Abschluss mit 349 Einträge (15%). Einige Unternehmen verlangen in 4 % der Fälle (82 Einträge) sogar einen Doktor-Abschluss.

Bei den Studiengängen steht Informatik mit 1257 Einträgen (54 %) an erster Stelle, gefolgt von Mathematik mit 31 % (717 Einträge), Statistik mit 21 % (479 Einträge) und Wirtschaftsinformatik mit 16 % (364 Einträge). Die Wirtschaftsstudiengänge mit einem Anteil von 11 % (251 Einträge) bei VWL und BWL mit 8 % (188) sind eher in der Unterzahl. Somit suchen die Unternehmen für eine Tätigkeit in der Datenumfeld, meistens einen Kanditen mit Bachelor-Abschluss in einem der MINT-Fächer. Was auf die benötigten Kenntnisse zurückführt, welche in dem nächsten Abschnitt analysiert werden.

Im Anbetracht der Ergebnisse soll an dieser Stelle erwähnt werden, dass Menschen, ohne oder mit einem fachfremden Hochschulabschluss weiterhin die Möglichkeit sich für die Stelle zu qualifizieren. Erfahrungsgemäß zeigt sich die IT-Branche offen gegenüber ungeraden Lebensläufen. Die praktischen Erfahrungen zählen mehr und nivellieren das Fehlen einiger Dokumente.

Die Quereinsteiger oder Menschen ohne Abschluss haben die Möglichkeit sich selbst für die Stelle zu qualifizieren. 
Die drei Alternativen gegenüber einer klassischen Ausbildung sind die MOOCs (Massive Open Online Course) in Verbindung mit mehreren Projekten in GitHub und Zertifizierungen, Traineeships sowie BootCamps.

Die Beliebtesten MOOcs Platformen wie Coursera oder eDX bieten Kurse zu Programmiersprachen, Datenbanken, Visualisierungstool usw.. Die erlernten Fähigkeiten können dazu genutzt werden, eigene Projekte umzusetzen, um diese dann dem Arbeitgeber vorzuzeigen. Außerdem bieten einige große Unternehmen wie z.B. Google in Kooperation mit MOOCs die Möglichkeit sich Zertifikate zu erwerben, welche in der Branche stark angesehen sind.
Traineships sind beliebt bei jungen Absolventen mit fachfremden Abschlüssen. In der Zeit von Fachkräftemangel setzen viele Unternehmen verstärkt darauf Menschen selbst auszubilden. Die Berufseinsteiger werden ‚on the job‘ geschult. Die Praxisnähe ermöglich ein schnelles Wissenstransfer in Verbindung mit einem guten Gehalt und macht die Traineestellen sehr begehrt.

Als BootCamp wird die Form einer intensiven Militärausbildung in USA bezeichnet. Aufgrund des Erfolges von diesen Trainingsformat wurde es für die Ausbildung von IT-Kenntnisse adaptiert. Dank der Intensivität der Ausbildung werden innerhalb von 3 Monaten nur die notwendigsten und wichtigsten Aspekte der Programmierung erlernt, um das Niveau eines einsatzbereiten Arbeitnehmers zu erreichen. Da die Studenten während ihres Studiums an realen Projekten arbeiten, ist das erworbene Wissen auch wichtig und aktuell. In Deutschland besteht die Möglichkeit der Finanzierung der Ausbildung in einem Coding Bootcamps durch die Agentur für Arbeit oder JobCenter.

<img width="1359" alt="Bildschirmfoto 2022-07-09 um 13 24 57" src="https://user-images.githubusercontent.com/77071620/178103574-7c7f20db-b82a-4d85-b7ce-3407e413c70a.png">

