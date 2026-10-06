<h1 align="center">Mouse Synchronization</h1>

<p align="center"><b>Tek bir fareyle birçok pencereyi aynı anda kontrol edin — bir lider pencerede tıklayın, kaydırın ve sürükleyin; listedeki diğer tüm pencereler aynı anda tıpatıp aynısını yapsın.</b></p>

<p align="center">
  <a href="README.md">English</a> ·
  <a href="README.vi.md">Tiếng Việt</a> ·
  <a href="README.bn.md">বাংলা</a> ·
  <a href="README.hi.md">हिन्दी</a> ·
  <a href="README.pt_BR.md">Português (BR)</a> ·
  <a href="README.ru.md">Русский</a> ·
  <b>Türkçe</b> ·
  <a href="README.ur.md">اردو</a> ·
  <a href="README.zh_CN.md">简体中文</a>
</p>

<p align="center">
  <a href="https://github.com/duckmartians/Mouse-Synchronization/releases/latest"><img alt="Windows için indir" src="https://img.shields.io/badge/%C4%B0ndir-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white"></a>
</p>

---

## Kurulum

### Adım 1 — İndirin

En son sürümü **[Releases](https://github.com/duckmartians/Mouse-Synchronization/releases/latest)** sayfasından indirin:

| Bilgisayarınız | İndir | Not |
|---|---|---|
| 🪟 **Windows** | [Windows (.zip)](https://github.com/duckmartians/Mouse-Synchronization/releases/latest) | Dosyanın adı [`Mouse-Synchronization_v<sürüm>.zip`](https://github.com/duckmartians/Mouse-Synchronization/releases/latest). macOS sürümü yoktur. |

### Adım 2 — Zipten çıkarın ve çalıştırın

<details open>
<summary><b>🪟 Windows'ta</b></summary>

1. İndirdiğiniz `.zip` dosyasını istediğiniz bir klasöre **çıkarın** (sağ tık → **Tümünü Ayıkla…**). Kurulum programı yoktur.
2. Çıkarılan klasörü açın ve **`Mouse Synchronization.exe`** dosyasını çalıştırın.
3. **"Windows bilgisayarınızı korudu"** (SmartScreen) uyarısı çıkarsa: **Ek bilgi** → **Yine de çalıştır**'a tıklayın. *(Uygulama Microsoft sertifikasıyla imzalanmadığı için işaretlenebilir — virüs değildir.)*
4. Klasörün tamamını bir arada tutun — `.exe` yanındaki dosyalara ihtiyaç duyar. Uygulamayı kaldırmak için klasörü silmeniz yeterli.

</details>

### Adım 3 — Ücretsiz, hesap gerekmez

Mouse Synchronization **ücretsizdir**: hesap yok, etkinleştirme anahtarı yok, reklam yok. Normal pencereler için yönetici hakları gerekmez (yönetici olarak çalışan pencereler için aşağıdaki Sorun giderme bölümüne bakın).

---

## İlk çalıştırma

1. **Kontrol etmek istediğiniz pencereleri açın** — örneğin aynı programın birkaç kopyası.
2. **Mouse Synchronization'ı çalıştırın.** Sol panel, **Açık pencereler**, o anda açık olan her şeyi listeler.
3. **Onları eşitleme listesine ekleyin.** Bir pencerenin yanındaki yeşil **➕**'ya tıklayın (ya da birkaçını seçip **Ekle →**'ye basın). Sağ panele, **Eşitleme listesi**'ne geçerler. **En az 2 pencere** gerekir.
4. **Lideri seçin.** Eşitleme listesinde, kontrol etmek istediğiniz pencerenin yanındaki **yıldıza ☆** tıklayın. **Altın sarısı ★** olur — artık ana pencereniz budur.
5. **Başlat'a basın** (ya da **Ctrl + 1**).
6. **Lider pencereyi kullanın.** İçinde tıklayın, kaydırın ya da tıklayıp sürükleyin; listedeki diğer tüm pencereler aynı anda aynısını yapar.

Durdurmak için **Eşitlemeyi durdur**'a tıklayın (ya da **Ctrl + 2**). Durdurmadan kısa bir ara vermek için **Duraklat**'a basın (**Alt + 1**).

---

## Özellikler

<img width="1052" height="792" alt="Mouse Synchronization" src="https://github.com/user-attachments/assets/57c22608-46a6-4206-adde-aa456440619e" />
<img width="1919" height="1032" alt="Mouse Synchronization" src="https://github.com/user-attachments/assets/c93fee4f-a696-451e-894b-94fe3312fd58" />

- **Tek fare, çok pencere** — lider penceredeki sol, sağ ve orta tıklamalar, kaydırma ve tıklayıp sürükleme, Eşitleme listesindeki tüm pencerelere aynı anda gönderilir. Yalnızca fare eşitlenir, klavye değil.
- **Pencere oranına göre eşitle** — pencerelerin boyutu veya konumu farklıysa, işlemler tam koordinat yerine *göreli* konuma göre eşleştirilir.
- **Pencereleri hızla bulun ve ekleyin** — arama kutulu canlı pencere listesi, bir grubu tek seferde eklemek için **Eşleşenleri ekle** ve geçerli sanal masaüstüne göre filtre.
- **Izgaraya diz** — eşitlenen pencerelerinizi seçtiğiniz monitörlerde düzenli bir ızgaraya yerleştirir.
- **Daha fazla pencere aç** — bir pencerenin arkasındaki programın 1–20 ek kopyasını başlatır.
- **Özelleştirilebilir kısayollar** — Başlat, Durdur ve Duraklat / Devam et; oturumlar arasında hatırlanır.
- **Yüzen durum rozeti** — eşitleme sırasında yeşil, duraklatıldığında kehribar rengi; duraklatmak veya devam ettirmek için üzerine tıklayın.
- **Aracın birden fazla kopyasını çalıştırın** — her kopyanın kendi numarası ve kendi Duraklat kısayolu vardır.
- **9 dil** — 🌐 düğmesiyle anında değiştirin, yeniden başlatma gerekmez.

---

## Ana pencere

### 🪟 Sol panel — Açık pencereler

Bilgisayarınızdaki tüm açık pencerelerin canlı listesi.
- **➕** — bu pencereyi eşitleme listesine ekler.
- **👁** — görebilmeniz için bu pencereyi öne getirir.
- **Arama kutusu** — listeyi filtrelemek için pencere adının bir kısmını yazın.
- **Eşleşenleri ekle** — aramanızla eşleşen tüm pencereleri tek tıkla ekler (arama kutusuna bir şey yazdıktan sonra çalışır). 10'dan fazla pencere eklerken çok işe yarar.
- **Yalnızca geçerli Masaüstü** — diğer sanal masaüstlerinizdeki pencereleri gizler.

### ➕ Daha fazla pencere aç

Bir programın daha fazla kopyasını mı istiyorsunuz? **Açık pencereler** listesinde bir pencereye tıklayın, **Pencere sayısı**'nı (1–20) ayarlayın ve **Daha fazla aç**'a tıklayın. Uygulama o pencerenin arkasındaki programı bulur ve ek kopyalar başlatır. Bazı programlar kendilerinin yalnızca bir kopyasına izin verir — fazlalıkları kendileri kapatır; bu programın kuralıdır, hata değildir.

### ↔️ Orta sütun — işlemler

- **Ekle → / ← Kaldır / Tümünü kaldır** — pencereleri eşitleme listesine ekler veya listeden çıkarır.
- **Yenile** — açık pencereleri yeniden tarar (bir pencere eksikse kullanın).
- **Diz** — eşitlenen pencereleri **Monitör seç** altında işaretli monitörlerde düzenli bir ızgaraya yerleştirir.
- **Monitör seç** — pencerelerin dizileceği ekranları işaretleyin. **Yıldız** "ana" ekranınızı gösterir; yalnızca uygulama içi bir etikettir ve Windows ayarlarınızı **değiştirmez**.

### ⭐ Sağ panel — Eşitleme listesi

Liderinizi takip edecek pencereler.
- **Yıldız ★** — lider (ana) pencereyi seçer. Yalnızca bir pencere lider olabilir.
- **👁** — o pencereyi öne getirir.
- **➖** — bu pencereyi listeden kaldırır.

Bir pencere eşitleme listesindeyken, uygulama onları ayırt edebilmeniz için başlığına `[1]`, `[2]` gibi küçük bir numara ekler. Pencereyi kaldırdığınızda veya uygulamayı kapattığınızda özgün başlıklar geri gelir.

### ▶️ Alt çubuk — kontroller

- **Başlat / Duraklat / Eşitlemeyi durdur** — eşitlemeyi başlatır, duraklatır veya durdurur. Her düğmenin altındaki küçük kutular onun klavye kısayoludur.
- **Pencere oranına göre eşitle** — pencereleriniz farklı boyutta veya farklı konumdaysa **açın**; hepsi aynı boyutta ve hizalıysa **kapalı** bırakın.
- **🏠** — Duck Martians web sitesini açar ([duckmartians.info](https://duckmartians.info)).
- **🌐** — uygulamanın dilini değiştirir (English, Tiếng Việt, বাংলা, हिन्दी, Português (Brasil), Русский, Türkçe, اردو, 简体中文).

---

## Klavye kısayolları

| İşlem | Varsayılan kısayol |
|---|---|
| Başlat | **Ctrl + 1** |
| Durdur | **Ctrl + 2** |
| Duraklat / Devam et | **Alt + 1** |

**Kısayolu değiştirme:** bir kısayol kutusuna tıklayın, istediğiniz tuşları yazın (örneğin ilk kutuya `Ctrl`, ikinciye `F5`) ve başka bir yere tıklayın. Kısayol kutuları **eşitleme sırasında kilitlidir** — değiştirmek için önce durdurun. Kısayollarınız uygulamayı bir sonraki açışınızda hatırlanır.

## Yüzen durum rozeti

Eşitleme başladığında ekranın köşesinde küçük bir rozet belirir: **yeşil** = eşitleniyor, **kehribar** = duraklatıldı. Duraklatmak veya devam ettirmek için **rozete tıklayın** — diğer pencereler uygulamayı kapattığında çok kullanışlıdır. Durdur'a bastığınızda kaybolur.

## Aracın birden fazla kopyasını çalıştırma

Mouse Synchronization'ı birden fazla kez açabilirsiniz. Her kopya, başlığında ve Duraklat düğmesinde görünen kendi numarasını ("Kopya 1", "Kopya 2"…) ve kendi varsayılan Duraklat kısayolunu (**Alt + kendi numarası**) alır; böylece onları birbirinden bağımsız duraklatabilirsiniz.

---

## Verileriniz nerede

| Ne | Nerede |
|---|---|
| Dil ve klavye kısayolları | `%APPDATA%\Mouse Synchronization\settings.ini` |

Başka hiçbir şey kaydedilmez ve uygulama hiçbir yere veri göndermez — fare işlemleri doğrudan kendi bilgisayarınızdaki pencerelere iletilir.

---

## Sorun giderme

**Başlat hiçbir şey yapmıyor / uyarı gösteriyor** — bir ana pencere seçin (altın yıldız ★) ve eşitleme listesine en az 2 pencere ekleyin.

**İstediğim pencere listede yok** — **Yenile**'ye tıklayın. Başka bir sanal masaüstündeyse **Yalnızca geçerli Masaüstü** işaretini kaldırın.

**Tıkladığımda diğer pencereler tepki vermiyor** — eşitleme çalışırken (yeşil rozet) lider pencerenin (altın yıldız) içinde işlem yapmalısınız. Hedef pencere "yönetici olarak" çalışıyorsa Windows normal uygulamaların onu kontrol etmesini engeller — Mouse Synchronization'a sağ tıklayın → **Yönetici olarak çalıştır**.

**Pencereler beklediğim gibi hizalanmıyor** — boyutları farklıysa **Pencere oranına göre eşitle**'yi açın. Izgaraya dizmek için **Monitör seç** altında monitörleri işaretleyip **Diz**'e tıklayın.

**"Daha fazla aç" hemen kapanan bir kopya açıyor** — o program kendisinin yalnızca bir kopyasına izin veriyor.

**Windows "Windows bilgisayarınızı korudu" ile engelliyor** — **Ek bilgi → Yine de çalıştır**'a tıklayın. Uygulama Microsoft sertifikasıyla imzalanmamıştır — virüs değildir.
