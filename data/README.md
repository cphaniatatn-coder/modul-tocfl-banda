# Data — Modul TOCFL Band A

Indeks file kerja proyek penyusunan modul ajar Mandarin persiapan TOCFL Band A
(thesis Carli). File di folder ini adalah yang disusun/dikompilasi langsung
untuk proyek — **bukan** materi sumber pihak ketiga (PDF ujian resmi TOCFL,
scan buku ajar) yang sengaja tidak diunggah ke repo publik ini karena hak cipta.

Halaman modul interaktifnya sendiri ada di [`../docs/index.html`](../docs/index.html)
([versi live](https://cphaniatatn-coder.github.io/modul-tocfl-banda/)).

## Metodologi & aturan kerja

| File | Isi |
|---|---|
| [`CLAUDE.md`](CLAUDE.md) | Instruksi kerja proyek — aturan inti penyusunan modul, urutan prioritas vs `prinsip-thesis.md`, prosedur wajib per bab |
| [`prinsip-thesis.md`](prinsip-thesis.md) | Fondasi metodologis thesis — prinsip scene-first, sistem dua-lapis 核心/補充, pemetaan level A0/A1/A2, lima pilar teori (Willis, Mayer, Sweller, Bachman & Palmer, Zimmerman) |

## Hasil analisis (memori)

| File | Isi |
|---|---|
| [`analisis-modul.md`](analisis-modul.md) | Analisis buku ajar yang sudah beredar (來學華語, 當代中文, 時代電子檔) — pola pengelompokan tema, praktik terbaik, pemetaan ke TOCFL/TBCL |
| [`analisis-ujian-tocfl.md`](analisis-ujian-tocfl.md) | Analisis penuh 5 set Mendengar + 5 set Membaca TOCFL Band A — format soal, kerangka Bachman & Palmer, tema & grammar yang sering diuji, peringkat 3 besar |

## Pencatat & data kerja

| File | Isi |
|---|---|
| [`ledger.md`](ledger.md) | Pencatat anti-pengulangan (zero redundancy) — kosakata & grammar per modul, hasil rekonsiliasi, hasil audit cakupan resmi TBCL |
| [`kosakata.xlsx`](kosakata.xlsx) | Daftar kosakata sumber, 3 sheet per level TBCL (第1級/第2級/第3級) |
| [`grammar.xlsx`](grammar.xlsx) | Daftar tata bahasa sumber, 3 sheet per level TBCL |

## Workbook modul per volume

| File | Isi |
|---|---|
| [`Volume1_TOCFL_A0.xlsx`](Volume1_TOCFL_A0.xlsx) | Volume 1 (第一級/A0) — 13 modul: ringkasan, kosakata+pinyin, dialog Tahap B, Free Pool (Kata Alat), catatan & keputusan |
| [`Volume2_TOCFL_A1.xlsx`](Volume2_TOCFL_A1.xlsx) | Volume 2 (第二級/A1) — Free Pool 226 kata tingkat 核心詞 resmi, dikelompokkan 3 kategori |
| [`Volume3_TOCFL_A2.xlsx`](Volume3_TOCFL_A2.xlsx) | Volume 3 (第三級/A2) — Free Pool 199 kata tingkat 核心詞 resmi, dikelompokkan 3 kategori |

## Ringkasan status (per catatan terakhir di `ledger.md`)

- **34 modul total**: 13 (Volume 1) + 9 (Volume 2) + 12 (Volume 3)
- **Cakupan kosakata terhadap daftar resmi TBCL**: Level 1 ~79.9%/70.7%
  (situasional/fungsi), Level 2 ~94.2%, Level 3 ~97.7% — detail lengkap
  termasuk penelusuran satu-satu kata yang belum tercakup ada di
  `ledger.md` bagian "Catatan Status"
- Beberapa titik masih ditandai terbuka (belum jadi keputusan final) —
  lihat `CLAUDE.md` bagian "Prinsip thesis" dan `ledger.md` bagian
  "Catatan Status" untuk daftar lengkapnya

---
*File `.md` di folder ini bisa dibuka langsung di VS Code (termasuk preview
lewat `Ctrl+Shift+V` / `Cmd+Shift+V`) atau dibaca langsung di GitHub. File
`.xlsx` perlu Excel/LibreOffice/Google Sheets.*
