---
aliases:
  - /cluster-api/m450/umsetzungsvorschlag/
title: Umsetzungsvorschlag
weight: 10
draft: false
---

# Umsetzungsvorschlag - Modul 450
Applikationen testen

## Lektionenplan

| Anzahl Lektionen | Themen                              | Kompetenzen | Tools                                     |
|------------------|-------------------------------------|-------------|-------------------------------------------|
| 2                | **Einführung**                      |             |                                           |
|                  | - Unterschied TEST, PROD etc.       |             |                                           |
| 4                | **Testkonzept**                     | A1, A2      | z.B. Confluence, Azure DevOps             |
|                  | - Testziele/-strategien             |             |                                           |
|                  | - Testdefinition/-umgebung          |             |                                           |
|                  | - Risikobasiertes Testen            |             |                                           |
| 4 / 10           | **Testdesign/-definition**          | B1          | z.B. Zephyr oder TestRail                 |
|                  | - Testarten/-stufen                 |             |                                           |
|                  | - Testfallentwurf                   |             |                                           |
|                  | - Black-Box-Testing                 |             |                                           |
|                  | - White-Box-Testing                 |             |                                           |
| 2                | **Funktionale Tests**               |             | z.B. TestComplete oder HP UFT             |
|                  | - Testarten/-methoden               |             |                                           |
|                  | - GUI Testing                       |             | z.B. Selenium                             |
| 8 /20            | **Automatisierung**                 | C1, C2      | z.B. Selenium oder Katalon Studio         |
|                  | - Testausführung/-überwachung       |             |                                           |
|                  | - Testautomatisierung und Werkzeuge |             |                                           |
|                  | - Fehlerreporting und -tracking     |             |                                           |
|                  | - Konfiguration der CI/CD-Pipeline  |             | z.B. GitHub, GitLab, BitBucket            |
| 2                | **Prüfung**                         |             |                                           |
| 4                | **Testmanagement**                  |             | z.B. HP ALM oder Zephyr                   |
|                  | - Testprozess/-phasen               |             |                                           |
|                  | - Testabdeckung und Testmetriken    |             |                                           |
|                  | - Testberichterstattung             |             |                                           |
|                  | - Schnittstellen / APIs             |             | z.B. Postman, Swagger                     |
| 6 / 32           | **Review**                          | D1          |                                           |
|                  | - Statische Code Analyse            |             | z.B. SonarQube, FxCop oder Lint           |
|                  | - Clean Code Prinzipien             |             |                                           |
| 2                | **Fehleranalyse und Debugging**     |             | z.B. Fiddler oder Firebug                 |
|                  | - Fehlerarten/-quellen              |             |                                           |
|                  | - Debugging-Techniken               |             |                                           |
| 2                | **Prüfung**                         |             |                                           |
| 4 / 40           | **Reserve Lektionen**               |             |                                           |
|                  | - Leistungs- und Lasttests          |             | z.B. LoadRunner oder JMeter               |


<mark>Es fehlt das HZ-8 und unserer Meinung nach etwas zum Thema "Auswerten der Testresulate" <br> Im Umsetzungsvorschlag sind diese Punkte drin, werden aber in der Matrix nicht abgebildet, deshalb im Umsetzungsvorschlag auch mit keinem Band verknüpft.</mark>


## Tools

| Funktionen            | Azure DevOps | Atlassian  | HP ALM | TestRail | qTest | JIRA | Zephir |
|-----------------------|--------------|------------|--------|----------|-------|------|--------|
| Testmanagement        | ✔            | ✔         | ✔      | ✔       | ✔     |      | ✔     |
| Testautomatisierung   | ✔            |            | ✔      | ✔       | ✔    | ✔    | ✔     |
| Testberichterstattung | ✔            |            | ✔      | ✔       | ✔    | ✔    | ✔     |
| Fehlerverfolgung      | ✔            | ✔         | ✔      | ✔       | ✔     | ✔    | ✔     |
| Integrationen         | ✔            | ✔         | ✔      | ✔       | ✔     | ✔    | ✔     |
| Agile Unterstützung   | ✔            |           | ✔      | ✔        | ✔    | ✔    |        |
| Review                |              | ✔         |         | ✔       | ✔     |      |        |
