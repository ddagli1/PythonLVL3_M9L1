# 🍍 Bikini Kasabası Yapay Zeka ile Web Geliştirme Kılavuzu

Bu depo, bir arka yüz (backend) geliştiricisinin bakış açısıyla; yapay zeka (AI) araçlarını en efektif şekilde yönlendirerek **HTML, CSS ve JavaScript** teknolojileriyle dinamik, animasyonlu ve etkileşimli bir **SüngerBob KareŞort** web sitesi inşa etmenin sırlarını barındırır.

Yapay zekayı sadece bir "kod üreticisi" olarak değil, bir "çözüm ortağı" olarak konumlandırmak için tasarlanmış prompt (komut) stratejilerini aşağıda bulabilirsiniz.

---

## 💡 Altın Kurallar: AI ile İletişim Stratejisi

1. **Rol ve Uzmanlık Tanımlayın:** AI'a her zaman bir kimlik verin (Örn: *"Kıdemli bir Frontend Geliştiricisisin"*). Bu, üreteceği kodun modern standartlara uygun olmasını sağlar.
2. **Adım Adım İlerleyin (Iterative Process):** Üç teknolojiyi (HTML, CSS, JS) aynı anda istemeyin. Önce iskeleti (HTML), sonra giydirmeyi (CSS), en son ruhu (JS) inşa ettirin.
3. **Kısıtlamaları ve Temayı Baştan Belirtin:** SüngerBob konseptini, zorunlu proje kriterlerini (buton, animasyon, etkileşim) ilk prompttan itibaren bağlam (context) olarak sunun.

---

## 🛠 Adım Adım Prompt Şablonları

### 🧱 1. Adım: Yapısal Temel (HTML)
Web sitesinin semantik yapısını kurmak ve şablon dosyanızı doldurmak için ilk adımı atın.

> **Prompt:**
> "Sen deneyimli bir frontend geliştiricisisin. SüngerBob KareŞort temalı bir web sitesi için temiz, modern ve semantik bir HTML5 yapısı oluşturmanı istiyorum. Sayfada bir ana başlık, SüngerBob hakkında eğlenceli bir tanıtım metni, karakterin görseli için bir alan, butona basıldığında repliklerin görüneceği boş bir metin alanı ve üzerinde 'Beni Neşelendir!' yazan bir buton bulunmalı. CSS ve JavaScript kodlarımı harici dosyalardan (`style.css` ve `script.js`) bağlayacağım, bu yüzden gerekli `<link>` ve `<script>` etiketlerini doğru şekilde yerleştir."

---

### 🎨 2. Adım: Görsel Tasarım ve Animasyonlar (CSS)
Sitenin Bikini Kasabası atmosferini yansıtmasını sağlama ve animasyon kriterini karşılama adımı.

> **Prompt:**
> "Harika, şimdi oluşturduğumuz bu HTML yapısı için modern ve canlı bir CSS tasarımı hazırlayalım. Renk paleti SüngerBob sarısı (`#FFD700`) ve okyanusun derinliklerini yansıtan mavi tonlarında olmalı. Tasarımın mobil, tablet ve masaüstü ekranlarda kusursuz görünmesi için responsive (uyumlu) kuralları uygula. Ayrıca, projenin animasyon kriterini karşılamak için SüngerBob görseline yukarı-aşağı hafifçe sallanma efekti (floating animation) ekle ve butonun üzerine gelindiğinde (hover) tatlı bir büyüme efekti ver."

---

### ⚡ 3. Adım: Dinamik Etkileşim ve Mantık (JavaScript)
Butona basıldığında bir eylemin tetiklenmesi ve sitenin canlı hissettirmesi adımı.

> **Prompt:**
> "Şimdi sitemize JavaScript ile etkileşim kazandıralım. HTML dosyamızdaki 'Beni Neşelendir!' butonuna tıklandığında (click event listener), sayfadaki boş metin alanında rastgele bir SüngerBob repliği belirmesini istiyorum. JavaScript içinde şu replikleri içeren bir dizi (array) oluştur:
> - 'Ben hazırım!
