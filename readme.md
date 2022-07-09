
# Analyse von Stellenausschreibungen hinsichtlich des Anforderungsprofils für datengetriebene Berufsfelder

## 1. Einleitung

Gegenstand der hier vorgestellten Masterarbeit ist die Analyse von Stellensauschreibungen hinsichtlich des Anforderungsprofils für datengetriebene Berufsfelder. Um den Rahmen der vorliegenden Meisterarbeit nicht zu sprängen, erfolgte die Konzentration auf die nachfolgenden vier Berufsfelder: Business Analyst, Data Analyst, Data Engineer und Data Scientist. Es wurde eine empirische Untersuchung von Stellenanzeigen über alle Hierarchiestufen, Branchen und deutsche Bundesländer durchgeführt. Ziel dabei war Anhand von entwickelten Anforderungsprofil für jede Berufsgruppe, die Stellenanzeigen zu analysieren und die benötigten Fachkenntnisse, Abschlüsse, Hard- und Softskills herauszufinden.

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

#### 3.1.1 Abschlüsse

Wie man aus der Abbildung entnehmen kann, wird bei 61 % (1416 Einträge) aller Stellenanzeigen (2311 Einträge) ein Abschluss vorausgesetzt. In 43 % der Fälle (1257 Einträge) setzen die Unternehmen einen Bachelor-Abschluss voraus, gefolgt von Master-Abschluss mit 349 Einträge (15%). Einige Unternehmen verlangen in 4 % der Fälle (82 Einträge) sogar einen Doktor-Abschluss.

Bei den Studiengängen steht Informatik mit 1257 Einträgen (54 %) an erster Stelle, gefolgt von Mathematik mit 31 % (717 Einträge), Statistik mit 21 % (479 Einträge) und Wirtschaftsinformatik mit 16 % (364 Einträge). Die Wirtschaftsstudiengänge mit einem Anteil von 11 % (251 Einträge) bei VWL und BWL mit 8 % (188) sind eher in der Unterzahl. Somit suchen die Unternehmen für eine Tätigkeit in der Datenumfeld, meistens einen Kanditen mit Bachelor-Abschluss in einem der MINT-Fächer. Was auf die benötigten Kenntnisse zurückführt, welche in dem nächsten Abschnitt analysiert werden.

Im Anbetracht der Ergebnisse soll an dieser Stelle erwähnt werden, dass Menschen, ohne oder mit einem fachfremden Hochschulabschluss weiterhin die Möglichkeit sich für die Stelle zu qualifizieren. Erfahrungsgemäß zeigt sich die IT-Branche offen gegenüber ungeraden Lebensläufen. Die praktischen Erfahrungen zählen mehr und nivellieren das Fehlen einiger Dokumente.

Die Quereinsteiger oder Menschen ohne Abschluss haben die Möglichkeit sich selbst für die Stelle zu qualifizieren. 
Die drei Alternativen gegenüber einer klassischen Ausbildung sind die MOOCs (Massive Open Online Course) in Verbindung mit mehreren Projekten in GitHub und Zertifizierungen, Traineeships sowie BootCamps.

Die Beliebtesten MOOcs Platformen wie Coursera oder eDX bieten Kurse zu Programmiersprachen, Datenbanken, Visualisierungstool usw.. Die erlernten Fähigkeiten können dazu genutzt werden, eigene Projekte umzusetzen, um diese dann dem Arbeitgeber vorzuzeigen. Außerdem bieten einige große Unternehmen wie z.B. Google in Kooperation mit MOOCs die Möglichkeit sich Zertifikate zu erwerben, welche in der Branche stark angesehen sind.
Traineships sind beliebt bei jungen Absolventen mit fachfremden Abschlüssen. In der Zeit von Fachkräftemangel setzen viele Unternehmen verstärkt darauf Menschen selbst auszubilden. Die Berufseinsteiger werden ‚on the job‘ geschult. Die Praxisnähe ermöglich ein schnelles Wissenstransfer in Verbindung mit einem guten Gehalt und macht die Traineestellen sehr begehrt.

Als BootCamp wird die Form einer intensiven Militärausbildung in USA bezeichnet. Aufgrund des Erfolges von diesen Trainingsformat wurde es für die Ausbildung von IT-Kenntnisse adaptiert. Dank der Intensivität der Ausbildung werden innerhalb von 3 Monaten nur die notwendigsten und wichtigsten Aspekte der Programmierung erlernt, um das Niveau eines einsatzbereiten Arbeitnehmers zu erreichen. Da die Studenten während ihres Studiums an realen Projekten arbeiten, ist das erworbene Wissen auch wichtig und aktuell. In Deutschland besteht die Möglichkeit der Finanzierung der Ausbildung in einem Coding Bootcamps durch die Agentur für Arbeit oder JobCenter.

<img width="1359" alt="Bildschirmfoto 2022-07-09 um 13 24 57" src="https://user-images.githubusercontent.com/77071620/178103574-7c7f20db-b82a-4d85-b7ce-3407e413c70a.png">

#### 3.1.2 Technologien

<img width="1357" alt="Bildschirmfoto 2022-07-09 um 13 31 33" src="https://user-images.githubusercontent.com/77071620/178103771-baddb995-b0c7-481e-b041-309654b9321b.png">

Angeführt wird die Liste mit 40 % (930 Erwähnungen) von Git. 

Git ist eine freie Software für Versionsverwaltung von Code. Dadurch, dass die vier Berufsgruppen bis auf den Business Analysten, viel mit Programmierung zu tun haben, muss der geschriebene Code ordnungsgemäß verwaltet und versionisiert werden. Git ist zurzeit die beste Lösung dafür. 

Allgemein ist die Gruppe Technologien sehr Data Engineering lastig und wie in der Abbildung 6 zu sehen ist, bildet diese den Schwerpunkt des Berufes ab. Kenntnisse in dem Umgang mit den Datenbanken mit 35 % (803 Erwähnungen) sind plausibel, da die Menschen viel mit den Datenbanken arbeiten, weil dort die Daten gespeichert sind. 

Microsoft Excel ist an dieser Stelle eher als ein Ausreißer zu betrachten da diese Technologie eher zu den Kenntnissen von Business Analysten gehört. Der Rest der Anforderungen ist wie bereits erwähnt, sehr Data Engineering lastig und wird von vielen Data Engineers verlangt, um mit Big Data zu arbeiten.

#### 3.1.3 Plattformen

<img width="1356" alt="Bildschirmfoto 2022-07-09 um 13 33 15" src="https://user-images.githubusercontent.com/77071620/178103809-56f83417-9abe-4f48-bade-64ae73bfe952.png">

Derzeit steigen viele Unternehmen von lokalen Lösungen, welche auf eigenen Servern laufen auf die Cloud-Lösungen um. Die bekanntesten Plattformen in Deutschland werden durch die 3 große Spieler auf dem Cloud-Markt: Azure von Microsoft, AWS von Amazon und Google Cloud repräsentiert.

#### 3.1.4 Programmiersprachen

<img width="1359" alt="Bildschirmfoto 2022-07-09 um 14 08 41" src="https://user-images.githubusercontent.com/77071620/178105051-7df4697f-dafa-4fe2-b3e5-73bbc680e372.png">

SQL mit einem Anteil von 50 % (1145 Ergebnisse) sowie Python mit 48 % (1102 Ergebnisse) sind nach wie vor die beliebtesten Sprachen, wenn es um datengetriebene Berufsfelder geht. Sogar HTML und Javascript stellen keine Ausreißer dar, weil diese von Web-Analysten für die Erstellung von Analysen verwendet werden. Java mit 15 % (353 Ergebnisse) wird immer noch benötigt. Dies ist zurückzuführen auf die Verwendung bestimmter Technologien oder Plattformen wie beispielsweise Talend oder Databricks. Diese sind entweder mit Java programmiert oder bieten Java als Programmiersprache für die Analyse an.

#### 3.1.5 Visualisierung

Die Visualisierung von Daten ist ein wichtiger Prozess, welches in einfacher Form die Grundlagen für die Entscheidungen liefert. Diese können entweder Strategieentscheidungen für das Unternehmen sein oder die Bewertung einer Machine Learning Pipeline.

Der Markt für die die Business Intelligence Tools ist seit langer Zeit aufgeilt in:
 - kommerzielle Software - Tableau, PowerBI, Qlik und Google Data Studio 
 - Open-Source - Dash, Superset, Matplotlib etc.

Open-Source Software oder Bibliotheken für die Visualisierung werden von wenigen Unternehmen eingesetzt. Diese sind schwierig zu konfigurieren oder setzen gewisse Kenntnisse in der Programmierung vor. 

Kommerzielle Software bietet dagegen Einfachheit und Design an, was vielen Nutzern bei Open-Source Lösungen gefehlt hat und deshalb bevorzugt wird.

Wie aus der Abbildung  klar wird, enthalten 27 % (627 Einträge) nicht spezifizierte Erwähnungen über Datenvisualiserungen. Dagegen werden bei 17 % der Stellenanzeigen (386) Kenntnisse mit PowerBI verlangt, bei 15 % (358 Einträge) Dash und bei 12 % (287 Einträge) Tableau. Das PowerBI an erster Stelle steht ist auch wenig überraschend, da Microsoft die Software innerhalb des Bundles von Office 365 zur Verfügung stellt und somit über die typische Massenstrategie von Microsoft an die hohe Nutzerzahlen kommt. Der Rivale Tableau dagegen, kostet um einiges Mehr und wird meistens von großen Unternehmen eingesetzt.

<img width="1361" alt="Bildschirmfoto 2022-07-09 um 13 35 08" src="https://user-images.githubusercontent.com/77071620/178103927-477a8bfa-7a7b-4571-8c0c-af8b3f3a5add.png">
 
#### 3.1.6 ML & DL

Mit 488 Ergebnissen (21 %), Machine Learning im Allgemeinen erwähnt, gefolgt von Artificial Intelligence mit 139 Ergebnissen (6 %) und speziellen Kenntnissen wie TensorFlow mit 90 Ergebnissen (ca. 4 %), Scikit-learn mit 68 Ergebnissen (ca. 3 %) sowie Keras mit 42 Ergebnissen (ca. 2 %).

<img width="1360" alt="Bildschirmfoto 2022-07-09 um 14 11 53" src="https://user-images.githubusercontent.com/77071620/178105211-5316e490-a934-486e-8415-c17dfeefa4ab.png">

#### 3.1.7 Sprachen

<img width="1356" alt="Bildschirmfoto 2022-07-09 um 14 14 25" src="https://user-images.githubusercontent.com/77071620/178105333-dcfa62d8-a0d2-4a5d-b75d-6d937e1cbf87.png">

Die Sprachkenntnisse beinhalten nur wenige Erwähnungen. Grund dafür ist, die Begrenzung der Stellenanzeigen auf Deutschland. Die Ergebnisse der Analyse beinhalten 1359 Ergebnisse (59 %) mit Erwähnungen von Deutsch und 1329 (58 %) Erwähnungen von English.


#### 3.1.8 Projektmanagement

<img width="1360" alt="Bildschirmfoto 2022-07-09 um 14 14 39" src="https://user-images.githubusercontent.com/77071620/178105407-146ab1aa-015c-47a9-b217-55271f9baa78.png">

Das agile Projektmanagement steht mit 30 % (694 Ergebnisse) an erster Stelle. Grund dafür ist, dass viele datengetriebene Berufe genauso wie die Softwareentwickler in Sprints arbeiten.  Sprints dauern meisten eine Woche und innerhalb dieser Zeit müssen bestimmte Arbeitspakete fertiggestellt und dokumentiert werden, danach erfolgt eine Evaluierung der Ergebnisse und die Zielsetzung für einen neuen Sprint.

Außerdem werden in den Ergebnissen Lean-Management mit 6 % (148 Einträge), Leadership mit 5 % (127 Einträge) sowie Scrum 5 % (117 Einträge) erwähnt. Der Punkt Leadership ist auf einige Führungspositionen zurückzuführen, welche auch in dem Datensatz vorhanden sind. Lean-Management ist ein Projektmanagementansatz für die ganzheitliche Steigerung von Effektivität und Effizienz. 

Scrum gehört zu der agilen Methode und ist fokussiert auf der Effizienzsteigerung und Fehlerreduzierung. Somit kann man sagen, dass die datengetriebenen Berufe sowie die Softwareentwickler nach agilen Methoden arbeiten, meisten in 3-4 Teams. Die Aufgaben werden in kleine Arbeitspakete verteilt und in Sprints abgearbeitet, was zu einer Fehlerreduzierung führt und die Effizienz steigert.


#### 3.1.8 Soft-Skills

<img width="1359" alt="Bildschirmfoto 2022-07-09 um 14 14 54" src="https://user-images.githubusercontent.com/77071620/178105411-576cccb2-42d2-4653-813e-5963c1fc89ef.png">

Hier werden von Kandidaten in erster Linie gute Kommunikationsfähigkeiten (43%) in Wort- und Schrift, Teamarbeit (10 %) und analytisches Denken (7%) verlangt. Die Fähigkeiten Probleme zu lösen, Entscheidungen zu treffen und Ergebnisse zu präsentieren, spielen auch eine wichtige Rolle. Der Grund für diese Anforderungen ist, dass Menschen, die mit den Daten Arbeit bis auf Data Engineer ständig im Austausch mit anderen Personen stehen. Sie müssen ihre Gedanken, Schritte und Ergebnisse in einer guten, verständlichen Art und Weise den anderen Menschen rüberbringen. Außerdem müssen die Menschen analytisch denken können, um Probleme und Herausforderung, welche ständig auftauchen werden, schnell und effektiv lösen zu können.

