# Installieren Sie unter Microsoft Windows ™

Laden Sie das neueste ** Windows-Archiv ** von [ QOwnNotes Releases auf GitHub ](https://github.com/pbek/QOwnNotes/releases) herunter und entpacken Sie es an einen beliebigen Ort. Es ist keine Installation erforderlich!

::: Warnung Wenn Sie den **automatischen Updater** verwenden möchten, stellen Sie sicher, dass Sie ihn an einen Ort entpacken, auf den Ihr Benutzerkonto Schreibzugriff hat. Standardmäßig hat Ihr Benutzerkonto höchstwahrscheinlich ** keinen Schreibzugriff ** auf Orte wie ` C: \ Programme (x86) ` oder ` C: \ Programme `. :::

You can then directly run `QOwnNotes.exe` from your `QOwnNotes` folder, no installation is required.

### Portabler Modus

Verwenden Sie ` QOwnNotesPortable.bat `, um QOwnNotes im ** portablen Modus ** auszuführen, in dem alles (einschließlich Ihrer Notizen) nur in Ihrem ` QOwnNotes ` -Ordner gespeichert wird.

::: Tip Sie benötigen den tragbaren Knoten nicht, wenn Sie nur keine Administratorrechte für Ihren Computer haben. QOwnNotes braucht nicht installiert werden! :::

## Windows XP

Qt hat die Unterstützung für Windows XP mit Version 5.8 eingestellt, QOwnNotes wurde jetzt auch mit Qt 5.7 erstellt, damit Windows XP-Benutzer es weiterhin verwenden können.

Obwohl Sie den neuesten Master-Build von [ AppVeyor ](https://ci.appveyor.com/project/pbek/qownnotes/history) selbst suchen müssen, wählen Sie die * Qt 5.7-Umgebung * und laden Sie das * Artefakt * herunter.

::: Tipp Info Der automatische Update-Mechanismus funktioniert nicht mit dem AppVeyor-Build für Windows XP! Sie müssen neue Versionen selbst herunterladen. :::

## Chocolatey

Unter [ Chocolatey ](https://chocolatey.org/packages/qownnotes/) gibt es ein von der Community gepflegtes Paket mit QOwnNotes.

Sie können es installieren mit:

```shell
choco install qownnotes
```