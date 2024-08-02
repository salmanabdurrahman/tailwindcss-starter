# TailwindCSS Starter Kit

## Deskripsi

Starter kit ini menyediakan dasar yang diperlukan untuk memulai proyek web menggunakan HTML, TailwindCSS, dan Vanilla JavaScript. Dengan menggunakan starter kit ini, Anda dapat dengan cepat membuat proyek web yang modern dan responsif.

## Struktur Direktori

```
tailwindcss-starter/
├── public/
│   └── css/
│       └── style.css
├── src/
│   ├── css/
│   │   └── input.css
│   └── js/
│       └── script.js
├── index.html
├── package.json
└── ...
```

## Cara Menggunakan

1. **Unduh ZIP dari GitHub**

    Unduh file ZIP dari [repo ini](https://github.com/salmanabdurrahman/tailwindcss-starter/archive/refs/heads/main.zip) dan ekstrak ke direktori pilihan Anda.

2. **Install npm Packages**

    Buka terminal di direktori proyek Anda dan jalankan perintah berikut untuk menginstall semua dependensi yang diperlukan:

    ```bash
    npm install
    ```

3. **Install TailwindCSS, PostCSS, dan Autoprefixer**

    Jalankan perintah berikut untuk menginstall TailwindCSS, PostCSS, dan Autoprefixer sebagai dev dependencies:

    ```bash
    npm install -D tailwindcss postcss autoprefixer
    ```

4. **Build CSS**

    Untuk memproses file CSS dengan TailwindCSS, jalankan perintah berikut:

    ```bash
    npm run build-css
    ```

5. **Jalankan Proyek**

    Anda bisa membuka file `index.html` di browser untuk melihat hasilnya. Untuk pengembangan yang lebih lanjut, disarankan untuk menggunakan live server seperti `live-server` atau ekstensinya di VSCode.

## Catatan

Pastikan Anda sudah menginstall Node.js dan npm di sistem Anda sebelum menjalankan langkah-langkah di atas.
