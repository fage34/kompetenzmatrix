---
aliases:
  - /cluster-platform/m123/
title: M123 Serverdienste in Betrieb nehmen
modul: m123
cluster: cluster-platform
date: 2025-07-02T10:06:47Z
draft: false
kompetenzbaender:
  - id: A
    titel: Hardware
    kompetenzen:
      - nr: 1
        hz: "1"
        grundlagen: Ich kann wesentliche Merkmale von Serverhardware aufzählen.
        fortgeschritten: Ich kann den Einfluss von einzelnen Hardwarekomponenten auf die
          Performance analysieren und Optimierungsmöglichkeiten aufzeigen.
        erweitert: Ich kann für einzelne Serverdienste sinnvolle Hardwareausrüstung
          empfehlen.
  - id: B
    titel: Funktion Netzwerkdienste
    kompetenzen:
      - nr: 1
        hz: "1"
        grundlagen: Ich kann das Prinzip von Serverdiensten (Server-Client) erklären,
          die per DHCP einem Client zugewiesenen Angaben erklären und das
          Grundprinzip der DNS-Namensauflösung erklären.
        fortgeschritten: Ich kann die Funktion der einzelnen Serverdienste (DNS, DHCP)
          im Netzwerk zuordnen, die mit DHCP zugewiesenen Werte und deren
          Grenzen bestimmen sowie den Ablauf einer DHCP-Zuweisung und einer
          DNS-Namensauflösung mit geeigneten Tools nachvollziehen und
          überprüfen.
        erweitert: Ich kann anhand betrieblicher Bedürfnisse spezifische Funktionen von
          DNS- und DHCP-Diensten erkennen und auswählen, die DNS-Auflösung
          analysieren, über die Hosts-Datei gezielt beeinflussen und erläutern,
          wann eine statische Zuweisung von IP-Adressen sinnvoll ist.
      - nr: 2
        hz: "1"
        grundlagen: Ich kann das Prinzip des Bereitstellens von Daten über
          Netzwerkfreigaben erklären und Vor- und Nachteile von Druckerservern
          gegenüber dem Direktdruck erläutern.
        fortgeschritten: Ich kann Kriterien (Datensicherheit, Zugriffsberechtigungen,
          Bezeichnungen) für die gemeinsame Nutzung von Daten über
          Netzwerkfreigaben anwenden und umsetzen sowie die Einstellungen eines
          Druckerservers in einem Netzwerk konfigurieren und seine Funktionen
          gezielt beeinflussen.
        erweitert: Ich kann Netzwerkfreigaben einrichten, zusätzliche Möglichkeiten
          (versteckte Freigaben, Werkzeuge für Tests) nutzen,
          Berechtigungskonzepte (Dateisystem, Freigabe) planen sowie einen
          Druckerserver einrichten und die Bereitstellung von Druckertreibern
          planen.
  - id: C
    titel: Konfiguration
    kompetenzen:
      - nr: 1
        hz: 1, 2
        grundlagen: Ich kann verschiedene Konfigurationsarten auflisten und eine
          vorgegebene Konfiguration auf dem System umsetzen.
        fortgeschritten: Ich kann bestehende Konfigurationen interpretieren und anpassen
          sowie Vorgaben eigenständig in Konfigurationen übertragen und auf dem
          System umsetzen.
        erweitert: Ich kann Konfigurationen auf verschiedenen Systemen gemäss
          Vorbereitung erstellen und spezielle Anwendungen eigenständig in
          Konfigurationen übertragen und auf dem System umsetzen.
  - id: D
    titel: Installation und Prüfen
    kompetenzen:
      - nr: 1
        hz: "2"
        grundlagen: Ich kann Serverdienste/-rollen installieren und feststellen, ob der
          Serverdienst korrekt startet.
        fortgeschritten: Ich kann unterschiedliche Möglichkeiten zur Installation und
          Aktivierung von Diensten anwenden und vergleichen sowie die
          grundlegende Funktion eines Serverdienstes mit verschiedenen
          Werkzeugen (Befehle, Schnittstellen, Log-Dateien) überprüfen.
        erweitert: Ich kann Serverdienste aus unterschiedlichen Quellen vergleichen,
          Vor- und Nachteile auswerten, einen passenden Dienst installieren
          sowie Fehlfunktionen bei Serverdiensten mit einem Repertoire
          verschiedener Werkzeuge (Befehle, Schnittstellen, Log-Dateien)
          erkennen und daraus Massnahmen ableiten.
  - id: F
    titel: Client-Anpassung
    kompetenzen:
      - nr: 1
        hz: "3"
        grundlagen: Ich kann auf dem Client die entsprechende Funktion aktivieren und
          einrichten.
        fortgeschritten: Ich kann auf dem Client die Funktion aktivieren und die
          Funktionalität überprüfen.
        erweitert: Ich kann auf dem Client die Funktion einrichten, überprüfen und
          zusätzliche Ereignisse für Tests auslösen.
  - id: G
    titel: Zugriffsschutz
    kompetenzen:
      - nr: 1
        hz: "4"
        grundlagen: Ich kann verschiedene Arten von Zugriffsschutz im Netzwerk und auf
          dem Dateisystem erklären.
        fortgeschritten: Ich kann Zugriffsschutz auf verschiedenen Systemen umsetzen.
        erweitert: Ich kann einen kombinierten Zugriffsschutz über Benutzer- und
          Gruppenrechte erreichen (z. B. AGDLP-Prinzip).
  - id: H
    titel: Sicherheit und Dienstverwaltung
    kompetenzen:
      - nr: 1
        hz: "4"
        grundlagen: Ich kann verschiedene Möglichkeiten aufzählen, Systeme und Software
          zu warten, und aktivierte Dienste auf einem System erkennen.
        fortgeschritten: Ich kann Systeme und Software warten, Sicherheitsaspekte zur
          Absicherung umsetzen sowie aktive Dienste auf einem System erkennen
          und nicht benötigte deaktivieren.
        erweitert: Ich kann Systeme und Software fachgerecht betreuen, wesentliche
          Sicherheitsaspekte (Benutzerauthentifizierung, Zugriffsschutz auf
          Konfigurationen und Dienste) umsetzen sowie aktive Dienste und deren
          offene Schnittstellen erkennen und nicht benötigte Dienste
          deaktivieren bzw. Schnittstellen schliessen.
  - id: J
    titel: Funktionstest und Betriebsdokumentation
    kompetenzen:
      - nr: 1
        hz: 5, 6
        grundlagen: Ich kann mit einfachen Tests die Funktion eines Dienstes prüfen und
          wesentliche Aspekte eines Serverdienstes dokumentieren.
        fortgeschritten: Ich kann mit gut gewählten Testfällen die Funktion eines
          Dienstes prüfen, notwendige Massnahmen zur Fehlerbehebung umsetzen und
          eine vollständige Dokumentation von Serverdiensten erstellen.
        erweitert: Ich kann mit nach Anforderungen gewählten Testfällen die Funktion und
          Grenzen des Dienstes nachvollziehbar aufzeigen, notwendige Massnahmen
          umsetzen und eine vollständige sowie nachvollziehbare Dokumentation
          von Serverdiensten erstellen, die Konfiguration, Funktionstests und
          Planung bzw. Überlegungen dazu abbildet.
---
