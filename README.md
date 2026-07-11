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
![Genel Duygu Dağılımı](https://raw.githubusercontent.com/birguldumlu/birgul/main/genel-duygu-dagilimi.png)

*Sosyal medyadaki genel bilgi aktarımı ve haber dilinin baskınlığından ötürü tüm markalarda Nötr oranları %73 - %87 bandında seyretmektedir.*
| Marka | Toplam Veri | Pozitif (%) | Negatif (%) | Nötr (%) |
| :--- | :--- | :--- | :--- | :--- |
| **Togg** | 3430 | %14.5 | %3.3 | %82.2 |
| **Tesla** | 2840 | %11.3 | %4.0 | %84.7 |
| **BYD** | 754 | %15.9 | %5.4 | %78.6 |
| **BMW** | 376 | %14.9 | %3.7 | %81.4 |

## 🚀 Kullanım
Kişisel verilerden arındırılmış veri setine [elektrikli_arac_temiz.csv](elektrikli_arac_temiz.csv) dosyasından erişebilirsiniz.
