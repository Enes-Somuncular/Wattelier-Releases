<p align="right"><strong>Türkçe</strong> · <a href="README.en.md">English</a></p>

<div align="center">

<img src="site/assets/logo.svg" width="86" height="86" alt="Wattelier" />

# Wattelier

**Power, clarified. · Pil yüzdesinin ötesini gör.**

Mac’inin pilini, güç akışını ve uyku sonrası pil değişimini menü çubuğundan takip et.

**[↓ Wattelier 1.6.3’ü indir](https://github.com/Enes-Somuncular/Wattelier-Releases/releases/download/v1.6.3/Wattelier-1.6.3.dmg)** · [Sürüm notları](https://github.com/Enes-Somuncular/Wattelier-Releases/releases/tag/v1.6.3) · [Tüm sürümler](https://github.com/Enes-Somuncular/Wattelier-Releases/releases)

Apple Silicon · macOS 13+ · Türkçe arayüz · Sistem / Açık / Koyu tema

</div>

## 1.6.3 — Enerjinin geçmişini gör

**Yeni enerji analizi, uyku raporları ve daha küçük bir panel.** Beta 5’te denenen özellikler, aynı uygulama koduyla yeniden derlenen 1.6.3 kararlı sürümünde bir araya geliyor.

| Genel bakış · Koyu tema | Yeni enerji analizi |
| :---: | :---: |
| <img src="assets/screenshots/wattelier-1.6.3-overview-dark.png" width="360" alt="Wattelier 1.6.3: pil özeti, animasyonlu güç akışı ve pil sağlığı" /> | <img src="assets/screenshots/wattelier-1.6.3-analysis-dark.png" width="360" alt="Wattelier 1.6.3: ortak tarih seçimi, ekran ve uyku süreleri, kalıcı güç geçmişi" /> |

<sub>1.6.3 uygulama arayüzünden örnek verilerle oluşturulmuş görseller; kişisel kullanım ölçümleri değildir.</sub>

### Geçmişe dön, aynı dönemi birlikte incele

Güç geçmişi artık uygulamayı kapatıp açınca kaybolmaz. **30 günlük ayrıntılı kayıt** ve **90 günlük saatlik özet**, Mac’inin kullanımını zaman içinde incelemene yardımcı olur.

**Son saat · Bugün · 7 gün · 30 gün · Tarih seç.** Grafikte bir aralık seçtiğinde dönem özeti, uyku oturumları, olay listesi ve uygulama etkisi aynı zaman aralığına göre güncellenir. Pil yüzdesi ve tahmini Mac gücü ayrı grafiklerde gösterilir; veri boşlukları çizgiyle doldurulmaz.

### Kapağı kapattıktan sonra ne oldu?

Uyku raporu; oturumun süresini, başlangıç ve bitiş pil seviyelerini, hesaplanabiliyorsa **net yüzde puanı farkını** gösterir. Erişilebilen sistem kayıtları, bakım veya ağ erişimi gibi arka plan uyanma kategorileriyle rapora eşlik eder.

Ekranın kapalı olmasıyla sistemin uyuması ayrı izlenir. Böylece **ekran açık**, **ekran kapalı çalışma**, **uyku** ve **bilinmeyen dönemler** birbirine karışmaz. Yeni raporlar, uygulama kayıt yaparken gerçekleşen uyku/uyanma oturumlarıyla oluşur; kaydedilmemiş eski boşluklar sonradan uyku sayılmaz.

### Küçük panel, ihtiyaç duyduğunda geniş görünüm

İlk kullanımda küçük panelle başla. **Pil → Güç akışı → Analiz** sayfalarını büyük ok düğmeleriyle veya panel odaktayken klavyenin sağ/sol oklarıyla gezebilirsin.

- Pil seviyesi, şarj durumu, pil sağlığı ve döngü sayısı tek Pil kartında.
- Aynı paneli genişletip küçültebilirsin; son seçtiğin boyut hatırlanır.
- **Sistem, Açık ve Koyu** tema seçenekleri; okunabilir kartlar ve yerel cam yüzeyler.
- Klasik kısa pil simgesi ve menü çubuğunda seçilebilir bilgi gösterimi.

### Gücü hareket halinde gör

Kehribar elektrik hattı Mac’e, turkuaz hat şarj olan pile akar. **Animasyonun hızı watt değerine göre değişir; enerji kartlara ulaştıkça çerçeveleri canlanır.** Şarj beklemedeyken pil kolu sönük kalır. Elektrik akışı panel kapalıyken durur ve macOS’un **Hareketi Azalt** tercihi desteklenir.

| Açık görünüm | Elektrik akışı |
| :---: | :---: |
| <img src="assets/screenshots/wattelier-1.6.3-overview-light.png" width="360" alt="Wattelier açık görünümde okunabilir pil ve güç kartları" /> | <img src="assets/screenshots/wattelier-1.6.3-power-flow.png" width="360" alt="Mac ve pil kartlarına ulaşan dallanan elektrik akışı" /> |

## Ölçümleri doğru yorumla

| Gösterilen bilgi | Ne anlama gelir? |
| --- | --- |
| **Pil seviyesi ve uyku farkı** | İşletim sisteminin bildirdiği seviyeler ve aralarındaki net yüzde puanı farkı. Ölçülmüş Wh veya uygulama bazında kesin tüketim değildir. |
| **Mac gücü ve enerji** | Model tahminleri. Uyku boşluklarına son açık ekran watt değeri taşınmaz. |
| **Uygulama etkisi** | CPU temelli göreceli tahmin. GPU, ekran ve tüm arka plan yükleri uygulamalara kesin olarak dağıtılamaz. |
| **Ekran açık süresi** | Gözlenen ekran durumu; ekranın tek başına kesin watt tüketimi değildir. |
| **Uyanma nedenleri** | Erişilebilen sistem olayları. Her uyanmayı kapsamayabilir ve kaybın tamamını bir uygulamaya atfetmez. |

Eksik veri **sıfır tüketim** sayılmaz. Şarjla karışan veya sınır ölçümü eksik oturumlarda kesin kayıp hesaplanmaz. Pil yüzdesi yuvarlandığı için değişmeyen yüzde, hiç enerji harcanmadığı anlamına gelmez.

## Yerel kayıt, açık tercihler

- Ayrıntılı pil/analiz kayıtları ve uygulama geçmişi en fazla **30 gün**, analiz saatlik özetleri ve uyku olayları en fazla **90 gün** bu Mac’te tutulur.
- **Uygulama geçmişi varsayılan kapalıdır.** Kaydı açabilir, durdurabilir veya kayıtları silebilirsin.
- Küçük ek kayıtlar ve saatlik dosya yenileme, bütün geçmişi her dakika yeniden yazmayı önler.
- Pil ölçümleri ve uygulama listeleri sunucuya gönderilmez. Güncelleme denetimi ve indirmeler GitHub üzerinden yapılır.
- Ölçüm için Mac uyandırılmaz; yönetici izni, kalıcı ayrıcalıklı yardımcı veya güç/firmware ayarı değişikliği gerekmez.

## Koruma ve bildirimler

Şarj hedefi ve düşük pil hatırlatmalarını **Koruma** bölümünden yönet. Tam dolum bildirimi macOS’un gerçek tam dolum durumunu bekler; uygulamayı dolu pille açmak tekrar uyarı üretmez.

**Şarj sınırı ayarlarını aç** düğmesi macOS Pil sayfasına gider. Şarj satırındaki **alttaki ⓘ** düğmesini kullan. Wattelier’in şarj hatırlatma hedefi gerçek şarj sınırı değildir; uygulama mevcut sistem sınırını okumaz veya değiştirmez. Apple Kestirmeler kurulumu gerekmez.

## İndir, güncelle ve başla

1. **[Wattelier 1.6.3 DMG](https://github.com/Enes-Somuncular/Wattelier-Releases/releases/download/v1.6.3/Wattelier-1.6.3.dmg)** dosyasını aç, Wattelier’i **Uygulamalar / Applications** klasörüne sürükle.
2. Uygulamayı açıp menü çubuğundaki pil simgesine tıkla.
3. **Analiz** bölümünde **Pil ve analiz geçmişini kaydet** seçeneğini açık bırak. Uyku raporu için bir uyku/uyanma oturumu gerçekleştir.

**Zaten kullanıyorsan:** **Ayarlar → Güncellemeleri denetle** yoluyla güncelle. Önceki kararlı sürümlerden ve **1.6.3-beta.5**’ten 1.6.3’e geçiş desteklenir; tercihler ve mevcut geçmiş korunur. Kararlı kanal için **Ayarlar → Güncellemeler → Kararlı** seçeneğini kullan.

[ZIP paketi](https://github.com/Enes-Somuncular/Wattelier-Releases/releases/download/v1.6.3/Wattelier-1.6.3.zip) · [SHA256](https://github.com/Enes-Somuncular/Wattelier-Releases/releases/download/v1.6.3/SHA256SUMS) · [Kurulum rehberi](docs/INSTALL.md) · [Sorun bildir](https://github.com/Enes-Somuncular/Wattelier-Releases/issues/new/choose)

**Gereksinimler:** Apple Silicon MacBook ve macOS 13 veya üzeri. Intel sürümü yoktur. Uygulama ad-hoc imzalıdır; Apple Developer ID / notarization henüz yoktur. İlk açılışla ilgili ayrıntılar kurulum rehberindedir.

## Beta kanalı ve eski kurulumlar

Yeni denemeler için **Ayarlar → Güncellemeler → Beta** kanalını seçebilirsin. 1.6.3, Beta 5 kodunun kararlı kimlikle yeniden derlenmiş sürümüdür; beta paketleri [sürüm arşivinde](https://github.com/Enes-Somuncular/Wattelier-Releases/releases) değişmeden kalır.

Görünen ürün adı **Wattelier**’dir. Eski MacBattery kurulumlarının tercihlerini, geçmişini ve Sparkle güncellemelerini korumak için iç paket yolu **MacBattery.app** ve uygulama kimliği korunur. Yeni indirmeler **Wattelier-VERSION.dmg / .zip** adını taşır.

Bu depo indirmeler ve ürün dokümantasyonu içindir; kaynak kodu özeldir. GitHub’ın otomatik **Source code (zip/tar.gz)** dosyaları kurulum paketi değildir. Kurulum için DMG veya uygulama ZIP’ini kullan.

---

<div align="center">

[Son kararlı sürüm](https://github.com/Enes-Somuncular/Wattelier-Releases/releases/latest) · [SSS](docs/FAQ.md) · [Geri bildirim](https://github.com/Enes-Somuncular/Wattelier-Releases/issues/new/choose)

<sub>Wattelier · Power, clarified. · Enes Somuncular</sub>

</div>
