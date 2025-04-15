### Deskripsi Game: Petualangan Mahasiswa

*Judul*: Petualangan Mahasiswa  
*Genre*: Petualangan Interaktif / Visual Novel  
*Platform*: Android (menggunakan Godot)

#### Sinopsis
"Petualangan Mahasiswa" adalah game petualangan interaktif yang mengajak pemain untuk merasakan kehidupan seorang mahasiswa bernama Someone. Pemain akan menjelajahi kampus, berinteraksi dengan berbagai karakter, dan membuat pilihan yang akan memengaruhi hubungan Someone dengan perempuan idamannya. Setiap keputusan yang diambil akan membawa konsekuensi yang dapat mengubah jalannya cerita.

---

### Fitur Utama

1. *Interaksi Karakter*:
   - Pemain dapat berbicara dengan NPC dan perempuan idaman, memilih dialog yang memengaruhi hubungan.

2. *Sistem Hubungan*:
   - Hubungan dengan karakter ditentukan oleh pilihan dialog, yang dapat meningkat atau menurun.

3. *Akhir Cerita Beragam*:
   - Beberapa ending berdasarkan hubungan dan keputusan yang diambil, memberikan replayability.

4. *Antarmuka Pengguna Responsif*:
   - Desain UI yang intuitif dan mudah digunakan, cocok untuk perangkat mobile.

5. *Grafik Menarik*:
   - Gaya visual yang menggambarkan kehidupan kampus dengan ilustrasi karakter dan latar belakang yang menarik.

6. *Misi dan Tantangan*:
   - Pemain dapat menyelesaikan misi kecil yang memperkaya pengalaman bermain.

### Struktur Proyek

#### 1. *Folder Struktur Proyek*
   - *Assets/*: Menyimpan semua aset grafis, audio, dan data.
     - *Images/*: Gambar karakter dan latar belakang.
     - *Audio/*: Musik latar dan efek suara.
     - *Fonts/*: Font yang digunakan dalam UI.
   - *Scripts/*: Menyimpan semua skrip C#.
     - *Character.cs*: Skrip untuk logika karakter dan interaksi.
     - *GameManager.cs*: Skrip untuk mengelola alur permainan dan interaksi.
   - *Scenes/*: Menyimpan semua scene game.
     - *MainMenu.tscn*: Scene untuk menu utama.
     - *GameScene.tscn*: Scene untuk gameplay utama.
   - *UI/*: Menyimpan semua elemen UI.
     - *Buttons/*: Sumber daya untuk tombol.
     - *Labels/*: Sumber daya untuk label dialog.
