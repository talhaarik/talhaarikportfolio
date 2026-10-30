# Talha Arık — Portfolio

Responsive personal portfolio. HTML, CSS and JavaScript; no build step or API key required.

## GitHub’a yükleme
1. ZIP’i bilgisayarında çıkart.
2. GitHub reponda **uploading an existing file** veya **Add file → Upload files** seç.
3. Bu klasörün **içindekileri** yükle: index.html, styles.css, script.js, assets/, vercel.json ve README.md. ZIP dosyasını doğrudan yükleme.
4. **Commit changes** seç. Repo kökünde index.html görünmeli.

## Vercel
GitHub reposunu Import Project ile seç.
- Project Name: talhaarik (müsaitse)
- Framework Preset: Other
- Root Directory: ./
- Build Command: boş bırak
- Output Directory: .
- Environment variables: gerekmiyor

## Lokal önizleme
Dosyayı doğrudan çift tıklamak yerine klasörde bir statik sunucu aç:

```bash
python -m http.server 3000
```

Ardından http://localhost:3000 adresine gir.

## Dahil olanlar
- Masaüstü scroll animasyonlu 3D proje çarkı
- Mobil sağ/sol kaydırma ve senkronize proje açıklamaları
- Scroll ile gündüz/gece değişen pixel oda ve tüm görseller
- Pixel karakterler, konuşma balonları, logolar ve proje kapakları
- Responsive stiller, sosyal hesap bağlantıları, reduced-motion desteği

## İletişim formu
Form, ziyaretçinin e-posta uygulamasında önceden doldurulmuş bir taslak açar. Sunucudan otomatik e-posta gönderimi yoktur. Alıcı: talhaarikyatirim@gmail.com.

## Fontlar
Bricolage Grotesque, Instrument Sans ve IBM Plex Mono mevcut Google Fonts bağlantısından yüklenir. İnternet olmadan sistem fontları kullanılır.

## Düzenleme
Metinler ve yapı: index.html. Deneyimler, projeler ve etkileşimler: script.js. Tasarım ve responsive kurallar: styles.css. Görseller: assets/.
