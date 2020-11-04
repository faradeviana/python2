# Tugas Ini Untuk Melengkapi Pertemuan 6 <br>
## Dan Menjelaskan Project <br>

**NAMA : Fara Deviana** <br>
**NIM : 312010407** <br>
**KELAS : TI.20.A.2** <br>
**TUGAS : BAHASA PEMOGRAMAN** <br>

## DAFTAR ISI <br>

| NO | Description | Link |
| ----- | ----- | ---- |
| 1. | Pertemuan 5 - Latihan| [silahkan klik](#pertemuan-5---latihan) |
| 2. | Pertemuan 6 - Lab 1 | [silahkan klik](#pertemuan-6---lab-1) |
| 3. | Pertemuan 6 - Lab 1-2 | [silahkan klik](#pertemuan-6---lab-1-2) |
| 4. | Pertemuan 6 - Lab 2 | [silahkan klik](#pertemuan-6---lab-2) |
### Pertemuan 5 - Latihan

Pada pertemuan 5 bahasa pemograman, saya diberi soal untuk latihan oleh Dosen untuk membuat Aplikasi Biodata dengan python (Seperti gambar di bawah ini:)
![latihan pertemuan 5]
![foto 1](https://user-images.githubusercontent.com/72803399/98158136-0989e500-1f0d-11eb-91b5-56175197d357.jpg)

Saat ini saya akan menjelaskan hasil dari tugas tersebut. <br>
Berikut *source code* nya atau klik berikut ([latihan 5](tugas5.py)): <br>
``` python
print "  ====================================" 
print "        Latihan  Biodata Fara        "
print "  ===================================="
#variabel
nama= raw_input ("Masukan Nama Lengkap Anda: ")
panggilan= raw_input ("Masukan Nama Panggilan: ")
nim= raw_input ("Masukan Nim Anda: ")
ttl= raw_input ("Masukan Tempat Lahir Anda`: ")
tl= input ("Masukan Umur Anda: ")
telpone= raw_input ("Masukan No Telpon Anda: ")
alamat= raw_input ("Masukan Alamat Anda: ")


#Menampilkan Inputan User
print "\n Assalamu'alaikum Wr.Wb. "
print "Let me introduce my self My name is",nama,"but you can call me",panggilan,".My NIM is",nim,"I was born in",ttl,"and I am",tl,"years old. I am very glad if you want to invite my house in",alamat,".So, don't forget to call me before with the number",telpone,
print "\n Terimakasih Jangan Lupa Semangat"
```

* Berikut penjelasan :<br>
``` python
print("please your full name : ")
```
source code fiatas berfungsi untuk mencetak hasil / output berupa " **Masukan Nama Anda :** ". <br>
 Untuk menampilkan output string, saya menggunakan *tanda petik dua* didalam fungsi print(), sedangkan jika saya ingin menampilkan output / hasil berupa angka / interger saya tidak perlu menggunakan *tanda petik dua*. Contohnya:
 ``` python 
 print("masukan nama anda ...")
print(4646)
```
<br>(Seperti gambar berikut ini <br>)
![foto 2](https://user-images.githubusercontent.com/72803399/98158140-0b53a880-1f0d-11eb-8d8a-1d34d0eb7a7f.jpg)
* Untuk source code berikutnya adalah inputan atau membuat variable. Seperti syntax dibawah ini:

``` python
nama=raw_input()
```
Keterangan : <br>
1. Variable adalah sebuah wadah penyimpanan data pada program yang akan digunakan selama program itu berjalan. Yang berfungsi sebagai variable dalam source code diatas adalah **fullname** . <br>

2. Fungsi **input()** adalah untuk memasukan nilai dar layar console di command prompt, lalu kemudian mengembalikan nilai saat kita menekan tombol enter *(newline)* 
![foto 3](https://user-images.githubusercontent.com/72803399/98158141-0bec3f00-1f0d-11eb-910b-47cdcda8b9fd.jpg)

Pada gambar diatas, hasil dari inputan tersebut berwarna *putih* <br>
* Untuk memasukan printah lain seperti *Nama, NIM, Tempat Lahir, Umur, No Telpon,* mengikuti perintah yang sama seperti memasukan *fullname* <br>

* Untuk menghitung rumus umur saya menggunakan variable *DOB* yaitu 2020 (Tahun sekarang) dikurangi dengan Year of bircth, pada source code berikut : <br>
``` python
dob=2020-year
```
Pada syntax / source code diatas, saya menggunakan variable *dob* dimana untuk menghitung umur (variable **age** pada output), yaitu dengan rumus pada variable *dob=2020-year* <br>

* Langkah kali ini saya akan menampilkan output yang diminta oleh Dosen. <br>
Output pertama yang di minta Dosen adalah menampilkan salam, yaitu dengan mengetikkan syntax / source code berikut : 
``` python
print("\n Asalammualaikum.")
```
Keterangan :
1. Fungsi **\n** pada source code diatas adalah untuk memberi baris baru / enter / *newline*
2. Fungsi print() seperti dijelaskan pada point **Output** diatas
Hasil source code diatas adalah seperti gambar dibawah ini : 
![foto 45](https://user-images.githubusercontent.com/72803399/98158156-0f7fc600-1f0d-11eb-8b98-fcd7919b323b.jpg)
* Langkah terakhir menampilkan semua hasil dari inputan diatas. Dengan mengetikan source code berikut : <br>
``` python
print "Let me introduce my self My name is",nama,"but you can call me",panggilan,
".My NIM is",nim,"I was born in",ttl,"and I am",tl,"years old. I am very glad if you want to invite my house in",alamat,".So, don't forget to call me before with the number",telpone,
```
Keterangan : <br>
* Fungsi huruf **f** pada perintah *print(f"....")* adalah fungsi print atau bisa memudahkan program dalam mencetak statement dalam suatu baris dibandingkan dengan metode yang lama yaitu memisahkan string dan variable dengan symbol koma ( , ) atau plus ( + ) <br>
* Sedangkan fungsi {} pada output tersebut menampilkan hasil variable 
Hasil dari output tersebut sebagai berikut :
![foto 45](https://user-images.githubusercontent.com/72803399/98158156-0f7fc600-1f0d-11eb-8b98-fcd7919b323b.jpg)

### Pertemuan 6 - lab 1

Pada halaman ini (Tugas pertemuan 6 - lab 1) Saya di berikan tugas oleh Dosen yaitu mempelajari Operator Aritmatika menggunakan bahasa pemograman python. Berikut source yang di berikan oleh Dosen [source code lab 1]
![foto 6](https://user-images.githubusercontent.com/72803399/98158142-0c84d580-1f0d-11eb-8820-ae3bbb520a18.jpg)

``` python
#Penggunaan End
print("A", end="")
print("B", end="")
print("C", end="")

print()
print("X")
print("Y")
print("Z")

#Penggunaan Separator
w,x,y,z=10,15,20,25
print(w,x,y,z)
print(w,x,y,z,sep=",")
print(w,x,y,z,sep="")
print(w,x,y,z,sep=":")
print(w,x,y,z,sep="-----")
```
Oke, kali ini saya menjelaskan materi yang dijelaskan oleh Dosen. <br><br>

* Penggunaan END
Penggunaan end digunakan untuk menambahkan kata yang dicetak di akhir baris

``` python
print("A", end="")
print("B", end="")
print("C", end="")
```

> Penggunaan print() digunakan untuk mencetak output, seperti syntax dibawah ini : <br>
``` python 
print()
```
> Syntax dibawah ini digunakan untuk menampilkan output berupa string
``` python
print("X")
print("Y")
print("Z")
```
Hasil dari source code terseut seperti gambar di bawah ini: 
![foto 7](https://user-images.githubusercontent.com/72803399/98158144-0d1d6c00-1f0d-11eb-8fb8-34b5c0589330.jpg)


* Pengertian separaktor
Sepaktor adalah pemisah yang berfungsi sebagai tanda pemisah antar objek yang dicetak. Defaultnya adalah tanda sepasi <br><br>
> Pendeklarasian beberapa variable berserta nilainya
``` python
w,x,y,z=10,15,20,25
```
> Menampilkan hasil setiap variable tiap-tiap variable
``` python
print(w,x,y,z)
```
> Menampilkan hasil variable dari tiap-tiap variable menggunakan pemisah , (koma)
``` python
print(w,x,y,z,sep=",")
```
> Menampilkan hasil variable dari tiap-tiap variable tanpa menggunakan pemisah
``` python
print(w,x,y,z,sep="")
```
> Menampilkan hasil variable dari tiap-tiap variable dengan menggunakan pemisah : (titik dua)
``` python
print(w,x,y,z,sep=":")
```
> Menampilkan hasil variable dari tiap-tiap variable dengan menggunakan pemisah ----
``` python
print(w,x,y,z,sep="-----")
```

Hasil dari syntax / source code diatas adalah seperti berikut iniL: <br>
![foto 8](https://user-images.githubusercontent.com/72803399/98158147-0d1d6c00-1f0d-11eb-85b1-87cf2122e6e3.jpg)

### Pertemuan 6 - lab 1-2 
* String format <br>
String formatting atau pemformatan string memungkinkan kita menyuntikkan item kedalam string daripada kita mencoba menggabungkan string menggunakan koma atau string concatenation.<br>

Penggunaan pada source yang di berikan Dosen sebagai berikut : 
![foto 9](https://user-images.githubusercontent.com/72803399/98158148-0db60280-1f0d-11eb-82e2-f5dba2ed3c22.jpg)

``` python
#Rizky
# string format 1
print(0, 10 ** 0)
print(1, 10 ** 1)
print(2, 10 ** 2)
print(3, 10 ** 3)
print(4, 10 ** 4)
print(5, 10 ** 5)
print(6, 10 ** 6)
print(7, 10 ** 7)
print(8, 10 ** 8)
print(9, 10 ** 9)
print(10, 10 ** 10)

# string format 2
print('{0:>3}{1:>16})'.format(0, 10 ** 0))
print('{0:>3}{1:>16})'.format(1, 10 ** 1))
print('{0:>3}{1:>16})'.format(2, 10 ** 2))
print('{0:>3}{1:>16})'.format(3, 10 ** 3))
print('{0:>3}{1:>16})'.format(4, 10 ** 4))
print('{0:>3}{1:>16})'.format(5, 10 ** 5))
print('{0:>3}{1:>16})'.format(6, 10 ** 6))
print('{0:>3}{1:>16})'.format(7, 10 ** 7))
print('{0:>3}{1:>16})'.format(8, 10 ** 8))
print('{0:>3}{1:>16})'.format(9, 10 ** 9))
print('{0:>3}{1:>16})'.format(10, 10 ** 10))
```
<br>
Saat ini saya akan menjelaskan satu persatu dari syntax yang diberikan oleh Dosen <br>
Tugas yang di berikan oleh Dosen adalah seperti gambar dibawah ini atau bisa di temukan dengan link berikut : ([source code](lanjutan lab1.py))
1. **String format 1** <br>
Pada syntax / source code string format 1 akan menampilkan output berupa 2 outputan. <br>
Yang pertama (sebelah kiri) akan menampilkan angka urut dari angka 0 hingga 10, sedangkan sebelah kanan akan menampilkan Oprasi Aritmatika Pangkat. <br>
Dengan ketentuan sebagau berikut, oprasi pangkat dengan angka kiri sebagai pokok (Rumus : ** [Bintang dua]) <br>
Hasil dari syntax tersebut adalah 10 pangkat 0, hingga 10 pangkat 10. Dengan output sebagai berikut : <br>

![foto 10](https://user-images.githubusercontent.com/72803399/98158151-0e4e9900-1f0d-11eb-835f-8f9a97f429b1.jpg)


2. **String Format 2** <br><br>
Pada syntax / source code string format 2 akan menampilkan output berupa 2 output'an juga (Seoerti string format 1, yaitu kanan dan kiri) <br>
Dengan ketentuan sebagai berikut : <br>
> > Alignment, padding, dan precesion dengan **.format()** dalam kurung kurawal kita dapat menetapkan panjang bidang, rata kanan/kiri, parameter pembulatan dan banyak lagi. Contoh lain seperti berikut :
``` python
print('{0:8} | {1:9}'.format('sepatu','Jumlah'))
print('{0:8} | {1:9}'.format('dalas', 3.))
print('{0:8} | {1:9}'.format('NB',10))
```
Hasil dari source code contoh di atas akan seperti berikut : 
![foto 11](https://user-images.githubusercontent.com/72803399/98158153-0e4e9900-1f0d-11eb-95f4-2f6f0b3b9a29.jpg)

> Secara default, **.format()** menggunakan rata text kiri, angka ke kanan. <,^, atau > untuk perataan kiri, tengah , atau kanan. Contoh lain dari penggunaan **.format()** sebagai berikut : <br>
``` python
print('{:<30}{:^30}{:>30}'.format('Kiri','Tengah','Kanan'))
print('{:<30}{:^30}{:>30}'.format(12,34,56))
```
Hasil dari source code contohdiatas akan muncul seperti ini : <br>
![Output Alignment](isi%20foto/foto%2012.png)
<br>
<br>
Hasil string format 2 adalah : <br>
![Output Alignment contoh 2](isi%20foto/foto%2013.png)
<br>
<br>

### Pertemuan 6 - Lab 2

* Konversi Nilai Variable
Untuk pembahasan terakhir, kali ini akan myenyelesaikan tugas Lab 2 dari Dosen, yaitu Konversi Nilai Variable <br>
Tugas yang di berikan oleh Dosen adalah seperti gambar dibawah ini atau bisa di temukan dengan link berikut : ([source code](lab2.py))
``` python
a=int(input("Masukkan Nilai A : "))
b=int(input("Masukkan Nilai B : "))
print("Variable A : ",a)
print("Variable B : ",b)
print("Hasil penggabungan {1}&{0}=%d".format(a,b) %(a+b))

#Konversi nilai variable
a=int(a)
b=int(b)
print("Hasil penjumlahan {1}+{0}=%d".format(a,b) %(a+b))
print("Hasil pembagian {1}/{0}=%d".format(a,b) %(a/b))
```
<br>
Hasil dari source / code diatas : <br>


![foto 14](https://user-images.githubusercontent.com/72803399/98158154-0ee72f80-1f0d-11eb-8d51-fd7c6b57de95.jpg)

