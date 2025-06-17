# Evini Keşfet Akıllı Ev Sistemleri

## Proje Konusu
Evini Keşfet Akıllı Ev Sistemleri, güvenlik, konfor ve enerji verimliliği sağlayan bir IoT sistemi geliştirmeyi amaçlamaktadır. Sistem; sensörler ve iletişim modülleri gibi donanım bileşenlerinin yanı sıra, uzaktan kontrol ve izleme için bir mobil uygulama içerecektir.

## Proje Kısa Özeti
Bu proje kapsamında geliştirilecek olan sistem aşağıdaki bileşenleri içerecektir:
- **Akıllı Kapı Erişim Sistemi**: Kapıya yaklaşan kişiyle birlikte kamera aktive olacak, fotoğraf çekilecek ve mobil uygulamaya bildirim gönderilecektir. Kapı, manuel olarak şifre girilerek veya mobil uygulama üzerinden açılabilecektir.
- **Kapı Zili Bildirimi**: Kapı zili çaldığında mobil uygulamaya bildirim gidecektir.
- **Hareket ve Veri Kaydı**: Genel sensör verileri Firebase veya ThingSpeak'e kaydedilecektir.
- **Akıllı Aydınlatma Sistemi**: Ortam karanlıksa, ışık sensöründen alınan veriye göre aydınlatma otomatik olarak açılacaktır.
- **Ortam İzleme**: Evin iç sıcaklığı mobil uygulama üzerinden izlenebilecek, RGB ışıklar kontrol edilebilecek ve sıcaklık ile sensör verileri grafiksel olarak gösterilecektir.

## Proje Gereksinimleri

### Donanım

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


### Yazılım
- **Mobil Uygulama** (kontrol ve izleme için)
- **Firebase veya ThingSpeak** (veri depolama ve API işlemleri)
- **Arduino IDE** (mikrodenetleyici programlama)
- **Firebase Cloud Messaging** (bildirim gönderme için)

## Projeyi Çalıştırma
1. Tüm sensörler ve iletişim modülleri **Arduino/ESP8266/ESP32**'ye bağlanmalıdır. Bağlantı şemaları ilerleyen aşamalarda repoya eklenecektir.
2. Mobil uygulamanın indirilmesi gerekmektedir (geliştirme aşamasında).

## Proje Lisans Bilgileri
Bu proje, **MIT Lisansı** altında lisanslanmıştır. Detaylar için [LICENSE](https://github.com/Emir-Karaman/EviniKesfet/blob/main/LICENSE) dosyasına bakınız.

## Proje Anahtar Kelimeleri
IoT, Ev Otomasyonu, Güvenlik, Enerji Verimliliği, Mobil Uygulama, Sensörler, Arduino, ESP8266, ESP32, Firebase, ThingSpeak
