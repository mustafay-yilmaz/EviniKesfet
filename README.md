# Evini Keşfet Akıllı Ev Sistemleri

## Proje Konusu
Evini Keşfet Akıllı Ev Sistemleri, güvenlik, konfor ve enerji verimliliği sağlayan bir IoT sistemi geliştirmeyi amaçlamaktadır. Sistem; sensörler ve iletişim modülleri gibi donanım bileşenlerinin yanı sıra, uzaktan kontrol ve izleme için bir mobil uygulama içerecektir.

## Proje Kısa Özeti
Bu proje kapsamında geliştirilecek olan sistem aşağıdaki bileşenleri içerecektir:
- **Akıllı Kapı Erişim Sistemi**: Kapıya yaklaşan kişiyle birlikte kamera aktive olacak, fotoğraf çekilecek ve mobil uygulamaya bildirim gönderilecektir. Kapı, manuel olarak şifre girilerek veya mobil uygulama üzerinden açılabilecektir.
- **Kapı Zili Bildirimi**: Kapı zili çaldığında mobil uygulamaya bildirim gidecektir.
- **Hareket ve Veri Kaydı**: Genel hareketler Firebase veya ThingSpeak'e kaydedilecektir.
- **Akıllı Aydınlatma Sistemi**: Ortam karanlıksa, ışık sensöründen alınan veriye göre aydınlatma otomatik olarak açılacaktır.
- **Ortam İzleme**: Evin iç sıcaklığı mobil uygulama üzerinden izlenebilecek, RGB ışıklar kontrol edilebilecek ve sıcaklık ile sensör verileri grafiksel olarak gösterilecektir.

## Proje Gereksinimleri

### Donanım
- **Arduino/ESP8266/ESP32** (iletişim için)
- **Ultrasonik Sensör** (hareket algılama)
- **LDR** (ışık seviyesi algılama)
- **Mesafe Sensörü** (yakınlık algılama)
- **16x2 LCD** (yerel ekran)
- **Keypad** (şifre girişi)
- **RGB LED** (aydınlatma)
- **Buzzer** (zil)
- **Sıcaklık Sensörü (LM35)**
- **Dirençler**

### Yazılım
- **Mobil Uygulama** (kontrol ve izleme için)
- **Firebase veya ThingSpeak** (veri depolama ve API işlemleri)
- **Arduino IDE** (mikrodenetleyici programlama)
- **Firebase Cloud Messaging** (bildirim gönderme için)

## Projeyi Çalıştırma
1. Tüm sensörler ve iletişim modülleri **Arduino/ESP8266/ESP32**'ye bağlanmalıdır. Bağlantı şemaları ilerleyen aşamalarda repoya eklenecektir.
2. Mobil uygulamanın indirilmesi gerekmektedir (geliştirme aşamasında).

## Proje Lisans Bilgileri
Bu proje, **MIT Lisansı** altında lisanslanmıştır. Detaylar için LICENSE dosyasına bakınız.

## Proje Anahtar Kelimeleri
IoT, Ev Otomasyonu, Güvenlik, Enerji Verimliliği, Mobil Uygulama, Sensörler, Arduino, ESP8266, ESP32, Firebase, ThingSpeak

