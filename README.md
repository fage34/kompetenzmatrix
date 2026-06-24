# Kompetenzmatrizen ZH

Öffentlich zugängliche Kompetenzmatrizen des Projekts **Modulentwicklung ZH** für die ICT-Module
der Fachrichtungen Applikationsentwicklung und Plattformentwicklung nach **BiVo2021**.

Live: **https://kompetenzmatrix.ch** · Bearbeiten: **/admin/** (Decap CMS)

## Was ist das hier?

Das **Arbeitsrepo** (Single Source of Truth) für die Matrizen. Inhalt = strukturierte YAML-Daten,
gerendert mit [Hugo](https://gohugo.io) (+ Theme `hugo-theme-learn` als Submodul).

```
content/<cluster>/<modul>/
  _index.md               # Kompetenzmatrix (YAML) + Bloom-Analyse/Änderungsprotokoll
  umsetzungsvorschlag.md   # Lektionsplanung
  handlungssituationen.md  # Handlungssituationen
layouts/                   # Matrix-Rendering (partials/matrix.html) + Navigation
static/admin/              # Decap CMS (Web-Editor)
schema/                    # JSON-Schema der Moduldaten
scripts/validate_modules.py# CI-Validierung (EHB-Regeln)
.github/workflows/         # validate.yml (PR) + deploy.yml (rsync nach it.bzz.ch)
```

Cluster: `cluster-api`, `cluster-cloud`, `cluster-data`, `cluster-math`, `cluster-org`,
`cluster-platform`.

## Versionen

`main` enthält die aktuelle (vormals „v2") Matrix. Die alte **Version 1** ist auf dem Branch
`v1-archive` eingefroren (nicht in Bearbeitung, nicht auf der Website).

## Lokale Entwicklung

```bash
git clone --recurse-submodules <repo-url>
cd kompetenzmatrix
hugo server
```

## Beitragen

Siehe [CONTRIBUTING.md](CONTRIBUTING.md) — Editieren via CMS oder PR, inkl. EHB-Inhaltsregeln.
Den vollständigen Ablauf (Bearbeiten → CI → Deploy) zeigt
[docs/matrix-bearbeiten.md](docs/matrix-bearbeiten.md).

## Setup-Hinweise (einmalig)

- **CMS-Auth** (Open Authoring): selbst-gehostetes PHP-Relay auf dem Server unter
  `https://kompetenzmatrix.ch/cms-oauth` (Code: `/var/www/kompetenzmatrix.ch/cms-oauth/index.php`).
  GitHub-OAuth-App erstellen (Callback `https://kompetenzmatrix.ch/cms-oauth/callback`),
  `client_id`/`client_secret` in `/etc/cms-oauth-config.php` eintragen. `base_url` steht in
  `static/admin/config.yml`. Das Relay ist via `rsync --exclude=cms-oauth/` vor Deploys geschützt.
- **Deploy-Secrets**: `DEPLOY_SSH_KEY` (Secret) + `DEPLOY_PATH` (Variable) für `root@it.bzz.ch`.
