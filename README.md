# AnimeStream ID

Aplikasi Android katalog anime online.

## Fitur
- Anime yang sedang tayang dari Jikan API
- Pencarian anime
- Detail anime, sinopsis, genre, rating, jumlah episode, status
- Poster anime
- Tombol "Tonton Resmi" yang membuka pencarian judul di Crunchyroll
- Dark UI
- Tidak membutuhkan database server untuk katalog dasar

## Sumber data
Jikan API: https://api.jikan.moe/v4/
Jikan merupakan API tidak resmi untuk data MyAnimeList. API bersifat read-only.

## Build
1. Buka folder ini di Android Studio.
2. Tunggu Gradle selesai sync.
3. Pilih Build > Build APK(s).
4. APK debug biasanya berada di:
   app/build/outputs/apk/debug/app-debug.apk

## Catatan lisensi
Project ini tidak meng-host, mengunduh, atau mendistribusikan episode anime berhak cipta.
Untuk streaming penuh, gunakan penyedia resmi dan pastikan lisensi tersedia di wilayah pengguna.

## Build otomatis di GitHub
Push project ke GitHub. Workflow `.github/workflows/build-apk.yml` akan menjalankan build dan menyimpan `app-debug.apk` sebagai Artifact pada halaman Actions.
