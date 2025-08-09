# 🎯 Yüz Tespiti Projesi

[![Python](https://img.shields.io/badge/Python-3.8+-mavi.svg)](https://www.python.org/downloads/)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.8+-yeşil.svg)](https://opencv.org/)
[![Lisans](https://img.shields.io/badge/Lisans-MIT-sarı.svg)](https://opensource.org/licenses/MIT)

> OpenCV ve Python kullanarak gerçek zamanlı yüz tespiti uygulaması. Haar Cascade algoritması ile webcam'den canlı video akışında yüz tespiti yapar.

## ✨ Özellikler

- 🔍 **Gerçek zamanlı yüz tespiti**
- 📹 **Canlı webcam akışı**
- 🎯 **Yüksek doğruluk**
- 🚀 **Kolay kullanım**
- 💻 **Platform bağımsız**

## 🛠️ Kullanılan Teknolojiler

- **Python 3.x**
- **OpenCV (cv2)**
- **Haar Cascade Classifier**

## 📋 Gereksinimler

- Python 3.8 veya üzeri
- OpenCV kütüphanesi
- Web kamerası
- Windows/Linux/macOS

## 🚀 Kurulum

### 1. Repository'yi klonlayın
```bash
git clone https://github.com/Semihkulekcioglu/face-detection-project.git
cd face-detection-project
```

### 2. Bağımlılıkları yükleyin
```bash
pip install -r requirements.txt
```

### 3. Uygulamayı çalıştırın
```bash
python face_detectiob.py
```

## 🎮 Kullanım

1. **Uygulamayı başlatın**
2. **Webcam açılacak**
3. **Yüzler tespit edilecek**
4. **Mavi dikdörtgenler** tespit edilen yüzleri işaretleyecek
5. **Çıkmak için 'q' tuşuna basın**

## 📁 Proje Yapısı

```
face-detection-project/
├── face_detectiob.py      # Ana uygulama
├── requirements.txt       # Python bağımlılıkları
├── README.md             # İngilizce proje dokümantasyonu
├── README_TR.md          # Türkçe proje dokümantasyonu
├── LICENSE               # Lisans dosyası
├── .gitignore           # Git ignore kuralları
├── screenshots/         # Ekran görüntüleri
├── video1.mp4           # Test videosu 1
├── video2.mp4           # Test videosu 2
└── video3.mp4           # Test videosu 3
```

## 🔧 Nasıl Çalışır

1. **Video Yakalama**: Webcam'den video akışı alınır
2. **Frame İşleme**: Her frame gri tonlamaya çevrilir
3. **Yüz Tespiti**: Haar Cascade algoritması ile yüzler tespit edilir
4. **Görselleştirme**: Tespit edilen yüzler mavi dikdörtgen ile işaretlenir
5. **Görüntüleme**: İşlenmiş frame ekranda gösterilir

## 🎯 Ana Özellikler

- **Gerçek zamanlı işleme**
- **Çoklu yüz tespiti**
- **Yüksek performans**
- **Kullanıcı dostu arayüz**

## 📸 Ekran Görüntüleri

![Uygulama Ekran Görüntüsü](screenshots/app_screenshot.png)

*Yüz tespiti uygulamasının çalışır haldeki ekran görüntüsü*

## 🤝 Katkıda Bulunma

Katkılarınızı bekliyoruz! Lütfen Pull Request göndermekten çekinmeyin.

## 📄 Lisans

Bu proje MIT Lisansı altında lisanslanmıştır - detaylar için [LICENSE](LICENSE) dosyasına bakın.

## 👨‍💻 Yazar

**Muhammed Semih Külekçioğlu**

- GitHub: [@Semihkulekcioglu](https://github.com/Semihkulekcioglu)

## 🙏 Teşekkürler

- OpenCV ekibi mükemmel bilgisayarlı görü kütüphanesi için
- Haar Cascade algoritması geliştiricileri
- Harika araçlar ve kütüphaneler için Python topluluğu

---

<img width="416" height="416" alt="result" src="https://github.com/user-attachments/assets/07497c90-fe08-4ed1-8410-866fbfc64f1b" />

⭐ **Bu projeyi faydalı bulursanız, lütfen yıldız verin!**
