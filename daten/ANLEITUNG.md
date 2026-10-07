# Anleitung: Kindergarten-Daten pflegen (PRiK)

Alles, was für den Kindergarten auf der Webseite steht, kommt aus der Datei **`prik.js`** in diesem Ordner.
Die Dateien `prigs.js` und `pris.js` sind für die 1.–6. Klasse — dort bitte nichts ändern.

## 1. Fotos hochladen
1. Auf github.com das Projekt **StaFF_Material** öffnen, in den Ordner **bilder** wechseln.
2. **Add file → Upload files**, Fotos hineinziehen.
3. Dateinamen einfach und eindeutig wählen, ohne Leerzeichen und Umlaute, z. B. `k1-handpuppe.jpg`
   (`k1` = Kindergarten Gruppe 1).
4. Unten bei **Commit changes** auf den grünen Knopf klicken.

## 2. Text und Material ändern
1. Im Ordner **daten** die Datei **prik.js** öffnen.
2. Auf das Stift-Symbol (Edit) klicken.
3. Ändern oder ergänzen — das Beispiel in der Datei zeigt, wie ein Eintrag aussieht.
4. **Commit changes** klicken. Nach 1–2 Minuten ist die Änderung auf der Webseite sichtbar.

## 3. Wichtige Regeln
- Jede Zeile in der Liste endet mit einem **Komma**.
- Texte stehen zwischen **'einfachen Anführungszeichen'**.
- Ein Foto wird mit `photo:'dateiname.jpg'` eingetragen; der Name muss genau zum hochgeladenen Bild passen.
- Nicht in `index.html` arbeiten.

## 4. Wenn etwas kaputt geht
Auf github.com die Datei öffnen → **History** → die letzte gute Version wählen → **Revert**. Es geht nie etwas verloren.

## 5. Mit einer KI arbeiten (z. B. Claude)
Gib der KI nur die Datei `prik.js` und schreibe: «Ändere nur diese Datei, behalte das Format bei und ändere nichts anderes.»
Den neuen Inhalt in `prik.js` einfügen und mit **Commit changes** speichern.
