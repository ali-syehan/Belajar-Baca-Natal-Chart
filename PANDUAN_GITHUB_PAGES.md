# Panduan Upload HTML Tunggal ke GitHub Pages

## Tahap 1 — Buat repository baru

1. Buka GitHub.
2. Klik tombol **+** di kanan atas.
3. Pilih **New repository**.
4. Isi nama repository, contoh:

```text
natal-chart-klasik-modern
```

5. Pilih **Public** agar mudah dibuka melalui GitHub Pages.
6. Klik **Create repository**.

## Tahap 2 — Upload file

1. Di halaman repository baru, klik **uploading an existing file**.
2. Upload isi folder dari ZIP ini, bukan ZIP-nya.
3. Pastikan file utama bernama:

```text
index.html
```

4. Klik **Commit changes**.

## Tahap 3 — Aktifkan GitHub Pages

1. Masuk ke tab **Settings**.
2. Di sidebar kiri, pilih **Pages**.
3. Pada bagian **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
4. Klik **Save**.

## Tahap 4 — Buka link aplikasi

Setelah Pages aktif, GitHub akan memberi link seperti:

```text
https://USERNAME.github.io/natal-chart-klasik-modern/
```

Jika halaman belum muncul, tunggu sebentar lalu refresh halaman **Settings → Pages**.

## Catatan penting

- Jangan ubah nama `index.html`, karena GitHub Pages mencari file utama dengan nama itu.
- Karena aplikasi ini HTML tunggal, tidak perlu install apa pun.
- Jika nanti Anda revisi aplikasi, cukup replace `index.html` lalu **Commit changes** lagi.
