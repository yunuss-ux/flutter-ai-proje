# 📱 Flutter AI Entegrasyon Projesi: Akıllı Mobil Asistan

![Flutter](https://img.shields.io/badge/Flutter-3.x-blue?style=flat&logo=flutter)
![Dart](https://img.shields.io/badge/Dart-3.x-blue?style=flat&logo=dart)
![AI](https://img.shields.io/badge/AI-Gemini%20API%20%2F%20TFLite-orange)

## 📖 Proje Hakkında
**Ders:** Mobil Uygulamalar
**Konu:** Flutter ve Cihaz İçi (On-Device) / Cloud Makine Öğrenmesi

Bu proje, Flutter kullanılarak geliştirilmiş, yapay zeka destekli bir mobil uygulamadır. Projenin temel amacı, **[BURAYA PROJENİN AMACINI YAZ: Örn. Google Gemini API kullanarak metin üretme]** yeteneklerini mobil platforma entegre etmektir.

### 🔍 1. Araştırma ve Konu Derinliği
Bu projede teknoloji olarak **[KULLANDIĞIN TEKNOLOJİYİ YAZ: Örn. Google Gemini API / TensorFlow Lite]** tercih edilmiştir.

* **Teorik Altyapı:** Seçilen yapay zeka modeli, mobil cihazlarda [Örn: doğal dil işleme / görüntü işleme] yeteneği kazandırmak için kullanılmıştır. Sadece yüzeysel bir API çağrısı değil, verinin işlenmesi ve kullanıcıya sunulması süreçleri optimize edilmiştir.
* **Neden Bu Teknoloji?:** [Örn: Gemini API'nin geniş dil desteği ve hızlı yanıt süresi nedeniyle tercih edilmiştir.]

---

### ⚙️ 2. Teknik Uygulama ve Fonksiyonellik
Uygulama temel olarak şu yeteneklere sahiptir ve hatasız çalışmaktadır:

* ✅ **AI Entegrasyonu:** [Örn: Kullanıcıdan alınan metni analiz eder ve akıllı yanıtlar üretir.]
* ✅ **Kamera/Galeri Erişimi:** (Eğer kullandıysan) Cihaz donanımları ile tam uyumlu çalışır.
* ✅ **Hata Yönetimi:** İnternet kopması veya API hataları kullanıcıya uygun mesajlarla bildirilir.

---

### 🏗️ 3. Kod Kalitesi ve Mimari
Proje geliştirilirken **"Clean Code"** prensiplerine sadık kalınmış ve kodun okunabilirliği ön planda tutulmuştur.

* **Mimari:** Projede **[Örn: MVVM veya Clean Architecture]** yapısı kullanılmıştır. İş mantığı (Business Logic) ve Arayüz (UI) birbirinden ayrılmıştır.
* **Dosya Yapısı:**
    * `lib/services`: API servis istekleri burada yönetilir.
    * `lib/screens`: Kullanıcı arayüzleri buradadır.
    * `lib/models`: Veri modelleri (JSON parsing işlemleri) buradadır.

---

### 🎨 4. UI/UX Tasarımı ve Kullanılabilirlik
Arayüz estetik, tutarlı ve kullanıcı dostu olacak şekilde tasarlanmıştır.

* **Responsive Tasarım:** Uygulama farklı ekran boyutlarına uyum sağlar.
* **Kullanıcı Deneyimi:** İşlemler sırasında kullanıcıya yükleniyor (loading) simgeleri gösterilerek akıcılık sağlanır.

*(Buraya GitHub'a yüklediğin ekran görüntülerinin linkini koyabilirsin, yoksa bu parantezi sil)*
`![Ekran Görüntüsü](screenshots/ornek.png)`

---

### 🚀 5. Kurulum ve Dokümantasyon

Projeyi yerel ortamınızda çalıştırmak için:

1.  Projeyi klonlayın.
2.  Paketleri yükleyin: `flutter pub get`
3.  Uygulamayı başlatın: `flutter run`

*(Not: API Anahtarı gerekiyorsa `lib/constants.dart` içerisine kendi anahtarınızı giriniz.)*
