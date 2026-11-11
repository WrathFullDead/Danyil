# SGM Zyklus-Trainer

Lern-Simulator für den **Zyklusablauf einer Spritzgießmaschine (SGM)** – passend zum Arbeitsblatt
„Zyklusablauf einer SGM“ (Kunststoff- und Kautschuktechnik). Unabhängiges Schulprojekt, kein Herstellerprodukt.

## Starten
`index.html` im Browser öffnen (PC, iPad, Handy) – keine Installation, läuft offline.
Über GitHub Pages kann die Datei auch als Webseite bereitgestellt werden.

## Funktionen
- **Produktionsablauf-Editor** mit Symbolen: Werkzeug schließen/öffnen, Einspritzen, Nachdruck, Restkühlzeit,
  Dosieren, Dekompression, Düse vor/zurück, Auswerfer vor/zurück/Rütteln/Zwischenstopp,
  Schutztür auf/zu, Ausblasventil 1 Start/Ende, Überwachung 1 Start/Ende (Ausdrehkern).
- **Ablauf editieren**: Symbol einfügen (seriell/parallel), verschieben, löschen, Startbedingung ändern,
  Antrieb umschalten, Zweigende verschieben, Grundablauf, Rückgängig.
- **Simulation** (1 Zyklus / Automatik) mit animierter Maschine, Verriegelungen und Alarmen
  (z. B. „Einspritzen gesperrt: Düse nicht angelegt“, „Werkzeugsicherung“).
- **Zeitdiagramm** und Zykluszeit – zeigt, wie Parallelbewegungen die Zykluszeit verkürzen.
- **Antriebskonzepte**: 1 Hydraulikpumpe (keine Parallelbewegungen), Hydrospeicher/Mehrkreis, elektrisch.
- **Aufgaben 1–8 + Ausdrehkern-Varianten** mit „Prüfen“ und „Lösung laden“, inkl. Erkenntnis-Fragen.
- Speicherung im Browser, Export/Import als JSON.
