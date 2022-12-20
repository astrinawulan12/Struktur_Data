# Struktur_Data
Tugas Struktur Data

Nama : Astrina Wulan Putri
NIM : H071211018
Kelas : Struktur Data A

A.	STACK
Stack adalah salah satu struktur data yang digunakan untuk menyimpan sekumpulan objek ataupun variable. Karakteristik stack bersifat LIFO (last in first out). Artinya, data yang terakhir masuk merupakan data yang akan keluar terlebih dahulu.
Seperti halnya tumpukan pada umumnya, misalnya tumpukan buku, yang diatas atau yang terakhir masuk harus dikeluarkan terlebih dahulu untuk mendapatkan buku yang berada di tumpukan bawah. 
1.	Kelebihan dan Kekurangan Menggunakan Stack
•	Kelebihan :
-	Membantu mengelola data dengan metode LIFO
-	Secara otomatis membersihkan objek
-	Tidak mudah rusak

•	Kekurangan :
-	Memori stack sangat terbatas
-	Kemungkinan stack akan meluap atau overflow jika terlalu banyak objek
-	Tidak memungkinkan akses acak

2.	Jenis-Jenis Operasi Stack
•	Pop : Operasi Pop pada stack adalah operasi yang berfokus pada penghapusan elemen. Dikarenakan dalam stack programmer hanya memiliki akses pada bagian atas, hanya ada satu elemen yang dapat dihapus.
•	Push : Operasi Push lebih berfokus pada memasukkan elemen ke dalam stack atau tumpukan. 
•	isFull : Operasi untuk mengetahui apakah tumpukan sudah penuh atau belum.
•	isEmpty : Operasi yang digunakan untuk memeriksa apakah tumpukan kosong atau tidak.
•	Peek : Operasi Peek atau mengintip adalah operasi yang dilakukan untuk mengetahui data teratas dari tumpukan tanpa harus menghapusnya. 

3.	Implementasi Stack
•	Array : salah satu implementasi dari stack yang paling sederhana dan menawarkan akses acak ke pengguna berdasarkan indeks.
•	Linked List : dengan menggunakan linked list , operasi push bisa diganti dengan metode addAtFront dan operasi pop bisa diganti dengan fungsi yang menghapus node depan dari lisked list.

B.	QUEUE
Queue adalah struktur data linier yang menerapkan prinsip operasi dimana elemen data yang masuk pertama akan keluar terlebih dahulu. Prinsip ini dikenal dengan istilah FIFO (First In, First Out).
1.	Jenis-Jenis Queue
•	Simple Queue : Struktur data queue paling dasar dimana penyisipan item dilakukan di simpul belakang (real atau tail) dan penghapusan terjadi di simpul depan (front atau head).
•	Circular Queue : Pada circular queue, simpul terakhir terhubung ke simpul pertama. Queue jenis ini juga dikenal sebagai Ring Buffer karena semua ujungnya terhubung ke ujung yang lain. Penyisipan terjadi di akhir antrian dan penghapusan di depan antrian.
•	Priority Queue : Struktur data queue dimana simpul akan memiliki beberapa prioritas yang telah ditentukan. Simpul dengan prioritas terbesar akan menjadi yang pertama dihapus dari antrian. Sedangkan penyisipan item terjadi sesuai urutan kedatangannya.
•	Double-Ended Queue (Dequeue) : Operasi penyisipan dan penghapusan dapat terjadi di ujung depan dan belakang dari queue.

2.	Karakteristik Queue 
•	Queue adalah struktur FIFO (First In First Out).
•	Untuk menghapus elemen terakhir dari Queue, semua elemen yang dimasukkan sebelum elemen tersebut harus dihilangkan atau dihapus.
•	Queue adalah daftar berurutan dari elemen-elemen dengan tipe data yang serupa.

3.	Operasi-Operasi Dasar pada Queue
•	Enqueue : Menambahkan elemen ke akhir antrian.
•	Dequeue : Menghapus elemen dari depan antrian.
•	IsEmpty : Memeriksa apakah antrian kosong.
•	isFull : Memeriksa apakah antrian sudah penuh.
•	Peek : Mendapatkan nilai bagian depan antrian tanpa menghapusnya.
•	Initialize : Membuat antrian baru tanpa elemen data (kosong).

