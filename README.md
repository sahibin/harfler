# 🎯 Sözlük Sırası Quiz - GitHub Pages Kurulum

## 📱 Uygulama Hakkında
İlkokul 3. sınıf seviyesinde Türkçe kelimeler için alfabetik sıralama quiz uygulaması.

### ✨ Özellikler:
- **2 farklı quiz modu**: Farklı harfler ve Aynı harf modları
- **100+ soru** her modda
- **Otomatik ilerlemе** (2 saniye sonra)
- **iPhone Safari uyumlu** tasarım
- **Kompakt ve modern** arayüz

## 🚀 GitHub Pages'da Yayınlama

### 1. Repository Oluşturma
```bash
# GitHub'da yeni repository oluşturun
# Repository adı: sozluk-quiz-app (veya istediğiniz isim)
```

### 2. Dosyaları Yükleme
```bash
# Bu klasördeki tüm dosyaları repository'nize yükleyin
git init
git add .
git commit -m "İlk commit: Sözlük quiz uygulaması"
git branch -M main
git remote add origin https://github.com/USERNAME/REPO-NAME.git
git push -u origin main
```

### 3. GitHub Pages Ayarları
1. Repository'nize gidin
2. **Settings** sekmesine tıklayın
3. Sol menüden **Pages** seçin
4. **Source** olarak **Deploy from a branch** seçin
5. **Branch** olarak **main** ve **/ (root)** seçin
6. **Save** butonuna tıklayın

### 4. Erişim
Birkaç dakika sonra uygulamanız şu adreste yayında olacak:
```
https://USERNAME.github.io/REPO-NAME/
```

## 📁 Dosya Yapısı
```
build/ (Bu klasör)
├── index.html           # Ana HTML dosyası
├── static/
│   ├── css/
│   │   └── main.f6ddf303.css
│   └── js/
│       └── main.6435c25d.js
├── asset-manifest.json
└── README.md
```

## 🔧 Özelleştirme İpuçları

### Başlık Değiştirme
`index.html` dosyasında `<title>` tagını düzenleyin.

### Renk Teması
CSS dosyasında renk değişkenlerini düzenleyerek farklı tema oluşturabilirsiniz.

### Kelime Ekleme
Kaynak koddan yeniden build almanız gerekir.

## 📱 Kullanım
1. **Farklı Harfler**: araba, çanta, elma → hangisi önce?
2. **Aynı Harf**: kadın, karanfil, katı → hangisi önce?

## 🎮 Oyun Kuralları
- 3 kelime görüntülenir
- Alfabetik sırada ilk gelen kelimeyi seçin
- Doğru cevaptan sonra 2 saniye bekleyip otomatik geçiş
- Yanlış cevaplarda doğru cevap gösterilir
- Puanınız sürekli takip edilir

---

**Geliştirici**: Emergent AI ile oluşturulmuştur  
**Lisans**: Eğitim amaçlı kullanım için ücretsiz  
**Versiyon**: 1.0.0