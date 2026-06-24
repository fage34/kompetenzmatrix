---
title: M114 Codierungs- Kompressions- und Verschlüsselungsverfahren einsetzen
modul: m114
cluster: cluster-data
date: '2025-07-02T10:05:51Z'
draft: false
kompetenzbaender:
- id: A
  titel: Daten codieren
  kompetenzen:
  - nr: 1
    hz: '1'
    grundlagen: Ich kann die binäre Interpretation einer Codierung erklären (z. B. Zahlen, Text)
    fortgeschritten: Ich kann eine Codierung unter Berücksichtigung verschiedener, aufgabenbezogener Faktoren auswählen (z. B. Zeichenvorrat, Wertebereich, Berechenbarkeit)
    erweitert: Ich kann den Aufwand und die Risiken einer Codierungstransformation beurteilen und eine begründete Empfehlung für den geeigneten Ansatz abgeben (z. B. Text <--> Zahl)
  - nr: 2
    hz: '1'
    grundlagen: Ich kann Unterschiede von Bildformaten (Raster- und Vektorgrafik sowie z. B. JPG, GIF, PNG, SVG) und Farbcodierungen (z. B. RGB, CMYK, YCrCb) erläutern
    fortgeschritten: Ich kann unterschiedliche Bildformate passend für den Einsatz des Bildes anwenden und parametrisieren (z. B. für Logo, Galerien, Thumbnails in Bezug auf Speicherplatz, Transparenz, Skalierbarkeit, Komprimierung)
    erweitert: Ich kann das Format eines Bildes in Bezug auf seine spezifische Anwendung wandeln
  - nr: 3
    hz: '1'
    grundlagen: Ich kann eine zusammengesetzte Codierung erklären (z. B. alte AHV Nummer, IBAN, EAN)
    fortgeschritten: Ich kann eine zusammengesetzte Codierung umsetzen (z. B. Sitzplatz in Stadion)
    erweitert: Ich kann eine zusammengesetzte Codierung kritisch hinterfragen (z. B. Eindeutigkeit, Auswertbarkeit) und Verbesserungen vorschlagen
- id: B
  titel: Daten komprimieren
  kompetenzen:
  - nr: 1
    hz: '2'
    grundlagen: Ich kann den Unterschied (Vorteile/Nachteile) zwischen verlustloser und verlustbehafteter Komprimierung erklären und die typischen Einsatzgebiete erläutern
    fortgeschritten: Ich kann ein gängiges, verlustloses Kompressionsverfahren wie z. B. VLC/Huffman, RLC, BWT, LZW und ein gängiges, verlustbehaftetes Kompressionsverfahren wie z. B. DCT bei JPG anwenden
    erweitert: Ich kann abhängig vom zu komprimierenden Medium ein geeignetes Verfahren begründet auswählen
- id: C
  titel: Daten verschlüsseln
  kompetenzen:
  - nr: 1
    hz: '3'
    grundlagen: Ich kann den Zweck und das Prinzip der Verschlüsselung (chiffrieren und dechiffrieren) erklären
    fortgeschritten: Ich kann Daten mit Hilfe einer Software verschlüsseln (chiffrieren und dechiffrieren)
    erweitert: Ich kann verschiedene Verschlüsselungsverfahren analysieren und vergleichen (Vor- und Nachteile)
- id: D
  titel: Gesicherte Übertragungen
  kompetenzen:
  - nr: 1
    hz: '4'
    grundlagen: Ich kann den Zweck und das Prinzip der gesicherten Datenübertragung erklären (z. B. Public/Private Key, Zertifikate, Protokolle und Standards)
    fortgeschritten: Ich kann Daten gesichert übertragen (Senden und Empfangen, z. B. E-Mail)
    erweitert: Ich kann Verfahren für eine gesicherte Datenübertragung vergleichen und begründet auswählen
- id: E
  titel: Verschlüsselungstechnologien bewerten
  kompetenzen:
  - nr: 1
    hz: '5'
    grundlagen: Ich kann verschiedene Verschlüsselungstechnologien unterscheiden
    fortgeschritten: Ich kann Unterschiede der verschiedenen Verschlüsselungstechnologien aufzeigen
    erweitert: Ich kann Schwachstellen von Verschlüsselungstechnologien erkennen und Alternativen vorschlagen
---

---

## Bloom-Taxonomie-Analyse

| Code | Ziel (Anfang) | Bloom-Stufe | Stufenname | Schlüsselverben |
| ---- | ------------- | :-----------: | ---------- | --------------- |
| A1G  | Ich kann die binäre Interpretation… | 2 | Verstehen | erklären |
| A1F  | Ich kann eine Codierung unter Berücksichtigung… | 5 | Bewerten | auswählen (begründet) |
| A1E  | Ich kann den Aufwand und die Risiken… | 5 | Bewerten | beurteilen, empfehlen |
| A2G  | Ich kann Unterschiede von Bildformaten… | 2 | Verstehen | erläutern |
| A2F  | Ich kann unterschiedliche Bildformate passend… | 3 | Anwenden | anwenden, parametrisieren |
| A2E  | Ich kann das Format eines Bildes… | 3 | Anwenden | wandeln |
| A3G  | Ich kann eine zusammengesetzte Codierung… | 2 | Verstehen | erklären |
| A3F  | Ich kann eine zusammengesetzte Codierung umsetzen… | 3 | Anwenden | umsetzen |
| A3E  | Ich kann eine zusammengesetzte Codierung kritisch… | 5 | Bewerten | hinterfragen, vorschlagen |
| B1G  | Ich kann den Unterschied zwischen verlustloser… | 2 | Verstehen | erklären, erläutern |
| B1F  | Ich kann ein gängiges, verlustloses Kompressionsverfahren… | 3 | Anwenden | anwenden |
| B1E  | Ich kann abhängig vom zu komprimierenden… | 5 | Bewerten | begründet auswählen |
| C1G  | Ich kann den Zweck und das Prinzip… | 2 | Verstehen | erklären |
| C1F  | Ich kann Daten mit Hilfe einer Software… | 3 | Anwenden | verschlüsseln |
| C1E  | Ich kann verschiedene Verschlüsselungsverfahren… | 4 | Analysieren | analysieren, vergleichen |
| D1G  | Ich kann den Zweck und das Prinzip… | 2 | Verstehen | erklären |
| D1F  | Ich kann Daten gesichert übertragen… | 3 | Anwenden | übertragen |
| D1E  | Ich kann Verfahren für eine gesicherte… | 5 | Bewerten | vergleichen, begründet auswählen |
| E1G  | Ich kann verschiedene Verschlüsselungstechnologien… | 2 | Verstehen | unterscheiden |
| E1F  | Ich kann Unterschiede der verschiedenen… | 2 | Verstehen | aufzeigen |
| E1E  | Ich kann Schwachstellen von Verschlüsselungstechnologien… | 5 | Bewerten | erkennen, vorschlagen |

---

## Änderungsprotokoll V2

| Zelle | Änderung | Begründung |
| ----- | -------- | ---------- |
| Header | `Kompetenzband:` zu `Kompetenzband` (Doppelpunkt entfernt) | Einhaltung des vorgegebenen Tabellenformats |
| Tabellentrenner | Separator auf `| --- | --- | :--- | --- | --- |` standardisiert | Konsistenz mit Tabellenformat-Vorgabe |
| Alle Kompetenzbänder | Buchstaben-Präfix ergänzt (A - Daten codieren, B - Daten komprimieren, C - Daten verschlüsseln, D - Gesicherte Übertragungen, E - Verschlüsselungstechnologien bewerten) | Konsistenz mit Tabellenformat-Vorgabe |
| A2G (Zell-ID) | Falsche ID `A1G` in zweiter Zeile von Band A zu `A2G` korrigiert | Tippfehler / falsche Nummerierung |
| B1G | "Ich kenne" → "Ich kann den Unterschied ... erklären und die typischen Einsatzgebiete erläutern" | "Ich kann"-Format |
| A2G, A2E, A3G, A3F, B1G, B1F, C1G, C1F, D1G, D1F, D1E, E1G, E1F | Punkte am Satzende entfernt | Einheitliche Formatierung ohne Trailing Periods |
| A1F, A3G, A3F, C1E, D1G | Konstruktionen wie `erklären. (z. B. ...)` zu `erklären (z. B. ...)` bereinigt | Klammern nach Punkt korrigiert |
| B1G, B1F, C1F, E1G | Mehrfach-Leerzeichen entfernt | Formatbereinigung |
| C1E, E1G, E1E, Kompetenzband E | "Verschlüsselungs-verfahren" zu "Verschlüsselungsverfahren", "Verschlüsselungs-technologien" zu "Verschlüsselungstechnologien" | Trennstriche entfernt |
| Kompetenzband D | "gesicherte Übertragungen" zu "Gesicherte Übertragungen" korrigiert | Grossschreibung im Bandtitel |
| D1F | `<br />` entfernt und Klammer-Inhalt in den Satz integriert | HTML-Tag entfernt |
| C1F | Überflüssiges Leerzeichen vor dem schliessenden Punkt entfernt, dann Punkt entfernt | Formatbereinigung |
| B1E | "- abhängig ... -" Gedankenstriche entfernt | Flüssigere Formulierung |
| D1F | "Email" zu "E-Mail" korrigiert | Korrekte Schreibweise im Schweizer Hochdeutsch |
| A1E | Rewrite: "Ich kann eine Codierung in andere transformieren (z. B. Text <--> Zahl)" → "Ich kann den Aufwand und die Risiken einer Codierungstransformation beurteilen und eine begründete Empfehlung für den geeigneten Ansatz abgeben (z. B. Text <--> Zahl)" | Bloom Regel 2: A1F ist Stufe 5 (Bewerten), A1E war Stufe 3 (Anwenden) — nicht-monotone Abnahme. A1E auf Stufe 5 angehoben. |
| Bloom-Tabelle | Bloom-Taxonomie-Analyse-Tabelle eingefügt | Neue Anforderung |
