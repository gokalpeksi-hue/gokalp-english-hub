# Gökalp English Hub

İngilizce çalışma uygulamalarının en son yedeklerini tek çatı altında toplayan hub.

**Canlı adres:** https://gokalpeksi-hue.github.io/gokalp-english-hub/

## İçerik

| Uygulama | Klasör | Kaynak repo | Yedek tarihi |
|---|---|---|---|
| MyDictionary (İngilizce sözlük & cümle kartları) | `kelime-karti/` | [kelime-karti-app](https://github.com/gokalpeksi-hue/kelime-karti-app) | 18.09.2026 |
| English Studio (kelime kartları) | `english-studio/` | [english-studio](https://github.com/gokalpeksi-hue/english-studio) | 12.09.2026 |
| EZBER (arşiv sürüm) | `ezber/` | [EZBER](https://github.com/gokalpeksi-hue/EZBER) | 29.06.2026 |

## Yedekleme

Hub açılış sayfasında **⬇️ Yedek al (.json)** ve **⬆️ Yedekten yükle** butonları vardır.
Uygulamaların tümü veriyi tarayıcının `localStorage`'ında tuttuğu ve GitHub Pages'te
aynı origin'i paylaştığı için hub, bu tarayıcıdaki bütün uygulama verilerini
(MyDictionary kartları, English Studio listesi/konumu, EZBER kayıtları) tek JSON
dosyasında dışa aktarır ve başka cihazda/tarayıcıda geri yükler.

## Güvenlik notu

Bu repo yalnızca **kopyaları** barındırır. Orijinal repolar ve masaüstündeki eski
klasörler değiştirilmemiştir; oradaki uygulamalar eskisi gibi çalışmaya devam eder.
Yeni bir yedek almak için ilgili alt klasörün içeriğini kaynak reponun güncel
haliyle değiştirip commit atmak yeterlidir.
