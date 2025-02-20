# FTTx Calculator

Aplikasi komprehensif untuk perhitungan, perencanaan, dan implementasi jaringan Fiber To The x (FTTx). Dirancang khusus untuk teknisi, engineer, dan profesional telekomunikasi dalam mengelola instalasi jaringan fiber optik.

![image](https://github.com/user-attachments/assets/d4a32243-b933-4887-a364-17d90b4d7f67)

## 📊 Fitur Utama

### 1. Dashboard (Main Activity)
Halaman utama dengan akses cepat ke semua fitur kalkulator dan tools.

**Komponen Dashboard:**
- Quick Access Cards
  - Power Budget Calculator
  - Loss Budget Calculator
  - Splice Loss Estimator
  - Fiber Color Guide
  
**Fitur Dashboard:**
- Recent Calculations
  - Riwayat 5 perhitungan terakhir
  - Quick preview hasil
  - One-tap untuk membuka detail

- Quick Tools
  - Unit Converter (dB ⟷ dBm)
  - Power Meter Simulator
  - Quick Loss Calculator
  - Distance Estimator

- Project Management
  - Create New Project
  - Open Recent Project
  - Project Templates
  - Import/Export Data

- Shortcuts & Favorites
  - Customizable quick actions
  - Frequently used calculations
  - Saved presets
  - Bookmarked results

**Fitur Navigasi:**
- Bottom Navigation Bar
  - Home
  - Calculators
  - Tools
  - Settings

- Side Navigation Drawer
  - User Profile
  - Project Management
  - Tools & Calculators
  - Settings & Preferences
  - Help & Documentation

**Personalisasi:**
- Customizable Dashboard Layout
- Dark/Light Mode Toggle
- Favorite Tools Pinning
- Widget Arrangement

### 2. Power Budget Calculator
Menghitung power budget end-to-end pada jaringan fiber optik.

**Komponen Perhitungan:**
- Transmit Power (dBm)
- Receiver Sensitivity (dBm)
- Fiber Loss (dB/km)
- Total Jarak (km)
- Jumlah Splice
- Jumlah Connector
- Safety Margin

**Rumus:**
```
Total Loss = (α × L) + (Nc × Lc) + (Ns × Ls) + SM

Dimana:
α  = Fiber Loss (dB/km)
L  = Panjang Fiber (km)
Nc = Jumlah Connector
Lc = Loss per Connector (dB)
Ns = Jumlah Splice
Ls = Loss per Splice (dB)
SM = Safety Margin (dB)

Power Margin = Tx Power - Rx Sensitivity - Total Loss
```
## 📱 Screenshot

![image](https://github.com/user-attachments/assets/2168b80e-20f5-456f-9ac4-558847de88d4)

### 3. Loss Budget Calculator
Kalkulasi detail untuk setiap komponen loss dalam jaringan.

![image](https://github.com/user-attachments/assets/d82600f8-bdd9-49c5-a504-820246fd3638)

**Fitur Perhitungan:**
- Insertion Loss
- Return Loss
- Bending Loss
- Temperature-Dependent Loss
- Splice Loss
- Connector Loss

**Formula Detail:**
```
Total Insertion Loss = Fiber Loss + Splice Loss + Connector Loss + Bending Loss

Return Loss = -10 log₁₀(Reflected Power/Input Power)

Temperature Loss = α × L × ΔT
Dimana ΔT = Perubahan temperatur dalam °C
```

### 4. Splice Loss Estimator
Estimasi dan analisis loss pada titik splice fiber optik.

**Metode Estimasi:**
- Core Misalignment Loss
- Angular Misalignment Loss
- End Separation Loss

**Rumus Perhitungan:**
```
Core Offset Loss = -10 log₁₀[1-(d/w)²]
Dimana:
d = offset distance
w = mode field diameter

Angular Loss = -10 log₁₀[cos(θ)]
Dimana θ = sudut misalignment

End Separation Loss = -10 log₁₀[1/(1+(z/w)²)]
Dimana z = jarak gap
```

### 5. Fiber Color Guide 🎨
Panduan lengkap kode warna fiber optik standar industri.

![image](https://github.com/user-attachments/assets/fe889a58-95b4-4d95-8da0-9fd18a200bfe)
![image](https://github.com/user-attachments/assets/35ee4e20-dfd8-4a89-9eea-2a16a3b6787b)

**Fitur:**
- Kode Warna TIA-598
- Kode Warna IEC 60304
- Identifikasi Tube dan Buffer
- Panduan Visual Interaktif

### 6. OTDR Event Analysis (Coming Soon) 🔜
Analisis trace OTDR dan interpretasi event.

**Fitur Mendatang:**
- Interpretasi Trace
- Event Classification
- Loss Measurement
- Distance Calculation
- Reflectance Analysis

### 7. Bandwidth Calculator (Coming Soon) 🔜
Perhitungan bandwidth dan kapasitas jaringan.

**Akan Mencakup:**
- Modal Bandwidth
- Chromatic Dispersion
- Polarization Mode Dispersion
- Channel Capacity
- Bit Error Rate Estimation

### 8. Network Design Assistant (Coming Soon) 🔜
Asisten perancangan jaringan FTTx.

**Fitur Direncanakan:**
- Topology Optimization
- Equipment Placement
- Coverage Planning
- Cost Estimation
- Material Requirements

## 🎯 Keunggulan Aplikasi

### Antarmuka Modern
- Material Design 3 dengan Dynamic Color
- Gesture Navigation yang Intuitif
- Dark/Light Mode Support
- Responsive Layout

### Fitur Teknis
- Perhitungan Real-time
- Validasi Input Otomatis
- Riwayat Perhitungan
- Export Data (PDF/CSV)
- Backup & Restore

### Keamanan & Privasi
- Offline Operation
- No Data Collection
- Local Storage Only
- Regular Updates

## 🔧 Spesifikasi Teknis

### Teknologi
- Kotlin 1.9.x
- Android SDK 34
- Material Design 3
- AndroidX Components
- ViewBinding
- Coroutines
- Room Database
- DataStore Preferences

### Arsitektur
- MVVM Pattern
- Clean Architecture
- Repository Pattern
- Dependency Injection
- Unit Testing

## 📱 Persyaratan Sistem

- Android 7.0 (API 24) atau lebih tinggi
- RAM 2GB minimum
- Storage 50MB minimum
- Processor 1.4 GHz minimum

## 💻 Instalasi & Penggunaan

### Instalasi
1. Download APK dari [releases page](link_ke_releases)
2. Izinkan instalasi dari sumber tidak dikenal
3. Install aplikasi
4. Buka dan mulai penggunaan

### Build dari Source
```bash
git clone https://github.com/username/FTTxCalculator.git
cd FTTxCalculator
./gradlew assembleDebug
```

## 🤝 Kontribusi

Kami menerima kontribusi dalam bentuk:
- Bug Reports
- Feature Requests
- Code Contributions
- Documentation
- Translations

### Panduan Kontribusi
1. Fork repositori
2. Buat branch fitur (`git checkout -b feature/AmazingFeature`)
3. Commit perubahan (`git commit -m 'Add AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buat Pull Request

## 📄 Lisensi

Didistribusikan di bawah Lisensi MIT. Lihat `LICENSE` untuk informasi lebih lanjut.

## 👥 Tim Pengembang

- [Syaiful Wachid] - Lead Developer - [@github_username](https://github.com/syaifulwachid)
- [Kontributor] - Maintainer - [@github_username](https://github.com/username)

## 📞 Kontak & Dukungan

- Email: [syaiful.wachid@gmail.com]
- Telegram: [@Wildan]
- Discord: [Server Link]

## 🙏 Pengakuan & Referensi

- [ITU-T Standards](https://www.itu.int)
- [Material Design](https://m3.material.io)
- [Android Jetpack](https://developer.android.com/jetpack)
- [Kotlin](https://kotlinlang.org)

## 📝 Catatan Rilis

### Versi 1.1.0 (Coming Soon)
- Fiber Color Guide
- Enhanced Power Budget Calculator
- Performance Improvements
- Bug Fixes

### Versi 1.0.0
- Initial Release
- Basic Power Budget Calculator
- Material Design 3 Implementation
- Gesture Navigation
- Share & Copy Features



