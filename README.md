# BlockThumb

Minecraft-Thumbnail-Generator im EinfachGustaf-Look - eine einzige HTML-Datei, kein Server, kein Build.

## Nutzung

1. Seite oeffnen (`index.html` lokal oder die GitHub-Pages-URL).
2. Hintergrundbild waehlen; ohne Upload wird ein Platzhalter-Biom gezeichnet.
3. Charakter-PNG mit Transparenz waehlen, Groesse und Seite einstellen.
4. Headline eintippen: eine Zeile pro Zeile, Akzentwort in `|...|` setzen.
5. Kontur / Schatten / Pfeil nach Bedarf schalten, dann **Thumbnail herunterladen** -> 1280x720 JPG.

## Hinweise

- Die weisse Kontur braucht ein PNG mit Alpha-Kanal; bei einem JPG entsteht ein Rahmen ums ganze Rechteck.
- Der Download haengt den Anchor vor dem Klick an `<body>` (noetig fuer Safari/iOS) und faengt `toDataURL`-Fehler ab.
- Alles laeuft lokal im Browser: keine Requests, keine Tracker, keine Abhaengigkeiten.
