# TürkOS — Bilge Sürüm v4.2.0

Bu paket, TürkOS tanıtım sitesi ve uygulamasını birlikte içerir.

## Dosyalar
- `index.html`: Tek dosyada çalışan tanıtım sitesi ve gömülü canlı TürkOS önizlemesi.
- `turkos.html`: Ayrı açılabilen TürkOS HTML uygulaması.
- `version.json`: İnternet sitesindeki sürüm kontrolü için.
- `CHANGELOG.md`: Sürüm notları.
- `favicon.svg`: Site simgesi.

## Hemen denemek
1. ZIP dosyasını tamamen bir klasöre çıkart.
2. `index.html` dosyasını Chrome veya Edge ile aç.
3. Canlı TürkOS önizlemesindeki alttaki ☾ Başlat düğmesine bas.
4. Başlat menüsünden bir uygulama seç. Canlı önizleme uygulaması site dosyasının içine gömülüdür; kardeş dosya yolu bulamama sorunu giderildi.
5. İndirme düğmesi tek HTML dosyası oluşturur. Ayrı aç düğmesi uygulamayı yeni sekmede açar.

`turkos.html` dosyası bağımsız uygulama olarak da açılabilir.

## GitHub Pages ile yayınlama
1. GitHub'da `turkos-site` adında Public bir repository oluştur.
2. ZIP içindeki dosyaları repository'nin ana dizinine yükle.
3. Settings → Pages → Deploy from a branch seç.
4. Branch olarak `main`, klasör olarak `/(root)` seçip kaydet.
5. Site adresini aç. Canlı önizleme uygulaması `index.html` içine gömülüdür; `turkos.html` ayrıca indirilebilir.

## Güncelleme
Yeni sürümde `turkos.html` dosyasını değiştir, `version.json` içindeki sürümü ve sürüm notlarını artır; aynı zamanda TürkOS uygulamasındaki `APP_VERSION` sabitini de aynı sürüme getir. `index.html` içindeki gömülü önizlemeyi de yeni `turkos.html` içeriğiyle yeniden üretmek gerekir. Yeni sürüm, kullanıcıya haber verilir; HTML indirmesi kullanıcı tarafından başlatılır.

## Not
TürkOS tarayıcıda çalışan bir masaüstü simülasyonudur. Windows gibi bilgisayara kurulan bağımsız bir işletim sistemi değildir. Veriler tarayıcı yerel depolamasında saklanır; izin yoksa o oturum için bellek yedeği kullanılır.
