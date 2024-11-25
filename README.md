seluruh coding awal
![ss1 kodingnya crop dewek](https://github.com/user-attachments/assets/6dc9b397-d877-42c2-8f7e-ef27c725bab1)

===================================================================================
1. membuat tampilan awal web dan Membuat Judul Halaman
kodingnya
![ss1 kodingnya membuat tampilan awal web](https://github.com/user-attachments/assets/f2aad5ca-e35d-489a-af6c-8fde077147eb)
- <!DOCTYPE html>: Menentukan dokumen sebagai HTML5.
- <html lang="id">: Mendefinisikan bahasa utama dokumen sebagai bahasa Indonesia (id).
- <meta charset="UTF-8">: Menentukan karakter encoding agar mendukung karakter internasional (termasuk huruf dengan tanda diakritik seperti é).
- <meta name="viewport" content="width=device-width, initial-scale=1.0">: Mengatur responsif agar tampilan dapat menyesuaikan layar perangkat.
- <title>Form Input Data</title>: Menampilkan judul di tab browser. Anda akan melihat tulisan "Form Input Data" di tab browser.
- <h2>: Digunakan untuk menampilkan teks sebagai judul besar (heading) pada halaman.
hasilnya
![ss1 kodingnya membuat tampilan awal web hasilnya](https://github.com/user-attachments/assets/a03fbc71-7663-466a-b9a1-fbf89a2e9db7)


2. membuat Input Nama
![ss1 kodingnya Input Nama](https://github.com/user-attachments/assets/bf6fd3b9-3693-4dc2-866c-23e68997fb73)
- <label for="nama">Nama:</label>: Label untuk input nama dengan teks "Nama:". Atribut for="nama" menghubungkan label ke input dengan id="nama".
- <input type="text" id="nama" name="nama" required>: Membuat input teks untuk nama. Atribut required memastikan pengguna wajib mengisi.
hasilnya
![ss1 kodingnya Input Nama hasilnya](https://github.com/user-attachments/assets/6d344602-ca3e-439e-bfcf-d7d01704bfdd)


3. membuat tanggal lahir dan Membuat Form Input
![ss1 kodingnya Input Tanggal Lahir](https://github.com/user-attachments/assets/e6e08098-3bdc-453c-ab85-2b93aeb0aaee)
- <input type="date">: Membuat input untuk tanggal dengan format kalender
- <form>: Membuat form untuk menerima input dari pengguna.
- action="": Menentukan lokasi file PHP untuk memproses data. Kosong berarti data akan dikirim ke file yang sama.
- method="POST": Data dikirim menggunakan metode POST, yang lebih aman dibandingkan GET karena tidak menampilkan data di URL.
hasilnya
![ss1 kodingnya Input Tanggal Lahir hasilnya](https://github.com/user-attachments/assets/0337cc8d-a26d-4f02-ad4e-162898ff17a0)


4. memilih pekerjaan
![ss1 kodingnya memilih pekerjaan](https://github.com/user-attachments/assets/41589aa1-70ab-40a1-8a89-d779669cec4d)
- <select>: Membuat dropdown untuk pilihan pekerjaan.
- <option>: Pilihan yang dapat dipilih pengguna.
hasilnya
![ss1 kodingnya memilih pekerjaan hasilnya](https://github.com/user-attachments/assets/184c8612-9a11-46cf-b9b7-eb87f6d707dd)


5. membuat tombol sumbit
![ss1 kodingnya membuat tombol sumbit](https://github.com/user-attachments/assets/1cc04f84-ff78-4e15-90f8-95ad2114a6cd)
- <input type="submit">: Tombol untuk mengirimkan form.
hasilnya
![ss1 kodingnya membuat tombol sumbit hasilnya](https://github.com/user-attachments/assets/4dc64841-43b5-42ca-bd1a-abba13e003a5)


output
seluruh kodingnya
![ss2 input](https://github.com/user-attachments/assets/ccd98191-1d73-4bb0-a897-20bfebda1fb9)


===================================================================================
1. output Menghitung Umur
![ss2 menghitung umur](https://github.com/user-attachments/assets/f6f3b59d-953a-4b2b-94a7-f104490063a0)
- new DateTime($tanggal_lahir): Membuat objek tanggal lahir.
- $sekarang->diff($tanggalLahir)->y: Menghitung selisih tahun.


2. output Menentukan Gaji
![ss2 menghitung gaji](https://github.com/user-attachments/assets/0947332a-022a-4690-b3b7-d108830ff86a)
- $gajiList: Array berisi daftar gaji sesuai pekerjaan.
- $gaji = isset(...): Mengecek apakah pekerjaan valid.


   - pengisian
![pengisian](https://github.com/user-attachments/assets/4cdfbaac-a60f-407a-a700-e6d0f9f74ccb)

   - hasil akhir output
![hasil inout](https://github.com/user-attachments/assets/899289d1-8856-4583-9a5e-a81661d1931e)

