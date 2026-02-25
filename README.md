# Yerel Dosya Önizleyici

Firefox, Chrome ve Edge tarayıcılarında yerel dosyaları/dizinleri önizlemenizi sağlayan bir web arayüzü.
⚠️ **Not:** Şu anda sadece Firefox'ta tam performansla çalışmaktadır.

![Preview Screenshot](Ekran_görüntüsü_2025-03-18_08-52-58.png?text=Önizleyici+Ekran+Görüntüsü)

## Özellikler

- 📂 Klasör seçme ve dosya listeleme
- 🖼️ Metin dosyalarını ve görüntüleri tarayıcıda görüntüleme
- 🌓 Açık/Koyu tema desteği
- 🇹🇷/🇬🇧 Çoklu dil desteği (Türkçe/İngilizce)
- 📊 CSV tablolarını otomatik formatlama
- ⏲️ Önizleme süresini özelleştirme
- 🔀 Karışık ve döngüsel oynatma modları

## Kurulum

1. Bu repo'yu klonlayın veya `preview.html` dosyasını indirin
2. Dosyayı bir web tarayıcısında açın (Firefox önerilir)
3. "Klasör Seç" butonuyla bir dizin seçin

## Kullanım

- **Dil Değiştirme:** Sağ üstteki bayrak butonlarıyla Türkçe/İngilizce arasında geçiş yapın
- **Tema Değiştirme:** Ay simgesiyle açık/koyu temayı değiştirin
- **Dosya Yönetimi:**
  - Sol panelde dosyaları tıklayarak önizleme
  - Sağ üstteki "ℹ️" butonuyla bağış bilgilerini görüntüleme
  - Sayısal tuşlarla hızlı geçiş yapabilme

## Katkıda Bulunma

Geliştiriciler için önerilen iyileştirmeler:
1. **Çoklu Dil Desteği Genişletme:**
   - `turkishcontent` ve `englishcontent` özelliklerini kullanarak yeni diller ekleyin
   - `switchLanguage()` fonksiyonunu genişleterek dil seçeneklerini artırın

2. **Tarayıcı Uyumluluğu:**
   - Chrome/Edge için `webkitdirectory` özelliğini optimize edin
   - Dosya okuma API'larında tarayıcı farklılıklarını yönetin

3. **Gelişmiş Önizleme:**
   - PDF görüntüleyici entegrasyonu
   - Medya oynatıcı desteği (video/audio)

## Bilinen Sorunlar

- 🚫 Chrome/Edge'de bazı dosyalar indiriliyor (güvenlik kısıtlamaları)
- 🐞 Büyük dosyalarda performans düşüşü
- 🌍 Bazı karakter kodlamalarında görüntüleme sorunları

## Lisans

Bu proje [Özel Lisans] ile lisanslanmıştır. Bağış yapmak için [Bağış Bağlantısı](https://ppr.ist/1T9dx8tUT) kullanabilirsiniz.

---

**Not:** Bu dosya yerel dosya sistemi API'larını kullanır. Tarayıcı izinlerini yönetmek için ayarlarınızı kontrol edin.

## ☕ Destek Olun / Support

Projemi beğendiyseniz, bana bir kahve ısmarlayarak destek olabilirsiniz!

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://buymeacoffee.com/metatronslove)

Teşekkürler! 🙏
