# Sistem Persamaan Linier

## A. Pengertian, Ciri - Ciri dan Jenis - Jenis Sistem Persamaan Linier <br>
1. Definis Sistem Persamaan Linier
  Sitem Persamaan Linier adalah variabel yang mempuyai pangkat satu atau tidak lebih dan tidak mempunyai akar. Sistem Persamaan Linier bisa di artikan sebagai suatu persamaan aljabar.
2. Ciri-ciri Sistem Persamaan Linier
* Variabelnya hanya memiliki pangkat satu dan tidak lebih (tidak memiliki pangkat)
* Variabelnya tidak memiliki akar
3. Jenis-jenis Sistem Persamaan Linier
* Persamaan Linier Satu Variabel
Persamaan linier satu variabel adalah persamaan linier yang hanya memiliki satu variabel saja, contohnya
```
ax + b = 0
```
* Persamaan Linier Dua Variabel
Persamaan linier dua variabel adalah persamaan linier yang memiliki dua variabel, contohnya
```
ax + by + c = 0
```
* Persamaan Linier Tiga Variabel
Persamaan linier tiga variabel adalah persamaan linier yang memiliki tiga variabel, contohnya
```
ax + by + cz =0
```

## B. Solusi Penyelesaian Sistem Persamaan Linier 
Berikut adalah beberapa solusi penyelesaian sistem persamaan linier.
1. Penyelesaian Tunggal 
Sistem persamaan linier dengan penyelesaian tunggal terjadi ketika persamaan-persamaan dalam sistem tersebut saling berpotongan di satu titik saja.
* Syarat penyelesaian tunggal sebagai berikut : 
Determinan matriks koefisien atau tidak nol. 
* Cara menyelesaikannya : 
a. Metode Eliminasi : menghilangkan salah satu variabel dengan menjumlahkan atau mengurangkan kedua persamaan. 
b. Metode Subtitusi : memecahkan salah satu persamaan untuk satu variabel, lalu mensubtituskannya ke persamaan lain. 
c. Metode Matriks : menggunakan invers matriks koefisien untuk mencari nilai variabel.

<iframe scrolling="no" title="penyelesaian tunggal" src="https://www.geogebra.org/material/iframe/id/peerrkyt/width/1536/height/631/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/false/rc/false/ld/false/sdz/false/ctl/false" width="1536px" height="631px" style="border:0px;"> </iframe>

2. Tidak ada penyelesaian 
Sistem persamaan linier tidak memiliki penyelesaian jika persamaan - persamaan daldam sistem tersebut merepretasikan garis-garis yang paralel dan tidak berpotongan.
* Syarat tidak ada penyelesaian :
Sistem persamaan linier tidak memiliki penyelesaian jika determinan koefisien nol, tetapi konstanta pada ruas kanan tidak sebanding dengan koefisien variabel.

<iframe scrolling="no" title="tidak ada penyelesaian" src="https://www.geogebra.org/material/iframe/id/tfahwvyd/width/1536/height/631/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/false/rc/false/ld/false/sdz/false/ctl/false" width="1536px" height="631px" style="border:0px;"> </iframe>

3. Banyak penyelesaian 
Sistem persamaan linier memiliki banyak penyelesaian jika persamaan - persamaan dalam sistem tersebut merepresentasikan garis yang sama.
* Syarat banyak penyelesaian : 
a. Sistem persamaan linier memiliki banyak penyelesaian jika koefisien dan konstanta sebanding. 
b. Secara geometris, kedua persamaan menggambarkan garis yang berhimpit, sehingga setiap titik pada garis tersebut merupakan solusi.

<iframe scrolling="no" title="terdapat banyak penyelesaian" src="https://www.geogebra.org/material/iframe/id/cpqyuqwh/width/1536/height/631/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/false/rc/false/ld/false/sdz/false/ctl/false" width="1536px" height="631px" style="border:0px;"> </iframe>

## Eliminasi
Eliminasi adalah metode penyelesaian sistem persamaan linear dengan cara menghilangkan salah satu variabel.Dimana metode eliminasi secara garis besar akan menghapus atau menghilangkan satu variabel dalam persamaan tersebut. Metode ini dapat digunakan untuk menyelesaikan sistem persamaan linear dua variabel maupun tiga variabel.

Langkah-langkah metode eliminasi yaitu : 
a. Tentukan variabel yang akan dieliminasi
b. Samakan koefisien variabel yang akan dieliminasi
c. Jumlahkan atau kurangkan persamaan-persamaan untuk mengeliminasi variabel yang ditentukan 
d. Gunakan persamaan yang baru untuk mencari nilai variabel yang belum diketahui

### Eliminasi Gaus
Eliminasi Gauss adalah metode untuk menyelesaikan sistem persamaan linear (SPL) dengan mengubah persamaan menjadi matriks. Metode ini ditemukan oleh matematikawan Jerman Carl Friedrich Gauss (1777-1855). Tujuan utamanya adalah untuk mempermudah proses substitusi mundur dalam mencari solusi persamaan. Eliminasi Gauss dapat digunakan untuk menentukan determinan matriks tanpa memiliki suatu persyaratan.

### Solusi Grafik

Solusi grafik pada sistem persamaan linear adalah titik perpotongan kedua garis yang digambar dalam sistem koordinat yang sama.

Berikut langkah-langkah menyelesaikan sistem persamaan linear dengan metode grafik :
a. Gambarkan kedua persamaan dalam sistem koordinat yang sama. 
b. Tentukan titik potong salah satu persamaan linear dengan sumbu X atau sumbu Y.
c. Hubungkan kedua titik potong dengan garis lurus. 
d. Lakukan langkah 1 dan 2 untuk persamaan lain. 
e. Jika kedua garis berpotongan di (x,y) = (x1, y1), penyelesaian SPLD adalah x=x1 dan y=y1.

<iframe scrolling="no" title="Solving Linear Systems by Graphing: REVAMPED" src="https://www.geogebra.org/material/iframe/id/vyxxahhq/width/824/height/529/border/888888/sfsb/true/smb/false/stb/true/stbh/false/ai/false/asb/false/sri/false/rc/false/ld/false/sdz/false/ctl/false" width="824px" height="529px" style="border:0px;"> </iframe>