# Ikemen Joshi Demo Kawaii Heroine ni Naremasu ka?

> 'Bisakah kamu membuat diriku menjadi seorang princess (Heroine)?'' Sumeragi Tsukasa — siswi SMA yang dijuluki ikemen, seorang artis populer, dan selalu dikerubungi cewek-cewek. Sedangkan Mikage Himeno — cowok SMA yang sudah debut jadi mangaka tapi proposal serialisasinya selalu ditolak. Saat tujuan mereka saling bertemu, Mereka langsung sembunyi-sembunyi latihan untuk menjadi seorang heroine dan nggak boleh ketahuan sama siapa pun! dan itu yang bikin situasi diantara mereka menjadi mendebarkan!

---

## Info

| | |
|---|---|
| Judul | Ikemen Joshi Demo Kawaii Heroine ni Naremasu ka? |
| Judul Alternatif | イケメン女子でもかわいいヒロインになれますか？ |
| Author | Tsumikitsuki |
| Tipe | Manga (Hitam Putih) |
| Status | Ongoing |
| Genre | Shounen · Comedy · Romance · School Life · Slice of Life |
| Chapter | 1 chapter |

## Link

- [MangaDex](https://mangadex.org/title/755733bb-5842-4ff5-af0f-b4c1605bfe85/ikemen-joshi-demo-kawaii-heroine-ni-naremasu-ka)
- [Raw](https://kirapo.jp/meteor/titles/ikemenjoshi)

---

## Struktur

```
IkemenJoshi/
├── manga-config.json     # Metadata manga
├── manga.json            # Data chapter (auto-generated)
├── manga-automation.js   # Script automation
├── encrypt-manifest.js   # Script enkripsi manifest
├── daily-views.json      # Data views harian
└── <chapter>/
    └── manifest.json     # Daftar halaman (encrypted)
```

## Automation

Semua proses berjalan otomatis via GitHub Actions:

1. Push chapter baru (folder + manifest.json)
2. `encrypt-manifest.yml` — enkripsi manifest
3. `manga-automation.yml` — regenerate manga.json
4. Trigger rebuild ke website utama
5. `sync-cover.yml` — sinkronisasi cover dari website

---

Bagian dari [Nurananto Scanlation](https://nuranantoscans.my.id)