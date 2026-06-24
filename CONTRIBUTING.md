# Mitwirken an den Kompetenzmatrizen

Dieses Repo ist das **Arbeitsrepo** für die Kompetenzmatrizen der ICT-Module (BiVo2021).
Änderungen laufen über **Pull Requests** und werden nach dem Merge automatisch auf
[kompetenzmatrix.ch](https://kompetenzmatrix.ch) publiziert.

## Wie bearbeiten?

### Variante A — Web-Editor (empfohlen für Lehrpersonen)
Du brauchst **nur einen GitHub-Account** — keine Freischaltung, keine Schreibrechte.
1. `https://kompetenzmatrix.ch/admin/` öffnen, mit GitHub anmelden.
2. Cluster → Modul wählen, Felder ausfüllen (Formular, keine Tabellen-Syntax nötig).
3. Speichern → der Editor legt automatisch einen **Fork** an und öffnet einen **Pull Request**
   (Open Authoring). Eine berechtigte Person reviewt und merged → wird automatisch publiziert.

### Variante B — direkt im Repo (für Git-erfahrene)
Modul forken / Branch erstellen, `content/<cluster>/<modul>/_index.md` bearbeiten, PR öffnen.
Tipp: Taste `.` im GitHub-Repo öffnet einen Browser-Editor (github.dev).

## Aufbau eines Moduls

Jedes Modul ist ein Ordner `content/<cluster>/<modul>/` mit:
- `_index.md` — die **Kompetenzmatrix als YAML** (+ Bloom-Analyse / Änderungsprotokoll im Textteil)
- `umsetzungsvorschlag.md` — Umsetzungsvorschlag (Lektionsplanung)
- `handlungssituationen.md` — Handlungssituationen

Die Matrix-Tabelle wird aus dem YAML automatisch gerendert; Zell-IDs (z.B. `A1G`) werden berechnet.

## Inhaltsregeln (EHB)

Diese Regeln werden bei jedem PR automatisch geprüft (`scripts/validate_modules.py`):

- **Sprache**: Schweizer Hochdeutsch, sachlich, geschlechtsneutral.
- **"Ich kann …"**: Jeder Kompetenz-Deskriptor (Grundlagen / Fortgeschritten / Erweitert) **muss** mit `Ich kann` beginnen.
- **In sich geschlossen**: Jede Gütestufe ist eigenständig lesbar, baut nicht auf der vorherigen auf.
- **Aktiv & beobachtbar**: konkrete, beobachtbare Formulierungen — keine vagen Wertungen.
- **Gütestufen**: Grundlagen / Fortgeschritten / Erweitert.
- **Struktur pro Band**: `id` (A, B, C …, Grossbuchstabe), `titel`, `kompetenzen[]` mit `nr`, `hz`, und den drei Stufen.
- **Produktneutralität**: keine Produktnamen ausser wenn fachlich nötig.
- **Keine neuen Kompetenzbänder erfinden** — bestehende ergänzen/korrigieren.

ÜK-Module ohne Matrix: `uek: true` im Frontmatter setzen (dann keine Matrix-Pflicht).

## Lokal bauen

```bash
git clone --recurse-submodules <repo>
hugo server          # http://localhost:1313
python scripts/validate_modules.py
```

## Publishing

Merge auf `main` → GitHub Action baut Hugo und deployt per `rsync` nach `it.bzz.ch`.
Das Repo `kompetenzmatrix.ch` / der Server werden **nie von Hand** bearbeitet.
