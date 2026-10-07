# Speichersystem — Spielversion 2

Jeder Spieler speichert unter seinem Heldennamen.
Wer denselben Namen wieder eingibt, bekommt denselben Stand.

Live-App: [spielversion2.grok.me](https://spielversion2.grok.me/)
Quellcode der laufenden Grok-Build-App liegt nicht in diesem Repo.
Der spielbare Stand mit verdrahtetem Speicher sitzt in [SpielVersion1.0](https://github.com/PromptBrainless/SpielVersion1.0).

## Regel

1. Speichern schreibt den kompletten Held unter `name`.
2. Namen werden getrimmt und kleingeschrieben verglichen (`Anna` = `anna`).
3. Ein zweiter Spieler mit anderem Namen bekommt einen eigenen Slot.
4. Derselbe Name überschreibt den alten Slot.
5. Laden beim Aufbruch: Namensfeld ausfüllen → vorhandener Stand wird angeboten.

## Wo der Stand liegt

| Schicht | Ort | Zweck |
| --- | --- | --- |
| Browser | `localStorage.lindendorf-saves-v2` | Sofort laden, mehrere Namen |
| Projekt | `saves/<name-key>.json` | Archiv / Austausch zwischen Geräten per Datei |

Kein Konto. Kein Passwort. Der Name *ist* der Schlüssel.

## Drop-in

`src/save/named-save.ts` ist absichtlich ohne Spiel-Typen.
In der Grok-Build-App:

- Beim HUD-Knopf Speichern: `saveNamed(held.name, held)`
- Beim Namensfeld: `loadNamed(name)` — wenn nicht null, Fortsetzen anbieten
- Auf der Titelseite: `listNamed()` für die Slot-Liste

Weltwerkzeug, Kanon und Auflagen bleiben unangetastet.
