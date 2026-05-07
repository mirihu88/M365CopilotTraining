# 📊 Microsoft 365 Copilot – Excel Prompt-Sammlung
## Trainings-Leitfaden für M365Copilot_Excel.xlsx

---

## 🎯 Wie du diese Prompts verwendest

1. **Datei öffnen**: M365Copilot_Excel.xlsx in Excel laden
2. **Copilot aktivieren**: Auf der Excel-Multifunktionsleiste auf "Copilot" klicken
3. **Prompt kopieren**: Den gewünschten Prompt aus dieser Datei kopieren
4. **Einfügen & ausführen**: Prompt in das Copilot-Eingabefeld einfügen und Enter drücken

💡 **Tipp**: Du kannst die Prompts auch anpassen und mit eigenen Daten kombinieren!

---

## 📝 TEIL 1: Sortieren, Filtern & Hervorheben

### 1.1 Beispieldatensatz generieren (optional)
**Was macht dieser Prompt**: Erstellt eine Verkaufstabelle mit 200 Beispiel-Einträgen für Q1 2026.

```
Erstelle eine neue Tabelle namens "Q1 Sales Data". Verwende genau diese Spalten in folgender Reihenfolge: Datum, Marke, Modell, Kategorie, Verkaufte Einheiten, Stückpreis, Bruttogewinn, Verkäufer, Standort. Generiere 200 Reihen synthetischer Verkaufstransaktionen für das erste Quartal 2026. Nutze diese Standorte: Berlin, Hamburg, München, Wien, Zürich. Verwende diese Marken und halte die Modelle konsistent: - Contoso EV: Zephyr S, Zephyr Pro, Apex GT, Apex Sport, Bolt Mini - Meridian: Crown Sedan, Crown SUV, Prestige Coupé, Luxe Kombi - Volta: Scout SUV, Scout Compact, Blaze Sedan, Edge Pickup. Verwende diese Kategorien: EV, Limousine, SUV, Pickup, Kombi, Coupé (passen sie logisch an das Modell an). Regeln: Verkaufte Einheiten sollten in der Regel 1–4 sein, aber 3 klare "Spike"-Reihen mit verkauften Einheiten zwischen 8 und 12. Der Einheitspreis sollte pro Modell realistisch aussehen (grobe Bereiche) und innerhalb eines Modells konsistent sein. Der Bruttogewinn sollte plausibel sein und mit den verkauften Einheiten und dem Einheitspreis korrelieren (keine negativen Werte). Verwende 6–8 verschiedene Verkäufernamen.
```

### 1.2 Daten nach Monat und Ort filtern
**Was macht dieser Prompt**: Zeigt nur Verkäufe aus März 2026 in Berlin, sortiert nach Menge.

```
Filtere auf die Reihen im März 2026 für Berlin. Sortiere die Ergebnisse nach verkauften Einheiten vom höchsten bis zum niedrigsten.
```

### 1.3 Alle Filter & Hervorhebungen löschen
**Was macht dieser Prompt**: Setzt die Tabelle auf den Ausgangszustand zurück.

```
Lösche alle Filter und Hervorhebungen.
```

### 1.4 Premium-Deals filtern & hervorheben
**Was macht dieser Prompt**: Zeigt nur teure oder vielverkaufte Modelle und hebt sie farblich hervor.

```
Filtere die Tabelle auf Premium-Deals, indem du nur Coupés oder Verkäufe mit einem Stückpreis von mindestens 70.000 zeigst. Sortiere nach Stückpreis absteigend. Hebe alle Zeilen mit einem Stückpreis über 80.000 hervor und zusätzlich alle Zeilen, bei denen fünf oder mehr Einheiten verkauft wurden.
```

### 1.5 Hervorhebungsfarbe ändern
**Was macht dieser Prompt**: Passt die Highlighting-Farbe an.

```
Ändere die Hervorhebungsfarbe zu Gelb.
```

### 1.6 Zahlen anpassen
**Was macht dieser Prompt**: Modifiziert Zahlenwerte basierend auf Bedingungen.

```
Let's adjust some of the numbers. Unit Price lower than 80 k Units Sold more than 4
```

### 1.7 Tägliches Stand-up: Schnelle Erkenntnisse
**Was macht dieser Prompt**: Extrahiert die wichtigsten Erkenntnisse für dein Morning Meeting.

```
Erstelle drei Erkenntnisse aus diesen Daten für mein tägliches Stand-up.
```

---

## 🔍 TEIL 2: Fragen an die Daten stellen (Q&A)

### 2.1 Umsatz nach Marke
**Was macht dieser Prompt**: Zeigt, welche Marke am meisten verdient hat.

```
Welche Marke hatte im 1. Quartal 2026 den höchsten Gesamtumsatz?
```

### 2.2 Top 5 meistverkaufte Modelle
**Was macht dieser Prompt**: Ranking der erfolgreichsten Modelle nach Verkaufsmengen.

```
Zeig mir die Top 5 der meistverkauften Modelle nach verkauften Einheiten.
```

### 2.3 Bester Verkäufer (nach Gewinn)
**Was macht dieser Prompt**: Wer hat im letzten Monat am meisten verdient?

```
Welcher Verkäufer hat letzten Monat den höchsten Bruttogewinn erzielt?
```

---

## ⚠️ TEIL 3: Ausreißer & automatische Highlights

### 3.1 Anomalien finden & markieren
**Was macht dieser Prompt**: Identifiziert ungewöhnliche Daten und hebt sie hervor.

```
Gibt es Ausreißer oder Anomalien in den Verkaufszahlen, die ich kennen sollte? Markiere sie in der Tabelle.
```

### 3.2 Umsatz vs. Durchschnitt hervorheben
**Was macht dieser Prompt**: Zeigt farblich, welche Verkäufe über/unter dem Schnitt liegen.

```
Hebe Zeilen hervor, bei denen der Umsatz (verkaufte Einheiten x Stückpreis) mindestens 25 Prozent über oder unter dem Durchschnitt liegt. Über dem Durchschnitt grün markieren, unter dem Durchschnitt rot markieren.
```

---

## 🧮 TEIL 4: Berechnungen & Formeln

### 4.1 Gesamtumsatz Januar berechnen
**Was macht dieser Prompt**: Summiert alle Verkäufe für einen bestimmten Monat.

```
Berechne die Gesamtverkäufe für Januar.
```

### 4.2 Wachstumschart (Jan–März)
**Was macht dieser Prompt**: Visualisiert Verkaufstrends als Balkendiagramm.

```
Erstelle ein Balkendiagramm, das das Verkaufswachstum zwischen Januar und März zeigt.
```

### 4.3 Umsatzformel hinzufügen
**Was macht dieser Prompt**: Erstellt eine neue Berechnungsspalte.

```
Füge eine Formel hinzu, die den Umsatz basierend auf „verkauften Einheiten" und „Stückpreis" berechnet
```

### 4.4 Kreisdiagramm: EV-Verkäufe
**Was macht dieser Prompt**: Zeigt den Anteil der EV-Kategorie als Kreisdiagramm.

```
Summiere die Verkäufe für alle Modelle in der Kategorie „EV" und stelle die Ergebnisse in einem Kreisdiagramm dar.
```

---

## 📋 TEIL 5: PivotTables erstellen

### 5.1 PivotTable: Umsatz nach Marke & Monat
**Was macht dieser Prompt**: Erstellt eine kompakte Übersicht in einem neuen Blatt.

```
Erstelle eine PivotTable in einem neuen Arbeitsblatt, die den Umsatz und die verkauften Einheiten nach Marke und Monat zeigt.
```

---

## 📈 TEIL 6: Dashboards erstellen

### 6.1 Sales Dashboard (vollständig)
**Was macht dieser Prompt**: Erstellt ein professionelles Dashboard mit KPIs und Diagrammen.

```
Lege ein neues Arbeitsblatt namens „Dashboard" an.
Platziere oben drei KPI Karten: insgesamt verkaufte Einheiten, insgesamter Bruttogewinn, durchschnittlicher Stückpreis.
Erstelle darunter ein Liniendiagramm nach Monat (Jan–Mär 2026) mit zwei Reihen: Verkaufte Einheiten und Bruttogewinn.
Erstelle rechts daneben ein Balkendiagramm: Bruttogewinn nach Standort.
Erstelle darunter ein Balkendiagramm: Verkaufte Einheiten nach Kategorie.
```

### 6.2 Dashboard-Design: Farben anpassen
**Was macht dieser Prompt**: Passt die visuelle Optik des Dashboards an.

```
Verwende ein Frühlingsfarbschema für das gesamte Dashboard.
```

---

## 📂 TEIL 7: Mehrere Dateien kombinieren (Actuals vs. Targets)

### 7.1 Zielwerte-Tabelle erstellen
**Was macht dieser Prompt**: Erstellt ein Vergleich-Blatt mit Verkaufszielen.

```
Erstelle eine neue Arbeitsmappe oder ein neues Arbeitsblatt namens „Targets". Lege dort eine Tabelle mit dem Namen „SalesTargets" an mit folgenden Spalten: Monat, Verkäufer, Target verkaufte Einheiten. Erstelle realistische, nicht identische Zielwerte für Jan, Feb und Mar 2026 für die Verkäufer aus dem aktuellen Arbeitsblatt.
```

### 7.2 Actuals vs. Targets vergleichen
**Was macht dieser Prompt**: Zeigt, wer seine Ziele erreicht hat (mit Farbmarkierung).

```
Kombiniere die Sales Transaktionen mit der aus dem Arbeitsblatt „Targets". Schritt 1: Aggregiere die Transaktionen nach Monat und Verkäufer: Actual Verkaufte Einheiten = Summe von verkauften Einheiten. Schritt 2: Verknüpfe die aggregierten Ergebnisse mit „SalesTargets" über Monat + Verkäufer. Schritt 3: Erstelle ein neues Arbeitsblatt namens „Actuals vs Targets" mit folgenden Spalten: Monat, Verkäufer, Actual Verkaufte Einheiten, Zielerreichung in %. Berechne „Zielerreichung in % als Actual verkaufte Einheiten geteilt durch Target verkaufte Einheiten. Markiere Zielerreichung unter 90% rot und über 110% grün.
```

---

## 📄 TEIL 8: Tabelle zusammenfassen

### 8.1 Zusammenfassung der Datei
**Was macht dieser Prompt**: Gibt einen schnellen Überblick über den Inhalt der Excel-Datei.

```
Gib mir eine verständliche Zusammenfassung, was diese Excel Datei enthält.
```

---

## 🔧 TEIL 9: Daten bereinigen & transformieren

### 9.1 CSV-Rohdaten in Excel-Tabelle umwandeln
**Was macht dieser Prompt**: Wandelt ungeordnete kommagetrennte Daten in eine saubere Tabelle um.

Füge zuerst diese Beispieldaten in eine Spalte ein:

```
Sale Date,Brand,Model,Full Name,Units Sold,Unit Price,Revenue
05/01/2026,contoso motors ev,Zephyr S,Sophie Brandt,1,42000,42000
05-01-2026,MERIDIAN,Crown Sedan,Mark Turner,1,58000,58000
2026-01-06,Volta AG,Scout Suv,Lena Müller,2,32000,64000
06/01/2026,Contoso EV,Zhephyr Pro,Carlos Rivera,,55000,
2026-01-07,meridian,Crown SUV,Anna Koch,1,72000,72000
07-01-2026,VOLTA,Blaze sedan,James Whitfield,3,24000,72000
2026-01-08,Contoso ev,Apex GT,Yuki Tanaka,1,62000,62000
08/01/2026,Meridian,Prestige coupe,Priya Sharma,1,88000,88000
,,,,,,
09/01/2026,CONTOSO EV,Zephyr  S,Sophie Brandt,2,42000,84000
2026-01-09,Meridian,crown SUV,Mark Turner,,72000,
2026-01-12,volta,Scout Compact,Lena Müller,2,26000,52000
12/01/2026,Contoso EV,Bolt Mini,Carlos Rivera,3,35000,105000
2026-01-13,MERIDIAN,Luxe wagon,Anna Koch,1,64000,64000
13-01-2026,Volta AG,Edge Pickup,James Whitfield,1,38000,38000
2026-01-14,Contoso motors EV,Apex Sport,Yuki Tanaka,1,68000,68000
14/01/2026,meridian,Crown Sedan,Priya Sharma,2,58000,116000
,,,,,,
2026-01-15,VOLTA,scout suv,Sophie Brandt,1,32000,32000
15/01/2026,Contoso EV,zephyr S,Mark Turner,,42000,
2026-01-16,Meridian,crown suv,Lena Müller,1,72000,72000
16-01-2026,volta ag,Blaze Sedan,Carlos Rivera,2,24000,48000
2026-01-19,CONTOSO EV,Apex GT,Anna Koch,2,62000,124000
19/01/2026,Meridian,PRESTIGE COUPE,James Whitfield,1,88000,88000
2026-01-20,Volta,Scout compact,Yuki Tanaka,3,26000,78000
20/01/2026,contoso ev,Zephyr Pro,Priya Sharma,1,55000,55000
,,,,,,
2026-01-21,MERIDIAN,luxe wagon,Sophie Brandt,2,64000,128000
21-01-2026,Volta AG,Edge pickup,Mark Turner,2,38000,76000
2026-01-22,Contoso EV,Apex sport,Lena Müller,1,68000,68000
22/01/2026,meridian,Crown sedan,Carlos Rivera,1,58000,58000
2026-01-23,volta,Scout Suv,Anna Koch,2,32000,64000
23/01/2026,CONTOSO EV,bolt mini,James Whitfield,3,35000,105000
```

Dann diesen Prompt verwenden:

```
Ich habe Daten als kommagetrennte Werte in eine einzelne Spalte eingefügt. Wandle diesen Rohtext in eine saubere Excel Tabelle um.
```

### 9.2 Namen aufteilen (Vorname / Nachname)
**Was macht dieser Prompt**: Teilt z.B. "Sophie Brandt" in zwei separate Spalten.

```
Teile die Spalte „Vollständiger Name" in „Vorname" und „Nachname" auf und entferne anschließend die Spalte „Vervollständiger Name".
```

### 9.3 Marken-Namen standardisieren
**Was macht dieser Prompt**: Vereinheitlicht unterschiedliche Schreibweisen der Markennamen.

```
Standardisiere die Spalte „Marke": Einträge wie „contoso motors" und „Contoso" sollen alle zu „Contoso EV" vereinheitlicht werden.
```

### 9.4 Leere Zeilen entfernen
**Was macht dieser Prompt**: Löscht Zeilen ohne Verkaufsdaten.

```
Entferne alle Zeilen, in denen die Spalte „Verkaufte Einheiten" leer ist.
```

### 9.5 Datumsformat konvertieren
**Was macht dieser Prompt**: Standardisiert alle Datumsangaben auf ein einheitliches Format.

```
Konvertiere das Datumsformat in Spalte A von DD/MM/YYYY zu YYYY-MM-DD.
```

### 9.6 Deutsche Sonderzeichen bereinigen
**Was macht dieser Prompt**: Repariert beschädigte Umlaute und Sonderzeichen.

```
Bereinige und normalisiere den markierten Text hinsichtlich deutscher Sonderzeichen und Encoding Problemen (z. B. ü, ä, ö, ß sowie falsch dargestellte Zeichen).
```

---

## 🔮 TEIL 10: Prognosen & What-If-Szenarien

### 10.1 Q2-Prognose mit Szenarien
**Was macht dieser Prompt**: Erstellt mehrere Wachstumsszenarien für das nächste Quartal.

```
Füge eine Prognosespalte für Q2 hinzu und gehe davon aus, dass der Umsatz jeder Marke im Vergleich zu Q1 um 10 % wächst. Berechne außerdem, wie sich der gesamte Bruttogewinn verändern würde, wenn die verkauften EV Einheiten um 20 % steigen und gleichzeitig der Durchschnittspreis um 5 % sinkt. Erstelle auf Basis der Q1 Daten eine Best Case , Base Case  und Worst Case Umsatzprognose für Q2.
```

---

## 📚 Zusätzliche Tipps für Teilnehmer

### ✅ Best Practices beim Prompt-Schreiben
1. **Klar & konkret**: Je präziser die Anweisung, desto besser das Ergebnis
2. **Schritt-für-Schritt**: Komplexe Aufgaben in Schritte unterteilen
3. **Beispiele geben**: "Beispiel: ..." hilft Copilot, die Intention zu verstehen
4. **Kontext liefern**: Welche Spalten? Welche Zeiträume?
5. **Ergebnis beschreiben**: Was soll am Ende herauskommen?

### 💡 Häufige Fehler vermeiden
- ❌ Zu vage: "Sortiere die Daten" → ✅ "Sortiere nach Stückpreis absteigend"
- ❌ Mehrdeutig: "Hebe das Wichtigste hervor" → ✅ "Hebe Werte > 80.000 gelb hervor"
- ❌ Zu komplex auf einmal → ✅ Teile in mehrere Prompts auf

