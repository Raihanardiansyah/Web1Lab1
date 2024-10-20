# laporan praktikum

## Membuat repository

### Membuat akun github

pertama tama yang pasti kalian harus membuat akun gituhub terlebih dahulu, buatlah akun pada github.com
apabila sudah membuat/memiliki akunnya silahkan login dan akan adatampilan profil seperti ini:

![gambar 1](Profil.png)

### Membuat file
setelah itu silahkan kembalik ke menu home dan nekan menu NEW:

![gambar](repositories.png]

setelah setelah di tekan silakhkan isi nama dari file repository dan pilih menu publik dari 2 menu tersebut,
lalu tekan Create Repository :

![Gambar](part1.png)

## Membuat flowchart untuk menghitung 3 bilangan untuk menetukan bilangan terbesar

Pertama tama yang pasti kalian harus membuat flowchatr terlebih dahulu seperti gambar di bawah :

![image](Flowchart.png)

### Langkah langkah dalam flowchatr

1. Mulai: Titik awal proses.

2. Input Bilangan: Minta pengguna untuk memasukkan tiga bilangan (misalnya A, B, C).

3. Bandingkan A dan B:

Jika A > B, lanjut ke langkah berikutnya.
Jika B >= A, lanjut ke langkah 5.

4. Bandingkan A dan C:

Jika A > C, maka A adalah yang terbesar.
Jika C >= A, maka C adalah yang terbesar.
Setelah itu, output hasil dan selesai.

5. Bandingkan B dan C:

Jika B > C, maka B adalah yang terbesar.
Jika C >= B, maka C adalah yang terbesar.
Setelah itu, output hasil dan selesai.

4. Output Hasil: Tampilkan bilangan yang terbesar.

7. Selesai: Titik akhir proses.

Flowchart untuk menghitung tiga bilangan dan menentukan bilangan terbesar biasanya terdiri dari beberapa langkah yang sistematis. Berikut adalah penjelasan mengenai proses tersebut:

1. Inisialisasi: Proses dimulai dengan mendefinisikan tiga bilangan yang akan dibandingkan, misalnya A, B, dan C. Input untuk bilangan ini dapat dilakukan secara manual atau melalui sistem.

2. Perbandingan Pertama: Langkah selanjutnya adalah membandingkan bilangan A dan B.

Jika A lebih besar daripada B, maka A adalah kandidat terbesar saat ini.
Jika B lebih besar atau sama dengan A, maka B menjadi kandidat terbesar.

3. Perbandingan Kedua: Setelah menentukan kandidat terbesar antara A dan B, langkah berikutnya adalah membandingkan kandidat tersebut dengan bilangan C.

Jika kandidat (A atau B) lebih besar daripada C, maka kandidat tersebut tetap sebagai bilangan terbesar.
Jika C lebih besar daripada kandidat, maka C menjadi bilangan terbesar.

4. Output: Setelah semua perbandingan selesai, hasil akhirnya adalah bilangan yang terpilih sebagai terbesar di antara ketiga bilangan tersebut. Proses ini diakhiri dengan menampilkan hasil kepada pengguna.

### Program phyton untuk mengitung 3 bilangan untuk menentukan bilangan terbesar

di sini saya memiliki program untuk menghitung 3 bilangan untuk menentukan bilangan terbesar,
di contoh saya menggunakan bilangan A yang saya isi dengan 20 dan B dengan 40 Dan C dengan 50, di bawah ini adalah contoh :

![image](program.png)

dan di bawah inilah penejelasan daro program tersebut :

1. Input Bilangan:

- a = float(input("Masukkan bilangan A: ")): Meminta pengguna untuk memasukkan bilangan A dan mengonversinya menjadi tipe data float.

- b dan c: Dikerjakan dengan cara yang sama untuk bilangan B dan C.

2. Menentukan Bilangan Terbesar:

- Struktur Kondisional: Menggunakan if, elif, dan else untuk membandingkan ketiga bilangan.

- if a >= b and a >= c:: Mengecek apakah A lebih besar atau sama dengan B dan C. Jika ya, A adalah yang terbesar.

- elif b >= a and b >= c:: Jika kondisi sebelumnya tidak terpenuhi, memeriksa apakah B lebih besar atau sama dengan A dan C. Jika ya, B adalah yang terbesar.

- else:: Jika tidak ada kondisi di atas yang terpenuhi, maka C adalah yang terbesar.

3. Output Hasil:

4. print("Bilangan terbesar adalah:", terbesar): Menampilkan bilangan terbesar yang telah ditentukan di langkah sebelumnya.

### Cara Kerja Program

- Program ini meminta pengguna untuk memasukkan tiga bilangan.

- Dengan menggunakan logika perbandingan, program menentukan bilangan terbesar di antara ketiga bilangan tersebut.

- Hasilnya kemudian ditampilkan kepada pengguna.

### Contoh Penggunaan

Jika pengguna memasukkan:

A = 20
B = 40
C = 50

maka output yang di keluarkan adalah 

Bilangan Terbesar adalah: 50
>>>>>>> acc394c8d4d063cd14bedb2d3d8e424a595d314b
