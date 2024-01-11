**Proje Adı:** **Aydınlatma, Hareket ve Mesafe Sensörü**

**Proje Açıklaması:**

Bu proje, bir STM32F4 mikrodenetleyiciyi kullanarak ışık yoğunluğunu, hareketi ve mesafeyi ölçen bir sistem uygular. Sistem, bir ADC, bir PIR sensörü ve bir ultrasonik sensör kullanır.

**Proje Özellikleri:**

* Işık yoğunluğunu 2900 lüksün altındaysa LED'i aydınlatır ve zili kapatır.
* Hareket algılanırsa zili açar ve LED rengini değiştirir.
* Mesafeye göre zil frekansını ayarlar.

**Kod Yapısı:**

* **Başlangıç:**
    * Periferleri yapılandırır (ADC, I2C, zamanlayıcılar, USART, LCD).
* **Ana Döngü:**
    * Sensör değerlerini sürekli olarak okur.
    * Sensör okumalarına göre zil ve LED'i kontrol eder.
    * LCD ekranını günceller.

**Kod Açıklığı:**

* Yorumlar ve açıklayıcı değişken adları eklenmiştir.

**Kod Modülerliği:**

* Kod, işlevlere bölünmüştür.

**Kod Verimliliği:**

* Sensör okuma ve ekran güncelleme döngüleri optimize edilmiştir.

**Ek İçgörüler:**

* Kesmeler, sensör işleme ve yanıt verme için kullanılabilir.
* Veri kaydı veya iletişimi, daha fazla analiz ve kontrol için kullanılabilir.
* Kullanıcı giriş mekanizmaları, yapılandırma veya etkileşim için kullanılabilir.

**Gerekli Donanım:**

* STM32F4 mikrodenetleyici
* ADC sensörü
* PIR sensörü
* Ultrasonik sensör
* LCD ekran

**Gerekli Yazılım:**

* STM32CubeIDE

**Ders:**

* Mikrodenetleyiciler
