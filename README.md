# ✈️ Esenyurt BİLSEM — İHA Takımları Web Sitesi

Teknofest 2026 İHA Teknolojileri yarışmasına katılan Esenyurt Bilim ve Sanat Merkezi takımlarının tanıtım sitesi.

---

## 🚀 Canlı Site

> `iha_takilmari.html` dosyasını tarayıcıda aç ya da GitHub Pages'e yükle.

---

## 📁 Dosya Yapısı

```
iha_takilmari.html   → Tek dosya, her şey içinde
README.md            → Bu dosya
```

---

## 👥 Takımlar

| # | Takım | Motto | Danışman |
|---|-------|-------|----------|
| 01 | **YELÇE** | Yerli Elektronik Lider Çoban | Oğuz Güven |
| 02 | **AETHERSIL** | Gökyüzündeki Orman Koruyucusu | Oğuz Güven |
| 03 | **CELEON** | Gökyüzünden İlham Alan | Dr. Muhammed Çiftçi |

> Proje detayları gizlidir. Yarışma sonrasında güncellenebilir.

---

## 🎮 İHA Pilotu Oyunu

Sitede gömülü mini oyun bulunmaktadır.

- **Kontrol:** Fare ile dronu yönlendir
- **Amaç:** Altın halkalardan geç, engellerden kaçın
- **Başlangıç:** 3 saniyelik geri sayım sonrası başlar
- **Çakılma:** Sınır dışına çıkarsan veya engele çarparsan oyun biter

---

## 🛠️ Güncelleme Rehberi

### Yeni takım üyesi eklemek
`iha_takilmari.html` dosyasında ilgili takımın `members-list` div'ini bul, aşağıdaki şablonu kopyala:

```html
<div class="member-row">
  <div class="member-avatar green">AB</div>
  <div class="member-info">
    <div class="member-name">Ad Soyad</div>
    <div class="member-role">Görev</div>
  </div>
</div>
```

Avatar renkleri: `green` → YELÇE, `blue` → AETHERSIL, `red` → CELEON

### Proje bilgilerini açmak (yarışma sonrası)
`classified-wrap` div'ini sil, yerine proje açıklamasını ekle.

### GitHub Pages'e yüklemek
```bash
git add iha_takilmari.html README.md
git commit -m "site güncellendi"
git push
```

---

## 🏫 Kurum

**Esenyurt Bilim ve Sanat Merkezi**  
Teknofest 2026 / İHA Teknolojileri

---

*Yapıldı: Mart 2026*
