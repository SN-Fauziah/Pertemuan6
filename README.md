# Tugas Pertemuan ke 5 & 6 - Bahasa Pemrograman
Repository ini dibuat untuk memenuhi tugas pertemuan 5 & 6 <br><br>
Nama    : Siti Nur Fauziah<br>
NIM     : 312010032<br>
Kelas   : TI.20.B1<br>

#### DAFTAR ISI<br>
| No | Description | Link|
| ----- | ----- | ----- |
| 1 | Tugas Pertemuan 5 | [Click Here](#tugas-pertemuan-5) |
| 2 | Tugas Pertemuan 6 | [Click Here] |

## 1. Tugas Pertemuan 5
Pertama saya akan menjelaskan Tugas Pertemuan ke 5 yaitu Membuat Program untuk menginputkan biodata yang terdiri dari Nama lengkap, Nickname, NPM, TTL, No Telp, dan Alamat :
![Tugas5](Foto/Latihan5.PNG)<br>
Berikut <i>source code</i> yang telah diberikan oleh Dosen saya atau klik link berikut ([Tugas 5 Python](p5_tugas.py))
```python
print("Please enter your Full name : ")
fullname=input()
print("Please enter your Nickname : ")
nickname=input()
print("Please insert your NPM : ")
npm=int(input())
print("Please enter your Born place : ")
bornplace=input()
print("Please insert your Age : ")
age=int(input())
print("Please enter your Home address : ")
address=input()
print("Please enter your Phone number : ")
phonenumber=int(input())


print("\nAssalamualaikum Wr, Wb.")
print(f"Let me introduce my self.My name is {fullname}, but you can call me {nickname}.My NPM's {NPM}.I was born in {bornplace} and i am {age} years old. I am very glad if you want to invite my house in {address}.So, don't forget to call me before with the number {phonenumber}.")
print("\nThank you.")
```

Berikut untuk penjelasannya : <br>
```python
print("Please enter your Full name : ")
fullname=input()
```
* Source code di atas berfungsi untuk mencetak hasil / output berupa string " Please enter your full name : ", dan secara otomatis kita akan bisa mengisi / input nama kita.Seperti gambar di bawah ini <br>
![Tugas 5](Foto/inputnama.PNG)<br>
* Syntax atau perintah <i>fullname=input()</i> seperti di atas tadi adalah source code untuk membuat inputan/variable.<br>
Maksud Variable disini adalah tempat menyimpan data, dan lokasi di memori yang digunakan untuk menyimpan nilai, sedangkan tipe data adalah jenis data yang tersimpan dalam variable.Variable bersifat <i>mutable</i> artinya nilainya bisa berubah-ubah.Yang berfungsi sebagai variable dalam source code diatas adalah fullname.<br><br>
> Untuk menampilkan output berupa integer atau angka kita tidak perlu menambahkan tanda petik dua ("input") di dalam kurung jadi kita bisa langsung saja untuk menginputkan angkanya.<br>
```python
print(270799)
```
* Maka hasilnya akan otomatis keluar angka yang kita inputkan tadi seperti di bawah ini. <br>
![Tugas 5](Foto/inputangka.PNG)<br><br>
> Namun untuk syntax output angka dalam program ini kita hanya perlu menambahkan kata <i>int</i> sebelum kata input seperti di bawah ini. <br>
```python
print("Please insert your NPM : ")
npm=int(input())
```
* Hasil untuk mengisi inputan akan seperti ini :<br>
![Tugas 5](Foto/npm.PNG)<br>

* Langkah selanjutnya untuk menghasilkan output / mengisi inputan yang lainnya seperti Nickname, Born Place, Home Address, bisa mengikuti source code/syntax pengisian Fullname, sedangkan untuk Age, dan Phone Number bisa mengikuti syntax untuk penginputan NPM.<br>
> Lalu untuk syntax/source code :<br>
```python
print("\nAssalamualaikum Wr, Wb.")
```
* Fungsi <i>\n</i> pada syntax di atas adalah untuk memberi baris baru/enter/lebih sering dikenal newline.<br>
* Sedangkan fungsi <i>print("...")</i> seperti yang sudah dibahas di atas, hasil dari syntax terserbut seperti di bawah ini.<br>
![Tugas 5](Foto/print.PNG)<br>
> Yang terakhir untuk menampilkan semua hasil dari inputan di atas yaitu dengan mengetikkan syntax seperti di bawah<br>
 ```python
print(f"Let me introduce my self.My name is {fullname}, but you can call me {nickname}.My NPM's {npm}.I was born in {bornplace} and i am {age} years old. I am very glad if you want to invite my house in {address}.So, don't forget to call me before with the number {phonenumber}.")
```
* Fungsi <i>f</i> pada syntax di atas adalah agar bisa memudahkan programmer dalam mencetak statement dalam satu baris dibandingkan dengan metode yang lama yaitu memisahkan string dan variable dengan simbol koma ( , ) atau plus ( + ).<br>
* Sedangkan fungsi {} pada output tersebut adalah untuk menampilkan hasil dari variable.<br>
Hasil dari output tersebut seperti berikut :<br>
![Tugas 5](Foto/f.PNG)<br>
<br>
<hr>
<br>

## 2. Tugas Pertemuan 6 - Lab 1
Selanjutnya yang kedua saya akan menjelaskan tugas pertemuan ke 6 yaitu tentang mempelajari <b>Operator pada Python</b>.<br>
![Tugas 6](Foto/operator.PNG)<br>
Berikut <i>source code</i> yang telah diberikan oleh Dosen saya atau klik link berikut ([Tugas 6 - Lab 1](lab1.py))
```python
#penggunaan end
print('A', end='')
print('B', end='')
print('C', end='')
print()
print('X')
print('Y')
print('z')

#penggunaan separator
w, x, y, z = 10, 15, 20, 25
print(w, x, y, z)
print(w, x, y, z, sep=',')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='-----')
```

Berikut untuk penjelasannya : <br>
* Penggunaan <i>end</i> digunakan untuk menambahkan karakter yang dicetak di akhir baris, atau lebih sering kita kenal dengan istilah <i>ganti baris</i>.Seperti contoh di bawah ini.<br>
```python
print('A', end='')
print('B', end='')
print('C', end='')
print()
print('X')
print('Y')
print('z')
```
> Hasilnya akan seperti ini.<br>
![Tugas 6](Foto/end.PNG)<br>

* Untuk penggunaan <i>separator</i> digunakan untuk pemisah, atau fungsinya sebagai perintah pemisah antar objek yang di cetak.Seperti contoh di bawah ini.<br>
```python
w, x, y, z = 10, 15, 20, 25
print(w, x, y, z)
print(w, x, y, z, sep=',')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='-----')
```
> Hasilnya akan seperti ini.<br>
![Tugas 6](Foto/separator.PNG)<br>

