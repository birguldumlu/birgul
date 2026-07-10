# Türkiye Elektrikli Araç (EV) Pazarı Duygu Analizi

Bu proje, Türkiye elektrikli araç pazarındaki tüketici algısını, eğilimlerini ve duygu dağılımlarını **Doğal Dil İşleme (NLP)** ve **Metin Madenciliği** yöntemleriyle analiz etmek amacıyla geliştirilmiştir.

## 📊 Veri Kaynakları ve Hacim
Çalışmada toplam **40.000+ benzersiz Türkçe yorum** işlenmiştir. Veriler şu platformlardan derlenmiştir:
- Ekşi Sözlük (Canlı ve Genişletilmiş Veri Havuzları)
- Google Haberler
- Mobil Uygulama Kullanıcı Geri Bildirimleri
- Çeşitli EV Marka ve Model Havuzları (Togg, Tesla, BYD, Chery, Kia, Hyundai, Porsche, BMW, MG, Renault)

## 🛠️ Metodoloji
1. **Veri Temizliği ve Birleştirme:** Çoklu kaynaklardan gelen CSV dosyaları birleştirilmiş, yinelenen veriler ayıklanmıştır.
2. **Otomatik Marka Etiketleme:** Metin içerisindeki anahtar kelimelere göre yorumlar ilgili markalara atanmıştır.
3. **Sözlük Tabanlı Duygu Analizi:** Türkçe pozitif ve negatif kelime sözlükleri (`lexicon`) kullanılarak metinler Pozitif, Negatif ve Nötr olarak sınıflandırılmıştır.

## 📈 Bulgular ve Dağılımlar (Örnek)
*Sosyal medyadaki genel bilgi aktarımı ve haber dilinin baskınlığından ötürü tüm markalarda Nötr oranları %73 - %87 bandında seyretmektedir.*

| Marka | Toplam Veri | Pozitif (%) | Negatif (%) | Nötr (%) |
| :--- | :--- | :--- | :--- | :--- |
| **Togg** | 3441 | %14.0 | %3.3 | %82.7 |
| **Tesla** | 2399 | %9.0 | %3.4 | %87.7 |
| **BYD** | 559 | %14.1 | %3.4 | %82.5 |
| **BMW** | 288 | %12.8 | %3.8 | %83.3 |

## 🚀 Kullanım
Kişisel verilerden arındırılmış veri setine [elektrikli_arac_temiz.csv](elektrikli_arac_temiz.csv) dosyasından erişebilirsiniz.
