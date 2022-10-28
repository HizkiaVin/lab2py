# lab2py
Latihan Python

Jika anda belum mempunyai aplikasi Phyton, silahkan download pada situs resmi python.org, lalu ikuti langkah instalasinya.
![Download python](https://user-images.githubusercontent.com/116176746/197666495-415a2a51-738f-4cbf-82f8-638e600391c4.png)
Checklist pilihan Add Python.exe to PATH, agar python dapat dipanggil dari CMD.
![Install Python](https://user-images.githubusercontent.com/116176746/197667547-2a765b18-9526-4b10-bcca-f741a4d04852.png)

Setelah proses instalasi selesai, mari kita coba beberapa latihan berikut
Buka CMD pada laptop anda, lalu masukkan perintah >python untuk memanggil python dari CMD
![Python from CMD](https://user-images.githubusercontent.com/116176746/197668235-83ec94b4-add4-4851-9769-7da5cffd1cad.png)
Jika muncul pesan seperti diatas, python berhasil dipanggil dari CMD.

Latihan pertama adalah menampilkan tulisan di layar.
Kita bisa menggunakan perintah >>>print("tulisan yang ingin ditampilkan"). Fungsi print pada python adalah sebuah fungsi yang digunakan untuk memunculkan output yang ingin kita print pada console.
Contoh: Kita akan menampilkan tulisan "Hello" dan "Saya sedang belajar python". Masukkan perintah >>>print("Hello") dan >>>print("Saya sedang belajar python"), maka tulisan akan muncul di layar seperti gambar di bawah.
![latihan 1](https://user-images.githubusercontent.com/116176746/197669533-9238e17a-322f-4e83-8bce-f784638b685a.png)


Latihan kedua adalah menjumlahkan dua buah bilangan menggunakan variable a dan b.
Kita akan mendefinisikan variable a dengan nilai 8 dan variable b dengan nilai 6, lalu mencetak nilai variable a dan b, dan mencetak hasil penjumlahan a+b
![latihan 2](https://user-images.githubusercontent.com/116176746/197988184-ff760a85-5839-4e3b-8689-1aeab5420fee.png)


Latihan 3 adalah menjalankan IDLE
Buka IDLE python yang telah kita download sebelumnya, lalu buat file baru dengan nama latihan3.py pada direktori kerja anda.Kita akan menggunakan fungsi input untuk mengambil nilai variabel dari keyboard.
Masukkan perintah berikut:

#Input nilai variable
a=input("Masukkan Nilai A =")
b=input("Masukkan Nilai B =")

#Cetak nilai variable
print("Variable A =", a)
print("Variable B =", b)

#Cetak hasil operasi kedua variable dengan string format
print("Hasil Penggabung {1}&{0}=%s".format(a,b) %(a+b))

#Konversi nilai variable
a=int(a)
b=int(b)
print("Hasil Penjumlahan {1}+{0}=%s".format(a,b) %(a+b))
print("Hasil Pembagian {1}/{0}=%s".format(a,b) %(a/b))

![latihan 3](https://user-images.githubusercontent.com/116176746/198471443-da553ed0-500a-4795-b9b3-9647cb8f4a67.png)

Kemudian kita Run, jika sesuai maka output yang dditampilkan akan seperti gambar dibawah
![output](https://user-images.githubusercontent.com/116176746/198471484-686412f4-eda2-4baf-b26e-c3aee6d1eb20.png)
