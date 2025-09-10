# KanbanReminders

KanbanReminders bringt Apple Erinnerungen (EventKit) in drei Arbeitsmodi zusammen: als Kanban‑Boards, als kompakte Listen und in einer Kalenderansicht. Projekte gruppieren deine Boards, Drag & Drop macht das Sortieren schnell, Zuweisungen an Personen halten Verantwortlichkeiten klar – mit Undo/Redo und einer anpassbaren Oberfläche.

## Installation

- TestFlight (Beta): https://testflight.apple.com/join/QXSkD4CW  
- App Store: folgt nach Veröffentlichung

## Funktionen

- Arbeitsmodi
  - Kanban: Spalten pro Liste mit Drag & Drop (inkl. Auto‑Scroll)
  - Liste: Kompakte vertikale Board‑Ansicht
  - Kalender: Monatsansicht mit Tages‑Detail und Schnellanlage
- Projekte
  - Projekte anlegen/auswählen, Boards pro Projekt verwalten
  - Reihenfolge pro Projekt, Boards ein-/ausblenden
  - Projektübersicht mit schneller Auswahl
- Aufgaben-Details
  - Titel, Notizen, Link, Bild‑Anhang (lokal gespeichert)
  - Fälligkeit (Datum/Uhrzeit), Priorität
  - Wiederholung: Nie, Täglich, Wöchentlich, Monatlich, Jährlich
  - Zuweisung an Personen (mit optionalen Avataren)
- Boards/Listen
  - Erstellen, Umbenennen, Löschen
  - Account/Quelle wählen (z. B. iCloud, Exchange, Lokal)
- Personen
  - Anlegen, Umbenennen, Löschen
  - Avatare via Fotos (lokal gespeichert)
  - Automatische Erkennung von Personennamen aus Notizen
- Archiv
  - Erledigte Aufgaben mit Wiederherstellen
- Darstellung
  - Erscheinungsbild: System/Hell/Dunkel
  - Akzentfarbe wählbar
  - Avatare statt Namen (optional)

## Entwicklung

- Xcode 15+ und iOS 16.0+
- App starten, Zugriff auf Erinnerungen erlauben
- In der App: Einstellungen öffnen, Boards/Projekte/Personen verwalten

## Daten & Synchronisierung

- Aufgaben/Boards: Apple Erinnerungen (EventKit), Synchronisierung über deine Accounts (z. B. iCloud)
- Projektstruktur: Spezieller Erinnerungs‑Kalender „Projekt:Struktur“ zur portablen Ablage von Zuordnung/Reihenfolge
- Personen & Einstellungen: Lokal via UserDefaults
- Bilder: Lokal im App‑Dokumentenordner

## Datenschutz

- Keine eigenen Server, keine Drittanbieter‑Tracker
- Daten bleiben in deinen Apple‑Accounts oder lokal
- Bilder/Avatare werden nur lokal gespeichert

## Lizenz

Proprietär – Alle Rechte vorbehalten. Der Quellcode ist nicht zur Weiterverwendung lizenziert. Die App ist aktuell über TestFlight verfügbar; eine Veröffentlichung im App Store ist geplant.
