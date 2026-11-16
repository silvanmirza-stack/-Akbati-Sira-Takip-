AKBATI TAKSİ SESLİ SIRA TAKİP - ANDROID PROJE KAYNAĞI

Hedef cihaz: Redmi Note 14 Pro Plus
İşlev: Ekrandaki 1-30 arasındaki tam sayı metinlerinden soldaki en küçük x koordinatlı numarayı okur. Son kaydedilen sayıdan küçük olduğunda Türkçe TTS ile “Sıranız azaldı. [sayı]” anonsu yapar.

KULLANIM
1) Android Studio'da bu klasörü açın.
2) Gradle senkronizasyonunu tamamlayın.
3) Build > Build Bundle(s) / APK(s) > Build APK(s) ile APK oluşturun.
4) Telefona yükleyin.
5) Uygulamayı açın, “1. EKRAN OKUMA İZNİNİ AÇ” düğmesine basın.
6) Erişilebilirlik listesinden “Akbatı sıra okuyucu” hizmetini etkinleştirin.
7) Uygulamaya dönüp “TAKİBİ BAŞLAT” deyin ve Akbatı sıra ekranına geçin.

ÖNEMLİ
- Bu kaynak proje henüz derlenmiş APK değildir.
- Ekran uygulamasının sıra numarasını erişilebilir metin olarak sunması gerekir. Eğer numara yalnızca resim olarak çiziliyorsa OCR tabanlı farklı bir yöntem gerekir.
- Şu an soldaki 1-30 arası sayısal metni seçer; gerçek Akbatı ekranında test edilmeden doğru hedef alanı okuduğu garanti edilemez.
- Erişilebilirlik izni ekran içeriğini okumaya yetki verir; yalnızca sıra takibi amacıyla kullanılır. Takip kapatıldığında anons üretmez.
