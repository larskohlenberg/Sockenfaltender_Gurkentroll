# Sockenfaltender Gurkentroll

Eine absurde Wortgenerator-App mit Slot-Machine-Animation für den Browser.

**→ [Ausprobieren](https://larskohlenberg.github.io/Sockenfaltender_Gurkentroll/)**

---

## Was ist das?

Eine minimalistische Web-App, die zufällige, grammatikalisch korrekte aber inhaltlich vollkommen durchgeknallte deutsche Wortkombinationen generiert — im Stil einer Spielautomaten-Animation.

Drück auf **Tap**. Lehn dich zurück. Staune.

Beispiele:
- *Gurkenbrütender Quarktunichtgut mit pelzigem Wabbeltroll*
- *Hektisch tanzender Knatterbengel*
- *Schrulliger Knirpsgauner hinterm Pommesstrolch*
- *Marmeladepiepsender Wurstklopfer*

## Features

- **Slot-Machine-Animation** — Wörter rollen über den Bildschirm und rasten nacheinander ein
- **Grammatikalisch korrekt** — Adjektivdeklination, Kasusformen, Komposita-Bildung nach deutschen Regeln
- **Echter Zufall** — `crypto.getRandomValues`, keine vorhersehbaren Sequenzen
- **Über 900.000 Kombinationen** — aus strukturierten Wortlisten für Verben, Objekte, Präfixe und Substantive
- **2–5 Wörter** — sechs verschiedene Satzmuster (Partizip, Adverb, Adjektiv, Präpositionalgefüge)
- **Offline-fähig** — alles in einer einzigen HTML-Datei, kein Backend, keine externen Abhängigkeiten
- **Mobiloptimiert** — Touch-ready, Safe-Area-Support, funktioniert auf iPhone/Safari
- **Sanfter Glow-Effekt** auf dem Endergebnis

## Technisch

| Was | Wie |
|-----|-----|
| Technologie | Reines HTML + CSS + JavaScript |
| Frameworks | Keine |
| Abhängigkeiten | Keine |
| Backend | Keins |
| Dateien | Eine (`index.html`) |

## Lokal starten

Einfach `index.html` im Browser öffnen — fertig. Oder per lokalem Server:

```bash
python3 -m http.server 8080
# → http://localhost:8080
```

## Grammatik-Engine

Die App kombiniert echte Wortklassen mit korrekten deutschen Flexionsregeln:

- **Partizip-Adjektive** wie *sockenfaltender* aus `socken` + `faltend` + `-er` (Nom. Mask. stark)
- **Adjektive im Dativ** wie *pelzigem* für Konstruktionen mit *mit/im/beim*
- **Komposita** aus Präfix- und Basisstämmen (nur starke Maskulina, keine n-Deklination)
- **6 Satzmuster** von 2-wörtig bis 5-wörtig

## Lizenz

MIT
