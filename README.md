# AR Chess Arena

AR Chess Arena adalah aplikasi Flutter bertema catur yang menghadirkan pengalaman 3D, Augmented Reality (AR), dan pembelajaran interaktif.

## Tema Project

Project ini memilih tema catur karena catur cocok divisualisasikan dalam bentuk papan dan bidak 3D. Pengguna dapat melihat arena catur secara interaktif, mempelajari posisi bidak, dan memahami contoh gerakan melalui mode belajar AR.

## Metode AR Yang Digunakan

AR Chess Arena menggunakan pendekatan markerless AR berbasis viewer 3D. Model papan catur dan bidak ditampilkan sebagai objek 3D yang dapat ditempatkan ke ruang nyata melalui dukungan AR pada perangkat atau browser yang kompatibel.

Alasan menggunakan metode ini:

- Tidak membutuhkan marker khusus, sehingga pengalaman pengguna lebih sederhana.
- Cocok untuk visualisasi objek seperti papan catur di atas meja.
- Mudah dikombinasikan dengan model 3D GLB dan Flutter.
- Dapat dijalankan lintas platform, terutama web dan perangkat mobile yang mendukung AR.

## Fitur Utama

- Mode bermain catur 3D interaktif.
- Mode belajar AR untuk menampilkan papan catur di ruang nyata.
- Model 3D papan dan bidak catur dalam format `.glb`.
- Animasi contoh gerakan catur untuk kebutuhan edukasi.
- Panel status permainan dan dialog LAN untuk dukungan interaksi antarpemain.
- Dukungan multi-platform Flutter: Android, iOS, web, Windows, Linux, dan macOS.

## Struktur Proyek

- `lib/` - Kode sumber Flutter, layar aplikasi, widget, model, dan service catur.
- `lib/features/chess/` - Fitur utama terkait catur, viewer 3D, aturan catur, bot, dan layar AR.
- `assets/models/` - Aset model 3D catur dalam format `.glb`.
- `web/` - Konfigurasi web Flutter.
- `android/`, `ios/`, `windows/`, `linux/`, `macos/` - Konfigurasi platform.
- `test/` - File pengujian Flutter.
- `tools/` - Script pendukung pembuatan aset/model.

## Prasyarat

- Flutter SDK sesuai environment pada `pubspec.yaml`.
- Browser modern untuk menjalankan versi web.
- Perangkat mobile yang mendukung AR jika ingin mencoba pengalaman AR secara langsung.

## Instalasi

1. Clone atau buka folder project ini.
2. Pastikan Flutter sudah terpasang dan dapat dijalankan dari terminal.
3. Ambil dependensi:

```bash
flutter pub get
```

4. Jalankan aplikasi:

```bash
flutter run
```

Untuk menjalankan :

```bash
flutter run 
```

## Aset 3D

Aset utama project berada di folder `assets/models/`:

- `chess.glb`
- `chess-learning.glb`
- `chess-interactive.glb`

Semua aset tersebut sudah didaftarkan melalui konfigurasi `assets/models/` di `pubspec.yaml`.

## Tujuan Proyek

Project ini bertujuan membuat media pembelajaran dan demonstrasi catur berbasis 3D/AR yang mudah dipahami. Selain sebagai implementasi Grafika Komputer, aplikasi ini juga menunjukkan bagaimana Flutter dapat digunakan untuk membangun pengalaman visual interaktif dengan aset 3D.

## Lisensi

Lisensi belum ditentukan.
