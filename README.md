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
![Screenshot 2024-12-07 111446](https://github.com/user-attachments/assets/f65a1ac8-84e2-491b-ab90-d9e9c4af007b)

# Diagram Class
![Screenshot 2024-12-08 080008](https://github.com/user-attachments/assets/b28d1629-982a-4b90-8465-1d6e63aa7a3f)

- Nama Class : Mahasiswa
- Atribut : -daftar_mahasiswa (Tanda minus (-) menunjukkan bahwa atribut bersifat private (hanya dapat diakses dari dalam kelas).
- Metode :
- init(): konstruktor kelas yang dipanggil saat kita membuat instance baru dari kelas Mahasiswa. Metode ini menginisialisasi atribut daftar_mahasiswa sebagai list kosong.
- tambah(nama: str, nilai: int): untuk menambahkan data mahasiswa baru ke dalam daftar_mahasiswa. Ia menerima dua parameter: nama (tipe string) dan nilai (tipe integer). Setelah menambahkan data, metode ini juga memberikan konfirmasi bahwa data telah berhasil ditambahkan.
- tampilkan(): untuk menampilkan semua data mahasiswa yang ada dalam daftar_mahasiswa. Jika daftar kosong, metode ini akan mencetak pesan bahwa daftar mahasiswa kosong. Jika ada data, ia akan mencetak nama dan nilai setiap mahasiswa.
- hapus(nama: str): untuk menghapus data mahasiswa berdasarkan nama. Ia mencari mahasiswa dengan nama yang diberikan, dan jika ditemukan, data tersebut dihapus dari daftar_mahasiswa. Jika tidak ditemukan, metode ini akan mencetak pesan bahwa data mahasiswa tidak ditemukan.
- ubah(nama: str, nilai_baru: int): untuk mengubah nilai mahasiswa berdasarkan nama. Ia mencari mahasiswa dengan nama yang diberikan, dan jika ditemukan, nilai mahasiswa tersebut diubah menjadi nilai_baru. Jika tidak ditemukan, metode ini akan mencetak pesan bahwa data mahasiswa tidak ditemukan.

# Flowchart
![Screenshot 2024-12-08 075619](https://github.com/user-attachments/assets/1b988e03-7762-4b2c-aa60-3d9e2791d286)

