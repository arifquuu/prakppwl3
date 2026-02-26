# ppwl3

To install dependencies:

```bash
bun install
```

To run:

```bash
bun run index.ts
```

This project was created using `bun init` in bun v1.3.8. [Bun](https://bun.com) is a fast all-in-one JavaScript runtime.


# Praktikum Modul 3 – Tailwind CSS

## Praktikum 2 – Perbedaan Tailwind CSS v3 vs v4

Tailwind v3 berjalan di atas Node.js sehingga proses compile kodenya relatif lebih lambat. Lalu, Tailwind v3 membutuhkan proses konfigurasi awal yang lumayan panjang dan memiliki banyak dependensi NPM
Tailwind v4 menggunakan engine baru berbasis Rust (bernama Oxide) yang membuat proses compile jauh lebih cepat. Lalu, Tailwind v4 bersifat zero-configuration (langsung siap pakai setelah diinstal) dan ukuran instalasinya jauh lebih ringan.

## Praktikum 4 – Box Model Tailwind CSS
Jika kita coba memberi warna pada latar belakang elemen dengan kode bg-blue-600, Maka bagian type box yang terpengaruh adalah content box & padding box.
