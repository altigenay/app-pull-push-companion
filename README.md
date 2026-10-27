# Pull&Push Yardımcı

**App Pull&Push**'ın cihaza kurduğu küçük (~70 KB) dosya yöneticisi. Telefon, tablet ve Android TV / Google TV / Fire TV'de çalışır.

| Sürüm | Dosya | Nerede |
|---|---|---|
| Telefon / tablet | `yardimci-phone.apk` | Dokunmatik, tek panel (geniş ekranda iki panel) |
| TV | `yardimci-tv.apk` | Kumanda (yön tuşları) ile, iki panel yan yana, TV uygulama satırında görünür |

Her sürümde `latest.json` bulunur: sürüm, dosya adları, SHA-256 özetleri ve boyutlar. App Pull&Push indirdiği APK'yı kurmadan önce bu özetle karşılaştırır.

## Ne yapar

- Dosyaları gezme, kopyalama, taşıma, silme, yeniden adlandırma, yeni klasör, zip oluşturma ve açma, arama, sıralama, gizli dosyalar.
- Dosyayı başka uygulamayla açma, paylaşma, APK kurma; dahili depolama, SD kart ve USB bellekler.
- App Pull&Push bağlıyken ona ADB üzerinden uygulama adlarını, simgelerini (cihazın kendisi çizer), pil, depolama ve bellek bilgisini verir. Bu kanala yalnızca ADB bağlanabilir; cihazdaki diğer uygulamalar kullanamaz.
- İzinleri (tüm dosyalara erişim, APK kurma, kullanım erişimi...) App Pull&Push kurulumdan hemen sonra ADB ile verir.

Reklam, izleyici ya da internet bağlantısı yoktur.

Kurulum App Pull&Push'ın **Yardımcı uygulama** ekranından yapılır; APK'lar elle de kurulabilir.
