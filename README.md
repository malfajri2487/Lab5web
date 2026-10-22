# Praktikum 5: Pengenalan JavaScript - Pemrograman Web
Repository ini dibuat untuk menyelesaikan tugas Praktikum 5 Pemrograman Web.
 
## Identitas Mahasiswa
 
| Keterangan      | Data                          |
| --------------- | ----------------------------- |
| **Nama**        | Muhammad Al Fajri             |
| **Kelas**       | I251D                         |
| **NIM**         | 312510353                     |
| **Mata Kuliah** | Pemrograman Web               |
| **Dosen**       | Agung Nugroho, S.Kom., M.Kom. |
 
### Tujuan Praktikum
 
Mahasiswa mampu memahami dasar-dasar JavaScript (variabel, operator, function).
 
Mahasiswa mampu menggunakan `console.log()`, `alert()`, `prompt()`, dan `textContent` untuk input/output.
 
Mahasiswa mampu menggunakan seleksi kondisi (`if-else` dan `switch`).
 
Mahasiswa mampu memanipulasi DOM dan menangani event pada HTML.
 
---
 
## Struktur Folder Proyek
 
```
Lab5Web/
├── Mini Project/
│   ├── Kalkulator_Mahasiswa.html
│   └── kalkulator.js
├── Lab5_JavaScript.html
├── script.js
└── README.md
```
 
<!-- Ganti dengan screenshot struktur folder -->
<img width="283" height="199" alt="image" src="https://github.com/user-attachments/assets/415b3b8e-d486-4b79-9450-86c5893d3eab" />

 
---
 
## Langkah-langkah Praktikum
 
### 1. Membuat Dokumen HTML dan `console.log()`
 
Membuat dokumen HTML dengan nama `Lab5_JavaScript.html` yang berisi judul "Pengenalan JavaScript", sebuah paragraf dengan `id="Pesan"`, dan menghubungkan file `script.js`.
 
<img width="784" height="336" alt="image" src="https://github.com/user-attachments/assets/b38bda8c-e50f-4c8c-bfe5-baa6621ab9a0" />

 
Pada `script.js`, isi paragraf diubah menggunakan `textContent` dan ditampilkan juga di console dengan `console.log()`.
 
<img width="802" height="92" alt="image" src="https://github.com/user-attachments/assets/4000fd49-159c-40c6-97bf-6f6cf7c64a3b" />


Menampilkan Hasil Console.log (“Hello World”) di Inspek Console 
<img width="960" height="564" alt="Screenshot 2026-10-22 093617" src="https://github.com/user-attachments/assets/0f320048-dccd-4dad-89c0-a69ceef26e79" />

---
 
### 2. Alert dan Prompt
 
Program meminta nama pengguna dengan `prompt()`. Jika diisi, ditampilkan `alert` sapaan dan teks pada halaman diubah. Jika kosong atau dibatalkan (Cancel), muncul alert "Nama belum diisi."
 
<img width="559" height="189" alt="image" src="https://github.com/user-attachments/assets/138ca444-e77d-49c6-9738-7a1d0f15eebe" />

 

 
| Skenario | Hasil |
| -------- | ----- |
| Nama diisi | Muncul alert "Halo, Muhammad Al Fajri!" dan teks halaman berubah |
| Cancel / input kosong | Muncul alert "Nama belum diisi." |
 
<img width="960" height="564" alt="Screenshot 2026-10-22 093844" src="https://github.com/user-attachments/assets/0032c076-67d0-46f2-85d5-3388529b5c0d" />

 
<img width="960" height="564" alt="Screenshot 2026-10-22 093907" src="https://github.com/user-attachments/assets/d090ec39-e703-4124-8073-c03b44a24fff" />

 <img width="960" height="564" alt="Screenshot 2026-10-22 093854" src="https://github.com/user-attachments/assets/fb90f6fe-910d-42dc-a36b-372bd44788c7" />


---
 
### 3. Function dan Operasi Aritmetika
 
Membuat function `operasiDasar(a, b)` untuk operasi penjumlahan, pengurangan, perkalian, pembagian (dengan pengecekan pembagi nol), dan modulus. Function dipanggil dengan `operasiDasar(9, 4)`.

<img width="724" height="186" alt="image" src="https://github.com/user-attachments/assets/0f6d1e31-32d9-4fba-a005-0c106c34d9df" />

Hasil di console: Penjumlahan `13`, Pengurangan `5`, Perkalian `36`, Pembagian `2.25`, Modulus `1`.

<img width="960" height="564" alt="Screenshot 2026-10-22 094033" src="https://github.com/user-attachments/assets/f8e188fc-c76e-4171-aba4-434f2de9d057" />



 
---
 
### 4. Seleksi Kondisi `if-else`
 
Program meminta nilai (0-100) dengan `prompt()`, lalu memvalidasi input. Nilai >= 60 dinyatakan "Lulus", selain itu "Belum lulus", dan input tidak valid akan menampilkan pesan kesalahan.
 
<img width="610" height="410" alt="image" src="https://github.com/user-attachments/assets/f48544ae-a9e3-4d9a-8ba8-231063b71f79" />
 
<img width="960" height="564" alt="Screenshot 2026-10-22 094138" src="https://github.com/user-attachments/assets/aa5a4f9b-1076-407e-b09c-8f4643851a28" />


<img width="960" height="564" alt="Screenshot 2026-10-22 094146" src="https://github.com/user-attachments/assets/2401c784-56a1-46bf-b392-6dbab71f05a5" />



Jika Nilai Mahasiswa di bawah 60, maka alert akan memberi tahu “Belum lulus”

<img width="960" height="564" alt="Screenshot 2026-10-22 094212" src="https://github.com/user-attachments/assets/55c1ccd0-8cd4-4ede-baef-fa19cde47cfa" />


 
---
 
### 5. Seleksi Kondisi `switch`
 
Program meminta angka 1-5. Setiap angka menampilkan alert bilangan yang sesuai (satu sampai lima), dan selain itu menampilkan "Pilihan tidak tersedia" melalui `default`.
 
<img width="333" height="288" alt="image" src="https://github.com/user-attachments/assets/0afbdf18-bac0-480a-b5b5-c9df89a9101a" />

 
<img width="960" height="564" alt="Screenshot 2026-10-22 094448" src="https://github.com/user-attachments/assets/049b1a1c-127f-4fd2-93b5-e4eaf2ac5d1d" />



<img width="960" height="564" alt="Screenshot 2026-10-22 094424" src="https://github.com/user-attachments/assets/9cd5fe2c-9820-4c8d-8f2e-4768691f9536" />



 
<img width="480" height="246" alt="image" src="https://github.com/user-attachments/assets/6899dbd8-901b-4c51-ae6b-7815a9d54130" />

 
<img width="489" height="167" alt="image" src="https://github.com/user-attachments/assets/be6f9032-7e66-4f6b-a6b6-b0b74aa7cbe7" />

 
---
 
### 6. Form Bilangan Genap atau Ganjil
 
Membuat form input bilangan dan tombol "Periksa" yang memanggil function `cekBilangan()`. Function memvalidasi bahwa input adalah bilangan bulat, lalu menentukan genap atau ganjil menggunakan operator modulus.
 
<img width="685" height="136" alt="image" src="https://github.com/user-attachments/assets/36f36e42-c932-481d-b93a-1429866d3392" />

 
<img width="506" height="269" alt="image" src="https://github.com/user-attachments/assets/08f84a75-a1f8-4fb4-ac7e-0ff52c86a5c4" />

 
| Input | Hasil |
| ----- | ----- |
| `6` | Bilangan genap |
| `3.5` | Masukkan bilangan bulat yang valid. |
 
<img width="960" height="564" alt="Screenshot 2026-10-22 095008" src="https://github.com/user-attachments/assets/2b3eeff1-39aa-424f-a224-1141668afa87" />


 
<img width="960" height="564" alt="Screenshot 2026-10-22 095028" src="https://github.com/user-attachments/assets/ae99c1d8-bfb6-482a-b85a-2f351ab85ba7" />



 
---
 
### 7. Mengubah Warna Halaman
 
Menambahkan tiga tombol (Latar Hijau, Latar Putih, Latar Kuning) yang memanggil function `ubahWarnaLatar(warna)` untuk mengubah `document.body.style.backgroundColor`.
 
<img width="805" height="165" alt="image" src="https://github.com/user-attachments/assets/15011705-553f-49cc-bd67-56f59686f133" />

<img width="800" height="126" alt="image" src="https://github.com/user-attachments/assets/1bf9cc46-05b9-4c31-9517-e78aac120111" />

<img width="960" height="564" alt="Screenshot 2026-10-22 095158" src="https://github.com/user-attachments/assets/f5fab654-a837-480a-b33a-7bbff5381e12" />


 
---
 
### 8. DOM dan Checkbox Menu Makanan
 
Membuat daftar menu makanan dengan checkbox (class `menu`) yang nilainya berisi harga. Setiap perubahan checkbox memicu function `hitungTotal()` yang menjumlahkan harga menu yang dicentang dan menampilkannya pada elemen `#total`.
 
<img width="457" height="368" alt="image" src="https://github.com/user-attachments/assets/a4f67597-5e07-41e9-a006-51502ff8c030" />

<img width="570" height="286" alt="image" src="https://github.com/user-attachments/assets/9893afd4-71de-48c2-b323-ca0c295f3906" />

<img width="960" height="564" alt="Screenshot 2026-10-22 100112" src="https://github.com/user-attachments/assets/2ec9f549-dfd8-4132-bcc6-749a1a007a7e" />


 
---
 
## F. Mini Project - Kalkulator Nilai Mahasiswa
 
Mini project berada di folder `Mini Project` (`Kalkulator_Mahasiswa.html` dan `kalkulator.js`). Form menerima nilai **Tugas**, **UTS**, dan **UAS**, kemudian menghitung nilai akhir dengan bobot:
 
| Komponen | Bobot |
| -------- | ----- |
| Tugas    | 30%   |
| UTS      | 30%   |
| UAS      | 40%   |
 
Predikat ditentukan dengan ketentuan: **A** (>= 85), **B** (>= 75), **C** (>= 60), **D** (>= 50), dan **E** (< 50). Status **Lulus** jika nilai akhir >= 60. Setiap nilai divalidasi harus berada pada rentang 0-100.
 
<img width="422" height="331" alt="image" src="https://github.com/user-attachments/assets/badf672b-681a-4efa-9f48-d7e751f22e5e" />


 
<img width="464" height="429" alt="image" src="https://github.com/user-attachments/assets/dbdab0e8-9cad-4f90-a7c8-22002d83958d" />

 
| Skenario | Input (Tugas, UTS, UAS) | Nilai Akhir | Predikat | Status |
| -------- | ----------------------- | ----------- | -------- | ------ |
| 1 (Lulus) | 80, 80, 80 | 80.00 | B | Lulus |
| 2 (Belum Lulus) | 40, 30, 40 | 37.00 | E | Belum lulus |
| 3 (Validasi Gagal) | 50, 40, 120 | - | - | Alert "Validasi Gagal: Setiap nilai harus berada pada rentang 0-100." |
 <img width="960" height="564" alt="Screenshot 2026-10-22 100924" src="https://github.com/user-attachments/assets/fbce61f3-6337-4d1c-b294-d29467ebc2f6" />



<img width="960" height="564" alt="Screenshot 2026-10-22 100953" src="https://github.com/user-attachments/assets/16930e9b-955b-4f11-9379-a5fd3c1a369b" />



 
<img width="511" height="231" alt="image" src="https://github.com/user-attachments/assets/e35e4555-8dfc-435b-980b-67407dd95d77" />

 
---
 
## G. Eksperimen Mandiri
 
Eksperimen yang dilakukan pada `script.js`:
 
- **Poin 1 & 9:** Function `operasiDariPrompt()` meminta dua angka lewat `prompt()` lalu menampilkan hasil operasi dasar. Jika kolom kosong, muncul alert "Kolom operasi dasar tidak boleh kosong!".
- **Poin 7:** Function `tabelPerkalianTujuh()` menampilkan tabel perkalian 7 menggunakan perulangan `for`.
- **Poin 8:** Function `cekGenapPoin8(angka)` mengembalikan `true` atau `false` (contoh: 10 genap = `true`, 7 genap = `false`).
- **Poin 11:** Tombol "Sembunyikan / Tampilkan Teks" untuk menyembunyikan dan menampilkan kembali sebuah teks.

<img width="398" height="467" alt="image" src="https://github.com/user-attachments/assets/93afafd3-0a2d-4873-9b49-4383f873e7fe" />

 
<img width="418" height="204" alt="image" src="https://github.com/user-attachments/assets/a810149b-3e87-44fc-90ce-0464e3861173" />

 
<img width="433" height="216" alt="image" src="https://github.com/user-attachments/assets/67ea4161-e980-4593-bcad-63479850e5eb" />

 
Hasil di console (Poin 1 & 9, Poin 7, dan Poin 8):

<img width="363" height="428" alt="image" src="https://github.com/user-attachments/assets/031d0355-cd34-40d8-8dcb-c9e5d7b0e921" />

 
**Poin 11: Fitur Tombol Sembunyikan Teks**
 
Sebelum tombol diklik, teks tampil
 
<img width="642" height="151" alt="image" src="https://github.com/user-attachments/assets/025e7113-6a15-4b81-8678-e0c41c841e2f" />

 
Sesudah tombol diklik, teks tersembunyi
 
<img width="417" height="173" alt="image" src="https://github.com/user-attachments/assets/b512e882-ac5d-4a6c-9353-b7a0e2272f00" />

 
### Hasil Keseluruhan Praktikum
 
<img width="960" height="564" alt="Screenshot 2026-10-22 132457" src="https://github.com/user-attachments/assets/df86b5c0-4add-4928-8287-68b41fb9ce4d" />


 
<img width="960" height="564" alt="Screenshot 2026-10-22 100924" src="https://github.com/user-attachments/assets/8af03c96-ec20-462a-89b6-8c7439a8d17d" />


 
---
 
## Kesimpulan
 
Pada praktikum ini telah dipelajari dasar-dasar JavaScript, mulai dari output (`console.log`, `alert`, `textContent`), input (`prompt`), function, operasi aritmetika, seleksi kondisi `if-else` dan `switch`, hingga manipulasi DOM dan penanganan event seperti pada form bilangan, tombol ubah warna, dan checkbox menu makanan. Selain itu dibuat mini project Kalkulator Nilai Mahasiswa dengan validasi input.
 
