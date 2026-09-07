# ebook-claude-llm

Pengetahuan & draft **Seri Buku Piano Musti Musik** (Dave Henokh Liong), dipindahkan dari chat claude.ai "kurikulum pembelajaran lagu pop" supaya kerja lanjutan bisa dilakukan di Claude Code.

## Mulai dari sini

1. Baca [`RANGKUMAN_PROYEK_BUKU.md`](RANGKUMAN_PROYEK_BUKU.md) — status tiap buku + hal yang masih pending.
2. Baca [`CLAUDE.md`](CLAUDE.md) — gaya penulisan, format baku, dan sistem notasi pattern yang wajib diikuti semua buku.

## 5 buku dalam seri

1. **Strategi Denger Lagu 1x Langsung Bisa Main** — draft, ajarkan Relative Pitch. (pending: BAB VI Template, penempatan pattern Jazz/Latin, 10 lagu latihan)
2. **Worship Starter — Belajar Worship dalam 7 Hari** — draft. (pending: pattern Hari 2 & 3, nomor WhatsApp)
3. **Cara Buat dan Aransemen Lagu** — selesai (9 step aransemen).
4. **Cara Buat Lagu dari 0** — selesai (6 BAB songwriting).
5. **6 Cara Pindah Kunci dengan Manis** — selesai (catatan: transkrip sumber mismatch, cross-check kalau video asli ketemu).

Detail lengkap tiap buku ada di `RANGKUMAN_PROYEK_BUKU.md`.

## Ebook jadi (folder `ebooks/`)

Ebook format .docx, siap dibuka di Word. A5, Montserrat (body 11 / heading 14 bold / sub-heading 12 bold), spasi 1,5, paragraf menjorok, tanpa strip panjang. Struktur baku: Kata Penulis, Kata Mereka, Cara Buku Ini Membantumu, Daftar Isi, BAB (judul 1 halaman sendiri), Langkah Praktis. QR di awal tiap bab.

| File | Isi |
|---|---|
| `ebooks/EBOOK Fill In dan Improvisasi.docx` | Fill in umum (pop/jazz/worship) sampai improvisasi. 4 BAB. ~59 hlm. 27 screenshot dari `sumber-fill-in/Modul Improvisasi Jazz.pdf`. Ada halaman timestamp video di akhir. |
| `ebooks/Buku_Fill_In_dan_Improvisasi.md` | Draft markdown ebook Fill In (versi awal, sebelum jadi .docx) |
| `ebooks/EBOOK Strategi Pakai AI ala Musti Musik.docx` | Cara pakai AI (Claude Code) untuk bikin deck presentasi dan game edukasi. 2 BAB. ~48 hlm. 6 diagram dibuat sendiri. |

Sumber materi: `sumber-fill-in/` (transkrip .sbv + 2 PDF PPT) dan `sumber-strategi-ai/` (2 workflow .md).

Script generator + gambar hasil crop ada di `build/` (`build_ebook.js` untuk Fill In, `build_ebook2.js` untuk Strategi AI, `diagrams.py` + `crop.py` untuk gambar). Perlu Node `docx` dan Python `Pillow`. Path input di script masih absolut ke mesin lokal, sesuaikan sebelum jalan ulang.

**Perlu diisi manual di tiap .docx:** kotak QR (awal bab), foto testimoni, dan (khusus Fill In) 3 slot penerapan di BAB I + link video Modul Improvisasi Jazz.
