# 🍭 Kebun Binar Bumi

Game match-3 dengan mode Kasual dan mode Target (level, pesanan pelanggan, uang, Warung Ucok, dan berbagai alat ajaib). Bisa dimainkan di HP maupun desktop, langsung dari browser — tidak perlu server backend atau instalasi apa pun.

## Cara deploy ke GitHub Pages

1. Buat repository baru di GitHub (bisa publik atau privat, asal privat perlu paket GitHub yang mendukung Pages).
2. Upload/push semua isi folder ini (terutama `index.html`) ke branch utama repository tersebut (misalnya `main`).
3. Di repository, buka **Settings → Pages**.
4. Pada bagian **Build and deployment → Source**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/ (root)`, lalu klik **Save**.
6. Tunggu sebentar (biasanya 1-2 menit), lalu GitHub akan menampilkan URL situsnya, formatnya seperti:
   `https://<username-github-kamu>.github.io/<nama-repo>/`
7. Buka URL tersebut — game langsung bisa dimainkan, dan link itu juga bisa dibagikan ke orang lain.

## Catatan

- Semua kode (HTML, CSS, JavaScript) dan gambar (logo, ikon Durian, ikon Buah Naga) sudah menyatu di dalam satu file `index.html`, jadi tidak ada file lain yang perlu di-upload.
- Kalau ingin mengganti nama game/URL folder, cukup ganti nama repository-nya di GitHub — tidak perlu mengubah isi `index.html`.
