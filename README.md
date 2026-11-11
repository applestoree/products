# Apple Products — Visual Prompt Library

Repository ini merupakan library **AI visual product prompts** untuk menghasilkan gambar produk Apple dengan tampilan yang konsisten, detail desain yang akurat, dan kualitas visual komersial.

Setiap file Markdown berisi satu **master visual prompt** untuk satu model produk. Prompt dirancang untuk menggambarkan identitas visual dan keseluruhan tampilan model tersebut, bukan dipisahkan menjadi file berdasarkan jenis gambar atau sudut kamera.

## Repository Structure

```text
products/
├── iPhone/
│   ├── iPhone 16.md
│   └── iPhone Air.md
├── iWatch/
├── iMac/
├── iPad/
└── AirPods/
```

### Product Categories

| Folder | Kategori |
|---|---|
| `iPhone/` | Apple iPhone |
| `iWatch/` | Apple Watch |
| `iMac/` | Apple iMac |
| `iPad/` | Apple iPad |
| `AirPods/` | Apple AirPods |

## File Convention

Gunakan satu file Markdown untuk setiap model produk.

Contoh:

- `iPhone/iPhone 16.md`
- `iPhone/iPhone Air.md`

Nama file mengikuti nama model produk agar mudah ditemukan dan digunakan kembali.

## Master Prompt Structure

Setiap master visual prompt menggunakan 11 bagian berikut:

1. **SUBJECT** — Identitas produk dan karakteristik desain utama.
2. **ACTION** — Posisi atau cara produk ditampilkan.
3. **ENVIRONMENT** — Latar dan lingkungan visual.
4. **COMPOSITION** — Sudut pandang, framing, dan tata letak produk.
5. **VISUAL STYLE** — Gaya fotografi atau visual yang diinginkan.
6. **LIGHTING** — Pengaturan pencahayaan dan refleksi.
7. **CAMERA & QUALITY** — Karakteristik kamera dan kualitas hasil.
8. **COLOR & MOOD** — Warna produk, latar, dan suasana.
9. **DETAILS** — Detail hardware, material, tombol, kamera, dan proporsi.
10. **NEGATIVE CONSTRAINTS** — Elemen atau kesalahan visual yang harus dihindari.
11. **FINAL INSTRUCTION** — Instruksi akhir untuk menghasilkan gambar.

## Prompt Guidelines

- Satu model produk = satu file `.md`.
- Satu file merupakan master prompt yang mencakup keseluruhan tampilan model produk.
- Pertahankan karakteristik hardware, material, susunan kamera, tombol, port, dan proporsi sesuai model yang dituju.
- Hindari detail desain yang tidak sesuai dengan model produk.
- Gunakan instruksi visual yang spesifik dan dapat dipahami oleh image generation model.
- Jangan membuat file terpisah hanya untuk variasi sudut atau jenis tampilan; cakupan tersebut ditangani oleh master prompt.

## Existing Prompts

### iPhone

- [iPhone 16](./iPhone/iPhone%2016.md)
- [iPhone Air](./iPhone/iPhone%20Air.md)

---

**Purpose:** Reusable master prompts for AI-generated Apple product visuals.
