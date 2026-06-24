---
title: Handlungssituationen
weight: 20
draft: false
---

# Handlungssituationen - Modul 426

Zu jedem Handlungsziel aus der Modulidentifikation (hier gekürzt wiedergegeben) werden eine oder mehrere realistische, beispielhafte und konkrete Handlungssituationen beschrieben, die zeigen, wie die Kompetenzen in der Praxis angewandt werden.

## 1. Vorgegebene Funktionalität mit einer agilen Methode umsetzen.

Ich kann für mein bevorstehendes Projekt, das erst einmal aus einer Idee und einem Satz von Funktionalitäten besteht, eine Vorgehensmethode auswählen. Dabei weiss ich, was wann zu tun sein wird und was die Rollen im Projektteam sind und wer die bekleiden könnte, damit und kann dies meiner Abteilungsleitung und/oder dem Kunden vorschlagen kann. 

## 2. Funktionalität iterativ umsetzen.

Aus dem Sprintbacklog nehme ich eine nächste UserStory, um diese umzusetzen. Ich analysiere die bestehenden Epics und überlege mir, wo Ergänzungen aus der UserStory hinzufügen und wo allenfalls ein Refactoring notwendig wird. 

Ich implementiere mit dem Team die Ergänzungen. Parallel dazu ergänze ich die bestehenden Unit Tests, die automatisiert meine Anpassungen überprüfen. Ich überprüfe die Qualität meiner Implementierung mit einer statischen Code-Analyse (Lint) und füge, wo nötig, Korrekturen an. Ich committe meine Änderungen in die Versionsverwaltung und pushe diese auf den Server, wodurch ich einen Continuous-Build, einen Continuous-Test und die Continuous-Integration anstosse.

Den Output der Continuous-Integration nutze ich für die Überprüfung meiner Implementierung auf dem Testsystem. Ich schliesse die Umsetzung der UserStory mit einer Überprüfung anhand der Definition of Done (DoD) ab.

Am Ende des Sprints bereitet sich mein Team auf die Sprint-Demo vor. Dabei bereite ich mich so vor, dass ich an der Sprint-Demo die von mir umgesetzten Teile live vorführen kann.

## 3. Bestehende Entwurfsmuster und/oder Softwarekomponenten gezielt einsetzen.

Für eine Bank soll die Erstellung der Konti zentralisiert werden. Nach einer Spezialisierung (Vererbung) der Konti (Sparkonto, Lohnkonto, Jugendsparkonto, etc.) wird der Einsatz eines Entwurfsmusters sichtbar. Es ist nun nötig, das Factory-Pattern zu realisieren, wodurch die Instanzierung und Erstellung der Objekte an eine Factory (Fabrik) ausgelagert wird.

## 4. Die Ergebnisse reflektieren und Erkenntnisse ableiten.

Ich bereite mich auf das Daily Scrum vor, indem ich mir die drei "Scrum-Fragen" bzgl. Sprint Goal überlege:
- Was habe ich seit dem letzten Stand-Up Meeting erledigt?
- Was werde ich bis zur nächsten Stand-Up Besprechung tun?
- Welche Hindernisse oder Risiken gibt es?

Am Ende eines Sprints nach dem Review Meeting nehme ich an der Retrospektive teil, wo ich meine Erfahrungen und Erkenntnisse aus dem vergangenen Sprint einbringe.

## 5. Versionsverwaltungssystem verwenden.

Im Rahmen der Umsetzung des Projektes nutzte ich die Versionsverwaltung, um meine Änderungen im kollaborativen Zusammenspiel mit dem Team zu sichern, zu verwalten und auszutauschen. Ich wende "commit" und "push" sicher an und achte auf die Inhalte der "messages" (wieso und nicht was). Ich kann mit "merge-requests" umgehen und bei einem "merge" auftretende Probleme lösen.

## 6. Programmquelltext bei Bedarf überarbeiten.

Ich bekomme einen Programmcode und kann die Code-Konventionen dieser Programmiersprache darauf anwenden, kenne die Best Practices für einen Clean-Code und kann (oder muss) jetzt das Refactoring durchführen.
