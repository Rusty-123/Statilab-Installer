<p align="center">
  <img src="bilder/statilab.png" alt="Statilab" width="520">
</p>

<p align="center"><b>Statikprogramm für ideale Statik in 2D und 3D</b><br>
Stabwerke, Gelenksysteme, Seile über Rollen und Starrkörper – auf Deutsch, nach ÖNORM.</p>

<p align="center">
  <a href="https://github.com/Rusty-123/Statilab-Installer/releases/latest"><b>⬇ Neueste Version herunterladen</b></a>
  &nbsp;·&nbsp;
  <a href="SETUP.md"><b>Setup-Anleitung</b></a>
</p>

---

## Was ist Statilab?

Statilab ist ein Statikprogramm für ideale Statik. Bauteile wie Träger, Stützen, Sparren, Seile oder Rollen werden gezeichnet, Lager und Lasten gesetzt – Statilab zeigt Bestimmtheit, Lagerkräfte und Schnittgrößen.

| Bereich | Umfang |
|---|---|
| **Systeme** | Träger, Rahmen, Fachwerke, Gerberträger, Dreigelenkrahmen, gekrümmte Bauteile, Seile über Rollen, Zylinder und Quader als Starrkörper – in 2D und 3D |
| **Bedienung** | Zeichnen wie im CAD (Fang, Raster, Ortho, Bemaßung), Gelenke und Federn am Anschluss, Rückgängig/Wiederholen, Befehlssuche mit Strg+K |
| **Lasten** | Einzelkraft, Einzelmoment, Trapezlast, Lastfälle, Überlagerung und Umhüllende |
| **Ergebnisse** | Bestimmtheit über den Rang der Gleichgewichtsmatrix, Lagerkräfte, N/V/M-Verläufe, Freikörperbild |
| **Ausgabe** | bearbeitbarer Bericht im A4-Format, Datenblatt je Bauteil, PDF |

> **Entwicklungsstand:** Die Oberfläche ist weit fortgeschritten, der Rechenkern ist noch im Aufbau. Bis er fertig ist, werden die mitgelieferten Beispiele mit hinterlegten Ergebnissen vorgerechnet. Neue Versionen meldet das Programm beim Start und installiert sie auf Wunsch direkt.

## Herunterladen

Alle Dateien liegen unter **[Releases](https://github.com/Rusty-123/Statilab-Installer/releases/latest)** (der Link führt immer zur neuesten Version).

| System | Datei |
|---|---|
| **Windows 10 / 11** | `Statilab-Setup.exe` – [direkt herunterladen](https://github.com/Rusty-123/Statilab-Installer/releases/latest/download/Statilab-Setup.exe) |
| Ubuntu 24.04+, Linux Mint 22, Debian 13 | `statilab_<Version>_all.deb` |
| andere Linux-Systeme (z. B. Ubuntu 22.04) | `Statilab-<Version>-x86_64.AppImage` |

## Installieren

**Windows:** `Statilab-Setup.exe` herunterladen, ausführen und dem Setup-Assistenten folgen. Keine Administratorrechte nötig.
👉 **Schritt für Schritt mit Bildern: [SETUP.md](SETUP.md)**

**Linux:**
- **.deb:** Datei doppelklicken (Softwareverwaltung) oder `sudo apt install ./statilab_<Version>_all.deb`
- **AppImage:** ausführbar machen (`chmod +x Statilab-*.AppImage`) und starten

## Entfernen

Windows: *Einstellungen → Apps → Installierte Apps → Statilab → Deinstallieren*. Eigene Modelle (`.stad`) bleiben erhalten.

---

<sub>Dieses Repository enthält nur die Installationsdateien. Statilab ist keine geprüfte Statiksoftware – Ergebnisse immer mit Handrechnung oder einem zweiten Programm kontrollieren.</sub>
