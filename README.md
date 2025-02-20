# FTTx Calculator

Aplikasi kalkulator power budget untuk jaringan Fiber To The x (FTTx) yang membantu teknisi dan engineer dalam menghitung power budget pada instalasi jaringan fiber optik.

## 🌟 Fitur Utama

- **Perhitungan Power Budget**
  - Kalkulasi transmit power (dBm)
  - Perhitungan fiber loss (dB/km)
  - Estimasi jarak (km)
  - Hasil perhitungan yang akurat dan real-time

- **Antarmuka Modern**
  - Material Design 3 dengan tema dinamis
  - Navigasi gesture yang intuitif
  - Dark mode support
  - Layout responsif untuk berbagai ukuran layar

- **Fitur Tambahan**
  - Riwayat perhitungan
  - Opsi berbagi hasil perhitungan
  - Salin hasil ke clipboard
  - Panduan penggunaan terintegrasi

## 📱 Screenshot

![image](https://github.com/user-attachments/assets/2168b80e-20f5-456f-9ac4-558847de88d4)
![image](https://github.com/user-attachments/assets/d4a32243-b933-4887-a364-17d90b4d7f67)
![image](https://github.com/user-attachments/assets/35ee4e20-dfd8-4a89-9eea-2a16a3b6787b)
![image](https://github.com/user-attachments/assets/fe889a58-95b4-4d95-8da0-9fd18a200bfe)
![image](https://github.com/user-attachments/assets/d82600f8-bdd9-49c5-a504-820246fd3638)








## 🚀 Teknologi yang Digunakan

- Kotlin
- Android Jetpack Components
- Material Design 3
- ViewBinding
- AndroidX
- Coroutines

## 📋 Persyaratan Sistem

- Android 7.0 (API level 24) atau lebih tinggi
- Minimal RAM 2GB
- Ruang penyimpanan minimal 50MB

## 💻 Instalasi

1. Download APK dari [releases page](link_ke_releases)
2. Izinkan instalasi dari sumber tidak dikenal di pengaturan Android
3. Install aplikasi
4. Buka aplikasi dan mulai gunakan

Atau build dari source code:
```bash
git clone https://github.com/username/FTTxCalculator.git
cd FTTxCalculator
./gradlew assembleDebug
```

## 🔧 Penggunaan

1. Buka aplikasi FTTx Calculator
2. Masukkan nilai Transmit Power dalam dBm
3. Masukkan nilai Fiber Loss dalam dB/km
4. Masukkan jarak dalam kilometer
5. Tekan tombol "Calculate" untuk mendapatkan hasil
6. Gunakan tombol "Copy" atau "Share" untuk membagikan hasil

## 📖 Cara Kerja

Aplikasi menggunakan rumus dasar power budget untuk menghitung total loss:

```
Total Loss = (Fiber Loss × Distance) + Connector Loss + Splice Loss
```

Dimana:
- Fiber Loss: Loss per kilometer fiber optik (dB/km)
- Distance: Jarak total fiber optik (km)
- Connector Loss: Loss pada konektor (dB)
- Splice Loss: Loss pada sambungan (dB)

## 🤝 Kontribusi

Kontribusi selalu diterima! Berikut cara untuk berkontribusi:

1. Fork repositori
2. Buat branch fitur baru (`git checkout -b feature/AmazingFeature`)
3. Commit perubahan (`git commit -m 'Add some AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buka Pull Request

## 📄 Lisensi

Didistribusikan di bawah Lisensi MIT. Lihat `LICENSE` untuk informasi lebih lanjut.

## 📞 Kontak

[Syaiful Wachid] - [@social_media](link_social_media)

Project Link: [https://github.com/username/FTTxCalculator](https://github.com/username/FTTxCalculator)

## 🙏 Pengakuan

- [Material Design](https://m3.material.io/)
- [Android Jetpack](https://developer.android.com/jetpack)
- [Kotlin](https://kotlinlang.org/)

## 📝 Catatan Rilis

### Versi 1.0.0
- Rilis awal
- Fitur dasar kalkulator power budget
- Implementasi Material Design 3
- Gesture navigation
- Fitur copy dan share hasil
