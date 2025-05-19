# Shell SEO Nedir?

**Shell SEO**, arama motorları tarafından taranan ancak kullanıcılar için görünmeyen sahte veya düşük kaliteli içerik sunma yöntemidir. Genellikle JavaScript tabanlı sitelerde, sunucu tarafında (server-side) özel olarak arama motorlarına yönelik bir sayfa sunulurken, gerçek kullanıcıya farklı veya zayıf içerikli bir sayfa gösterilir.

Bu durum **"Cloaking"** (örtme/gizleme) olarak da adlandırılır ve arama motoru yönergelerine aykırıdır.

---

## Shell SEO Nasıl Çalışır?

Shell SEO, genellikle şu yöntemlerle uygulanır:

- Kullanıcı **tarayıcı** üzerinden siteye girdiğinde sade bir sayfa görür.
- Arama motoru **botları**, özel olarak hazırlanmış ve anahtar kelimelerle dolu sayfayı görür.
- Bu farklı içerikler sayesinde arama sonuçlarında üst sıralara çıkma hedeflenir.

Bu teknik, arama motorlarını manipüle etmeyi amaçladığı için **Black Hat SEO** kategorisine girer.

---

## Shell SEO Kullanımına Örnek

Örnek bir senaryo:

1. Googlebot siteyi ziyaret eder:
    - Bot'a, yüzlerce anahtar kelime barındıran, optimize edilmiş bir HTML sayfa gösterilir.

2. Gerçek kullanıcı aynı sayfaya gider:
    - JavaScript ile oluşturulmuş, neredeyse boş veya çok sade bir sayfa görür.

```html
<!-- Arama motoru için -->
<html>
  <head><title>UCUZ Ayakkabılar | En İyi Fiyatlar</title></head>
  <body>
    <h1>En Ucuz Ayakkabılar</h1>
    <p>Adidas, Nike, Puma %50 indirimli...</p>
  </body>
</html>
<!-- Kullanıcıya gösterilen sayfa -->
<html>
  <head><title>Home</title></head>
  <body>
    <script src="app.js"></script>
  </body>
</html>
