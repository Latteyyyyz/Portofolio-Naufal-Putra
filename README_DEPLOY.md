# Deploy Portfolio Website

Project ini adalah website statis biasa, jadi paling gampang di-deploy ke Netlify atau GitHub Pages.

## Opsi paling cepat: Netlify Drop

1. Buka [https://app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag folder `Portofolio_Web` ke area upload
3. Tunggu proses selesai
4. Netlify akan memberi link publik yang bisa langsung dibuka orang lain

Kalau mau nama link yang lebih rapi, login ke Netlify lalu ubah nama situs di dashboard.

## Opsi yang lebih rapi: GitHub + Netlify

1. Buat repository baru di GitHub
2. Upload isi folder project ini
3. Login ke Netlify
4. Pilih `Add new site` -> `Import an existing project`
5. Hubungkan repository GitHub tadi
6. Karena ini website statis, pengaturan deploy-nya cukup:
   - Build command: kosongkan
   - Publish directory: `.`
7. Klik `Deploy site`

File `netlify.toml` sudah disiapkan supaya Netlify langsung membaca konfigurasi project ini.

## Opsi gratis lain: GitHub Pages

1. Buat repository GitHub
2. Upload semua file project ke repository itu
3. Masuk ke `Settings` repository
4. Buka menu `Pages`
5. Pada bagian source, pilih branch `main` lalu folder `/root`
6. Simpan
7. Tunggu beberapa menit sampai muncul link publik GitHub Pages

## File utama project

- `index.html`
- `style.css`
- folder `assets`

Saat deploy, pastikan ketiganya ikut ter-upload.
