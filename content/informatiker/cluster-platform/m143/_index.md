---
title: M143 Backup- und Restore-Systeme implementieren
modul: m143
cluster: cluster-platform
date: '2025-07-02T10:06:42Z'
draft: false
kompetenzbaender:
- id: A
  titel: Datensicherheitskonzept
  kompetenzen:
  - nr: 1
    hz: '1'
    grundlagen: Ich kann die Rahmenbedingungen und Vorschriften, die bei einem Datensicherungssystem zu beachten sind, erklären und wesentliche Einflussfaktoren aufzählen
    fortgeschritten: Ich kann technische und personelle Risiken eines Datensicherungssystems einschätzen und dabei passende Einflussfaktoren bei der Erstellung eines Datensicherungskonzepts berücksichtigen
    erweitert: Ich kann vorhandene Datensicherungssysteme analysieren und unter Berücksichtigung von Rahmenbedingungen, Vorschriften und erhobenen Daten (Einflussfaktoren) ein Datensicherungskonzept entwickeln und fachgerecht darstellen
  - nr: 2
    hz: '1'
    grundlagen: Ich kann unterschiedliche Datensicherungsverfahren und -technologien erklären und deren wesentliche Merkmale beschreiben
    fortgeschritten: Ich kann Kriterien berücksichtigen, die einen effizienten Einsatz von Backup- und Restore-Systemen ermöglichen, und das optimale Datensicherungsverfahren für ein Datensicherungskonzept bestimmen
    erweitert: Ich kann anhand von aktuellen technischen Lösungen ein optimales Datensicherungsverfahren auswählen und bei der Entwicklung des Datensicherungskonzepts anspruchsvolle Einflussfaktoren berücksichtigen sowie deren technische Umsetzung bei der Realisierung aufzeigen
- id: B
  titel: Machbarkeit
  kompetenzen:
  - nr: 1
    hz: '2'
    grundlagen: Ich kann Kriterien aufzählen, die bei der Machbarkeitsprüfung eines Datensicherungskonzepts berücksichtigt werden sollten
    fortgeschritten: Ich kann zwischen technischen und betriebswirtschaftlichen Kriterien unterscheiden und begründen, welche Einflüsse diese auf die Machbarkeit eines Datensicherungskonzepts haben
    erweitert: Ich kann aufgrund von technischen und betriebswirtschaftlichen Kriterien ein individualisiertes Datensicherungskonzept erstellen und auf Machbarkeit überprüfen
- id: C
  titel: Bedarfsermittlung
  kompetenzen:
  - nr: 1
    hz: '3'
    grundlagen: Ich kann anhand von Vorgaben den Speicherbedarf ermitteln und die Einsatzmerkmale von Backupgeräten und Speichermedien erklären
    fortgeschritten: Ich kann anhand von Vorgaben den Speicherbedarf ermitteln und technisch angemessene Lösungen (Geräte, Speichermedien) erheben
    erweitert: Ich kann den aktuellen und längerfristigen Speicherbedarf ermitteln und individualisierte Lösungen (Geräte, Speichermedien) sowie optimale Datenstandorte (On-Prem, Cloud) ausarbeiten und anbieten
- id: D
  titel: Sicherungsprozeduren
  kompetenzen:
  - nr: 1
    hz: '4'
    grundlagen: Ich kann verschiedene Befehle, welche für die Erstellung von Sicherungs- und Wiederherstellungsprozeduren notwendig sind, erklären
    fortgeschritten: Ich kann ein bestehendes Script, welches für die Sicherungs- und Wiederherstellung von Daten genutzt wird, verstehen und bestimmten Anforderungen anpassen
    erweitert: Ich kann selbständig eine funktionsfähige Sicherungs- und Wiederherstellungsprozedur erstellen, automatisieren, testen und individuellen Anforderungen anpassen
  - nr: 2
    hz: '4'
    grundlagen: Ich kann feststellen, ob eine Sicherungs- und Wiederherstellungsprozedur korrekt funktioniert
    fortgeschritten: Ich kann überprüfen, ob eine bestehende Sicherungs- und Wiederherstellungsprozedur funktioniert und bei Bedarf entsprechende Massnahmen einleiten
    erweitert: Ich kann eine bestehende Sicherungs- und Wiederherstellungsprozedur kontinuierlich weiterentwickeln und Änderungen angemessen und zeitnah implementieren
  - nr: 3
    hz: '4'
    grundlagen: Ich kann wesentliche Aspekte einer Sicherungs- und Wiederherstellungsprozedur erklären und dokumentieren
    fortgeschritten: Ich kann eine verständliche Dokumentation einer Sicherungs- und Wiederherstellungsprozedur erstellen
    erweitert: Ich kann eine vollständige Dokumentation einer Sicherungs- und Wiederherstellungsprozedur erstellen, welche die Konfiguration sowie die Funktionalität dazu nachvollziehbar abbildet
- id: E
  titel: Sicherungs- und Wiederherstellungsprozesse
  kompetenzen:
  - nr: 1
    hz: '5'
    grundlagen: Ich kann Schritte aufzählen, welche bei einer Sicherungs- und Wiederherstellungsprozedur durchgeführt werden
    fortgeschritten: Ich kann anhand eines vorgegebenen Szenarios eine Sicherungs- und Wiederherstellungsprozedur durchführen und überprüfen
    erweitert: Ich kann Sicherungs- und Wiederherstellungsprozeduren erstellen, prüfen, automatisieren und bei Bedarf optimieren oder anpassen
- id: F
  titel: Betriebs- und Wartungsdokumentation
  kompetenzen:
  - nr: 1
    hz: '6'
    grundlagen: Ich kann die Notwendigkeit einer aktuell nachgeführten Betriebs- und Wartungsdokumentation erklären
    fortgeschritten: Ich kann eine Methode anwenden, um die Betriebs- und Wartungsdokumentation aktuell zu halten, und deren Anwendung erklären
    erweitert: Ich kann einen Prozess definieren, der die regelmässige Aktualisierung der Betriebs- und Wartungsdokumentation sicherstellt
---

## Bloom-Taxonomie-Analyse

| Code | Ziel (Anfang) | Bloom-Stufe | Stufenname | Schlüsselverben |
| ---- | ------------- | :-----------: | ---------- | --------------- |
| A1G  | Ich kann die Rahmenbedingungen und Vorschriften erklären… | 2 | Verstehen | erklären, aufzählen |
| A1F  | Ich kann technische und personelle Risiken einschätzen… | 5 | Bewerten | einschätzen, berücksichtigen |
| A1E  | Ich kann vorhandene Datensicherungssysteme analysieren… | 6 | Erschaffen | analysieren, entwickeln |
| A2G  | Ich kann unterschiedliche Datensicherungsverfahren erklären… | 2 | Verstehen | erklären, beschreiben |
| A2F  | Ich kann Kriterien berücksichtigen und das optimale Verfahren bestimmen… | 4 | Analysieren | berücksichtigen, bestimmen |
| A2E  | Ich kann anhand von aktuellen technischen Lösungen auswählen… | 5 | Bewerten | auswählen, berücksichtigen, aufzeigen |
| B1G  | Ich kann Kriterien aufzählen, die bei der Machbarkeitsprüfung… | 1 | Erinnern | aufzählen |
| B1F  | Ich kann zwischen technischen und betriebswirtschaftlichen Kriterien unterscheiden… | 5 | Bewerten | unterscheiden, begründen |
| B1E  | Ich kann aufgrund von technischen und betriebswirtschaftlichen Kriterien… | 5 | Bewerten | erstellen, überprüfen |
| C1G  | Ich kann anhand von Vorgaben den Speicherbedarf ermitteln… | 3 | Anwenden | ermitteln, erklären |
| C1F  | Ich kann anhand von Vorgaben den Speicherbedarf ermitteln und erheben… | 3 | Anwenden | ermitteln, erheben |
| C1E  | Ich kann den aktuellen und längerfristigen Speicherbedarf ermitteln… | 6 | Erschaffen | ermitteln, ausarbeiten, anbieten |
| D1G  | Ich kann verschiedene Befehle erklären… | 2 | Verstehen | erklären |
| D1F  | Ich kann ein bestehendes Script verstehen und anpassen… | 3 | Anwenden | verstehen, anpassen |
| D1E  | Ich kann selbständig eine funktionsfähige Sicherungs- und Wiederherstellungsprozedur… | 6 | Erschaffen | erstellen, automatisieren, testen, anpassen |
| D2G  | Ich kann feststellen, ob eine Sicherungs- und Wiederherstellungsprozedur… | 3 | Anwenden | feststellen |
| D2F  | Ich kann überprüfen, ob eine bestehende Prozedur funktioniert… | 3 | Anwenden | überprüfen, einleiten |
| D2E  | Ich kann eine bestehende Prozedur kontinuierlich weiterentwickeln… | 4 | Analysieren | weiterentwickeln, implementieren |
| D3G  | Ich kann wesentliche Aspekte einer Prozedur erklären und dokumentieren… | 3 | Anwenden | erklären, dokumentieren |
| D3F  | Ich kann eine verständliche Dokumentation erstellen… | 3 | Anwenden | erstellen |
| D3E  | Ich kann eine vollständige Dokumentation erstellen… | 3 | Anwenden | erstellen |
| E1G  | Ich kann Schritte aufzählen, welche bei einer Prozedur durchgeführt werden… | 1 | Erinnern | aufzählen |
| E1F  | Ich kann anhand eines vorgegebenen Szenarios eine Prozedur durchführen… | 3 | Anwenden | durchführen, überprüfen |
| E1E  | Ich kann Sicherungs- und Wiederherstellungsprozeduren erstellen, prüfen… | 5 | Bewerten | erstellen, prüfen, automatisieren, optimieren |
| F1G  | Ich kann die Notwendigkeit einer aktuell nachgeführten Dokumentation erklären… | 2 | Verstehen | erklären |
| F1F  | Ich kann eine Methode anwenden, um die Dokumentation aktuell zu halten… | 3 | Anwenden | anwenden, erklären |
| F1E  | Ich kann einen Prozess definieren, der die regelmässige Aktualisierung sicherstellt… | 3 | Anwenden | definieren |

## Änderungsprotokoll V2

| Änderung | Betroffene Zelle(n) | Beschreibung |
| --- | --- | --- |
| Tabellenheader korrigiert | Header-Zeile | "Kompetenzband:" zu "Kompetenzband" (Doppelpunkt entfernt) |
| Tabellenseparator korrigiert | Separator-Zeile | Grundlagen-Spalte auf linksbündig (`:---`) geändert |
| Buchstabenpräfix ergänzt | Alle Kompetenzbänder | Fehlende Buchstabenpräfixe (A - , B - , C - , D - , E - , F - ) bei allen Kompetenzbändern ergänzt |
| Zell-IDs korrigiert | E2G, E2F, E2E | Falsche IDs E2G/E2F/E2E zu F1G/F1F/F1E korrigiert (Band F, nicht E) |
| Tippfehler korrigiert | B1F | "Kriteren" zu "Kriterien" |
| Tippfehler korrigiert | D2F | "Massnahemen" zu "Massnahmen" |
| Grammatik korrigiert | D2E | "eine bestehenden Sicherung-" zu "eine bestehende Sicherungs-" |
| Grammatik korrigiert | A1E | "erhobene Daten" zu "erhobenen Daten" |
| "Ich kann"-Format sichergestellt | A2F | Zwei Sätze zu einem "Ich kann"-Satz zusammengeführt |
| "Ich kann"-Format sichergestellt | A2E | Zwei Sätze zu einem "Ich kann"-Satz zusammengeführt |
| "Ich kann"-Format sichergestellt | C1G | "kenne die Einsatzmerkmale" umformuliert zu "Ich kann ... erklären" |
| "Ich kann"-Format sichergestellt | F1F (ehem. E2F) | "Ich kenne eine Methode" umformuliert zu "Ich kann eine Methode anwenden" |
| Trailing Periods entfernt | A1G, A1F | Abschliessende Punkte bei Deskriptoren entfernt |
| Trailing Whitespace entfernt | Diverse Zellen | Überflüssige Leerzeichen am Zeilenende entfernt |
| Fehlende Pipe-Zeichen ergänzt | A1E, A2E | Abschliessendes `\|` am Zeilenende ergänzt |
| F1G | "begründen, weshalb..." (Bloom L5) ersetzt durch "die Notwendigkeit ... erklären" (Bloom L2) | Bloom-Regel: G-Zellen dürfen max. Bloom-Stufe 3 erreichen |
| Alle Zellen | Bloom-Taxonomie-Analyse-Tabelle eingefügt | Neue Anforderung: Bloom-Analyse pro Zelle |
| A2G | "begründen" (Bloom L5) ersetzt durch "deren wesentliche Merkmale beschreiben" (Bloom L2) | Bloom-Regel: G-Zellen dürfen max. Bloom-Stufe 3 erreichen |
| C1G | Bloom-Stufe korrigiert: L2 → L3 (Anwenden), da "ermitteln" Bloom-Stufe 3 entspricht | Bloom-Analyse-Korrektur |
| C1E | Bloom-Stufe korrigiert: L5 → L6 (Erschaffen), da "ausarbeiten" Bloom-Stufe 6 entspricht | Bloom-Analyse-Korrektur |
| D3G | Bloom-Stufe korrigiert: L2 → L3 (Anwenden), da "dokumentieren" Bloom-Stufe 3 entspricht | Bloom-Analyse-Korrektur |
