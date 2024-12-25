1. Crypto.Cipher.py
   Nama Tugas: DES Encryption Simulation
   Deskripsi: Program simulasi enkripsi dan dekripsi menggunakan algoritma DES sederhana untuk edukasi. Data dienkripsi dengan membalik urutan byte dalam blok 8 byte, bukan implementasi DES asli.
   Cara Menjalankan:
      1. Buat objek DES dengan kunci 8 byte:  
         python
         des = DES(b'12345678')
      2. Siapkan data byte yang panjangnya kelipatan 8:  
         python
         data = b'abcdefgh'
      3. Enkripsi data:  
         python
         encrypted = des.encrypt(data)
      4. Dekripsi data:  
         python
         decrypted = des.decrypt(encrypted)
         
2. des_gui_app.py
   Nama Tugas: DES Encryption and Decryption Tool
   Deskripsi: Aplikasi GUI untuk mengenkripsi dan mendekripsi teks menggunakan algoritma DES dengan kunci 8 karakter.
   Cara Menjalankan: 
      1. Instal pustaka pycryptodome:  
         pip install pycryptodome
      2. Jalankan aplikasi:  
         python des_tool.py
      3. Masukkan teks di kolom Plain Text dan kunci 8 karakter di kolom Key.  
      4. Klik Encrypt untuk mengenkripsi teks (hasil di Encrypted Text) atau Decrypt untuk mendekripsi teks (hasil di Decrypted Text).

3. enigma.py
   Nama Tugas: Enigma Cipher Simulator
   Deskripsi: Aplikasi Python berbasis GUI untuk mengenkripsi dan mendekripsi teks menggunakan simulasi mesin Enigma dengan tiga rotor yang dapat diatur.
   Cara Menjalankan: 
      1. Jalankan file Python: python enigma_cipher.py.  
      2. Masukkan teks pada kolom Input Text.  
      3. Atur posisi rotor (default: 0).  
      4. Klik tombol Encrypt untuk menghasilkan teks terenkripsi di kolom Output Text.  
      5. Untuk dekripsi, gunakan teks terenkripsi sebagai input dan atur rotor ke posisi awal yang sama.

4. steganography_tool.py
   Nama Tugas: Steganography Tool
   Deskripsi: Aplikasi Python berbasis GUI (Tkinter) untuk menyisipkan (encode) pesan teks ke dalam gambar dan mengekstraknya (decode) menggunakan teknik steganografi.
   Cara Menjalankan: 
      1. Persiapan:  
         - Instal Python dan pustaka Pillow (pip install pillow).  
         - Jalankan file Python: python steganography_tool.py.  
      2. Fungsi Utama:  
         - Encode Message: Menyisipkan pesan teks ke dalam gambar dan menyimpan gambar baru.  
         - Decode Message: Membaca pesan tersembunyi dari gambar.  
      3. Penggunaan:  
         - Masukkan pesan di kolom teks untuk encode.  
         - Pilih gambar sumber untuk encode/decode.  
         - Klik tombol sesuai kebutuhan (Encode/Decode).  
      4. Keluar: Klik tombol Exit.
