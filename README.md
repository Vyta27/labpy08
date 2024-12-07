# Praktikum 8
Buat program sederhana dengan mengaplikasikan penggunaan class. Buatlah class untuk menampilkan daftar nilai mahasiswa, dengan ketentuan:

• Method tambah() untuk menambah data

• Method tampilkan() untuk menampilkan data

• Method hapus(nama) untuk menghapus data berdasarkan nama

• Method ubah(nama) untuk mengubah data berdasarkan nama

![Screenshot 2024-12-07 111224](https://github.com/user-attachments/assets/7197fce8-5ad7-47c5-b8bc-4a334650e943)
![Screenshot 2024-12-07 111303](https://github.com/user-attachments/assets/904510ea-082c-4da1-b223-531323570a0d)

Class mahasiswa
1. Metode __init__
- Metode ini adalah konstruktor yang dipanggil saat objek dari kelas Mahasiswa dibuat.
- Di sini, kita menginisialisasi atribut daftar_mahasiswa sebagai list kosong yang akan digunakan untuk menyimpan data mahasiswa.
2. Menambahkan Data Mahasiswa (tambah method):
- Metode ini menerima dua parameter: nama dan nilai. Data mahasiswa baru ditambahkan ke dalam daftar_mahasiswa dalam bentuk dictionary yang berisi nama dan nilai.
- Setelah menambahkan, metode ini mencetak pesan konfirmasi.
3. Menampilkan Data Mahasiswa (tampilkan method):
- Metode ini menampilkan semua data mahasiswa yang ada dalam daftar_mahasiswa.
- Jika daftar kosong, akan mencetak pesan bahwa daftar mahasiswa kosong.
- Jika ada data, akan mencetak nama dan nilai setiap mahasiswa.
4. Menghapus Data Mahasiswa (hapus method):
- Metode ini mencari mahasiswa berdasarkan nama. Jika ditemukan, data mahasiswa tersebut dihapus dari daftar_mahasiswa dan mencetak pesan konfirmasi.
- Jika tidak ditemukan, akan mencetak pesan bahwa data mahasiswa tidak ditemukan.
5. Mengubah Data Mahasiswa (ubah method):
- Metode ini juga mencari mahasiswa berdasarkan nama. Jika ditemukan, nilai mahasiswa tersebut diubah menjadi nilai_baru dan mencetak pesan konfirmasi.
- Jika tidak ditemukan, akan mencetak pesan bahwa data mahasiswa tidak ditemukan.

# Run
