# v0.3.10 — Blue-gray interface and easier mobile controls

## Türkçe

- Turuncu vurgular maviye, sıcak tonlu yüzeyler griye dönüştürüldü. Bağlantılar koyu zeminde daha okunaklı.
- Dokunmatik ekranlarda temel düğmeler en az 44 piksel yüksekliğinde. Telefon form alanları en az 16 piksel yazı kullanıyor; sekmeler dar ekranda yatay kaydırılabiliyor.
- Klavye ile gezinirken odak daha belirgin; azaltılmış hareket tercihi destekleniyor.
- Arayüz dosyaları sunucuda güncellendiğinde tarayıcı bunların güncelliğini yeniden kontrol ediyor; stil bağlantısı sürümlendi.

**iPhone/personal:** GitHub'a push yapmak kurulu PC sunucusunu güncellemez. Personal sunucusu güncellendikten sonra telefon uygulamasını arka plana alıp açın veya tamamen kapatıp yeniden açın. Eşleştirmeyi silmeniz gerekmez. Bu sayfadaki international masaüstü kurulumları ayrı uygulama kimliği kullanır; personal kurulumunu güncellemek için bunları yüklemeyin.

## English

- Blue accents and gray surfaces replace the orange theme; links are easier to read on dark backgrounds.
- Main touch controls have a minimum height of 44 pixels, mobile form fields use at least 16-pixel text, and narrow tab bars can scroll horizontally.
- Clearer keyboard focus and support for reduced-motion preferences.
- Updated UI assets are revalidated by the browser; the stylesheet URL is versioned.

**iPhone/personal:** pushing source to GitHub does not update an installed PC server. After updating the personal server, reopen the phone app. Pairing does not need to be removed. These international desktop installers use a separate app identity and are not personal-installation updates.

## Deutsch

- Blaue Akzente und graue Flächen ersetzen die orange Oberfläche; Links sind auf dunklem Hintergrund besser lesbar.
- Wichtige Touch-Schaltflächen sind mindestens 44 Pixel hoch. Mobile Formularfelder verwenden mindestens 16 Pixel Schriftgröße; schmale Tab-Leisten können horizontal gescrollt werden.
- Deutlicher Tastaturfokus und Unterstützung für reduzierte Bewegung.
- Der Browser überprüft aktualisierte Oberflächendateien erneut; die Stylesheet-URL enthält eine Versionsnummer.

**iPhone/personal:** Ein GitHub-Push aktualisiert den installierten PC-Server nicht. Nach dessen Aktualisierung die Smartphone-App erneut öffnen. Die Kopplung muss nicht gelöscht werden. Diese internationalen Desktop-Installer haben eine eigene App-Identität und sind kein Update für die persönliche Installation.

## Installation and validation

Desktop registration still requires explicit consent in the app; declining prevents registration and disconnecting revokes access. No shared enrollment secret is bundled. Read the [installation and consent guide](https://github.com/beyzakararti/sabreza-view-international#readme). macOS builds remain experimental and require system permissions. Linux does not support screen sharing.

The Android APK is the unchanged v0.3.8 phone client, verified against the previously published checksum; it was not rebuilt as v0.3.10. iPhone uses the web app, with no new phone installer.

Local automated suites passed: 86 international-source tests, 91 personal tests and 88 center tests. The shared administrative interface was checked at 390-pixel and 1440-pixel viewport widths. The generated Linux package was inspected for the new theme, touch styles, versioned stylesheet, consent/disconnect handlers and verified connection helper. Real-device testing on every supported OS was not performed. Verify downloaded files against SHA256SUMS.txt.

Source: `a8e8eaac0faf908f32dac4dd98a9b093df4e1085`. [Desktop build](https://github.com/beyzakararti/sabreza-view-international-source/actions/runs/44404892671) (source repository access required).
