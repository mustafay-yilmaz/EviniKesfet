# IoT Dönem Projesi Öneri Raporu: Evini Keşfet Akıllı Ev Sistemleri

## Grup 4
**Emir Karaman, Furkan Yaylaz, Metehan Sözenli, Mustafa Yüksel Yılmaz**

## 1. Proje Konusu
Bu projenin amacı, güvenlik, konfor ve enerji verimliliği sağlayan entegre bir IoT sistemi geliştirmektir. Sistem, sensörler, motorlar ve iletişim modülleri gibi donanım bileşenlerinin yanı sıra uzaktan kontrol ve izleme için bir mobil uygulama içerecektir.

## 2. Proje Hedefleri
- Ev güvenliğini artırmak için akıllı kapı erişim sistemi oluşturmak.
- Enerji tasarrufu sağlamak amacıyla ortam aydınlatmasını optimize etmek.
- Mobil uygulama ile sistemin kontrolünü sağlamak.
- Hareket ve sıcaklık verilerini kaydederek analiz edilebilir hale getirmek.

## 3. Tahmini Zaman Çizelgesi
| Görev | Süre |
|--------|------|
| Donanım seçimi ve entegrasyonu | 2 hafta |
| Sensör ve mikrodenetleyici programlaması | 2 hafta |
| Mobil uygulama geliştirme | 3 hafta |
| Veri depolama ve analiz entegrasyonu | 1 hafta |
| Testler, Son kontroller ve teslimat| 1 hafta |

## 4. Kaynak Planlaması
### Ekip Üyeleri ve Görev Dağılımı
- **Emir Karaman**: Donanım tasarımı ve entegrasyonu
- **Furkan Yaylaz**: Mikrodenetleyici programlaması
- **Metehan Sözenli**: Veri yönetimi ve analiz
- **Mustafa Yüksel Yılmaz**: Mobil uygulama geliştirme

### Kullanılacak Ekipmanlar
| Ekipman | Görsel |
|--------|------|
| Arduino/ESP8266/ESP32 (İletişim) | <img src="https://github.com/metehansozenli/EviniKesfet/blob/main/Öneri%20Raporu/Figure/Esp32-Arduino.png" width="200"> |
| Ultrasonik Sensör (HC-SR04) | <img src="https://github.com/metehansozenli/EviniKesfet/blob/main/Öneri%20Raporu/Figure/HC-SR04.png" width="200"> |
| Fotodirenç (LDR) | <img src="https://github.com/metehansozenli/EviniKesfet/blob/main/Öneri%20Raporu/Figure/LDR.png" width="200"> |
| Hareket Algılama Sensörü (PIR)| <img src="https://github.com/metehansozenli/EviniKesfet/blob/main/Öneri%20Raporu/Figure/PIR.png" width="200"> |
| 16x2 LCD (Yerel ekran) | <img src="https://github.com/metehansozenli/EviniKesfet/blob/main/Öneri%20Raporu/Figure/LCD.png" width="200"> |
| Keypad (Şifre girişi) | <img src="https://github.com/metehansozenli/EviniKesfet/blob/main/Öneri%20Raporu/Figure/Keypad.jpg" width="200"> |
| RGB LED (Aydınlatma) | <img src="https://github.com/metehansozenli/EviniKesfet/blob/main/Öneri%20Raporu/Figure/RGB.png" width="200"> |
| Buzzer (Zil) | <img src="https://github.com/metehansozenli/EviniKesfet/blob/main/Öneri%20Raporu/Figure/Buzzer.jpg" width="200"> |
| Sıcaklık Sensörü (LM35) | <img src="https://github.com/metehansozenli/EviniKesfet/blob/main/Öneri%20Raporu/Figure/LM35.jpg" width="200"> |
| Dirençler ve bağlantı elemanları | <img src="https://github.com/metehansozenli/EviniKesfet/blob/main/Öneri%20Raporu/Figure/BaglantiElemanlari.png" width="200"> |

### Kullanılacak Yazılımlar
- **Flutter**: Mobil uygulama geliştirme
- **Firebase/ThingSpeak**: Veri depolama ve API işlemleri
- **Arduino IDE**: Mikrodenetleyici programlama

## 5. Risk Analizi
| Risk | Çözüm Önerisi |
|------|--------------|
| Donanım uyumsuzluğu | Alternatif bileşenler belirlemek |
| Bağlantı sorunları | Wi-Fi ve Bluetooth yedekleme mekanizması sağlamak |
| Veri güvenliği riski | Şifreleme ve güvenlik önlemleri almak |
| Gecikmeli veri aktarımı | Optimize edilmiş algoritmalar ve veri sıkıştırma kullanmak |

## 6. Ticari Potansiyel
Bu sistem, ev otomasyonu ve güvenlik sektörlerinde kullanılabilir. Potansiyel müşteriler arasında bireysel ev sahipleri, apartman yönetimleri ve akıllı bina sistemleri geliştiricileri bulunmaktadır.


## Contributors

* **Emir Karaman** - [EmirKaraman](https://github.com/Emir-Karaman)
* **Furkan Yaylaz** - [FurkanYaylaz](https://github.com/furkanyaylaz)
* **Metehan Sözenli** - [MetehanSözenli](https://github.com/metehansozenli)
* **Mustafa Yüksel Yılmaz** - [MustafaYükselYılmaz](https://github.com/mustafay-yilmaz)

