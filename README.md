Nama: ZAENAL MAULANA RIZKI

Kelas: TI.24.A4

NIM: 312410332

Mata Kuliah: Bahasa Pemrograman

# Latihan OOP

![Screenshot 2024-12-10 075305](https://github.com/user-attachments/assets/7d41020c-5737-489f-9e13-c719982b6d51)

# Penjelasan Code

# data -> mahasiswa.py

Mahasiswa: Class yang mewakili entitas mahasiswa. Memiliki atribut: `nim, nama, dan jurusan`. 

Fungsi utama:
`tambah_mahasiswa(nim, nama, jurusan)`: Menambah data mahasiswa baru.

`hapus_mahasiswa(nim)`: Menghapus mahasiswa berdasarkan NIM.

`ubah_mahasiswa(nim, nama_baru, jurusan)`: Memperbarui data mahasiswa tertentu.

`cari_mahasiswa(nim)`: Mencari mahasiswa berdasarkan NIM.

`semua_mahasiswa()`: Mengembalikan seluruh data mahasiswa.

# view -> input_form.py

Berisi class InputForm untuk menangani input dari pengguna.

`input_mahasiswa()`: Fungsi untuk meminta pengguna memasukkan data mahasiswa berupa NIM, Nama, dan Jurusan.

# view/mahasiswa.py

Berisi class `ViewMahasiswa` untuk menampilkan data mahasiswa ke layar.

Fungsi utama:

`tampilkan_semua_mahasiswa(data)`: Menampilkan semua data mahasiswa dalam bentuk daftar.

`tampilkan_mahasiswa(mahasiswa)`: Menampilkan detail satu mahasiswa tertentu.

# main.py

File utama program yang berisi menu untuk berinteraksi dengan pengguna.

Cara kerjanya:

- Tampilkan menu pilihan kepada pengguna.
- Pengguna memasukkan opsi, seperti:

1. `Tambah mahasiswa`: Memasukkan NIM, Nama, dan Jurusan untuk disimpan.

2. `Lihat semua mahasiswa`: Menampilkan seluruh data mahasiswa yang sudah tersimpan.

3. `Cari mahasiswa`: Mencari mahasiswa berdasarkan NIM.

4. `Ubah mahasiswa`: Memperbarui data mahasiswa tertentu.

5. `Hapus mahasiswa`: Menghapus data mahasiswa berdasarkan NIM.

6. `Keluar`: Mengakhiri program.

- Setiap pilihan akan memanggil fungsi yang relevan dari modul di folder `data` atau `view`.

Code Program Tersebut:

![code](https://github.com/user-attachments/assets/2632d576-ccd1-488c-bb42-ee5578fbbb46)

Hasil Program Tersebut:

![Screenshot (102)](https://github.com/user-attachments/assets/f2228316-0e9f-492d-a29d-232773c7dcac)
