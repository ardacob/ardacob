<p align="center"><a href="#turkce">🇹🇷 Türkçe</a> · <a href="#english">🇬🇧 English</a></p>

<a id="turkce"></a>

# Merhaba, ben Arda 👋

Pratik uygulamalar, yaratıcı araçlar ve kişisel bulut sistemleri geliştiriyorum. Çalışmalarım Apple ekosistemini, platformlar arası bulut geliştirmeyi, kendi sunucumda çalışan sistemleri ve donanım denemelerini kapsıyor.

Bu projeleri **Codex** desteğiyle geliştiriyor; kaynak kodunu, arayüzleri, derlemeleri, testleri ve dokümantasyonu adım adım iyileştiriyorum.

## Projelerime genel bakış

| Proje | Odak | Mevcut durum |
| --- | --- | --- |
| 🌙 Lunoud | Özel geliştirme projesi | Private depo |
| 🔄 Convert | macOS ve iPhone için cihaz üzerinde dosya dönüştürme | Deneme sürümleri mevcut |
| 🎬 Kadrena | macOS, iPhone ve iPad için video düzenleme | Geliştirme derlemeleri |
| 🎨 LumaStudio | macOS için katmanlı görsel düzenleme | Geliştirme derlemeleri |
| 🎵 WAMP | Winamp'tan esinlenen yerel müzik oynatıcı | macOS derlemesi ve web sürümü |
| 🐲 HyperDrive · Beast Core | Windows için dahili ve harici depolama hız testi | 1 GiB test; Windows geliştirme sürümü |
| ☁️ Mac mini Personal Cloud | Kendi sunucumda depolama ve uzaktan dosya erişimi | Herkese açık kurulum rehberi ve betikler |
| 💾 Harici macOS ve NVMe araştırması | Depolama, disk kutuları ve Mac uyumluluğu | Donanım araştırması |

## 🌙 Lunoud

Lunoud, özel olarak geliştirilen bir projedir.

## 🔄 Convert — çevrimdışı dosya dönüştürme

[Convert](https://github.com/ardacob/convert-offline), **Swift ve SwiftUI** ile geliştirdiğim bir **macOS ve iPhone** dosya dönüştürme uygulamasıdır. Dönüştürme, dosyalar bir dönüştürme sunucusuna yüklenmeden cihaz üzerinde yapılır.

### Özellikler

- Dosya seçme, hedef biçim önerileri, önizleme ve sonuçları kaydetme/paylaşma.
- Görsel ve PDF dönüştürme.
- İşletim sisteminin desteklediği çerçeveler ve kodeklerle belirli ses/video dönüşümleri.
- iPhone'da Fotoğraflar veya Dosyalar üzerinden **HEIC → JPG** dahil toplu görsel dönüştürme.
- Birden fazla dönüştürülmüş görseli birlikte paylaşma.
- Saydamlığı ayarlanabilen Açık, Koyu ve Liquid Glass temaları.
- Tema tercihleri ve uygulama bilgileri için ayrı bir Ayarlar ekranı.

### Mevcut durum

macOS ve iPhone için deneme sürümleri ve kaynak kodu mevcut. Başlangıçtaki daha geniş platform fikri, yerel Apple uygulamalarına dönüştü.

Biçim kapsamı, giriş dosyasına ve sistem kodeklerine bağlıdır. MP3 çıktısı, birçok ofis/özel dosya biçimi ve Windows/Android uygulamaları mevcut yayımlanmış sürüme dahil değildir.

[Kaynak kodu](https://github.com/ardacob/convert-offline) · [Sürümler](https://github.com/ardacob/convert-offline/releases) · [Biçim kapsamı](https://github.com/ardacob/convert-offline/blob/main/FORMAT_SCOPE.md)

## 🎬 [Kadrena](https://github.com/ardacob/kadrena) — video düzenleme

**Kadrena**, CapCut ve Clipchamp gibi kolay kullanılan zaman çizelgesi tabanlı editörlerden esinlenerek geliştirdiğim **macOS, iPhone ve iPad** video düzenleme projesidir.

Amacım günlük düzenlemeleri kolaylaştırmak: yerel video ve sesleri içe aktarmak, klipleri sıralamak, kesmek, müzik eklemek ve sonucu dışa aktarmak.

### Geliştirilen özellikler

- Yerel dosyalardan video ve ses içe aktarma.
- Zaman çizelgesinde düzenleme, klip taşıma, kırpma ve bölme.
- Müzik/ses izleri ve soldurma kontrolleri.
- En-boy oranı seçimi.
- Tam ekran önizleme.
- Proje kaydetme.
- **MP4, MOV ve M4V** dışa aktarma.
- iPhone ve iPad için dokunmatik kullanıma uygun zaman çizelgesi.

### Mevcut durum

macOS ve mobil geliştirme derlemeleri hazırlandı. iPhone sürümü fiziksel bir cihaza kurulup başlatıldı.

Daha geniş biçim desteği bir geliştirme hedefi olmaya devam ediyor; mevcut proje her video biçiminde çıktı verme sözü sunmuyor.

## 🎨 [LumaStudio](https://github.com/ardacob/lumastudio) — katmanlı görsel düzenleme

**LumaStudio**, Photoshop'un katmanlı çalışma mantığından ve yumuşak, Apple tarzı bir arayüzden esinlenerek geliştirdiğim **macOS** görsel düzenleyicisidir.

### Geliştirilen özellikler

- Boş tuval oluşturma.
- Görsel, metin, şekil ve fırça katmanları ekleme.
- Katmanları taşıma, sıralama, gizleme, çoğaltma ve silme.
- Katman opaklığını ayarlama.
- Düzenlenebilir **`.luma` projelerini** kaydetme ve yeniden açma.
- Birleştirilmiş görseli dışa aktarma.
- Sistem, Açık ve Koyu görünüm ayarları.
- Kalıcı varsayılan çıktı biçimi ve kalite tercihleri.

### Mevcut durum

**Apple Silicon ve Intel Mac'ler** için geliştirme derlemeleri hazırlandı. Geliştirme sırasında katmanları kaydetme/yeniden açma ve birleştirilmiş görseli dışa aktarma doğrulandı.

Tam Photoshop uyumluluğu henüz mevcut özellikler arasında değil. Maskeler, gelişmiş seçim araçları ve katmanlı PSD alışverişi gelecekteki çalışmalar arasında; mevcut PSD çıktısı düzleştirilmiş görsel üretir.

## 🎵 [WAMP](https://github.com/ardacob/wamp) — klasik müzik oynatıcı

**WAMP**, hem macOS uygulaması hem de tarayıcı sürümü bulunan, **Winamp'tan esinlenen müzik oynatıcım**.

### Geliştirilen özellikler

- Klasik koyu metalik arayüz ve yeşil ekran.
- Çalma listesi ve tanıdık oynatma kontrolleri.
- Yerel ses dosyası seçme.
- Web çalma listesine sürükleyip bırakma.
- Kişisel ses dosyalarını bir sunucuya yüklemeden oynatma.
- Web uygulamasının yanında çevrimdışı HTML sürümü.

### Mevcut durum

macOS derlemesi **Apple Silicon ve Intel Mac'ler** için hazırlandı; dosya seçme ve oynatma macOS'ta test edildi. Web sürümü de mevcut.

[Web oynatıcıyı aç](https://wamp-klasik-mp3-calar.sykenix.chatgpt.site)

## 🐲 [HyperDrive · Beast Core](https://github.com/ardacob/hyperdrive-beast-core) — depolama hız testi

**HyperDrive**, dahili disklerin, USB belleklerin ve harici disklerin sıralı okuma/yazma hızını ölçen **Windows** uygulamamdır. **C# ve WinForms** ile geliştirildi; CS2 Hyper Beast estetiğinden esinlenen özgün yaratık teması, nar çiçeği ve turkuaz vurgular kullanır.

### Mevcut özellikler

- Seçilen sürücüde **1 GiB** geçici veriyle sıralı yazma ve okuma testi.
- Ayrı **MB/sn** sonuçları, ilerleme göstergesi ve testi durdurma.
- Windows dosya önbelleğini atlayan erişim ve işlem sonunda geçici dosyanın temizlenmesi.
- C: üzerinde yazılabilir test klasörü seçimi; normal test için yönetici izni gerektirmez.
- Bahnschrift font ve özel çizilen, tamamen yuvarlak uçlu düğmeler.

### Mevcut durum

İlk Windows geliştirme sürümü **v0.1.0** hazır. Geliştirme sırasında C: üzerinde 1 GiB okuma/yazma ve dosya temizliği doğrulandı; düğmelerin hover, basılı ve devre dışı çizimleri kontrol edildi.

Bu sürüm sıralı dosya aktarımını ölçer; SMART sağlık kontrolü, rastgele I/O ve gerçek kapasite doğrulaması içermez.

[Kaynak kodu](https://github.com/ardacob/hyperdrive-beast-core) · [Windows indir](https://github.com/ardacob/hyperdrive-beast-core/releases/tag/v0.1.0) · [Değişiklikler](https://github.com/ardacob/hyperdrive-beast-core/blob/main/CHANGELOG.md)

## ☁️ Mac mini Personal Cloud — kendi sunucumda depolama

[Mac mini Personal Cloud](https://github.com/ardacob/mac-mini-personal-cloud), aşağıdaki bileşenlerle kurulmuş gerçek bir kişisel bulut ve medya depolama sistemini belgeler:

**Apple Silicon Mac mini + harici NVMe SSD + Docker + File Browser + Tailscale + NAStool**

### Projenin kapsamı

- iPhone/iPad'den uzaktan dosya erişimi ve yükleme.
- Router portlarını genel internete açmadan Tailscale ile erişim.
- Tek fiziksel SSD'yi dosya yönetimi ve medya servisleri arasında paylaşma.
- macOS'ta NTFS salt okunur davranışını teşhis etme ve APFS'e geçiş.
- Siyah, kısmi veya hatalı HEIC önizlemelerini araştırma.
- FFmpeg ve macOS `sips` dönüştürme sonuçlarını karşılaştırma.
- Önizleme/önbellek sorunlarını giderme.
- NAStool için DOM tabanlı Türkçe arayüz yaklaşımı.
- Yedekleme, geri dönüş ve sorun giderme dokümantasyonu.

### Hazırlanan kaynaklar

Depoda Docker yapılandırma örnekleri, kurulum rehberleri; depolama teşhisi, klasör oluşturma, HEIC önizleme yenileme, yedekleme ve servis doğrulama için yardımcı betikler bulunur.

NAStool'un kaynak projesi arşivlenmiştir; rehber bu bileşeni eski bir yazılım olarak ele alır.

[Depo ve Türkçe rehber](https://github.com/ardacob/mac-mini-personal-cloud) · [İngilizce rehber](https://github.com/ardacob/mac-mini-personal-cloud/blob/main/README_EN.md)

## 💾 Harici macOS ve NVMe — donanım araştırması

Uygulamaların yanında **Mac mini** için pratik depolama kurulumlarını araştırıyorum. Buna **Crucial T500 NVMe SSD**, harici disk kutuları ve harici diskten macOS başlatma olasılığı da dahil.

### Araştırılan konular

- USB 3.1 Gen 2 ile USB4/Thunderbolt disk kutusu seçenekleri.
- NVMe boyut ve arayüz uyumluluğu.
- APFS biçimlendirme ve depolama düzeni.
- Disk kutusu soğutması ve fiyat/performans karşılaştırmaları.
- Uyku/uyanma davranışı; dosya depolama uyumluluğu ile güvenilir macOS başlangıç diski kullanımının farkı.

### Mevcut durum

Bu, bir donanım araştırması çalışmasıdır. Bir disk kutusunun kağıt üzerindeki uyumluluğunu, kararlı bir harici macOS kurulumunun kanıtı olarak kabul etmiyorum.

## Teknolojiler ve ilgi alanları

- 🪟 **Windows uygulamaları:** C#, WinForms, depolama performansı, özel çizilen arayüzler
- 🍎 **Apple uygulamaları:** Swift, SwiftUI, macOS, iOS, Apple Silicon
- ☁️ **Bulut ve kendi sunucumda barındırma:** Docker, Docker Compose, File Browser, Tailscale, uzaktan erişim mimarisi
- 🎞️ **Dosyalar ve medya:** HEIC, PDF, FFmpeg, görsel katmanları, ses oynatma, video zaman çizelgeleri
- 🐧 **Sistemler:** Linux derleme ortamları, Android/LineageOS, recovery imajları
- 🔧 **Donanım:** NVMe depolama, APFS, homelab, sorun giderme

## Çalışma biçimim

Kaynak değişiklikleri, arayüz iyileştirmeleri, derleme sorunlarını giderme, doğrulama ve proje dokümantasyonunda **Codex** ile birlikte çalışıyorum.

Amacım günlük ihtiyaçları kullanışlı araçlara dönüştürmek, proje durumlarını doğru aktarmak ve süreçte öğrendiklerimi kaydetmek.

Herkese açık depoların ve demoların bağlantıları ilgili bölümlerde bulunuyor. Diğer projeler üzerinde geliştirme ve paketleme çalışmaları sürüyor.

[English ↓](#english)

---

<a id="english"></a>

# Hi, I'm Arda 👋

I build practical apps, creative tools, and personal cloud systems. My work spans the Apple ecosystem, cross-platform cloud development, self-hosting, and hardware experiments.

I develop these projects with help from **Codex**, iterating on source code, interfaces, builds, testing, and documentation.

## My projects at a glance

| Project | Focus | Current stage |
| --- | --- | --- |
| 🌙 Lunoud | Private development project | Private repository |
| 🔄 Convert | On-device file conversion for macOS and iPhone | Trial versions available |
| 🎬 Kadrena | Video editing for macOS, iPhone, and iPad | Development builds |
| 🎨 LumaStudio | Layer-based image editing for macOS | Development builds |
| 🎵 WAMP | Winamp-inspired local music player | macOS build and web version |
| 🐲 HyperDrive · Beast Core | Windows internal/external storage benchmark | 1 GiB test; Windows development build |
| ☁️ Mac mini Personal Cloud | Self-hosted storage and remote file access | Public setup guide and scripts |
| 💾 External macOS & NVMe research | Storage, enclosures, and Mac compatibility | Hardware research |

## 🌙 Lunoud

Lunoud is a private development project.

## 🔄 Convert — offline file conversion

[Convert](https://github.com/ardacob/convert-offline) is a **macOS and iPhone** file converter built with **Swift and SwiftUI**. Conversion happens on the device, without uploading files to a conversion server.

### Features

- File selection, suggested target formats, previews, and saving/sharing results.
- Image and PDF conversion.
- Selected audio/video conversions using the operating system's supported frameworks and codecs.
- Batch image conversion on iPhone from Photos or Files, including **HEIC → JPG**.
- Sharing multiple converted images together.
- Light, dark, and Liquid Glass themes, with adjustable transparency.
- A separate settings screen for theme preferences and app information.

### Current status

Trial versions and source code are available for macOS and iPhone. The original wider platform idea has evolved into native Apple applications.

Format coverage depends on the input and system codecs. MP3 output, many office/specialized formats, and Windows/Android applications are not included in the current published version.

[Source code](https://github.com/ardacob/convert-offline) · [Releases](https://github.com/ardacob/convert-offline/releases) · [Format scope](https://github.com/ardacob/convert-offline/blob/main/FORMAT_SCOPE.md)

## 🎬 [Kadrena](https://github.com/ardacob/kadrena) — video editing

**Kadrena** is my video editing project for **macOS, iPhone, and iPad**, inspired by approachable timeline-based editors such as CapCut and Clipchamp.

The goal is to make everyday editing straightforward: bring in local video and audio, arrange clips, cut them, add music, and export the result.

### Features developed

- Video and audio import from local files.
- Timeline editing, clip movement, trimming, and splitting.
- Music/audio tracks and fade controls.
- Aspect-ratio selection.
- Full-screen previews.
- Project saving.
- **MP4, MOV, and M4V** export.
- A touch-oriented timeline for iPhone and iPad.

### Current status

macOS and mobile development builds have been prepared. The iPhone version was installed and launched on a physical device.

Broader format support remains a development goal; the current project does not promise export to every video format.

## 🎨 [LumaStudio](https://github.com/ardacob/lumastudio) — layer-based image editing

**LumaStudio** is my **macOS** image editor, inspired by Photoshop's layered workflow and a soft, Apple-style interface.

### Features developed

- Creating a blank canvas.
- Adding image, text, shape, and brush layers.
- Moving, reordering, hiding, duplicating, and deleting layers.
- Adjusting layer opacity.
- Saving and reopening editable **`.luma` projects**.
- Exporting the combined image.
- System, light, and dark appearance settings.
- Persistent default export format and quality preferences.

### Current status

Development builds have been prepared for **Apple Silicon and Intel Macs**. Layer save/reopen and combined-image export were verified during development.

Full Photoshop compatibility is still outside the current feature set. Masks, advanced selection tools, and layered PSD interchange remain future work; current PSD export produces a flattened image.

## 🎵 [WAMP](https://github.com/ardacob/wamp) — classic music player

**WAMP** is my **Winamp-inspired music player**, with both a macOS application and a browser version.

### Features developed

- A classic dark metallic interface and green display.
- A playlist and familiar playback controls.
- Local audio file selection.
- Drag-and-drop files into the web playlist.
- Playback without uploading personal audio files to a server.
- An offline HTML version alongside the web application.

### Current status

The macOS build was prepared for **Apple Silicon and Intel Macs**, and file selection/playback were tested on macOS. A web version is also available.

[Open the web player](https://wamp-klasik-mp3-calar.sykenix.chatgpt.site)

## 🐲 [HyperDrive · Beast Core](https://github.com/ardacob/hyperdrive-beast-core) — storage benchmark

**HyperDrive** is my **Windows** app for measuring sequential read/write speeds of internal drives, USB flash drives, and external storage. Built with **C# and WinForms**, it uses an original creature theme inspired by CS2 Hyper Beast, with coral red and turquoise accents.

### Current features

- A fixed **1 GiB** temporary-file sequential write/read test on the selected drive.
- Separate decimal **MB/s** results, progress, and cancellation.
- Windows file-cache bypass and temporary-file cleanup after the test.
- Writable test-directory selection on C:, allowing a standard test without administrator rights.
- Bahnschrift typography and fully rounded custom buttons.

### Current status

The first Windows development build, **v0.1.0**, is ready. A 1 GiB C: write/read test and file cleanup were verified during development; hover, pressed, and disabled button rendering was checked.

This version measures sequential file throughput. It does not include SMART health checks, random I/O, or genuine-capacity validation.

[Source code](https://github.com/ardacob/hyperdrive-beast-core) · [Windows download](https://github.com/ardacob/hyperdrive-beast-core/releases/tag/v0.1.0) · [Changelog](https://github.com/ardacob/hyperdrive-beast-core/blob/main/CHANGELOG.md)

## ☁️ Mac mini Personal Cloud — self-hosted storage

[Mac mini Personal Cloud](https://github.com/ardacob/mac-mini-personal-cloud) documents a real personal cloud and media-storage setup using:

**Apple Silicon Mac mini + external NVMe SSD + Docker + File Browser + Tailscale + NAStool**

### What the project covers

- Remote file access and uploads from iPhone/iPad.
- Tailscale access without opening router ports to the public internet.
- Sharing one physical SSD between file management and media services.
- Diagnosing macOS NTFS read-only behavior and moving to APFS.
- Investigating black, partial, or incorrect HEIC previews.
- Comparing FFmpeg and macOS `sips` conversion results.
- Preview/cache troubleshooting.
- A DOM-based Turkish interface approach for NAStool.
- Backup, rollback, and troubleshooting documentation.

### Practical deliverables

The repository includes Docker configuration examples, setup guides, and helper scripts for storage diagnosis, folder creation, HEIC preview refresh, backups, and stack verification.

NAStool is an archived upstream project, so the guide records it as a legacy component.

[Repository & Turkish guide](https://github.com/ardacob/mac-mini-personal-cloud) · [English guide](https://github.com/ardacob/mac-mini-personal-cloud/blob/main/README_EN.md)

## 💾 External macOS & NVMe — hardware research

Alongside the apps, I research practical storage setups for the **Mac mini**, including a **Crucial T500 NVMe SSD**, external enclosures, and possible external macOS boot use.

### Topics explored

- USB 3.1 Gen 2 versus USB4/Thunderbolt enclosure options.
- NVMe size and interface compatibility.
- APFS formatting and storage organization.
- Enclosure cooling and price/performance comparisons.
- Sleep/wake behavior and the distinction between file-storage compatibility and reliable macOS boot use.

### Current status

This is a hardware research track. A particular enclosure's compatibility on paper is not treated as proof of a stable external macOS installation.

## Technologies & interests

- 🪟 **Windows apps:** C#, WinForms, storage performance, custom-drawn interfaces
- 🍎 **Apple apps:** Swift, SwiftUI, macOS, iOS, Apple Silicon
- ☁️ **Cloud & self-hosting:** Docker, Docker Compose, File Browser, Tailscale, remote-access architecture
- 🎞️ **Files & media:** HEIC, PDF, FFmpeg, image layers, audio playback, video timelines
- 🐧 **Systems:** Linux build environments, Android/LineageOS, recovery images
- 🔧 **Hardware:** NVMe storage, APFS, homelab, troubleshooting

## How I work

I use **Codex** as a development collaborator for source changes, interface iteration, build troubleshooting, verification, and project documentation.

My aim is to turn everyday needs into useful tools, keep project status honest, and record the practical lessons along the way.

Public repositories and demos are linked where available. Other projects are still being developed and packaged.


[Türkçe ↑](#turkce)
