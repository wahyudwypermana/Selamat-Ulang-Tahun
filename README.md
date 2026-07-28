# Kejutan Ulang Tahun 💌

Halaman kejutan ulang tahun interaktif — buka amplop, sapaan mengetik, peta jarak Indonesia–Taiwan, galeri foto polaroid, galeri foto bentuk hati, surat, dan tiup lilin kue.

## Isi folder ini

```
kejutan-ulang-tahun/
 ├── index.html      → halaman utamanya, jangan diganti nama
 ├── README.md        → file ini
 ├── foto1.jpg ... foto9.jpg   → TAMBAHKAN SENDIRI (belum ada)
 └── lagu.mp3                   → TAMBAHKAN SENDIRI (belum ada)
```

## Langkah 1 — Isi foto

Tambahkan foto ke folder ini, beri nama persis:
`foto1.jpg` sampai `foto12.jpg`

- Foto 1–5 dipakai di galeri polaroid (tap foto untuk ganti-ganti).
- Foto 1–12 dipakai di galeri bentuk hati (posisinya sudah otomatis dihitung supaya membentuk siluet hati yang rapi).
- Boleh kurang dari 12, sisanya otomatis tampil placeholder biasa — tidak akan error, cuma bentuk hatinya jadi kurang penuh.
- Kalau formatnya `.png` bukan `.jpg`, buka `index.html` dengan text editor, cari semua tulisan `.jpg` dan ganti jadi `.png`.

## Langkah 2 — Isi musik

Tambahkan file musik, beri nama persis `lagu.mp3`.

Lalu buka `index.html`, cari baris ini dan ganti sesuai lagu kamu (opsional, cuma buat rapi — tidak wajib):
```html
<audio id="audioPlayer" src="lagu.mp3" preload="none" loop></audio>
```

## Langkah 3 — Ganti nama panggilan pacarmu

Buka `index.html`, cari teks berikut di bagian JavaScript (dekat tulisan `typeGreeting`):
```js
const text = "Hai, sayangku.\nSelamat ulang tahun,\n2 Agustus ini spesial untukmu.";
```
Ganti `"sayangku"` dengan nama panggilan dia.

## Langkah 4 — Upload ke GitHub

1. Buat repository baru di GitHub (bisa **public** atau **private** — lihat catatan di bawah).
2. Upload semua isi folder ini (index.html, README.md, foto-foto, lagu.mp3) ke repo tersebut.
   - Cara termudah: di halaman repo GitHub, klik **Add file → Upload files**, lalu drag semua file dari folder ini sekaligus.
3. Buka menu **Settings → Pages** di repo tersebut.
4. Di bagian **Source**, pilih branch `main` (atau `master`) dan folder `/root`, lalu klik **Save**.
5. Tunggu 1–2 menit, GitHub akan kasih link seperti:
   `https://namakamu.github.io/nama-repo/`
6. Buka link itu di HP untuk memastikan foto & musiknya muncul, baru kirim ke pacar kamu.

## ⚠️ Catatan privasi

Kalau repo-nya **public**, semua orang yang tahu link repo-nya bisa lihat foto & pesan kalian, bukan cuma lewat link Pages-nya. Kalau ingin lebih privat:
- Buat repo **private** — tapi GitHub Pages dari repo private butuh akun **GitHub Pro** (berbayar).
- Alternatif gratis yang lebih privat: pakai **Netlify Drop** (https://app.netlify.com/drop) — cukup drag folder ini, dapat link langsung, tanpa perlu bikin repo publik sama sekali.
