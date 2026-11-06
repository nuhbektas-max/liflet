# 🍐 Liflet Stüdyosu

Tarım lifletleri ve broşürleri için tarayıcıda çalışan, kurulum gerektirmeyen düzenleme programı.
Ankara İl Tarım ve Orman Müdürlüğü için hazırlanmıştır.

## Kullanım

1. `index.html` dosyasını indirin.
2. Çift tıklayıp **Chrome** veya **Edge** ile açın.
3. İnternet bağlantısı gerekmez; yazı tipleri ve PDF araçları dosyanın içindedir.

## Özellikler

- **Şablonlar ve formatlar:** A4 üç kırım, iki kırım, A4 tek yaprak, A5, büyük yazı (4 sayfa), cep kartı
- **23 hazır taslak:** Armut, Elma, Kayısı, Vişne, Kiraz, Ceviz, Üzüm, Buğday, Arpa, Nohut, Mercimek, Kuru Fasulye, Ayçiçeği, Şeker Pancarı, Patates, Domates, Soğan; Toprak Analizi, Damla Sulama, Zirai Don, Anız Yakmayın, İyi Tarım Uygulamaları, Arıcılık
- **Metinden otomatik tasarım:** Word (.docx), .txt veya .md dosyası yükleyin; başlık, liste, tablo, bilgi kutusu, bakım takvimi ve iletişim otomatik tanınır, panellere dengeli yerleştirilir
- **Tasarım danışmanı:** kontrast, yazı boyutu, fotoğraf çözünürlüğü, yazım tutarlılığı, uzman onayı, taşma payı denetimi
- **Dışa aktarma:** vektörel PDF, matbaa PDF'i (taşma payı + kesim işaretleri), PNG, Word (düzenlenebilir / birebir görünüm), WhatsApp–Instagram görselleri, Instagram kaydırmalı seri, toplu PDF + Word (ZIP)
- **Kurum ayarları:** logo, iletişim, QR kod, künye, kurumsal kimlik kilidi
- **Diğer:** 50 tarım ikonu, 12 aylık renkli bakım takvimi, fotoğraf kütüphanesi, kırpma odağı, katlanmış 3B önizleme

## Klasörler

| Klasör | İçerik |
|---|---|
| `index.html` | Programın kendisi (tek dosya) |
| `taslaklar/` | 23 taslağın ve ana metin şablonunun Word (.docx) ve metin (.txt) hâlleri; düzenleyip programa yükleyebilirsiniz |
| `yazi-tipleri/` | Montserrat ve Open Sans; Word çıktılarının tasarımdaki gibi görünmesi için bilgisayara kurun (bkz. `KURULUM.txt`) |

## Önemli

Taslaklardaki teknik bilgiler genel tarım bilgisine dayanır ve bölgeye özel resmi önerilerle karşılaştırılmamıştır.
Yayımlamadan önce Müdürlüğün ziraat mühendislerine kontrol ettirilmelidir.

## Lisanslar

- Yazı tipleri (Montserrat, Open Sans, Roboto, Merriweather): SIL Open Font License 1.1
- html2canvas, jsPDF, qrcode-generator: MIT
