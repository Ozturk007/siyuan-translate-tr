<p align="center">
<img alt="SiYuan" src="https://b3log.org/images/brand/siyuan-128.png">
<br>
<em>Refactor your thinking</em>
<br><br>
<a title="Build Status" target="_blank" href="https://github.com/siyuan-note/siyuan/actions/workflows/ci.yml"><img src="https://img.shields.io/github/actions/workflow/status/siyuan-note/siyuan/cd.yml?style=flat-square"></a>
<a title="Releases" target="_blank" href="https://github.com/siyuan-note/siyuan/releases"><img src="https://img.shields.io/github/release/siyuan-note/siyuan.svg?style=flat-square&color=9CF"></a>
<a title="Downloads" target="_blank" href="https://github.com/siyuan-note/siyuan/releases"><img src="https://img.shields.io/github/downloads/siyuan-note/siyuan/total.svg?style=flat-square&color=blueviolet"></a>
<br>
<a title="Docker Pulls" target="_blank" href="https://hub.docker.com/r/b3log/siyuan"><img src="https://img.shields.io/docker/pulls/b3log/siyuan.svg?style=flat-square&color=green"></a>
<a title="Docker Image Size" target="_blank" href="https://hub.docker.com/r/b3log/siyuan"><img src="https://img.shields.io/docker/image-size/b3log/siyuan.svg?style=flat-square&color=ff96b4"></a>
<a title="Hits" target="_blank" href="https://github.com/siyuan-note/siyuan"><img src="https://hits.b3log.org/siyuan-note/siyuan.svg"></a>
<br>
<a title="AGPLv3" target="_blank" href="https://www.gnu.org/licenses/agpl-3.0.txt"><img src="http://img.shields.io/badge/license-AGPLv3-orange.svg?style=flat-square"></a>
<a title="Code Size" target="_blank" href="https://github.com/siyuan-note/siyuan"><img src="https://img.shields.io/github/languages/code-size/siyuan-note/siyuan.svg?style=flat-square&color=yellow"></a>
<a title="GitHub Pull Requests" target="_blank" href="https://github.com/siyuan-note/siyuan/pulls"><img src="https://img.shields.io/github/issues-pr-closed/siyuan-note/siyuan.svg?style=flat-square&color=FF9966"></a>
<br>
<a title="GitHub Commits" target="_blank" href="https://github.com/siyuan-note/siyuan/commits/master"><img src="https://img.shields.io/github/commit-activity/m/siyuan-note/siyuan.svg?style=flat-square"></a>
<a title="Last Commit" target="_blank" href="https://github.com/siyuan-note/siyuan/commits/master"><img src="https://img.shields.io/github/last-commit/siyuan-note/siyuan.svg?style=flat-square&color=FF9900"></a>
<br><br>
<a title="Twitter" target="_blank" href="https://twitter.com/b3logos"><img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/b3logos?label=Follow&style=social"></a>
<a title="Discord" target="_blank" href="https://discord.gg/dmMbCqVX7G"><img alt="Chat on Discord" src="https://img.shields.io/discord/808152298789666826?label=Discord&logo=Discord&style=social"></a>
<br><br>
<a href="https://trendshift.io/repositories/3949" target="_blank"><img src="https://trendshift.io/api/badge/repositories/3949" alt="siyuan-note%2Fsiyuan | Trendshift" style="width: 250px; height: 55px;" width="250" height="55"/></a>
</p>

<p align="center">
<a href="README_zh_CN.md">中文</a> | <a href="README_ja_JP.md">日本語</a>
</p>

---

## İçindekiler

* [💡 Giriş](#-introduction)
* [🔮 Özellikler](#-features)
* [🏗️ Mimarî ve Ekosistem](#-architecture-and-ecosystem)
* [🌟 Yıldız Geçmişi](#-star-history)
* [🗺️ Yol Haritası](#️-roadmap)
* [🚀 Kurulum ve İndirme](#-download-setup)
  * [Uygulama Marketi](#app-market)
  * [Kurulum Paketi](#installation-package)
  * [Docker ile Barındırma](#docker-hosting)
  * [Unraid ile Barındırma](#unraid-hosting)
  * [İçeriden Önizleme](#insider-preview)
* [🏘️ Topluluk](#️-community)
* [🛠️ Geliştirme Rehberi](#️-development-guide)
* [❓ Sıkça Sorulan Sorular](#-faq)
  * [SiYuan verileri nasıl saklar?](#how-does-siyuan-store-data)
  * [Üçüncü taraf senkronizasyon diskleriyle veri senkronizasyonu destekliyor mu?](#does-it-support-data-synchronization-through-a-third-party-sync-disk)
  * [SiYuan açık kaynak mı?](#is-siyuan-open-source)
  * [Yeni sürüme nasıl geçerim?](#how-to-upgrade-to-a-new-version)
  * [Bazı blokların (örneğin liste öğelerindeki paragraf blokları) blok simgesi bulunamazsa ne olur?](#what-if-some-blocks-such-as-paragraph-blocks-in-list-items-cannot-find-the-block-icon)
  * [Veri deposu anahtarı kaybolursa ne yapmalıyım?](#what-should-i-do-if-the-data-repo-key-is-lost)
  * [Ücret ödemem gerekiyor mu?](#do-i-need-to-pay-for-it)
* [🙏 Teşekkürler](#-acknowledgement)
  * [Katkıda Bulunanlar](#contributors)

---

## 💡 Giriş

SiYuan, gizlilik odaklı bir kişisel bilgi yönetim sistemidir. Blok düzeyinde referans ve Markdown WYSIWYG destekler.

Daha fazlası için [SiYuan İngilizce Forumu](https://liuyun.io)'nu ziyaret edebilirsiniz.

![feature0.png](https://b3logfile.com/file/2024/01/feature0-1orBRlI.png)

![feature51.png](https://b3logfile.com/file/2024/02/feature5-1-uYYjAqy.png)

## 🔮 Özellikler

Çoğu özellik ücretsizdir, ticari kullanım dahil.

* İçerik bloğu
  * Blok düzeyinde referans ve çift yönlü bağlantılar
  * Özel özellikler
  * SQL sorgu gömme
  * `siyuan://` protokolü
* Editör
  * Blok tabanlı
  * Markdown WYSIWYG
  * Liste ana hat
  * Blok yakınlaştırma
  * Milyon kelimelik büyük belge düzenleme
  * Matematik formülleri, grafikler, akış şemaları, DIYagramlar, zaman çizelgeleri, notalar vb.
  * Web sayfası kırpma
  * PDF bağlantısı ve açıklama
* Dışa Aktarma
  * Blok referansı ve gömme
  * Standart Markdown ile varlıklar
  * PDF, Word ve HTML
  * WeChat MP, Zhihu ve Yuque için kopyalama
* Veritabanı
  * Tablo görünümü
* Aralıklı tekrar flaş kartları
* OpenAI API ile AI yazım ve sohbet
* Tesseract OCR
* Çoklu sekme, sürükle ve bırak ile ekran bölme
* Şablon parçacıkları
* JavaScript/CSS parçacıkları
* Android/iOS/HarmonyOS uygulaması
* Docker dağıtımı
* [API](https://github.com/siyuan-note/siyuan/blob/master/API.md)
* Topluluk marketi

Bazı özellikler yalnızca ücretli üyeler içindir. Detaylar için [Fiyatlandırma](https://b3log.org/siyuan/en/pricing.html) sayfasına bakın.

## 🏗️ Mimarî ve Ekosistem

![SiYuan Arch](https://b3logfile.com/file/2023/05/SiYuan_Arch-Sgu8vXT.png "SiYuan Arch")

| Proje                                                  | Açıklama              | Forklar                                                                           | Yıldızlar                                                                            | 
|----------------------------------------------------------|-----------------------|---------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|
| [lute](https://github.com/88250/lute)                    | Editör motoru         | ![GitHub forks](https://img.shields.io/github/forks/88250/lute)                 | ![GitHub Repo stars](https://img.shields.io/github/stars/88250/lute)                 |
| [chrome](https://github.com/siyuan-note/siyuan-chrome)   | Chrome/Edge uzantısı  | ![GitHub forks](https://img.shields.io/github/forks/siyuan-note/siyuan-chrome)  | ![GitHub Repo stars](https://img.shields.io/github/stars/siyuan-note/siyuan-chrome)  |
| [bazaar](https://github.com/siyuan-note/bazaar)          | Topluluk marketi      | ![GitHub forks](https://img.shields.io/github/forks/siyuan-note/bazaar)         | ![GitHub Repo stars](https://img.shields.io/github/stars/siyuan-note/bazaar)         |
| [dejavu](https://github.com/siyuan-note/dejavu)          | Veri deposu           | ![GitHub forks](https://img.shields.io/github/forks/siyuan-note/dejavu)         | ![GitHub Repo stars](https://img.shields.io/github/stars/siyuan-note/dejavu)         |
| [petal](https://github.com/siyuan-note/petal)            | Eklenti API'si        | ![GitHub forks](https://img.shields.io/github/forks/siyuan-note/petal)          | ![GitHub Repo stars](https://img.shields.io/github/stars/siyuan-note/petal)          |
| [android](https://github.com/siyuan-note/siyuan-android) | Android uygulaması    | ![GitHub forks](https://img.shields.io/github/forks/siyuan-note/siyuan-android) | ![GitHub Repo stars](https://img.shields.io/github/stars/siyuan-note/siyuan-android) |
| [ios](https://github.com/siyuan-note/siyuan-ios)         | iOS uygulaması        | ![GitHub forks](https://img.shields.io/github/forks/siyuan-note/siyuan-ios)     | ![GitHub Repo stars](https://img.shields.io/github/stars/siyuan-note/siyuan-ios)     |
| [harmony](https://github.com/siyuan-note/siyuan-harmony) | HarmonyOS uygulaması  | ![GitHub forks](https://img.shields.io/github/forks/siyuan-note/siyuan-harmony) | ![GitHub Repo stars](https://img.shields.io/github/stars/siyuan-note/siyuan-harmony) |
| [riff](https://github.com/siyuan-note/riff)              | Aralıklı tekrar       | ![GitHub forks](https://img.shields.io/github/forks/siyuan-note/riff)           | ![GitHub Repo stars](https://img.shields.io/github/stars/siyuan-note/riff)           |

## 🌟 Yıldız Geçmişi

<a href="https://star-history.com/#siyuan-note/siyuan&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=siyuan-note/siyuan&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=siyuan-note/siyuan&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=siyuan-note/siyuan&type=Date" />
 </picture>
</a>

## 🗺️ Yol Haritası

* [SiYuan geliştirme planı ve ilerlemesi](https://github.com/orgs/siyuan-note/projects/1)
* [SiYuan değişiklik günlüğü](CHANGELOG.md)

## 🚀 Kurulum ve İndirme

Masaüstü ve mobil cihazlarda uygulama marketleri üzerinden kurulum önerilir, böylece gelecekte tek tıkla güncelleme yapabilirsiniz.

### Uygulama Marketi

Mobil:

* [App Store](https://apps.apple.com/us/app/siyuan/id1583226508)
* [Google Play](https://play.google.com/store/apps/details?id=org.b3log.siyuan)
* [F-Droid](https://f-droid.org/packages/org.b3log.siyuan)

Masaüstü:

* [Microsoft Store](https://apps.microsoft.com/detail/9p7hpmxp73k4)

### Kurulum Paketi

* [B3log](https://b3log.org/siyuan/en/download.html)
* [GitHub](https://github.com/siyuan-note/siyuan/releases)

### Docker ile Barındırma

<details>
<summary>Docker Dağıtımı</summary>

#### Genel Bakış

SiYuan'ı bir sunucuda barındırmanın en kolay yolu Docker ile dağıtımdır.

* Görüntü adı: `b3log/siyuan`
* [Görüntü URL'si](https://hub.docker.com/r/b3log/siyuan)

#### Dosya yapısı

Tüm program `/opt/siyuan/` altında yer alır. Temel olarak Electron kurulum paketinin kaynaklar klasöründeki yapıya benzer:

* appearance: simgeler, temalar, diller
* guide: kullanıcı kılavuzu
* stage: arayüz ve statik kaynaklar
* kernel: çekirdek program

#### Giriş Noktası

Docker görüntüsü oluşturulurken giriş noktası şu şekilde ayarlanır: `ENTRYPOINT ["/opt/siyuan/entrypoint.sh"]`. Bu betik, konteyner içinde çalışacak kullanıcının `PUID` ve `PGID` değerlerini değiştirmeye olanak tanır. Bu, özellikle ana makineden bağlanan dizinlerde izin sorunlarını çözmek için önemlidir. `PUID` (Kullanıcı Kimliği) ve `PGID` (Grup Kimliği) ortam değişkenleri olarak iletilebilir.

Konteyner `docker run b3log/siyuan` ile çalıştırılırken şu parametreler kullanılır:

* `--workspace`: çalışma alanı klasör yolunu belirtir, ana makineden `-v` ile bağlanır
* `--accessAuthCode`: erişim yetkilendirme kodunu belirtir

Daha fazla parametre için `--help` kullanılabilir. İşte yeni ortam değişkenleriyle örnek bir başlatma komutu:

```bash
docker run -d \
  -v workspace_dir_host:workspace_dir_container \
  -p 6806:6806 \
  -e PUID=1001 -e PGID=1002 \
  b3log/siyuan \
  --workspace=workspace_dir_container \
  --accessAuthCode=xxx
```

* `PUID`: Özel kullanıcı kimliği (isteğe bağlı, belirtilmezse varsayılan `1000`)
* `PGID`: Özel grup kimliği (isteğe bağlı, belirtilmezse varsayılan `1000`)
* `workspace_dir_host`: Ana makinedeki çalışma alanı klasör yolu
* `workspace_dir_container`: Konteyner içindeki çalışma alanı klasör yolu
  * Alternatif olarak, yol `SIYUAN_WORKSPACE_PATH` ortam değişkeni ile de ayarlanabilir. Komut satırı her zaman önceliklidir
* `accessAuthCode`: Erişim yetkilendirme kodu (lütfen **mutlaka değiştirin**, aksi takdirde herkes verilerinize erişebilir)
  * Alternatif olarak, yetkilendirme kodu `SIYUAN_ACCESS_AUTH_CODE` ortam değişkeni ile ayarlanabilir
  * Erişim kodunu devre dışı bırakmak için `SIYUAN_ACCESS_AUTH_CODE_BYPASS=true` ortam değişkeni kullanılabilir

Basitleştirmek için, çalışma alanı klasör yolunu ana makine ve konteynerde aynı yapmanız önerilir, örneğin her ikisi de `/siyuan/workspace` olarak ayarlanabilir:

```bash
docker run -d \
  -v /siyuan/workspace:/siyuan/workspace \
  -p 6806:6806 \
  -e PUID=1001 -e PGID=1002 \
  b3log/siyuan \
  --workspace=/siyuan/workspace/ \
  --accessAuthCode=xxx
```

#### Docker Compose

Docker Compose kullanıcıları için `PUID` ve `PGID` ortam değişkenleri kullanıcı ve grup kimliklerini özelleştirmek için iletilebilir. İşte örnek bir Docker Compose yapılandırması:

```yaml
version: "3.9"
services:
  main:
    image: b3log/siyuan
    command: ['--workspace=/siyuan/workspace/', '--accessAuthCode=${AuthCode}']
    ports:
      - 6806:6806
    volumes:
      - /siyuan/workspace:/siyuan/workspace
    restart: unless-stopped
    environment:
      - TZ=${YOUR_TIME_ZONE}
      - PUID=${YOUR_USER_PUID}
      - PGID=${YOUR_USER_PGID}
```

Bu yapılandırmada:

* `PUID` ve `PGID` dinamik olarak ayarlanır
* Bu değişkenler sağlanmazsa, varsayılan `1000` kullanılır

#### Kullanıcı İzinleri

Görüntüdeki `entrypoint.sh` betiği, belirtilen `PUID` ve `PGID` ile `siyuan` kullanıcısını ve grubunu oluşturur. Bu nedenle, ana makinede çalışma alanı klasörü oluşturulurken, klasörün kullanıcı ve grup sahipliğinin `PUID` ve `PGID` ile eşleştiğinden emin olunmalıdır:

```bash
chown -R 1001:1002 /siyuan/workspace
```

#### Gizli Port

NGINX reverse proxy kullanarak 6806 portunu gizleyebilirsiniz. WebSocket için `/ws` yolunu da yapılandırmayı unutmayın.

#### Notlar

* Bağlanan dizinin doğruluğundan emin olun, aksi takdirde konteyner silindiğinde veriler kaybolur
* URL yeniden yönlendirmesi kullanmayın, kimlik doğrulama sorunları yaşanabilir
* İzin sorunları yaşıyorsanız, `PUID` ve `PGID` ortam değişkenlerinin ana makinedeki dizin sahipliğiyle eşleştiğini kontrol edin

#### Sınırlamalar

* Masaüstü ve mobil uygulama bağlantıları desteklenmez, yalnızca tarayıcı üzerinden kullanılabilir
* PDF, HTML ve Word dışa aktarma desteklenmez
* Markdown dosya içe aktarma desteklenmez

</details>

### Unraid ile Barındırma

<details>
<summary>Unraid Dağıtımı</summary>

Not: İlk olarak terminalde `chown -R 1000:1000 /mnt/user/appdata/siyuan` komutunu çalıştırın

Şablon referansı:

```
Web UI: 6806
Container Port: 6806
Container Path: /home/siyuan
Host path: /mnt/user/appdata/siyuan
PUID: 1000
PGID: 1000
Publish parameters: --accessAuthCode=******(Erişim yetkilendirme kodu)
```

</details>

### İçeriden Önizleme

Büyük güncellemelerden önce içeriden önizlemeler yayınlarız: [https://github.com/siyuan-note/insider](https://github.com/siyuan-note/insider)

## 🏘️ Topluluk

* [İngilizce Tartışma Forumu](https://liuyun.io)
* [Kullanıcı topluluğu özeti](https://liuyun.io/article/1687779743723)
* [Harika SiYuan](https://github.com/siyuan-note/awesome)

## 🛠️ Geliştirme Rehberi

Bkz. [Geliştirme Rehberi](https://github.com/siyuan-note/siyuan/blob/master/.github/CONTRIBUTING.md)

## ❓ Sıkça Sorulan Sorular

### SiYuan verileri nasıl saklar?

Veriler çalışma alanı klasöründe saklanır. Çalışma alanı veri klasörü içinde:

* `assets`: eklenen tüm dosyalar
* `emojis`: emoji görselleri
* `snippets`: kod parçacıkları
* `storage`: sorgular, düzenler, flaş kartlar vb.
* `templates`: şablon parçacıkları
* `widgets`: widget'lar
* `plugins`: eklentiler
* `public`: herkese açık veriler
* Geri kalan klasörler kullanıcı tarafından oluşturulan not defterleridir. `.sy` uzantılı dosyalar belge verilerini JSON formatında saklar

### Üçüncü taraf senkronizasyon diskleriyle veri senkronizasyonu destekliyor mu?

Üçüncü taraf senkronizasyon diskleri desteklenmez, aksi halde veriler bozulabilir.

Bunun yerine üçüncü taraf bulut depolamalarla bağlantı kurmak desteklenir (ücretli üyelik gerekir).

Ayrıca manuel olarak veri dışa/içe aktarma ile senkronizasyon sağlanabilir:

* Masaüstü: <kbd>Ayarlar</kbd> - <kbd>Dışa Aktar</kbd> - <kbd>Verileri Dışa Aktar</kbd> / <kbd>Verileri İçe Aktar</kbd>
* Mobil: <kbd>Sağ sütun</kbd> - <kbd>Hakkında</kbd> - <kbd>Verileri Dışa Aktar</kbd> / <kbd>Verileri İçe Aktar</kbd>

### SiYuan açık kaynak mı?

SiYuan tamamen açık kaynaktır. Katkılarınız bekleniyor:

* [Kullanıcı Arayüzü ve Çekirdek](https://github.com/siyuan-note/siyuan)
* [Android](https://github.com/siyuan-note/siyuan-android)
* [iOS](https://github.com/siyuan-note/siyuan-ios)
* [HarmonyOS](https://github.com/siyuan-note/siyuan-harmony)
* [Chrome Kırpma Uzantısı](https://github.com/siyuan-note/siyuan-chrome)

Daha fazlası için [Geliştirme Rehberi](https://github.com/siyuan-note/siyuan/blob/master/.github/CONTRIBUTING.md)'ne bakın.

### Yeni sürüme nasıl geçerim?

* Uygulama marketi üzerinden kurduysanız, oradan güncelleyin
* Masaüstünde kurulum paketiyle kurduysanız: <kbd>Ayarlar</kbd> - <kbd>Hakkında</kbd> - <kbd>Güncellemeleri otomatik indir</kbd> seçeneğini açabilirsiniz
* Manuel kurulum yaptıysanız, yeni kurulum paketini tekrar indirip kurun

Güncellemeleri <kbd>Ayarlar</kbd> - <kbd>Hakkında</kbd> - <kbd>Sürümü Kontrol Et</kbd> üzerinden yapabilir veya [Resmî İndirme](https://b3log.org/siyuan/en/download.html) veya [GitHub Sürümleri](https://github.com/siyuan-note/siyuan/releases) sayfalarını takip edebilirsiniz.

### Bazı blokların (örneğin liste öğelerindeki paragraf blokları) blok simgesi bulunamazsa ne olur?

Liste öğesi altındaki ilk alt blokta blok simgesi gizlidir. İmleci bu bloğa getirip <kbd>Ctrl+/</kbd> ile blok menüsünü açabilirsiniz.

### Veri deposu anahtarı kaybolursa ne yapmalıyım?

* Eğer anahtar daha önce doğru şekilde yapılandırıldıysa, tüm cihazlarda aynıdır. <kbd>Ayarlar</kbd> - <kbd>Hakkında</kbd> - <kbd>Veri deposu anahtarı</kbd> - <kbd>Anahtar dizisini kopyala</kbd> ile geri alabilirsiniz
* Daha önce doğru yapılandırılmadıysa veya tüm cihazlardan anahtar erişilemez hale geldiyse, şu adımlarla sıfırlayabilirsiniz:

  1. Verileri manuel olarak yedekleyin: <kbd>Verileri Dışa Aktar</kbd> veya doğrudan `workspace/data/` klasörünü kopyalayın
  2. <kbd>Ayarlar</kbd> - <kbd>Hakkında</kbd> - <kbd>Veri deposu anahtarı</kbd> - <kbd>Veri deposunu sıfırla</kbd>
  3. Anahtarı yeniden başlatın. Bir cihazda başlatıldıktan sonra diğer cihazlarda içe aktarın
  4. Bulutta yeni bir senkronizasyon dizini kullanın, eskisi silinebilir
  5. Eski bulut anlık görüntüleri artık kullanılamaz, silinebilir

### Ücret ödemem gerekiyor mu?

Çoğu özellik ücretsizdir, ticari kullanım dahil.

Ücretli üyelik gerektiren özellikler için [Fiyatlandırma](https://b3log.org/siyuan/en/pricing.html) sayfasına bakın.

## 🙏 Teşekkürler

SiYuan'ın doğması birçok açık kaynak projesine ve katkıcıya borçludur. Detaylar için proje kaynak kodlarındaki `kernel/go.mod`, `app/package.json` ve proje ana sayfasına bakın.

SiYuan'ın büyümesi kullanıcı geri bildirimleri ve tanıtımlarıyla mümkün olmuştur. Herkese teşekkürler ❤️

### Katkıda Bulunanlar

SiYuan'a kod katkısında bulunmak için aramıza katılın.

<a href="https://github.com/siyuan-note/siyuan/graphs/contributors">
   <img src="https://contrib.rocks/image?repo=siyuan-note/siyuan" />
</a>
</details>
```