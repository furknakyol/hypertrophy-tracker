# 🏋️ Guray's Hypertrophy Max Tracker

Haftalık ağırlık takibi için interaktif dashboard. 12 haftalık progressive overload programı için tasarlandı.

## 🔗 Canlı Demo

<<<<<<< HEAD
🌐 **[https://ismai.github.io/hypertrophy-tracker](https://ismai.github.io/hypertrophy-tracker)**
=======
> 🌐 https://ismai.github.io/hypertrophy-tracker
>>>>>>> b4bc0c0bb59ef40533c2a2ec43bd1184bc951323

---

## ✨ Özellikler

- **Hareket odaklı görünüm** — Günlere göre değil hareketlere göre takip
- **3 grup** — İtiş / Çekiş / Bacak kategorileri
- **İnteraktif çizgi grafik** — X: Hafta, Y: Ağırlık (kg), 5'er aralıklı
- **Çift gün desteği** — Aynı hareketi iki farklı günde yapıyorsan (örn. Triceps PAZ+CUM) tek grafikte iki çizgi
- **Ağırlık üzerinde etiket** — Her veri noktasında kg değeri görünür
- **Excel yükleme** — `.xlsx` dosyasını direkt yükle, veriler otomatik aktarılır
- **Tarayıcı hafızası** — Veriler localStorage'a kaydedilir, sayfa kapansa bile korunur
- **Hücre düzenleme** — Alt tablodaki hücreye tıklayarak ağırlık gir/güncelle

---

## 🚀 Kullanım

### Seçenek 1 — GitHub Pages (önerilen)
1. Bu repoyu fork'la veya kendi hesabına yükle
2. **Settings → Pages → Branch: main → / (root)** seç
3. Birkaç dakika sonra `https://<kullanıcı-adı>.github.io/hypertrophy-tracker` adresinde yayında

### Seçenek 2 — Lokal
```bash
git clone https://github.com/<kullanıcı-adı>/hypertrophy-tracker
# index.html dosyasını tarayıcıda aç
open index.html
```

---

## 📊 Excel'den Veri Aktarma

1. Excel tracker'ını aç (`.xlsx`)
2. Dashboard'da sağ üstteki **⬆ Excel Yükle** butonuna tıkla
3. Dosyayı seç → veriler otomatik aktarılır
4. Veriler tarayıcıya kaydedilir

> **Not:** Excel dosyasındaki sayfa adlarının değişmemiş olması gerekir:
> `PAZARTESİ` · `SALI` · `ÇARŞAMBA` · `CUMA` · `CUMARTESİ`

---

## 🗂️ Program

| Gün | Kas Grubu |
|-----|-----------|
| Pazartesi | İtiş (Göğüs, Omuz, Triceps) |
| Salı | Çekiş (Sırt, Biceps) |
| Çarşamba | Bacak |
| Cuma | İtiş (Tekrar) |
| Cumartesi | Çekiş + Bacak (Tekrar) |

Her 2 antrenman sonunda: **3x10 Cable Crunch / 3x10 Standing Calf Raise**

---

## 🛠️ Teknolojiler

- Vanilla HTML/CSS/JS — sıfır bağımlılık, sıfır build step
- [Chart.js 4.4](https://www.chartjs.org/) — grafik kütüphanesi
- [SheetJS](https://sheetjs.com/) — Excel okuma

---

## 📁 Dosya Yapısı

```
hypertrophy-tracker/
├── index.html      # Tüm uygulama tek dosyada
└── README.md
```
