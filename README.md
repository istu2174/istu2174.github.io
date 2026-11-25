# istu2174.github.io

Kode sumber portofolio saya, live di [istu2174.github.io](https://istu2174.github.io).

Isinya tujuh proyek web beserta demo live, riwayat magang dan pendidikan, daftar keahlian, sertifikat, dan kontak. Halamannya statis: satu `index.html` dengan CSS dan JavaScript inline, tanpa framework dan tanpa build step, jadi GitHub Pages langsung menyajikannya dari branch utama.

## Struktur

```
index.html   halaman portofolio
go.html      halaman perantara saat membuka demo yang server-nya perlu waktu bangun (cold start)
img/         screenshot proyek (desktop & HP), foto, dan sertifikat
```

## Menjalankan di lokal

Buka `index.html` langsung di browser, atau jalankan server statis apa saja:

```bash
npx serve .
```

Perubahan yang di-push ke branch utama otomatis tayang lewat GitHub Pages.
