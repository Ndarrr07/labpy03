# labpy03
## latihan praktek modul ke 3
### Berikut untuk program dan hasil nya 
     NAMA    : MUHAMMAD ISKANDAR
     KELAS   : TI.21.A.1
     NIM     : 312110035
     MATKUL  : BAHASA PEMROGRAMAN
Berikut untuk program nya menggunakan editor pycharm<p>
1. latihan1.py<P>
1.Tampilkan n bilangan acak yang lebih kecil dari 0.5.<p>
2.nilai n diisi pada saat runtime<P>
3.anda bisa menggunakan kombinasi while dan for untuk menyelesaikannya<p>
4.gunakan fungsi random() yang dapat diimport terlebih dahulu
Berikut untuk gambar program nya:<P>
![gambar 1](screenshot/ss1.png)

dari hasil tersebut menghasilkan output seperti ini<P>
   
     C:\Users\sdnke\AppData\Local\Programs\Python\Python310\python.exe D:/latihan3ku/labpy03/latihan1.py
     ========================================
     Bilangan random yang lebih kecil dari 0,5
     ========================================
     Masukan nilai n : 5
     Data ke 1  =  0.15096984215079234
     Data ke 2  =  0.21356004612311147
     Data ke 3  =  0.22985332279850357
     Data ke 4  =  0.08450664248444828
     Data ke 5  =  0.4574985262911251
              
     Process finished with exit code 0

Berikut untuk Algoritma beserta program nya:

     import random

     print(40 * "=")
     print("Bilangan random yang lebih kecil dari 0,5")
     print(40 * "=")
     jum = int(input("Masukan nilai n : "))
     i = 0
     for i in range(jum):
     i += 1
     angkaDec = random.uniform(0, 0.5)
     print("Data ke", i, " = ", angkaDec)

Algoritma nya:<p>

     "print" : berfungsi untuk mencetak atau menampilkan objek ke perangkat keluaran (layar) atau ke file teks.
     "import" : fungsi lanjut yang dipanggil oleh statement import.
     "random" : untuk menentukan suatu pilihan.
     "range" : merupakan fungsi yang menghasilkan list. Fungsi ini akan menciptakan sebuah list baru dengan rentang nilai tertentu.
     "uniform": digunakan untuk menampilkan bilangan float random dengan batas awal bilangan x, dan batas akhir bilangan y.

2. Algoritma,Program beserta hasil output dari latihan2:<p>
![gambar 2](screenshot/latian5.PNG)

