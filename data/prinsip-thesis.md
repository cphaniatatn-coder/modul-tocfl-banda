# prinsip-thesis.md — Prinsip Perancangan (WAJIB dibaca sebelum menyusun modul/soal)

> File ini adalah fondasi metodologis thesis. Setiap modul & setiap soal HARUS
> patuh pada prinsip di sini. Jika ada perintah yang bertentangan dengan prinsip
> ini, hentikan dan tanyakan dulu — jangan diam-diam melanggar.

## Prinsip utama: SCENE-FIRST (情境優先)
- Silabus bersifat situasional-fungsional, BUKAN struktural/leksikal.
- Urutan berpikir: rancang ADEGAN dulu → kosakata & grammar dipilih karena
  adegan itu membutuhkannya ("adegan dulu, kosakata mengikuti").
- Tiap modul = satu adegan kehidupan nyata, diberi judul berupa ujaran nyata
  (gaya 來學華語: 您好 / 我有兩個弟弟).
- Ekspresi dari Willis TBLT: makna/tugas mendahului bentuk (form).
- DITOLAK: pendekatan "kumpulkan daftar kata dulu, baru ditempeli situasi."

## Alur enam tahap tiap modul (logika Willis TBLL — tugas SEBELUM grammar)
1. 情境導入 — pengantar konteks + penetapan tujuan (SRL).
2. 情境對話 — dialog situasional (dual-coding, Mayer).
3. 詞彙 — input kosakata dengan audio.
4. 溝通任務 — tugas komunikatif bergaya TOCFL Band A (cloze + listening).
5. 語法聚焦/積木 — grammar "balok Lego", ditempatkan SETELAH tugas.
6. 反思與進度 — evaluasi diri + pelacakan kemajuan.
> Grammar TIDAK boleh diletakkan sebelum tugas (itu pola PPP, bukan TBLL).

## Prinsip kosakata
- Dua lapis: 核心 (produktif/aktif) vs 補充 (reseptif/pengenalan) — cakupan ujian
  penuh tanpa membebani (Sweller CLT).
- Input dikunci pada daftar kata level TBCL yang tetap (fidelitas level).
- 新詞量 (jumlah kata benar-benar baru per modul) dipakai sebagai metrik beban kognitif.
- 工具詞 (angka, waktu, sapaan, fungsi) disebar & didaur ke adegan yang secara
  alami membutuhkannya — BUKAN dijadikan modul terpisah.
- Vol 1: dahulukan 具體詞 (kata konkret/mudah dibayangkan), tapi tetap terikat
  pada adegan ("concrete-first DI DALAM scene-first").

## Penanganan kosakata sisa: scene-first vs cakupan ujian
> Menjawab ketegangan: kalau adegan yang menentukan kata, pasti ADA kata level
> TBCL yang tidak kebagian adegan. Karena ini produk ujian, saat scene-first &
> cakupan bentrok → CAKUPAN MENANG, tapi lewat dua lapis (bukan dengan memaksa
> semua kata jadi 核心).

- Adegan menentukan STRUKTUR & urutan belajar; TIDAK ada kata level TBCL yang
  boleh bocor tak terajarkan.
- 核心 (produktif): kata yang lahir dari adegan, dipakai aktif di dialog & tugas.
  Scene-first berlaku penuh di lapis ini; jumlah per modul dijaga rendah (Sweller).
- 補充 (reseptif): RUMAH bagi kata level yang tak muncul di adegan mana pun —
  diajarkan untuk DIKENALI, bukan diproduksi; ditempel ke adegan terdekat yang
  paling relevan (tetap tidak decontextualized).
- Aturan cakupan: cakupan daftar kata per level = 100% WAJIB, dipenuhi oleh
  gabungan 核心 + 補充. JANGAN paksa semua kata jadi 核心 (overload, langgar CLT).
- 工具詞 & 功能詞 (angka, waktu, sapaan, partikel) dikecualikan dari "harus muncul
  di adegan tertentu" — disebar & didaur ke banyak adegan (spiral Bruner).
- Konsekuensi angka: "berapa kata per modul" hanya mengatur porsi 核心; "berapa
  kata per level" dipenuhi 100% oleh 核心 + 補充. Kedua angka TIDAK lagi bertabrakan.

### Instruksi operasional saat menyusun modul
- Saat sebuah adegan disusun, kata level yang tidak terpakai JANGAN dibuang —
  alokasikan sebagai 補充 di modul yang paling relevan.
- Di AKHIR tiap level, jalankan audit cakupan: pastikan seluruh daftar kata level
  itu sudah tercakup (sebagai 核心 ATAU 補充). Laporkan sisa yang belum tertampung
  ke Carli, jangan diam-diam dianggap selesai.

## Kosakata 多義詞 (banyak arti) yang muncul di beberapa adegan
> Masalah: satu 詞形 (bentuk kata) bisa punya beberapa 義項 (makna), dan tiap makna
> wajar muncul di adegan berbeda (mis. 打: 打電話 di komunikasi vs 打籃球 di olahraga;
> 開: 開門 / 開車 / 開會). Aturan zero-redundancy yang naif akan salah menolak ini.

- UNIT PELACAKAN REDUNDANSI adalah 義項 (bentuk + makna), BUKAN bentuk kata telanjang.
  - Bentuk sama + makna BARU (belum diajarkan) = item 核心 baru yang SAH →
    boleh muncul lagi, DIHITUNG sebagai 新詞.
  - Bentuk sama + makna SAMA (sudah diajarkan) = daur ulang/複習 (spiral) →
    TIDAK memakan jatah 新詞量, TIDAK melanggar zero-redundancy.
- Batas level: hanya 義項 yang ditetapkan/dibutuhkan pada level TBCL itu yang
  dihitung. Makna di luar level TIDAK dipaksa dimunculkan.
- Ini menajamkan Aturan Zero-Redundancy di CLAUDE.md: "tidak boleh diulang"
  berlaku pada 義項, bukan 詞形. Selaras dengan metrik 新詞量.

### Cara Claude mengetahui & mencatatnya (operasional)
- Ledger mencatat per-義項, bukan per-詞形. Format entri:
  `詞形（makna singkat｜情境/modul）`. Contoh: `打（打電話｜komunikasi）` dan
  `打（打籃球｜olahraga）` = dua entri berbeda, dua-duanya boleh.
- Saat 詞形 yang sudah ada di ledger muncul lagi, Claude WAJIB cek dulu:
  makna ini SAMA atau BEDA dengan yang tercatat?
  - Beda → item 核心 baru, tambahkan entri baru.
  - Sama → daur ulang (複習), jangan dihitung sebagai kata baru.
- Jika daftar kata level menandai 義項 secara eksplisit → pakai itu. Jika tidak →
  Claude mendeteksi makna dari konteks dan TANDAI kasus ambigu untuk Carli putuskan
  (jangan diselesaikan diam-diam — konsisten dengan prinsip kejujuran metodologis).

## Prinsip grammar
- Grammar dipilih dengan "principled fit": grammar yang DITETAPKAN untuk level
  TBCL itu DAN dibutuhkan untuk memakai kosakata inti dalam kalimat —
  BUKAN "mana yang lebih gampang" (ditolak: terlalu subjektif untuk sidang).
- Rakitan "balok Lego" untuk mengendalikan beban kognitif.
- 功能詞 (partikel, konjungsi) JANGAN dipaksa masuk kategori situasional →
  gunakan keranjang 功能詞／語法 tersendiri (lebih jujur & berguna).

## Pemetaan level (sudah dikonfirmasi)
- A0 = TBCL 級1 | A1 = TBCL 級2 | A2 = TBCL 級3.
- Berpijak pada daftar resmi TBCL 漢字/詞語/語法點 — BUKAN label TOCFL (準備/入門/基礎).
- Sumber: 華語文能力基準應用參考指引 (國教院, 2023).
- A0 (級1): 246 漢字, 396 詞語, 15 語法點.
- A1 (級2): 258 漢字, 402 詞語, 92 語法點.
- A2 (級3): 297 漢字, 456 詞語, 134 語法點.

## Pendekatan berbeda per level (disetujui pembimbing)
- A0: vocabulary-first. Adegan tetap ada tapi jadi wadah kosakata; grammar
  diminimalkan. Kata yang tak muat di adegan tetap diajarkan sebagai 補充詞.
- TBLL penuh hanya diterapkan di A1 & A2 (bahasa yang langsung terpakai harian).
- Grammar A0 dipilih lewat principled fit, bukan tingkat kemudahan.

## Prioritas audiens
- Sasaran: peserta TOCFL asal Indonesia.
- Latihan soal & strategi ujian LEBIH diprioritaskan daripada elemen visual/multimedia
  (koreksi setelah sempat terlalu menonjolkan rekomendasi visual Mayer).

## Prinsip kejujuran metodologis (untuk pertahanan thesis)
- Pemetaan grammar→situasi yang ambigu: TANDAI dengan catatan metodologis eksplisit,
  jangan diselesaikan diam-diam.
- Klasifikasi 主線/支線 = "prioritas hipotetis, menunggu validasi" (belum ada kunci jawaban resmi).
- Jumlah modul harus dibingkai sebagai hasil berbasis teori (turunan dari batasan CLT +
  cakupan grammar penuh), bukan pilihan estetis/sembarang.

## Lima pilar teori — prinsip terapan
(Bukan sekadar "mengapa", tapi cara menerapkannya saat menyusun modul & soal.)

### 1. Willis — Task-Based Language Learning (TBLT)
- Siklus tugas: pra-tugas → TUGAS komunikatif → laporan/refleksi → fokus bahasa.
  Grammar SELALU setelah tugas (dasar alur enam tahap & scene-first).
- Inti tiap modul adalah tugas nyata (Tahap 4 溝通任務), bukan latihan bentuk.
- Bahasa dipelajari lewat pemakaian bermakna, bukan drill struktur lebih dulu.

### 2. Mayer — Multimedia Learning (desain audio/visual)
- Dual-coding: pasangkan kata dengan gambar/audio relevan (Tahap 2 情境對話 & Tahap 3 詞彙).
- Coherence: buang elemen dekoratif yang tak menunjang makna — visual mendukung adegan, bukan menghias.
- Signaling: soroti kata & pola kunci yang jadi fokus.
- Redundancy & Modality: jangan tumpuk audio + teks identik; untuk 聽力 utamakan
  audio + visual, bukan audio + transkrip penuh (menjawab kesulitan "kecepatan
  audio" & "mengingat kosakata" dari analisis kebutuhan).
- Segmenting: pecah input jadi potongan kecil (selaras Sweller).
- PROPORSI: multimedia MELAYANI latihan soal & strategi ujian, bukan sebaliknya
  (lihat "Prioritas audiens") — koreksi setelah rekomendasi visual sempat terlalu dominan.

### 3. Sweller — Cognitive Load Theory (CLT)
- Batasi beban: maksimal ~10 kata inti + ~2 poin grammar per modul.
- Grammar "balok Lego": dirakit dari potongan kecil yang sudah dikuasai.
- Dua lapis kosakata 核心/補充 mencegah overload; 新詞量 dipakai sebagai metrik terukur.
- Segmenting input & spiral recurrence membantu menjaga beban tetap rendah.

### 4. Bachman & Palmer — Language Testing
- Autentisitas: tugas & soal meniru format serta situasi TOCFL Band A yang nyata.
- Fidelitas level: input dikunci ke daftar kata TBCL level itu — tidak bocor ke level lain.
- Konstruk sahih: yang diuji benar-benar kemampuan yang dimaksud (acuan saat mendesain soal).

### 5. Zimmerman — Self-Regulated Learning (SRL)
- Tiga fase: penetapan tujuan (Tahap 1 情境導入) → pelaksanaan → refleksi diri (Tahap 6 反思與進度).
- Bangun fitur pelacakan kemajuan & umpan balik reflektif ke dalam modul.
- Frekuensi checkpoint SRL menjadi dasar granularitas & jumlah modul.

## ⚠️ Ketegangan yang BELUM diselesaikan (jangan diputuskan sepihak — tanyakan ke Carli)
- 17 kategori situasional (dari pemetaan) vs 12 tema (dari desain modul) — perlu rekonsiliasi.
- Jumlah modul sengaja dibiarkan belum final — ditentukan setelah desain modul rampung.
