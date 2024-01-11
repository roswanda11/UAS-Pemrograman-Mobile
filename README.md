# Final Project : Ujian Akhir Semester

<h1 align="center"> UAS Rosé App</h1>

<table>
  <tr>
    <th colspan="2">DATA MAHASISWA</th>
  </tr>
  <tr>
    <td>Nama</td>
    <td>Roswanda Nuraini</td>
  </tr>
  <tr>
    <td>NIM</td>
    <td>312210328</td>
  </tr>
  <tr>
    <td>Kelas</td>
    <td>TI.22.A3</td>
  </tr>
  <tr>
    <td>Mata Kuliah</td>
    <td>Pemrograman Mobile</td>
  </tr>
</table>

## Logo Rosé App

![logowanda](https://github.com/roswanda11/Implicit-Intent/assets/115516632/a59cdac0-6ec7-46e3-ac8a-5b68580f4b0e)

## Demo Aplikasi

https://github.com/roswanda11/pm/assets/115516632/07c9ced3-2a3d-49a4-9110-3a372423acc2

## **Daftar Isi**
**[Tampilan & Menu Aplikasi](#tampilan--menu-aplikasi)**<br>
**[Link Demo Aplikasi](https://drive.google.com/drive/folders/10nI-5LB052D7TD2CJVZSv6rpYIuCmbFq)**<br>
**[Link PDF Langkah-Langkah Pembuatan Aplikasi](https://drive.google.com/drive/folders/1fjt5BtepI-f59jkyB4LsD7zbjOaEL8il)**

## **Tampilan & Menu Aplikasi**

![tampilanmenuapp-wanda](https://github.com/roswanda11/pm/assets/115516632/2f3481df-fca0-4f6d-907d-80ceeb8db995)

## **Launcher Splash**

![launchersplashwanda](https://github.com/roswanda11/pm/assets/115516632/2a9c5640-0405-4104-86ba-9a6b2ee03d46)

Terdapat 7 menu pada aplikasi, diantaranya:
###  1. **Hello** <br>
Ini adalah program yang hanya menampilkan teks pada aplikasi. Disini teksnya adalah "Bagaimana kabar anda hari ini?". <br>

![hellowanda](https://github.com/roswanda11/pm/assets/115516632/7c76eee4-1845-4617-a7af-75eec97d60b1)

https://github.com/roswanda11/pm/assets/115516632/68ad6f9f-8bf4-46fd-8143-dab8105ab563

### 2. **Count** <br>
Count adalah program yang menampilkan perhitungan tambah 1 bisa juga disebut program Toast.

### 3. **Maps** <br>
Maps adalah program yang menampilkan tampilan maps dari aplikasi Google Maps, program ini menerapkan fungsi Implisit. Implisit intent memungkinkan Anda meminta sistem Android untuk menemukan aplikasi yang sesuai untuk menangani tugas tertentu, dalam hal ini menunjukkan lokasi di peta.

https://github.com/roswanda11/pm/assets/115516632/d2398757-e5c1-4268-86ee-98733fa000d8

### 4. **News** <br>
News adalah program yang menampilkan tampilan seperti Artikel dari sebuah berita. Berita disini adalah tentang **"Ice Cold"**.

![newsswandaa](https://github.com/roswanda11/pm/assets/115516632/2cd45f09-3557-42a9-af57-44d89d319983)

https://github.com/roswanda11/pm/assets/115516632/d9476aa1-5f5d-4d31-84b6-7fe04ff62715

### 5. **Alarm** <br>
Alarm adalah program yang menampilkan alarm menggunakan fungsi dari **AlarmManager**. **AlarmManager** adalah komponen sistem Android yang memungkinkan Anda menjadwalkan dan mengeksekusi kode pada waktu tertentu, baik itu dalam waktu segera, satu kali, atau berulang.

![alarmwandaaa](https://github.com/roswanda11/pm/assets/115516632/4b32e568-9b07-4b46-935e-93ce5dc6e069)

https://github.com/roswanda11/pm/assets/115516632/36a06e7e-5941-4478-bc14-64f2ce5014d3

### 6. **Fibonacci** <br>
Fibonacci Sequence (Deret angka Fibonacci) adalah deret angka yang diperoleh dengan menjumlahkan dua angka didepannya / sebelumnya:<br>

      1, 1, 2, ... 1 + 2 = 3 ( 1, 1, 2, 3, ... ) 2 + 3 = 5 ( 1, 1, 2, 3, 5, ... ) 3 + 5 = 8 ( 1, 1, 2, 3, 5, 8, ... )

**- Mode Perhitungan**  
Terdapat 2 Mode pada aplikasi fibonacci tersebut yakni:<br>
- Limited-Mode : harus memasukkan limit/batas terlebih dahulu baru bisa melakukan perhitungan.
- Unlimited-Mode : tanpa harus memasukkan limit/batas untuk melakukan perhitungan.<br>

**- Limit/Batas Perhitungan**  
Arti limit/Batas disini adalah User bisa membatasi perhitungan fibonacci dibaris keberapa contoh user menginputkan 12 maka perhitungan fibonacci akan berhenti pada nilai 144 karna nilai 144 adalah baris ke-12 dalam perhitungan fibonacci.<br>

**- Perhitungan Naik (Count Up) dan Perhitungan Turun (Count Down)**  
Yaitu perhitungan bisa dilakukan naik (Count Up) dan Perhitungan bisa dilakukan menurun (Count Down), maksudnya adalah pada saat user melakukan perhitungan naik smpai nilai 21 daln jika user melakukan perhitungan turun sekali maka akan mundur satu baris, nilainya menjadi 13 karna nilai sebelum 21 adalah 13.<br>

**- Reset**  
Yaitu semua nilai terkait Fibonacci diatur kembali ke nilai awal, dan tampilan diperbarui.<br>

### Tampilan UI
    Saya mempunyai 3 button dan 1 edit text :
    - edit text untuk user dapat menginput memberikan maksimal angka fibonacci
    - button max untuk membatasi angka maksimal yg sudah di input pada edit text
    - button count untuk menambah angka fibonacci untuk mencapai nilai maksimalnya
    - button back untuk mereset angka fibonacci dan inputan max menjadi 0

Penjelasan Menampilkan Angka Fibonacci

    Membuat Objek Toast:
    Toast adalah suatu fitur di Android yang digunakan untuk menampilkan Angka Fibonacci ditengah layar.
    Toast.makeText(this, R.string.toast_message, Toast.LENGTH_SHORT); membuat pesan dengan durasi singkat. 
    Pesan yang ditampilkan diambil dari resource string yang diidentifikasi oleh R.string.toast_message.

    Menampilkan Toast:
        toast.show(); digunakan untuk menampilkan Toast yang telah dibuat sebelumnya.

    Mengatur Teks pada Elemen Tampilan:
        showHitung.setText(Integer.toString(1)); Menampilkan Angka Fibonacci menjadi "1" pada saat awal.
        Integer.toString(1) digunakan untuk mengonversi angka 1 menjadi string, karena setText membutuhkan parameter berupa string.

Penjelasan ButtonMax

    Mengambil Teks dari Elemen Tampilan:
    inputCount.getText().toString(); mengambil teks dari EditText yang telah di input user dan menyimpannya dalam bentuk string.

    Memeriksa String Tidak Kosong:
        if (!maxCountString.isEmpty()) memeriksa apakah EditText tidak kosong. Jika tidak kosong, maka melanjutkan ke langkah berikutnya.

    Mengonversi String ke Integer:
        int newMaxCount = Integer.parseInt(maxCountString); mengonversi string yg telah di input di EditText menjadi integer (bilangan bulat).

    Memeriksa Nilai Integer Baru:
        if (newMaxCount >= 0) memeriksa apakah nilai integer baru tidak kurang dari 0.

    Mengatur Nilai Maksimum (maxCount):
        maxCount = newMaxCount; jika semua kondisi terpenuhi, nilai maksimum (maxCount) diatur menjadi nilai integer baru (newMaxCount).

Penjelasan ButtonBack

    fib1 dan fib2 diatur ke 1
        fib1 dan fib2 membuat bilangan yg sudah ditambah menjadi 1.

    maxCount diatur ke 0.
       batas maksimum Angka Fibonacci menjadi 0.

    maxCountSet diatur ke false.
       batas maksimum angka Fibonacci menjadi false atau belum dimasukkan
       
    Teks pada elemen inputCount dikosongkan.
        Mengosongkan EditText atau inputan maksimal untuk angka Fibonacci

    Teks pada elemen showHitung diatur menjadi "0".
       Menampilkan Angka Fibonacci menjadi 0

Penjelasan ButtonCount

    Mengambil Nilai Input:
        maxCountString mengambil nilai input dari EditText yang telah di input.

    Memeriksa Input Tidak Kosong:
        Memeriksa apakah EditTExt tidak kosong.

    Mengonversi Input menjadi Integer:
        Mengonversi nilai Inputan maksimalnya menjadi integer.

    Menghitung Fibonacci Berikutnya:
        Menghitung nilai Fibonacci berikutnya (nextFib).

    Memeriksa Kondisi:
        Melakukan beberapa pengecekan kondisi terkait nilai maxCount, fib1, dan nextFib.

    Memperbarui Nilai dan Menampilkan:
        Memperbarui nilai fib1 dan fib2 tergantung pada kondisi.
        Menampilkan nilai terbaru pada elemen tampilan showHitung.


**- Tampilan Baris Fibonacii**  
Yaitu menampilkan baris berapa dalam perhitungan fibonacci saat ini.

![fibonacciwanda](https://github.com/roswanda11/pm/assets/115516632/5ee034aa-381c-464a-83d9-f8547262be5b)

https://github.com/roswanda11/pm/assets/115516632/2b10bb6b-069c-4f56-a4a9-92fb77b9d247

### 7. **Chat** <br>
Chat adalah program yang terdapat 2 fungsi yaitu mengirim pesan dan membalas pesan tetapi ini hanya implementasi dari program **Two Activity**.

![activity1wandaa](https://github.com/roswanda11/pm/assets/115516632/b611ccc9-e7fd-4e12-9f91-63ee4e77c5dd)

![activity2wanda](https://github.com/roswanda11/pm/assets/115516632/31c3f226-ed7c-4bc5-ad07-c6fdf8a7775c)

https://github.com/roswanda11/pm/assets/115516632/c7804534-1514-42fd-9131-4d408a30504c

### 8. **Movie** <br>
Movie adalah program yang dibuat untuk mengimplementasikan fungsi **Fragment** dalam program movie yang saya buat ini terdapat beberapa Fragment dan fitur, diantaranya:<br>
**Menu-Buttom**<br>
- **Home**<br>
    adalah fragment yang menampilkan tampilan utama yang berisikan poster-poster dari sebuah film.

**Menu-Sidebar**
- **Home**<br>
    adalah fragment yang menampilkan tampilan utama yang berisikan poster-poster dari sebuah film.

- **Settings**<br>
    adalah fragment yang berisikan pengaturan sistem apliksi dan pengaktifan fitur dan lain sebagainya.

![fragmenteyelinerwanda](https://github.com/roswanda11/pm/assets/115516632/d9569ec1-2d3c-420d-8fc9-bfb1ad17efe2)

![fragmentlipcreamwanda](https://github.com/roswanda11/pm/assets/115516632/721be209-4713-4a27-aabc-639f05634219)

![fragmenteyebrowwanda](https://github.com/roswanda11/pm/assets/115516632/b8de1277-2f04-4693-8358-c275fc525e47)

https://github.com/roswanda11/UAS-Pemrograman-Mobile/assets/115516632/7c5819fe-039c-4d37-8d29-c2ce47ddddc2

