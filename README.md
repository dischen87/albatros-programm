# Albatros – das Programm

Albatros begleitet dich beim Bauen deiner Webseite mit deiner eigenen KI.

Dieses Repository ist der öffentliche Ort für die Programmdateien. Der Quelltext liegt in einem separaten Repository. Hier werden nur signierte und geprüfte Fassungen für Mac und Windows veröffentlicht.

[Veröffentlichte Fassungen und Downloads](https://github.com/dischen87/albatros-programm/releases) · [Albatros im Browser starten](https://albatros.build/loslegen)

Solange die Liste der Veröffentlichungen leer ist, gibt es noch keine öffentliche Programmfassung. Du kannst Albatros bereits im Browser nutzen.

## Mac

Wähle bei der gewünschten Fassung die passende Datei:

| Dein Mac | Datei |
| --- | --- |
| Apple-Chip (M1 oder neuer) | `Albatros-<Version>-mac-arm64.dmg` |
| Intel | `Albatros-<Version>-mac-x64.dmg` |

Deinen Chip findest du im Apple-Menü unter «Über diesen Mac». Öffne die heruntergeladene Datei, ziehe Albatros nach «Programme» und starte es von dort.

Die App wird mit Apple Developer ID signiert und von Apple notarisiert. Die veröffentlichten `.zip`-Dateien sind ebenfalls für die jeweilige Architektur bestimmt.

## Windows

Eine Windows-Fassung erscheint erst, wenn ihr Setup signiert und geprüft ist. Die Datei heisst `Albatros-Setup-<Version>-x64.exe`. Welche KI auf Windows bereits unterstützt wird, zeigt Albatros beim Start.

## Download prüfen

Jede Veröffentlichung enthält `SHA256SUMS.txt`. Lade sie zusammen mit der gewünschten Programmdatei in denselben Ordner. Auf dem Mac kannst du dort im Terminal prüfen:

```sh
shasum -a 256 -c SHA256SUMS.txt --ignore-missing
```

Für deine heruntergeladene Datei muss `OK` erscheinen. Unter Windows zeigt PowerShell die Prüfsumme mit `Get-FileHash .\Albatros-Setup-<Version>-x64.exe -Algorithm SHA256`; vergleiche sie mit dem Eintrag in `SHA256SUMS.txt`.

Die Dateien `latest-mac.yml`, `latest.yml` und `.blockmap` gehören zur Aktualisierung des Programms; du musst sie nicht von Hand öffnen.

## Hilfe

[Frage stellen oder Problem melden](https://github.com/dischen87/albatros-programm/issues) · [Datenschutz](https://albatros.build/datenschutz) · [Impressum](https://albatros.build/impressum)

Bitte veröffentliche in Issues keine Passwörter, Schlüssel oder persönlichen Projektdaten.
