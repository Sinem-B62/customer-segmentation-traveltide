# **Der Kunden-Kompass: Kundensegmentierung für TravelTide**

Dieses Projekt analysiert das Nutzerverhalten des fiktiven Reiseportals TravelTide mittels unüberwachtem maschinellem Lernen. Ziel ist die Entwicklung von datengestützten Kunden-Personas, die als strategische Grundlage für die Konzeption eines personalisierten Prämienprogramms dienen.

## ➡️ Vollständige Projektdokumentation (PDF) und Präsentation sind ebenfalls in diesem Repository zu finden.

## Business Case
Der Online-Reisemarkt ist hart umkämpft und die Akquise von Neukunden ist kostspielig. Der Schlüssel zu nachhaltigem Wachstum liegt daher in der Bindung bestehender Kunden. Ein personalisiertes Prämienprogramm kann die Kundenloyalität signifikant steigern. Dieses Projekt beantwortet die zentrale Frage: "Welche unterschiedlichen Kundentypen haben wir und wie können wir sie gezielt ansprechen?"

## 📂 Daten
Die Analyse basiert auf internen Produktionsdaten von TravelTide. Für die Segmentierung wurde der Datensatz gezielt gefiltert: Berücksichtigt wurden ausschließlich aktive Nutzer mit mehr als 7 Sitzungen, deren Interaktionen nach dem 4. Januar 2023 stattfanden.

## ⚙️ Methodik & Vorgehen

Der Weg zur Erkenntnis folgte einem strukturierten, 5-stufigen Prozess:
    
    Datenbasis & Filterung: Erstellung eines sauberen, relevanten Datensatzes als Fundament der Analyse.
    
    EDA & Feature Engineering: Aufdecken von Mustern und Entwicklung neuer, aussagekräftiger Merkmale.
    
    Transformation & Optimierung: Übersetzung der Daten für das Modell (Hashing, Skalierung) und Reduktion der Komplexität (PCA).
    
    Clustering: Identifikation von natürlichen Gruppen im Datensatz mittels K-Means-Algorithmus.
    
    Persona-Definition: Analyse der Cluster und Ausformung zu greifbaren Personas.

## 📊 Ergebnisse: Die 4 Kunden-Personas
### Die Analyse hat vier klar voneinander abgrenzbare Kundengruppen identifiziert:

| Persona | Anteil | Kurzbeschreibung |
| :--- | :--- | :--- |
|  **Die Schaufensterbummler** | 39,8% | Größte Gruppe; zeigt hohes Interesse, hat aber noch nie gebucht. Stellt das größte Wachstumspotenzial dar. |
|  **Die effizienten Städtereisenden** | 36,4% | Die solide Basis der aktiven Kunden; buchen gezielt und unkompliziert kurze Trips mit leichtem Gepäck. |
|  **Die aufstrebenden Stammkunden** | 21,5% | Zeigen erste Loyalität, haben bereits mehrfach gebucht und sind entscheidend für zukünftiges Wachstum. |
|  **Die Premium-Familienplaner** | 2,3% | Kleinste, aber wertvollste und profitabelste Gruppe; geben sehr viel Geld für lange Familienurlaube aus. |

<br>

## ✨ Handlungsempfehlungen

Aus den Personas lassen sich direkte, maßgeschneiderte Marketing-Strategien für das neue Prämienprogramm ableiten:

| Persona |Schlüsselfaktor (Verhaltensmerkmale)| Strategisches Ziel | Top-Vorteil (Perk) |
| :--- |:--- | :--- | :--- |
|  **Die Schaufensterbummler** |Zeigt Interesse, aber bucht nie (Reisen = 0) | Aktivierung & Erstbuchung | Exklusive Rabatte |
|  **Die Städtereisenden** |Bucht kurze, unkomplizierte Trips (Dauer ≈ 2-3 Nächte)| Bindung & Wiederholungskauf | Keine Stornogebühren |
|  **Die Stammkunden** |Ist bereits Mehrfach-Bucher (Reisen > 1) & zeigt Loyalität| Loyalität steigern & entwickeln | 1 Hotelnacht gratis |
|  **Die Premium-Planer** |Hohe Ausgaben (> 5.500€) für lange Familienreisen| VIP-Pflege & Maximierung | Kostenfreies Aufgabegepäck |


## Fazit und Ausblick
Das Projekt "Der Kunden-Kompass" hat das Ziel, eine datengestützte Grundlage für personalisiertes Marketing bei TravelTide zu schaffen, erfolgreich erreicht.

Die zentrale Erkenntnis ist, dass der "typische" Kunde nicht existiert. Stattdessen konnten durch den Einsatz von unüberwachtem maschinellem Lernen vier klar voneinander abgrenzbare Kunden-Personas identifiziert werden, von preissensiblen Einmal-Buchern bis hin zu hochprofitablen VIP-Kunden.

Diese Segmentierung ermöglicht den strategischen Übergang von einem ineffizienten "Gießkannenprinzip" zu einer gezielten, persona-basierten Marketingstrategie. Die abgeleiteten Handlungsempfehlungen bieten eine konkrete Grundlage für die Gestaltung des neuen Prämienprogramms. Der empfohlene nächste Schritt ist die Validierung dieser Strategien mittels A/B-Tests, um den Erfolg in messbaren Kennzahlen wie der Konversionsrate und Kundenbindung zu quantifizieren.
