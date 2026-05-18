# 📋 Proje Geliştirme Planı

## 🎯 Hedefler

1. **BlackBox AI Kullanımı** - AI asistanı ile kod geliştirme
2. **MD Dosyaları Oluşturma** - README, PLANNING gibi Markdown dokümantasyonu
3. **Skill Eklemeyi Öğrenme** - Web uygulaması geliştirme becerileri

---

## 📝 Görev Listesi

### 1. Faz: Temel Web Uygulaması ✅
- [x] HTML yapısı oluşturma
- [x] CSS stilleri tanımlama
- [x] JavaScript mantığı ekleme

### 2. Faz: Excel Entegrasyonu ✅
- [x] SheetJS kütüphanesi entegrasyonu
- [x] Dosya yükleme özelliği
- [x] Veri parse etme

### 3. Faz: Hesaplama Motoru ✅
- [x] Ders ortalaması hesaplama
- [x] Ağırlıklı ortalama hesaplama
- [x] Genel not ortalaması hesaplama

### 4. Faz: Sonuç Görüntüleme ✅
- [x] Teşekkür/Takdir belirleme
- [x] Renkli sonuç kartları
- [x] Detaylı ders listesi

### 5. Faz: Dokümantasyon 📚
- [x] README.md oluşturma
- [x] PLANNING.md oluşturma
- [ ] CHANGELOG.md ekleme

---

## 📊 Veri Yapısı

### Excel Sütunları
| Sütun | Açıklama |
|-------|----------|
| Ders Adı | Dersin ismi |
| Kredi | Dersin saat/ağırlık değeri |
| Yazılı1 | 1. Yazılı sınav notu |
| Yazılı2 | 2. Yazılı sınav notu |
| Dersiç.Et1 | 1. Ders içi etkinlik notu |
| Dersiç.Et2 | 2. Ders içi etkinlik notu |
| Dersiç.Et3 | 3. Ders içi etkinlik notu |

### Örnek Veri
```javascript
const ogrenciler = [
  { ders: "Matematik", kredi: 5, notlar: [27] },
  { ders: "Türkçe", kredi: 6, notlar: [64] },
  { ders: "Yabancı Dil", kredi: 3, notlar: [88.5] }
];
```

---

## 🎨 Tasarım Kararları

### Renk Paleti
- **Primary:** #3498db (Mavi)
- **Success:** #27ae60 (Yeşil - Takdir)
- **Warning:** #f39c12 (Turuncu - Teşekkür)
- **Danger:** #e74c3c (Kırmızı - Belge yok)

### Tipografi
- Font: system-ui, sans-serif
- Başlık: Bold, 24px
- Normal metin: Regular, 16px

---

## 🔧 Teknik Gereksinimler

- Modern web tarayıcısı (Chrome, Firefox, Edge)
- SheetJS kütüphanesi (Excel okuma için)
- İnternet bağlantısı (CDN için)

---

## 📅 Tarih

Oluşturulma: 12 Ocak 2026
Son Güncelleme: 12 Ocak 2026
