# 📥 YouTube Downloader (Kivy)

🚀 **Türkçe ve İngilizce dil desteğine sahip basit bir YouTube video indirici**  
🎨 Python ve [Kivy](https://kivy.org/) ile geliştirilmiştir. Android ve bilgisayarlarda çalışır.

A simple **YouTube video downloader with Turkish 🇹🇷 and English 🇬🇧 language support**, built using Python and [Kivy](https://kivy.org/). Works on Android and desktop platforms.

---

## ✨ Özellikler / Features

✅ Türkçe 🇹🇷 ve İngilizce 🇬🇧 dil desteği  
✅ YouTube videolarını en iyi kalitede indirir  
✅ Videoları **Download** klasörüne kaydeder  
✅ Modern ve basit arayüz  
✅ Android (Pydroid 3) ve PC (Windows/Linux) uyumlu  

---

## 📦 Kullanılan Kütüphaneler / Used Libraries

| Kütüphane          | Açıklama (Türkçe)                                                                                  | Description (English)                                                                                 |
|---------------------|-----------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|
| **Kivy**           | Uygulamanın arayüzünü (butonlar, yazı kutuları, ekranlar) oluşturur.                                | Creates the app’s user interface (buttons, text fields, screens).                                     |
| **pytube**         | YouTube videolarını indirir.                                                                        | Downloads YouTube videos.                                                                             |
| **yt-dlp** (opsiyonel) | Daha gelişmiş bir YouTube indirici alternatifi.                                                   | An advanced alternative YouTube downloader.                                                           |
| **threading**      | İndirme işlemini arka planda çalıştırır, uygulamanın donmasını önler.                               | Runs the download process in the background to keep the app responsive.                               |
| **android**        | Android cihazlarda dosya indirmek için gerekli izinleri yönetir.                                   | Manages storage permissions for downloading files on Android devices.                                 |
| **requests**       | YouTube’dan video bilgilerini almak için internet üzerinden veri iletişimi sağlar (pytube bağımlılığı).| Sends and receives data from YouTube (used by pytube).                                                |

---

## 📥 Kurulum / Installation

### 🖥️ Bilgisayar / On Desktop

1️⃣ Bu repoyu klonlayın / Clone this repo:
```bash
git clone https://github.com/kullaniciadi/repo-adi.git
cd repo-adi
