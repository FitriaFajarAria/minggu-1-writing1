# minggu-1-writing1

UNIX COMMAND LINE
---------------
### 1. Shell

Shell adalah interpreter baris perintah (command line interpreter) sebagai script host untuk antar muka user pada sistem operasi Unix. Shell mengandung
perintah-perintah yang dapat diketik dan langsung dijalankan melalui konsol.Perintah-perintah tersebut juga dapat disimpan dalam suatu file untuk kemudian dijalankan dengan cara memanggil nama file tersebut. 

Shell ini adalah program yang menerima perintah, kemudian meneruskan perintah tersebut ke system untuk dieksekusi.  Selain command line, kita juga punya shell berbasis grafis yang lebih dikenal dengan nama GUI atau graphical user interface.


### 2. CLI (Command Line Interface)

CLI atau Command Line Interface adalah sebuah programan yang dimana user bisa mengetikkan perintah dalam bentuk teks dan memberikan instruksi pada komputer untuk mengerjakan tugas tertentu.


### 3. Terminal 

Terminal merupakan aplikasi atau tempat yang biasa digunakan untuk mengakses CLI .


### 4. File System Structure 

File system struktur merupakan struktur penyimpanan yang mengatur bagaimana sebuah file disimpan kedalam sistem. Pada Sistem Operasi Windows struktur file biasanya akan disimpan menggunakan struktur yang berbentuk mirip dengan sebuah pohon seperti gambar dibawah.


### 5. Command 

- pwd (print working directory), untuk melihat current working directory.
- dir (directory), untuk melihat directory.
- cd (change directory), untuk berpindah directory.
- ls (list), untuk melihat isi file di dalam directory.
- touch, untuk membuat file dan directory.
- cp (copy), untuk menyalin file dan directory.
- mv (move), untuk memindahkan serta merename file dan directory.
- rm (remove), untuk menghapus file dan directory.
  

GIT DAN GITHUB
---------------
### 1. Pengertian GIT dan GITHUB

- GIT 
  
    Git merupakan aplikasi yang dapat melacak setiap perubahan yang terjadi pada suatu folder atau file. Git biasanya digunakan oleh para programmer sebagai tempat penyimpanan file pemrograman mereka, karena lebih efektif dan sebagai Version Control System.

- GITHUB
  
    GITHUB  merupakan manajemen project, sistem versioning code, sekaligus platform jaringan sosial bagi para developer seluruh dunia yang menyediakan layanan cloud untuk menyimpan dan mengelola project/repository git.

### 2. Mengapa Wajib Menggunakan GIT DAN GITHUB 
  
  Ada sebuah ungkapan yang mengatakan bahwa sepandai apapun seoarang programmer tidak akan mampu untuk mengerjakan semua pekerjaan secara mandiri, oleh karena itu penggunaan bantuan seperti GIT dan GITHUB dapat memudahkan seorang programmer untuk berkerjasama serta berkolaborasi dalam sebuah tim yang memiliki tujuan agar mempermudah para programmer dalam membuat proyek/pekerjaan yang sama tanpa perlu repot meng-copy paste sebuah folder pekerjaan.

- Beberapa command di Dalam Git & Github
  
    - git init, berfungsi untuk membuat repositori baru.
      - $ git init fitria_1
    - git commit, untuk melakukan commit atau menyimpan perubahan pada version control pada git. 
      - $ git commit -m "tes commit"
    - git push origin, berfungsi untuk mempublish file atau aplikasi ke github.
      - $ git push origin 
    - git clone, berfungsi untuk melakukan cloning dari github ke komputer atau lokal (dengan memasukkan link yang ingin di cloning).
      - $ git clone 
     
     
HTML 
---------------

### 1.Pengertian HTML

Hypertext Markup Language (HTML) adalah sebuah bahasa markah standar untuk dokumen yang dirancang untuk menampilkan konten-konten pada perambah/browser yang dimana biasanya HTML dituliskan menggunakan tag dengan tanda kurung siku <>. Pada dasarnya HTML sendiri memiliki sifat statis yang hanya bertugas menampilkan konten yang diminta oleh developer, untuk membuat HTML diperlukan kerangka kerja.



    <!DOCTYPE html>
    <html>
    <head>
     <title>
         Fitria Fajar Arianingsih 
     </title>
     </head>
     <body>
        saya sedang membuat tugas wiriting and presentation 
     </body>
      </html>
      
 ### 2. Tag-tag Pada HTML
Tag adalah sebuah penanda awalan dan akhiran dari sebuah elemen di HTML. Tag dibuat dengan kurung siku (<...>), lalu di dalamnya berisi nama tag dan kadang juga ditambahkan dengan atribut.Contoh beberapa tag populer pada HTML:
  
- Tag untuk menambahkan/menampilkan gambar  

    
               <img src="..." alt=""></img>
               
               
- Tag untuk membuat sebuah paragraph


               <body>
                   <p>Belajar tentang tag di HTML</p>
                </body> 
                
                
- Tag untuk membuat list
   - Unordered List


                <ul>
                    benda padat
                 <li>batu</li>
                 <li>kayu</li>
                 <li>besi</li>
               </ul>
               
               
    - Ordered List
   

            <ol>
                benda cair
              <li>air</li>
              <li>minyak</li>
              <li>sirup</li>
            </ol>
        
- Tag HTML Untuk Membuat tulisan dengan link

        <a href="">Selamat Berjuang</a>
        
        
### 3. Semantic HTML

Semantic HTML adalah HTML penggunaan markup HTML untuk memperkuat semantik, atau makna, dari informasi di halaman web dan aplikasi web daripada hanya untuk mendefinisikan presentasi atau tampilannya. HTML semantik diproses oleh browser web tradisional serta oleh banyak agen pengguna lainnya. Contoh elemen semantik:


          <form>, <table>, <footer> dan <article> - Mendefinisikan isinya dengan jelas.
          
          
### 4. Deploy HTML

Deploy adalah sebuah proses untuk menyebarkan aplikasi yang sudah kita kerjakan supaya bisa digunakan oleh orang-orang. Jika aplikasi kita HTML atau Web App kita perlu mendeploy ke server. Untuk melakukan hal tersebut kita bisa menggunakan layanan yang bernama Netlify


CSS
---------------
### 1. Apa Itu CSS
CSS adalah singkatan dari cascading style sheets, yaitu bahasa yang digunakan untuk menentukan tampilan dan format halaman website. Dengan CSS, Anda bisa mengatur jenis font, warna tulisan, dan latar belakang halaman.CSS digunakan bersama dengan bahasa markup, seperti HTML untuk membangun sebuah website yang menarik dan memiliki fungsi yang berjalan baik.

CSS juga berguna untuk mengatasi keterbatasan HTML dalam mengatur format halaman website. Dengan adanya CSS, kita hanya perlu menulis kode satu kali untuk sebuah elemen HTML yang nantinya akan diterapkan ke semua halaman. 

### 2. Beberapa Cara Penggunaan CSS 
- Inline CSS
Inline CSS adalah kode CSS yang ditulis langsung pada atribut elemen HTML. Setiap elemen HTML memiliki atribut style, di situ lah inline CSS ditulis

      <p style="color:green">Hai !!</p>

- External CSS
Kode CSS yang diletakkan di luar dokumen HTML sebagai file .css. Jenis CSS ini berfungsi untuk mengatur tampilan semua halaman website yang Anda tentukan. Jadi, external CSS berguna ketika Anda ingin mengatur tampilan beberapa halaman sekaligus.Untuk menggunakan external CSS kita harus mempunyai file .HTML dan .CSS

   File .HTML


         <html>
        <head>
              <title> Fitria Fajar Arianingsih  </title>
                <link rel="stylesheet" href="file.css"/>
        <body>
             saya sedang membuat tugas wiriting and presentation 
        <h1>Hai !!</h1>
         </body>
          </html>
          
      
    File .CSS


              body {
                 color: red;
                 background-color: black;
               }
              h1 {
                color: green;
                }
                
               
- Internal CSS
Internal CSS adalah kode CSS yang ditulis dalam tag<style> dan kode HTML yang ditulis di bagian header file HTML. Internal CSS digunakan untuk membuat tampilan pada satu halaman website dan tidak digunakan di halaman website yang lain.
  
  
            <html>
            <head>
            <title> Fitria Fajar Arianingsih  </title>
               <style>
                  body {
                    color: white;
                    background-color: black;
                  }
                   h1 {
                    color: green;
                  }
               </style>
            <body>
                  saya sedang membuat tugas wiriting and presentation 
            <h1>Hai !!</h1>
              </body>
              </html>
              
              
### 3. CSS Syntax
CSS Syntax adalah syntax yang digunakan untuk menunjuk atau memilih HTML element mana yang ingin diberi style (dihias). CSS syntax terdiri dari selector, property, dan value. CSS memiliki syntax yang sederhana dan menggunakan sejumlah kata kunci berbahasa Inggris untuk menentukan nama-nama berbagai properti. CSS memiliki dua aturan utama, yaitu Selector dan Declaration.
              
              
              h1 {
                  background-color: royalblue;
                 }
              
           
  Keterangan :
   **h1** merupakan selector yang nantinya akan mengalami perubahan pada HTML.
   **backgruond-color** merupakan sebuah property. Property adalah atribut style yang ingin dirubah, misalnya color, background, margin, dll.
   **royalblue** merupakan value atau nilai dari suatau property.
              
 ### 4. Flexbox
flexbox merupakan mode layout yang ada di CSS3 dan digunakan untuk mengatur elemen di suatu halaman web. Flexbox ini akan mengatur ukuran dari elemen anaknya secara    otomatis, dan mampu beradaptasi dengan ukuran container-nya. Contohnya Properti align-content 
              
              
         align-content: stretch;
  
              
 ALGORITMA           
---------------
### 1. Pengertian Algoritma
Algoritma adalah deskripsi berupa step-step yang dibutuhkan untuk menyelesaikan suatu masalah dengan rangkaian terbatas dari instruksi-instruksi yang rumit, yang biasanya digunakan untuk menyelesaikan atau menjalankan suatu kelompok masalah komputasi tertentu. Algoritma digunakan sebagai spesifikasi untuk melakukan perhitungan dan pemrosesan data.
### 2. Perbedaan Algoritma 
Algoritma memberikan langkah-langkah yang dilakukan untuk menyelesaikan masalah, sedangkan struktur data mengatur data yang dibutuhkan dalam memori (mengorganisasi data).
### 3. Manfaat Algoritma
   -Menjadi tidak bergantung dengan bahasa pemrograman.
              
   -Dapat membuat notasi algoritma yang dapat diterjemahkan ke dalam bahasa pemrograman apapun.
              
   -Cara berpikir dan analisis menjadi lebih kuat.
              
   -Membuat kita menjadi lebih berpikir panjang untuk menyelesaikan suatu masalah dengan cara seefektif mungkin.
              
### 4. Kualitas Wajib Algoritma
   -Input dan output harus didefinisikan terlebih dahulu dengan tepat.
              
   -Setiap step harus benar-benar clear dan tidak ambigu.
              
   -Algoritma seharusnya tidak mengandung suatu code pada bahasa pemograman tertentu. Algoritma harus dibuat agar dapat digunakan dalam bahasa pemograman apapun.
           
### 5. Algoritma Sederhana
  -Contoh algoritma untuk menghitung luas persegi panjang adalah

              
    Masukkan panjang (p)
    Masukkan lebar (l)
    Menghitung luas persegi panjang yaitu panjang * lebar (p*l)
    Tampilkan luas persegi panjang             
              
              
### 6. Pseudocode     
Pseudocode atau kode semu dapat diartikan sebagai deskripsi dari algoritma pemrograman yang dituliskan secara sederhana dibandingkan dengan sintaksis bahasa pemrograman. Tujuannya, agar lebih mudah dibaca dan dipahami manusia. Setelah mengetahui pengertian dan fungsi dari pseudocode, kamu juga harus mengetahui notasi apa saja yang digunakan untuk mengetahui proses yang terjadi. Berikut ini adalah beberapa notasinya.

  -INPUT
   Digunakan untuk menunjukan proses memasukan suatu isi variabel.

  -OUTPUT
   Digunakan untuk menunjukan proses keluaran yang terjadi.

  -WHILE
   Digunakan untuk sebuah perulangan yang memiliki iterasi awal.

  -FOR
   Digunakan untuk sebuah perulangan perhitungan iterasi.

  -REPEAT – UNTIL
   Digunakan untuk sebuah perulangan yang memiliki kondisi akhir.

  -IF – THEN – ELSE
   Digunakan untuk mengambil sebuah keputusan dari beberapa kondisi.
             
              
              deklarasi
              var number : integer

              algortima:
                  INPUT number
              if (number % 2 = 0) THEN 
                   OUTPUT "genap"
              else 
                   OUPUT "ganjil"
              
              

### 7. Penerapan Algoritma Dengan Java script 
              
              
              
              for(let i = 0; i < 10; i++){
                document.write("<p>Perulangan ke-" + i + "</p>")
                }
                                    
                                    
### 8. Pendekatan dan Penyelesaikan Suatu Masalah Melalui Program    
  - Procedural 
    Procedural adalah cara berpikir secara runtun. Artinya serangkaian perintah yang berurutan.
                       
                                    
                                    
                STORE "width" with any value
                STORE "height" with any value
                STORE "area" without any value

                CALCULATE "width" times "height"
                SET "area" value with calculation result
                DISPLAY "area"
 
                                    
 
 - Conditional
 Conditional digunakan saat dibutuhkan percabangan kasus. Komputer akan melakukan suatu tindakan jika suatu kondisi terpenuhi. 

   Jika hari ini tidak hujan, maka Bob pergi ke pasar, jika tidak maka Bob dirumah aja.
   Jika tidak terpenuhi, maka tidak akan dijalankan.
                                    
 - Looping 
 Komputer dapat melakukan sebuah proses yang sama berulang-ulang. Jika membutuhkan perulangan dalam kasus tertentu, kita bisa menggunakan Looping.
                                    
 - Recursive
 Recursive adalah pola pikir dalam algoritma yang memanggil method/function didalam sebuah function.    
                                    
 
JAVASCRIPT                                    
---------------         
### 1. Pengertian JAVASCRIPT
Javascript adalah bahasa pemograman yang sangat powerful yang digunakan untuk logic pada sebuah website, Javascript juga dapat membuat website menjadi interaktif dan dinamis  
### 2. Syntax dan Statement
Syntax bisa dianalogikan seperti kosa kata (vocabulary) dan tata cara (grammar) pada bahasa pemograman.
Kita menggunakan syntax tertentu untuk membuat statement program, instruksi untuk djalankan/dieksekusi oleh web browser, compiler, ataupun intrepreter
contohnya:
  - Alert()
    alert() biasanya digunakan untuk menampilkan sebuah pesan peringatan atau informasi.
                                    
                                    
                                    alert("Hai Saya Fitria ");
                                   
                                    
 - Prompt() 
   prompt() berfungsi untuk mengambil sebuah inputan dari pengguna.   
                                    
                                    
                                    var nama = prompt("Siapa nama kamu?", "");
                                    document.write("<p>Hello "+ nama +"</p>");
                                    
                                    
  - confirm()
    confirm() digunakan untuk melakukan konfirmasi dalam melakukan tindakan tertentu.  
                                    
                                    
                                    confirm("apakah anda yakin untuk mengumpulkan tugas ?");
                                    
                                    
 ### 3. Tipe Data Pada JAVASCRIPT
 Tipe data adalah klasifikasi yang kita berikan untuk berbagai macam data yang digunakan dalam programming.
                                    
  - number
                                    
     Tipe data number adalah tipe data yang mengandung semua angka termasuk angka desimal.
                                    
  - string
                                    
    Tipe data string adalah grup karakter yang ada pada keyboard laptop/PC kita yaitu letters (huruf), number (angka), spaces (spasi), symbol, dan lainnya.
Harus diawali dan diakhiri dengan single quotes ‘ … ‘ ataupun double quotes “ … “     
                                    
  - boolean
                                    
     Tipe data boolean adalah tipe data yang hanya mempunyai 2 buah nilai.2 buah nilai tersebut adalah TRUE (benar) or FALSE (salah).
Analoginya adalah seperti tombol/button ON/OFF dan juga seperti sebuah jawaban antara YES/NO.
                                    
  - null
                                    
    Tipe data null adalah tipe data yang diartikan bahwa sebuah variable/data tidak memiliki nilai. Null berbeda dengan string kosong. String kosong masih memiliki tipe data string.
                                    
  - undefined
                                    
    Tipe data undefined adalah tipe data yang merepresentasikan varibel/data yang tidak memiliki nilai.
Undefined berbeda dengan null.
Nilai dari pemanggilan variabel yang belum didefinisikan
Nilai dari pemanggilan element array yang tidak ada
Nilai dari pemanggilan property objek yang tidak ada
Nilai dari pemanggilan fungsi yang tidak mengembalikan nilai (return)
Nilai dari parameter fungsi yang tidak memiliki argumen
                            
   - object
                                    
      Tipe data object adalah koleksi data yang saling berhubungan (related). Tipe data pbject dapat menyimpan data dengan tipe data apapun (number, string, boolean, dan lainnya).Tipe data object mempunyai key dan value.
                              
 
### 4. Operator di JAVASCRIPT
  - Opeartor Aritmatika pada Javascript
Operator aritmatika merupakan operator untuk melakukan operasi aritmatika seperti penjumlahan, pengurangan, pembagian, perkalian, dsb.
                                    Tambah (+)
                                    Kuramg (-)
                                    Perkalian (*)
                                    Pembagian (/)
                                    Modulus (%) Modulus adalah hasil dari sisa bagi.
                                    
                                    
 - Comparison/Perbandingan operator
                                    
                                    
                                    Lebih kecil dari : <
                                    Lebih besar dari: >
                                    Lebih kecil atau sama dengan: <=
                                    Lebih besar atau sama dengan: >=
                                    Sama dengan: ===
                                    Tidak sama dengan: !==
              
              
- Opeartor Logika 
  Logical operator biasa digunakan untuk sebuah CONDITIONAL pada pemograman. Menghasilkan nilai BOOLEAN yaitu TRUE or FALSE.
              
              
              
                                     AND operator : &&
                                     OR operator: ||
                                     NOT operator: !

              
              
### 5. Control Flow (conditional dan looping)      
  #### Conditional   
Conditional merupakan statement percabangan yang menggambarkan suatu kondisi. Conditional statement akan mengecek kondisi spesifik dan menjalankan perintah berdasarkan kondisi tersebut Yang dicek adalah apakah kondisi tersebut TRUE (benar). Jika TRUE maka code didalam kondisi tersebut dijalankan.
Contoh Conditional dalam kehidupan :
Jika cuaca cerah hari ini, maka kita akan pergi keluar
Jika alarm berbunyi, maka kita akan bangun dari tidur
              
              
              Contoh Conditional  IF Statement
              if (ture) {
                console.log ('akan diterima ')  ;
                }
              if (false) {
                 console.log ('tidak diterima');
                }
              
              
             Contoh Conditional IF … ELSE Statement IF 
             var buah = "jeruk";
             if( buah == "jeruk" ) {
                document.write("<b>Kamu suka buah jeruk</b>");
              } else if( buah == "salak" ) {
                document.write("<b>Kamu suka buah salak</b>");
              } else if( buah == "manggis" ) {
                document.write("<b>Kamu suka buah manggis</b>");
             } else {
                 document.write("<b>Kamu tidak suka buah, mungkin kamu suka daging.</b>");
             }



              
  - Truthy and Falsy 
    Digunakan untuk mengecek apakah variabel telah terisi namun tidak mementingkan nilainya.
    - Falsy
Sebuah nilai yang dievaluasi menjadi nilai False oleh JavaScript. Hanya ada enam nilai yang dievaluasi menjadi False, atau bersifat falsy, oleh JavaScript, yaitu:
              
              
              false
              0 (nol)
              "", string kosong
              null
              undefined
              NaN
             
              
- Truthy
Sebuah nilai yang dievaluasi menjadi nilai true di JavaScript. Ada banyak nilai yang dievaluasi menjadi true, bersifat truthy hanya perlu memahami keenam nilai yang bersifat falsy. Selebihnya, nilai apapun selain keenam nilai tersebut bersifat truthy.
              
- Switch Case Conditional
Gunakan switch case jika kondisi dan percabangan terlalu banyak
              
              
              
                    switch (nilai) {
                       case variabel1:
                       pernyataan akan di eksekusi, bila nilai = variabel1
                    break;
              
              
- Ternary Operator
Ternary operator merupakan short-syntax dari statement if … else.
              
              
              Bentuk Code Statement If-Else Secara Umum:
                      $nilai = 9;
                      if ($nilai > 8) {
	                    echo 'Sangat Baik';
                      } else {
                          	echo 'Baik';
                      }
              
              
              Penggunaan Ternary Operator:
                      $nilai = 9;
                      echo $nilai > 8 ? 'Sangat Baik' : 'Baik'; // Baik
                    case variabel2:
                    pernyataan akan di eksekusi, bila nilai = variabel2
                    break;
                    ...
                    default:
                    pernyataan akan di eksekusi, bila tidak ada variabel yang sama dengan nilai
                    } 
              

                                   
  #### Looping
    Looping adalah statement yang mengulang sebuah instruksi hingga kondisi terpenuhi atau jika kondisi stop/berhenti tercapai.
              
  - FOR LOOP 
    For Loop merupakan instruksi pengulangan yang dapat kita berikan pada program yang kita kembangkan. Gunakan FOR LOOP jika kita tahu seberapa banyak nilai pasti untuk pengulangannya
              
  - FOR LOOP PARAMETER
    Inisialisasi: Sebagai inisialisasi awal dari mana mulainya sebuah pengulangan. Kita memberikan nilai awal/default pada parameter ini.
    Condition: For loop akan terus berjalan selama kondisi ini terpenuhi. Selama kondisi bernilai TRUE. 
    Post-expression (Increment/Decrement): Iterasi statement yang digunakan untuk mengupdate variabel yang menjadi kontrol pada pengulangan.

  - WHILE LOOP 
    While Loop akan menjalankan instruksi pengulangan kondisi bernilai TRUE. Gunakan WHILE LOOP jika kita tidak mengetahui jumlah pasti pengulangan.
              
  - Nested Loop
    Jika kita membuat looping didalam looping. Maka ini dinamakan Nested Loop.
    Looping pertama dianalogikan sebagai baris.
    Looping kedua dianalogikan sebagai kolom.
              
  - DO WHILE
    Perulangan do/while akan melakukan perulangan sebanyak 1 kali terlebih dahulu, lalu mengecek kondisi yang ada di dalam kurung while .
       
              
