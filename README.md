# CHEM-ESCAPE
Thalen, siswa kelas 9 SMPN 1 Dhailton, sedang melakukan eksperimen di laboratorium kimia. Ia begitu fokus hingga tak sadar hari mulai gelap dan sistem otomatis mengunci pintu. Terjebak sendirian, ia sempat panik, namun memutuskan memanfaatkan bahan yang ada untuk meracik ramuan yang mungkin bisa membantunya keluar

# Konsep Game
Chem Escape merupakan permainan edukatif berbasis teka-teki yang menggabungkan unsur pembelajaran kimia dengan eksplorasi dan pemecahan masalah. Pemain ditantang untuk berpikir logis serta memanfaatkan informasi dari lingkungan untuk menyelesaikan misi utama.

# Genre
Game ini mengusung genre Puzzle Edukatif, yaitu permainan yang tidak hanya memberi pengalaman bermain, tetapi juga mendorong proses belajar melalui interaksi dan tantangan yang diberikan.

# Target Audience
Chem Escape ditujukan untuk siswa SMP/MTs atau sederajat yang sedang mempelajari materi dasar kimia, sehingga game ini dapat berfungsi sebagai media pendukung pembelajaran yang menyenangkan dan interaktif.

# Platform
Permainan ini dirancang untuk dimainkan melalui Windows, sehingga dapat diakses melalui komputer atau laptop, baik di sekolah maupun di rumah.

# Core Mechanics
Chem Escape memiliki beberapa mekanik inti yang membentuk alur gameplay, yaitu:
- Movement: Pemain dapat bergerak bebas di dalam laboratorium untuk mencari petunjuk.
- Interaction: Pemain dapat mengklik objek untuk berinteraksi seperti membuka laci, membaca catatan, atau mengambil item.
- Inspect/Evidence Reading: Pemain membaca catatan dan informasi penting sebagai referensi pemecahan puzzle.
- Item Identification: Pemain memilih bahan kimia yang benar atau salah sesuai petunjuk yang ditemukan.
- Verification/Result Mechanic: Sistem akan menilai apakah pilihan pemain tepat dan memberikan kunci jika berhasil.
- Unlocking Door: Kunci digunakan untuk membuka pintu laboratorium dan menyelesaikan permainan.

# Objective
Tujuan utama pemain adalah menyusun ramuan secara benar berdasarkan petunjuk untuk mendapatkan kunci keluar dari laboratorium dan menyelesaikan level permainan.

# Story
Cerita Chem Escape bermula ketika Thalen, siswa kelas 9 SMPN 1 Dhailton, sedang melakukan eksperimen kimia setelah jam pelajaran berakhir. Terlalu fokus, ia tidak menyadari bahwa sistem otomatis telah mengunci pintu laboratorium. Saat menyadari dirinya terjebak, ia harus berpikir cepat dan menggunakan pengetahuan kimia serta petunjuk di sekitarnya untuk membuat formula khusus yang menjadi kunci keluar. Dari sini, perjalanan teka-teki dimulai.

# Visual Style
Game ini menggunakan gaya visual Low Poly, memberikan tampilan sederhana namun modern, serta mudah diterima oleh pemain muda.

# Audio Direction
- Backsound Laboratorium
Menghadirkan atmosfer sunyi dan menegangkan dengan suara tetesan air, gas berdesis, jam berdetak, dan cairan mendidih dalam tabung kaca.
- Audio Karakter
Terdapat suara langkah kaki pemain untuk memberikan kesan interaksi nyata dengan lingkungan.
- Audio User Interface
Termasuk suara klik tombol, efek pop-up informasi, dan suara indikator benar atau salah saat menjawab puzzle.

# Technical Design Document
Arsitektur Sistem & Design Pattern
- State Pattern
Mengatur alur antar fase permainan seperti Opening, Pencarian Petunjuk, Puzzle, Final Experiment, hingga Ending.
- Singleton Pattern
Digunakan pada sistem yang hanya membutuhkan satu instance seperti GameManager, InventoryManager, ScoreManager, dan AudioManager.
- Observer Pattern
Menghubungkan event dalam game seperti perubahan skor, update UI, penambahan item, dan validasi puzzle.

# Struktur Folder Proyek
- Assets
- Scripts (Player, Item, UI)
- Prefabs
- Scenes (Menu, Puzzle, Dialog)
- Audio
- Materials
- User Interface
