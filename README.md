# YEC® — Yunus Can Portfolio

İstanbul merkezli multidisipliner grafik tasarımcı **Yunus Can**'ın kişisel portfolyo sitesi.

`index.html` + `assets/` klasörü — kütüphane yok, kurulum yok. Tüm görseller
projenin içinde: dış servislere bağımlılık yok. ⚡

## Özellikler

- 🪐 **YEC Güneş Sistemi:** 3D krom YEC etrafında yörüngelerde dönen 18 proje (saf CSS 3D)
- 🃏 **Kağıt destesi galerileri:** Projeye gir, kağıda tıkla ya da kaydır — görseller
  deste gibi savrulup değişir (IKSV 37, Game Force 21, Osmanlı Destesi 12 görsel...)
- 🌌 Yıldız alanı, kayan yıldızlar, yörünge halkaları ve mini gezegenler
- 📱 Telefonda sağa/sola kaydırarak görsel ve proje gezintisi, iki parmakla zoom
- 🎬 Açılışta işlerin hızlı geçidi, Rings/Spiral dizilim, süzülen kağıt animasyonları

## GitHub'a Yükleme

1. Reponu aç → **Add file → Upload files**
2. Bu klasördeki **index.html**, **README.md** dosyalarını VE **assets** klasörünü
   olduğu gibi pencereye **sürükle-bırak** (Chrome klasör sürüklemeyi destekler —
   assets içindeki 117 görsel otomatik gelir)
3. **Commit changes** → 1-2 dakikada canlı

> Eski `index.html` üzerine yazılır; `assets` klasörü yoksa oluşturulur.

## Özelleştirme

- **Projeler:** `index.html` içindeki `PROJECTS` dizisi (başlık, kategori, not,
  Behance linki, `g:G('klasör',adet)` galeri tanımı)
- **Görsel ekleme:** `assets/<proje>/` içine `NN.jpg` at, `G('proje', yeniAdet)` yap
- **Renkler:** üstteki `:root` değişkenleri

## Not

- **Perfume** projesinin görseli arşivde bulunmadığı için şimdilik Behance'ten
  yükleniyor — orijinal dosya eklendiğinde yerelleştirilebilir.

---
© 2026 Yunus Can — Tüm hakları saklıdır.
