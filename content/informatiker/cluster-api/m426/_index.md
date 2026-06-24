---
title: M426 Software mit agilen Methoden entwickeln
modul: m426
cluster: cluster-api
date: '2025-07-02T10:04:57Z'
draft: false
kompetenzbaender:
- id: A
  titel: Agile Methoden kennen
  kompetenzen:
  - nr: 1
    hz: '1'
    grundlagen: Ich kann die linearen Vorgehensmodelle wie das Wasserfall-Modell, das V-Modell und RUP sowie die zyklischen Modelle wie das Spiralmodell und die unterschiedlichen Prototypenverfahren erläutern
    fortgeschritten: Ich kann das "Agile Manifesto" und dessen Prinzipien erklären und aufzeigen, was daran gut ist und wo Probleme auftauchen können
    erweitert: Ich kann die linearen und die zyklischen Vorgehensmodelle erkennen und aufzeigen, wie das Beste von allem kombiniert werden kann
  - nr: 2
    hz: '1'
    grundlagen: Ich kann das SCRUM-Modell mit dem zyklischen Ablauf, den Rollen, den Zeremonien (Meetings/Sitzungen) und die Philosophie von SCRUM erklären
    fortgeschritten: Ich kann aufzeigen, wie ein Vorhaben in eine "Vision", in "Epics" und in "User-Stories" formuliert werden kann
    erweitert: Ich kann ein Vorhaben mit meinem Team in einen SCRUM-Ablauf einkleiden und die richtigen Schritte planen
  - nr: 3
    hz: '1'
    grundlagen: Ich kann die drei Aspekte erklären, wie man eine Anforderung in einem Satz für eine User-Story formuliert
    fortgeschritten: Ich kann unter Einhaltung der DoR eine User-Story beschreiben, sie gemeinsam mit dem Team einordnen und deren Aufwand mit Story Points bewerten (Planning Poker) sowie Abnahmekriterien dafür bestimmen (DoD)
    erweitert: Ich kann den "guten" Schnitt zwischen User-Story und Aufgaben-Tasks zusammen mit dem Team bestimmen
- id: B
  titel: Agile Iteration realisieren
  kompetenzen:
  - nr: 1
    hz: '2'
    grundlagen: Ich kann bestehende Softwaremodule interpretieren und erklären, wo für die Umsetzung einer User Story die Software ergänzt werden muss
    fortgeschritten: Ich kann die Software für die Umsetzung einer User Story implementieren
    erweitert: Ich kann bestehende Software für die Umsetzung einer User Story anpassen (Refactoring)
  - nr: 2
    hz: '2'
    grundlagen: Ich kann die Bedeutung einer lauffähigen Software im Rahmen der agilen Softwareentwicklung erläutern
    fortgeschritten: Ich kann die von mir umgesetzte User-Story anhand der lauffähigen Software präsentieren und zeigen, dass die DoD eingehalten sind
    erweitert: Ich kann eine Sprint-Demo vorbereiten (inkl. Burndown Chart) und durchführen
- id: C
  titel: Komponenten wiederverwenden
  kompetenzen:
  - nr: 1
    hz: '3'
    grundlagen: Ich kann das Prinzip von Softwarekomponenten (Wiederverwendbarkeit, Aufgabenaufteilung, Schnittstellen) an einem Beispiel erläutern
    fortgeschritten: Ich kann für eine Applikation, unter Berücksichtigung der Wiederverwendbarkeit, Softwarekomponenten evaluieren und auswählen
    erweitert: Ich kann in einem Entwurf Softwarekomponenten identifizieren, deren Wiederverwendbarkeit beurteilen und begründet integrieren
- id: D
  titel: Vorgehen reflektieren und verbessern
  kompetenzen:
  - nr: 1
    hz: '4'
    grundlagen: Ich kann erklären, wie ich mich auf das Daily Scrum vorbereite
    fortgeschritten: Ich kann meine Erfahrungen und Erkenntnisse an der Retrospektive einbringen und geeignete Verbesserungsmassnahmen ableiten
    erweitert: Ich kann eine Retrospektive vorbereiten und anleiten sowie die gewonnenen Erkenntnisse priorisieren und in konkrete Verbesserungsmassnahmen überführen
- id: E
  titel: Versionsverwaltung anwenden
  kompetenzen:
  - nr: 1
    hz: '5'
    grundlagen: Ich kann ein Repository klonen, Änderungen committen und pushen sowie Änderungen vom Server übernehmen (fetch, pull) und das Anwenden von Branches erklären (z. B. Git-Flow)
    fortgeschritten: Ich kann mit Merge Requests umgehen und Branches gezielt anwenden (z. B. Git-Flow)
    erweitert: Ich kann Merge-Konflikte lösen, den Git-Tree kritisch hinterfragen und Verbesserungen umsetzen (z. B. rebase, cherry-pick)
- id: F
  titel: Umgang mit Clean Code und Refactorings
  kompetenzen:
  - nr: 1
    hz: '6'
    grundlagen: Ich kann erklären, was zur guten Lesbarkeit von Code wichtig ist und welche Regeln es zu beachten gibt
    fortgeschritten: Ich kann einen Code durch die Anwendung der "Clean Code"-Empfehlungen besser lesbar machen und ein Refactoring durchführen
    erweitert: Ich kann Funktionsbereiche zur besseren Verständlichkeit so umschreiben, dass die (zyklomatische) Komplexität entflochten wird
---

### Hinweis

Eine Softwarekomponente kann auch mit Hilfe eines Entwurfsmusters umgesetzt sein. Darum wird im Handlungsziel das Entwurfsmuster nicht explizit aufgeführt und dem HZ trotzdem Rechnung getragen.

---

## Bloom-Taxonomie-Analyse

| Code | Ziel (Anfang) | Bloom-Stufe | Stufenname | Schlüsselverben |
| ---- | ------------- | :-----------: | ---------- | --------------- |
| A1G | Ich kann die linearen Vorgehensmodelle… erläutern… | 2 | Verstehen | erläutern |
| A1F | Ich kann das "Agile Manifesto"… erklären und aufzeigen… | 4 | Analysieren | erklären, aufzeigen (Probleme) |
| A1E | Ich kann die linearen und zyklischen Vorgehensmodelle erkennen… | 6 | Erschaffen | erkennen, aufzeigen, kombinieren |
| A2G | Ich kann das SCRUM-Modell… erklären… | 2 | Verstehen | erklären |
| A2F | Ich kann aufzeigen, wie ein Vorhaben in… formuliert werden kann… | 3 | Anwenden | aufzeigen, formulieren |
| A2E | Ich kann ein Vorhaben… in einen SCRUM-Ablauf einkleiden… planen… | 6 | Erschaffen | einkleiden, planen |
| A3G | Ich kann die drei Aspekte erklären, wie man eine Anforderung… | 2 | Verstehen | erklären |
| A3F | Ich kann unter Einhaltung der DoR eine User-Story beschreiben… bewerten… | 5 | Bewerten | bewerten, bestimmen |
| A3E | Ich kann den "guten" Schnitt zwischen User-Story… bestimmen… | 5 | Bewerten | bestimmen |
| B1G | Ich kann bestehende Softwaremodule interpretieren und erklären… | 2 | Verstehen | interpretieren, erklären |
| B1F | Ich kann die Software für die Umsetzung einer User Story implementieren… | 3 | Anwenden | implementieren |
| B1E | Ich kann bestehende Software für die Umsetzung… anpassen (Refactoring)… | 4 | Analysieren | anpassen, refaktorisieren |
| B2G | Ich kann die Bedeutung einer lauffähigen Software… erläutern… | 2 | Verstehen | erläutern |
| B2F | Ich kann die von mir umgesetzte User-Story… präsentieren… | 3 | Anwenden | präsentieren, zeigen |
| B2E | Ich kann eine Sprint-Demo vorbereiten… und durchführen… | 3 | Anwenden | vorbereiten, durchführen |
| C1G | Ich kann das Prinzip von Softwarekomponenten… erläutern… | 2 | Verstehen | erläutern |
| C1F | Ich kann für eine Applikation… Softwarekomponenten evaluieren und auswählen… | 5 | Bewerten | evaluieren, auswählen |
| C1E | Ich kann in einem Entwurf Softwarekomponenten identifizieren… beurteilen… | 5 | Bewerten | identifizieren, beurteilen, integrieren |
| D1G | Ich kann erklären, wie ich mich auf das Daily Scrum vorbereite… | 2 | Verstehen | erklären |
| D1F | Ich kann meine Erfahrungen… einbringen und… ableiten… | 5 | Bewerten | ableiten (begründeten Ansatz) |
| D1E | Ich kann eine Retrospektive vorbereiten und anleiten… priorisieren… | 5 | Bewerten | priorisieren, überführen |
| E1G | Ich kann ein Repository klonen, Änderungen committen… erklären… | 3 | Anwenden | klonen, committen, erklären |
| E1F | Ich kann mit Merge Requests umgehen und Branches… anwenden… | 3 | Anwenden | umgehen, anwenden |
| E1E | Ich kann Merge-Konflikte lösen, den Git-Tree kritisch hinterfragen… | 5 | Bewerten | lösen, hinterfragen |
| F1G | Ich kann erklären, was zur guten Lesbarkeit von Code wichtig ist… | 2 | Verstehen | erklären |
| F1F | Ich kann einen Code durch die Anwendung der "Clean Code"-Empfehlungen… | 4 | Analysieren | anwenden, durchführen (Refactoring) |
| F1E | Ich kann Funktionsbereiche zur besseren Verständlichkeit so umschreiben… | 6 | Erschaffen | umschreiben, entflechten |

## Änderungsprotokoll V2

| Zelle | Änderung | Begründung |
| ----- | -------- | ---------- |
| Header | `Kompetenzband:` → `Kompetenzband` | Vorgabe Tabellenformat |
| Separator | → `| --- | --- | :--- | --- | --- |` | Vorgabe |
| Alle Bänder | Buchstaben-Präfix A–F ergänzt | Vorgabe |
| A1G | "Ich kenne die linearen Vorgehensmodelle..." → "Ich kann die linearen Vorgehensmodelle... erläutern" | "Ich kann"-Format |
| A1F | "Ich kenne das 'Agile Manifesto' und kann..." → "Ich kann das 'Agile Manifesto' und dessen Prinzipien erklären..." | "Ich kann"-Format |
| A1E | "Ich erkenne die linearen..." → "Ich kann die linearen... erkennen und aufzeigen..." | "Ich kann"-Format |
| A2G | "Ich kenne das SCRUM-Modell..." → "Ich kann das SCRUM-Modell... erklären" | "Ich kann"-Format |
| A2F | "Ich weiss, wie wir unser Vorhaben..." → "Ich kann aufzeigen, wie ein Vorhaben..." | "Ich kann"-Format |
| A3G | "Ich kenne die drei Aspekte..." → "Ich kann die drei Aspekte erklären..." | "Ich kann"-Format |
| D1G | "Ich weiss wie ich mich..." → "Ich kann erklären, wie ich mich..." | "Ich kann"-Format |
| F1G | "Ich weiss, was zur guten Lesbarkeit..." → "Ich kann erklären, was zur guten Lesbarkeit..." | "Ich kann"-Format |
| C1G, C1F, C1E | `C2G/C2F/C2E` → `C1G/C1F/C1E` | Erste und einzige Zeile in Band C |
| A2G | "philosophie" → "Philosophie" | Tippfehler |
| A3F | "Planning Pocker" → "Planning Poker" | Tippfehler |
| E1G | "Sever" → "Server" | Tippfehler |
| Hinweis | "expliziet" → "explizit" | Tippfehler |
| E2F | "anwenden anwenden" → "anwenden" | Dopplung entfernt |
| B2G | "Agilen" → "agilen" | Kein Eigenname |
| C1G | "Aufgaben  Aufteilung" → "Aufgabenaufteilung" | Doppeltes Leerzeichen + Schreibweise |
| Diverse Zellen | Trailing Periods entfernt | Keine abschliessenden Punkte |
| E1+E2 → E1 | Basis-Git-Operationen und Branches in eine Zeile zusammengeführt | Beide adressieren HZ 5 (Versionsverwaltung); Branches sind natürliche Erweiterung der Basis-Operationen |
| Alle Zellen | `<br/>` Tags vor "Ich kann" entfernt | Keine HTML-Tags in Markdown-Tabellen |
| C1E | "in einem Entwurf Softwarekomponenten identifizieren und integrieren" → "…identifizieren, deren Wiederverwendbarkeit beurteilen und begründet integrieren" | Bloom-Regel 2: C1F ist Stufe 5 (Bewerten), C1E muss ≥ Stufe 5 sein |
| D1E | "eine Retrospektive vorbereiten und anleiten" → "…anleiten sowie die gewonnenen Erkenntnisse priorisieren und in konkrete Verbesserungsmassnahmen überführen" | Bloom-Regel 2: D1F ist Stufe 5 (Bewerten), D1E muss ≥ Stufe 5 sein |
| Bloom-Tabelle | Neu hinzugefügt | Bloom-Taxonomie-Analyse für alle G/F/E-Zellen ergänzt |
