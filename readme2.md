# 🎮 AI ile Oyun Geliştirme Rehberi

> Yapay zekayı bir kod kölesi değil, yaratıcı bir ekip arkadaşı olarak kullanarak harika oyunlar geliştirmek için adım adım kılavuz.

---

## 💡 Temel Strateji: İteratif (Adım Adım) Geliştirme

Yapay zekaya tüm oyunu tek seferde yazdırmaya çalışmak genellikle hatalı veya eksik kodlarla sonuçlanır. En iyi yaklaşım, oyunu aşamalı olarak inşa etmektir:

```
Fikir ➔ Tasarım ➔ Temel Kod ➔ Mekanik Ekleme ➔ Hata Ayıklama
```

---

## 🛠 Adım Adım Prompt Şablonları

### 🧠 1. Adım: Oyun Fikri Bulma (Beyin Fırtınası)

Eğer aklınızda kesin bir fikir yoksa, AI'dan PyGame Zero sınırlarına uygun yaratıcı fikirler isteyin.

**Prompt:**
```
Sen deneyimli bir bağımsız (indie) oyun geliştiricisisin. PyGame Zero kütüphanesini
kullanarak 2D bir oyun yazmak istiyorum. PyGame Zero'nun yapısına (basit aktör yönetimi,
çizim ve güncelleme döngüleri) uygun, yapımı aşırı karmaşık olmayan ama oynaması aşırı
eğlenceli 3 farklı oyun fikri ve mekaniği önerir misin?
```

---

### 📝 2. Adım: Oyun Tasarımı ve Kuralların Belirlenmesi

Fikri seçtikten sonra oyunun kurallarını ve mantığını netleştirin.
*(Örnek: "Uzay Gemisiyle Meteor Vurma" oyunu)*

**Prompt:**
```
Seçtiğim oyun fikri: Bir uzay gemisiyle yukarıdan gelen meteorları vurma oyunu.
Bu oyun için bana mini bir oyun tasarımı dökümanı (GDD) hazırlar mısın?
Oyunda skor sistemi, can sistemi, meteorların hızlanma dengesi nasıl olmalı?
Teknik olarak hangi aktörlere (Actor) ve değişkenlere ihtiyacım olacak?
```

---

### 🧱 3. Adım: İlk Çalışan Sürüm (MVP)

Sadece ekranda bir şeylerin hareket ettiği, en temel kod yapısını isteyin.

**Prompt:**
```
Harika. Şimdi bu meteor vurma oyunu için PyGame Zero uyumlu ilk temel kodları (game.py)
yazar mısın? Şimdilik sadece ekranda yön tuşlarıyla sağa sola hareket eden bir uzay gemisi
aktörü (player) olsun. Ekran boyutu 800x600 olsun ve draw() ile update() fonksiyonları
temiz bir şekilde tanımlansın. Görseller için şimdilik yer tutucu (placeholder) isimler
kullanabilirsin.
```

---

### 🔄 4. Adım: Kod Geliştirme ve İterasyon

AI'ın ilk verdiği kodu test ettikten sonra eksik veya hatalı kısımları revize ettirin.

**Prompt:**
```
Yazdığın ilk kod çalıştı ancak uzay gemisi ekranın dışına çıkabiliyor, bunu engellemeliyiz.
Ayrıca şimdi oyuna yukarıdan aşağıya rastgele konumlardan süzülen meteor aktörleri ekleyelim.
Meteor ekranın altına ulaştığında canımız 1 azalsın. Bu güncellemeleri koda yansıtır mısın?
```

---

### 🔫 5. Adım: Ana Mekanikleri Ekleme

Oyunun ana döngüsünü tamamlayacak mekanikleri entegre edin.

**Prompt:**
```
Şimdi oyuna ateş etme mekaniği eklemek istiyorum. Oyuncu 'Space' (Boşluk) tuşuna bastığında
uzay gemisinin olduğu konumdan yukarıya doğru giden bir lazer aktörü oluşsun. Eğer lazer
bir meteora çarparsa (colliderect kullanarak) hem meteor hem lazer yok olsun ve skor 10 puan
artsın.
```

---

## 🚀 İleri Seviye Promptlar

### 🔍 Hata Ayıklama (Debugging)

Kod hata verdiğinde panik yapmayın, hatayı AI'a yorumlatın.

**Prompt:**
```
Oyunu çalıştırdığımda şöyle bir hata alıyorum:

  NameError: name 'meteor' is not defined

Kodumun ilgili kısmı şu şekilde:
[İlgili Kod Bloklarını Buraya Yapıştırın]

Bu hatayı PyGame Zero mantığına göre nasıl düzeltebilirim?
```

---

### 🎨 Klasör Yapısı ve Asset Yönetimi

PyGame Zero'nun çalışması için görsel ve ses klasörlerinin doğru yapılandırılması gerekir.

**Prompt:**
```
Yazdığımız bu oyundaki görselleri (uzay gemisi, meteor, lazer) projemde hangi klasör isimleri
altına, hangi formatta kaydetmeliyim? PyGame Zero'nun standart klasör mimarisini açıklar mısın?
```

---

## ✅ Proje Teslim Öncesi Kontrol Listesi

Oyununuzu bitirmeden önce şu maddeleri kontrol edin:

- [ ] `pip install pgzero` kurulumu yapıldı
- [ ] `pgzrun game.py` komutuyla oyun takılmadan başlatılabiliyor
- [ ] Oyunda bir **kazanma (Win)** veya **kaybetme (Game Over)** senaryosu mevcut
- [ ] Tuş kombinasyonları ve kontroller akıcı çalışıyor
- [ ] Gereksiz yorum satırları ve kalıntı AI çıktıları temizlendi

---

> Klavyenize kuvvet! 🕹️
