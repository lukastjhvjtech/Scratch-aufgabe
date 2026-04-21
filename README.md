# Scratch Programm: Wiederholungen (Einstieg)

Dieses Scratch-Programm demonstriert das Konzept der **Wiederholung mit fester Anzahl** basierend auf dem Beispiel von [inf-schule.de](https://inf-schule.de/imperative-programmierung/scratch/wiederholungen/einstieg_wiederholungen).

## Beschreibung

Das Programm zeigt eine Ente ("ducki"), die auf einem Trampolin springt. Anstatt die Bewegungsbefehle mehrfach zu wiederholen, wird hier die **Wiederholungsblock** (`repeat 4`) verwendet, um den Code effizienter und übersichtlicher zu gestalten.

### Funktionsweise

1. **Event**: Wenn auf die Ente geklickt wird (`when this sprite clicked`)
2. **Wiederholung**: Die folgende Aktion wird 4 Mal wiederholt (`repeat 4`):
   - Gleite in 0.5 Sekunden nach oben (x: 12, y: 64)
   - Gleite in 0.5 Sekunden nach unten (x: 12, y: -64)

### Blöcke im Detail

```
Wenn ducki angeklickt
wiederhole 4 mal
    gleite in 0.5 Sek. zu x: 12 y: 64
    gleite in 0.5 Sek. zu x: 12 y: -64
```

## Datei

- `ente_wiederholung.sb3` - Die fertige Scratch 3.0 Projektdatei

## Verwendung

1. Öffne die Datei `ente_wiederholung.sb3` im [Scratch Editor](https://scratch.mit.edu/projects/editor/)
2. Klicke auf die Ente, um die Wiederholungsbewegung zu starten
3. Beobachte, wie die Ente 4 Mal hintereinander springt

## Lernziel

Dieses Beispiel veranschaulicht:
- Das Konzept der **Wiederholung mit fester Anzahl**
- Wie man durch Schleifen Code duplizierung vermeidet
- Den Unterschied zwischen sequentieller Ausführung und strukturierter Wiederholung

## Quelle

Basierend auf dem Beispiel "Ente auf Trampolin" von [inf-schule.de - Einstieg Wiederholungen](https://inf-schule.de/imperative-programmierung/scratch/wiederholungen/einstieg_wiederholungen)
