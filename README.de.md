<p align="center"><img src="docs/title.de.svg" width="1200" alt="Sabreza View International — JavaScript, Rust, Kotlin, PowerShell, HTML / CSS"></p>

[English](README.md) · [Deutsch](README.de.md) · [Türkçe](README.tr.md)

## Neu in v0.3.10

Blau-graue Farben, deutlicher Tastaturfokus, größere Touch-Schaltflächen und reduzierte Bewegung. Für die neue iPhone-Oberfläche muss der verbundene PC-Server aktualisiert werden. Diese internationalen Installer sind von persönlichen Installationen getrennt.

## Vor dem Download lesen

**Die Desktop-Installer v0.3.10 verbinden sich erst nach Ihrer ausdrücklichen Zustimmung zum Fernzugriff mit dem Betreiber „beyzakararti — Kararti is Watching“.** Das unterscheidet sich von älteren Downloads für den persönlichen Gebrauch. Download, Installation oder frühere allgemeine Vertragsannahme sind keine Zustimmung zur Überwachung.

Wenn Sie die Erklärung in der App akzeptieren, kann der Betreiber im Rahmen der unterstützten Funktionen Ihren Bildschirm sehen und aufzeichnen, Maus und Tastatur steuern, auf Dateien zugreifen, Terminalbefehle ausführen und Systeminformationen einsehen. Während die Anwendung läuft, kann der Zugriff bis zum Trennen bestehen bleiben. Stimmen Sie nur zu, wenn Sie den Computer verwalten dürfen und diesen Zugriff wünschen.

**Bei Ablehnung erfolgt keine Registrierung beim Betreiber. Über „Verbindung trennen“ auf der Zustimmungsseite können Sie jederzeit widerrufen.** Der Hinweis am Infobereich-Symbol zeigt die Überwachung an. Beim Trennen wird der Zugriffsschlüssel lokal widerrufen, auch wenn die Zentrale nicht erreichbar ist.

## Download

| Platform | Download |
|---|---|
| Windows 10/11 (x64) | [Sabreza-View-Windows-x64-Setup.exe](https://github.com/beyzakararti/sabreza-view-international/releases/latest/download/Sabreza-View-Windows-x64-Setup.exe) |
| macOS Apple Silicon | [Sabreza-View-macOS-AppleSilicon.dmg](https://github.com/beyzakararti/sabreza-view-international/releases/latest/download/Sabreza-View-macOS-AppleSilicon.dmg) |
| macOS Intel | [Sabreza-View-macOS-Intel.dmg](https://github.com/beyzakararti/sabreza-view-international/releases/latest/download/Sabreza-View-macOS-Intel.dmg) |
| Linux Debian/Ubuntu | [Sabreza-View-Linux-amd64.deb](https://github.com/beyzakararti/sabreza-view-international/releases/latest/download/Sabreza-View-Linux-amd64.deb) |
| Linux RPM | [Sabreza-View-Linux-x86_64.rpm](https://github.com/beyzakararti/sabreza-view-international/releases/latest/download/Sabreza-View-Linux-x86_64.rpm) |
| Android | [Sabreza-View-Android.apk](https://github.com/beyzakararti/sabreza-view-international/releases/latest/download/Sabreza-View-Android.apk) |

**Android:** Die APK bleibt der veröffentlichte, unveränderte und prüfsummenverifizierte Smartphone-Client aus v0.3.8; sie wurde nicht als v0.3.10 neu gebaut.

[Versionen](https://github.com/beyzakararti/sabreza-view-international/releases) · [SHA256-Prüfsummen](https://github.com/beyzakararti/sabreza-view-international/releases/latest/download/SHA256SUMS.txt)

**Sabreza View International** ist die Version für Endnutzer. Sie übernimmt weder Zustimmung noch Kopplung aus der persönlichen Installation. Windows ist das primäre Desktop-Ziel. macOS ist experimentell und benötigt zusätzliche macOS-Freigaben für Bildschirmaufnahme / Bedienungshilfen. **Linux unterstützt keine Bildschirmfreigabe. Android ist ein Smartphone-Client, kein Installer zur Überwachung des Telefons.**

## Installation und Zustimmung

1. Laden Sie das passende Paket herunter und vergleichen Sie SHA-256 mit [SHA256SUMS.txt](https://github.com/beyzakararti/sabreza-view-international/releases/latest/download/SHA256SUMS.txt).
2. Installieren und öffnen Sie die App. Lesen Sie Betreibername, Zugriffsrechte und die Anleitung zum Trennen.
3. Wählen Sie bewusst **Akzeptieren** oder **Ablehnen**. Für diese Registrierung benötigen Sie keinen Beitrittsschlüssel, keine Kopplungs-PIN und kein Tailscale- oder Cloudflare-Konto.
4. Nach Zustimmung und erfolgreicher Verbindung erscheint der Computer in der Zentrale. Beide Computer benötigen Internet; die Zentrale muss laufen. Bei einem Fehler versuchen Sie es erneut, sobald die Verbindung wieder funktioniert.
5. Öffnen Sie zum Beenden die Zustimmungsseite auf dem installierten Computer (`http://127.0.0.1:7376/consent`) und wählen Sie **Verbindung trennen**. Nur das Fenster zu schließen widerruft die Zustimmung nicht.

## Verbindung und Datenschutz

Das Verbindungsprogramm ist enthalten und wird beim Build anhand einer Prüfsumme kontrolliert. Desktop-Verkehr läuft über einen ausgehenden Cloudflare Tunnel; die Registrierung erreicht das Tailscale-Funnel-Gateway des Betreibers. Diese Dienste transportieren den Verbindungsverkehr. Die Verwaltungsoberfläche der Zentrale wird nicht über das Registrierungsgateway veröffentlicht.

Kein gemeinsamer geheimer Beitrittsschlüssel der Zentrale wird im Installer verteilt. Jedes Gerät erzeugt eigene Zugangsdaten automatisch. Technische Schlüssel ersetzen keine ausdrückliche Zustimmung. Geben Sie keine Geräteschlüssel, Kontopasswörter oder persönlichen Konfigurationsdateien weiter.

Ältere Installationen werden nicht heimlich registriert oder migriert. Eine neue Zentrale oder Adresse kann aktualisierte Client-Einstellungen erfordern. Die Zustimmung in der App ersetzt keine Betriebssystemberechtigungen.


## So funktioniert die Verbindung

![Du entscheidest über den Zugriff.](docs/how-it-works.de.svg)

Keine Betreiber-Registrierung ohne Zustimmung. Trennen ist jederzeit möglich.

## Verwendete Technologien

| Ebene | Technologie |
|---|---|
| Server / Weboberfläche | JavaScript · Node.js · HTML · CSS |
| Desktop | Rust · Tauri |
| Android | Kotlin |
| Windows-Integration | PowerShell |
| Verbindung | Cloudflare Tunnel · Tailscale Funnel · HTTPS |

## Andere Betriebsarten

Die bisherige Anleitung für persönliche Nutzung bleibt unter [MANUAL-MODE.de.md](MANUAL-MODE.de.md) erhalten. Ihre Angaben zu privatem Tailscale-Netz, manueller Kopplung und PIN beschreiben diesen separaten Modus und gelten nicht als Zusicherung für die oben angebotenen betreiberverwalteten Downloads.

## Zugang zum Quellcode

Wenn Sie Zugang zum Quellcode dieser Anwendung wünschen, kontaktieren Sie mich bitte über die folgenden Kontaktdaten.

- Telefon: [+49 15253371943](tel:+4915253371943)
- E-Mail: [beyza.kararti@outlook.com](mailto:beyza.kararti@outlook.com)

This project is licensed under CC BY-NC-ND 4.0. See [LICENSE](LICENSE).
