# 📱 Flutter AI Entegrasyon Projesi: Akıllı Asistan

![Flutter](https://img.shields.io/badge/Flutter-3.x-blue?style=flat&logo=flutter)
![Dart](https://img.shields.io/badge/Dart-3.x-blue?style=flat&logo=dart)
![AI](https://img.shields.io/badge/AI-Gemini%20API-orange)

## 📖 Proje Hakkında
**Ders:** Mobil Uygulamalar
**Konu:** Flutter ve Cihaz İçi (On-Device) / Cloud Makine Öğrenmesi

Bu proje, Flutter kullanılarak geliştirilmiş, yapay zeka destekli bir mobil uygulamadır. Projenin temel amacı, **Google Gemini API kullanarak metin üretme ve AI Chatbot** yeteneklerini mobil platforma entegre etmektir.

### 🔍 1. Araştırma ve Konu Derinliği
Bu projede teknoloji olarak **Google Gemini API** tercih edilmiştir.

* **Teorik Altyapı:** Seçilen yapay zeka modeli, mobil cihazlarda **doğal dil işleme (NLP)** yeteneği kazandırmak için kullanılmıştır. Sadece yüzeysel bir API çağrısı değil, verinin işlenmesi ve kullanıcıya sunulması süreçleri optimize edilmiştir.
* **Neden Bu Teknoloji?:** Gemini API'nin geniş dil desteği, yüksek doğruluk oranı ve hızlı yanıt süresi nedeniyle tercih edilmiştir.

---

### ⚙️ 2. Teknik Uygulama ve Fonksiyonellik
Uygulama temel olarak şu yeteneklere sahiptir ve hatasız çalışmaktadır:

* ✅ **AI Entegrasyonu:** Kullanıcıdan alınan metni analiz eder ve akıllı yanıtlar üretir.
* ✅ **Hata Yönetimi:** İnternet kopması veya API hataları kullanıcıya uygun mesajlarla bildirilir.
* ✅ **State Management:** Anlık durum değişimleri (Yükleniyor, Mesaj Geldi vb.) arayüze anında yansıtılır.

---

### 🏗️ 3. Kod Kalitesi ve Mimari
Proje geliştirilirken **"Clean Code"** prensiplerine sadık kalınmış ve kodun okunabilirliği ön planda tutulmuştur.

* **Mimari:** Projede **MVVM (Model-View-ViewModel)** prensiplerinden esinlenilmiştir. İş mantığı (Business Logic) ve Arayüz (UI) birbirinden ayrılmıştır.
* **Dosya Yapısı:**
    * `lib/services`: API servis istekleri ve veri alışverişi.
    * `lib/screens`: Kullanıcı arayüzleri ve widget'lar.
    * `lib/models`: Veri modelleri.

---

### 🎨 4. UI/UX Tasarımı ve Kullanılabilirlik
Arayüz estetik, tutarlı ve kullanıcı dostu olacak şekilde tasarlanmıştır.

* **Responsive Tasarım:** Uygulama farklı ekran boyutlarına uyum sağlar.
* **Kullanıcı Deneyimi:** Mesajlaşma sırasında kullanıcıya yükleniyor (loading) simgeleri gösterilerek akıcılık sağlanır.

---

### 🚀 5. Kurulum ve Dokümantasyon

Projeyi yerel ortamınızda çalıştırmak için:

1.  Projeyi klonlayın.
2.  Paketleri yükleyin: `flutter pub get`
3.  Uygulamayı başlatın: `flutter run`

*(Not: API Anahtarı güvenlik gereği kod içerisine doğrudan eklenmemiştir, test için kendi API anahtarınızı tanımlamanız gerekebilir.)*
