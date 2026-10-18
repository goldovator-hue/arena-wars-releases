# GOLDOVATOR · ARENA WARS – Windows Downloads

Offizieller öffentlicher Downloadkanal für **Arena Wars** von Goldovator Studios.

Die Entwicklung und alle internen Quelldateien verbleiben im **privaten** Repository. Dieses öffentliche Repository enthält ausschließlich geprüfte Windows-Veröffentlichungen und die nötigen Update-Dateien. Es werden **keine** Twitch-Tokens, OBS-Passwörter, Datenbanken oder privaten Quelltexte veröffentlicht.

## Windows installieren

Sobald die erste geprüfte Version veröffentlicht wurde, findest du sie unter **[Releases](https://github.com/goldovator-hue/arena-wars-releases/releases)**. Die Windows-EXE enthält den lokalen Arena-Wars-Server. Node.js muss nicht separat installiert werden.

Die Veröffentlichungen enthalten:
- `Arena-Wars-VERSION-x64.exe` – Windows-Installer
- `Arena-Wars-VERSION-x64.zip` – portable Windows-Version
- `Arena-Wars-VERSION-x64.exe.blockmap` – Update-Datei
- `latest.yml` – Manifest für die automatische Aktualisierung
- `SHA256SUMS.txt` – Prüfsummen für alle vier Dateien

Nach der Erstinstallation prüft Arena Wars beim Start und anschließend alle sechs Stunden auf neue Versionen. Der Download und die Installation benötigen eine Bestätigung. Während einer aktiven Twitch-Arena-Sitzung wird nicht installiert, und Spielstände werden zuvor gesichert.

## Sicherheits- und Entwicklungsstatus

Die Builds werden im **privaten Quellrepository** automatisiert auf Windows getestet. Vor einer Veröffentlichung werden Installer, Versionsmanifest und Dateiprüfsummen abgeglichen. Die Windows-Dateien sind derzeit **nicht mit einem kommerziellen Codesigning-Zertifikat signiert**; Windows SmartScreen kann daher einen Hinweis anzeigen. Lade Dateien ausschließlich aus diesem Repository herunter.

**Wichtig:** Ein angelegtes Download-Repository ist noch keine Veröffentlichung. Solange die [Releases-Seite](https://github.com/goldovator-hue/arena-wars-releases/releases) leer ist, gibt es hier noch keinen Installer. Der Veröffentlichungslauf wird erst aktiviert, wenn seine GitHub-Actions-Berechtigungen korrekt eingerichtet und getestet sind.

---
© Goldovator Studios · Arena Wars
