# Belajar HTML Ke-2

**Sebelumnya, kita telah belajar HTML:**

1. Peletakan html, body & title.

2. Membuat Heading.

3. Membuat Paragraf

4. Menggunakan center.

5. Membuat link.

---

**Kali ini, kita akan mempelajari, Sebagai Berikut:**

1. Cara membuat teks miring, tebal & strike line

2. Cara membuat tombol agar mengarah ke Local Page.

3. Cara membuat tabel dengan HTML.

4. Cara memasukan gambar & video.

---

Sebelum itu, halaman ini telah ditulis Tana dengan Bahasa Markdown. Apa itu Markdown? 

*Markdown adalah (lightweight markup language) bahasa markup yang lebih ringan dari HTML untuk formatting teks.*

*Markdown bisa dikonversi ke dalam HTML menggunakan beberapa aplikasi. Biasanya menggunakan markdown editor itu sendiri.*

*Markdown dibuat pada tahun 2004 oleh John Gruber. Tujuannya untuk mempermudah penulisan dokumen web—mudah ditulis dan mudah dibaca—Karena menulis langsung HTML terasa melelahkan dan susah dibaca.*

Kita akan mempelajari Markdown setelah selesai dengan Bahasa HTML5, CSS3, JS

---

**Mari Kita Lanjut Ke Pembahasan HTML5**

1. Cara membuat teks Miring, Tebal & Strike line.

Mungkin kamu sendiri sudah diajarkan di sekolah. Namun agar menambah daya ingat, akan saya ajarkan lagi..

Untuk format teks *Miring*, **Tebal** dan <s>StrikeLine</s> seperti ini, kita bisa menggunakan kode sebagai berikut

```html

<em>Teks Miring<em>

<b>Teks Tebal</b>

<s>Strike Line<s>

```

Begitulah cara membuat teks *Miring*, **Tebal** dan <s>Strike Line</s>

---

2. Cara membuat tombol, agar mengarah ke Local Page.

Sebenarnya ini adalah hal yang lebih penting, daripada membuat link, cuman saya nya aja yang lupa, seharusnya ini adalah materi awal.

Cara bekerja tombol ini sangatlah sama dengan cara memasukkan link pada materi sebelumnya, contoh nya seperti ini:

```html

<a href="youtube.com>Memasukkan Link</a>

<a href="home.html>Local Page</a>

```

Maka hasilnya seperti ini:

[Memasukkan Link](youtube.com) &

[Local Page](home.html)

Oleh karen itu, kita akan belajar cara membuat tombol & sekaligus mengarah ke Local Page..

Apa itu Local Page? Local Page sama hal nya dengan index.html, semua website pasti memiliki file index.html. Index berfungsi sebagai halaman utama Website, index.html juga termasuk local page. Kemudian, setiap web pasti memiliki halaman kedua, karena tidak mungkin Website hanya berisi 1 halaman, oleh karena itu kita membuat local page ke-2, atau halaman website kedua. Pastikan setiap local page menjadi 1 folder, namun karena kita menggunakan Replit maka tidak perlu memikirkan hal itu.

Cara membuat tombol agar mengarah ke Local Page Lainnya:

Untuk dasarnya, silahkan membuat file baru dengan nama (sebagai contoh) home.html, jika sudah selesai, maka pada hal. index atau file index.html kita menuliskan:

```html

<a href="home.html">

    <button type="button">Menuju Halaman Lain</button>

  </a>

```

Maka Hasilnya seperti ini:

<a href="home.html">

    <button type="button">Menuju Halaman Lain</button>

  </a>

  

  Jika kamu menekan tombol tersebut, maka akan membuka Local Page ke-2 kalian yang bernama home.html. Bagaimana? Mudah bukan? Kita juga bisa membuat tombol tersebut menuju ke akun media sosial kita sebagai contoh:

```html

<a href="youtube.com">

    <button type="button">Menuju Youtube</button>

  </a>

```

Maka Hasilnya seperti ini:

<a href="youtube.com">

    <button type="button">Menuju Youtube</button>

  </a>

  

  Begitulah cara membuat tombol agar menuju ke Local Page lainnya.

  

  ---

  

  3. Cara membuat tabel menggunakan HTML5.

  

 Untuk meng-input data, kita menggunakan tabel, terkadang kita menggunakan software lain seperti Microsoft Excel, atau Microsoft Word, namun kali ini, kita akan mencoba membuat tabel menggunakan HTML5. Berikut cara membuat nya:

  

  ```html

    <table>

    <thead>

      <tr>

        <th>Nama</th>

        <th>NIM</th>

        <th>Jurusan</th>

      </tr>

    </thead>

    <tbody>

      <tr>

        <td>Tana</td>

        <td>123456789</td>

        <td>Teknik Informatika</td>

      </tr>

      <tr>

        <td>Adnan</td>

        <td>987654321</td>

        <td>Sistem Informatika</td>

      </tr>

    </tbody>

  </table>

  ```

  

  Dengan Kode tersebut, akan menghasilkan:

    <table>

    <thead>

      <tr>

        <th>Nama</th>

        <th>NIM</th>

        <th>Jurusan</th>

      </tr>

    </thead>

    <tbody>

      <tr>

        <td>John Doe</td>

        <td>123456789</td>

        <td>Teknik Informatika</td>

      </tr>

      <tr>

        <td>Jane Smith</td>

        <td>987654321</td>

        <td>Sistem Informasi</td>

      </tr>

    </tbody>

  </table>

  

 Ribet bukan? Iya njir, ribet banget, makanya jarang² ada orang pake tabel di web, lol

 ```html

 <table> Adalah awalan membuat tabel.

 <thead> Adalah bagian atas tabel.

 <tr> Adalah garis untuk tabel tersebut.

 <th> Adalah isi pada kolom tersebut.

 <tbody> Adalah badan dalam tabel tersebut.

 ```

 

 Itu adalah cara membuat Tabel menggunakan kode HTML5, tentu saja sangat susah & ribet, makanya kamu jarang lihat tabel, namun ini hanya sebagai ilmu saja...

 

 ---

 

 4. Cara memasukan Gambar & Video.

 

 Agar tampilan website makin jelas, maka kita menggunakan foto agar isi website juga terlihat beragam dan menarik. Sebelum itu, masukkan foto atau video yang kamu inginkan, pastikan foto atau video tersebut ada dalam satu folder dengan Local Page itu. Berikut adalah caranya:

 

 ```html

 <img src="img.jpg" alt="Contoh Gambar">

 ```

 

 Kode tersebut akan memberikan gambar yang kamu pilih tadi, pastikan nama file gambar yang kamu pilih itu sama dengan contoh kode diatas. Maksudnya ialah jika nama file gambar kamu bernama img.jpg, maka pastikan di kode tersebut nama filenya juga img.jpg. Jika nama file & yang berada di kode berbeda, maka gambar tidak akan keluar di Website mu. *alt* pada kode diatas ialah caption jika gambar tidak keluar. Hasilnya seperti ini:

 

 <img src="img.jpg" alt="Contoh Gambar">

 

 Cara upload video untuk website. Merupakan cara yang sama hanya berbeda sebagai berikut:

 

 ```html

   <video controls>

    <source src="vid.mp4" type="video/mp4">

    Maaf, browser Anda tidak mendukung pemutaran video.

  </video>

  ```

  

Lumayan Ribet Bukan? 

Dalam contoh di atas, video tersebut bernama vid.mp4. Browser akan mencoba memutar video dalam format (.mp4) yang didukung. Jika format yang didukung tidak tersedia, teks "Maaf, browser Anda tidak mendukung pemutaran video" akan ditampilkan.

Berikut Hasilnya:

<video controls>

    <source src="vid.mp4" type="video/mp4">

    Maaf, browser Anda tidak mendukung pemutaran video.

  </video>

  

Pastikan nama file video yang kamu pilih itu sama dengan yang ada di kode. Jika berbeda, maka Video tidak akan muncul.

  

Pada dasarnya, foto & video yang kamu beri di Website tersebut akan berukuran file original nya, oleh karena itu jika kamu ingin belajar cara mengatur ukuran foto & video, Tunggulah di pelajaran selanjutnya..

---

Itu adalah materi untuk *Belajar HTML Ke-2*, Sangat mudah bukan? kecuali membuat tabel pastinya hehe.. Berikut adalah Tugasnya:

**Tugas setelah mempelajari materi ke-2:**

  <ul>

    <li><label><input type="checkbox">Membaca Materi</label></li>

    <li><label><input type="checkbox">Memahami Materi</label></li>

    <li><label><input type="checkbox">Mengerjakan tugas</label></li>

  </ul>

  

 Tugas: Buatlah halaman website dengan ketentuan sebagai berikut:

 1. Buat paragraf kecil dengan memasukkan huruf tebal, miring & strikeline.

 2. Buat tombol pada file index.html agar mengarah ke file home.html, begitu juga sebaliknya, buat tombol pada file home.html agar mengarah ke file index.html

 3. Buatlah simpel tabel pada file home.html (terserah mau di isi apa..)

 4. Masukkan Gambar/Video (pilih salah satu, atau dua² nya juga boleh) pada file home.html

 

 ---

 

 Sekian dari Tana, Terimakasih. Merasa materi menarik? Share ke teman² kamu agar sama² mengetahui. Kunjungi Saya:

 

 <a href="github.com/Nikesyg">

    <button type="button">My Github</button>

  </a>

  <a href="instagram.com/Hyug4_N4t10n">

    <button type="button">My Instagram</button>

  </a>

 <a href="wa.me/6281332383711">

    <button type="button">Call Me</button>

  </a>

