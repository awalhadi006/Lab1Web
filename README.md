# Lab1Web
<h1> Langkah-langkah Praktikum </h1>

<p>
<ol>
  <li> Langkah pertama adalah membuka visual studio codenya.

![Screenshot_25](https://user-images.githubusercontent.com/24362384/113001739-4cd64000-919b-11eb-9261-e621c027f1ab.png)

  <li> Langkah kedua adalah membuat file baru pada visual studio codenya dengan nama <b> lab1_tag_dasar.html. </b>

![Screenshot_26](https://user-images.githubusercontent.com/24362384/113002672-38467780-919c-11eb-8c03-b0796b40846d.png)

  <li> Langkah ketiga adalah menambahkan tag dasar pada file yang telah kita buat sebelumnya.
  
  ![Screenshot_27](https://user-images.githubusercontent.com/24362384/113003282-c3277200-919c-11eb-8713-ede83415e847.png)

  <li> Setelah kita menambahkan tag dasar pada file tersebut, selanjutnya kita coba buka filenya menggunakan web browser yang tersedia pada Laptop/Komputer kalian (bisa menggunakan chrome, mozilla firefox, dll).
  
  ![Screenshot_28](https://user-images.githubusercontent.com/24362384/113003835-4ba61280-919d-11eb-9d2b-ee9eb6fa2196.png)
  
  </li>
</ol>
</p>

<p>
<ol>
  <li><h3> Membuat Paragaraf </h3>
  Cara menambahkan beberapa paragraf sederhana sebagai berikut :
    
    <p> Saya sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran Pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML. </p>
    <p> Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan tag dasar HTML. </p>

   Selanjutnya simpan kembali perubahannya, dan lakukan refresh (reload) pada web browser, lihat hasilnya.

![Screenshot_30](https://user-images.githubusercontent.com/24362384/113396174-47f4d480-93c5-11eb-97e3-ed03809290e6.png)

   Kemudian bisa mengatur align paragraf seperti <i> left, right, center, justify </i> dengan menambahkan atribut seperti dibawah ini (paragraf pertama menggunakan <i> Right </i> paragraf kedua menggunakan <i> Center </i>) :
</p>

![Screenshot_31](https://user-images.githubusercontent.com/24362384/113400586-395deb80-93cc-11eb-8c39-d5ebf89d4023.png)

<p>
  <li><h3> Menambahkan Judul </h3>
Judul memiliki 6 level/tingkatan yaitu mulai h1 sampai h6. Kemudian coba tambahkan judul h1 sebelum paragraf pertama dan tambahkan sub judul h2 sebelum paragraf kedua.
  
    <h1>Belajar Dasar HTML</h1>
    <h2>Paragraf pada HTML</h2>

Simpan perubahannya dan coba lihat hasilnya dengan melakukan refresh (reload) pada web browser kalian. 
</p>

![Screenshot_32](https://user-images.githubusercontent.com/24362384/113404267-159da400-93d2-11eb-81ea-e22bf751a441.png)

<p>
<li><h3> Memformat Teks </h3>
di HTML pun bisa melakukan pemformatan teks layaknya di Microsoft Word ataupun aplikasi yang lainnya, dengan cara sebagai berikut :
  
    <mark></mark> : digunakan untuk menandai teks.
    <b></b>       : digunakan untuk menebalkan teks.
    <i></i>       : digunakan untuk memiringkan teks.
    <ins></ins>   : digunakan untuk memberikan garis bawah pada teks.
                    dan lain sebagainya.
    
Contoh penggunaan tag &lt;mark&gt;, &lt;b&gt;, &lt;i&gt;, dan &lt;ins&gt; untuk memformat teks.
</p>

![Screenshot_33](https://user-images.githubusercontent.com/24362384/113408656-ec811180-93d9-11eb-8bce-03e402beb639.png)

<p>
<li><h3> Menyisipkan Gambar </h3>
  Untuk menyisipkan gambar, siapkan gambar yang akan disisipkan pada halaman web, kemudian simpan file gambar tersebut dalam satu folder dengan file dokumen html yang telah kita buat sebelumnya. Atau bisa juga menyisipkan gambar dari website eksternal.
  
  ![Screenshot_34](https://user-images.githubusercontent.com/24362384/113408753-26521800-93da-11eb-8902-79b26b53e388.png)

Kemudian tambahkan tag <b> img </b> setelah paragraf yang kedua, dengan menambahkan heading 3 sebelumnya.

    <h3>Menambahkan Gambar</h3>
    <img src="lab1_contoh_gambar.png" title="Logo Universitas Pelita Bangsa">
    
Simpan perubahan yang telah kita buat, kemudian refresh (reload) web browser.

![Screenshot_35](https://user-images.githubusercontent.com/24362384/113409025-a2e4f680-93da-11eb-8bcd-cec2710f9484.png)

Gambar akan ditampilkan apa adanya sesuai dengan ukuran gambar aslinya. Untuk mengatur ukuran gambar sesuai dengan yang kita inginkan, dapat digunakan atribut <b> witdh </b> dan <b> height </b> dengan nilai <i> integer </i> yang disesuaikan.

    <img src="lab1_contoh_gambar.png" width="200" title="Logo Universitas Pelita Bangsa">
</p>

![Screenshot_36](https://user-images.githubusercontent.com/24362384/113409219-053df700-93db-11eb-9a88-43cc1919fdf4.png)

<p>
<li><h3> Menambahkan Hyperlink </h3>
  Hyperlink merupakan suatu fungsi dalam HTML yang tujuannya untuk memudahkan visitor atau pengunjung web untuk menelusuri informasi yang tersimpan di dalam suatu website yang dikunjunginya dan link juga berguna untuk menghubungkan antar dokumen HTML. Cara menambahkan Hyperlink pada halaman web yang telah kita buat sebagai berikut.
  
    <nav>
        <a href="lab1_tag_dasar.html">Dasar HTML</a>
        <a href="lab1_halaman2.html>Halaman 2</a>
        <a href="https://ecampus.pelitabangsa.ac.id">Halaman Web Eksternal Kampus Universitas Pelita Bangsa</a>
    </nav>
    <hr>

Buat satu file lagi dengan nama <b> lab1_halaman_web2.html </b> kemudian isi dokumen tersebut dengan tag html dasar dan dengan isi bebas, boleh mengcopy dari halaman sebelumnya.

![Screenshot_37](https://user-images.githubusercontent.com/24362384/113409521-a927a280-93db-11eb-8110-52db67271988.png)

Halaman Web kedua :

![Screenshot_43](https://user-images.githubusercontent.com/24362384/113465479-6fe44680-945e-11eb-9a30-875aecec7840.png)

</ol>
</p>

<p>
<h3> Jawab Pertanyaan Berikut </h3>
<ol>
  <li> Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah <i> error </i> ketika terjadi kesalahan penulisan tag?
  <li> Apa perbedaan dari tag &lt;p&gt; dengan tag &lt;br&gt;, berikan penjelasannya!
  <li> Apa perbedaan atribut "title" dan "alt" pada tag &lt;img&gt;, berikan penjelasannya!
  <li> Untuk mengatur ukuran gambar, digunakan atribut "width" dan "height". Agar tampilan gambar proporsional sebaikanya kedua atribut tersebut diisi semua atau tidak? Berikan penjelesannya!
  <li> Pada "link" tambahkan atribut "target" dengan nilai atribut bervariasi (_<i> blank </i>, _<i> self </i>, _<i> top </i>, _<i> parent </i>), apa yang terjadi pada masing-masing nilai atribut tersebut?
  </li></ol>
    
<h3> Jawaban </h3>
<ol>
  <li> Setelah saya melakukan perubahan pada kode sesuai keinginan saya, terdapat perubahan atau <i> error </i> jika saya melakukan kesalahan pada penulisan tag, seperti contoh dibawah ini :
  Jika tag tidak ditutup.
    
  ![Screenshot_39](https://user-images.githubusercontent.com/24362384/113463773-1d049200-9452-11eb-8c04-cc5d65356c13.png)

  Maka hasilnya jadi seperti ini.
  
  ![Screenshot_38](https://user-images.githubusercontent.com/24362384/113463781-2a218100-9452-11eb-9915-251395d63845.png)

  Namun jika tagnya ditutup.
  
  ![Screenshot_40](https://user-images.githubusercontent.com/24362384/113463826-72d93a00-9452-11eb-936d-a65df5405696.png)

  Maka hasilnya akan jadi seperti ini.
  
  ![Screenshot_37](https://user-images.githubusercontent.com/24362384/113463837-85ec0a00-9452-11eb-9213-1cea195d735f.png)

  <li> Perbedaan antara tag &lt;p&gt; dengan tag &lt;br&gt; adalah dari fungsinya, tag &lt;p&gt; digunakan untuk membuat paragraf baru, sedangkan tag &lt;br&gt; hanya membuat garis baru, masih dalam paragraf yang sama tidak membuat paragraf baru.
  Contoh penggunaan tag &lt;p&gt; dan tag &lt;br&gt; :
  
  ![Screenshot_41](https://user-images.githubusercontent.com/24362384/113463999-cbf59d80-9453-11eb-95e7-17362529b25d.png)
  
  <li> Perbedaan antara tag &lt;title&gt; dengan tag &lt;alt&gt; pada tag &lt;img&gt; adalah kalau tag &lt;title&gt; lebih ke judul gambar, dan jika cursor diarahkan ke gambarnya maka akan muncul balon teks. Sedangkan kalau tag &lt;alt&gt; lebih ke keterangan dari gambar jika gambar tersebut gagal ditampilkan oleh browser. Atau jika web broser telah disetting untuk tidak menampilkan gambar maka akan muncul deskripsi gambar tersebut, dan jika cursor diarahkan ke gambarnya maka balon teks tidak akan muncul.
  Contoh balon teks yang muncul jika kursor diarahkan ke gambar.

![Screenshot_42](https://user-images.githubusercontent.com/24362384/113464339-ffd1c280-9455-11eb-96d2-5ca98ae753c2.png)

  <li> Untuk mempertahankan proporsi gambar, cantumkan hanya salah satu atribut saja (width saja atau height saja, namun tidak keduanya). Misalkan jika kita menetapkan atribut width=300 (tanpa mencantumkan height), maka web browser akan menampilkan gambar dengan lebar 300, dan menghitung secara otomatis tinggi gambar agar gambar tetap proporsional. <br><br>

  <li> Yang terjadi pada "link" jika ditambahkan atribut "target" dengan nilai atribut (_<i> blank </i>, _<i> self </i>, _<i> top </i>, _<i> parent </i>) :
  <ul>
    <li> _<i> blank </i>  : Untuk membuka link di tab baru.
    <li> _<i> self </i>   : Untuk membuka link di frame link itu berada. Ini merupakan setelan dasar link jika pada elemen link tidak diberi atribut target.
    <li> _<i> top </i>    : Untuk membuka link di frame paling atas (paling luar). Misalnya gini, jika di website(1) di dalamnya ada website (2) lalu di website(2) di dalamnya ada website(3) lalu di website(3) ini ada link yang ditambahkan atribut target="top") dan kita klik, maka link akan terbuka di website(1).
    <li> _<i> parent </i> : Untuk membuka link di frame yang satu tingkat diatas frame link tersebut berada. Misalnya gini, jika di website(1) di dalamnya ada website(2) lalu di website(2) ini ada link yang ditambahkan atribut (target="parent") dan kita klik, maka link akan terbuka di website(1).
  
</li></ol></p>
