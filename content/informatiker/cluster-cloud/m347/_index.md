---
aliases:
  - /cluster-cloud/m347/
title: M347 Dienst mit Container anwenden
modul: m347
cluster: cluster-cloud
date: 2025-07-02T10:05:13Z
draft: false
kompetenzbaender:
  - id: A
    titel: Grundlagen
    kompetenzen:
      - nr: 1
        hz: "1"
        grundlagen: Ich kann zwischen Container und virtuellen Maschinen unterscheiden
          und deren Vor- und Nachteile aufzählen [^1][^2]
        fortgeschritten: Ich kann Anforderungen für einen Dienst mit Containern
          zielgerichtet und strukturiert erfassen [^3]
        erweitert: Ich kann Anforderungen für einen Dienst mit Containern analysieren
          und Verbesserungen sowie Optimierungen vorschlagen
  - id: B
    titel: Containerkomposition (Architektur)
    kompetenzen:
      - nr: 1
        hz: "2"
        grundlagen: Ich kann die Unterschiede zwischen monolithischen und
          Micro-Service-Architekturen darlegen und beschreiben
        fortgeschritten: Ich kann aufgrund der Anforderungen eine sinnvolle
          Container-Komposition vorschlagen und begründen
        erweitert: Ich kann aufgrund der Anforderungen mehrere Varianten von
          Container-Komposition vorschlagen und deren Vor- und Nachteile
          begründen
      - nr: 2
        hz: "2"
        grundlagen: Ich kann die wichtigsten Bestandteile [^6] der Container-Technologie
          aufzählen und beschreiben
        fortgeschritten: Ich kann eine einfache Analyse[^9] zur Entwicklung[^7] von
          containerisierten Diensten[^8] erstellen und erklären
        erweitert: Ich kann ein einfaches[^11] (Netzwerk-)Diagramm zum sicheren Betrieb
          von containerisierten Diensten[^8] erstellen und beschreiben
  - id: C
    titel: Containerdienstleister auswählen
    kompetenzen:
      - nr: 1
        hz: "3"
        grundlagen: Ich kann die benötigten Dienste des Containerdienstleisters für
          meine Zielapplikation aufzählen und beschreiben [^5][^22]
        fortgeschritten: Ich kann die Vor- und Nachteile[^4] von Public-Cloud-Anbietern
          (PCA) beschreiben und diese gegenüberstellen
        erweitert: Ich kann eine Entscheidungsmatrix mit relevanten Kriterien erstellen,
          um einen Containerdienstleister auszuwählen
      - nr: 2
        hz: "3"
        grundlagen: Ich kann wesentliche Merkmale einer Container-Registry nennen und
          Beispiele aufzählen [^23]
        fortgeschritten: Ich kann die relevantesten Technologien zur Orchestrierung von
          Containern aufzählen und deren Zweck beschreiben
        erweitert: Ich kann die Unterschiede zwischen public und private Container
          Registry aufzählen und beschreiben
  - id: D
    titel: Praxis mit Containern in der Entwicklung erlangen
    kompetenzen:
      - nr: 1
        hz: "4"
        grundlagen: Ich kann die Schritte zur Virtualisierung eines containerisierten
          Dienstes[^8] aufzeigen und beschreiben
        fortgeschritten: Ich kann eine einfache Container-Konfiguration gemäss Vorgaben
          erweitern, anpassen und ausführen
        erweitert: Ich kann eine umfangreiche Container-Konfiguration gemäss Vorgaben
          erweitern, anpassen und ausführen, mögliche Fehlerquellen erkennen und
          beheben
      - nr: 2
        hz: "4"
        grundlagen: Ich kann Container-Images aus einem Repository beziehen und
          anschliessend starten, anbinden/ausführen (attach/exec), evtl. Ports
          mappen, stoppen, löschen
        fortgeschritten: Ich kann selbst erstellte Container-Images in einer Registry
          dokumentieren und publizieren
        erweitert: Ich kann selbst erstellte Container-Images in mehrere Registries
          dokumentieren und publizieren
  - id: E
    titel: Praxis mit Containern beim Public-Cloud-Anbieter (PCA) erlangen (Betrieb)
    kompetenzen:
      - nr: 1
        hz: 2, 3, 4
        grundlagen: Ich kann einen sicheren Zugriff auf den PCA konfigurieren und
          anwenden sowie mindestens eine vom PCA zur Verfügung gestellte
          Storage-Variante beschreiben, konfigurieren und anwenden
        fortgeschritten: Ich kann eine Cloud-Instanz des PCA konfigurieren und verwalten
          sowie die verschiedenen Varianten zur Skalierung von PCA-Instanzen
          aufzählen und mindestens eine konfigurieren
        erweitert: Ich kann ein einfaches Netzwerk gemäss Vorgaben zum sicheren Betrieb
          von containerisierten Diensten konfigurieren und Metadaten einer
          Cloud-Instanz verwalten und auslesen
  - id: F
    titel: Qualitätskontrollen planen und umsetzen
    kompetenzen:
      - nr: 1
        hz: "5"
        grundlagen: Ich kann die wichtigsten Methoden[^18][^19] zur Qualitätssicherung
          und -kontrolle von Containern aufzählen und beschreiben
        fortgeschritten: Ich kann die wichtigsten Indikatoren zum sicheren Betreiben
          (Security) von Containern aufzählen und beschreiben
        erweitert: Ich kann bei einem vorgegebenen Container-Image die grundlegendsten
          Sicherheitslücken[^20] überprüfen und beseitigen
---
### Matrix

## Hinweise

[^1]: [Containers vs. Virtual Machines (VMs): What's the Difference?](https://www.netapp.com/blog/containers-vs-vms/)

[^2]: Wichtige Begriffe: Verfügbarkeit, Redundanz, Container, Image, Ressourcen, Wartbarkeit,.

[^3]: Anforderungen des Betriebes auf Bandbreite, Hardware, Instanzen, Skalierbarkeit in Bezug auf Containerisierung. <br/>[How to write a user story](https://www.ibm.com/garage/method/practices/think/user-stories/), [How User Stories Help Leaders Learn the Cloud](https://jdmeier.com/cloud-user-stories/)

[^4]: [Pro and Cons of Public Cloud](https://wisdomplexus.com/blogs/pros-cons-public-cloud/), Service models and responsiblities, difference public vs private cloud

[^5]: [What is the Public Cloud and what are typical use cases?](https://www.nine.ch/en/blog/what-is-the-public-cloud-and-what-are-typical-use-cases)

[^6]: Stages of Containerization (File - Build, Image - Ship, Container - Run), Docker Basic Commands, Dockerfile Syntax and Instructions, Container lifecycle, Container Hub usw.

[^7]: und Betrieb

[^8]: und Applikationen

[^9]: i.e. mit SWOT: <https://www.slideshare.net/techieguy85/cloud-computing-swot-analysis>

[^10]: Im Kontext von AWS: Classless Inter-Domain Routing (CIDR), Virtual Private Cloud (VPC), VPC Subnet, Route Table, Internet Gateway, NAT Gateway

[^11]: Internet Gateway und VPC mit je einem public und private Subnet. Alternative Service Discovery mit K8s demonstrieren/veranschaulichen.

[^12]: Internet Gateway, VPC mit je einem public und private Subnet, Bastion Host (public subnet). Alternative Ingress (Reverse Proxy, URL based Routing) mit K8s demonstrieren/veranschaulichen.

[^13]: Webinterface, CLI

[^14]: z.B. Identity and Access Management (IAM) bei AWS

[^15]: EC2 bei AWS

[^16]: Start, Stop, Delete der Cloud-Instanz

[^17]: Horzontal vs. Vertical Scaling, Scaling out vs. Scaling up

[^18]: Qualitätsmerkmale Norm (DIN/ISO 9126), Testarten, z.B. Schnittstellen-, Integration-, Komponenten-, System-, Lasttest usw.

[^19]: [Software Testing for Docker Containers: What's the Same, What's Different?](https://saucelabs.com/blog/software-testing-for-docker-containers-whats-the-same-whats-different), [Structure Testing for Docker Containers](https://semaphoreci.com/blog/structure-testing-for-docker-containers)

[^20]: [How to harden Docker images to enhance security](https://www.techtarget.com/searchitoperations/feature/How-to-harden-Docker-images-to-enhance-security), siehe Container-Abschnitt von  [National Security Agency: Kubernetes Hardening Guidance](https://media.defense.gov/2021/Aug/03/2002820425/-1/-1/1/CTR_KUBERNETES%20HARDENING%20GUIDANCE.PDF)

[^22]: Typen von Cloudcomputing aufzählen und beschreiben wurde entfernt, weil in M346 thematisiert wird (<https://aws.amazon.com/types-of-cloud-computing/>)

[^23]: Grundlagen zu Informationen zu Registrierungen, Repositories und Artefakten <https://docs.microsoft.com/de-de/azure/container-registry/container-registry-concepts>

- - -
