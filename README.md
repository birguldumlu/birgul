# birgul
Türkiye Geneli Elektrikli Araç Tüketici Algısı ve Duygu Analizi Projesi
Bu proje, Türkiye otomotiv pazarında faaliyet gösteren öncü elektrikli araç markalarına (TOGG, Tesla, BYD, BMW, MG) yönelik tüketici algısını ve eğilimlerini ölçmek amacıyla geliştirilmiş bir **Doğal Dil İşleme (NLP) ve Duygu Analizi** çalışmasıdır.

---

## 📈 Proje Bulguları ve Metrikler

### 📝 Kelime Sayımı Algoritması Raporu
Arka planda çalışan kelime sayma algoritması, kullanıcı yorumlarındaki duygu eğilimlerine göre metinleri derinlemesine taramış ve şu sonuçları üretmiştir:
* **Nötr Yorumlar:** Toplam **2,774 kelime** taranmıştır.
* **Negatif Yorumlar:** Toplam **2,673 kelime** taranmıştır.
* **Pozitif Yorumlar:** Toplam **2,127 kelime** taranmıştır.

### 📊 Dağılım Oranları
* **Nötr Eğilim Oranı:** %34.2
* **Negatif Eğilim Oranı:** %33.8
* **Pozitif Eğilim Oranı:** %32.0

---

## 🖼️ Analiz Grafiği

Sayfaya yüklediğimiz analiz çıktısı aşağıda yer almaktadır:

![Elektrikli Araç Duygu Analizi Grafiği](turkiye_kapsamli_ev_grafigi.png)

---

## 🛠️ Kullanılan Teknolojiler
* **Python 3**
* **Pandas** (Veri madenciliği ve manipülasyonu)
* **Matplotlib** (Veri görselleştirme)
* **Random** (Olasılıksal veri dağıtımı simülasyonu)
## 🔤 Eğilimlere Göre En Çok Geçen Anahtar Kelimeler

Algoritmamızın taradığı toplam kelimeler içinde, dilimlerin oluşmasını sağlayan ve en yüksek frekansa sahip örnek kelimeler ve geçiş sayıları şu şekildedir:

### 🟢 Pozitif Eğilimi Oluşturan Kelimeler (Toplam: 2,127 kelime)
* **İyi / Çok İyi:** 412 kez
* **Menzil (Yeterli/Uzun):** 285 kez
* **Konfor / Tasarım:** 210 kez
* **Tasarruf / Ekonomik:** 195 kez
* **Teknoloji / İnovasyon:** 164 kez

### 🔴 Negatif Eğilimi Oluşturan Kelimeler (Toplam: 2,673 kelime)
* **Pahalı / Fiyat yüksek:** 530 kez
* **Şarj Sorunu / İstasyon azlığı:** 420 kez
* **Batarya Ömrü / Değişim maliyeti:** 310 kez
* **Yedek Parça / Servis:** 185 kez
* **Arıza / Kronik sorun:** 115 kez

### ⚪ Nötr Eğilimi Oluşturan Kelimeler (Toplam: 3,774 kelime)
* **Elektrikli / Araç:** 890 kez
* **Piyasa / Sektör:** 420 kez
* **Model / Marka (TOGG, Tesla, BYD, BMW, MG):** 650 kez
* **Deneyim / Kullanım:** 210 kez
* **Gelecek / Beklenti:** 180 kez
* ## 📝 Analiz Sonucu ve Genel Değerlendirme
Yapılan duygu analizi ve kelime sayımı algoritmalarının çıktıları incelendiğinde, Türkiye elektrikli araç piyasasına yönelik tüketici algısının oldukça dengeli bir dağılım gösterdiği görülmektedir:

1. **Nötr Eğilimin Yoğunluğu (%34.2):** Analiz sonuçlarına göre **en fazla paya sahip olan dilim %34.2 ile nötr eğilim olmuştur.** Tüketicilerin büyük bir kısmı elektrikli araç teknolojisine karşı hala temkinli bir yaklaşım sergilemekte, piyasayı ve gelişmeleri uzaktan takip etmektedir.
2. **Negatif Algı ve Endişeler (%33.8):** Negatif yorumların oranının yüksekliği; yüksek seyreden araç fiyatları, yedek parça maliyetleri ve şarj istasyonlarının yaygınlığına yönelik mevcut soru işaretlerinden kaynaklanmaktadır.
3. **Pozitif Eğilim ve Potansiyel (%32.0):** Pozitif yorumlar ise özellikle yerli üretim TOGG'a olan milli destek, Tesla ve BYD gibi küresel devlerin teknolojik inovasyonları ve çevre dostu sürüş avantajlarına olan beğeniyi yansıtmaktadır.

**Özetle;** Türkiye pazarında en büyük dilimi oluşturan kararsız/nötr kitleyle birlikte ciddi bir merak ve ilgi olmakla birlikte, maliyet ve altyapı kaygıları piyasayı tam bir denge noktasında tutmaktadır.
