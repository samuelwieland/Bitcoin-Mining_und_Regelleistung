# Steigender Regelleistungsbedarf – Wie Bitcoin-Mining helfen kann
<i>Blog Beitrag zu Bitcoin-Mining & Regelleistung, Publiziert am 21.11.22, Autor Samuel Wieland</i>

Dieser Beitrag ist dazu gedacht meine gesammelten Ideen zum Bitcoin-Mining zu teilen und ein paar spannende Aspekte in die Diskussion zu bringen. Ich beginne mit der Problemstellung, dann gebe ich eine kurze Erklärung zum Bitcoin-Mining, beschreibe einige Anwendungsbeispiele und fasse zusammen, wie das Bitcoin-Mining für die Stromversorgung von Nutzen sein kann. Abschliessend werfe ich einen Blick in die Zukunft und führe mögliche Schwierigkeiten und philosophische Überlegungen zum Bitcoin-Mining zusammen.

![image](https://user-images.githubusercontent.com/93722117/202992023-58aa16a6-7718-4eaf-a4b5-f96bbae426e4.png)

<i>Quelle: [Bitcoin is An Idea](https://dergigi.com/2021/06/13/bitcoin-is-an-idea/)</i>

## Was ist das Problem?
Mit der erzielten Energiewende nimmt der Ausbau der erneuerbaren Energien (EE) stetig zu. Damit erhöht sich der EE-Anteil im Elektrizitätsmix und Stromnetzbetreiber sind mit der Aufgabe konfrontiert diese schwankende und unzuverlässige Energie bestmöglich zu prognostizieren und zu regeln. Oft ist der Ausbau grösserer EE-Projekte nicht ökonomisch und muss durch staatliche Subventionen vorangetrieben werden. Ein Beispiel dafür ist die kostendeckende Einspeisevergütung für EE in der Schweiz, welche gegen Ende dieses Jahres auslauft. Eine Einmalvergütung wird danach zum Hauptfördersystem für neue PV-Anlagen.

## Was sind die Folgen?
Um eine stabile Stromversorgung zu gewährleisten, müssen grössere Regelleistungskapazitäten ans Netz kommen. Es wird schnell verfügbare positive und insbesondere negative Regelleistung benötigt zur Absorption von Produktionsspitzen. Dies wird bisher teilweise durch Drosseln von Kraftwerken erreicht, was für diese zusätzliche Opportunitätskosten verursacht, die am Schluss beim Konsumenten landen. Zusätzlich ist das Stromnetz noch nicht bereit grosse Leistungen (z.B. aus zukünftigen alpinen EE-Projekten) zu Produktionsspitzenzeiten an den Verbrauchsstandorten zu transportieren.

## Was ist Bitcoin-Mining?
Bitcoin ist die erste und stärkste Kryptowährung und bildet seit 2009 ein dezentrales Buchungssystem ohne Intermediäre. Um den dafür benötigten dezentralisierten Hauptbuch unveränderlich und zensurresistent zu machen, benutzt der Bitcoin-Netzwerk ein <i>Proof of Work</i> System. Mit einem solchen Rechenleistungsnachweis wird zum Beispiel auch E-Mail-Spam verhindert. Wegen Analogien zum Goldschürfen, wird dieser Prozess beim Bitcoin auch <i>Bitcoin-Mining</i> genannt.

Beim Mining werden Transaktionen in einem Block zusammengenommen und die <i>Miner</i> wenden Rechenleistung auf, um den nächsten gültigen Block ans Hauptbuch hinzuzufügen. Das Hauptbuch ist deshalb eine Kette solcher Blöcke, eine Blockchain. Die Rechenleistung wird benötig, um eine kryptographische Aufgabe zu lösen, die man als ein wildes um die Wette Würfeln vorstellen kann. Anreiz für die Miner zum Bitcoin schürfen ist die Summe aller Transaktionsgebühren im Block und neu geschöpfte Bitcoin. Momentan liegt diese Belohnung bei 6.25 Bitcoin (ca. 125'000 CHF) und ein gültiger Block wird im Durschnitt alle 10 Minuten gefunden. Dies ist so im Code mit einer Anpassung der Schwierigkeit festgelegt, die sogenannte <i>difficulty adjustment</i>.

### Bitcoin-Mining in Zahlen
Das Bitcoin Mining Council schätzt, dass der nachhaltige Energiemixanteil aller Bitcoin-Miner bei 59.4% liegt. Dies wurde aus einer Umfrage für das dritte Quartal erhoben, bei der Miner mit zusammengerechnete fast die Hälfte des Netzwerks teilgenommen haben. Bitcoin-Mining schneidet damit besser als die meisten Industrien ab. Zum Vergleich sitzt Deutschlands Stromverbrauch bei 48.5%.

Bitcoin-Mining benutzt geschätzte 266TWh und ist daher vergleichbar mit dem Verbrauch von Computerspielen oder Weihnachtsbeleuchtungen.

Eine Cambridge Studie rechnet, dass die Miner mit einem durchschnittlichen Strompreis von 5 Cent pro kWh operieren. Für jeden Cent höher nähert sich die Profitabilitätsgrenze. Somit ist es in der Schweiz nicht rentabel zu schürfen, wo sogar der Industrie und Grossverbraucher Strompreis letztes Jahr zwischen 15-20 Rp. Pro kWh lag. Dies widerlegt die Aussage, dass Bitcoin-Mining ein Stromfresser sei, der den Haushältern den Strom wegnehme.

Die Hash-Rate des Bitcoin-Netzwerks liegt bei über 260 EH/s (Exa-Hash pro Sekunde). Damit ist die Anzahl kryptografische Berechnungen (230 Quintillionen Hashwerte pro Sekunde) gemeint, die pro Sekunde global stattfinden. Einer der neusten ASICs, der Antminer S19 Pro vom letzten Jahr, verbraucht gerade mal 21.5 J/Th (Joule pro Terra-Hash).

### Anwendungsbeispiele fürs Bitcoin-Mining
Obwohl das Mining in den Anfangsjahren mit handelsüblichen Computern möglich war, ist die Schwierigkeit des Minings so weit angestiegen, dass dies schnell unwirtschaftlich wurde. Heutzutage werden <i>anwendungsspezifische integrierte Schaltungen</i> (ASIC) fürs Mining verwendet. In grossen spezialisierten Mining-Farmen (Rechenzentren/ Serverzentren) werden solche ASICs so effizient wie möglich zusammengeschaltet, um möglichst viel Rechenleistung zu erzielen. Mining-Farmen sind daher auf die neusten ASICs, günstigen und konstanten Strom sowie eine effiziente Kühlung angewiesen, um wirtschaftlich zu sein.

Auch wird Mining eingesetzt, um unbenutzte Energien zu verwerten. Sei das beispielsweise bei grossen Wasserkraftwerken in China, die keinen Abnehmer in Reichweite haben, beim sonst abgefackelten Flaring-Gas, welches bei der Ölförderung auftritt, oder bei biologische Abfallverbrennungen. Gemeinsamkeiten haben diese Beispiele, dass sie billige Energie bieten, die mit möglichst effizienten Prozessen in Elektrizität umgewandelt werden. Diese günstige Elektrizität eignet sich dann wiederum fürs Mining.

Weiter gibt es Anwendungen, wo die Abwärme genutzt wird. Indem zum Beispiel übliche Elektroheizungen mit ASICs ersetzt werden, Trocknungsanlagen in der Industrie auf Mining-Abwärme umsteigen oder auch Treibhausplantagen die Temperatur somit aufrechterhalten. Öl-, Gas- und Strompreise, wie auch Umbaukosten, müssen dafür in Betracht gezogen werden, um einen Mehrnutzen aus der Abwärme des Bitcoin-Minings zu erzielen.

## Wie passt Bitcoin-Mining in die Stromversorgung?
Es ist wichtig zu bemerken, dass dieser Beitrag sich in erster Linie mit dem Bitcoin-Mining beschäftigt und nicht mit Bitcoin an sich als Anlage-, Finanzprodukt oder Transaktionsmittel. Kurz gesagt bietet das Bitcoin-Mining das folgende: einen flexiblen orts- und zeitunabhängigen Stromabnehmer letzter Instanz, der überschüssigen Storm direkt monetarisiert und Wärme als Nebenprodukt hat.

Konkret, aber nicht abschliessend, sind folgende Anwendungen für eine zuverlässige Stromversorgung relevant. Grosse Mining-Anlagen, die nur mit günstigem Strom profitabel betrieben werden, können aus eigenem Interesse in Zusammenarbeit mit den Netzbetreibern bei der Laststeuerung helfen. Positive Regelleistung kann durch sekundenschnelles Abschalte der Mining-Geräte freigegeben werden. Dies hat bereits dieses Jahr bei einer Hitzewelle in Texas genau so stattgefunden. Aber auch negative Regelleistung durch hochfahren mehrere ASICs erlaubt Flexibilität in die andere Richtung.

Den wohl geeignetsten Fall für negative Regelleistung ist das Peak-Shaving bei Solar- und Windstrom. Zu Spitzenzeiten wird mit dem Ausbau der EE mehr Strom produziert werden als gebraucht, so dass diese Stromproduzenten sogar zahlen müssten, um die Energie ins Netz zu speisen. Daher wird das Absorbieren dieser Spitzen auch mit älteren ASICs möglich, solange die Einspeisung nicht subventioniert wird und Batterien diesen Markt nicht im grossen Stil übernehmen. Dies kann überall direkt bei den Anlagen vor Ort stattfinden. Es ist nur ein Platz für die Miner (zum Beispiel in einem Container) und eine Internetverbindung nötig. Spätestens mit dem globalen Internetzugang durch Sattelitennetzwerke kann dies an jedem beliebigen Ort stattfinden.

Diese zusätzliche Möglichkeit Strom direkt in Wert umzuwandeln bietet einen Anreiz mehr EE auszubauen und auch grössere Projekte profitabel zu realisieren.

Weiter gibt es Anwendungen, die nicht direkt mit der Stromversorgung verknüpft sind. Die allgemeine Monetarisierung überschüssiger Energie, die in Strom umgewandelt werden kann, ist eine davon. Eine andere ist die Nutzung des Nebenprodukts Wärme. Sicher sind noch weitere Anwendungen möglich an denen bisher noch niemand gedacht hat.

## Ausblick in die Zukunft?
Die hier präsentierte Idee wird bei der Umsetzung auch sicherlich auf ein paar Schwierigkeiten treffen. Zum einen reduziert der volatile Marktpreis von Bitcoin die Bereitschaft von Minern längere Verträge einzugehen. Weiter steht das Bitcoin-Mining als Wertspeicherung mit physikalischen Speicherkapazitäten in Konkurrenz. Falls Pumpspeicherkraftwerke oder Batterien in Zukunft ökonomisch ausgebaut werden können, werden diese das Mining aus manchen Marktsektoren verdrängen.

Dann weiter auf menschlicher Ebene sind Regulierungen gegen Bitcoin-Mining und auch strikte Verbote wegen Netzüberlastungen möglich. Wobei das Mining bei liberalen Marktkonditionen eher Hilfe als Bürde sein wird, da diese so nahe an der Profitabilitätsgrenze agieren. Zudem ist es ein sehr neues Thema und Wissen noch nicht weit verbreitet. Sogar noch schlimmer haben es vermehrt Missverständnisse und schlechte Vorurteile es in den Schlagzeilen geschafft, was oft eine ablehnende erste Reaktion bewirkt.

Zusammenfassend heben sich die positiven Aspekte hervor. Bitcoin-Mining bietet eine neue Einnahmequelle und Vermögensoptimierung. Bitcoin-Mining bietet Regelleistung zur Nachfragesteuerung und Lastausgleich. Bitcoin-Mining hilft bei der Steuerung und Planung des Übertragungs- und Verteilnetzes. Die direkte Umwandlung von Elektrizität, oder allgemein verfügbare Energie, in einem monetären Wert ist in dieser Form noch nie da gewesen. Es ermöglicht etwas zu verkaufen, was man vorher nicht verkaufen konnte.

Einige der grossen Bitcoin-Denker, wie Michael Saylor oder Jeff Booth, sind sogar der Meinung, dass in Zukunft Bitcoin-Miner und Stromproduzenten ein und dieselbe Identität sein werden und dass Bitcoin zur direkten Wertbemessung der Energie werden kann.

# 
**TL;DR:** Bitcoin-Mining bietet als flexibler orts- und zeitunabhängiger Stromabnehmer eine ökonomische Möglichkeit elektrischen Strom direkt und effizient in einem monetären Wert umzuwandeln. Mit steigendem Anteil an erneuerbaren Energien im Elektrizitätsmix unterstützt Bitcoin-Mining eine sichere Stromversorgung, indem es positive und negative Regelleistung zur Verfügung stellt.
