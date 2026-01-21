🏥 Si Penolong Cilik - Web Edukasi P3K Anak

Si Penolong Cilik adalah aplikasi web edukatif berbasis gamifikasi yang dirancang untuk mengajarkan anak-anak (khususnya anak dengan disabilitas intelektual ringan) tentang cara merawat luka ringan secara mandiri.

Aplikasi ini menggunakan pendekatan visual, audio interaktif, dan simulasi motorik halus (drag & drop) untuk memaksimalkan pemahaman.

✨ Fitur Utama

Avatar Pendamping Cerdas (Beruang):

Memberikan instruksi suara (Text-to-Speech) dan teks.

Ekspresi wajah berubah sesuai konteks (Senang/Sedih).

Bisa disembunyikan/dimunculkan dengan tombol panah agar tidak menutupi layar.

4 Level Pembelajaran Bertahap:

Level 1 (Inquiry): Memilih alat P3K yang benar (Kasa, Plester, Obat, Air).

Level 2 (Inquiry): Mengurutkan langkah perawatan luka dengan benar.

Level 3 (Questioning): Kuis pemahaman sederhana.

Level 4 (Constructivism): Simulasi praktik mengobati karakter (Animasi Luka Berubah).

Sistem Reward & Monitoring:

Victory Popup: Muncul piala dan sorakan "Hore!" setiap level selesai.

Monitoring Bar: Guru/Orang tua bisa memantau Skor dan Progres Level secara real-time di bagian atas layar.

Audio & Efek Suara:

Narasi otomatis (Suara Google Bahasa Indonesia).

Efek suara (SFX) untuk jawaban benar, salah, klik, dan kemenangan.

📂 Struktur Folder (Wajib)

Agar aplikasi berjalan lancar, pastikan susunan file di komputer Anda seperti ini:

📁 Si_Penolong_Cilik/
│
├── 📄 index.html           <-- File Kode Utama (Aplikasi)
├── 📄 README.md            <-- File Dokumentasi ini
│
├── 📁 img/                 <-- FOLDER GAMBAR (Wajib ada)
│   ├── beruang.png
│   ├── alat_air.png
│   ├── alat_betadine.png
│   ├── alat_kasa.png
│   ├── alat_plester.png
│   ├── alat_tisu.png
│   ├── alat_permen.png
│   ├── alat_mainan.png
│   ├── langkah_cuci.png
│   ├── langkah_air.png
│   ├── langkah_kering.png
│   ├── langkah_obat.png
│   ├── langkah_tutup.png
│   ├── karakter_luka_kotor.png
│   ├── karakter_luka_bersih.png
│   ├── karakter_luka_kering.png
│   ├── karakter_luka_obat.png
│   └── karakter_luka_tutup.png
│
└── 📁 audio/               <-- FOLDER SUARA (Opsional tapi disarankan)
    ├── correct.mp3
    ├── wrong.mp3
    ├── victory.mp3
    └── click.mp3


PENTING: Nama file gambar harus sama persis (huruf kecil semua, format .png) agar terbaca oleh kode.

🚀 Cara Menjalankan

Cara 1: Offline (Di Laptop/Komputer)

Pastikan semua file gambar dan audio sudah dimasukkan ke folder masing-masing.

Klik kanan file index.html.

Pilih Open with > Google Chrome (atau browser lain).

Aplikasi siap dimainkan!

Cara 2: Online (Tanpa Install)

Buka situs Netlify Drop.

Tarik (Drag & Drop) folder proyek Si_Penolong_Cilik ke area upload.

Tunggu sebentar, link website akan muncul dan bisa dibagikan ke siapa saja.

🛠️ Teknologi yang Digunakan

HTML5 & CSS3: Struktur dan tampilan antarmuka.

JavaScript (Vanilla JS): Logika permainan, drag & drop, dan manajemen state.

Tailwind CSS (CDN): Framework CSS untuk desain responsif yang cepat.

Lucide Icons: Ikon vektor ringan.

Web Speech API: Teknologi bawaan browser untuk suara narator otomatis.

📝 Catatan Pengembang

Ukuran Gambar: Disarankan menggunakan gambar dengan rasio 1:1 (kotak) dan latar belakang transparan (PNG) untuk hasil terbaik.

Suara: Pastikan volume perangkat aktif untuk mendengar instruksi narator.

Dibuat oleh: Tiara Sinta Aulia
Untuk: Skripsi Pendidikan Luar Biasa