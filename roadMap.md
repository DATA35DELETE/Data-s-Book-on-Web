# Data's Book on Web
 
## HTML
 
### Ön Söz
- Ben kimim?
- Bu Data's Book on Web nedir?
- Bu dokümantasyon ne öğretecek?
 
---
 
### HTML : Giriş
- **Web Nedir?**
  - **İnternet ve Web Farkı**: İnternet altyapı, Web ise üzerinde çalışan bir servis. Tanım.
  - **İstemci-Sunucu Modeli (Client-Server)**: Tarayıcı nedir? Sunucu nedir? İstek-Yanıt döngüsü. Tanım.
  - **URL Yapısı**: Protokol. Domain. Port. Path. Query String. Fragment. Örnek.
  - **HTTP ve HTTPS**: Tanım. Farkları. SSL/TLS. Durum Kodları (200, 301, 404, 500). Örnek.
- **HTML Nedir?**
  - **Kısa Tarihçesi**: Tim Berners-Lee. HTML1'den HTML5'e.
  - **Markup Language Kavramı**: Programlama Dili mi? İşaretleme Dili mi? Tanım.
  - **HTML'in Rolü**: Yapı. CSS ile Farkı. JS ile Farkı.
  - **HTML Standartları**: W3C. WHATWG. HTML5. Tanım.
- **Geliştirme Ortamı Kurma**
  - **Metin Editörü Seçimi**: VS Code. Tanım. Eklenti Önerileri. Örnek.
  - **Tarayıcı ve DevTools**: Chrome DevTools. Elements Paneli. Console. Network. Tanım. Örnek.
  - **Live Server**: Tanım. Kurulum. Kullanım. Örnek.
- **İlk HTML Dosyası**: Tanım. `.html` Uzantısı. Örnek.
  - **`<!DOCTYPE html>`**: Tanım. Neden Gerekli? Quirks Mode. Örnek.
  - **`<html>` Etiketi**: Tanım. `lang` Attribute. Örnek.
  - **`<head>` ve `<body>`**: Tanım. Farkları. Örnek.
  - **`<meta charset="UTF-8">`**: Karakter Kodlama. Tanım. Neden Önemli? Örnek.
  - **`<title>` Etiketi**: Tanım. SEO Önemi. Örnek.
- **Etiket (Tag) Kavramı**: Tanım. Açılış ve Kapanış Etiketleri. Self-Closing. Attribute. Örnek.
  - **Attribute Nedir?**: Tanım. `id`, `class`, `style`, `title`. Örnek.
  - **Global Attribute'lar**: `id`, `class`, `style`, `title`, `hidden`, `data-*`, `tabindex`, `lang`, `dir`. Tablo Halinde.
  - **Boolean Attribute'lar**: Tanım. `disabled`, `checked`, `readonly`, `required`. Örnek.
 
---
 
### HTML : Temel Etiketler
- **Başlık Etiketleri (Headings)**: `<h1>` — `<h6>`. Tanım. Hiyerarşi. SEO Önemi. Örnek.
- **Paragraf**: `<p>`. Tanım. Örnek.
- **Satır Atlatma ve Yatay Çizgi**: `<br>`. `<hr>`. Self-Closing. Tanım. Örnek.
- **Metin Biçimlendirme**
  - **`<b>` ve `<strong>`**: Kalın. Semantik Fark. Tanım. Örnek.
  - **`<i>` ve `<em>`**: İtalik. Semantik Fark. Tanım. Örnek.
  - **`<u>` ve `<ins>`**: Altı Çizili. Tanım. Örnek.
  - **`<s>` ve `<del>`**: Üstü Çizili. Tanım. Örnek.
  - **`<mark>`**: Vurgulama. Tanım. Örnek.
  - **`<small>`**: Küçük Metin. Tanım. Örnek.
  - **`<sub>` ve `<sup>`**: Alt Simge ve Üst Simge. Tanım. Örnek.
  - **`<abbr>`**: Kısaltma. `title` Attribute. Tanım. Örnek.
  - **`<blockquote>` ve `<q>`**: Alıntı. `cite` Attribute. Tanım. Örnek.
  - **`<code>`, `<pre>`, `<kbd>`, `<samp>`, `<var>`**: Kod ve Teknik Metin. Tanım. Örnek.
- **Bağlantılar (Links)**
  - **`<a>` Etiketi**: Tanım. `href` Attribute. Örnek.
  - **Dahili ve Harici Bağlantılar**: Tanım. Farkları. Örnek.
  - **`target` Attribute**: `_self`, `_blank`, `_parent`, `_top`. Tanım. Örnek.
  - **`rel` Attribute**: `noopener`, `noreferrer`, `nofollow`. Güvenlik. Tanım. Örnek.
  - **Çapa Bağlantılar (Anchor Links)**: `#id` ile Sayfa İçi Gezinme. Tanım. Örnek.
  - **E-posta ve Telefon Bağlantıları**: `mailto:`. `tel:`. Tanım. Örnek.
  - **İndirme Bağlantısı**: `download` Attribute. Tanım. Örnek.
- **Görseller (Images)**
  - **`<img>` Etiketi**: Tanım. `src`, `alt`, `width`, `height`. Örnek.
  - **`alt` Attribute Önemi**: Erişilebilirlik. SEO. Tanım. Örnek.
  - **Görsel Formatları**: JPEG, PNG, GIF, SVG, WebP, AVIF. Farkları. Tablo Halinde.
  - **`<figure>` ve `<figcaption>`**: Tanım. Semantik Kullanım. Örnek.
  - **`<picture>` ve `<source>`**: Responsive Görseller. `media` Attribute. `srcset`. Tanım. Örnek.
  - **Lazy Loading**: `loading="lazy"`. Tanım. Performans. Örnek.
- **Yorum Satırı**: `<!-- -->`. Tanım. Kullanım Senaryoları. Örnek.
 
---
 
### HTML : Listeler
- **Listeler Nedir?**: Tanım. Kullanım Senaryoları.
- **Sırasız Liste (Unordered List)**: `<ul>`. `<li>`. Tanım. Örnek.
- **Sıralı Liste (Ordered List)**: `<ol>`. `<li>`. `type` ve `start` Attribute. Tanım. Örnek.
- **Tanımlama Listesi (Definition List)**: `<dl>`. `<dt>`. `<dd>`. Tanım. Örnek.
- **İç İçe Listeler (Nested Lists)**: Tanım. Örnek.
 
---
 
### HTML : Tablolar
- **Tablo Nedir?**: Tanım. Ne Zaman Kullanılmalı?
- **Temel Tablo Yapısı**: `<table>`, `<tr>`, `<td>`, `<th>`. Tanım. Örnek.
- **Tablo Bölümleri**: `<thead>`, `<tbody>`, `<tfoot>`. Tanım. Semantik Anlam. Örnek.
- **`<caption>` Etiketi**: Tablo Başlığı. Tanım. Örnek.
- **Hücre Birleştirme**: `colspan`. `rowspan`. Tanım. Örnek.
- **`<colgroup>` ve `<col>`**: Sütun Gruplama ve Stillendirme. Tanım. Örnek.
- **Erişilebilir Tablolar**: `scope` Attribute. `headers` Attribute. Tanım. Örnek.
 
---
 
### HTML : Formlar
- **Form Nedir?**: Tanım. Kullanım Senaryoları.
- **`<form>` Etiketi**: Tanım. `action`, `method` (GET/POST), `enctype`. Örnek.
- **`<input>` Etiketi ve Türleri**
  - **text**: Tanım. `placeholder`, `maxlength`, `minlength`, `pattern`. Örnek.
  - **password**: Tanım. Örnek.
  - **email**: Tanım. Doğrulama. Örnek.
  - **number**: Tanım. `min`, `max`, `step`. Örnek.
  - **tel**: Tanım. Örnek.
  - **url**: Tanım. Örnek.
  - **search**: Tanım. Örnek.
  - **date, time, datetime-local, month, week**: Tarih/Saat Girdileri. Tanım. Örnek.
  - **color**: Renk Seçici. Tanım. Örnek.
  - **range**: Kaydırıcı. `min`, `max`, `step`. Tanım. Örnek.
  - **file**: Dosya Yükleme. `accept`, `multiple`. Tanım. Örnek.
  - **checkbox**: Tanım. `checked`. Örnek.
  - **radio**: Tanım. `name` ile Gruplama. Örnek.
  - **hidden**: Gizli Alan. Tanım. Örnek.
  - **submit, reset, button**: Buton Türleri. Tanım. Örnek.
- **`<label>` Etiketi**: Tanım. `for` Attribute. Erişilebilirlik. Örnek.
- **`<textarea>` Etiketi**: Çok Satırlı Metin. `rows`, `cols`. Tanım. Örnek.
- **`<select>`, `<option>`, `<optgroup>`**: Açılır Liste. `multiple`, `selected`. Tanım. Örnek.
- **`<datalist>` Etiketi**: Otomatik Tamamlama Listesi. Tanım. Örnek.
- **`<fieldset>` ve `<legend>`**: Form Gruplama. Tanım. Örnek.
- **`<output>` Etiketi**: Hesaplama Sonucu. Tanım. Örnek.
- **`<progress>` ve `<meter>`**: İlerleme ve Ölçüm Çubuğu. Tanım. Örnek.
- **`<button>` Etiketi**: `type` Attribute. `submit`, `reset`, `button`. Input ile Farkı. Tanım. Örnek.
- **Form Doğrulama (Validation)**
  - **HTML5 Doğrulama Attribute'ları**: `required`, `pattern`, `min`, `max`, `minlength`, `maxlength`. Tanım. Örnek.
  - **`:valid` ve `:invalid` Pseudo-Class'lar**: Tanım. CSS ile Kullanım. Örnek.
  - **`novalidate` ve `formnovalidate`**: Doğrulamayı Kapatma. Tanım. Örnek.
  - **Custom Validation Mesajları**: `setCustomValidity()`. Tanım. Örnek.
 
---
 
### HTML : Semantik HTML
- **Semantik HTML Nedir?**: Tanım. Neden Önemli? Div Soup Sorunu. Örnek.
- **Sayfa Yapısı Etiketleri**
  - **`<header>`**: Tanım. Kullanım Senaryoları. Örnek.
  - **`<nav>`**: Navigasyon. Tanım. Örnek.
  - **`<main>`**: Ana İçerik. Tanım. Örnek.
  - **`<section>`**: Bölüm. Tanım. `<div>` ile Farkı. Örnek.
  - **`<article>`**: Bağımsız İçerik. Tanım. `<section>` ile Farkı. Örnek.
  - **`<aside>`**: Yan İçerik. Tanım. Örnek.
  - **`<footer>`**: Alt Bilgi. Tanım. Örnek.
- **İçerik Etiketleri**
  - **`<details>` ve `<summary>`**: Açılır-Kapanır İçerik. `open` Attribute. Tanım. Örnek.
  - **`<dialog>`**: Modal Pencere. `open`. `showModal()`. `close()`. Tanım. Örnek.
  - **`<time>`**: Tarih ve Zaman. `datetime` Attribute. Tanım. Örnek.
  - **`<address>`**: İletişim Bilgisi. Tanım. Örnek.
  - **`<template>`**: Gizli Şablon. Tanım. JS ile Kullanım. Örnek.
- **`<div>` ve `<span>`**: Tanım. Semantik Anlam Taşımayan Konteynerler. Ne Zaman Kullanılmalı? Farkları. Örnek.
 
---
 
### HTML : Medya Etiketleri
- **`<audio>` Etiketi**: Tanım. `src`, `controls`, `autoplay`, `loop`, `muted`, `preload`. Örnek.
  - **`<source>` ile Çoklu Format**: `type` Attribute. Tanım. Örnek.
  - **Desteklenen Formatlar**: MP3, WAV, OGG, AAC. Tablo Halinde.
- **`<video>` Etiketi**: Tanım. `src`, `controls`, `autoplay`, `loop`, `muted`, `poster`, `preload`. Örnek.
  - **`<source>` ile Çoklu Format**: `type` Attribute. Tanım. Örnek.
  - **Desteklenen Formatlar**: MP4, WebM, OGG. Tablo Halinde.
  - **`<track>` Etiketi**: Altyazı. `kind`, `srclang`, `label`. VTT Formatı. Tanım. Örnek.
- **`<iframe>` Etiketi**: Tanım. `src`, `width`, `height`, `sandbox`, `allow`, `loading`. Güvenlik. Örnek.
  - **YouTube / Harita Gömme**: Tanım. Örnek.
  - **`sandbox` Attribute**: Güvenlik Kısıtlamaları. Tanım. Örnek.
- **`<embed>` ve `<object>`**: Harici İçerik Gömme. Tanım. Farkları. Örnek.
 
---
 
### HTML : Meta Etiketler ve SEO
- **`<head>` İçeriği**: Tanım. Tarayıcıya Bilgi Verme.
- **`<meta>` Etiketleri**
  - **`charset`**: Karakter Kodlama. UTF-8. Tanım. Örnek.
  - **`viewport`**: Responsive Tasarım. `width=device-width`, `initial-scale=1.0`. Tanım. Örnek.
  - **`description`**: Sayfa Açıklaması. SEO. Tanım. Örnek.
  - **`keywords`**: Anahtar Kelimeler. Tanım. Güncel Kullanımı. Örnek.
  - **`author`**: Yazar Bilgisi. Tanım. Örnek.
  - **`robots`**: Arama Motoru Yönergeleri. `index`, `noindex`, `follow`, `nofollow`. Tanım. Örnek.
  - **`http-equiv`**: `refresh`, `X-UA-Compatible`, `Content-Security-Policy`. Tanım. Örnek.
- **Open Graph (og:)**: Sosyal Medya Paylaşım Kartları. `og:title`, `og:description`, `og:image`, `og:url`. Tanım. Örnek.
- **Twitter Card**: `twitter:card`, `twitter:title`, `twitter:description`, `twitter:image`. Tanım. Örnek.
- **`<link>` Etiketi**: Tanım. Kullanım Senaryoları.
  - **Favicon**: `rel="icon"`. Boyutlar. Tanım. Örnek.
  - **Stylesheet Bağlama**: `rel="stylesheet"`. Tanım. Örnek.
  - **Preload ve Prefetch**: `rel="preload"`, `rel="prefetch"`, `rel="preconnect"`. Performans. Tanım. Örnek.
  - **Canonical URL**: `rel="canonical"`. SEO. Tanım. Örnek.
- **`<script>` Etiketi**: `src`, `defer`, `async`, `type="module"`. Tanım. Farkları. Tablo Halinde. Örnek.
- **`<noscript>` Etiketi**: JS Desteği Olmayan Tarayıcılar. Tanım. Örnek.
- **Yapısal Veri (Structured Data)**: JSON-LD. Schema.org. Tanım. Örnek.
 
---
 
### HTML : Erişilebilirlik (Accessibility)
- **Web Erişilebilirliği Nedir?**: Tanım. WCAG. Neden Önemli? Kullanım Senaryoları.
- **ARIA (Accessible Rich Internet Applications)**
  - **ARIA Rolleri**: `role` Attribute. `button`, `navigation`, `alert`, `dialog`, `banner`. Tanım. Örnek.
  - **ARIA Attribute'ları**: `aria-label`, `aria-labelledby`, `aria-describedby`, `aria-hidden`, `aria-live`, `aria-expanded`, `aria-required`. Tanım. Örnek.
  - **ARIA Landmarks**: `banner`, `navigation`, `main`, `complementary`, `contentinfo`. Tanım. Örnek.
- **Klavye Navigasyonu**: `tabindex`. Tanım. Sıralama. Örnek.
- **Skip Navigation Links**: Tanım. Ekran Okuyucu Kullanıcıları. Örnek.
- **Renk Kontrastı ve Metin Boyutu**: WCAG Standartları. Tanım. Araçlar.
- **Alt Metinleri ve Görsel Erişilebilirlik**: `alt` Attribute Kuralları. Dekoratif Görseller. Tanım. Örnek.
- **Form Erişilebilirliği**: `<label>`. `aria-required`. Hata Mesajları. Tanım. Örnek.
 
---
 
### HTML : Canvas
- **`<canvas>` Nedir?**: Tanım. SVG ile Farkı. Kullanım Senaryoları.
- **Canvas Oluşturma**: `<canvas>` Etiketi. `width`, `height`. `getContext('2d')`. Tanım. Örnek.
- **Temel Çizim İşlemleri**
  - **Dikdörtgen**: `fillRect()`, `strokeRect()`, `clearRect()`. Tanım. Örnek.
  - **Çizgi (Path)**: `beginPath()`, `moveTo()`, `lineTo()`, `closePath()`, `stroke()`, `fill()`. Tanım. Örnek.
  - **Daire ve Yay**: `arc()`, `arcTo()`. Tanım. Parametreler. Örnek.
  - **Eğri**: `quadraticCurveTo()`, `bezierCurveTo()`. Tanım. Örnek.
- **Stil ve Renkler**
  - **`fillStyle` ve `strokeStyle`**: Renk, Gradient, Pattern. Tanım. Örnek.
  - **`lineWidth`, `lineCap`, `lineJoin`**: Çizgi Stilleri. Tanım. Örnek.
  - **Gradient**: `createLinearGradient()`, `createRadialGradient()`. Tanım. Örnek.
  - **Pattern**: `createPattern()`. Tanım. Örnek.
  - **Gölge**: `shadowColor`, `shadowBlur`, `shadowOffsetX`, `shadowOffsetY`. Tanım. Örnek.
- **Metin Çizme**: `fillText()`, `strokeText()`, `font`, `textAlign`, `textBaseline`. Tanım. Örnek.
- **Görsel Çizme**: `drawImage()`. Kaynak Kırpma. Boyutlandırma. Tanım. Örnek.
- **Dönüşümler (Transformations)**: `translate()`, `rotate()`, `scale()`, `transform()`, `setTransform()`. Tanım. Örnek.
- **Durumu Kaydetme ve Geri Yükleme**: `save()`, `restore()`. Tanım. Örnek.
- **Piksel Manipülasyonu**: `getImageData()`, `putImageData()`, `createImageData()`. Tanım. Örnek.
- **Canvas Animasyonu**: `requestAnimationFrame()`. Tanım. Oyun Döngüsü. Örnek.
 
---
 
### HTML : SVG
- **SVG Nedir?**: Scalable Vector Graphics. Tanım. Canvas ile Farkı. Kullanım Senaryoları.
- **Inline SVG**: `<svg>` Etiketi. `viewBox`, `width`, `height`, `xmlns`. Tanım. Örnek.
- **Temel Şekiller**
  - **`<rect>`**: Dikdörtgen. `x`, `y`, `width`, `height`, `rx`, `ry`. Tanım. Örnek.
  - **`<circle>`**: Daire. `cx`, `cy`, `r`. Tanım. Örnek.
  - **`<ellipse>`**: Elips. `cx`, `cy`, `rx`, `ry`. Tanım. Örnek.
  - **`<line>`**: Çizgi. `x1`, `y1`, `x2`, `y2`. Tanım. Örnek.
  - **`<polyline>`**: Çoklu Çizgi. `points`. Tanım. Örnek.
  - **`<polygon>`**: Çokgen. `points`. Tanım. Örnek.
  - **`<path>`**: Serbest Yol. `d` Attribute. M, L, H, V, C, S, Q, T, A, Z Komutları. Tanım. Örnek.
- **SVG Stillendirme**: `fill`, `stroke`, `stroke-width`, `opacity`, `stroke-dasharray`. Tanım. Örnek.
- **SVG Metin**: `<text>`. `x`, `y`, `font-size`, `text-anchor`. Tanım. Örnek.
- **SVG Grupları ve Dönüşümler**: `<g>`, `transform`. Tanım. Örnek.
- **SVG Tanımlar ve Yeniden Kullanım**: `<defs>`, `<use>`, `<symbol>`. Tanım. Örnek.
- **SVG Gradient ve Filtre**: `<linearGradient>`, `<radialGradient>`, `<filter>`. Tanım. Örnek.
- **SVG Animasyonları**: `<animate>`, `<animateTransform>`. Tanım. CSS ile Animasyon. Örnek.
- **SVG'yi Sayfalara Dahil Etme**: Inline, `<img>`, `<object>`, CSS `background-image`. Farkları. Tablo Halinde.
 
---
 
### HTML : Web API'leri (HTML5)
- **Web Storage**
  - **localStorage**: Tanım. `setItem()`, `getItem()`, `removeItem()`, `clear()`. Kalıcı Depolama. Örnek.
  - **sessionStorage**: Tanım. localStorage ile Farkı. Oturum Bazlı. Örnek.
  - **Storage Event**: Tanım. Sekmeler Arası İletişim. Örnek.
- **Geolocation API**: `navigator.geolocation`. `getCurrentPosition()`. `watchPosition()`. Tanım. Örnek.
- **Drag and Drop API**: `draggable` Attribute. `dragstart`, `dragover`, `drop` Olayları. `dataTransfer`. Tanım. Örnek.
- **History API**: `history.pushState()`, `history.replaceState()`, `popstate` Olayı. SPA Navigasyonu. Tanım. Örnek.
- **Clipboard API**: `navigator.clipboard.writeText()`, `navigator.clipboard.readText()`. Tanım. Örnek.
- **Fullscreen API**: `requestFullscreen()`, `exitFullscreen()`. Tanım. Örnek.
- **Notification API**: `Notification.requestPermission()`, `new Notification()`. Tanım. Örnek.
- **Web Workers**: Tanım. Arka Plan İşlemleri. `new Worker()`. `postMessage()`. `onmessage`. Örnek.
  - **Dedicated Worker**: Tanım. Örnek.
  - **Shared Worker**: Tanım. Birden Fazla Sekme. Örnek.
- **Intersection Observer API**: Tanım. Lazy Loading. Scroll Animasyonları. `threshold`, `rootMargin`. Örnek.
- **MutationObserver**: DOM Değişikliklerini İzleme. Tanım. Örnek.
- **Performance API**: `performance.now()`, `performance.mark()`, `performance.measure()`. Tanım. Örnek.
 
---

## CSS
 
### CSS : Giriş
- **CSS Nedir?**: Cascading Style Sheets. Tanım. HTML ile İlişkisi. Neden Gerekli?
  - **Kısa Tarihçesi**: CSS1'den CSS3'e. Tanım.
  - **CSS Versiyonları**: CSS1, CSS2, CSS3. Modüler Yapı. Tanım.
- **CSS'i HTML'e Dahil Etme**
  - **Inline CSS**: `style` Attribute. Tanım. Neden Tercih Edilmemeli? Örnek.
  - **Internal CSS**: `<style>` Etiketi. Tanım. Örnek.
  - **External CSS**: `<link rel="stylesheet">`. Tanım. Neden En İyi Yöntem? Örnek.
  - **`@import` Kuralı**: Tanım. `<link>` ile Farkı. Performans. Örnek.
- **CSS Sözdizimi (Syntax)**: Seçici. Özellik. Değer. Bildirim Bloğu. Tanım. Örnek.
- **CSS Yorumları**: `/* */`. Tanım. Örnek.
- **Cascading (Basamaklama)**: Tanım. Kuralların Çakışması. Öncelik Sırası.
- **Specificity (Özgüllük)**: Tanım. Hesaplama Kuralları. Inline > ID > Class > Element. Tablo Halinde. Örnek.
- **Inheritance (Kalıtım)**: Tanım. Hangi Özellikler Miras Alınır? `inherit`, `initial`, `unset`, `revert`. Örnek.
- **`!important` Kuralı**: Tanım. Neden Dikkatli Kullanılmalı? Örnek.
 
---
 
### CSS : Seçiciler (Selectors)
- **Seçici Nedir?**: Tanım. Kullanım Senaryoları.
- **Temel Seçiciler**
  - **Evrensel Seçici**: `*`. Tanım. Örnek.
  - **Element Seçici**: `p`, `h1`, `div`. Tanım. Örnek.
  - **Class Seçici**: `.className`. Tanım. Örnek.
  - **ID Seçici**: `#idName`. Tanım. Örnek.
  - **Attribute Seçici**: `[attr]`, `[attr="value"]`, `[attr~="value"]`, `[attr|="value"]`, `[attr^="value"]`, `[attr$="value"]`, `[attr*="value"]`. Tanım. Tablo Halinde. Örnek.
- **Birleştirici Seçiciler (Combinators)**
  - **Soyundan Gelen (Descendant)**: `A B`. Tanım. Örnek.
  - **Doğrudan Çocuk (Child)**: `A > B`. Tanım. Örnek.
  - **Bitişik Kardeş (Adjacent Sibling)**: `A + B`. Tanım. Örnek.
  - **Genel Kardeş (General Sibling)**: `A ~ B`. Tanım. Örnek.
- **Grup Seçici**: `A, B`. Tanım. Örnek.
- **Pseudo-Class Seçiciler**
  - **Durumsal**: `:hover`, `:active`, `:focus`, `:focus-within`, `:focus-visible`, `:visited`, `:link`. Tanım. Örnek.
  - **Yapısal**: `:first-child`, `:last-child`, `:nth-child(n)`, `:nth-last-child(n)`, `:nth-of-type(n)`, `:first-of-type`, `:last-of-type`, `:only-child`, `:only-of-type`. Tanım. Örnek.
  - **Form**: `:checked`, `:disabled`, `:enabled`, `:required`, `:optional`, `:valid`, `:invalid`, `:in-range`, `:out-of-range`, `:placeholder-shown`, `:read-only`, `:read-write`. Tanım. Örnek.
  - **Diğer**: `:root`, `:empty`, `:not()`, `:is()`, `:where()`, `:has()`, `:target`, `:lang()`. Tanım. Örnek.
- **Pseudo-Element Seçiciler**
  - **`::before` ve `::after`**: `content` Özelliği. Dekoratif Kullanım. Tanım. Örnek.
  - **`::first-line` ve `::first-letter`**: Tanım. Örnek.
  - **`::placeholder`**: Form Placeholder Stili. Tanım. Örnek.
  - **`::selection`**: Seçili Metin Stili. Tanım. Örnek.
  - **`::marker`**: Liste İşareti Stili. Tanım. Örnek.
 
---
 
### CSS : Renkler ve Arka Planlar
- **Renk Değerleri**
  - **Renk İsimleri**: `red`, `blue`, `tomato`. Tanım. Örnek.
  - **HEX**: `#RRGGBB`, `#RGB`, `#RRGGBBAA`. Tanım. Örnek.
  - **RGB ve RGBA**: `rgb()`, `rgba()`. Alpha Kanalı. Tanım. Örnek.
  - **HSL ve HSLA**: `hsl()`, `hsla()`. Hue, Saturation, Lightness. Tanım. Neden Tercih Edilebilir? Örnek.
  - **`currentColor` Anahtar Kelimesi**: Tanım. Miras Alınan Renk. Örnek.
  - **`transparent` Anahtar Kelimesi**: Tanım. Örnek.
- **`color` Özelliği**: Metin Rengi. Tanım. Örnek.
- **`opacity` Özelliği**: Saydamlık. `0` — `1`. Tanım. Örnek.
- **Arka Plan Özellikleri**
  - **`background-color`**: Tanım. Örnek.
  - **`background-image`**: `url()`. Tanım. Örnek.
  - **`background-repeat`**: `repeat`, `no-repeat`, `repeat-x`, `repeat-y`, `space`, `round`. Tanım. Örnek.
  - **`background-size`**: `cover`, `contain`, `auto`, `px`, `%`. Tanım. Örnek.
  - **`background-position`**: `center`, `top`, `bottom`, `left`, `right`, `%`, `px`. Tanım. Örnek.
  - **`background-attachment`**: `scroll`, `fixed`, `local`. Parallax Efekti. Tanım. Örnek.
  - **`background-origin`**: `border-box`, `padding-box`, `content-box`. Tanım. Örnek.
  - **`background-clip`**: `border-box`, `padding-box`, `content-box`, `text`. Tanım. Örnek.
  - **`background` Kısaltması**: Tüm Özellikleri Tek Satırda. Tanım. Örnek.
  - **Çoklu Arka Plan**: Birden Fazla `background-image`. Katmanlama. Tanım. Örnek.
- **Gradient'lar**
  - **`linear-gradient()`**: Yön. Renk Durakları. Tanım. Örnek.
  - **`radial-gradient()`**: Şekil. Boyut. Konum. Tanım. Örnek.
  - **`conic-gradient()`**: Konik Gradient. Tanım. Örnek.
  - **`repeating-linear-gradient()` ve `repeating-radial-gradient()`**: Tekrarlayan Gradient. Tanım. Örnek.
 
---
 
### CSS : Tipografi (Typography)
- **`font-family`**: Font Yığını (Font Stack). Web-Safe Fontlar. Tanım. Örnek.
- **`@font-face` Kuralı**: Özel Font Yükleme. `src`. `format`. `font-display`. Tanım. Örnek.
- **Google Fonts Kullanımı**: `<link>` ve `@import` ile Yükleme. Tanım. Örnek.
- **`font-size`**: `px`, `em`, `rem`, `%`, `vw`, `vh`. Tanım. Farkları. Tablo Halinde. Örnek.
- **`font-weight`**: `normal`, `bold`, `lighter`, `bolder`, `100` — `900`. Tanım. Örnek.
- **`font-style`**: `normal`, `italic`, `oblique`. Tanım. Örnek.
- **`font-variant`**: `small-caps`. Tanım. Örnek.
- **`font` Kısaltması**: Tanım. Sözdizimi. Örnek.
- **`line-height`**: Satır Yüksekliği. Tanım. Okunabilirlik. Örnek.
- **`letter-spacing`**: Harf Aralığı. Tanım. Örnek.
- **`word-spacing`**: Kelime Aralığı. Tanım. Örnek.
- **`text-align`**: `left`, `right`, `center`, `justify`. Tanım. Örnek.
- **`text-decoration`**: `underline`, `overline`, `line-through`, `none`. `text-decoration-color`, `text-decoration-style`, `text-decoration-thickness`. Tanım. Örnek.
- **`text-transform`**: `uppercase`, `lowercase`, `capitalize`, `none`. Tanım. Örnek.
- **`text-indent`**: Paragraf Girintisi. Tanım. Örnek.
- **`text-shadow`**: `x-offset`, `y-offset`, `blur`, `color`. Çoklu Gölge. Tanım. Örnek.
- **`white-space`**: `normal`, `nowrap`, `pre`, `pre-wrap`, `pre-line`, `break-spaces`. Tanım. Tablo Halinde. Örnek.
- **`word-break` ve `overflow-wrap`**: Uzun Kelime Kırma. Tanım. Farkları. Örnek.
- **`text-overflow`**: `ellipsis`, `clip`. `overflow: hidden` ile Kullanım. Tanım. Örnek.
- **`writing-mode`**: `horizontal-tb`, `vertical-rl`, `vertical-lr`. Tanım. Örnek.
- **Değişken Fontlar (Variable Fonts)**: `font-variation-settings`. `wght`, `wdth`, `ital`. Tanım. Örnek.
 
---
 
### CSS : Kutu Modeli (Box Model)
- **Box Model Nedir?**: Content → Padding → Border → Margin. Tanım. Görselleştirme. Örnek.
- **`width` ve `height`**: Tanım. `auto`. `min-width`, `max-width`, `min-height`, `max-height`. Örnek.
- **`padding`**: Tanım. Yönlü Kullanım (`padding-top`, `-right`, `-bottom`, `-left`). Kısaltma. Örnek.
- **`margin`**: Tanım. Yönlü Kullanım. `auto` ile Ortalama. Negatif Margin. Margin Collapse. Örnek.
  - **Margin Collapse**: Tanım. Ne Zaman Olur? Nasıl Engellenir? Örnek.
- **`border`**: `border-width`, `border-style`, `border-color`. Yönlü Kullanım. Kısaltma. Tanım. Örnek.
  - **`border-style` Değerleri**: `solid`, `dashed`, `dotted`, `double`, `groove`, `ridge`, `inset`, `outset`, `none`. Tablo Halinde.
  - **`border-radius`**: Yuvarlak Köşeler. Eliptik Köşeler. Daire Yapma. Tanım. Örnek.
- **`outline`**: Tanım. `border` ile Farkı. `outline-offset`. Erişilebilirlik. Örnek.
- **`box-sizing`**: `content-box` vs `border-box`. Tanım. Farkları. Neden `border-box`? Örnek.
  > Global Reset Kuralı
- **`overflow`**: `visible`, `hidden`, `scroll`, `auto`. `overflow-x`, `overflow-y`. Tanım. Örnek.
- **`box-shadow`**: `x-offset`, `y-offset`, `blur`, `spread`, `color`, `inset`. Çoklu Gölge. Tanım. Örnek.
 
---
 
### CSS : Display ve Görünürlük
- **`display` Özelliği**: Tanım. Element Davranışı.
  - **`block`**: Tanım. Özellikler. Örnek.
  - **`inline`**: Tanım. Özellikler. Blok ile Farkı. Örnek.
  - **`inline-block`**: Tanım. Inline ve Block Arası. Örnek.
  - **`none`**: Tanım. `visibility: hidden` ile Farkı. Örnek.
  - **`flex`**: Tanım. (Detay Flexbox Bölümünde)
  - **`grid`**: Tanım. (Detay Grid Bölümünde)
  - **`inline-flex` ve `inline-grid`**: Tanım. Örnek.
  - **`table`, `table-row`, `table-cell`**: Tablo Benzeri Düzen. Tanım. Örnek.
  - **`contents`**: Tanım. Kullanım Senaryoları. Örnek.
- **`visibility`**: `visible`, `hidden`, `collapse`. `display: none` ile Farkı. Tanım. Örnek.
 
---
 
### CSS : Konumlandırma (Positioning)
- **`position` Özelliği**: Tanım. Normal Akış.
  - **`static`**: Varsayılan. Tanım. Örnek.
  - **`relative`**: Tanım. `top`, `right`, `bottom`, `left`. Normal Akışta Yeri. Örnek.
  - **`absolute`**: Tanım. En Yakın Konumlandırılmış Ataya Göre. Akıştan Çıkma. Örnek.
  - **`fixed`**: Tanım. Viewport'a Göre. Sabit Header/Footer. Örnek.
  - **`sticky`**: Tanım. Scroll ile Yapışma. `top` Değeri. Tarayıcı Desteği. Örnek.
- **`top`, `right`, `bottom`, `left`**: Offset Özellikleri. Tanım. Örnek.
- **`z-index`**: Katman Sıralaması. Stacking Context. Tanım. Negatif Değerler. Örnek.
  - **Stacking Context**: Tanım. Ne Zaman Oluşur? Örnek.
- **`float` ve `clear`**: Tanım. Eski Düzen Yöntemi. `clearfix` Tekniği. Örnek.
  > Neden Artık Flexbox/Grid Tercih Edilmeli?
 
---
 
### CSS : Flexbox
- **Flexbox Nedir?**: Tanım. Tek Boyutlu Düzen. Kullanım Senaryoları.
- **Flex Container (Ana Kutu)**
  - **`display: flex`**: Tanım. Örnek.
  - **`flex-direction`**: `row`, `row-reverse`, `column`, `column-reverse`. Tanım. Örnek.
  - **`flex-wrap`**: `nowrap`, `wrap`, `wrap-reverse`. Tanım. Örnek.
  - **`flex-flow`**: Kısaltma (`flex-direction` + `flex-wrap`). Tanım. Örnek.
  - **`justify-content`**: `flex-start`, `flex-end`, `center`, `space-between`, `space-around`, `space-evenly`. Tanım. Görselleştirme. Örnek.
  - **`align-items`**: `stretch`, `flex-start`, `flex-end`, `center`, `baseline`. Tanım. Görselleştirme. Örnek.
  - **`align-content`**: Çok Satırlı Hizalama. `stretch`, `flex-start`, `flex-end`, `center`, `space-between`, `space-around`. Tanım. Örnek.
  - **`gap` (`row-gap`, `column-gap`)**: Eleman Arası Boşluk. Tanım. Örnek.
- **Flex Item (Çocuk Elemanlar)**
  - **`flex-grow`**: Büyüme Oranı. Tanım. Örnek.
  - **`flex-shrink`**: Küçülme Oranı. Tanım. Örnek.
  - **`flex-basis`**: Başlangıç Boyutu. `auto`, `0`, `px`, `%`. Tanım. Örnek.
  - **`flex` Kısaltması**: `flex: grow shrink basis`. Yaygın Değerler. Tanım. Örnek.
  - **`align-self`**: Tekil Hizalama. Container'dan Bağımsız. Tanım. Örnek.
  - **`order`**: Görsel Sıralama. Tanım. Örnek.
- **Flexbox ile Yaygın Düzenler**: Navbar. Kart Düzeni. Footer'ı Alta Yapıştırma. Dikey ve Yatay Ortalama. Örnek.
 
---
 
### CSS : Grid
- **CSS Grid Nedir?**: Tanım. İki Boyutlu Düzen. Flexbox ile Farkı. Kullanım Senaryoları.
- **Grid Container**
  - **`display: grid`**: Tanım. Örnek.
  - **`grid-template-columns`**: Sütun Tanımlama. `fr`, `px`, `%`, `auto`, `minmax()`, `repeat()`. Tanım. Örnek.
  - **`grid-template-rows`**: Satır Tanımlama. Tanım. Örnek.
  - **`grid-template-areas`**: İsimli Alan Tanımlama. Tanım. Örnek.
  - **`grid-template`**: Kısaltma. Tanım. Örnek.
  - **`gap` (`row-gap`, `column-gap`)**: Boşluk. Tanım. Örnek.
  - **`justify-items`**: Yatay Hücre Hizalama. `start`, `end`, `center`, `stretch`. Tanım. Örnek.
  - **`align-items`**: Dikey Hücre Hizalama. Tanım. Örnek.
  - **`justify-content`**: Grid Container İçi Yatay Hizalama. Tanım. Örnek.
  - **`align-content`**: Grid Container İçi Dikey Hizalama. Tanım. Örnek.
  - **`place-items` ve `place-content`**: Kısaltmalar. Tanım. Örnek.
  - **`grid-auto-rows` ve `grid-auto-columns`**: Otomatik Oluşan İzler. Tanım. Örnek.
  - **`grid-auto-flow`**: `row`, `column`, `dense`. Tanım. Örnek.
- **Grid Item**
  - **`grid-column-start` ve `grid-column-end`**: Sütun Yerleştirme. Tanım. Örnek.
  - **`grid-row-start` ve `grid-row-end`**: Satır Yerleştirme. Tanım. Örnek.
  - **`grid-column` ve `grid-row`**: Kısaltma. `span` Kullanımı. Tanım. Örnek.
  - **`grid-area`**: Alan İsmiyle Yerleştirme. Kısaltma. Tanım. Örnek.
  - **`justify-self` ve `align-self`**: Tekil Hücre Hizalama. Tanım. Örnek.
  - **`place-self`**: Kısaltma. Tanım. Örnek.
- **Grid Fonksiyonları**
  - **`repeat()`**: Tekrarlayan İz Tanımı. `auto-fill`, `auto-fit`. Tanım. Farkları. Örnek.
  - **`minmax()`**: Minimum ve Maksimum Boyut. Tanım. Örnek.
  - **`fit-content()`**: İçeriğe Göre Boyut. Tanım. Örnek.
- **Alt Grid (Subgrid)**: Tanım. İç İçe Grid Hizalama. Tarayıcı Desteği. Örnek.
- **Grid ile Yaygın Düzenler**: Holy Grail Layout. Dergi Düzeni. Galeri. Dashboard. Örnek.
 
---
 
### CSS : Geçişler ve Animasyonlar
- **Transitions (Geçişler)**
  - **`transition-property`**: Hangi Özellik Geçiş Yapacak? `all`. Tanım. Örnek.
  - **`transition-duration`**: Süre. `s`, `ms`. Tanım. Örnek.
  - **`transition-timing-function`**: `ease`, `linear`, `ease-in`, `ease-out`, `ease-in-out`, `cubic-bezier()`, `steps()`. Tanım. Örnek.
  - **`transition-delay`**: Gecikme. Tanım. Örnek.
  - **`transition` Kısaltması**: Tanım. Çoklu Geçiş. Örnek.
  - **Hangi Özellikler Animate Edilebilir?**: Tanım. Performans. `transform` ve `opacity` Tercih Edilmeli. Tablo Halinde.
- **Animations (Animasyonlar)**
  - **`@keyframes` Kuralı**: `from` / `to`. `%` ile Ara Kareler. Tanım. Örnek.
  - **`animation-name`**: Tanım. Örnek.
  - **`animation-duration`**: Tanım. Örnek.
  - **`animation-timing-function`**: Tanım. Örnek.
  - **`animation-delay`**: Tanım. Negatif Değerler. Örnek.
  - **`animation-iteration-count`**: `infinite`. Sayısal Değer. Tanım. Örnek.
  - **`animation-direction`**: `normal`, `reverse`, `alternate`, `alternate-reverse`. Tanım. Örnek.
  - **`animation-fill-mode`**: `none`, `forwards`, `backwards`, `both`. Tanım. Örnek.
  - **`animation-play-state`**: `running`, `paused`. JS ile Kontrol. Tanım. Örnek.
  - **`animation` Kısaltması**: Tanım. Çoklu Animasyon. Örnek.
- **Performans İpuçları**: `will-change`. GPU Hızlandırma. Repaint vs Reflow. Tanım. Örnek.
 
---
 
### CSS : Dönüşümler (Transforms)
- **`transform` Özelliği**: Tanım. Kullanım Senaryoları.
- **2D Dönüşümler**
  - **`translate(x, y)`**: Taşıma. `translateX()`, `translateY()`. Tanım. Örnek.
  - **`rotate(angle)`**: Döndürme. `deg`, `turn`, `rad`. Tanım. Örnek.
  - **`scale(x, y)`**: Ölçekleme. `scaleX()`, `scaleY()`. Tanım. Örnek.
  - **`skew(x, y)`**: Eğme. `skewX()`, `skewY()`. Tanım. Örnek.
  - **`matrix()`**: 2D Matris Dönüşümü. Tanım. Örnek.
- **3D Dönüşümler**
  - **`perspective`**: 3D Derinlik. Container'a ve Element'e Uygulama. Tanım. Örnek.
  - **`perspective-origin`**: Bakış Noktası. Tanım. Örnek.
  - **`translateZ()` ve `translate3d()`**: Z Ekseninde Taşıma. Tanım. Örnek.
  - **`rotateX()`, `rotateY()`, `rotateZ()`, `rotate3d()`**: 3D Döndürme. Tanım. Örnek.
  - **`scaleZ()` ve `scale3d()`**: 3D Ölçekleme. Tanım. Örnek.
  - **`transform-style`**: `flat`, `preserve-3d`. Tanım. Örnek.
  - **`backface-visibility`**: `visible`, `hidden`. Kart Çevirme Efekti. Tanım. Örnek.
- **`transform-origin`**: Dönüşüm Merkezi. `x`, `y`, `z`. Tanım. Örnek.
- **Çoklu Dönüşüm**: Sıralama Önemi. Tanım. Örnek.
 
---
 
### CSS : Responsive Tasarım
- **Responsive Tasarım Nedir?**: Tanım. Mobile-First vs Desktop-First. Neden Önemli?
- **Viewport**: `<meta name="viewport">`. Tanım. Mobil Uyumluluk. Örnek.
- **CSS Birimleri Karşılaştırması**
  - **Mutlak Birimler**: `px`, `pt`, `cm`, `mm`, `in`. Tanım. Tablo Halinde.
  - **Göreceli Birimler**: `em`, `rem`, `%`, `vw`, `vh`, `vmin`, `vmax`, `ch`, `ex`. Tanım. Farkları. Tablo Halinde. Örnek.
  - **Yeni Viewport Birimleri**: `dvw`, `dvh`, `svw`, `svh`, `lvw`, `lvh`. Mobil Adres Çubuğu Sorunu. Tanım. Örnek.
- **Media Queries**
  - **`@media` Kuralı**: Sözdizimi. Tanım. Örnek.
  - **Genişlik Sorguları**: `min-width`, `max-width`. Breakpoint Kavramı. Tanım. Örnek.
  - **Yükseklik Sorguları**: `min-height`, `max-height`. Tanım. Örnek.
  - **Yönlendirme (Orientation)**: `portrait`, `landscape`. Tanım. Örnek.
  - **Tercih Sorguları**: `prefers-color-scheme` (dark/light), `prefers-reduced-motion`, `prefers-contrast`. Tanım. Örnek.
  - **`hover` ve `pointer` Sorguları**: Dokunmatik vs Mouse. `hover: hover`, `pointer: fine`. Tanım. Örnek.
  - **Mantıksal Operatörler**: `and`, `or` (`,`), `not`, `only`. Tanım. Örnek.
  - **Yaygın Breakpoint'ler**: Mobil. Tablet. Desktop. Büyük Ekran. Tablo Halinde.
- **Container Queries**: `@container`. `container-type`. `container-name`. Tanım. Media Query ile Farkı. Örnek.
- **Responsive Görseller**: `max-width: 100%`. `object-fit`. `object-position`. Tanım. Örnek.
- **Responsive Tipografi**: `clamp()`. `calc()`. `vw` Birimiyle. Tanım. Örnek.
- **`clamp()`, `min()`, `max()` Fonksiyonları**: Tanım. Kullanım Senaryoları. Örnek.
 
---
 
### CSS : Filtre ve Efektler
- **`filter` Özelliği**: Tanım. Kullanım Senaryoları.
  - **`blur()`**: Bulanıklaştırma. Tanım. Örnek.
  - **`brightness()`**: Parlaklık. Tanım. Örnek.
  - **`contrast()`**: Kontrast. Tanım. Örnek.
  - **`grayscale()`**: Gri Tonlama. Tanım. Örnek.
  - **`sepia()`**: Sepya Efekti. Tanım. Örnek.
  - **`saturate()`**: Doygunluk. Tanım. Örnek.
  - **`hue-rotate()`**: Renk Tonu Döndürme. Tanım. Örnek.
  - **`invert()`**: Renk Ters Çevirme. Tanım. Örnek.
  - **`opacity()`**: Filter İçinde Saydamlık. Tanım. Örnek.
  - **`drop-shadow()`**: Gerçek Gölge. `box-shadow` ile Farkı. Tanım. Örnek.
  - **Çoklu Filtre**: Birden Fazla Filtreyi Birleştirme. Tanım. Örnek.
- **`backdrop-filter` Özelliği**: Arka Plan Filtresi. Glassmorphism. `blur()`, `saturate()`. Tanım. Tarayıcı Desteği. Örnek.
- **`mix-blend-mode`**: Karışım Modu. `multiply`, `screen`, `overlay`, `darken`, `lighten`. Tanım. Örnek.
- **`background-blend-mode`**: Arka Plan Karışımı. Tanım. Örnek.
- **`clip-path`**: Kırpma Şekilleri. `circle()`, `ellipse()`, `polygon()`, `inset()`, `path()`. Tanım. Örnek.
- **`mask` ve `mask-image`**: Maskeleme. Gradient Maske. Tanım. Örnek.
- **`shape-outside`**: Metin Sarma Şekli. `circle()`, `ellipse()`, `polygon()`. Tanım. Örnek.
 
---
 
### CSS : Değişkenler (Custom Properties)
- **CSS Değişkenleri Nedir?**: Tanım. Neden Kullanılır? Preprocessor Değişkenleri ile Farkı.
- **Tanımlama ve Kullanma**: `--variable-name`. `var(--variable-name)`. Tanım. Örnek.
- **`:root` ile Global Değişkenler**: Tanım. Tüm Sayfada Erişim. Örnek.
- **Kapsam (Scope)**: Yerel ve Global. Geçersiz Kılma (Override). Tanım. Örnek.
- **Fallback Değerler**: `var(--color, #000)`. Tanım. Örnek.
- **JavaScript ile Değişken Kontrolü**: `setProperty()`, `getPropertyValue()`. Dinamik Tema. Tanım. Örnek.
- **Karanlık/Aydınlık Tema Sistemi**: `prefers-color-scheme` ile CSS Değişkenleri. Tanım. Örnek.
- **CSS Değişkenleri ile Animasyon**: `@property` Kuralı. Tanım. Animasyon Kısıtlamaları ve Çözüm. Örnek.
 
---
 
### CSS : Modern CSS Özellikleri
- **`aspect-ratio`**: En-Boy Oranı. `16 / 9`, `1 / 1`. Tanım. Örnek.
- **`accent-color`**: Form Elemanı Aksan Rengi. Tanım. Örnek.
- **`scroll-behavior`**: `smooth`. Yumuşak Kaydırma. Tanım. Örnek.
- **`scroll-snap`**: Kaydırma Yakalama. `scroll-snap-type`, `scroll-snap-align`. Tanım. Örnek.
- **`object-fit`**: `fill`, `contain`, `cover`, `none`, `scale-down`. Tanım. Örnek.
- **`object-position`**: Tanım. Örnek.
- **`resize`**: `none`, `both`, `horizontal`, `vertical`. Tanım. Örnek.
- **`caret-color`**: İmleç Rengi. Tanım. Örnek.
- **`user-select`**: `none`, `auto`, `text`, `all`. Tanım. Örnek.
- **`pointer-events`**: `none`, `auto`. Tıklama Engelleme. Tanım. Örnek.
- **`isolation`**: Stacking Context Oluşturma. `isolate`. Tanım. Örnek.
- **Mantıksal Özellikler (Logical Properties)**: `margin-inline`, `padding-block`, `border-inline-start`, `inline-size`, `block-size`. Tanım. LTR/RTL Desteği. Örnek.
- **`@supports` Kuralı**: Feature Query. Tanım. Tarayıcı Desteği Kontrolü. Örnek.
- **`@layer` Kuralı**: Cascade Layers. Tanım. Specificity Yönetimi. Örnek.
- **Nesting**: CSS İç İçe Yazım. `&` Seçici. Tanım. Tarayıcı Desteği. Örnek.
- **`:has()` Seçicisi**: Parent Selector. Tanım. Kullanım Senaryoları. Örnek.
- **`color-mix()`**: Renk Karıştırma. Tanım. Örnek.
- **`@starting-style`**: Geçiş Başlangıç Stili. `display: none`'dan Geçiş. Tanım. Örnek.
- **View Transitions API**: Sayfa Geçiş Animasyonları. `view-transition-name`. `::view-transition-old`, `::view-transition-new`. Tanım. Örnek.
 
---
 
### CSS : Tasarım Teknikleri ve Best Practices
- **CSS Reset ve Normalize**: Tanım. Farkları. Yaygın Resetler. Örnek.
- **BEM Metodolojisi**: Block-Element-Modifier. Tanım. İsimlendirme Kuralları. Örnek.
- **CSS Mimarisi**: OOCSS. SMACSS. ITCSS. Tanım. Farkları. Tablo Halinde.
- **Utility-First vs Component-Based**: Tanım. Farkları. Avantaj/Dezavantaj.
- **Performans Optimizasyonu**: Seçici Performansı. Repaint/Reflow. `will-change`. `contain`. Critical CSS. Tanım. Örnek.
- **Print Stilleri**: `@media print`. Yazdırma İçin Özelleştirme. Tanım. Örnek.

---
 
## JavaScript
 
### JavaScript : Giriş
- **JavaScript Nedir?**: Tanım. Web'in Üçüncü Ayağı. Kullanım Alanları.
  - **Kısa Tarihçesi**: Brendan Eich. Netscape. ECMAScript Standartları. Tanım.
  - **ECMAScript Versiyonları**: ES5, ES6 (ES2015), ES2016 — ES2024. Tanım. Önemli Dönüm Noktaları.
  - **JavaScript vs Java**: Tanım. Farkları. Neden Benzer İsimleri Var?
  - **Dinamik ve Zayıf Tipli Dil**: Tanım. C++ ile Karşılaştırma.
- **JavaScript Nasıl Çalışır?**
  - **Tarayıcı Motorları**: V8 (Chrome), SpiderMonkey (Firefox), JavaScriptCore (Safari). Tanım.
  - **Yorumlama vs Derleme**: JIT (Just-In-Time) Compilation. Tanım.
  - **Call Stack**: Tanım. Çalışma Prensibi. Stack Overflow. Örnek.
  - **Event Loop**: Tanım. Tek İşlem Parçacıklı (Single-Threaded). Callback Queue. Microtask Queue. Örnek.
- **JavaScript'i HTML'e Dahil Etme**
  - **Inline**: `onclick` gibi Attribute'lar. Tanım. Neden Tercih Edilmemeli? Örnek.
  - **Internal**: `<script>` Etiketi. Tanım. Örnek.
  - **External**: `<script src="">`. Tanım. Neden En İyi Yöntem? Örnek.
  - **`defer` ve `async`**: Tanım. Farkları. Yükleme Sırası. Tablo Halinde. Örnek.
- **`console` Nesnesi**: `console.log()`, `console.error()`, `console.warn()`, `console.table()`, `console.time()`, `console.group()`, `console.dir()`. Tanım. Hata Ayıklama. Örnek.
- **`"use strict"` Modu**: Tanım. Katı Mod Kuralları. Neden Kullanılmalı? Örnek.
 
---
 
### JavaScript : Değişkenler ve Veri Tipleri
- **Değişken Nedir?**: Tanım. Bellek ve Değer. Kullanım Senaryoları.
- **Değişken Tanımlama**
  - **`var`**: Tanım. Function Scope. Hoisting. Neden Artık Tercih Edilmemeli? Örnek.
  - **`let`**: Tanım. Block Scope. Tanım. Örnek.
  - **`const`**: Tanım. Sabit Değer. Referans Tipler İçin Dikkat. Örnek.
  - **`var` vs `let` vs `const`**: Farkları. Tablo Halinde.
- **Hoisting**: Tanım. `var`, `let`, `const`, `function` Davranışları. Temporal Dead Zone (TDZ). Örnek.
- **Primitive (İlkel) Veri Tipleri**
  - **`string`**: Tanım. Tek Tırnak, Çift Tırnak, Backtick. Örnek.
  - **`number`**: Tanım. Tam Sayı ve Ondalıklı. `Infinity`, `-Infinity`, `NaN`. Örnek.
  - **`bigint`**: Tanım. Büyük Sayılar. `n` Soneki. Örnek.
  - **`boolean`**: `true`, `false`. Tanım. Örnek.
  - **`undefined`**: Tanım. Değer Atanmamış. Örnek.
  - **`null`**: Tanım. Bilerek Boş Bırakma. `undefined` ile Farkı. Örnek.
  - **`symbol`**: Tanım. Benzersiz Tanımlayıcı. `Symbol()`. Örnek.
- **`typeof` Operatörü**: Tanım. Her Tip İçin Sonuçları. `typeof null` Sorunu. Örnek.
- **Tip Dönüşümü (Type Conversion)**
  - **Açık Dönüşüm (Explicit)**: `String()`, `Number()`, `Boolean()`, `parseInt()`, `parseFloat()`. Tanım. Örnek.
  - **Örtük Dönüşüm (Implicit / Coercion)**: `+` Operatörü. Truthy/Falsy. Tanım. Örnek.
  - **Truthy ve Falsy Değerler**: Tanım. Tam Liste. Tablo Halinde. Örnek.
- **İsimlendirme Kuralları**: camelCase. Geçerli Karakterler. Rezerve Kelimeler. Tanım. Tablo Halinde.
 
---
 
### JavaScript : Operatörler
- **Aritmetik Operatörler**: `+`, `-`, `*`, `/`, `%`, `**`. `++`, `--` (Prefix/Postfix). Tanım. Örnek.
- **Atama Operatörleri**: `=`, `+=`, `-=`, `*=`, `/=`, `%=`, `**=`, `&&=`, `||=`, `??=`. Tanım. Örnek.
- **Karşılaştırma Operatörleri**: `==`, `===`, `!=`, `!==`, `>`, `<`, `>=`, `<=`. Tanım. `==` vs `===` Farkı. Tablo Halinde. Örnek.
- **Mantıksal Operatörler**: `&&`, `||`, `!`. Short-Circuit Evaluation. Tanım. Örnek.
- **Nullish Coalescing Operatörü**: `??`. `||` ile Farkı. Tanım. Örnek.
- **Optional Chaining**: `?.`. Tanım. Güvenli Erişim. Örnek.
- **Ternary Operatörü**: `koşul ? değer1 : değer2`. Tanım. Örnek.
- **Bitwise Operatörler**: `&`, `|`, `^`, `~`, `<<`, `>>`, `>>>`. Tanım. Örnek.
- **String Birleştirme**: `+` Operatörü. Template Literals ile Farkı. Tanım. Örnek.
- **Virgül Operatörü**: `,`. Tanım. Örnek.
- **`in` Operatörü**: Nesne İçinde Anahtar Kontrolü. Tanım. Örnek.
- **`instanceof` Operatörü**: Tanım. Örnek.
- **Spread Operatörü**: `...`. Dizi ve Nesne Yayılımı. Tanım. Örnek.
- **Rest Parametresi**: `...args`. Tanım. Spread ile Farkı. Örnek.
 
---
 
### JavaScript : String İşlemleri
- **String Tanımlama**: Tek Tırnak. Çift Tırnak. Backtick. Tanım. Örnek.
- **Template Literals (Şablon Dizgeleri)**: Backtick. `${}` ile İfade Gömme. Çok Satırlı String. Tanım. Örnek.
- **Kaçış Karakterleri (Escape Characters)**: `\'`, `\"`, `\\`, `\n`, `\t`, `\r`. Tanım. Örnek.
- **String Özellikleri ve Metodları**
  - **`length`**: Tanım. Örnek.
  - **Karakter Erişimi**: `[]`, `charAt()`, `charCodeAt()`, `at()`. Tanım. Örnek.
  - **Arama**: `indexOf()`, `lastIndexOf()`, `includes()`, `startsWith()`, `endsWith()`, `search()`. Tanım. Örnek.
  - **Kesme**: `slice()`, `substring()`, `substr()`. Tanım. Farkları. Örnek.
  - **Değiştirme**: `replace()`, `replaceAll()`. Regex ile Kullanım. Tanım. Örnek.
  - **Dönüştürme**: `toUpperCase()`, `toLowerCase()`, `trim()`, `trimStart()`, `trimEnd()`. Tanım. Örnek.
  - **Bölme ve Birleştirme**: `split()`, `concat()`. Tanım. Örnek.
  - **Tekrarlama ve Doldurma**: `repeat()`, `padStart()`, `padEnd()`. Tanım. Örnek.
  - **`match()` ve `matchAll()`**: Regex ile Eşleşme. Tanım. Örnek.
  - **`localeCompare()`**: Yerel Karşılaştırma. Türkçe Sıralama. Tanım. Örnek.
- **String Immutability**: Değişmezlik. Tanım. Yeni String Oluşturma. Örnek.
 
---
 
### JavaScript : Karar ve Döngü Yapıları
- **Karar Yapıları**
  - **`if` / `else if` / `else`**: Tanım. Örnek.
  - **`switch` / `case` / `default`**: Tanım. `break`. Fall-Through. Örnek.
  - **Ternary Operatörü**: Kısa Koşul. Tanım. Örnek.
- **Döngü Yapıları**
  - **`for` Döngüsü**: Tanım. `initialization; condition; increment`. Örnek.
  - **`while` Döngüsü**: Tanım. Örnek.
  - **`do...while` Döngüsü**: Tanım. `while` ile Farkı. Örnek.
  - **`for...in` Döngüsü**: Nesne Anahtarlarını Döngüleme. Tanım. Örnek.
  - **`for...of` Döngüsü**: İterable Değerleri Döngüleme. `for...in` ile Farkı. Tanım. Örnek.
  - **`break` ve `continue`**: Tanım. Etiketli (Labeled) Kullanım. Örnek.
 
---
 
### JavaScript : Diziler (Arrays)
- **Dizi Nedir?**: Tanım. Sıralı Koleksiyon. `[]` Sözdizimi. Örnek.
- **Dizi Oluşturma**: Literal. `new Array()`. `Array.of()`. `Array.from()`. Tanım. Örnek.
- **Elemana Erişim ve Değiştirme**: `[]` İndeksle. `at()`. Tanım. Örnek.
- **Dizi Özellikleri**: `length`. Tanım. Örnek.
- **Ekleme ve Çıkarma Metodları**
  - **`push()` ve `pop()`**: Sondan. Tanım. Örnek.
  - **`unshift()` ve `shift()`**: Baştan. Tanım. Örnek.
  - **`splice()`**: Herhangi Bir Konumdan. Ekleme, Silme, Değiştirme. Tanım. Örnek.
- **Arama Metodları**: `indexOf()`, `lastIndexOf()`, `includes()`, `find()`, `findIndex()`, `findLast()`, `findLastIndex()`. Tanım. Örnek.
- **Sıralama ve Ters Çevirme**: `sort()`. Karşılaştırma Fonksiyonu. `reverse()`. `toSorted()`, `toReversed()`. Tanım. Örnek.
- **Dönüştürme Metodları**
  - **`map()`**: Her Eleman İçin Dönüşüm. Yeni Dizi Döner. Tanım. Örnek.
  - **`filter()`**: Koşula Uyan Elemanlar. Yeni Dizi Döner. Tanım. Örnek.
  - **`reduce()` ve `reduceRight()`**: Biriktirme. Tanım. Accumulator, CurrentValue. Örnek.
  - **`forEach()`**: Her Eleman İçin İşlem. Değer Döndürmez. Tanım. `map()` ile Farkı. Örnek.
  - **`flat()` ve `flatMap()`**: İç İçe Dizileri Düzleştirme. Tanım. Örnek.
- **Diğer Metodlar**: `concat()`, `slice()`, `join()`, `fill()`, `copyWithin()`, `every()`, `some()`. Tanım. Örnek.
- **Dizi Kopyalama**: Shallow Copy. `[...arr]`, `Array.from()`, `slice()`. Deep Copy. `structuredClone()`. Tanım. Örnek.
- **Destructuring (Yapı Bozma)**: Dizi Destructuring. Varsayılan Değerler. Swap. Rest ile Kullanım. Tanım. Örnek.
 
---
 
### JavaScript : Nesneler (Objects)
- **Nesne Nedir?**: Tanım. Anahtar-Değer Çifti. `{}` Sözdizimi. Örnek.
- **Nesne Oluşturma**: Literal. `new Object()`. `Object.create()`. Tanım. Örnek.
- **Özellik Erişimi**: Nokta Notasyonu (`.`). Köşeli Parantez (`[]`). Tanım. Farkları. Örnek.
- **Özellik Ekleme, Değiştirme, Silme**: Dinamik Ekleme. `delete` Operatörü. Tanım. Örnek.
- **Kısaltmalar (Shorthand)**: Property Shorthand. Method Shorthand. Computed Property Names. Tanım. Örnek.
- **Nesne Metodları**
  - **`Object.keys()`**: Anahtarlar Dizisi. Tanım. Örnek.
  - **`Object.values()`**: Değerler Dizisi. Tanım. Örnek.
  - **`Object.entries()`**: `[anahtar, değer]` Çiftleri. Tanım. Örnek.
  - **`Object.fromEntries()`**: Entries'den Nesne Oluşturma. Tanım. Örnek.
  - **`Object.assign()`**: Nesne Birleştirme. Shallow Copy. Tanım. Örnek.
  - **`Object.freeze()`**: Değiştirilemez Nesne. Tanım. Shallow Freeze. Örnek.
  - **`Object.seal()`**: Yeni Özellik Eklenemez ama Değiştirilebilir. Tanım. Örnek.
  - **`Object.defineProperty()`**: Özellik Tanımlayıcılar. `writable`, `enumerable`, `configurable`. Getter/Setter. Tanım. Örnek.
  - **`Object.getOwnPropertyDescriptor()`**: Tanım. Örnek.
  - **`hasOwnProperty()` ve `in` Operatörü**: Tanım. Farkları. Örnek.
- **Nesne Destructuring**: Tanım. Yeniden İsimlendirme. Varsayılan Değerler. İç İçe. Rest ile Kullanım. Örnek.
- **Spread ile Nesne Kopyalama ve Birleştirme**: `{...obj}`. Tanım. Örnek.
- **`this` Anahtar Kelimesi**: Tanım. Farklı Bağlamlarda `this`. Global, Method, Constructor. Örnek.
  - **`call()`, `apply()`, `bind()`**: `this` Bağlamını Değiştirme. Tanım. Farkları. Örnek.
- **Getter ve Setter**: `get` ve `set` Anahtar Kelimeleri. Tanım. Örnek.
 
---
 
### JavaScript : Fonksiyonlar
- **Fonksiyon Nedir?**: Tanım. Yeniden Kullanılabilir Kod. Örnek.
- **Fonksiyon Tanımlama Yöntemleri**
  - **Function Declaration**: `function isim() {}`. Hoisting. Tanım. Örnek.
  - **Function Expression**: `const isim = function() {}`. Tanım. Örnek.
  - **Arrow Function**: `const isim = () => {}`. Tanım. `this` Davranışı. Kısa Sözdizimi. Örnek.
  - **Declaration vs Expression vs Arrow**: Farkları. Tablo Halinde.
- **Parametreler ve Argümanlar**
  - **Varsayılan Parametreler (Default Parameters)**: Tanım. Örnek.
  - **Rest Parametresi**: `...args`. Tanım. Örnek.
  - **`arguments` Nesnesi**: Tanım. Arrow Function'da Olmayışı. Örnek.
  - **Destructuring Parametreler**: Nesne ve Dizi Parametresi. Tanım. Örnek.
- **Return Değeri**: `return`. Tanım. Birden Fazla Değer Döndürme (Nesne/Dizi ile). Örnek.
- **Scope (Kapsam)**
  - **Global Scope**: Tanım. Örnek.
  - **Function Scope**: Tanım. Örnek.
  - **Block Scope**: `let`, `const`. Tanım. Örnek.
  - **Lexical Scope**: Tanım. Örnek.
- **Closure (Kapanış)**: Tanım. İç Fonksiyonun Dış Scope'a Erişimi. Pratik Kullanım. Özel Değişken. Örnek.
- **IIFE (Immediately Invoked Function Expression)**: `(function() {})()`. Tanım. Kullanım Senaryoları. Örnek.
- **Higher-Order Functions**: Fonksiyonu Parametre Alan veya Döndüren Fonksiyonlar. `map`, `filter`, `reduce`. Tanım. Örnek.
- **Callback Fonksiyonlar**: Tanım. Kullanım Senaryoları. Örnek.
- **Pure Functions**: Tanım. Yan Etki Yok. Aynı Girdi = Aynı Çıktı. Örnek.
- **Recursion (Özyineleme)**: Tanım. Base Case. Örnek. Stack Overflow Riski.
- **Generator Functions**: `function*`. `yield`. Tanım. Lazy Evaluation. Örnek.
 
---
 
### JavaScript : OOP (Nesne Yönelimli Programlama)
- **JS'de OOP**: Tanım. Prototype-Based vs Class-Based. C++ ile Karşılaştırma.
- **Constructor Functions**: `new` Anahtar Kelimesi. Tanım. Örnek.
- **Prototype**: `__proto__`. `prototype`. Tanım. Prototype Chain. Örnek.
  - **Prototype Kalıtımı**: `Object.create()`. Tanım. Örnek.
  - **Prototype Metod Ekleme**: Tanım. Bellek Avantajı. Örnek.
- **`class` Sözdizimi (ES6)**
  - **Sınıf Tanımlama**: `class`. `constructor`. Tanım. Syntactic Sugar. Örnek.
  - **Metodlar**: Tanım. Örnek.
  - **Getter ve Setter**: Tanım. Örnek.
  - **Statik Metodlar ve Özellikler**: `static`. Tanım. Örnek.
  - **Özel Alanlar (Private Fields)**: `#` Prefix. Tanım. Örnek.
  - **Özel Metodlar (Private Methods)**: `#method()`. Tanım. Örnek.
- **Kalıtım (Inheritance)**: `extends`. `super()`. Tanım. Metod Override. Örnek.
- **`instanceof` ve `typeof`**: Tanım. Farkları. Örnek.
- **Mixin Pattern**: Tanım. Çoklu Kalıtım Alternatifi. `Object.assign()` ile. Örnek.
 
---
 
### JavaScript : DOM Manipülasyonu
- **DOM Nedir?**: Document Object Model. Tanım. Ağaç Yapısı. Node Türleri. Örnek.
- **Eleman Seçme**
  - **`document.getElementById()`**: Tanım. Örnek.
  - **`document.getElementsByClassName()`**: HTMLCollection. Tanım. Örnek.
  - **`document.getElementsByTagName()`**: Tanım. Örnek.
  - **`document.querySelector()`**: CSS Seçici ile. İlk Eşleşme. Tanım. Örnek.
  - **`document.querySelectorAll()`**: NodeList. Tanım. Örnek.
  - **HTMLCollection vs NodeList**: Canlı vs Statik. Farkları. Tablo Halinde.
- **DOM Gezinme (Traversal)**
  - **`parentNode` ve `parentElement`**: Üst Düğüm. Tanım. Örnek.
  - **`children` ve `childNodes`**: Alt Düğümler. Farkları. Tanım. Örnek.
  - **`firstChild` / `firstElementChild`**: Tanım. Örnek.
  - **`lastChild` / `lastElementChild`**: Tanım. Örnek.
  - **`nextSibling` / `nextElementSibling`**: Kardeş Düğüm. Tanım. Örnek.
  - **`previousSibling` / `previousElementSibling`**: Tanım. Örnek.
  - **`closest()`**: En Yakın Ebeveyn (CSS Seçici ile). Tanım. Örnek.
- **DOM Değiştirme**
  - **`textContent` ve `innerText`**: Metin İçerik. Farkları. Tanım. Örnek.
  - **`innerHTML`**: HTML İçerik. Güvenlik (XSS). Tanım. Örnek.
  - **`outerHTML`**: Tanım. Örnek.
  - **`setAttribute()` ve `getAttribute()`**: Attribute Yönetimi. Tanım. Örnek.
  - **`removeAttribute()`**: Tanım. Örnek.
  - **`dataset`**: `data-*` Attribute'lara Erişim. Tanım. Örnek.
  - **`classList`**: `add()`, `remove()`, `toggle()`, `contains()`, `replace()`. Tanım. Örnek.
  - **`style`**: Inline Stil Değiştirme. `element.style.property`. Tanım. Örnek.
  - **`getComputedStyle()`**: Hesaplanmış Stil Okuma. Tanım. Örnek.
- **DOM Eleman Oluşturma ve Silme**
  - **`document.createElement()`**: Tanım. Örnek.
  - **`document.createTextNode()`**: Tanım. Örnek.
  - **`appendChild()` ve `append()`**: Eleman Ekleme. Farkları. Tanım. Örnek.
  - **`prepend()`**: Başa Ekleme. Tanım. Örnek.
  - **`insertBefore()`**: Belirli Bir Yere Ekleme. Tanım. Örnek.
  - **`before()` ve `after()`**: Kardeş Olarak Ekleme. Tanım. Örnek.
  - **`replaceChild()` ve `replaceWith()`**: Eleman Değiştirme. Tanım. Örnek.
  - **`removeChild()` ve `remove()`**: Eleman Silme. Tanım. Örnek.
  - **`cloneNode()`**: Eleman Kopyalama. `deep` Parametresi. Tanım. Örnek.
  - **`document.createDocumentFragment()`**: Fragment ile Toplu Ekleme. Performans. Tanım. Örnek.
 
---
 
### JavaScript : Olaylar (Events)
- **Olay Nedir?**: Tanım. Kullanıcı Etkileşimi. Tarayıcı Olayları. Örnek.
- **Olay Dinleme Yöntemleri**
  - **Inline Event Handler**: `onclick="..."`. Tanım. Neden Tercih Edilmemeli? Örnek.
  - **DOM Property**: `element.onclick = function`. Tanım. Örnek.
  - **`addEventListener()`**: Tanım. Çoklu Dinleyici. Üçüncü Parametre. Örnek.
  - **`removeEventListener()`**: Tanım. Anonim Fonksiyon Sorunu. Örnek.
- **Olay Nesnesi (`event`)**: Tanım. Otomatik Parametre. Örnek.
  - **`event.target` ve `event.currentTarget`**: Tanım. Farkları. Örnek.
  - **`event.type`**: Olay Türü. Tanım. Örnek.
  - **`event.preventDefault()`**: Varsayılan Davranışı Engelleme. Form Submit. Link. Tanım. Örnek.
  - **`event.stopPropagation()`**: Yayılımı Durdurma. Tanım. Örnek.
  - **`event.stopImmediatePropagation()`**: Tanım. Örnek.
- **Olay Yayılımı (Event Propagation)**
  - **Capturing (Yakalama)**: Tanım. Yukarıdan Aşağı. Örnek.
  - **Bubbling (Kabarcıklanma)**: Tanım. Aşağıdan Yukarı. Örnek.
  - **`addEventListener` Üçüncü Parametre**: `capture`, `once`, `passive`. Tanım. Örnek.
- **Olay Delegasyonu (Event Delegation)**: Tanım. Üst Elemanda Dinleme. Performans Avantajı. Dinamik Elemanlar. Örnek.
- **Yaygın Olay Türleri**
  - **Mouse Olayları**: `click`, `dblclick`, `mousedown`, `mouseup`, `mousemove`, `mouseenter`, `mouseleave`, `mouseover`, `mouseout`, `contextmenu`. Tanım. Örnek.
  - **Klavye Olayları**: `keydown`, `keyup`, `keypress` (Deprecated). `event.key`, `event.code`. Tanım. Örnek.
  - **Form Olayları**: `submit`, `reset`, `change`, `input`, `focus`, `blur`, `focusin`, `focusout`. Tanım. Örnek.
  - **Pencere Olayları**: `load`, `DOMContentLoaded`, `resize`, `scroll`, `beforeunload`, `unload`, `hashchange`, `popstate`. Tanım. Farkları. Örnek.
  - **Dokunmatik Olaylar**: `touchstart`, `touchmove`, `touchend`, `touchcancel`. Tanım. Örnek.
  - **Clipboard Olayları**: `copy`, `cut`, `paste`. Tanım. Örnek.
  - **Drag Olayları**: `drag`, `dragstart`, `dragend`, `dragover`, `dragenter`, `dragleave`, `drop`. Tanım. Örnek.
- **Custom Events (Özel Olaylar)**: `new CustomEvent()`. `dispatchEvent()`. `detail` Özelliği. Tanım. Örnek.
- **Debounce ve Throttle**: Tanım. Performans. Scroll ve Resize İçin. Farkları. Örnek.
 
---
 
### JavaScript : Hata Yönetimi
- **Hata Türleri**: `SyntaxError`, `ReferenceError`, `TypeError`, `RangeError`, `URIError`, `EvalError`. Tanım. Tablo Halinde.
- **`try` / `catch` / `finally`**: Tanım. Sözdizimi. Örnek.
- **`throw` İfadesi**: Manuel Hata Fırlatma. Tanım. Örnek.
- **Error Nesnesi**: `message`, `name`, `stack`. Tanım. Örnek.
- **Özel Hata Sınıfı Oluşturma**: `extends Error`. Tanım. Örnek.
- **`try...catch` ile Asenkron Hatalar**: `async/await` İçinde Kullanım. Tanım. Örnek.
 
---
 
### JavaScript : Asenkron Programlama
- **Asenkron Nedir?**: Tanım. Senkron vs Asenkron. Blocking vs Non-Blocking. Neden Gerekli? Örnek.
- **Event Loop Detaylı**: Call Stack. Web APIs. Callback Queue. Microtask Queue. Tanım. Çalışma Sırası. Örnek.
- **Callback'ler**: Tanım. Callback Hell (Piramit Sorunu). Örnek.
- **Promise (Söz)**
  - **Promise Nedir?**: Tanım. `pending`, `fulfilled`, `rejected` Durumları. Örnek.
  - **Promise Oluşturma**: `new Promise((resolve, reject) => {})`. Tanım. Örnek.
  - **`.then()` ve `.catch()`**: Tanım. Zincirleme (Chaining). Örnek.
  - **`.finally()`**: Tanım. Her Durumda Çalışır. Örnek.
  - **`Promise.all()`**: Tüm Promise'ler Tamamlanınca. Tanım. Örnek.
  - **`Promise.allSettled()`**: Tümü Sonuçlanınca (Başarılı veya Başarısız). Tanım. Örnek.
  - **`Promise.race()`**: İlk Sonuçlanan. Tanım. Örnek.
  - **`Promise.any()`**: İlk Başarılı. Tanım. Örnek.
  - **`Promise.resolve()` ve `Promise.reject()`**: Tanım. Örnek.
- **`async` / `await`**
  - **`async` Fonksiyon**: Tanım. Her Zaman Promise Döner. Örnek.
  - **`await` Anahtar Kelimesi**: Tanım. Promise Bekletme. Örnek.
  - **Hata Yönetimi**: `try...catch` ile. Tanım. Örnek.
  - **Paralel `await`**: `Promise.all()` ile Birlikte. Tanım. Örnek.
  - **Top-Level Await**: Modül İçinde. Tanım. Örnek.
- **Zamanlayıcılar (Timers)**
  - **`setTimeout()`**: Tanım. `clearTimeout()`. Örnek.
  - **`setInterval()`**: Tanım. `clearInterval()`. Örnek.
  - **`requestAnimationFrame()`**: Tanım. Animasyon İçin. `cancelAnimationFrame()`. Örnek.
 
---
 
### JavaScript : Fetch API ve HTTP İstekleri
- **Fetch API Nedir?**: Tanım. XMLHttpRequest ile Farkı. Kullanım Senaryoları.
- **`fetch()` Fonksiyonu**: Tanım. Promise Döner. Sözdizimi. Örnek.
- **GET İsteği**: Tanım. Varsayılan Metod. Örnek.
- **Response Nesnesi**: `status`, `ok`, `headers`, `statusText`. Tanım. Örnek.
  - **`response.json()`**: JSON Ayrıştırma. Tanım. Örnek.
  - **`response.text()`**: Düz Metin. Tanım. Örnek.
  - **`response.blob()`**: Binary Veri. Tanım. Örnek.
- **POST İsteği**: `method`, `headers`, `body`. `JSON.stringify()`. Tanım. Örnek.
- **PUT, PATCH, DELETE İstekleri**: Tanım. Örnek.
- **Headers Yönetimi**: `Content-Type`. `Authorization`. `new Headers()`. Tanım. Örnek.
- **FormData ile Dosya Gönderme**: `new FormData()`. `append()`. Tanım. Örnek.
- **CORS (Cross-Origin Resource Sharing)**: Tanım. Neden Hata Verir? Çözüm Yolları. Örnek.
- **AbortController ile İstek İptali**: `AbortController()`. `signal`. `abort()`. Tanım. Timeout. Örnek.
- **`async/await` ile Fetch Kullanımı**: Tanım. Hata Yönetimi. Örnek.
 
---
 
### JavaScript : JSON
- **JSON Nedir?**: JavaScript Object Notation. Tanım. Veri Formatı. Kullanım Senaryoları.
- **JSON Sözdizimi**: Kurallar. Geçerli Veri Tipleri. Tanım. Örnek.
- **`JSON.stringify()`**: Nesneyi JSON String'e Çevirme. `replacer`. `space`. Tanım. Örnek.
- **`JSON.parse()`**: JSON String'i Nesneye Çevirme. `reviver`. Tanım. Örnek.
- **Deep Clone**: `JSON.parse(JSON.stringify())`. Kısıtlamaları. `structuredClone()` Alternatifi. Tanım. Örnek.
 
---
 
### JavaScript : Web Storage ve Veri Saklama
- **Web Storage API**: Tanım. Cookie ile Farkı. Tablo Halinde.
- **localStorage**
  - **`setItem()`**: Tanım. Örnek.
  - **`getItem()`**: Tanım. Örnek.
  - **`removeItem()`**: Tanım. Örnek.
  - **`clear()`**: Tanım. Örnek.
  - **`key()`**: Tanım. Örnek.
  - **Nesne ve Dizi Saklama**: `JSON.stringify()` ve `JSON.parse()` ile. Tanım. Örnek.
- **sessionStorage**: Tanım. localStorage ile Farkı. Oturum Süresi. Örnek.
- **Cookie'ler**
  - **Cookie Nedir?**: Tanım. Sunucuya Gönderilmesi. Web Storage ile Farkı. Boyut Limiti.
  - **`document.cookie`**: Tanım. Okuma. Yazma. Silme. Örnek.
  - **Cookie Attribute'ları**: `expires`, `max-age`, `path`, `domain`, `secure`, `SameSite`, `HttpOnly`. Tanım. Tablo Halinde. Örnek.
- **IndexedDB**: Tanım. Büyük Veri. Asenkron API. `open()`, `createObjectStore()`, `transaction()`. Kullanım Senaryoları. Örnek.
 
---
 
### JavaScript : Modüller (Modules)
- **Modül Nedir?**: Tanım. Neden Gerekli? Kod Organizasyonu.
- **ES Modules (ESM)**
  - **`export`**: Named Export. Default Export. Tanım. Farkları. Örnek.
  - **`import`**: Named Import. Default Import. `* as` ile Tümünü İçe Aktarma. Tanım. Örnek.
  - **`import()` Dinamik İçe Aktarma**: Lazy Loading. Tanım. Koşullu Import. Örnek.
  - **`<script type="module">`**: Tanım. Tarayıcıda Modül. `defer` Davranışı. Örnek.
- **Eski Yöntem: CommonJS**: `require()`. `module.exports`. Tanım. ESM ile Farkı. Node.js Kullanımı.
- **Modül Desenleri (Patterns)**: Revealing Module. Barrel Export. Re-Export. Tanım. Örnek.
 
---
 
### JavaScript : Regular Expressions (Düzenli İfadeler)
- **RegExp Nedir?**: Tanım. Desen Eşleştirme. Kullanım Senaryoları.
- **RegExp Oluşturma**: Literal (`/pattern/flags`). Constructor (`new RegExp()`). Tanım. Farkları. Örnek.
- **Bayraklar (Flags)**: `g` (global), `i` (case-insensitive), `m` (multiline), `s` (dotAll), `u` (unicode), `d` (indices). Tanım. Tablo Halinde. Örnek.
- **Karakter Sınıfları**: `\d`, `\D`, `\w`, `\W`, `\s`, `\S`, `.`. Tanım. Tablo Halinde. Örnek.
- **Özel Karakterler**: `^`, `$`, `\b`, `\B`. Tanım. Sınırlar. Örnek.
- **Niceleyiciler (Quantifiers)**: `*`, `+`, `?`, `{n}`, `{n,}`, `{n,m}`. Greedy vs Lazy (`?`). Tanım. Örnek.
- **Gruplar ve Yakalama**: `()`. Named Groups `(?<name>)`. Non-Capturing `(?:)`. Backreference `\1`. Tanım. Örnek.
- **Alternatif (Alternation)**: `|`. Tanım. Örnek.
- **Lookahead ve Lookbehind**: `(?=)`, `(?!)`, `(?<=)`, `(?<!)`. Tanım. Örnek.
- **String Metodlarıyla Kullanım**: `match()`, `matchAll()`, `search()`, `replace()`, `replaceAll()`, `split()`, `test()`, `exec()`. Tanım. Örnek.
- **Yaygın RegExp Desenleri**: E-posta. URL. Telefon. Şifre Doğrulama. Tanım. Örnek.
 
---
 
### JavaScript : Tarih ve Zaman (Date)
- **`Date` Nesnesi**: Tanım. `new Date()`. Epoch (Unix Timestamp). Örnek.
- **Date Oluşturma Yöntemleri**: Parametre ile. String ile. Timestamp ile. Tanım. Örnek.
- **Get Metodları**: `getFullYear()`, `getMonth()`, `getDate()`, `getDay()`, `getHours()`, `getMinutes()`, `getSeconds()`, `getMilliseconds()`, `getTime()`, `getTimezoneOffset()`. Tanım. Örnek.
- **Set Metodları**: `setFullYear()`, `setMonth()`, `setDate()`, `setHours()`, `setMinutes()`, `setSeconds()`, `setMilliseconds()`. Tanım. Örnek.
- **Date Formatlama**: `toLocaleDateString()`, `toLocaleTimeString()`, `toLocaleString()`, `toISOString()`, `toUTCString()`. Tanım. `Intl.DateTimeFormat`. Örnek.
- **Date Karşılaştırma ve Hesaplama**: Fark Hesaplama. Gün Ekleme. Tanım. Örnek.
- **`Date.now()`**: Tanım. Performans Ölçümü. Örnek.
- **`Intl.RelativeTimeFormat`**: "3 gün önce", "2 saat sonra". Tanım. Örnek.
 
---
 
### JavaScript : Map, Set ve Diğer Koleksiyonlar
- **`Map`**: Tanım. Object ile Farkı. Herhangi Bir Tip Anahtar. Sıralı.
  - **Metodlar**: `set()`, `get()`, `has()`, `delete()`, `clear()`, `size`, `keys()`, `values()`, `entries()`, `forEach()`. Tanım. Örnek.
- **`WeakMap`**: Tanım. Map ile Farkı. Garbage Collection. Kullanım Senaryoları. Örnek.
- **`Set`**: Tanım. Benzersiz Değerler. Dizi ile Farkı.
  - **Metodlar**: `add()`, `has()`, `delete()`, `clear()`, `size`, `keys()`, `values()`, `entries()`, `forEach()`. Tanım. Örnek.
  - **Dizi Benzersizleştirme**: `[...new Set(arr)]`. Tanım. Örnek.
- **`WeakSet`**: Tanım. Set ile Farkı. Garbage Collection. Örnek.
- **`WeakRef` ve `FinalizationRegistry`**: Zayıf Referans. Tanım. Bellek Yönetimi. Örnek.
 
---
 
### JavaScript : İteratörler ve Generatörler
- **Iterable Protokolü**: `Symbol.iterator`. Tanım. `for...of` ile Kullanım. Örnek.
- **Iterator Protokolü**: `next()`. `{ value, done }`. Tanım. Örnek.
- **Özel Iterable Oluşturma**: Tanım. Sınıf veya Nesne ile. Örnek.
- **Generator Fonksiyonlar**: `function*`. `yield`. Tanım. Lazy Evaluation. Örnek.
  - **`yield*` ile Delegasyon**: Tanım. Örnek.
  - **Generator ile `next(value)`**: Değer Gönderme. Tanım. Örnek.
  - **`return()` ve `throw()`**: Generator'ı Sonlandırma. Tanım. Örnek.
- **Async Generator**: `async function*`. `for await...of`. Tanım. Asenkron Veri Akışı. Örnek.
 
---
 
### JavaScript : Proxy ve Reflect
- **`Proxy` Nedir?**: Tanım. Nesne İşlemlerini Kesme (Intercept). Kullanım Senaryoları.
- **Proxy Oluşturma**: `new Proxy(target, handler)`. Tanım. Örnek.
- **Handler Tuzakları (Traps)**
  - **`get`**: Özellik Okuma. Tanım. Örnek.
  - **`set`**: Özellik Yazma. Doğrulama (Validation). Tanım. Örnek.
  - **`has`**: `in` Operatörü. Tanım. Örnek.
  - **`deleteProperty`**: `delete` Operatörü. Tanım. Örnek.
  - **`apply`**: Fonksiyon Çağrısı. Tanım. Örnek.
  - **`construct`**: `new` Operatörü. Tanım. Örnek.
- **`Reflect` API**: Tanım. Proxy ile Birlikte Kullanım. `Reflect.get()`, `Reflect.set()`, `Reflect.has()`. Örnek.
- **Pratik Kullanımlar**: Reactive Veri. Doğrulama. Loglama. Negatif İndeks. Tanım. Örnek.
 
---
 
### JavaScript : Hata Ayıklama ve Performans
- **Hata Ayıklama (Debugging)**
  - **`console` Metodları**: `log`, `error`, `warn`, `table`, `trace`, `time/timeEnd`, `group/groupEnd`, `assert`, `count`. Tanım. Örnek.
  - **`debugger` İfadesi**: Tanım. Breakpoint. Örnek.
  - **Chrome DevTools Kullanımı**: Sources Paneli. Breakpoints. Watch. Call Stack. Network. Tanım. Örnek.
  - **Source Maps**: Tanım. Minified Kod Hata Ayıklama. Örnek.
- **Performans Optimizasyonu**
  - **DOM Manipülasyonu Minimizasyonu**: DocumentFragment. Toplu Güncelleme. Tanım. Örnek.
  - **Debounce ve Throttle**: Tanım. Tekrar. Scroll ve Input İçin. Örnek.
  - **Lazy Loading**: Görseller. Modüller. `import()`. Intersection Observer. Tanım. Örnek.
  - **Bellek Yönetimi**: Garbage Collection. Memory Leak Kaynakları. Closure Sızıntısı. Event Listener Temizliği. Tanım. Örnek.
  - **Web Workers ile Ağır Hesaplamalar**: Tanım. Ana İş Parçacığını Engelleme. Örnek.
  - **`requestAnimationFrame()`**: Animasyon Performansı. `setTimeout` ile Farkı. Tanım. Örnek.
  - **Performance API**: `performance.now()`, `performance.mark()`, `performance.measure()`. Tanım. Örnek.
 
---
 
### JavaScript : Güvenlik
- **XSS (Cross-Site Scripting)**: Tanım. Türleri (Stored, Reflected, DOM-Based). Korunma Yolları.
  - **innerHTML Tehlikesi**: Tanım. `textContent` Alternatifi. Örnek.
  - **Input Sanitization**: Tanım. Özel Karakterleri Escape Etme. Örnek.
  - **Content Security Policy (CSP)**: Tanım. `<meta>` ile Kullanım. Örnek.
- **CSRF (Cross-Site Request Forgery)**: Tanım. Token ile Korunma. Örnek.
- **Clickjacking**: Tanım. `X-Frame-Options`. `frame-ancestors`. Örnek.
- **`eval()` ve `Function()` Tehlikesi**: Tanım. Neden Kullanılmamalı? Alternatifler. Örnek.
- **HTTPS Önemi**: Tanım. Mixed Content Sorunu. Örnek.
- **`rel="noopener noreferrer"`**: `target="_blank"` Güvenliği. Tanım. Örnek.
- **Subresource Integrity (SRI)**: `integrity` Attribute. CDN Güvenliği. Tanım. Örnek.
 
---
 
### Sonsöz
- **Bu Dokümantasyonda Ne Öğrendik?**
- **İlerki Projeler**
- **Diğer Data's Books Dökümantasyonları**
- **Özel Teşekkürler**
 
---
