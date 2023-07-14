# tugas-magang-iris

Setiap variabel atau objek lain dalam program memiliki lokasi masing-masing (alamat memori).

### POINTER
pointer merupakan variabel yang menampung alamat memori.
```c
int a = 10, b=5;

int* p; //deklarasi (ada 2 cara)
int *q = &b; //langsung inisiasi
p = &a; //assignment (tidak pake *)

cout<< *p <<" "<< q;
````
outputnya
````c
10 0x61fe08
````
karena 'p' menggunakan operator dereference yang berfungsi mengakses nilai yang ditunjuk si pointer.

### Double Pointer
Pointer menunjuk pointer lainnnya (pointer to pointer)
cara deklarasi :
````c
int a, *b, **c;
cin>>a;
b=&a;
c=&b;
cout<<**c<<endl<<*b<<endl<<a;
````
outputnya akan sama semua


### Pointer dan Array
Alamat dari array = alamat elemen pertama array tersebut.
````c
contoh array
````
### Pointer dan Fungsi
### 1. Pass by Value
Perubahan hanya terjadi di fungsi, tidak berubah pada variabel asal (int main)
````c
contoh (kuadrat)
````
### 2. Pass by Reference
Menggunakan pointer, dimana dia memasukkan alamat memorinya, sehingga perubahannya tidak hanya di parameter fungsi, tetapi juga berpengaruh pada variabel asal (int main)
````c
contoh
````

### ****Nodes Interaction****

Program mengenai interaksi antara node pada folter NodesInteraction_BeginnerTutorial
![Screenshot from 2021-04-26 14-42-40 (1)](https://github.com/taz06/tugas-magang-iris/assets/81939053/aa3d77ae-138e-4c87-b967-85642ef2671e)

Full folder : https://drive.google.com/drive/folders/1PP67thokWPia5tqfNioEz9OH4rUDBtIW?usp=sharing
