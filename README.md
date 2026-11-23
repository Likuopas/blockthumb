# BlockThumb

Thumbnail-Generator im EinfachGustaf-Look: eine einzelne `index.html`, alles im Browser (Canvas), kein Build.

## Nutzung

1. Seite öffnen: https://likuopas.github.io/blockthumb/
2. Optional Hintergrundbild hochladen. Ohne Upload zeichnet die Seite eine Minecraft-Wiese wie auf einem Spiel-Screenshot: blauer Himmel mit Blockwolken, Baumreihe und Blockhügel am Horizont, davor ein Grasfeld mit Blockraster und Grashalmen.
3. Charakter hochladen:
   - **Skin 64×64** (128×128 geht auch) – wird zur Figur gerendert.
     - Klassisches Modell: 4 px breite Arme.
     - Slim-Modell (Alex): 3 px breite Arme, wird an den Außenkanten der Armtextur erkannt und nicht gestreckt.
   - **Altes 64×32-Layout** – Arme und Beine werden gespiegelt, damit die Figur vollständig ist.
   - **Fertiges PNG** mit Transparenz – wird direkt eingesetzt.
   - Falls die Erkennung daneben liegt: Feld „Modell“ auf „klassisch“ oder „slim“ stellen.
4. Headline ist optional. Leer gelassen erscheint **kein Text** im Thumbnail, so wie in den Vorlagen. Wenn Text gewünscht ist: eine Zeile pro Textzeile, `|…|` färbt einzelne Wörter in der Akzentfarbe.
5. „Thumbnail herunterladen“ speichert ein 1280×720-JPG.

## Hinweise

- Kontur, Schatten und oranger Pfeil lassen sich einzeln abschalten.
- Der Pfeil zeigt automatisch zur Seite, auf der der Charakter steht.
- Größe der Figur über den Regler (240–760 px).
- Alles läuft lokal im Browser, es werden keine Bilder hochgeladen.
