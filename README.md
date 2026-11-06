# Marketplace Sales Dashboard

Interaktives Verkaufs-Dashboard für Marktplatz-Händler (z. B. Wildberries / Ozon).
Aus einem wöchentlichen Verkaufsbericht (Excel, über 2.000 Einzelbuchungen) wird eine übersichtliche Auswertung erstellt.

> **Hinweis:** Die Daten im Ordner `data/` sind **generierte Übungsdaten**, keine echten Verkäufe.
> Im Dashboard werden alle Beträge in **Euro** angezeigt (Umrechnung zum festen Demo-Kurs 1 € = 100 ₽; die Excel-Rohdaten sind in Rubel).

## Funktionen
- Umsatzentwicklung pro Tag und pro Artikel
- Umsatzanteile (Donut-Diagramm)
- Wasserfall-Diagramm: vom Umsatz bis zur Auszahlung (Logistik, Lagerung, Gebühren, Rückgaben)
- Rücklaufquote, Stückkosten, ABC-Analyse
- Problemartikel und aufklappbare Artikeltabelle
- **Dreisprachig: Deutsch, Russisch, Englisch** (Umschalter oben rechts, Auswahl wird gespeichert)

## Technik
- **D3.js** – Diagramme
- **HTML / CSS / JavaScript** – Oberfläche, Hell-/Dunkelmodus
- Aufbereitung der Excel-Rohdaten zu einem kompakten Datensatz (eingebettet als JSON)
- Wiederholbarer Ablauf mit KI-Unterstützung: neuer Wochenbericht rein → aktualisiertes Dashboard raus

**Live-Demo:** https://sischin-evgheni.github.io/marketplace-sales-dashboard/

## Starten
`index.html` im Browser öffnen.

## Was ich dabei gelernt habe
- Rohdaten bereinigen und zusammenfassen (Verkäufe, Rückgaben, Gebühren)
- Datenvisualisierung mit D3.js
- Automatisierung wiederkehrender Auswertungen mit Unterstützung von KI-Tools (Claude)

---
*Interactive sales dashboard for marketplace sellers – personal learning project with generated demo data.*
