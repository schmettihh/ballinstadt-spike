> **Konzeptstudie zur Überprüfung von Perspektive und Darstellung.** Kein Spiel und kein fertiges Produkt. Mit Hilfe von KI erstellt, um Ansichten, Grafikstile und die Spielidee zu prüfen. Familie Lewin und alle Namen sind erfunden; die historischen Angaben sind nicht fachlich geprüft.
>
> Ansehen: https://schmettihh.github.io/ballinstadt-spike/ · Quellen und Ableitung: [RESEARCH.md](RESEARCH.md)
>
> Der folgende Text ist das ursprüngliche Briefing der Studie.

---

Du bist gleichzeitig **Historical Researcher, Game Designer und Senior Frontend Engineer**.

Erstelle einen **kleinen, direkt spielbaren HTML-Game-Spike für „Ballinstadt“**.

Das Wichtigste: **Erfinde die Architektur und Raumaufteilung nicht einfach. Recherchiere zuerst, wie die historischen Auswandererhallen auf der Veddel tatsächlich aufgebaut waren, und leite daraus die Spielkarte ab.**

Der Prototyp soll anschließend zeigen, wie sich dieser historische Ort als **isometrische Management-/Decision-Simulation** spielen und darstellen lässt.

---

# 1. Ausgangspunkt

Das Projekt ist eine Management-Simulation über die Auswandererhallen in Hamburg-Veddel zwischen **1901 und 1914**.

Die Spielerin leitet die Hallen aus Sicht der Reederei.

Der zentrale Ablauf ist:

**Ankunft → Registrierung → Untersuchung → Unterbringung → Einschiffung**

Dabei entstehen Einzelfälle, bei denen Menschen nicht einfach abstrakte Ressourcen sind, sondern konkrete Personen mit Namen, Familien, Hoffnungen und Konsequenzen.

Das Spiel soll nicht primär eine große Stadt oder ein Tycoon-Spiel simulieren.

**Ein Ort. Ein Ablauf. Viele Fälle.**

Das ist ein zentraler Designgrundsatz des Projekts.

---

# 2. ERST RECHERCHIEREN – DANN BAUEN

Bevor du Code schreibst, recherchiere online möglichst gründlich die historische Anlage der **Auswandererhallen / BallinStadt auf der Veddel**.

Suche insbesondere nach:

* historischen Lageplänen
* Bauplänen
* Grundrissen
* Karten
* historischen Fotografien
* Luftbildern, soweit verfügbar
* Museumsinformationen
* architektonischen Beschreibungen
* historischen Dokumenten
* Informationen über die einzelnen Hallen und Gebäude
* Wegeführung
* Eingänge und Ausgänge
* Schlafbereiche
* Speisebereiche
* Untersuchungs-/Desinfektionsbereiche
* Verwaltungsbereiche
* Aufenthaltsbereiche
* sanitäre Einrichtungen
* Gepäck / Logistik
* Verbindung der Gebäude untereinander

Priorisiere:

1. **BallinStadt Museum / offizielle historische Quellen**
2. Stadt-/Archivquellen aus Hamburg
3. historische Karten und Pläne
4. wissenschaftliche bzw. museale Quellen
5. historische Fotografien

Verwende Suchbegriffe sowohl auf Deutsch als auch auf Englisch, z.B.:

* „BallinStadt historische Grundriss“
* „Auswandererhallen Veddel Lageplan“
* „Auswandererhallen Hamburg Bauplan“
* „Ballinstadt Veddel historische Karte“
* „Auswandererhallen Veddel Hallen“
* „BallinStadt 1901 Grundriss“
* „Hamburg Veddel Auswandererhallen architecture“
* „Ballinstadt historical site plan“

---

# 3. RECHERCHE NICHT NUR ALS TEXT VERWENDEN

Die Recherche soll nicht nur dazu dienen, historische Fakten in einem Infofenster anzuzeigen.

Sie soll die **Spielkarte selbst beeinflussen**.

Wenn du beispielsweise feststellst, dass bestimmte Gebäudekomplexe historisch anders angeordnet waren als eine typische Management-Simulation sie darstellen würde, übernimm die historische Struktur.

Wenn es unterschiedliche Gebäudetypen gab, überlege:

**Welche davon eignen sich als spielbare Bereiche?**

Wenn eine genaue historische Raumaufteilung nicht zuverlässig rekonstruierbar ist, kennzeichne die Unsicherheit intern und treffe eine **bewusste, plausible Game-Design-Entscheidung**, statt eine scheinbar exakte historische Tatsache zu erfinden.

---

# 4. ZIEL: HISTORISCHE KARTE → SPIELBARE KARTE

Entwickle aus der Recherche eine vereinfachte spielbare Karte.

Die Karte soll sich so anfühlen, als wäre sie aus einem:

**historischen Lageplan + architektonischen Bauplan + isometrischen Strategiespiel**

entstanden.

Nicht wie eine moderne Game-Map.

Die historische Struktur darf dabei abstrahiert werden.

Das Ziel ist:

**historisch glaubwürdige Geometrie + gute spielerische Lesbarkeit.**

---

# 5. ISOMETRISCHE DARSTELLUNG

Die gesamte Szene soll **isometrisch** dargestellt werden.

Dabei darfst du dich visuell an folgenden Dingen orientieren:

* historische Bauzeichnungen
* alte Lagepläne
* technische Grundrisse
* historische Stadtpläne
* architektonische Schnittzeichnungen
* frühe 20.-Jahrhundert-Illustrationen

Die Spielwelt könnte beispielsweise wirken wie eine:

**lebendige historische Bauzeichnung in isometrischer Perspektive.**

Wichtig:

Nicht einfach ein normales Top-Down-Spiel um 45° drehen.

Die Architektur soll bewusst für die isometrische Ansicht gestaltet werden.

---

# 6. VISUELLE SPRACHE

Die Grafik soll nicht nach generischem Pixel-Art-Asset-Pack aussehen.

Suche stattdessen eine visuelle Sprache zwischen:

**historischem Hamburg + Architekturzeichnung + isometrischem Indie-Game.**

Mögliche visuelle Eigenschaften:

* rote / braune Backsteine
* dunkle Holzkonstruktionen
* helle Putzflächen
* gealtertes Papier
* technische Linien
* dezente Grundriss-Markierungen
* gedeckte Farben
* dunkles Grau
* Sepia-/Creme-Töne
* gedämpftes Grün und Blau
* historische Beschriftungen
* feine Schraffuren
* sichtbare Materialität
* leichte Unregelmäßigkeiten

Die Szene darf durchaus aussehen, als wäre sie **aus einem historischen Plan herausgebaut worden**.

Aber:

Sie muss trotzdem ein Spiel bleiben.

Personen, Wege und wichtige Interaktionen müssen sofort erkennbar sein.

---

# 7. DIE KARTE SOLL SPIELERISCH LESBAR SEIN

Nachdem du die historische Anlage untersucht hast, identifiziere die wichtigsten Spielbereiche.

Beispielsweise könnten sich aus der Recherche Bereiche wie diese ergeben:

* Ankunft
* Registrierung
* Verwaltung
* Untersuchung
* Desinfektion
* Unterbringung
* Essen / Aufenthalt
* Gepäck
* Warten
* Einschiffung

Aber:

**Übernimm diese Liste NICHT blind.**

Entscheide anhand der historischen Recherche, welche Bereiche tatsächlich existierten und welche davon für den Prototypen relevant sind.

Die Spielerin soll die Bewegung der Menschen nachvollziehen können.

Zum Beispiel:

**Eingang → Registrierung → Untersuchung → Warten → Unterbringung → Einschiffung**

Die Wege selbst sind Teil des Gameplays.

---

# 8. DER ORT IST DIE HAUPTFIGUR

Die Karte soll nicht bloß Hintergrund sein.

Der Ort selbst soll vermitteln:

* Kontrolle
* Warten
* Enge
* Durchsatz
* Ordnung
* Bürokratie
* medizinische Untersuchung
* menschliche Nähe
* Familien
* Gepäck
* Zeitdruck

Der Spieler soll nach kurzer Zeit verstehen:

**Hier werden Menschen durch einen organisatorischen Prozess bewegt.**

Und genau darin liegt der Konflikt des Spiels.

---

# 9. MENSCHEN ALS TEIL DER KARTE

Zeige viele kleine Menschen in der Szene.

Aber nicht als abstrakte Einheiten.

Es soll Gruppen geben:

* Familien
* Einzelreisende
* Kinder
* ältere Menschen
* Mitarbeiter
* Ärzte / medizinisches Personal
* Verwaltung
* Gepäckträger

Menschen sollen sich entlang der tatsächlichen Wege bewegen.

Eine Familie kann beispielsweise gemeinsam von der Registrierung zur Untersuchung gehen.

Eine Person kann warten.

Ein Mitarbeiter kann einen anderen Bereich betreten.

Ein Gepäckstück kann bewegt werden.

Dadurch wird die Karte lebendig.

---

# 10. EIN EINZIGER STARKER SPIELFALL

Baue nicht zehn verschiedene Systeme.

Baue **einen wirklich gut sichtbaren Fall**.

Beispiel:

Eine Familie wird untersucht.

Bei einem Familienmitglied besteht ein unklarer Verdacht.

Das Schiff fährt am nächsten Morgen.

Die Spielerin muss entscheiden:

* Familie trennen
* Familie zurückhalten
* Familie gemeinsam weiterreisen lassen

Die konkrete Entscheidung soll nicht über abstrakte Moralwerte funktionieren.

---

# 11. KONSEQUENZEN MÜSSEN AUF DER KARTE SICHTBAR SEIN

Das ist besonders wichtig.

Die Entscheidung verändert den Zustand der Karte.

Beispielsweise:

### Entscheidung: Sohn bleibt zurück

Die Eltern gehen weiter.

Der Sohn bleibt in einem Raum zurück.

Später sieht man ihn allein.

### Entscheidung: Familie wartet

Die Familie sitzt weiterhin in der Unterkunft.

Ein Bett bleibt belegt.

Der Weg zur Einschiffung findet für sie nicht statt.

### Entscheidung: Alle fahren

Die Familie verlässt die Halle gemeinsam.

Später erscheint ein Telegramm.

Die Familie kommt möglicherweise zurück.

**Die Konsequenz soll physisch im Raum erscheine**
