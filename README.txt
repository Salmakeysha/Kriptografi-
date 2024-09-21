Pendahuluan

`cipherApp.py` adalah sebuah alat enkripsi dan dekripsi berbasis GUI (antarmuka grafis) yang mengimplementasikan tiga jenis cipher: Vigenere Cipher, Playfair Cipher, dan Hill Cipher. Program ini memungkinkan pengguna untuk memasukkan teks, baik melalui input dari keyboard atau mengunggah file, dan mengenkripsi atau mendekripsi teks tersebut menggunakan kunci minimal 12 karakter.

Persyaratan

Untuk menjalankan program ini, pastikan hal-hal berikut sudah terpasang:
- Python 3.x
- Pustaka `tkinter` (biasanya sudah termasuk dalam distribusi standar Python)

Cara Menjalankan Program

1. Install Python:
   Pastikan Python sudah terpasang di komputer Anda. Anda bisa mengunduhnya dari [python.org](https://www.python.org/).

2. Buka Terminal atau Command Prompt:
   Arahkan ke direktori tempat file `cipherApp.py` disimpan menggunakan perintah `cd`.

3. Jalankan Program:
   Gunakan perintah berikut untuk menjalankan program:
   python cipherApp.py

4. Menggunakan GUI:
   - Input: Anda bisa mengetik pesan langsung ke dalam area teks yang disediakan atau mengunggah file `.txt` yang berisi teks.
   - Kunci: Masukkan kunci yang panjangnya minimal 12 karakter untuk melakukan enkripsi dan dekripsi.
   - Enkripsi/Dekripsi: Setelah memasukkan teks dan kunci, pilih tombol yang sesuai untuk mengenkripsi atau mendekripsi teks.

5. Menyimpan Hasil:
   Program ini menyediakan opsi untuk menyimpan hasil enkripsi atau dekripsi ke dalam file `.txt` setelah pemrosesan selesai.

Fitur

- Input Teks: Mendukung input manual melalui keyboard atau dengan mengunggah file `.txt`.
- Input Kunci: Kunci harus memiliki panjang minimal 12 karakter.
- Cipher yang Didukung:
  - Vigenere Cipher
  - Playfair Cipher
  - Hill Cipher
- Simpan Hasil: Setelah pemrosesan, hasil enkripsi atau dekripsi dapat disimpan sebagai file teks.

Catatan

- Program ini harus dijalankan pada komputer yang mendukung lingkungan grafis karena menggunakan GUI berbasis Tkinter.
- Pastikan panjang kunci sesuai dengan cipher yang dipilih.