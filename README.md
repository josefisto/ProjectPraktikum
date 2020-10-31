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

[Penggunaan End](Lab1/ScreenShot_Output_Lab1/Penggunaan-END.png)

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

[]()

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

String format di gunakan sebagai konversi data ke bentuk string sebagai contoh bila 2 merupakan pangkat, dan 4 adalah angka, maka 4 pangkat 2 yaitu 16 maka konversi data tersebut termasuk jenis perpangkatan.

[]()

pada perintah python di atas :

1. `print(0, 10**0)`
2. `print(1, 10**1)`
3. `print(2, 10**2)`
4. `print(3, 10**3)`
5. `print(4, 10**4)`
6. `print(5, 10**5)`
7. `print(6, 10**6)`
8. `print(7, 10**7)`
9. `print(8, 10**8)`
10. `print(9, 10**9)`
11. `print(10, 10**10)`

menunjukkan perintah bahwa :

1. print jika 0 merupakan pangkat, maka 10 adalah angka dengan pangkat 0. dan hasil yang keluar pada output adalah 1.

2. print jika 1 merupakan pangkat, maka 10 adalah angka dengan pangkat 1. dan hasil yang keluar pada output adalah 10.

3. print jika 2 merupakan pangkat, maka 10 adalah angka dengan pangkat 2. dan hasil yang keluar pada output adalah 100.

4. print jika 3 merupakan pangkat, maka 10 adalah angka dengan pangkat 3. dan hasil yang keluar pada output adalah 1000.

5. print jika 4 merupakan pangkat, maka 10 adalah angka dengan pangkat 4. dan hasil yang keluar pada output adalah 10000.

6. print jika 5 merupakan pangkat, maka 10 adalah angka dengan pangkat 5. dan hasil yang keluar pada output adalah 100000.

7. print jika 6 merupakan pangkat, maka 10 adalah angka dengan pangkat 6. dan hasil yang keluar pada output adalah 1000000.

8. print jika 7 merupakan pangkat, maka 10 adalah angka dengan pangkat 7. dan hasil yang keluar pada output adalah 100.000.000.

9. print jika 8 merupakan pangkat, maka 10 adalah angka dengan pangkat 8. dan hasil yang keluar pada output adalah 10.000.0000.

10. print jika 9 merupakan pangkat, maka 10 adalah angka dengan pangkat 9. dan hasil yang keluar pada output adalah 1.000.000.000.

11. print jika 10 merupakan pangkat, maka 10 adalah angka dengan pangkat 10. dan hasil yang keluar pada output adalah 10.000.000.000.

[]()

pada perintah di atas merupakan jenis konversi data perpangkatan yang mempunyai jarak antar baris yang disejajarkan dengan yang lain, yaitu :

1. `print('{0:>3} {1:>16}'.format(0, 10**0))`
2. `print('{0:>3} {1:>16}'.format(1, 10**1))`
3. `print('{0:>3} {1:>16}'.format(2, 10**2))`
4. `print('{0:>3} {1:>16}'.format(3, 10**3))`
5. `print('{0:>3} {1:>16}'.format(4, 10**4))`
6. `print('{0:>3} {1:>16}'.format(5, 10**5))`
7. `print('{0:>3} {1:>16}'.format(6, 10**6))`
8. `print('{0:>3} {1:>16}'.format(7, 10**7))`
9. `print('{0:>3} {1:>16}'.format(8, 10**8))`
10. `print('{0:>3} {1:>16}'.format(9, 10**9))`
11. `print('{0:>3} {1:>16}'.format(10, 10**10))`

Menyatakan bahwa :

1. Menampilkan objek, pada jarak baris pertama diberi jarak `3` baris, lalu di awali dengan angka `0`. Di baris selanjutnya setelah angka `0` diberi jarak 16 baris dimana hasil perpangkat yaitu `1` ditulis diratakan pada sebelah kanan pada baris ke 16.

2. Menampilkan objek, pada jarak baris pertama diberi jarak `3` baris, lalu di awali dengan angka `1`. Di baris selanjutnya setelah angka `1` diberi jarak `16` baris dimana hasil perpangkat yaitu `10` ditulis diratakan pada sebelah kanan pada baris ke `16`.

3. Menampilkan objek, pada jarak baris pertama diberi jarak 3 baris, lalu di awali dengan angka `2`. Di baris selanjutnya setelah angka `2` diberi jarak `16` baris dimana hasil perpangkat yaitu `100` ditulis diratakan pada sebelah kanan pada baris ke `16`.

4. Menampilkan objek, pada jarak baris pertama diberi jarak 3 baris, lalu di awali dengan angka `3`. Di baris selanjutnya setelah angka `3` diberi jarak `16` baris dimana hasil perpangkat yaitu `1000` ditulis diratakan pada sebelah kanan pada baris ke `16`.

5. Menampilkan objek, pada jarak baris pertama diberi jarak `3` baris, lalu di awali dengan angka `4`. Di baris selanjutnya setelah angka `4` diberi jarak `16` baris dimana hasil perpangkat yaitu `10000` ditulis diratakan pada sebelah kanan pada baris ke `16`.

6. Menampilkan objek, pada jarak baris pertama diberi jarak `3` baris, lalu di awali dengan angka `5`. Di baris selanjutnya setelah angka `5` diberi jarak `16` baris dimana hasil perpangkat yaitu `100000` ditulis diratakan pada sebelah kanan pada baris ke `16`.

7. Menampilkan objek, pada jarak baris pertama diberi jarak `3` baris, lalu di awali dengan angka `6`. Di baris selanjutnya setelah angka `6` diberi jarak `16` baris dimana hasil perpangkat yaitu `1000000` ditulis diratakan pada sebelah kanan pada baris ke `16`.

8. Menampilkan objek, pada jarak baris pertama diberi jarak `3` baris, lalu di awali dengan angka `7`. Di baris selanjutnya setelah angka `7` diberi jarak `16` baris dimana hasil perpangkat yaitu `10000000` ditulis diratakan pada sebelah kanan pada baris ke `16`.

9. Menampilkan objek, pada jarak baris pertama diberi jarak `3` baris, lalu di awali dengan angka `8`. Di baris selanjutnya setelah angka `8` diberi jarak `16` baris dimana hasil perpangkat yaitu `100000000` ditulis diratakan pada sebelah kanan pada baris ke ``16``.

10. Menampilkan objek, pada jarak baris pertama diberi jarak `3` baris, lalu di awali dengan angka `9`. Di baris selanjutnya setelah angka `9` diberi jarak `16` baris dimana hasil perpangkat yaitu `1000000000` ditulis diratakan pada sebelah kanan pada baris ke ``16``.

11. Menampilkan objek, pada jarak baris pertama diberi jarak `3` baris, lalu di awali dengan angka `10`. Di baris selanjutnya setelah angka `10` diberi jarak `16` baris dimana hasil perpangkat yaitu `10000000000` ditulis diratakan pada sebelah kanan dari baris ke ``16``.

Jika perintah di atas dijalankan maka outputnya, yaitu :

[]()

# Lab 2

