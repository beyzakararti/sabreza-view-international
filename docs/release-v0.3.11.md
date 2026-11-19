# v0.3.11 — Sabreza View International

## Türkçe

- Kurulum, uygulama penceresi, sistem tepsisi, Android başlığı ve web giriş ekranları **Sabreza View International** adını kullanır.
- Telefon eşleştirme/PIN ekranları ve PC başlangıç ekranlarında şu alt bilgi bulunur: **© 2026 Beyza KARARTI & Sabri DEMİR — Tüm hakları saklıdır. Kullanım lisans koşullarına tabidir.** Metin Türkçe, İngilizce ve Almanca sunulur.
- International kendi uygulama kimliğini, veri klasörünü ve 7377 yerel portunu kullanır. Personal ve deneysel kurulumlar değiştirilmez.

**Önceki sürümlerden geçiş:** Bu sürüm ayrı uygulama olarak kurulur. Önceki uygulamanın eşleştirmeleri, kayıtları ve erişim onayı otomatik aktarılmaz. Yeni uygulamada kurulum/onay akışını tamamlayın; eski uygulamanın erişimini kapatmak istiyorsanız onun içinden bağlantıyı kesin. PC onay sayfası: `http://127.0.0.1:7377/consent`.

## English

- Installers, application windows, the tray, Android labels and web entry screens use **Sabreza View International**.
- Phone pairing/PIN and PC entry screens display **© 2026 Beyza KARARTI & Sabri DEMİR — All rights reserved. Use is subject to the license terms.** Available in Turkish, English and German.
- International has its own application identity, data directory and local port 7377. Personal and experimental installations are separate.

**Upgrading:** this release installs as a separate application. Pairings, registrations and consent are not imported automatically. Complete setup/consent in the new application. If you want to revoke the older application's access, disconnect inside that application. PC consent page: `http://127.0.0.1:7377/consent`.

## Deutsch

- Installer, App-Fenster, Infobereich, Android-Beschriftungen und Web-Anmeldeseiten heißen **Sabreza View International**.
- Die Kopplungs-/PIN-Seiten auf dem Smartphone und die PC-Startseiten zeigen **© 2026 Beyza KARARTI & Sabri DEMİR — Alle Rechte vorbehalten. Die Nutzung unterliegt den Lizenzbedingungen.** Der Hinweis ist auf Türkisch, Englisch und Deutsch verfügbar.
- International besitzt eine eigene App-Identität, ein eigenes Datenverzeichnis und den lokalen Port 7377. Persönliche und experimentelle Installationen bleiben getrennt.

**Umstieg:** Diese Version wird als separate Anwendung installiert. Kopplungen, Registrierungen und Zustimmungen werden nicht automatisch übernommen. Einrichtung/Zustimmung in der neuen App abschließen. Um den Zugriff der bisherigen App zu widerrufen, dort die Verbindung trennen. PC-Zustimmungsseite: `http://127.0.0.1:7377/consent`.

## Validation and downloads

87 International tests and 91 personal tests passed locally. Identity checks verify that the native shell, Android and server use matching International configuration and do not write into another edition's data directory. Phone and desktop entry layouts were checked at 390 and 1440 pixels. Real-device execution on every supported OS was not performed.

All desktop packages and the Android client are rebuilt for this version. The Android download is the signed ARM64 (arm64-v8a) release APK; its application identity and display name were verified. The Windows installer metadata reports Sabreza View International 0.3.11. iPhone continues to use the web app. macOS remains experimental and requires system permissions; Linux does not support screen sharing. See the [installation and consent guide](https://github.com/beyzakararti/sabreza-view-international#readme) and verify downloads using `SHA256SUMS.txt`.

Source: `ef784ce189f19b1d1e011b8ff3c524df998282e6`. [Build](https://github.com/beyzakararti/sabreza-view-international-source/actions/runs/44479541070) (source repository access required).
