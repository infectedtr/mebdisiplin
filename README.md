# 🎓 MEB Öğrenci Disiplin Kurulu Asistanı (v1.1.1)

Milli Eğitim Bakanlığı Ortaöğretim Kurumları Yönetmeliği Ödül ve Disiplin Hükümlerine **%100 uyumlu**, okul idarecileri ve disiplin kurulu başkanları için geliştirilmiş akıllı masaüstü otomasyonu ve evrak yönetim asistanı.

---

## 🌟 Öne Çıkan Özellikler

### 📄 1. Eksiksiz Evrak ve Tutanak Üretimi
* **Tek Tıkla Resmi Evraklar:** Olay bildirim formu, savunma istem yazısı, veli bilgilendirme tebligatı, disiplin kurulu karar tutanağı ve karar tebliğ belgeleri otomatik hazırlanır.
* **Akıllı Karar Matrisi:** Öğrencinin geçmiş cezaları, hafifletici sebepler ve eylem türü değerlendirilerek yönetmeliğe uygun ceza teklifleri ve puan hesaplamaları dinamik yapılır.
* **Yüksek Çözünürlüklü PDF:** Tüm resmi yazılar MEB şablonlarına uygun antetli, tarih ve sayılı formatta PDF olarak dışa aktarılır ve yazdırılır.

### 📊 2. e-Okul Entegrasyonu & Hızlı Veri Aktarımı
* **Toplu Sınıf / Öğrenci Yükleme:** e-Okul'dan indirilen sınıf listesi Excel (`.XLS`, `.XLSX`) dosyaları saniyeler içinde içeri aktarılır.
* **Öğrenci Ceza ve Puan Takibi:** Öğrencilerin ceza puanları (100 üzerinden düşüm) ve disiplin geçmişi anlık takip edilir.

### 🌐 3. MEB / Fatih Ağı Kesintisiz Lisanslama (Cloudflare Worker Proxy)
* **Engelsiz Okul Ağı Erişimi:** Okullardaki MEB/Fatih internet filtrelerine takılmayan güvenli proxy altyapısı sayesinde kesintisiz lisans doğrulaması ve canlı sürüm kontrolü.
* **Hibrit Çalışma:** Çevrimdışı (offline) lisans anahtarı ve donanım kilitleme (HWID) desteği ile internetsiz ortamlarda da tam kapasite çalışır.

### 🖥️ 4. Modern Masaüstü Deneyimi
* **Şık ve Ergonomik Arayüz:** Modern koyu/açık tema desteği, akıcı mikro animasyonlar ve sezgisel kullanıcı deneyimi.
* **Tamamen Bağımsız Kurulum:** Ekstra kurulum veya veritabanı ayarı gerektirmeyen tek tık kurulum (.exe).

---

## 🚀 Sürüm 1.1.1 Yenilikleri (Changelog)

* 🌐  MEB okul internet hatlarında kesintisiz bağlantı sağlayan optimize edilmiş ters vekil sunucu (reverse proxy) mimarisine geçildi.
* 🛡️ **Web ve Sistem Güvenliği İyileştirmesi:** Harici navigasyon izolasyonu ve gelişmiş güvenlik politikaları (`webSecurity`) devreye alındı.
* ⚡ **PDF Çıktı Kararlılığı:** Karar tutanağı ve savunma formlarının PDF yazdırma motorundaki biçimlendirmeler optimize edildi.
* 📦 **Kurulum Paketi Güncellemesi:** Bağımsız NSIS Windows kurulum paketi en son motor bileşenleriyle güncellendi.

---

## 📥 Kurulum ve Başlatma

1. **[Releases](https://github.com/infectedtr/mebdisiplin/releases/latest)** sayfasından **`MEB_Ogrenci_Disiplin_Asistani_Setup_1.1.1.exe`** dosyasını indirin.
2. İndirilen kurulum dosyasını çalıştırıp kurulum adımlarını tamamlayın.
3. Masaüstündeki **"MEB Öğrenci Disiplin Programı"** kısayoluna tıklayarak uygulamayı başlatın.

---

## 💻 Sistem Gereksinimleri

* **İşletim Sistemi:** Windows 10 / Windows 11 (64-bit)
* **Bellek (RAM):** Minimum 2 GB (4 GB önerilir)
* **Disk Alanı:** ~300 MB boş alan
* **Gereksinimler:** İnternet bağlantısı (ilk aktivasyon ve güncelleme kontrolleri için; sonrasında çevrimdışı çalışabilir)

---

## 📞 Destek ve İletişim

* **Geliştirici:** Antigravity / MEB Yazılım Çözümleri
* **E-Posta:** `mebaiprogram@gmail.com`
* **Sorun Bildirimi:** [GitHub Issues](https://github.com/infectedtr/mebdisiplin/issues)
