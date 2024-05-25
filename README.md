```markdown
# LifeSim++

LifeSim++ ist ein interaktives Lebenssimulationsspiel, das in C++ entwickelt wurde und sich an der beliebten App BitLife orientiert. Ziel des Projekts ist es, den Spieler durch verschiedene Lebensphasen zu führen und Entscheidungen treffen zu lassen, die das Leben des Charakters beeinflussen. 

## Projektübersicht

**LifeSim++** bietet eine umfassende Simulation des Lebens eines Charakters von der Geburt bis zum Tod. Spieler können Entscheidungen über Bildung, Karriere, Beziehungen und viele andere Aspekte des Lebens treffen. Diese Entscheidungen wirken sich auf die Attribute des Charakters wie Gesundheit, Glück und Intelligenz aus. 

## Features

- **Objektorientierte Programmierung (OOP)**: Nutzung von Klassen für die verschiedenen Komponenten des Spiels (Character, Event, Game).
- **Generische Templates & Datenstrukturen**: Einsatz von `std::vector`, `std::map` und Templates zur Verwaltung von Spielinformationen.
- **Ausnahmebehandlung**: Implementierung von `try-catch`-Blöcken und benutzerdefinierten Ausnahmen zur robusten Fehlerbehandlung.
- **Datenströme und Dateien**: Speichern und Laden von Spielständen mit `ifstream` und `ofstream`.
- **Grafische Programmierung (Qt)**: Entwicklung einer grafischen Benutzeroberfläche mit Qt, einschließlich Widgets wie `QMainWindow`, `QPushButton` und `QLabel`.
- **Threads, nebenläufige und verteilte Programme**: Einsatz von `QThread` zur parallelen Ausführung von Hintergrundaufgaben.

## Installation

1. **Abhängigkeiten installieren**:
    - Qt Framework
    - C++ Compiler (z.B. g++ oder clang)

2. **Repository klonen**:
    ```sh
    git clone https://github.com/deinusername/LifeSimPlusPlus.git
    cd LifeSimPlusPlus
    ```

3. **Projekt bauen**:
    ```sh
    qmake
    make
    ```

## Nutzung

Starten Sie das Spiel durch Ausführen der erstellten ausführbaren Datei. Das Hauptfenster zeigt die verschiedenen Attribute des Charakters und bietet Interaktionen für Entscheidungen und Ereignisse im Spiel.

## Projektstruktur

- **src/**: Enthält den Quellcode des Projekts.
  - `main.cpp`: Einstiegspunkt des Programms.
  - `Character.h` und `Character.cpp`: Definieren die Charakterklasse und ihre Methoden.
  - `Event.h` und `Event.cpp`: Definieren die Ereignisklasse und ihre Methoden.
  - `Game.h` und `Game.cpp`: Steuern den Spielfluss und die Interaktionen.
- **ui/**: Enthält die Qt-UI-Dateien und -Ressourcen.
- **data/**: Beinhaltet Beispieldateien für gespeicherte Spielstände.

Viel Spaß beim Spielen von LifeSim++! 🍀
```
