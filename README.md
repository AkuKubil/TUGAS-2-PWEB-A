# TUGAS-2-PWEB-A
## Membuat Website Profil Diri  

### Identitas  
- **Nama** : Brilian Kurniawan Prasisto  
- **NRP**  : 5025241213  
- **Mata Kuliah** : Pemrograman Web  

---

## Tujuan  
Tugas ini bertujuan untuk membuat halaman web sederhana menggunakan **HTML** yang menampilkan informasi profil diri. Halaman ini mencakup deskripsi diri, hobi, riwayat pendidikan, form kontak, serta tautan sosial media.  

---

## Hasil Implementasi Per Bagian


### 1. Tampilan & Struktur Halaman  
Website terdiri dari beberapa bagian utama:  
1. **Judul, Identitas & Foto Profil**  
   - Menampilkan judul "Welcome To" dan identitas berupa nama serta NRP. Lalu, menampikan foto profil juga
    ![Tampilan Identitas](identitas.png)

      Potongan Kode :
     ```html
     <h1>Welcome To</h1>
     <h2>Brilian Kurniawan Prasisto's Profile</h2>
     <h3>NRP  : 5025241213</h3>
     <img src="Profile Picture.jpg" alt="Profile Picture" width="400">

2. **Deskripsi Diri**  
   - Paragraf yang menjelaskan pengalaman kepemimpinan, kemampuan komunikasi, serta motivasi untuk berkembang.
    ![Tampilan Deskripsi Diri](assets/screenshot-profil.png)

    Potongan Kode :
   ```html
   <h2>Deskripsi Diri</h2>
   
   <p>Seorang mahasiswa yang berkomitmen di bidang Teknik Informatika dengan pengalaman dalam perencanaan acara dan kepemimpinan, pernah menjabat sebagai Ketua
   OSIS SMA dan Ketua Panitia Acara. Melalui posisi-posisi ini, saya dapat mengasah kemampuan kepemimpinan, perencanaan proyek,
   komunikasi, dan pemecahan masalah yang membantu saya mengelola tim dan memastikan acara-acara kompleks dapat dilaksanakan
   dengan sukses. Saya selalu siap untuk menerapkan keahlian teknis dan keterampilan sosial saya agar dapat bekerja pada inisiatif inovatif, berkolaborasi
   dengan tim yang berbeda, dan berkembang dalam lingkungan yang dinamis dan cepat berubah.</p>


4. **Hobi**  
   - Ditampilkan dalam bentuk **list** (`<ul>` dan `<li>`).
     ![Tampilan Hobi](assets/screenshot-profil.png)

     Potongan Kode :
     ```html
     <h2>Hobi</h2>
     <ul>
     <li>Main Gitar</li>
     <li>Mendengarkan Musik</li>
     <li>Main Game</li>
     <li>Nonton Film</li>
     </ul>

5. **Riwayat Pendidikan**  
   - Ditampilkan dalam bentuk **tabel** (`<table>` dengan border).
    ![Tampilan Deskripsi Diri](assets/screenshot-profil.png)

    Potongan Kode :
   ```html
   <h2>Tabel Riwayat Pendidikan</h2><table border="1">
    <tr>

        <th>Jenjang Pendidikan</th>

        <th>Keterangan</th>

        <th>Tahun</th>

    </tr>

    <tr>

        <td>Sekolah Dasar</td>

        <td>SDIT Al-Mubarak</td>

        <td>2012 s.d 2018</td>

    </tr>

    <tr>

        <td>Sekolah Menengah Pertama</td>

        <td>MTs Istiqlal Jakarta</td>

        <td>2018 s.d 2021</td>

    </tr>

    <tr>

        <td>Sekolah Menengah Atas</td>

        <td>SMA Insan Cendekia Boarding School</td>

        <td>2021 s.d 2024</td>

    </tr>

    <tr>

        <td>Perguruan Tinggi</td>

        <td>Institut Teknologi Sepuluh Nopember</td>

        <td>2024 s.d Sekarang</td>

    </tr>
   </table>

7. **Form Kontak**  
   - Form sederhana dengan input nama, email, dan pesan.
     ![Tampilan Deskripsi Diri](assets/screenshot-profil.png)

     Potongan Kode :
     ```html
     <h2>Form Kontak</h2>
     <form>
     <label>Nama:</label><br>
     <input type="text" name="nama"><br><br>
     <label>Email:</label><br>
     <input type="email" name="email"><br><br>
     <label>Pesan:</label><br>
     <input type="text" name="pesan"><br><br>
     <input type="submit" value="Kirim">
     </form>
     
8. **Sosial Media**  
   - Link ke Instagram dan LinkedIn menggunakan tag `<a>` dengan `target="_blank"`.
     ![Tampilan Deskripsi Diri](assets/screenshot-profil.png)

     Potongan Kode :
     ```html
     <h2>Sosial Media</h2>
     <p>Instagram : <a href="https://www.instagram.com/brilian_kurniawan/" target="_blank">Kunjungi Instagram</a></p>
     <p>LinkedIn  : <a href="https://www.linkedin.com/in/brilian-kurniawan-prasisto-066327327/" target="_blank">Kunjungi LinkedIn</a></p>

---


