# Latihan Soal 2

## Soal 2.1
Nilai-nilai Latihan-1 para peserta sudah dikumpulkam. Sekarang para tutor tinggal memberikan huruf pada nilai tersebut. Konversi nilai ke huruf untuk praktikum sama seperti konversi nilai pada mata kuliah

| Huruf  | Nilai   |
|:------:| --------|
| A      | 86-100  |
| AB     | 76-85   |
| B      | 66-75   |
| BC     | 61-65   |
| C      | 56-60   |
| D      | 41-55   |
| E      | 0-40    |

Diberikan suatu nilai dari peserta, konversikanlah nilai tersebut ke huruf.

Input 1:

```c
87
```

Output 1:

```c
A
```

Input 2:

```c
63
```

Output 2:

```c
BC
```

## Soal 2.2
Diberikan 3 bilangan bulat a,b, dan c. Carilah bilangan terbesar dari 3 bilangan tersebut

Format Input :
3 buah bilangan a, b, dan c yang terpisah oleh spasi.

Input 1:

```c
1 2 3
```

Output 1:

```c
3
```

Input 2:

```c
3 2 1
```

Output 2:

```c
3
```

## Soal 2.3
Diberikan suatu bilangan real x, carilah nilai floor dari x dan nilai ceil dari x. Nilai floor dari x adalah bilangan bulat terbesar yang lebih kecil atau sama dengan x. Nilai cell adalah bilangan bulat terkecil yang lebih besar atau sama dengan x.

Sebagai contoh, floor(2.2) adalah 2 dan ceil (2.2) adalah 3. Floor juga dikenal dengan pembulatan ke bawah sedangkan Ceil dikenal dengan pembulatan ke atas.

Format Input :
Suatu bilangan real x.

Foramt Output :
Nilai floor dan ceil dari x, secara beruntun, dipisahkan oleh spasi.

Input :

```c
-69.69
```

Output :

```c
-70 -69
```

Notes!

Untuk mengambil bagian bulat dari suatu bilangan real, dapat dilakukan dengan type casting sebagai berikut
```c
float x = -69.69
int a = (int)x; //a = -69
```

Warning!

Pada bahasa C, sudah tersedia fungsi floor dan ceil. Namun pada latihan soal ini, cobalah membuat floor dan ceil dengan menggunakan if else.

## Soal 2.4
Di planet Vecashee satu tahun ada 72 hari. Dan tidak ada tahun kabisat. Warga planet Vecashee mempunyai 7 hari dalam 1 minggu dan menamainya hari 0, hari 1, hari 2, hari 3, hari 4, hari 5, dan hari 6.

Suatu hari, Arshad berpikiran untuk mengubah nama-nama hari tersebut. Ia ingin mengubahnya menjadi seperti berikut

| Hari versi Normal  | Hari versi Arshad |
|:------------------:| ------------------|
| Hari 0             | Monin             |
| Hari 1             | Tuesasa           |
| Hari 2             | Wednesbu          |
| Hari 3             | Thumis            |
| Hari 4             | Friat             |
| Hari 5             | Saturtu           |
| Hari 6             | Sunggu            |

Format Input :
Diberikan 2 nilai yang dipisahkan oleh spasi.

Format output :
Hari dimana Arshad berulang tahun ke-m. Outputkan hari dalam versi Arshad

Input 1:

```c
0 1
```

Output 1:

```c
Wednesbu
```

Input 2:

```c
2 2
```

Output 2:

```c
Sunggu
```