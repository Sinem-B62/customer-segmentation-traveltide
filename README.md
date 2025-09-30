# **Der Kunden-Kompass: Kundensegmentierung für TravelTide**

Dieses Projekt analysiert das Nutzerverhalten des fiktiven Reiseportals TravelTide mittels unüberwachtem maschinellem Lernen. Ziel ist die Entwicklung von datengestützten Kunden-Personas, die als strategische Grundlage für die Konzeption eines personalisierten Prämienprogramms dienen.

## ➡️ Vollständige Projektdokumentation (PDF) und Präsentation sind ebenfalls in diesem Repository zu finden.

### Business Case
Der Online-Reisemarkt ist hart umkämpft und die Akquise von Neukunden ist kostspielig. Der Schlüssel zu nachhaltigem Wachstum liegt daher in der Bindung bestehender Kunden. Ein personalisiertes Prämienprogramm kann die Kundenloyalität signifikant steigern. Dieses Projekt beantwortet die zentrale Frage: "Welche unterschiedlichen Kundentypen haben wir und wie können wir sie gezielt ansprechen?"

### 📂 Daten
Die Analyse basiert auf internen Produktionsdaten von TravelTide. Für die Segmentierung wurde der Datensatz gezielt gefiltert: Berücksichtigt wurden ausschließlich aktive Nutzer mit mehr als 7 Sitzungen, deren Interaktionen nach dem 4. Januar 2023 stattfanden.

### ⚙️ Methodik & Vorgehen

  Der Weg zur Erkenntnis folgte einem strukturierten, 5-stufigen Prozess:
    
  Datenbasis & Filterung: Erstellung eines sauberen, relevanten Datensatzes als Fundament der Analyse.
    
  EDA & Feature Engineering: Aufdecken von Mustern und Entwicklung neuer, aussagekräftiger Merkmale.
    
  Transformation & Optimierung: Übersetzung der Daten für das Modell (Hashing, Skalierung) und Reduktion der Komplexität (PCA).
    
  Clustering: Identifikation von natürlichen Gruppen im Datensatz mittels K-Means-Algorithmus.
    
  Persona-Definition: Analyse der Cluster und Ausformung zu greifbaren Personas.

### 📊 Ergebnisse: Die 4 Kunden-Personas
Die Analyse hat vier klar voneinander abgrenzbare Kundengruppen identifiziert:

### Persona	Anteil	Kurzbeschreibung
  Die Schaufensterbummler	39,8%	Größte Gruppe; zeigt hohes Interesse, hat aber noch nie gebucht.
  Die effizienten Städtereisenden	36,4%	Die solide Basis der aktiven Kunden; buchen gezielt kurze Trips.
  Die aufstrebenden Stammkunden	21,5%	Zeigen erste Loyalität und haben bereits mehrfach gebucht.
  Die Premium-Familienplaner	2,3%	Kleinste, aber wertvollste Gruppe; geben sehr viel Geld für lange Reisen aus.


### ✍️ Handlungsempfehlungen
  Aus den Personas lassen sich direkte, maßgeschneiderte Marketing-Strategien ableiten:

### Persona	Strategisches Ziel	Top-Vorteil (Perk)
  Schaufensterbummler	Aktivierung & Erstbuchung	Exklusive Rabatte
  Städtereisende	Bindung & Wiederholungskauf	Keine Stornogebühren
  Stammkunden	Loyalität steigern	1 Hotelnacht gratis
  Premium-Planer	VIP-Pflege & Maximierung	Kostenfreies Aufgabegepäck

