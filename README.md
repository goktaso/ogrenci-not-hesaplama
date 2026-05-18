# 📊 Öğrenci Not Hesaplama Uygulaması

Excel dosyasındaki sınav notlarına göre ağırlıklı not ortalaması hesaplar ve Teşekkür/Takdir durumunu belirler.

## 📁 Proje Yapısı

```
├── index.html          # Ana web uygulaması
├── README.md           # Bu dosya
└── PLANNING.md         # Geliştirme planı
```

## 🎯 Özellikler

- ✅ Excel dosyası yükleyerek notları otomatik okuma
- ✅ Ağırlıklı not ortalaması hesaplama
- ✅ Genel not ortalaması hesaplama
- ✅ Teşekkür/Takdir belgesi durumu belirleme
- ✅ Ders bazlı detaylı görüntüleme

## 📐 Not Hesaplama Formülü

### Ders İçi Ortalama Hesaplama
```
Ders İçi Ortalama = (Yazılı1 + Yazılı2 + Dersiç.Et1 + Dersiç.Et2 + Dersiç.Et3) / Ders Sayısı
```

### Ağırlıklı Ortalama Hesaplama
```
Ağırlıklı Toplam = Σ(Ders İçi Ortalama × Kredi)
Genel Ortalama = Ağırlıklı Toplam / Toplam Kredi
```

## 🏆 Teşekkür/Takdir Kriterleri

| Belge | Ortalama Aralığı |
|-------|------------------|
| Takdir Belgesi | ≥ 85.00 |
| Teşekkür Belgesi | 70.00 - 84.99 |
| Belge Yok | < 70.00 |

## 🚀 Kullanım

1. `index.html` dosyasını tarayıcıda açın
2. Excel dosyanızı yükleyin veya örnek verileri inceleyin
3. Sonuçları görüntüleyin

## 💡 Öğrenme Noktaları

Bu projede şunları öğreneceksiniz:
- HTML/CSS/JavaScript temelleri
- Excel dosya işleme (SheetJS kütüphanesi)
- Dokümantasyon oluşturma (Markdown)
- GitHub Markdown özellikleri

## 👤 Geliştirici

Arda'nın Not Hesaplama Sistemi
