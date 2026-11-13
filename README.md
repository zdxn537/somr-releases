# SOMR. Downloads

Installer und Update-Dateien für die Programme von [SOMR.](https://somr.me). Kein Quellcode.

| Programm | Windows | macOS (Apple Silicon) |
|---|---|---|
| SOMR. Studio | [Setup](https://github.com/zdxn537/somr-releases/releases/download/studio/SOMR-Studio-Setup.exe) | [Setup](https://github.com/zdxn537/somr-releases/releases/download/studio/SOMR-Studio-Setup.dmg) |
| SOMR. Libr | [Setup](https://github.com/zdxn537/somr-releases/releases/download/libr/SOMR-Libr-Setup.exe) | [Setup](https://github.com/zdxn537/somr-releases/releases/download/libr/SOMR-Libr-Setup.dmg) |
| SOMR. Notez | [Setup](https://github.com/zdxn537/somr-releases/releases/download/notez/SOMR-Notez-Setup.exe) | [Setup](https://github.com/zdxn537/somr-releases/releases/download/notez/SOMR-Notez-Setup.dmg) |

Die Links funktionieren, sobald die jeweilige Fassung veröffentlicht ist. Mehr zu den Programmen: [somr.me/programme](https://somr.me/programme).

## Aufbau

Je Programm gibt es eine fortlaufende Veröffentlichung (`studio`, `libr`, `notez`). Darin liegen:

- `latest.json` (Windows) und `latest-macos.json` (macOS): Manifest für die eingebaute Update-Prüfung
- die Update-Pakete mit Versionsnummer und ihre Signaturen
- `SOMR-<Programm>-Setup.exe` und `SOMR-<Programm>-Setup.dmg`: immer die aktuelle Fassung

Jedes Update ist signiert; die Programme prüfen die Signatur, bevor sie etwas installieren.
