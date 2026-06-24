---
aliases:
  - /cluster-cloud/m346/umsetzungsvorschlag/
title: Umsetzungsvorschlag
weight: 10
draft: false
---

# Umsetzungsvorschlag M346

## Grundidee und didaktisches Konzept

Neben den für die geforderten Kompetenzen essenziellen theoretischen und konzeptionellen Inhalten, soll in diesem Modulunterricht praxisorientiert und wenn möglich mit kleinen Fallstudien gearbeitet werden, um die komplexe und breite Materie zu vermitteln. Aufgrund der Themenvielfalt und der hohen Abstraktionsbreite müssen die Lernenden in den Aufträgen eng geführt werden und es soll möglichst viel vorgegeben sein. Es würde sich auch anbieten, (parallel) eine grössere Fallstudie zu bearbeiten, mithilfe einer etablierten Open-Source-Software, welche in  unterschiedlichen Arten betrieben werden kann und mittlere Anforderungen voraussetzt, so z.B. Application-, DB- und (File-)Storage-Server.

### Zeitliche Budgets:

* 1/3 Theorie, Grundwissen, Konzeptarbeit

* 2/3 praxisorientiertes "Hands-On"

## Grobplanung

| Anz. Lekt. | Themen                                                                                  | KB   | Ressourcen/Tools                                |
| ---------- | --------------------------------------------------------------------------------------- | ---- | ----------------------------------------------- |
| 3          | On-Premise, private/public-Cloud, VM, Rechenzentren, Betriebsmodi von Appl.             | A, D | MaaS, AWS, DO                                   |
| 3          | Service-Modelle Cloud-Anbieter, Anwendungsfälle und Stolpersteine                       | B, D | Fallstudie Heise                                |
| 2          | Kostenkalkulatoren, IT-Personalaufwände, Migrationsaufwände                             | C, D | AWS, GCP, Azure                                 |
| 3          | Cloud-Anbieter, Vor- und Nachteile, Recap der Anforderungen an Ziellösung               | A, D | Fallstudie Heise                                |
| 3          | Schutzziele (CIA), Wartung, Skalierbarkeit, Hochverfügbarkeit, Resilienz                | E    | BSI Grundschutz Handbuch, e-ch.ch               |
| 7          | Installationsscripts, Blueprint-VMs, Container-Images, Redundanz, Load-Balancing        | F    | Multipass, Docker for Desktop, Cloud Init, Bash |
| 2          | Security-Groups, Firewalling, Permissions                                               | F, G | AWS, SSH(d)                                     |
| 3          | Backup, Restore, 3-2-1, Snapshots, Sync                                                 | F, H | BorgBackup, Linux-Builtins, SCP/SFTP            |
| 3          | Testprotokoll, Performance-Testing, Linux-Tools, Skalierbarkeit vertikal vs. horizontal | I    | Linux-Tools, Anbieter-Tools                     |
| 3          | Monitoring, Notifications, Massnahmenplanung                                            | J, F | AWS                                             |
| 2          | Ressourcen-Skalierung (vert.) und Grenzen der Skalierbarkeit                            | K    | am Schluss: k8s/microk8 (Demo)                  |
|            |                                                                                         |      |                                                 |
| 2          | Kompetenzüberprüfungen (zzgl. zu den im Unterricht integrierten)                        |      |                                                 |
| 4          | Puffer                                                                                  | \-   |                                                 |
| 40         | Total                                                                                   |      |                                                 |
