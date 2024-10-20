# laporan praktikum

## Membuat repository

### Membuat akun github

pertama tama yang pasti kalian harus membuat akun gituhub terlebih dahulu, buatlah akun pada github.com
apabila sudah membuat/memiliki akunnya silahkan login dan akan ada tampilan profil seperti ini:

![Gambar1](Png/Profil.png)

### Membuat file
setelah itu silahkan kembalik ke menu home dan nekan menu NEW:

![Gambar1](https://github.com/Raihanardiansyah/Web1Lab1/blob/main/Png/Repositories.png?raw=true)

setelah setelah di tekan silakhkan isi nama dari file repository dan pilih menu publik dari 2 menu tersebut,
lalu tekan Create Repository :

![Gambar1](https://github.com/Raihanardiansyah/Web1Lab1/blob/main/Png/Part1.png?raw=true)

![Gambar1](https://github.com/Raihanardiansyah/Web1Lab1/blob/main/Png/Part2.png?raw=true)

### memasang git tools

kaliana harus download terlebih dahulu  Git Tool dengan melakuan percarian di chrome "Gistscm",
lau tekan download for windows.

![Gambar 1](https://github.com/Raihanardiansyah/Web1Lab1/blob/main/Png/Gitscm.png?raw=true)

lalu tekan click here to download

![Gambar1](https://github.com/Raihanardiansyah/Web1Lab1/blob/main/Png/GitscmD.png?raw=true)

setelah itu kalian masuk ke proses penginstalan git tools yang sudah kalian download lalu klik next teruh hingga tampilannya berubah lalu tekan instal,
tunggu hingga proses penginstalan selesai hingga tampilannya seperti ini: lalu centang kedua pilihan tersebut.

![Gambar1](https://github.com/Raihanardiansyah/Web1Lab1/blob/main/Png/finish.png?raw=true)

### mengoperasian Git Tools

setelah selesai melakukan penginstalan maka tampilannya akan seperti ini:

![Gambar1](https://github.com/Raihanardiansyah/Web1Lab1/blob/main/Png/Pwd.png?raw=true)

nah kalian masukan kode kode tersebut, kode tersebut yang berupa "pwd" adalah untuk memeriksa data file sebelum memulai ke langkah berikutnya,
selanjutnya kalian kembali ke dalam web github untuk mengcopy link repository yang sudah kalian buat, tekan kolom "Code" lalu salin code tersebut :

![Gambar](https://github.com/Raihanardiansyah/Web1Lab1/blob/main/Png/link.png?raw=true)

lalu kembali ke fit tools dan lanjutkan dengan code "git clone copy link yang tadi", lalu cari file README.md pada file Web1La1:

![Gambar1](https://github.com/Raihanardiansyah/Web1Lab1/blob/main/Png/file.png?raw=true)

lalu buka file README.md dengan vs code mkan tampolan dari README.md kalian akan seperti ini:

![Gambar1](https://github.com/Raihanardiansyah/Web1Lab1/blob/main/Png/vscode.png?raw=true)

lalu kalian buat file baru:

![Gambar1](https://github.com/Raihanardiansyah/Web1Lab1/blob/main/Png/newfile.png?raw=true)

lalu ganti mendaji Python:

![Gambar](https://github.com/Raihanardiansyah/Web1Lab1/blob/main/Png/py.png?raw=true)

dan save sesuai dengan kemauan kalian senidiri:

![Gambar1](https://github.com/Raihanardiansyah/Web1Lab1/blob/main/Png/save.png?raw=true)

## Membuat flowchart untuk menghitung 3 bilangan untuk menetukan bilangan terbesar

Pertama tama yang pasti kalian harus membuat flowchatr terlebih dahulu seperti gambar di bawah :

![Gambar1](Png/Flowchart.png)

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

![Gambar1](https://github.com/Raihanardiansyah/Web1Lab1/blob/main/Png/vscode1.png?raw=true)

dan di bawah inilah penejelasan daro program tersebut :

1. Input Bilangan:

- a = int(input("Masukkan bilangan A: ")): Meminta pengguna untuk memasukkan bilangan A dan mengonversinya menjadi tipe data int.

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

### Selesai
