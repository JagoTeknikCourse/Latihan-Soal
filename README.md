# Latihan Soal 1

## Soal 1.1
Buatlah suatu program yang mengoutputkan hal seperti berikut

Output :

```c
Halo Dunia!
"Halo Dunia!"
\(*o*)\ /(*o*)/
'Saya sedang belajar bahasa C'
```

## Soal 1.2
Diberikan suatu matriks 3x3 dengan isinya semua bilangan bulat. Transposkanlah matriks tersebut kemudian menambahkan 1 di setiap elemennya.

Format Input :
Input berisi 3 baris yang masing-masing barisnya berisi 3 bilangan bulat terpisah oleh spasi. 9 nilai ini menyatakan elemen-elemen pada matriks.

Format output :
Outputkan 3 baris yang masing-masing barisnya berisi bilangan bulat terpisah oleh spasi. Matriks yang dioutputkan adalah hasil transpose dari matriks yang diinputkan.

Input :

```c
1 2 3
4 5 6
7 8 9
```

Output :

```c
2 5 8
3 6 9
4 7 10
```

## Soal 1.3
![Image 1.3](https://github.com/JagoTeknikCourse/Latihan-Soal/img/img-1-3.png)
Bagaimana merubah koordinat pixel pada frame tersebut menjadi sebuah koordinat normal dengan offset pada (180,320)px?? Size frame = 320x640.
Input program hanya 2 yaitu koordinat pixel, sedangkan outputnya juga 2 yaitu koordinat normal.

Koordinat normal : y ke atas, x ke kanan.

Tambahkan newline pada akhir jawaban.

Input :

```c
360 320
```

Output :

```c
180 0
```

## Soal 1.4
Di planet Vecashee satu tahun ada 72 hari. Dan tidak ada tahun kabisat. Warga planet Vecashee mempunyai 7 hari dalam 1 minggu dan menamainya hari 0, hari 1, hari 2, hari 3, hari 4, hari 5, dan hari 6.

Jika Arshad lahir pada hari n, pada hari apakah Arshad akan berulang tahun ke m.

Format Input :
Diberikan 2 nilai yang dipisahkan oleh spasi, n, dan m.

Format output :
Hari dimana Arshad berulang tahun ke-m. Outputkan dengan format "hari x"

Input :

```c
0 1
```

Output :

```c
hari 2
```