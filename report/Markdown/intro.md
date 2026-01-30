
# Einleitung und Ausgangslage: 

Mit dem Projekt „Entwicklungsschwerpunkt (ESP) Bahnhof Thun“ plant die Stadt Thun eine umfassende Transformation des Bahnhofsareals, um dieses als moderne, multimodale Verkehrsdrehscheibe und attraktives Stadtquartier zu stärken. Ein zentrales Element dieser Planung ist die Neugestaltung des öffentlichen Raums sowie die Reorganisation der Verkehrsflüsse.

Für die STI Bus AG als Hauptakteurin im lokalen ÖV ist dabei entscheidend, dass die städtebauliche Aufwertung nicht zu Lasten der ÖV-Anbindungen geht. Insbesondere die geplante Neuordnung der Bushaltestellen könnte durch veränderte räumliche Anordnungen die Laufwege der Fahrgäste und die Effizienz beim Umsteigen beeinflussen.

Im Rahmen dieses Projekts untersuchen wir auf Basis von mobilfunkbasierten Nachfragedaten, welche Umsteigebeziehungen am Bahnhof Thun die meiste Nachfrage haben. Dies dient als Grundlage für eine datenbasierte Priorisierung der wichtigsten Umsteigebeziehungen im Rahmen der geplanten baulichen Veränderungen.

Ziel ist es, eine datengestützte Entscheidungsgrundlage zu schaffen, um die ÖV-Anschlüsse frühzeitig zu bewerten und gegebenenfalls optimierende Massnahmen in die weitere Planung des ESP Bahnhof einzubringen. Im ersten Schritt wurde die Nachfrage auf Korridor Niveau analysiert. Eine feiner aufgelöste  Analyse ist auf Wunsch möglich. 

**Durch Daten zu Validierende Risikos**
- **Kritische Zeitverluste beim Umsteigen**: Durch die Verschiebung von Kanten (Haltepositionen) könnten die Laufzeiten die Pufferzeiten im Fahrplan überschreiten.

- **Abwanderung durch Komfortverlust**: Falls die Wege zu den neuen STI-Standorten als zu lang oder unübersichtlich wahrgenommen werden, könnte die Nachfrage auf Kurzstrecken sinken.

- **Verschlechterung der Bus-Bus-Anschlüsse**: Wenn die neuen Busperrons weiter auseinanderliegen als heute, könnten Anschlüsse innerhalb des STI-Netzes instabil werden. 

## Methodik und Datengrundlage
Die verwendeten Mobilfunkdaten bieten anonymisierte Quell-Ziel-Bewegungsdaten auf einem 1-km2-Raster für einen durchschnittlichen Wochentag (Mo–Fr) beziehungsweise einen Wochenendtag (Sa oder So). Damit ist die eindeutige Zuordnung auf einzelne Bus- und Zuglinien, die im gleichen Korridor verkehren, nur begrenzt möglich. Wegen dieser Einschränkung haben wir die Nachfrage in erster Linie pro Korridor angegeben. Da ersichtlich ist, welche Angebote im jeweiligen Korridor verkehren, kann auf dieser Basis die Wichtigkeit der jeweiligen Umsteigebeziehungen abgelesen werden (mit der Einschränkung, dass eine scharfe Zuordnung der Fahrgastzahlen auf Bus- und Zuglinien nur als algorithmische Annäherung möglich ist). Wir empfehlen daher in erster Instanz, die Priorisierung der Umsteigebeziehungen pro Korridor beziehungsweise zwischen Korridoren zu betrachten.

Analysiert wurden im ersten Schritt alle Korridore, die den Bahnhof Thun anbinden. Die Korridore lassen sich nach Zug- und Buskorridoren filtern, also Korridoren, die von Bus- beziehungsweise Zuglinien bedient werden.

<div class="callout">
  <strong>Datengrundlage</strong><br>
  Die Analysen basieren auf anonymisierten, mobilfunkbasierten Nachfragedaten. Sofern nicht anders vermerkt, beziehen sich alle Grafiken auf ÖV-Fahrten an einem durchschnittlichen Werktag (Mo–Fr) im Jahr 2025. Für die Analyse wurden sämtliche Fahrten geroutet, wobei eine ungefähre Durchfahrtszeit am Bahnhof Thun um 07:30 Uhr zugrunde gelegt wurde. Dies erlaubt es, die spezifische Nachfrage während der morgendlichen Spitzenstunde am Bahnhof präzise zu erfassen.
</div>


## Interpretation der Korridoranalyse für die Praxis
Obwohl eine Liniengenaue Zuweisung der Nachfrage im ersten Schritt nur begrenzt möglich ist, erlaubt die Analyse auf Korridorebene eine belastbare strategische Einschätzung für die STI. Da die meisten Korridore im Einzugsgebiet Thun durch spezifische Linienbündel klar definiert sind, lassen sich die Hauptlastströme verlässlich identifizieren.

# Korridore
Wie oben dargelegt, analysieren wir die wichtigsten Korridore zum Bahnhof Thun sowie die entsprechenden Umsteigebeziehungen. Dabei führen wir die Bus- und Zuglinien auf, die im jeweiligen Korridor verkehren.

**Hinweis zur Korridor-Logik:**
Die Korridore sind räumlich definiert und korrespondieren nicht zwingend deckungsgleich mit einzelnen Linienverläufen. Das bedeutet beispielsweise, dass eine Buslinie zuerst durch einen westlichen und anschliessend durch einen östlichen Korridor verlaufen kann und somit beiden Korridoren zugeordnet ist. 

Die folgende Karte zeigt  die analysierten ÖV-Korridore zum Bahnhof Thun.

==karte==

Die folgende Tabelle gibt die Korridore, die Anzahl ÖV-Fahrten (durchschnittlicher Werktag Mo-Fr, 2025) und die betroffenen Busse und Züge wieder

==enter table Korridor | Anzahl Fahrten | Busse im Korridor | Züge im Korridor?==

# Umsteigebeziehungen
Im folgenden eine Zusammenfassung der wichtigsten Umsteigebeziehungen am Bahnhof Thun auf Korridor-Niveau.


## Bus zu Bus
Die 

## Bahnhof Thun: Erste/Letzte Meile
Mit Abstand die meisten Fahrten starten oder enden in der unmittelbaren Umgebung des Bahnhofs Thun (beziehungsweise innerhalb der 1-km2-Kachel, auf der sich der Bahnhof befindet). Aus den Mobilfunkdaten ist nicht direkt ersichtlich, welcher Anteil dieser Fahrten zu Fuss, mit dem Velo, mit dem Auto oder mit dem Bus zurückgelegt wird. 

Als Annäherung, nutzen wir den Modal Split der 1-km2-Kachel am Bahnhof Thun als Anhaltspunkt für die wahrscheinliche Verteilung dieser Fahrten. Dies erlaubt eine Einschätzung darüber, wie gross das Potenzial für die jeweiligen Verkehrsmittel im unmittelbaren Einzugsgebiet ist und welche Anforderungen daraus an die Umstiegswege und die Infrastruktur entstehen.

==table modal split / first/last mile==
|Erste/Letzte Meile|Anzahl Fahrten|Anteil
|---|---|---|
|Total|100|100|
|ÖV|00|00|
|LV|00|00
|MIV|00|00

# Empfehlung

# Nächste Schritte
**Optionale Verfeinerung der Analyse**

In einem optionalen zweiten Schritt könnten die bestehenden Analysen weiter vertieft werden, um die Planungsgrundlage für die STI zusätzlich zu schärfen:

* **Wettbewerbsanalyse mit PACE:** Durch die Ermittlung des PACE-Werts (Public Transport against the Car Evaluation) für jeden Korridor lassen sich Reisezeit und Anzahl der Umstiege zwischen dem ÖV und dem motorisierten Individualverkehr (MIV) direkt vergleichen. Dies liefert einen Indikator für die Wettbewerbsfähigkeit des ÖV und zeigt auf, in welchen Korridoren Optimierungspotenzial besteht.
* **Bewertung von Linienvarianten mit dem Line Potential Score (LPS):** Vorschläge für angepasste oder neue Buslinien können mit dem von 42hacks entwickelten LPS bewertet werden. Der LPS berechnet für verschiedene Planungsvarianten, welche Option die höchste Nachfrage generiert. Dies erlaubt es, Szenarien vor der Einführung virtuell zu testen, um das Angebot zielgerichtet zu optimieren und den ÖV-Marktanteil zu erhöhen.
* **Simulation räumlicher Veränderungen am Bahnhof:** Eine LPS-Analyse der bestehenden Linien am Bahnhof Thun würde es zudem erlauben, die geplanten Haltestellenverlegungen präzise zu prüfen. Dabei wird ermittelt, wie viele Fahrgäste von veränderten Fahrzeiten betroffen sind und ob beziehungsweise in welchem Ausmass die Anschlusssicherheit zwischen Bus-Bus- sowie Bus-Zug-Verbindungen durch potenziell längere Gehdistanzen beeinträchtigt wird.

---

# Impressum

**Projekt** 
Analyse der Umsteigeprioritäten im Rahmen des Entwicklungsschwerpunkts Bahnhof Thun

---

**Auftraggeber**
STI Bus AG

**Projektlaufzeit**
Januar 2025 2026

**Stand**
30 Januar 2026

---

**Kontakt**  
Julien McHardy  
julien@42hacks.com  
  
Berg 29    
9043 Trogen    
Zwitserland  
42hacks.com   



