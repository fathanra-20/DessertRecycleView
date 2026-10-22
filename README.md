# DessertRecycleView

**DessertRecycleView** adalah aplikasi Android sederhana yang dibangun menggunakan bahasa Kotlin untuk mendemonstrasikan implementasi `RecyclerView` dengan custom adapter (`DessertAdapter`) dan pola ViewHolder. Aplikasi ini menampilkan daftar dessert populer (Donut, Ice Cream Sandwich, dan Froyo) dengan tata letak item yang kustom dan pewarnaan latar belakang dinamis.

---

## 🚀 Fitur Utama

- **Implementasi RecyclerView**: Menampilkan daftar item secara efisien dengan pengguliran vertikal menggunakan `LinearLayoutManager`.
- **Custom Adapter & ViewHolder**: Menerapkan `RecyclerView.Adapter` dan `RecyclerView.ViewHolder` untuk daur ulang tampilan (`view recycling`) dan pengikatan data yang bersih.
- **Pewarnaan Dinamis**: Menghasilkan latar belakang berbentuk lingkaran secara dinamis dengan kode warna HEX yang berbeda untuk setiap ikon dessert menggunakan `GradientDrawable`.
- **Dukungan Edge-to-Edge**: Dibangun dengan penanganan `window insets` edge-to-edge Android modern untuk pengalaman antarmuka yang imersif.
- **Komponen Material Design**: Memanfaatkan pedoman Material Design dan tata letak XML.

---

## 📱 Teknologi & Kebutuhan Sistem

- **Bahasa Pemrograman**: Kotlin
- **Min SDK**: 27 (Android 8.1 Oreo)
- **Compile/Target SDK**: 37
- **UI Framework**: Android Views (Layout XML, RecyclerView, ConstraintLayout)
- **IDE**: Android Studio

---

## 📂 Struktur Proyek

```text
app/
├── src/
│   ├── main/
│   │   ├── java/lat/pam/dessertrecycleview/
│   │   │   ├── MainActivity.kt        # Titik masuk utama menginisialisasi RecyclerView & data dessert
│   │   │   ├── DessertAdapter.kt      # RecyclerView Adapter untuk mengikat data dessert ke tampilan
│   │   │   └── Dessert.kt             # Data class yang merepresentasikan atribut dessert
│   │   ├── res/
│   │   │   ├── layout/
│   │   │   │   ├── activity_main.xml  # Layout layar utama yang berisi RecyclerView
│   │   │   │   └── itemdesert.xml     # Layout item daftar individu untuk setiap dessert
│   │   └── drawable/              # Ikon dessert & bentuk latar belakang
└── build.gradle.kts                   # Konfigurasi Gradle tingkat aplikasi
```

---

## 🛠️ Cara Memulai

1. **Buka** proyek ini di **Android Studio**.
2. Tunggu hingga proses **Gradle sync** selesai dan dependensi terunduh.
3. Hubungkan perangkat fisik Android atau jalankan **Android Emulator** (API 27 atau lebih tinggi).
4. Klik tombol **Run** (▶) di Android Studio untuk membangun dan menjalankan aplikasi.

---

## 📄 Lisensi

Proyek ini dikembangkan untuk tujuan pembelajaran dan demonstrasi sebagai bagian dari tugas pengembangan aplikasi seluler.
