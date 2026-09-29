# 🛡️ Protokol Etika Riset & Formulir Informed Consent
*Pedoman Perlindungan Privasi Data Medis, Persetujuan Informan Bebas Paksaan, & Mitigasi Risiko Lapangan*  
*Startup Geny StuntCare — Inkubasi Bisnis Startup BTP Batch 24 Telkom University*

---

## 📌 Landasan Etika Penelitian Lapangan

Dalam melakukan validasi masalah (*Customer Discovery*) terkait kesehatan ibu dan anak, tim **Geny StuntCare** berinteraksi dengan kelompok rentan (*vulnerable groups*): ibu hamil, ibu balita berstatus ekonomi rendah, calon pengantin, dan kader posyandu. Oleh karena itu, seluruh aktivitas wawancara dan observasi lapangan wajib tunduk pada standar etika penelitian kesehatan dan kepatuhan hukum nasional:

1. **Undang-Undang No. 27 Tahun 2022 tentang Pelindungan Data Pribadi (UU PDP)**: Data kesehatan anak, riwayat kehamilan, data antropometri, dan kondisi ekonomi keluarga dikategorikan sebagai **Data Pribadi yang Bersifat Spesifik** yang wajib dilindungi kerahasiaannya dengan enkripsi dan hak privasi penuh.
2. **Deklarasi Helsinki (Etika Penelitian Melibatkan Manusia)**: Mengutamakan keselamatan, kesejahteraan psikologis, dan hak asasi subjek di atas kepentingan riset teknologi.
3. **Prinsip *Do No Harm* (Nir-Bahaya & Nir-Stigma)**: Peneliti dilarang memberikan vonis medis, menghakimi pola asuh, atau melabeli anak narasumber dengan kata "stunting" yang dapat menimbulkan trauma psikologis atau sanksi sosial di lingkungan warga.

---

## 🗣️ 1. Skrip Pembuka Lisan Pewawancara (Verbal Consent Script)

*Bacakan teks berikut secara ramah, santai, dan bersahabat sebelum memulai pertanyaan:*

> *"Selamat pagi/siang Ibu/Bapak/Mbak. Terima kasih banyak sudah meluangkan waktu untuk mengobrol santai bersama kami hari ini.*  
>  
> *Perkenalkan, saya **[Nama Pewawancara]** dan rekan saya **[Nama Notulis]** dari tim peneliti **Geny StuntCare - Telkom University & Bandung Techno Park**.  
>  
> *Maksud kedatangan kami hari ini adalah untuk **belajar dan mendengarkan pengalaman Ibu/Bapak** seputar bagaimana sehari-hari merawat kesehatan keluarga, memeriksa kehamilan, atau mengasuh tumbuh kembang si kecil. Kami **bukan sedang melakukan penilaian, bukan sedang menguji, dan sama sekali tidak sedang berjualan produk apa pun**.*  
>  
> *Seluruh obrolan kita hari ini bersifat **sangat rahasia dan anonim**. Nama asli Ibu/Bapak tidak akan pernah kami sebutkan dalam laporan, melainkan hanya akan diganti menggunakan kode rahasia. Ibu/Bapak berhak untuk tidak menjawab pertanyaan yang dirasa kurang nyaman, dan berhak menghentikan obrolan ini kapan saja tanpa ada konsekuensi apa pun.*  
>  
> *Agar kami tidak salah mencatat cerita berharga dari Ibu/Bapak, apakah kami diizinkan untuk **merekam suara obrolan ini hanya untuk keperluan dokumentasi internal tim riset kami**? Apakah Ibu/Bapak bersedia dan setuju untuk berbincang bersama kami sekitar 35 menit ke depan?"*

---

## 📋 2. Formulir Lembar Persetujuan Tertulis (Written Consent Form)

*Gunakan lembar ini jika wawancara dilakukan secara formal di balai desa, puskesmas, atau kegiatan posyandu:*

```
                 LEMBAR PERSETUJUAN PARTISIPASI RISET (INFORMED CONSENT)
                       PROGRAM INKUBASI STARTUP BTP BATCH 24

Saya yang bertanda tangan di bawah ini:
Nama Lengkap (Boleh Inisial) : ................................................................
Usia                         : ............ Tahun
Alamat / Wilayah             : Kel/Desa ........................... Kec .......................
                               Kabupaten/Kota .................................................

Menyatakan bahwa:
1. Saya telah menerima penjelasan lengkap mengenai maksud, tujuan, dan prosedur wawancara customer discovery yang dilaksanakan oleh Tim Riset Geny StuntCare - Bandung Techno Park & Telkom University.
2. Saya memahami bahwa keikutsertaan saya bersifat SUKARELA tanpa paksaan, dan saya berhak mengundurkan diri atau menolak menjawab pertanyaan tertentu sewaktu-waktu.
3. Saya menyetujui bahwa informasi yang saya berikan akan dianonimkan (disamarkan identitasnya) dan hanya dipergunakan untuk keperluan riset pengembangan platform kesehatan masyarakat serta pelaporan ilmiah inkubasi.
4. Saya [ MENYETUJUI / TIDAK MENYETUJUI ] perekaman audio selama proses wawancara berlangsung semata-mata untuk akurasi pencatatan data tim peneliti.

Demikian pernyataan persetujuan ini saya buat secara sadar dan sukarela tanpa ada tekanan dari pihak mana pun.

                                                   ......................, ..................... 2026

Pewawancara (Saksi),                               Partisipan (Narasumber),



(..........................................)       (..........................................)
```

---

## 🔒 3. Protokol Anonimisasi & Keamanan Data (UU PDP)

Untuk menjamin kepatuhan penuh terhadap UU Perlindungan Data Pribadi:

1. **Sistem Pengkodean Alfanumerik Unik**:
   * Nama asli subjek segera dienkripsi dan digantikan dengan kode alfanumerik:
     * `IB-[Nomor]` : Ibu Balita (Contoh: `IB-01`, `IB-02`)
     * `IH-[Nomor]` : Ibu Hamil (Contoh: `IH-01`, `IH-02`)
     * `CT-[Nomor]` : Calon Pengantin (Contoh: `CT-01`, `CT-02`)
     * `NK-[Nomor]` : Tenaga Kesehatan / Kader Posyandu (Contoh: `NK-01`, `NK-02`)
     * `ST-[Nomor]` : Stakeholder Desa / Puskesmas (Contoh: `ST-01`, `ST-02`)
2. **Pemisahan Kunci Identitas (*Identity Key Decoupling*)**:
   * Tabel pemetaan antara Nama Asli, NIK, Nomor HP dengan Kode Unik disimpan dalam file terpisah yang terenkripsi password dan hanya dapat diakses oleh *Principal Investigator* (Gerrard Sebastian).
   * Seluruh dokumen publikasi, transkrip markdown di repositori GitHub, notulensi workshop, dan pitch deck HANYA memuat kode unik informan.
3. **Penyimpanan Rekaman Suara**:
   * File rekaman audio (.m4a / .mp3) disimpan dalam media penyimpanan awan terenkripsi tim riset (*Google Drive Enterprise Telkom University*). Dilarang mengunggah rekaman suara mentah ke repositori publik.
   * File rekaman suara akan dimusnahkan secara permanen setelah laporan akhir tahapan inkubasi BTP Batch 24 disetujui.

---

## 🚨 4. Prosedur Operasional Standar (SOP) Mitigasi Situasi Kritis Lapangan

Saat melakukan wawancara lapangan, peneliti dapat menemui situasi psikologis atau kondisi darurat medis. Terapkan protokol berikut:

### Skenario 1: Informan Menangis atau Mengalami Tekanan Emosional
* *Pemicu*: Menceritakan beban ekonomi, anak sakit menahun, atau kekerasan verbal dari keluarga/mertua.
* *Tindakan Peneliti*:
  1. **Segera Hentikan Perekaman Audio**: Berikan jeda waktu dan tawarkan segelas air minum atau tisu.
  2. **Validasi Perasaan Subjek Tanpa Menghakimi**: Ucapkan kalimat empatik: *"Ibu, kami sangat memahami ini masa-masa yang berat. Terima kasih sudah begitu kuat dan mau berbagi rasa dengan kami."*
  3. **Tawarkan Pilihan Melanjutkan**: Jangan memaksa melanjutkan pertanyaan. Tanyakan apakah informan ingin istirahat sejenak, mengakhiri sesi, atau berganti topik yang lebih ringan.

### Skenario 2: Ditemukan Balita Gizi Buruk Akut (*Severe Acute Malnutrition*)
* *Pemicu*: Saat kunjungan rumah ditemukan anak dengan tanda klinis kurus kering ekstrim (*wasting*), edema bengkak kedua kaki, atau lesu tidak berdaya.
* *Tindakan Peneliti*:
  1. Peneliti dilarang memberikan intervensi obat atau mendiagnosis sendiri.
  2. Setelah wawancara selesai, peneliti wajib berkoordinasi secara rahasia dan santun dengan **Bidan Desa atau Kader Posyandu setempat** untuk memfasilitasi rujukan darurat ke Puskesmas terdekat (*Tata Laksana Gizi Buruk Kemenkes*).

### Skenario 3: Penolakan atau Kecurigaan Warga / Tokoh Masyarakat
* *Pemicu*: Tetangga atau anggota keluarga curiga peneliti adalah petugas survei bansos atau oknum penipu.
* *Tindakan Peneliti*:
  1. Tunjukkan kartu identitas resmi mahasiswa Telkom University dan Surat Tugas Inkubasi Startup Bandung Techno Park.
  2. Jelaskan kembali dengan bahasa daerah yang santun bahwa kegiatan ini murni riset akademik untuk membantu kemajuan posyandu desa setempat.

---

*Disusun untuk menjamin kepatuhan etik penelitian startup Geny StuntCare — Bandung Techno Park Batch 24.*
