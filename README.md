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

## Als Webseite veröffentlichen (Cloudflare Pages, kostenlos)
Die Seite ist eine **PWA**: auf Handy/Tablet über „Zum Home-Bildschirm“ installierbar, läuft danach auch offline.

1. Auf <https://dash.cloudflare.com> kostenlos registrieren.
2. **Workers & Pages → Erstellen → Pages → Mit Git verbinden** → GitHub verbinden → Repository `Danyil` wählen.
3. Projektname: `sgm-trainer` (ergibt `https://sgm-trainer.pages.dev`, falls der Name frei ist).
4. Produktionszweig: den Zweig mit diesem Code wählen. Framework: **Keins**, Build-Befehl: **leer lassen**, Ausgabeverzeichnis: **`/`**.
5. **Speichern und bereitstellen.** Jede neue Version auf diesem Zweig wird automatisch veröffentlicht.

Dateien: `index.html` (Trainer), `manifest.webmanifest` + `sw.js` (App/Offline), `icons/`, `datenschutz.html`, `_headers` (Cache-Regeln).
