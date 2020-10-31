<p align="center">
	BAHASA PEMROGRAMAN
</p>
<p align="center">
	TIPE DATA, VARIABEL, OPERATOR
</p>
<p align="center">
	Dosen : Agung Nugroho, M.Kom
</p>
<p align="center"> 
	<b>Tugas untuk memenuhi syarat penilain pada Pert-6</b>
</p>

<p align="center">
	<img src="/Logo/logo.png" alt="UPB" width="500" height="400">
</p>

<p align="center">
                 Nama : Jose Fisto
</p>
<p align="center">
                 NIM : 312010119
</p>
<p align="center">
                 Kelas : TI.20 A.1
</p>

<p align="center">
	<img src="/Logo/blank.png" width="20" height="20">
</p>

<p align="center">
	<b>UNIVERSITAS PELITA BANGSA</b>
</p>
<p align="center">
	<b>FAKULTAS TEKNIK</b>
</p>
<p align="center">
	<b>TEKNIK INFORMATIKA</b>
</p>
<p align="center">
	<b>TA 2020 / 2021</b>
</p>

---
# Tipe Data, Variabel, Operator

Pada repository kali ini saya akan memberikan penjelasan pada Latihan dari materi Pert-6 yaitu Lab 1 dan Lab 2 yang terdiri dari Tipe Data, Variabel, Operator.

**Daftar Isi**
- [Tipe Data, Variabel, Operator](#tipe-data-variabel-operator)
- [Lab 1](#lab-1)
	- [Penggunaan End](#penggunaan-end)
	- [Penggunaan Separator](#penggunaan-separator)
	- [Penggunaan pada String Format](#penggunaan-pada-string-format)

# Lab 1

Perintah `print('...')` merupakan perintah yang berfungsi untuk menunjukkan hasil pada layar baru atau output.

## Penggunaan End

`Penggunaan End` merujuk pada cetak akhir baris atau baris baru pada kalimat atau paragraf. 

 Pada perintah python di atas :

- `print('A', end='')`, 
- `print('B', end='')`,
- `print('C', end='')`,
- `print()`
- `print('X')`
- `print('Y')`
- `print('Z')`

menunjukkan perintah bahwa ;
- A,B,C adalah garis baru "`end=''`" nantinya menyambung dengan variabel lanjutannya atau kalimat. Maka hasil yang akan keluar pada Output menjadi "ABC".
- jika X, Y, Z di print maka hasil dicetak menjadi baris baru di setiap paragrafnya. Maka hasil akan menjadi pada gambar di bawah ini.

## Penggunaan Separator

`Penggunaan Separator` merupakan tanda pemisah dari objek yang dicetak atau menjadi satu kalimat yang mempunyai jarak penulisan setiap barisnya.

Pada perintah python di atas :

- `w, x, y, z = 10, 15, 20, 25`
- `print(w, x, y ,z)`
- `print(w, x, y, z, sep=',')`
- `print(w, x, y, z, sep='')`
- `print(w, x, y, z, sep=':')`
- `print(w, x, y, z, sep='-----')`

menunjukkan perintah bahwa :

- Diketahui bahwa w adalah 10, x adalah 15, y adalah 20, z adalah 25.
- Jika `w, x, y, z` diprintkan maka menjadi `10 15 20 25`.
- Jika `w, x, y, z` di separatorkan dengan tanda koma `(,)` pada setiap angka merupakan dari variabel dan diprintkan maka hasil pada output menjadi `10,15,20,25`.
- Jika `w, x, y, z` di gabungkan pada setiap angka merupakan dari variabel dan diprintkan maka hasil pada output menjadi `10152025`.
-  Jika `w, x, y, z` di separatorkan dengan tanda titik dua `(:)` pada setiap angka merupakan dari variabel  dan diprintkan maka hasil pada output menjadi `10:15:20:25`.
-  Jika `w, x, y, z` di separatorkan dengan tanda strip `(-)` pada setiap angka merupakan dari variabel  dan diprintkan maka hasil pada output menjadi `10-----15-----20-----25`.

Atau hasil bisa dilihat pada gambar dibawah ini

## Penggunaan pada String Format

String format di gunakan sebagai konversi data ke bentuk string sebagai contoh bila 2 merupakan pangkat, dan 4 adalah angka, maka 4 pangkat 2 yaitu 16.

pada perintah python di atas :

- print(0, 10**0)
- print(1, 10**1)
- print(2, 10**2)
- print(3, 10**3)
- print(4, 10**4)
- print(5, 10**5)
- print(6, 10**6)
- print(7, 10**7)
- print(8, 10**8)
- print(9, 10**9)
- print(10, 10**10)

menunjukkan perintah bahwa :

