# Anleitung: Kindergarten-Seite pflegen (PRiK)

Der Kindergarten hat eine **eigene Seite** und gehört dir:

- **`kindergarten.html`** (im Hauptordner): die Seite selbst, also Aufbau, Aussehen und Ablauf.
- **`daten/prik.js`**: der Inhalt, also Gruppen, Einheiten, Material, Fotos.
- **`bilder`**: alle Fotos (gemeinsam mit den anderen Klassen, deshalb Dateinamen mit `k` beginnen, z. B. `k1-handpuppe.jpg`).

**Bitte nichts ändern an:** `index.html`, `daten/prigs.js`, `daten/pris.js`. Das ist die Seite für die 1.–6. Klasse.

## 1. Fotos hochladen
1. Auf github.com das Projekt **StaFF_Material** öffnen, in den Ordner **bilder** wechseln.
2. **Add file → Upload files**, Fotos hineinziehen (Namen ohne Leerzeichen und Umlaute).
3. Unten **Commit changes** klicken.

## 2. Inhalt ändern (`daten/prik.js`)
1. Datei öffnen, Stift-Symbol (Edit) klicken.
2. Ändern oder ergänzen; das Beispiel in der Datei zeigt, wie ein Eintrag aussieht.
3. **Commit changes**. Nach 1–2 Minuten ist es auf der Seite sichtbar.

## 3. Aufbau ändern (`kindergarten.html`)
Dasselbe Vorgehen wie oben, aber in `kindergarten.html`. Hier steckt der ganze Aufbau der Seite. Am besten lässt du dir dabei von einer KI helfen (siehe unten) und prüfst die Seite danach im Browser.

## 4. Regeln für `prik.js`
- Jede Zeile in der Liste endet mit einem **Komma**.
- Texte stehen zwischen **'einfachen Anführungszeichen'**.
- Ein Foto wird mit `photo:'dateiname.jpg'` eingetragen; der Name muss genau zum Bild passen.

## 5. Wenn etwas kaputt geht
Auf github.com die Datei öffnen → **History** → letzte gute Version wählen → **Revert**. Es geht nie etwas verloren.

## 6. Mit einer KI arbeiten (ChatGPT, Claude)
Der Datei-Inhalt kommt in die KI mit dem Satz: «Ändere nur diese Datei, behalte das Format bei und ändere nichts anderes. Gib mir die ganze Datei zurück.»
Den neuen Inhalt in die Datei auf GitHub einfügen und mit **Commit changes** speichern. Bei `kindergarten.html` am besten zuerst eine Kopie der alten Version speichern.
