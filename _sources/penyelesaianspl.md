# Penyelesaian Sistem Persamaan Linier

pendekatan analitik dan numerik hasilnya bisa berbeda

cth analitik biasanya outputnya sama 

matrix adalah kumpulan bilangan yang disusun dalam baris dan kolom

## Apa itu operasi elementer ?

### 3 jenis operasi elementer
1. menukar dua baris
2. mengalikan baris dengan skala non 0 (maka hasil garis nya sama , dikalikan selain 0)
3. menambahkan kelipatan satu baris ke baris yang lain

### Bentuk eselon baris dan eselon baris teredukasi
- bentuk eselon baris : baris 0 dibawah sendiri, non 0 diatasnya
- eselon baris teredukasi : memenuhi persamaan garis , pivot bernilai 1 


## Aplikasi OBE : 
1. untuk menyelesaikan SPL
2. untuk mencari invers matriks
3. untuk menghitung determinan

koefisien linier adalah sesuatu yang melekat pada variable

## Langkah-langkah eliminasi gauss :
1. matrix augmentasi : mengubah persamaan ke matrix

contoh : | menandakan koefisien
$\[
\begin{bmatrix} 
1 & 2 & 1 & \vert & 9 \\ 
2 & 1 & -1 & \vert & 3 \\ 
3 & -1 & 2 & \vert & 8 
\end{bmatrix}\]$

dari persamaan :
- $x + 2y + z = 9$
- $2x + y - z = 3$
- $3x - y + 2x = 8$

2. bentuk eselon baris 

- menjadikan pivot (baris 1 kolom 1)

3. Hilangkan elemen-elemen di bawah pivot (angka utama di baris tersebut) menjadi nol, dari atas ke bawah (eliminasi maju).

4. Setelah mencapai bentuk eselon, lanjutkan dengan substitusi balik (back substitution) untuk menyelesaikan variabel-variabel.
