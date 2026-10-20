# DessertRecycleView

Tugas Praktikum Aplikasi Mobile (PAM) - Modul 2

## Deskripsi Proyek
Aplikasi Android berbasis Kotlin yang menampilkan katalog daftar dessert (Droid Desserts) interaktif. Proyek ini memodifikasi `RecyclerView` dengan menyajikan gambar avatar lingkaran bergradasi warna dinamis serta teks deskripsi untuk setiap menu.

## Fitur Utama
Katalog Dessert Visual: Menampilkan menu ikonik (Donuts, Ice Cream Sandwiches, Froyo) lengkap beserta visual dan deskripsinya.
Latar Belakang Lingkaran Dinamis: Mengubah pewarnaan background gambar (`circle_background.xml`) menggunakan kode Hex secara runtime via `GradientDrawable`.
Tata Letak CoordinatorLayout: Menggunakan `CoordinatorLayout` untuk menyusun struktur judul utama dan area daftar menu.
Tampilan Edge-to-Edge: Pengaturan tata letak yang mendukung tampilan penuh hingga batas layar perangkat.

## Teknologi & Library
Bahasa Pemrograman: Kotlin, Minimum SDK: API Level 27 (Android 8.1 Oreo), Komponen UI: `RecyclerView`, `CoordinatorLayout`, `FrameLayout`, `ImageView`, `TextView`, Build Tool: Gradle (Kotlin DSL)

## Struktur Berkas Utama
```text
.
├── app/
│   └── src/
│       └── main/
│           ├── java/lat/pam/dessertrecycleview/
│           │   ├── Dessert.kt
│           │   ├── DessertAdapter.kt
│           │   └── MainActivity.kt
│           └── res/
│               ├── drawable/
│               │   ├── circle_background.xml
│               │   ├── donut_circle.png
│               │   ├── froyo_circle.png
│               │   └── icecream_circle.png
│               └── layout/
│                   ├── activity_main.xml
│                   └── itemdesert.xml
