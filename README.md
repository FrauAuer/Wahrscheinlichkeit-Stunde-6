# 🎡 Wie oft landest du auf welcher Farbe?

Dieses Projekt ermöglicht es Schülerinnen und Schülern, Ergebnisse von Glücksrädern digital zu erfassen und gemeinsam auszuwerten. Die Daten werden in einer Firebase-Datenbank gespeichert und im Dashboard visualisiert.

---

## 📁 Projektstruktur

- index.html → Eingabeseite für die Schülerinnen und Schüler fileciteturn3file0  
- dashboard.html → Anzeige der Ergebnisse (Diagramme + Tabelle) fileciteturn3file2  
- firebase-config.js → Verbindung zur Firebase-Datenbank fileciteturn3file1  

---

## 🚀 Funktionen

### Eingabeseite (index.html)
- Eingabe der Gruppennummer
- Eingabe der Ergebnisse für zwei Glücksräder:
  - blau / gelb
- Automatische Eingabelogik:
  - „0“ verschwindet beim Klicken
  - leere Felder werden wieder zu „0“
- Speicherung per Klick auf „senden“

---

### Dashboard (dashboard.html)
- Darstellung der Ergebnisse als **zwei Säulendiagramme**:
  - Glücksrad 1
  - Glücksrad 2
- Übersichtliche Tabelle aller Gruppen
- Automatische Sortierung nach Gruppennummer
- Anzeige der Anzahl der Gruppen

---

## 🔧 Einrichtung

1. Firebase-Projekt erstellen  
2. Firebase-Konfiguration in `firebase-config.js` eintragen  
3. Dateien hochladen (z. B. Firebase Hosting)  

---

## 🔑 Nutzung

### Für Schülerinnen und Schüler:
1. Eingabeseite öffnen (`index.html`)
2. Passwort eingeben (z. B. „66“)
3. Gruppennummer eintragen
4. Ergebnisse der Glücksräder eintragen
5. Auf „senden“ klicken

---

### Für die Lehrkraft:
1. Dashboard öffnen (`dashboard.html`)
2. Passwort eingeben
3. Auf „anzeigen“ klicken
4. Ergebnisse gemeinsam auswerten

---

## 📊 Didaktischer Einsatz

- Vergleich von Wahrscheinlichkeiten bei Glücksrädern
- Förderung des Verständnisses für:
  - relative Häufigkeiten
  - faire vs. unfaire Spiele
- Visualisierung von Ergebnissen im Klassenverband
- Grundlage für mathematische Gespräche

---

## 💡 Hinweise

- Nur numerische Gruppennummern erlaubt
- Mindestens ein Wert muss größer als 0 sein
- Speicherung erfolgt unter:
  ```
  Stunde6/{Passwort}/groups/{Gruppennummer}
  ```

---

## 👩‍🏫 Autorin

Leonie Auer  
Lehramtsanwärterin (Primarstufe)  
Fach: Mathematik  

---
