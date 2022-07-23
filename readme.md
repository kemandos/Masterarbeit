
# Analyse von Stellenausschreibungen hinsichtlich des Anforderungsprofils für datengetriebene Berufsfelder

## 1. Einleitung

Die vorliegende Arbeit verfolgt das Ziel, ein Anforderungsprofil für datengetrie-bene Berufsfelder zu entwickeln und diesbezüglich eine empirische Analyse von Stellenausschreibungen durchzuführen. Dabei wird der Fokus der Arbeit auf die vier Berufsgruppen Business-Analyst, Data-Analyst, Data-Engineer sowie Data-Scientist gelegt. 

Anhand der Analyse soll die Forschungsfrage beantwortet werden, welche Anforderungen die Unternehmen an die Bewerber in ihren Stellenanzeigen für datengetriebene Berufsfelder stellen und welche Fähigkeiten, Abschlüsse und Kenntnisse von potenziellen Mitarbeitern verlangt werden. 


#### 1.1 Anforderungsprofil -  Schwerpunkte

![image](https://user-images.githubusercontent.com/77071620/178105461-440dd6e4-20d1-4814-9059-dd753b415033.png)

#### 1.2 Anforderungsprofil -  Data

![image](https://user-images.githubusercontent.com/77071620/178105491-8f69ad62-69b8-4b99-999c-fabb185c2adf.png)


## 2. Vorgehensweise

### 2.1 Datenbeschaffung

Die Daten wurden aus dem Angebot verschiedener Job Portale entnommen. Die Suche wurde auf die Berufsfelder Data-Scientist, Data-Analyst, Data-Engineer und Business- Analyst eingeschränkt. Insgesamt wurden 3097 Stellenausschreibungen gefunden und heruntergeladen. Nach manueller Prüfung und Enfernung der Duplikate, blieben insgesamt 2311 Stellenauschreibungen.

### 2.2 Datenaufbereitung

Die heruntergeladenen Stellenanzeigen wurden mit Hilfe der Python-Bibliothek pandas in ein strukturiertes Format umgewandelt.

### 2.3 Datenanalyse

Zunächst wurden die Anforderungen an Kandidaten in verschiedene Kategorien eingeteilt. Anschließend wurden die Häufigkeiten der einzelnen Anforderungen ermittelt und in Tableau Desktop dargestellt.
<img width="1517" alt="Bildschirmfoto 2022-07-09 um 13 18 52" src="https://user-images.githubusercontent.com/77071620/178103407-c15a5a5d-8d2a-45b0-96b8-32c7bf023d7b.png">

## 3. Ergebnisse

### 3.1. EDA

<img width="1512" alt="Bildschirmfoto 2022-07-09 um 13 11 28" src="https://user-images.githubusercontent.com/77071620/178103183-63ac916f-8138-48bd-a87b-90cf5b6bbf7e.png">

#### Ungefiltert liefert das Dashboard folgende Ergebnisse:

 - Bei der grafischen Darstellung der Daten wird deutlich, dass von 2311 einzigartigen Stellen, die in dem Datensatz vorhanden sind, die meistgesuchte Berufsbezeichnung mit 938 Ergebnissen Data-Analyst ist. Die Interpretation der Ergebnisse lässt vermuten, dass viele Unternehmen Generalisten suchen, die von allen ein wenig können.
 - Die Ergebnisse der Analyse von Erfahrungsstufen zeigt, dass nur ein geringer Anteil an Junior-Stellen verfügbar ist und meistens Menschen mit Berufserfahrung gesucht werden. Dieser Sachverhalt besteht bei allen Berufsbezeichnungen.
 - In West- und Süd-Deutschland werden die meisten Datenfachleute gesucht. Der Osten wird durch Berlin repräsentiert und der Norden durch Hamburg.
 - Die Top-3-Orte nach Anzahl der Stellenausschreibungen sind Berlin, München und Hamburg.
 - Der Anteil an Remote-Stellen mit 6,53 % ist ziemlich klein, was auf eine Konservativität der deutschen Unternehmen zurückzuführen ist.
 - Manche Stellenanzeigen befinden sich außerhalb von Deutschland, wurden jedoch auf einem deutschen Stellenportal veröffentlicht.
 - Die Top-3-Branchen, in denen die meisten Fachleute gesucht werden, entsprechen den Erwartungen. Beratungsunternehmen suchen nach Mitarbeitenden, um die Digitalisierung des Kundenunternehmens voranzubringen. IT-Unternehmen brauchen zwingend Datenspezialisten, da deren Geschäftsmodell meistens auf den Daten basiert. Retail ist eine der wenigen Branchen, die einen ‚data-driven‘ Ansatz verfolgen, um den Einkauf, die Logistik, das Marketing etc. zu verbessern.
 - Das durchschnittliche Gehalt für alle analysierten Berufe, unabhängig von Ort, Erfahrungsstufe und Branche, liegt bei ca. 73.000 Euro brutto pro Jahr.  
### 3.1. Anallyse der Anforderungen

#### 3.1.1 Abschlüsse

Wie aus der Abbildung entnommen werden kann, wird bei 61 % (1416 Einträge) aller Stellenanzeigen (2311 Einträge) ein Abschluss vorausgesetzt. In 43 % der Fälle (1257 Einträge) erwarten die Unternehmen einen Bachelorabschluss, gefolgt von einem Masterabschluss mit 349 Einträgen (15 %). Einige Unternehmen verlangen in 4 % der Fälle (82 Einträge) einen Doktorabschluss.

Bei den Studiengängen steht Informatik mit 1257 Einträgen (54 %) an erster Stelle, gefolgt von Mathematik mit 31 % (717 Einträge), Statistik mit 21 % (479 Einträge) und Wirtschaftsinformatik mit 16 % (364 Einträge). Die Wirtschafts-studiengänge mit einem Anteil von 11 % (251 Einträge) bei VWL und BWL mit 8 % (188) sind eher in der Unterzahl. Somit suchen die Unternehmen für eine Tätigkeit im Datenumfeld meistens eine Person mit Bachelorabschluss in ei-nem der MINT-Fächer, was auf die benötigten Kenntnisse zurückführt, die in dem nächsten Abschnitt analysiert werden.

Im Anbetracht der Ergebnisse soll an dieser Stelle erwähnt werden, dass Men-schen ohne oder mit einem fachfremden Hochschulabschluss weiterhin die Möglichkeit haben, sich für die Stelle zu qualifizieren. Erfahrungsgemäß zeigt sich die IT-Branche offen gegenüber ungeraden Lebensläufen. Die prakti-schen Erfahrungen zählen mehr und nivellieren das Fehlen einiger Dokumente.

Quereinsteigende oder Menschen ohne Abschluss haben die Möglichkeit, sich selbst für die Stelle zu qualifizieren. Die drei Alternativen gegenüber einer klassischen Ausbildung sind die MOOCs (Massive Open Online Course) in Verbindung mit mehreren Projekten in GitHub und Zertifizierungen, Trainee-ships sowie BootCamps.

Die beliebtesten MOOcs-Platformen wie Coursera oder eDX bieten Kurse zu Programmiersprachen, Datenbanken, Visualisierungstool an. Die erlernten Fähigkeiten können dazu genutzt werden, eigene Projekte umzusetzen, um diese dann dem Arbeitgebenden vorzuzeigen. Außerdem bieten einige große Unternehmen wie Google in Kooperation mit MOOCs die Möglichkeit, Zertifika-te zu erwerben, die in der Branche angesehen sind. 

Traineeships sind beliebt bei jungen Absolventen mit fachfremden Abschlüs-sen. In der Zeit des Fachkräftemangels setzen viele Unternehmen verstärkt darauf, Menschen selbst auszubilden. Die Berufseinsteiger werden ‚on the job‘ geschult. Die Praxisnähe ermöglicht einen schnellen Wissenstransfer in Verbindung mit einem guten Gehalt und macht die Traineestellen begehrt.

Als BootCamp wird die Form einer intensiven Militärausbildung in den USA bezeichnet. Aufgrund des Erfolges dieses Trainingsformats wurde es für die Ausbildung von IT-Kenntnissen adaptiert. Dank der Intensivität der Ausbildung werden innerhalb von drei Monaten nur die notwendigsten Aspekte der Pro-grammierung erlernt, um das Niveau eines einsatzbereiten Arbeitnehmenden zu erreichen. Da die Studierenden während ihres Studiums an realen Projek-ten arbeiten, ist das erworbene Wissen relevant und aktuell.  In Deutschland besteht die Möglichkeit, die Ausbildung in einem Coding-Bootcamps durch die Agentur für Arbeit oder das JobCenter fördern zu lassen. 


<img width="1359" alt="Bildschirmfoto 2022-07-09 um 13 24 57" src="https://user-images.githubusercontent.com/77071620/178103574-7c7f20db-b82a-4d85-b7ce-3407e413c70a.png">

#### 3.1.2 Technologien

<img width="1357" alt="Bildschirmfoto 2022-07-09 um 13 31 33" src="https://user-images.githubusercontent.com/77071620/178103771-baddb995-b0c7-481e-b041-309654b9321b.png">

Angeführt wird die Liste mit 40 % (930 Erwähnungen) von Git. 

Git ist eine freie Software für Versionsverwaltung von Code. Da die vier Be-rufsgruppen bis auf den Business-Analysten viel mit Programmierung zu tun haben, muss der geschriebene Code ordnungsgemäß verwaltet und versionisiert werden. Git ist zurzeit die beste Lösung dafür. Allgemein ist die Gruppe Technologien Data-Engineering-lastig und, wie in der Abbildung zu sehen ist, bildet diese den Schwerpunkt des Berufes ab. 

Kenntnisse in dem Umgang mit den Datenbanken mit 35 % (803 Erwähnungen) sind plausibel, da die Menschen intensiv mit den Datenbanken arbeiten, weil dort die Daten gespeichert sind. 

Microsoft Excel ist an dieser Stelle eher als ein Ausreißer einzuschätzen, da diese Technologie zu den Kenntnissen von Business-Analysten gehört. Der Rest der Anforderungen ist auf Data-Engineering fokussiert und wird von vielen Data-Engineers verlangt, um mit Big Data zu arbeiten.

#### 3.1.3 Plattformen

<img width="1356" alt="Bildschirmfoto 2022-07-09 um 13 33 15" src="https://user-images.githubusercontent.com/77071620/178103809-56f83417-9abe-4f48-bade-64ae73bfe952.png">

Derzeit steigen viele Unternehmen von lokalen Lösungen, die auf eigenen Servern laufen, auf die Cloud-Lösungen um. Die bekanntesten Plattformen in Deutschland werden durch die drei großen Spieler auf dem Cloud-Markt Azure von Microsoft, AWS von Amazon und Google Cloud repräsentiert. 

Die Ergebnisse der Analyse sehen plausibel aus, da AWS seit langer Zeit den Markt in dem Bereich bestimmt, wobei Microsoft in Deutschland aufholt.In diesem Datensatz liegt zwar der Anteil von AWS mit 16 % (367 Erwähnungen) noch vorne, jedoch aus beruflicher Erfahrung kann an dieser Stelle erwähnt werden, dass Microsoft von vielen Unternehmen mittlerweile bevorzugt wird.

#### 3.1.4 Programmiersprachen

<img width="1359" alt="Bildschirmfoto 2022-07-09 um 14 08 41" src="https://user-images.githubusercontent.com/77071620/178105051-7df4697f-dafa-4fe2-b3e5-73bbc680e372.png">

Die Ergebnisse der Analysegruppe Programmiersprachen sind bezugnehmend auf die datengetriebenen Berufsfelder auch erwartbar. 

SQL mit einem Anteil von 50 % (1145 Ergebnisse) sowie Python mit 48 % (1102 Ergebnisse) sind nach wie vor die beliebtesten Sprachen, wenn es um datengetriebene Berufsfelder geht. Auch HTML und Javascript stellen keine Ausreißer dar, weil diese von Web-Analysten für die Erstellung von Analysen verwendet werden. 

Java mit 15 % (353 Ergebnisse) wird immer noch benötigt. Dies ist zurückzuführen auf die Verwendung bestimmter Technologien oder Plattformen wie Talend oder Databricks. Diese sind entweder mit Java programmiert oder bieten Java (Scala) als Programmiersprache für die Analyse an.


#### 3.1.5 Visualisierung

Die Visualisierung von Daten ist ein zentraler Prozess, der in einfacher Form die Grundlagen für die Entscheidungen liefert. Diese können entweder Stra-tegieentscheidungen für das Unternehmen sein oder die Bewertung einer Machine Learning Pipeline.
Der Markt für die Business-Intelligence-Tools ist seit langer Zeit aufgeteilt in:

 •	kommerzielle Software – Tableau, PowerBI, Qlik und Google Data Studio 
 •	Open-Source – Dash, Superset, Matplotlib etc.
 
Open-Source-Software oder Bibliotheken für die Visualisierung werden von wenigen Unternehmen eingesetzt. Diese sind schwierig zu konfigurieren oder setzen gewisse Kenntnisse in der Programmierung voraus. 

Kommerzielle Software bietet dagegen Einfachheit und Design an, was vielen Nutzenden bei Open-Source-Lösungen gefehlt hat und deshalb bevorzugt wird.

Wie aus der Abbildung ersichtlich wird, enthalten 27 % der Stellenanzeigen (627 Einträge) nicht spezifizierte Erwähnungen über Datenvisualiserungen. Dagegen werden bei 17 % (386) Kenntnisse mit PowerBI verlangt, bei 15 % (358 Einträge) Dash und bei 12 % (287 Einträge) Tableau. Dass PowerBI an erster Stelle steht, ist auch wenig überraschend, da Microsoft die Software innerhalb des Bundles von Office 365 zur Verfügung stellt und somit über die typische Massenstrategie von Microsoft an die hohen Nutzerzahlen kommt. 

Der Rivale Tableau dagegen kostet um einiges mehr und wird meistens von großen Unternehmen eingesetzt.


<img width="1361" alt="Bildschirmfoto 2022-07-09 um 13 35 08" src="https://user-images.githubusercontent.com/77071620/178103927-477a8bfa-7a7b-4571-8c0c-af8b3f3a5add.png">
 
#### 3.1.6 ML & DL

Die speziellen Analysegruppen Machine Learning und Deep Learning sind bei der manuellen Extraktion von den Anforderungen, bis auf die Erwähnung von Machine Learning mit 594 Ergebnissen (26 %) und Neural Network mit 91 Ergebnissen (4 %), unterpräsentiert. 

<img width="1360" alt="Bildschirmfoto 2022-07-09 um 14 11 53" src="https://user-images.githubusercontent.com/77071620/178105211-5316e490-a934-486e-8415-c17dfeefa4ab.png">

Jedoch konnten über SkillNER einige Anforderungen herausgefunden werden.

<img width="1132" alt="image" src="https://user-images.githubusercontent.com/77071620/180604083-3ed98c3b-c2b0-4444-a07e-1537777ac0df.png">

Am häufigsten wird wie auch bei der manuellen Extraktion mit 488 Ergebnissen (21 %) Machine Learning im Allgemeinen erwähnt, gefolgt von Artificial Intelligence mit 139 Ergebnissen (6 %) und speziellen Kenntnissen wie TensorFlow mit 90 Ergebnissen (ca. 4 %), Scikit-learn mit 68 Ergebnissen (ca. 3 %) sowie Keras mit 42 Ergebnissen (ca. 2 %).


#### 3.1.7 Sprachen

<img width="1356" alt="Bildschirmfoto 2022-07-09 um 14 14 25" src="https://user-images.githubusercontent.com/77071620/178105333-dcfa62d8-a0d2-4a5d-b75d-6d937e1cbf87.png">

Die Sprachkenntnisse beinhalten nur wenige Erwähnungen. Grund dafür ist die Begrenzung der Stellenanzeigen auf Deutschland. Die Ergebnisse der Analyse beinhalten 1359 Ergebnisse (59 %) mit Erwähnungen von Deutsch und 1329 (58 %) von Englisch.


#### 3.1.8 Projektmanagement

<img width="1360" alt="Bildschirmfoto 2022-07-09 um 14 14 39" src="https://user-images.githubusercontent.com/77071620/178105407-146ab1aa-015c-47a9-b217-55271f9baa78.png">

Bei der Analysegruppe Projektmanagement konnten folgende Anforderungen festgestellt werden.
 
Das agile Projektmanagement steht mit 30 % (694 Ergebnisse) an erster Stelle. Grund dafür ist, dass viele datengetriebene Berufe genauso wie die Softwareentwickler in Sprints arbeiten. Diese dauern meisten eine Woche und innerhalb dieser Zeit müssen bestimmte Arbeitspakete fertiggestellt und dokumentiert werden, danach erfolgen eine Evaluierung der Ergebnisse und die Zielsetzung für einen neuen Sprint.

Außerdem werden in den Ergebnissen Lean Management mit 6 % (148 Einträge), Leadership mit 5 % (127 Einträge) sowie Scrum mit 5 % (117 Einträge) erwähnt. Der Punkt Leadership ist auf einige Führungspositionen zurückzuführen, die auch in dem Datensatz vorhanden sind. Lean Management ist ein Projektmanagementansatz für die ganzheitliche Steigerung von Effektivität und Effizienz. 

Scrum gehört zu den agilen Methoden und ist fokussiert auf der Effizienzsteigerung und Fehlerreduzierung. Somit kann konstatiert werden, dass die datengetriebenen Berufe sowie die Softwareentwickler meist in 3–4 Teams nach agilen Methoden arbeiten. Die Aufgaben werden in kleine Arbeitspakete verteilt und in Sprints abgearbeitet, was zu einer Fehlerreduzierung führt und die Effizienz steigert.



#### 3.1.9 Soft-Skills

<img width="1359" alt="Bildschirmfoto 2022-07-09 um 14 14 54" src="https://user-images.githubusercontent.com/77071620/178105411-576cccb2-42d2-4653-813e-5963c1fc89ef.png">

Hier werden von Bewerbenden in erster Linie gute Kommunikationsfähigkeiten (43 %) in Wort und Schrift, Teamarbeit (10 %) und analytisches Denken (7 %) verlangt. Die Fähigkeiten, Probleme zu lösen, Entscheidungen zu treffen und Ergebnisse zu präsentieren, spielen auch eine wesentliche Rolle. Der Grund für diese Anforderungen ist, dass Menschen, die mit Daten arbeiten – bis auf Data-Engineers, ständig im Austausch mit anderen Personen stehen. 

Sie müssen ihre Gedanken, Schritte und Ergebnisse in einer verständlichen Art den anderen Menschen vermitteln. Außerdem müssen sie analytisch denken können, um Probleme und Herausforderungen, die ständig auftauchen werden, schnell und effektiv lösen zu können.


## 4 Analyse der Anforderungen im Hinblick auf einzelne Berufe
Bei dieser Analyse konnte schnell festgestellt werden, dass sich die Anforderungen an verschiedene Berufe prozentual wenig bis gar nicht unterscheiden. Diese Feststellung basiert aus den Ergebnissen der Dashboards Skill Catego-ry und Analysis of the roles.

So liegen die prozentualen Anteile für die Anforderungsgruppe Visualisierun-gen für Data-Engineers fast auf dem gleichen Niveau wie bei Business-Analysten, Data-Analysten oder Data-Scientists. In der mittlerweile 7-jährigen beruflichen Praxis des Autors hat dieser jedoch noch nie einen Data-Engineer erlebt, der Daten mit PowerBI oder einer ähnlichen Software visualisiert hat. 

Ähnliche Erkenntnisse sind auch bei der Anforderungsgruppe Programmier-sprachen festzustellen. Es ist nicht die Aufgabe eines Business-Analysten, Code mit Python oder Java zu schreiben. Ein Business-Anlayst beschäftigt sich mit den geschäftlichen Daten, die in einer Datenbank von dem Data-Engineer oder eventuell Data-Analyst zur Verfügung gestellt werden. Daher sind Erfahrungen mit SQL sinnvoll. 

![image](https://user-images.githubusercontent.com/77071620/178105546-3541b308-628f-4a8a-82b3-b99379b7eae8.png)


Ein erwähnenswertes Ergebnis liefert die Anforderungsgruppe Machine Learning. Machine Learning ist ein anspruchsvolles Gebiet, in dem herausragende Kenntnisse in der Programmierung, Mathematik, Statistik etc. gefordert werden.
Laut dem Ergebnis der Analyse werden von einem Data-Analysten Kenntnisse in diesem Bereich gefordert, die Anzahl der Erwähnungen liegt auf dem ähnlichen Niveau wie bei einem Data-Scientist. Dies wurde sowohl bei der manuel-len Extraktion als auch bei der Analyse der Anforderungen mit SkillNER ermittelt.

![image](https://user-images.githubusercontent.com/77071620/180604301-1e44f130-ac3c-4eb8-b73a-cbc5e6db4b33.png)


Das sind einige Beispiele in der Analyse, die auf den ersten Blick nicht verständlich erscheinen. Ein möglicher Grund dafür wäre, wie bereits erwähnt wurde, die fehlende Unterscheidung zwischen den Berufen bei den Unternehmen in Deutschland. Um das zu überprüfen, wurde eine Klassifikationsanalyse durchgeführt.

Der Grund für die Auswahl der Klassifikationsanalyse ist, dass die Rollen bereits bekannt sind. Wären die Rollen Data-Analyst, Business-Analyst, Data-Scientist sowie Data-Engineer nicht bekannt, so müsste anstatt der Klassifikationsanalyse eine Clusteranalyse durchgeführt werden.



### 4.1 Klassifikationsanalyse

Als Referenz für die Klassifikationsanalyse wurde ein Artikel und Code des ehemaligen Indeed-Mitarbeiters Vincent Musgrove verwendet.  Dieser stellte die gleiche Frage bezüglich der Unterscheidung verschiedener Berufe bei den amerikanischen Unternehmen und ob diese Unterscheidungen aus den Daten abgeleitet werden können. In seinem GitHub Repository stellte er ein Jupyter Notebook zur Verfügung mit dem Code für die Klassifikationsanalyse und den Ergebnissen seiner Analyse.

![image](https://user-images.githubusercontent.com/77071620/178105656-ddca227e-183a-40e5-b75a-68c6e01fb9b9.png)

Wie in der Abbildung zu erkennen ist, enthält der von Musgrove verwendete Datensatz (links) nicht die gleichen Berufsbezeichnungen wie der Datensatz dieser Masterarbeit (rechts). Jedoch werden für die vorliegende Studie relevante Berufe durch Data-Scientist, Data-Engineer, Business-Intelligence (eigentlich Data-Analyst) sowie Data-Analyst vertreten. 

Auf der linken Grafik ist zu erkennen, dass die Berufe Data-Scientist, Data-Engineer sowie Business-Intelligence zwar schwache, jedoch sichtbare Cluster bilden. Die Punkte, die den Beruf Data-Analyst repräsentieren, sind deutlich zerstreut, was wiederum dafürspricht, dass dieser Beruf eher generalistisch ist. Bei der Anwendung der gleichen Klassifikationsanalyse auf den in dieser Arbeit verwendeten Datensatz konnte festgestellt werden, dass keine Cluster gebildet werden konnten. Die Punkte, die verschiedene Berufe repräsentieren, sind zerstreut, sodass kein Muster ermittelt werden kann.

Einen weiteren Beleg für die oben aufgeführte These liefert die manuelle, stichprobenartige Analyse der Stellenanzeigen für Data-Science, bei der festgestellt werden konnte, dass in den meisten Fällen bei großen Unternehmen eine Uneinigkeit darüber herrscht, welche Aufgaben von einem Data-Scientist zu erfüllen sind. Während Zeiss eher einen Machine-Learning-Engineer sucht, so erwartet die Deutsche Bahn, dass ein Data-Scientist die Aufgaben eines Systemadministrators und Data-Engineers übernimmt.

![image](https://user-images.githubusercontent.com/77071620/178105698-53725abb-06ac-4905-b107-f944b25d5e94.png)


## 5 Fazit

Diese Arbeit verfolgte das Ziel, anhand eines Anforderungsprofils Stellenanzeigen für die oben genannten Berufe zu analysieren. Die Aufgabe bestand darin, herauszufinden, welche Erfahrungen, Kenntnisse und Fähigkeiten von Bewerbenden verlangt werden.

Im Hinblick auf die Forschungsfrage wurden Stellenanzeigen aus verschie-denen Stellenportalen extrahiert, bereinigt und anschließend analysiert.

Anhand dieser Analyse konnte festgestellt werden, dass ein Hochschulabschluss nur in 61 % der analysierten Stellenanzeigen verlangt bzw. erwähnt wird, wobei in ca. 70 % der Fälle ein Bachelorabschluss ausreichend ist. 

Die am häufigsten erwähnten Studiengänge sind Informatik (54 %), Mathematik (31 %), Statistik (21 %) und Wirtschaftsinformatik (16 %). Jedoch sind auch an-dere, nicht IT-nahe Studiengänge wie VWL (11 %) und BWL (8 %) in der Auswertung vertreten.

Die Menschen, die sich für die Berufe interessieren, müssen in der Lage sein, zu programmieren und Daten zu visualisieren. 

Bei den Programmiersprachen erreichen Python und SQL besonders hohe Anteile. Insgesamt werden diese fast in 100 % aller Stellenbeschreibungen (2311) erwähnt. Um die Daten visuell darzustellen, werden Kenntnisse in gängigen Visualisierungs-Tools wie Microsoft PowerBI und Tableau benötigt.

Außerdem müssen sich Bewerbende mit einer großen Anzahl von Technolo-gien und Plattformen auskennen. Durch die Verlagerung der Prozesse in die Cloud sind Erfahrungen mit Azure, AWS, Google Cloud, Snowflake und Databricks besonders beliebt. Darüber hinaus sind Kenntnisse in folgenden Technologien bei der Arbeit mit Daten vorteilhaft: Git, Datenbanken, Docker, ETL, Hadoop, Airflow und Microsoft Excel. 

Aufgrund vieler Berührungspunkte mit verschiedenen Fachabteilungen müs-sen die Bewerbenden kommunikativ und lösungsorientiert sein sowie über analytisches Denkvermögen und Präsentationsfähigkeit verfügen.

Die tägliche Arbeit wird meistens in Projekten abgewickelt, weshalb Erfahrungen mit den agilen Projektmanagementmethoden hilfreich sind. Dazu kommt ein hoher Grad der Internationalisierung und dementsprechend benötigte Kenntnisse der englischen Sprache.

Zudem wurde in der Analyse festgestellt, dass die Anforderungen der Unter-nehmen an einzelne Berufe sich in diesem Datensatz nicht unterscheiden. Durch die Anwendung eines Klassifikationsmodells konnte ermittelt werden, dass die Anforderungen an verschiedene Berufe keine Cluster bilden, was für ein geringes Verständnis der Aufgabengebiete einzelner Berufe spricht.

Abgesehen von dem allgemeinen Verständnis über die Anforderungen an datengetriebene Berufsfelder liefern die Ergebnisse der Analyse nützliche Erkenntnisse für Unternehmen sowie Bildungseinrichtungen. 

Unternehmen können die Erkenntnisse aus der Analyse nutzen, um maßgeschneiderte, berufsbezogene Stellenbeschreibungen zu erstellen, wenn dies möglich ist.

Die Bildungseinrichtungen wie Hochschulen und Universitäten können die Ergebnisse verwenden, um die Entwicklung von in der Zukunft benötigten Fähigkeiten und Kompetenzen, unabhängig vom Studienschwerpunkt, bei Studierenden zu fördern und den Fokus ihrer Ausbildung praxisnaher und digitaler gestalten.

