<div align="center">

  <h1>📅 Web Tasarım ve Kodlama • Ders & Sınav Takvimi</h1>

  <p>
    <strong>2. Sınıf Güz Dönemi için hazırlanmış modern, mobil uyumlu ve Dark / Light tema destekli haftalık ders programı ve sınav takvimi web uygulaması.</strong>
  </p>

  <p>
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
    <img src="https://img.shields.io/badge/Responsive-Mobile--Friendly-10b981?style=for-the-badge" alt="Mobile Friendly" />
    <img src="https://img.shields.io/badge/Theme-Dark%20%2F%20Light-6366f1?style=for-the-badge" alt="Dark / Light Theme" />
  </p>

  <p>
    <a href="#-özellikler">Özellikler</a> •
    <a href="#-ders-programı-özeti">Ders Programı</a> •
    <a href="#-sayfalar">Sayfalar</a> •
    <a href="#-kurulum-ve-kullanım">Kurulum</a> •
    <a href="#-teknolojiler">Teknolojiler</a> •
    <a href="#-geliştirici">Geliştirici</a>
  </p>

</div>

---

## ✨ Özellikler

- 🌓 **Dinamik Dark / Light Mod:**
  - Tek tıkla açık ve koyu tema arasında geçiş.
  - Seçilen tema `localStorage` üzerinde saklanır; sayfa yenilendiğinde ve sayfalar arasında gezinildiğinde kaybolmaz.
  - Sistem renk tercihini (`prefers-color-scheme`) otomatik algılar ve yükleme esnasında ekran titremesini (FOUC) önler.

- 📱 **%100 Mobil Uyumlu ve Duyarlı (Responsive):**
  - Masaüstünde 5 sütunlu geniş ders ızgarası.
  - Tablet ve mobil ekranlarda dikey akıcı kart görünümü, büyük dokunma hedefleri ve optimize edilmiş yazı boyutları.

- 📍 **Akıllı "Bugün" Rozeti:**
  - Tarayıcının geçerli gününü JavaScript ile dinamik olarak tespit eder ve ilgili gün sütununu otomatik olarak vurgular.

- 🎨 **Modern ve Zengin Arayüz:**
  - *Plus Jakarta Sans* Google Font tipografisi.
  - Her ders için ayırt edici renk vurguları (accent border, duration badges).
  - Yumuşak geçiş efektleri (smooth transitions), mikro-etkileşimler ve kart hover animasyonları.

- ⚡ **Sıfır Bağımlılık (Pure Vanilla):**
  - Harici hiçbir kütüphane veya framework gerektirmez. Saf HTML5, CSS3 ve Vanilla JavaScript ile ultra hafif ve anında yüklenir.

---

## 📚 Haftalık Ders Programı Özeti (2. Sınıf)

| Gün | Saat Aralığı | Ders Adı | Öğretim Elemanı | Derslik | Saat |
| :--- | :--- | :--- | :--- | :--- | :---: |
| **Pazartesi** | — | ☕ *Ders Bulunmamaktadır (Serbest Gün)* | — | — | — |
| **Salı** | 13:30 - 16:05 | **Kullanıcı Deneyimi Tasarımı** | S. KORKMAZ | BİL. LAB. 114 | 3 |
| **Çarşamba** | 09:00 - 12:30 | **Web Tabanlı Kodlama** | S. KORKMAZ | BİL. LAB. 114 | 4 |
| **Çarşamba** | 13:30 - 17:00 | **İçerik Yönetimi** | T. DURAK | BİL. LAB. 114 | 4 |
| **Perşembe** | 13:30 - 16:05 | **İnternet Programcılığı** | G. E. KAHYA | BİL. LAB. 111 | 3 |
| **Cuma** | 09:00 - 12:30 | **Dijital Girişimcilik** | T. DURAK | BİL. LAB. 111 | 4 |
| **Cuma** | 14:25 - 17:00 | **Yapay Zeka Etiği** | G. E. KAHYA | BİL. LAB. 111 | 3 |

---

## 🗂 Proje Mimarisi ve Sayfalar

```text
Ders-Program--main/
├── index.html        # 2. Sınıf Haftalık Ders Programı (Ana Sayfa)
├── index2.html       # 2. Sınıf Vize Sınav Takvimi (Doldurulabilir Şablon)
└── README.md         # Proje Dokümantasyonu
```

### 1. `index.html` — Haftalık Ders Programı
- Haftalık gün sütunları, ders başlangıç/bitiş saatleri, derslikler (Laboratuvar 114 ve 111) ve hoca bilgileri.
- Pazartesi gününe özel şık serbest gün kartı.
- Güncel günü parıldatan "Bugün" etiketi.

### 2. `index2.html` — Vize Sınav Takvimi
- 2. sınıfın 6 dersine özel hazırlanmış sınav kartı şablonları.
- Tarih, saat, gözetmen ve sınav salonu bilgileri takvim açıklandığında kolayca doldurulacak formatta hazır bekletilir.
- `index.html` ile ortak tasarım sistemi ve tema senkronizasyonu.

---

## 🚀 Kurulum ve Çalıştırma

Projeyi bilgisayarınızda çalıştırmak için herhangi bir paket yöneticisi (`npm`, `yarn` vb.) kurmanıza gerek yoktur:

1. **Depoyu Klonlayın:**
   ```bash
   git clone https://github.com/kullaniciadi/Ders-Program-.git
   cd Ders-Program-
   ```

2. **Çalıştırın:**
   - `index.html` dosyasına çift tıklayarak doğrudan herhangi bir tarayıcıda açabilirsiniz.
   - Veya yerel bir HTTP sunucusu ile çalıştırmak isterseniz:
     ```bash
     # Python ile (3.x):
     python -m http.server 3000
     ```
     Tarayıcınızdan `http://localhost:3000` adresine gidin.
   - VS Code kullanıyorsanız **Live Server** eklentisiyle tek tıkla açabilirsiniz.

---

## 🛠 Kullanılan Teknolojiler

- **HTML5:** Anlamsal etiketleme (`header`, `main`, `section`, `article`, `nav`, `footer`).
- **CSS3:** 
  - CSS Custom Properties (CSS Değişkenleri ile Light & Dark Token Mimarisi).
  - CSS Grid & Flexbox esnek yerleşimleri.
  - Glassmorphic & Modern Neumorphic kart tasarımı.
- **Vanilla JavaScript:** 
  - Dinamik tema yönetimi ve `localStorage` entegrasyonu.
  - Gün tespiti (`new Date().getDay()`).
- **Google Fonts:** [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans)

---

## 👨‍💻 Geliştirici

Bu proje **Arda Utancak** tarafından tasarlanmış ve geliştirilmiştir.

<div align="center">
  <sub>Made with ❤️ by <strong>Arda Utancak</strong></sub>
</div>