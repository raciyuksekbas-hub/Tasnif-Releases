<div align="center">

# ⚖️ Tasnif

### Belgeler yerini bulsun.

**UYAP’tan indirdiğiniz belgeleri tek tek klasörlemekle uğraşmayın.**  
Tasnif; mahkeme/kurum, dosya numarası, belge türü ve dava dosyası ilişkisini bilgisayarınızda analiz eder, doğru klasörü önerir ve **yalnız siz onaylarsanız** düzenler.

![Version](https://img.shields.io/badge/version-v0.4.0%20Beta-555?style=flat-square)
![macOS](https://img.shields.io/badge/macOS-Apple%20Silicon-000?style=flat-square&logo=apple&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-x64-0078D4?style=flat-square&logo=windows&logoColor=white)
![Local](https://img.shields.io/badge/çalışma-yerel-success?style=flat-square)

</div>

---

## ⬇️ İndir

| 🪟 Windows | 🍎 macOS |
|---|---|
| **Windows x64** | **Apple Silicon (M1/M2/M3/M4 ve sonrası)** |
| [**Tasnif v0.4.0 Beta — Windows'u İndir**](https://github.com/raciyuksekbas-hub/Tasnif-Releases/releases/download/v0.4.0/Tasnif.Setup.0.4.0.exe) | [**Tasnif v0.4.0 Beta — macOS'u İndir**](https://github.com/raciyuksekbas-hub/Tasnif-Releases/releases/download/v0.4.0/Tasnif-0.4.0-arm64.dmg) |

> **Beta sürümüdür.** Önemli belgelerde işlem öncesinde Tasnif’in önerdiği hedefi kontrol etmenizi rica ederim.

---

## Tasnif ne yapar?

Gün içinde UYAP’tan onlarca belge indiriyoruz. Bir süre sonra masaüstü ve İndirilenler klasörü; dava dilekçeleri, tensip zaptları, kararlar, bilirkişi raporları, UDF’ler, PDF’ler ve taranmış belgelerle doluyor.

**Tasnif bu işi mümkün olduğunca otomatikleştirir:**

- 📂 Mahkeme veya kurumu tespit eder.
- 🔎 Esas/dosya numarasını belirler.
- 📄 Belge türünü anlamaya çalışır.
- 🧩 Aynı dava dosyasına ait belgeleri ilişkilendirir.
- 🗃️ Mevcut dava klasörünü bulur veya güvenliyse yenisini önerir.
- ⚖️ İstinaf/temyiz belgelerini mümkün olduğunda ana dava dosyasıyla ilişkilendirir.
- ✅ Dosyaları **siz onaylamadan taşımaz**.
- ↩️ Yapılan düzenleme işlemleri geri alınabilir.

---

## Nasıl çalışır?

### 1. Belgeleri ekleyin
PDF, UDF, DOCX, DOC, TIF/TIFF, JPG/JPEG belgelerinizi Tasnif’e bırakın.

### 2. Tasnif analiz etsin
Mahkeme/kurum, dosya numarası, belge türü ve ilgili dava dosyası için elindeki güvenilir bilgileri birlikte değerlendirir.

### 3. Öneriyi kontrol edin
Tasnif size hedef klasörü ve yapılacak işlemi gösterir. Gerçek bir belirsizlik varsa karar vermenizi ister.

### 4. Siz onaylayın, Tasnif uygulasın
Fiziksel dosya taşıma işlemi yalnız kullanıcı onayından sonra yapılır. Gerekirse işlem geri alınabilir.

> **Temel yaklaşım:** Algıla → Öner → İnsan onaylasın → Uygula.

---

## 🔐 Belgeleriniz sizde kalır

Tasnif’in özellikle hukuk pratiği için tasarlanmasının temel nedenlerinden biri **yerel çalışma** ilkesidir.

- 🤖 Yapay zekâ servisi kullanılmaz.
- 🔌 Harici API gerekmez.
- ☁️ Belgeler cloud’a yüklenmez.
- 🌐 Belge içeriği uzak bir sunucuya gönderilmez.
- 💻 Analiz bilgisayarınızda gerçekleştirilir.

**Dosyalarınız bilgisayarınızdan çıkmadan tasnif edilir.**

---

## Desteklenen belge türleri

`UDF` · `PDF` · `DOCX` · `DOC` · `TIF` · `TIFF` · `JPG` · `JPEG`

Bazı taranmış veya bozuk belgelerde içerik okunamayabilir. Tasnif, güvenilir biçimde karar veremediği durumlarda otomatik varsayım yapmak yerine kullanıcı kontrolünü tercih eder.

---

## 🧪 v0.4.0 Beta

Bu sürüm, gerçek kullanım geri bildirimlerinin kök-neden düzeltmelerini içeren bir bakım sürümüdür. Yeni özellik eklenmedi; odak doğru yönlendirme ve sorunsuz kurulum.

**Bu sürümde düzeltilenler:**
- Bir mahkeme diğerine müzekkere yazınca artık gereksiz yere dosya sorulmuyor (yazan mahkeme = dosya sahibi, hitap edilen = bilgi notu).
- Emniyet/Jandarma/SGK/hastane/banka gibi kurumların düzenleyip bir mahkeme dosyasına atıf yapan belgeleri (ör. Sosyal ve Ekonomik Durum Araştırma Raporu) artık atıf yapılan mahkeme dosyasına yönlendiriliyor.
- Reddiyat makbuzları, dosya tanınıyorsa artık her seferinde sorulmadan doğru klasöre bağlanıyor.
- Aynı mahkemenin farklı yazımları tek dava klasörüne toplanıyor; gerçekten farklı mahkemeler yanlışlıkla birleştirilmiyor.
- macOS’ta bazı Mac’lerde görülen “hasar görmüş olduğu için açılamıyor” hatası giderildi.

### macOS
- Apple Silicon / arm64 içindir.
- Intel Mac sürümü bu pakete dahil değildir.
- Paket Apple Developer ID ile imzalanmış/notarize edilmiş **değildir** (ücretsiz dağıtım). İlk açılışta macOS Gatekeeper “geliştirici doğrulanamadı” uyarısı görülebilir — bu normaldir.
- DMG’yi açıp `Tasnif.app` dosyasını **Uygulamalar** klasörüne sürükleyin.
- İlk açılışta uygulamaya **sağ tık → Aç** deyip bir kez onaylayın.

### Windows
- Windows x64 içindir.
- Kurulum paketi henüz code-signed değildir. Microsoft SmartScreen uyarısı görülebilir.
- Uyarı halinde **Ek bilgi → Yine de çalıştır** seçeneği kullanılabilir.

Dosya bütünlüğünü doğrulamak isteyenler için: [**SHA256SUMS.txt**](https://github.com/raciyuksekbas-hub/Tasnif-Releases/releases/download/v0.4.0/SHA256SUMS.txt)

---

## 🙏 Küçük bir ricam

Tasnif’i ücretsiz olarak meslektaşlarımın kullanımına açıyorum. Karşılığında kişisel bir ricam var:

**Rahmetli anneannem Cemile Salman için, herkes kendi inancı ve gönlünce bir dua eder veya güzel bir dilekte bulunursa çok sevinirim.**

Her inanca ve dünya görüşüne saygıyla; iyi niyetiniz benim için yeterli.

---

## 💬 Geri bildirim

Tasnif hâlâ beta aşamasında. Özellikle gerçek kullanım sırasında karşılaştığınız hatalar, yanlış klasör önerileri veya gereksiz kullanıcı müdahalesi isteyen durumlar çok değerli.

📧 **raci@yuksekbas.av.tr**

Olumlu veya olumsuz, birkaç cümlelik geri bildirim bile uygulamanın gelişmesine ciddi katkı sağlar.

---

<div align="center">

### ⚖️ Tasnif
**UYAP’tan indirin. Tasnif etsin. Belgeler yerini bulsun.**

</div>
