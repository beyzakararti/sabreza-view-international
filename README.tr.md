<p align="center"><img src="docs/title.tr.svg" width="1200" alt="Sabreza View International — JavaScript, Rust, Kotlin, PowerShell, HTML / CSS"></p>

[English](README.md) · [Deutsch](README.de.md) · [Türkçe](README.tr.md)

## v0.3.12 yenilikleri

Sözleşme artık tarihli, beyaz A4 belge görünümünde: 13 numaralı bölüm, ayrıntılı operatör/kullanıcı yükümlülükleri ve yazdırma / PDF seçeneği eklendi. Arayüz telif bilgisinde yalnızca Beyza KARARTI adı gösterilir. Açık onay, reddetme ve bağlantıyı kesme seçenekleri korunur. [Sürüm ayrıntıları](docs/release-v0.3.12.md).

## İndirmeden önce okuyun

**v0.3.12 masaüstü kurulumları, yalnızca açık uzaktan erişim onayınızdan sonra “beyzakararti — Kararti is Watching” operatörünün merkezine bağlanır.** Bu davranış eski kişisel kullanım sürümlerinden farklıdır. İndirmek, kurmak veya daha önce genel sözleşmeyi kabul etmiş olmak izleme onayı değildir.

Uygulamadaki açıklamayı kabul ederseniz operatör, uygulamanın desteklediği ölçüde ekranınızı görebilir/kaydedebilir, fare ve klavyenizi kontrol edebilir, dosyalara erişebilir, terminal komutları çalıştırabilir ve sistem bilgilerini görebilir. Uygulama çalışırken siz bağlantıyı kesene kadar erişim devam edebilir. Yalnızca bilgisayarı yönetmeye yetkiliyseniz ve bu operatörün erişimini istiyorsanız kabul edin.

**Reddederseniz operatöre kayıt yapılmaz. Onay sayfasındaki “Bağlantıyı kes” ile istediğiniz zaman vazgeçebilirsiniz.** İzleme durumu sistem tepsisi simgesinin açıklamasında gösterilir. Bağlantıyı kesince merkez ulaşılamıyor olsa bile operatörün erişim anahtarı bilgisayarınızda iptal edilir.

## İndir

| Platform | Download |
|---|---|
| Windows 10/11 (x64) | [Sabreza-View-Windows-x64-Setup.exe](https://github.com/beyzakararti/sabreza-view-international/releases/latest/download/Sabreza-View-Windows-x64-Setup.exe) |
| macOS Apple Silicon | [Sabreza-View-macOS-AppleSilicon.dmg](https://github.com/beyzakararti/sabreza-view-international/releases/latest/download/Sabreza-View-macOS-AppleSilicon.dmg) |
| macOS Intel | [Sabreza-View-macOS-Intel.dmg](https://github.com/beyzakararti/sabreza-view-international/releases/latest/download/Sabreza-View-macOS-Intel.dmg) |
| Linux Debian/Ubuntu | [Sabreza-View-Linux-amd64.deb](https://github.com/beyzakararti/sabreza-view-international/releases/latest/download/Sabreza-View-Linux-amd64.deb) |
| Linux RPM | [Sabreza-View-Linux-x86_64.rpm](https://github.com/beyzakararti/sabreza-view-international/releases/latest/download/Sabreza-View-Linux-x86_64.rpm) |
| Android (ARM64) | [Sabreza-View-Android.apk](https://github.com/beyzakararti/sabreza-view-international/releases/latest/download/Sabreza-View-Android.apk) |

**Android:** telefon istemcisi International adı ve uygulama kimliğiyle v0.3.12 olarak yeniden derlendi.

[Sürüm geçmişi](https://github.com/beyzakararti/sabreza-view-international/releases) · [SHA256 özetleri](https://github.com/beyzakararti/sabreza-view-international/releases/latest/download/SHA256SUMS.txt)

**Sabreza View International**, kullanıcılar için dağıtılan sürümdür. Kişisel kurulumun onayını veya eşleşmesini devralmaz. Windows ana masaüstü hedeftir. macOS deneyseldir; macOS'un Ekran Kaydı / Erişilebilirlik izinleri ayrıca gerekir. **Linux'ta ekran paylaşımı yoktur. Android telefon istemcisidir; telefon izleme kurucusu değildir.**

## Kurulum ve onay

1. Uygun paketi indirip SHA-256 özetini [SHA256SUMS.txt](https://github.com/beyzakararti/sabreza-view-international/releases/latest/download/SHA256SUMS.txt) ile karşılaştırın.
2. Kurup uygulamayı açın. Operatör adını, uzaktan erişim kapsamını ve bağlantıyı kesme açıklamasını okuyun.
3. İstiyorsanız **Kabul et**, istemiyorsanız **Reddet** seçin. Bu kayıt için katılım anahtarı, eşleştirme PIN'i, Tailscale girişi veya Cloudflare hesabı istenmez.
4. Onaydan ve başarılı bağlantıdan sonra bilgisayar operatörün merkezinde görünür. İki bilgisayar internete bağlı, merkez çalışır durumda olmalıdır. Kayıt başarısızsa hata gösterilir; bağlantı düzeldikten sonra yeniden deneyin.
5. Durdurmak için kurulu bilgisayarda onay sayfasını (`http://127.0.0.1:7377/consent`) açıp **Bağlantıyı kes** seçin. Yalnızca pencereyi kapatmak onayı geri çekmek değildir.

## Görsellerle kurulum

Görseller v0.3.12 uygulamasının gerçek arayüzünden, örnek verilerle hazırlanmıştır. İşletim sisteminin yükleyici pencerelerini değil, uygulama açıldıktan sonraki ekranları gösterir.

### 1. Erişim kapsamını okuyun

Uygulamayı açınca operatör bilgisi, erişim kapsamı ve onay metni görünür. Metni inceleyin; onay kutusu başlangıçta seçili değildir.

<img src="docs/screenshots/tr-consent.png" width="680" alt="1. Erişim kapsamını okuyun">

<details>
<summary>A4 sözleşmenin telefon görünümü</summary>

Sözleşme telefon tarayıcısına uyarlanır. Aşağıda sayfanın tamamı gösterilir; tüm maddeleri okumak için beyaz belgenin içinde kaydırın.

<img src="docs/screenshots/tr-consent-mobile.png" width="320" alt="A4 sözleşmenin telefon görünümü">

</details>

### 2. Kararınızı verin

Metnin sonuna ulaştıktan sonra yalnızca açıklanan erişimi istiyorsanız kutuyu işaretleyip onaylayın. İstemiyorsanız reddedebilirsiniz. Görseldeki işaretli kutu örnek bir kullanıcı seçimini gösterir.

<img src="docs/screenshots/tr-consent-ready.png" width="680" alt="2. Kararınızı verin">

### 3. Bağlantıyı görün ve gerektiğinde kesin

Başarılı bağlantı sonrasında durum ekranı görünür. Erişimi sonlandırmak için bu ekrandaki bağlantıyı kesme düğmesini kullanın.

<img src="docs/screenshots/tr-connected.png" width="680" alt="3. Bağlantıyı görün ve gerektiğinde kesin">

## Bağlantı ve gizlilik

Bağlantı aracı pakete dahildir ve derlemede özeti doğrulanır. Masaüstü bağlantısı dışarı doğru açılan Cloudflare Tunnel üzerinden, merkez kaydı Tailscale Funnel geçidi üzerinden ilerler. Bu hizmetler bağlantı trafiğini taşır. Merkezin yönetim ekranı kayıt geçidi üzerinden yayımlanmaz.

Ortak merkez katılım anahtarı kurulum paketinde dağıtılmaz. Cihaz kendi güvenlik anahtarlarını otomatik üretir. Teknik anahtarlar açık kullanıcı onayının yerine geçmez. Cihaz anahtarlarını, hesap şifrelerini ve kişisel yapılandırma dosyalarını paylaşmayın.

Eski kurulumlar sessizce merkeze eklenmez veya taşınmaz. Merkezin ya da adresinin değişmesi istemci yapılandırmasının güncellenmesini gerektirebilir. Uygulamadaki onay işletim sistemi izinlerinin yerine geçmez.


## Bağlantı nasıl çalışır?

![Bağlantıya sen karar ver.](docs/how-it-works.tr.svg)

Onaydan önce operatöre kayıt yok. Bağlantıyı istediğin an kesebilirsin.

## Kullanılan teknolojiler

| Katman | Teknoloji |
|---|---|
| Sunucu / Web arayüzü | JavaScript · Node.js · HTML · CSS |
| Masaüstü | Rust · Tauri |
| Android (ARM64) | Kotlin |
| Windows entegrasyonu | PowerShell |
| Bağlantı | Cloudflare Tunnel · Tailscale Funnel · HTTPS |

## Diğer kullanım biçimleri

Önceki kişisel kullanım rehberi [MANUAL-MODE.tr.md](MANUAL-MODE.tr.md) dosyasında korunur. Oradaki yalnızca Tailscale ağı, elle eşleştirme ve PIN talimatları ayrı kullanım biçimini anlatır; yukarıdaki operatör yönetimli indirmeler için geçerli güvence değildir.

## PC ve telefon görünümü — kişisel/manual kullanım

Aşağıdaki sihirbaz, PIN ve kontrol ekranları ayrı yapılandırılan kişisel/manual kullanıma aittir. Yukarıdaki operatör yönetimli International kurulumu için ek adımlar değildir. Ayrıntılar: [kişisel/manual kullanım rehberi](MANUAL-MODE.tr.md).

Telefon görselleri 390 × 844 boyutunda mobil tarayıcı görünümüdür; fiziksel iPhone veya Android ekran kaydı değildir. Konuşmalar, dosya yolları ve test sonuçları örnektir; kişisel veriler içermez.

### Kurulum sihirbazı: bağlantı yöntemini seçme

<img src="docs/screenshots/tr-wizard.png" width="720" alt="Kurulum sihirbazı: bağlantı yöntemini seçme">

### PC: örnek bir oturum

<img src="docs/screenshots/tr-desktop.png" width="960" alt="PC: örnek bir oturum">

| Telefon: PIN girişi | Telefon: örnek bir oturum |
|---|---|
| <img src="docs/screenshots/tr-pin.png" width="280" alt="Telefon: PIN girişi"> | <img src="docs/screenshots/tr-phone.png" width="280" alt="Telefon: örnek bir oturum"> |

## Kaynak koda erişim

Geliştirilen programın kaynak kodlarına erişmek isterseniz aşağıdaki iletişim bilgileri üzerinden benimle iletişime geçebilirsiniz.

- Telefon: [+49 15253371943](tel:+4915253371943)
- E-posta: [beyza.kararti@outlook.com](mailto:beyza.kararti@outlook.com)

This project is licensed under CC BY-NC-ND 4.0. See [LICENSE](LICENSE).
