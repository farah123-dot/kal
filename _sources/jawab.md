---
title: 'Penyelesaian Sistem Persamaan '

---

## Penyelesaian Sistem Persamaan Linier 

### Operasi Baris Elementer 

### Eliminasi Gauss 

### Contoh Soal 1
Selesaikan dengan menggunakan eleminasi gauss

$$
\begin{array}{cc}
x_1+2x_2+3x_3&=6\\
2x_1+4x_2+6x_3&=12\\
x_3+x_2&=2
\end{array}
$$

Penyelesaian
Langkah 1: Tulis dalam Bentuk Matriks Augmented
Bentuk matriks augmented dari sistem ini adalah:

$$
\begin{bmatrix}
1&2&3&|6\\
2&4&6&|12\\
0&1&1&|2
\end{bmatrix}

Langkah 2: Eliminasi Baris
Kita akan menghilangkan elemen di bawah elemen utama di kolom pertama. Gunakan operasi:

$$
\begin{array}{cc}
R_2 \rightarrow R_2 - 2R_1
\end{array}
$$

Sehingga:

$$
\begin{bmatrix}
1&2&3&|6\\
0&0&0&|0\\
0&1&1&|2
\end{bmatrix}
$$

Langkah 3: Interpretasi
Baris kedua dirubah menjadi *0 = 0*

$$
\begin{aligned}
x_1+2x_2+3x_3&= 6\\
x_2+x_3&=2
\end{aligned}
$$

Langkah 4: Substitusi
Dari persamaan kedua:

$$
\begin{array}{cc}
x_2=2-x_3
\end{array}
$$

Substitusikan ke persamaan pertama:

$$
\begin{array}{cc}
x_1+2(2-x_3)+3x_3&=6\\
x_1+4-2x_3+3x_3&=6\\
x_1+4+x_3&=6\\
x_1=&2-x_3
\end{array}
$$

Kesimpulan
Solusi umum dari sistem ini adalah:

$$
\begin{aligned}
x_1&=2-x_3\\
x_2&=2-x_3\\
x_3&=x_3
\end{aligned}
$$

### Contoh Soal 2 
Selesaikan dengan menggunakan eliminasi gauss

$$
\begin{array}{cc}
x_1+x_2+x_3&=3\\
2x_1+x_3&=5\\
x_1+2x_2&=3
\end{array}
$$

Penyelesaian 
Langkah 1: Tulis dalam Bentuk Matriks Augmented

$$
\begin{bmatrix}
1&1&1&|3\\
2&0&1&|5\\
1&2&0&|3
\end{bmatrix}
$$

Langkah 2: Eliminasi Baris
Kita akan menghilangkan elemen di bawah elemen utama di kolom pertama.

$$
\begin{array}{cc}
R_2\rightarrow R_2 - 2R_1
\end{array}
$$

$$
\begin{array}{cc}
R_3 \rightarrow R_3 - R_1
\end{array}
$$

Sehingga matriks berubah menjadi:

$$
\begin{bmatrix}
1&1&1&|3\\
0&-2&-1&|-1\\
0&1&-1&|0
\end{bmatrix}
$$

Selanjutnya, buat elemen utama di baris kedua menjadi 1 dengan membagi baris kedua dengan -2:

$$
\begin{array}{cc}
R_2 \rightarrow \frac{R_2}{-2}
\end{array}
$$

Hasilnya:

$$
\begin{bmatrix}
1&1&1&|3\\
0&1&\frac{1}{2}&|\frac{1}{2}\\
0&1&-1&|0
\end{bmatrix}
$$

Kemudian eliminasi elemen di bawah elemen utama dengan:

$$
\begin{array}{cc}
R_3 \rightarrow R_3 - R_2
\end{array}
$$

Sehingga diperoleh

$$
\begin{bmatrix}
1&1&1&|3\\
0&1&\frac{1}{2}&|\frac{1}{2}\\
0&0&-\frac{3}{2}&|-\frac{1}{2}
\end{bmatrix}
$$

Langkah 3: Substitusi Balik*
Dari baris ketiga:

$$
\begin{array}{cc}
-\frac{3}{2}x_3=-\frac{1}{2}
\end{array}
$$

$$
\begin{array}{cc}
x_3 =\frac{1}{3}
\end{array}
$$

Dari baris kedua:

$$
\begin{array}{cc}
x_2+\frac{1}{2}x_3=\frac{1}{2}
\end{array}
$$

$$
\begin{array}{cc}
x_2+\frac{1}{2}\times\frac{1}{3}=\frac{1}{2}
\end{array}
$$

$$
\begin{array}{cc}
x_2+\frac{1}{6}=\frac{1}{2}
\end{array}
$$

$$
\begin{array}{cc}
x_2=\frac{1}{2}-\frac{1}{6}=\frac{3}{6}-\frac{1}{6}=\frac{2}{6}=\frac{1}{3}
\end{array}
$$

Dari baris pertama:

$$
\begin{array}{cc}
x_1+x_2+x_3=3
\end{array}
$$

$$
\begin{array}{cc}
x_1+\frac{1}{3}+\frac{1}{3}=3
\end{array}
$$

$$
\begin{array}{cc}
x_1=3-\frac{2}{3}=\frac{9}{3}-\frac{2}{3}=\frac{7}{3}
\end{array}
$$

Kesimpulan
Jadi, solusi dari sistem persamaan adalah:

$$
\begin{aligned}
x_1&=\frac{7}{3}\\
x_2&=\frac{1}{3}\\
x_3&=\frac{1}{3}
\end{aligned}
$$

### Contoh Soal 3 
Selesaikan dengan menggunakan eliminasi gauss

$$
\begin{array}{cc}
2x_1+2x_2&=6\\
x_1+x_2&=2
\end{array}
$$

### Contoh Soal 4 
Selesaikan dengan menggunakan eliminasi gauss

$$
\begin{array}{cc}
x_1+x_2&=5\\
x_1+2x_3&=6\\
\end{array}
$$
