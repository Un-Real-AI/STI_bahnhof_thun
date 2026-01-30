
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

<div class="embed-wrap" style="--embed-height: 700px;">
  <iframe
    class="embed"
    src="korridor-analyse/Htmls/corridor_map.html"
    title="ÖV-Korridore: Karte"
    loading="lazy"
    referrerpolicy="no-referrer"
  ></iframe>
</div>
<div class="embed-caption">ÖV‑Korridore zum Bahnhof Thun.</div>

Die wichtigsten Korridore nach Anzahl ÖV-Fahrten sind:
<div class="embed-wrap" style="--embed-height: 640px;">
  <iframe
    class="embed"
    src="korridor-analyse/Htmls/bar_corridors_merged_sum_ov_nocategory.html"
    title="Korridor Nachfrage: Balkendiagramm"
    loading="lazy"
    referrerpolicy="no-referrer"
  ></iframe>
</div>
<div class="embed-caption">Korridor Nachfrage – Durchschnittliche Werktagsfahrten, 2025.</div>

## Bahnhof Thun: Erste/Letzte Meile
Analyse der Ersten/Letzten Meile am Bahnhof Thun
Mit fast 22’000 Fahrten pro Werktag starten oder enden mit Abstand die meisten Fahrten in der unmittelbaren Umgebung des Bahnhofs Thun – beziehungsweise innerhalb der 1-km²-Kachel, auf der sich der Bahnhof befindet. Daraus ergibt sich für den Standort ein erhebliches Potenzial für die «Erste/Letzte Meile», was die Rolle des Bahnhofs als zentralen Ziel- und Quellpunkt für den lokalen Verkehr unterstreicht.

Die vorliegenden Daten verdeutlichen folgende Schwerpunkte:
- Zentralität und Netzwirkung: Ein Grossteil der Fahrten, die über den Bahnknoten verlaufen, hat ihren Ursprung oder ihr Ziel direkt im unmittelbaren Umfeld des Hubs. Eine effiziente Anbindung für diese Erste/Letzte Meile ist daher von entscheidender Bedeutung für die Gesamtleistung und Attraktivität des öffentlichen Verkehrsnetzes.

- Integration der Buslinien: Dies betrifft massgeblich auch jene Buslinien, die Haltestellen innerhalb der Bahnhofskachel bedienen. Diese Linien übernehmen einen wesentlichen Teil der Feinerschliessung und fungieren als direkte Zubringer für die Erste/Letzte Meile.

- Verkehrsmittelwahl und Datengrundlage: Aus den Mobilfunkdaten ist ohne vertiefende Analyse nicht direkt ersichtlich, welcher Anteil dieser Fahrten zu Fuss, mit dem Velo, mit dem Auto oder mit dem Bus zurückgelegt wird. 

# Umsteigebeziehungen
---

Hinweis: Matrizen für die Bus <-> Bus, und Zug <-> Bus Korridor Umsteigebeziehung sowie eine tabellarische Darstellung aller Korridor Umsteigebeziehungen sind im Abschnitt [Korridor Analyse](#balkendiagramm-treemap) hinterlegt. 

---

### Top-Korridor-Umsteigebeziehungen
Die folgende Matrix stellt die Umsteigebeziehungen zwischen den Korridoren dar:

<div class="embed-wrap" style="--embed-height: 700px;">
  <iframe
    class="embed"
    src="umsteigebeziehungen/Htmls/corridor_matrix_all_ov_symmetric.html"
    title="Alle Korridore (symmetrisch)"
    loading="lazy"
    referrerpolicy="no-referrer"
  ></iframe>
</div>
<div class="embed-caption">Korridor Umsteigebeziehungen.</div>


Die mit Abstand wichtigste Umsteigebeziehung besteht zwischen dem unmittelbaren Einzugsgebiet des Bahnhofs (HUB – Thun Bahnhof) und dem Fernverkehr in Richtung Bern/Zürich mit über 4'200 täglichen Fahrten. Ein weiteres zentrales Muster ist die starke Kopplung des STI-Busnetzes an die SBB-Achse Bern–Zürich und Spiez Brig Interlaken.

Der Korridor Stocken/Pohlern weist mit fast 1'170 Fahrten die stärkste direkte Anbindung eines STI-Aussenkorridors an den Fernverkehr auf. Interessanterweise zeigt die Datenlage, dass die Umsteigebedürfnisse zum Fernverkehr (Richtung Bern) deutlich dominanter sind als die zum Regionalverkehr (z.B. BLS S1 oder S44), was die hohe Bedeutung kurzer und verlässlicher Wege für Pendler zwischen Bus und IC-Zügen unterstreicht. 

| Korridor A | Korridor B | Anzahl Korridor Umsteiger |
| :--- | :--- | :--- |
| HUB – Thun Bahnhof | SBB IC/EC/ICE – Bern (z.B. Zürich) | 4'233.9 |
| HUB – Thun Bahnhof | SBB IC/EC/ICE – Spiez Brig Interlaken | 2'849.4 |
| BLS S1 – Freiburg/Fribourg ↔ Bern | HUB – Thun Bahnhof | 1'279.2 |
| SBB IC/EC/ICE – Bern (z.B. Zürich) | Stocken/Pohlern (z.B. Bus 3) | 1'169.4 |
| BLS S44/S4 – Gürbetal/Seftigen | HUB – Thun Bahnhof | 1'066.0 |
| BLS S41/S42 – Heimberg/Steffisburg | SBB IC/EC/ICE – Spiez Brig Interlaken | 648.7 |
| SBB IC/EC/ICE – Spiez Brig Interlaken | Stocken/Pohlern (z.B. Bus 3) | 576.8 |
| BLS S44/S4 – Gürbetal/Seftigen | SBB IC/EC/ICE – Spiez Brig Interlaken | 517.9 |
| BLS S41/S42 – Heimberg/Steffisburg | HUB – Thun Bahnhof | 425.0 |
| BLS S1 – Freiburg/Fribourg ↔ Bern | SBB IC/EC/ICE – Spiez Brig Interlaken | 421.8 |
| BLS S44/S4 – Gürbetal/Seftigen | Stocken/Pohlern (z.B. Bus 3) | 395.6 |
| SBB IC/EC/ICE – Bern (z.B. Zürich) | Thunersee-Nordufer (z.B. Bus 21) | 389.8 |
| SBB IC/EC/ICE – Bern (z.B. Zürich) | Steffisburg-Korridor (z.B. Bus 41/42/43) | 381.4 |
| BLS S1 – Freiburg/Fribourg ↔ Bern | Stocken/Pohlern (z.B. Bus 3) | 358.5 |
| SBB IC/EC/ICE – Spiez Brig Interlaken | Steffisburg-Korridor (z.B. Bus 41/42/43) | 327.9 |
| BLS S41/S42 – Heimberg/Steffisburg | SBB IC/EC/ICE – Bern (z.B. Zürich) | 327.2 |
| SBB IC/EC/ICE – Bern (z.B. Zürich) | Spiez/Einigen (z.B. Bus 1) | 266.7 |
| BLS S41/S42 – Heimberg/Steffisburg | Stocken/Pohlern (z.B. Bus 3) | 185.1 |
| HUB – Thun Bahnhof | Stocken/Pohlern (z.B. Bus 3) | 160.2 |
| SBB IC/EC/ICE – Spiez Brig Interlaken | Thunersee-Nordufer (z.B. Bus 21) | 152.6 |

**Hinweise zur Tabelle:**
- Die Liste zeigt die kumulierte Nachfrage in beide Richtungen (symmetrisch).
- Der Korridor HUB – Thun Bahnhof repräsentiert die Erste/Letzte Meile (Fahrten, die im unmittelbaren Bahnhofsumfeld starten oder enden).
- Besonders stark frequentiert sind die Anschlüsse zwischen dem lokalen Busnetz (z. B. Bus 3) und dem Fernverkehr in Richtung Bern/Zürich.

*Die vollständige Tabelle steht im Abschnitt Korridor Analyse zum Download zur Verfügung*

# Empfehlung
- **Fokus auf Fernverkehrs-Anschlüsse**: Die Feinerschliessung des STI-Busnetzes muss konsequent auf die SBB-Achsen Richtung Bern/Zürich und Spiez/Interlaken ausgerichtet werden, da hier die höchste Umsteigedynamik besteht (allein über 4'200 Fahrten zwischen Hub und Fernverkehr Bern).

- **Priorisierung Korridor Stocken/Pohlern**: Der Korridor weist die stärkste direkte Anbindung eines STI-Korridors an den Fernverkehr auf und sollte priorisiert werden um verlässliche Umsteigewege sicherzustellen.

- **Optimierung der Ersten/Letzten Meile**: Da täglich rund 22’000 Fahrten direkt im unmittelbaren Bahnhofsumfeld (1-km²-Kachel) starten oder enden, ist die lokale Feinerschliessung durch Bus, Fuss- und Veloverkehr als zentraler Ziel- und Quellpunkt zu stärken.

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



