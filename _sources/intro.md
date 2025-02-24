# Persamaan Linier
Persamaan linier adalah persamaan aljabar yang melibatkan variabel-variabel yang memiliki pangkat 1, atau dengan kata lain, tidak ada variabel yang dipangkatkan lebih tinggi dari satu (misalnya, tidak ada $ x^2, y^3 $, dan seterusnya). Persamaan linier dapat digambarkan dalam bentuk umum, yakni $ a_1 x_1 + a_2 x_2 + \ldots + a_n x_n = b $.

# Sistem Persamaan Linier

Sistem persamaan linier adalah sekumpulan dari beberapa persamaan linear yang diselesaikan secara bersama untuk menemukan nilai dan variabel yang belum diketahui

## Solusi Sistem Persamaan Linier
Solusi dari persamaan linier adalah nilai dari variabel yang membuat persamaan tersebut menjadi benar. Pada sistem persamaan linier, solusi ini adalah jika titik-titik yang mewakili persamaan-persamaan tersebut saling berpotongan. Solusi tersebut bisa berupa:

### 1. Satu solusi : Jika garis atau berpotongan pada satu titik.


Contoh persamaan linier dengan dua variabel $x$ dan $y$ yang berpotongan bisa ditulis sebagai berikut : $x + y = 6$ dan $2x + y = 8$

Untuk menemukan titik potongnya kita selesaikan menggunakan metode eliminasi.

<iframe scrolling="no" title="Simultaneous Equations:Elimination" src="https://www.geogebra.org/material/iframe/id/MXa3HKy3/width/977/height/574/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/true/rc/false/ld/false/sdz/true/ctl/false" width="977px" height="574px" style="border:0px;"> </iframe>

lalu hasil nya akan seperti ini

![plot](1solusi.png) 

### 2. Tidak ada solusi : Jika garis tidak berpotongan

Kita dapat melihat bahwa kedua persamaan ini berbentuk sama, yaitu :
$ x + y = 5$ dan $ x + y = 8$.
maka, $x + y =$ (konstanta). Namun, konstanta mereka berbeda (5 dan 8). Jadi, tidak ada solusi yang dapat memenuhi kedua persamaan tersebut secara bersamaan.

Dengan kata lain, kedua persamaan ini saling sejajar dan tidak memiliki titik potong. Artinya, sistem persamaan ini tidak memiliki solusi.

Kita dapat menyimpulkan bahwa tidak ada titik potong. Jika digambarkan maka hasilnya akan seperti ini.

![plot](2solusi.png) 

### 3. Banyak solusi : Jika garis saling tumpang tindih

Untuk dua persamaan yang memiliki titik potong yang sama namun tidak identik, kita bisa membuat dua persamaan yang berbeda, tetapi keduanya saling mewakili garis yang sama. Berikut contohnya: 
$x + y = 7$ dan $2x + 2y = 14$

Persamaan kedua bisa disederhanakan menjadi $x + y = 7$, yang identik dengan persamaan pertama. Meskipun persamaan ini terlihat berbeda, keduanya sebenarnya menggambarkan garis yang sama, sehingga titik potongnya adalah garis itu sendiri.

Dengan kata lain, kedua persamaan ini akan tumpang tindih di sepanjang garis $x + y = 7$. Jika di gambarkan, maka hasilnya akan seperti ini.

![plot](3solusi.png) 

## Penyelesaian Sistem Persamaan Linear

Diberikan sistem persamaan:
### nomor 3

$$
2x_1 + 2x_2 = 4
$$
$$
x_1 + x_2 = 2
$$

Kita akan menyelesaikannya menggunakan metode eliminasi Gauss. Pertama, kita tuliskan sistem ini dalam bentuk matriks augmented:

$$
\begin{bmatrix}
2 & 2 & | & 4 \\
1 & 1 & | & 2
\end{bmatrix}
$$

Langkah pertama adalah membuat elemen di bawah pivot menjadi nol. Kita lakukan operasi berikut:

$$
R_1 \leftarrow R_1 - 2R_2
$$

Setelah melakukan perhitungan, kita mendapatkan:

$$
R_1: \quad 2 - 2 \cdot 1 = 0 \\
2 - 2 \cdot 1 = 0 \\
4 - 2 \cdot 2 = 0
$$

Sehingga, matriks augmented menjadi:

$$
\begin{bmatrix}
0 & 0 & | & 0 \\
1 & 1 & | & 2
\end{bmatrix}
$$

Dari baris kedua, kita dapat mengekspresikan \(x_1\) dalam bentuk \(x_2\):
