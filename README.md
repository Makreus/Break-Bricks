# Break Bricks

Neon tuğla kırma oyunu. Tek sayfa, kurulum gerektirmez; telefona uygulama gibi yüklenir (PWA) ve internetsiz de çalışır.

## GitHub'da yayınlama (5 dakika)

1. github.com'da **New repository** ile yeni bir depo aç (ör. `break-bricks`, Public).
2. Depoda **Add file → Upload files** de, bu klasördeki **tüm dosyaları ve `icons` klasörünü** sürükleyip bırak, **Commit changes**.
3. **Settings → Pages** bölümünde *Source* olarak **Deploy from a branch**, *Branch* olarak **main** ve **/ (root)** seç, **Save**.
4. 1-2 dakika sonra adresin hazır: `https://KULLANICI-ADIN.github.io/break-bricks/`

## Telefona uygulama olarak yükleme

- **Android (Chrome):** adresi aç → ⋮ menü → **Uygulamayı yükle** (veya *Ana ekrana ekle*).
- **iPhone (Safari):** adresi aç → Paylaş düğmesi → **Ana Ekrana Ekle**.

Yüklenince ana ekranda kendi simgesiyle, tam ekran açılır.

## APK (Android uygulama dosyası) isteğe bağlı

Yayınladığın adresi [pwabuilder.com](https://www.pwabuilder.com) sitesine yapıştır → **Package for stores → Android** ile APK/AAB indir.

## Güncelleme

`index.html` dosyasını GitHub'da değiştirdikten sonra `sw.js` içindeki `CACHE` sürümünü artır (`break-bricks-v1` → `v2`), böylece telefonlar yeni sürümü alır.

## Dosyalar

- `index.html` – oyunun kendisi
- `manifest.webmanifest` – uygulama adı, simge, tam ekran ayarları
- `sw.js` – çevrimdışı önbellek
- `icons/` – uygulama simgeleri
