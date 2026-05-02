# Lie & Truth Detector (Prank Edition)

Lie & Truth Detector adalah aplikasi web interaktif yang dirancang dengan estetika modern untuk mendeteksi "kebohongan" atau "kebenaran". Namun, aplikasi ini sebenarnya adalah alat **prank** yang sudah diprogram untuk selalu memberikan hasil tertentu.

## ✨ Fitur Utama

- **Premium UI Design**: Menggunakan desain *glassmorphism*, gradien warna yang harmonis, dan tipografi modern (Outfit) untuk memberikan kesan aplikasi profesional/militer.
- **Dynamic Gauge**: Jarum indikator yang bergerak secara dinamis dengan efek *jitter* saat menganalisis untuk mensimulasikan proses deteksi AI asli.
- **Scanning Effect**: Efek garis pemindaian (scanning line) yang muncul di atas UI saat proses analisis berlangsung.
- **Rigged Logic**: Secara default, jarum akan selalu bergerak ke arah **"Lie"** (Kebohongan) untuk mengerjai target Anda.
- **Customizable Results**: Teks hasil akhir yang muncul di popup dapat diubah dengan sangat mudah.

## 🛠️ Cara Kerja

1. **Input**: Pengguna mengeklik tombol "Check Reality".
2. **Analysis Simulation**: Sistem akan melakukan simulasi analisis selama 2 detik dengan animasi jarum bergetar dan garis pemindai.
3. **The Reveal**: Jarum akan berhenti di zona merah (**Lie**).
4. **Final Verdict**: Setelah 3 detik jarum berada di posisi "Lie", sebuah popup besar akan muncul menampilkan teks "vonis" yang sudah Anda tentukan.

## ⚙️ Cara Kustomisasi Teks

Anda dapat mengubah teks yang muncul pada popup agar sesuai dengan target prank Anda.

1. Buka file `detector.html`.
2. Cari baris kode berikut (sekitar baris 309):
   ```html
   <h2 id="popupText">ASLINYA EMANG SUKA PEGANG PEGANG IQBAL</h2>
   ```
3. Ganti teks di dalam tag `<h2>` dengan kalimat yang Anda inginkan.
4. Simpan file dan refresh browser.

## 🚀 Teknologi

- **HTML5**: Struktur semantik.
- **CSS3**: Animasi kompleks, *glassmorphism*, dan desain responsif.
- **JavaScript**: Logika animasi dan kontrol alur aplikasi.

---
*Dibuat untuk tujuan hiburan dan bercanda saja.*
