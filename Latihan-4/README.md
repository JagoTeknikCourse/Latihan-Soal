# Latihan Soal 4

## Soal 4.1

Buatlah program yang mengoutputkan pola seperti di contoh

**Format Input**

Bilangan bulat N

**Format Output**

Pola

Input 1 

```c
1
```

Output 1

```c
*
```

Input 2

```c
2
```

Output 2

```c
*
**
*
```

Input 3

```c
3
```

Output 3

```c
*
**
*
***
*
**
*
```

Input 4

```c
4
```

Output 4

```c
*
**
*
***
*
**
*
****
*
**
*
***
*
**
*
```


## Soal 4.2

Anda akan diberikan suatu array arr dengan ukuran N. Kemudian, anda akan diberikan Q baris berisi 3 bilangan l, r, dan x. Untuk setiap baris tersebut, outputkan nilai kembalian dari fungsi dosmth jika anda memanggil dosmth(arr,l,r,x).

```c
int dosmth(int *arr, int l, int r, int x){
    int counter = 0;

    for(int i=l; i<=r; i++){
        if(arr[i]<x){
            counter++;
        }
    }

    return counter;
}
```

**Format Input**

Baris pertama berisi bilangan bulat N.

Baris kedua berisi N bilangan bulat terpisah oleh spasi yang menyatakan elemen-elemen dari array. Baris ini akan selalu diinputkan dalam keadaan terurut.

Baris ketiga berisi bilangan bulat Q.

Q baris selanjutnya berisi 3 pasang bilangan l, r, dan x, dipisahkan oleh spasi.

**Format Output**

Output terdiri dari Q baris. Baris ke-i merupakan nilai dosmth(arr,l,r,x) untuk pasangan l,r,x, ke-i pada input

**Constraint**

> N <=10000

> 0<l<r<N

> Q < 100000

Input 1
```c
5
1 2 3 4 5
4
1 3 3
0 4 3
0 0 2
0 0 0
```

Output 1
```c
1
2
1
0
```

> hasil dosmth(arr,1,3,3) dengan arr = {1,2,3,4,5} adalah 1

> hasil dosmth(arr,0,4,3) dengan arr = {1,2,3,4,5} adalah 2

> hasil dosmth(arr,0,0,2) dengan arr = {1,2,3,4,5} adalah 1

> hasil dosmth(arr,0,0,0) dengan arr = {1,2,3,4,5} adalah 0
