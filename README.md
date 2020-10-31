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

Pada repository kali ini saya akan memberikan penjelasan pada Latihan pada halaman akhir dari materi Pert-6 yaitu Lab 1 dan Lab 2 yang terdiri dari Tipe Data, Variabel, Operator.

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

![Penggunaan End](Lab1/ScreenShot_Lab1/Perintah_Penggunaan-END.png)

 Pada perintah python di atas, untuk lebih jelasnya, yaitu :

- `print('A', end='')`, 
- `print('B', end='')`,
- `print('C', end='')`,
- `print()`
- `print('X')`
- `print('Y')`
- `print('Z')`

menunjukkan perintah bahwa ;
- A,B,C adalah garis baru "`end=''`" nantinya menyambung dengan variabel lanjutannya atau kalimat. Maka hasil yang akan keluar pada Output menjadi "ABC".
- jika X, Y, Z di print maka hasil dicetak menjadi baris baru di setiap paragrafnya.

 Maka hasil akan menjadi pada gambar di bawah ini.

![Penggunaan End](Lab1/ScreenShot_Lab1/Output_Penggunaan-END.png)

## Penggunaan Separator

`Penggunaan Separator` merupakan tanda pemisah dari objek yang dicetak atau menjadi satu kalimat yang mempunyai jarak penulisan setiap barisnya.

![Penggunaan Separator](Lab1/ScreenShot_Lab1/Perintah_Penggunaan_Separator.png)

Pada perintah python di atas, untuk lebih jelasnya, yaitu :

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

Atau hasil bisa dilihat pada gambar dibawah ini.

![Penggunaan Separator](Lab1/ScreenShot_Lab1/Output_Penggunaan_Separator.png)

## Penggunaan pada String Format

String format di gunakan sebagai konversi data ke bentuk string sebagai contoh bila 2 merupakan pangkat, dan 4 adalah angka, maka 4 pangkat 2 yaitu 16 maka konversi data tersebut termasuk jenis perpangkatan.

![Penggunaan pada String Format](Lab1/ScreenShot_Lab1/Perintah_Penggunaan_String_Format(1).png)

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

1. Jika `0` merupakan perpangkatan, maka `10` adalah angka dengan pangkat `0`. dan di cetak maka hasil yang keluar pada output adalah `1`.

2. Jika `1` merupakan perpangkatan, maka `10` adalah angka dengan pangkat `1`. dan di cetak maka hasil yang keluar pada output adalah `10`.

3. Jika `2` merupakan perpangkatan, maka `10` adalah angka dengan pangkat `2`. dan di cetak maka hasil yang keluar pada output adalah `100`.

4. Jika `3` merupakan perpangkatan, maka `10` adalah angka dengan pangkat `3`. dan di cetak maka hasil yang keluar pada output adalah `1000`.

5. Jika `4` merupakan perpangkatan, maka `10` adalah angka dengan pangkat `4`. dan di cetak maka hasil yang keluar pada output adalah `10000`.

6. Jika `5` merupakan perpangkatan, maka `10` adalah angka dengan pangkat `5`. dan di cetak maka hasil yang keluar pada output adalah `100000`.

7. Jika `6` merupakan perpangkatan, maka `10` adalah angka dengan pangkat `6`. dan di cetak maka hasil yang keluar pada output adalah `1000000`.

8. Jika `7` merupakan perpangkatan, maka `10` adalah angka dengan pangkat `7`. dan di cetak maka hasil yang keluar pada output adalah `100000000`.

9. Jika `8` merupakan perpangkatan, maka `10` adalah angka dengan pangkat `8`. dan di cetak maka hasil yang keluar pada output adalah `100000000`.

10. Jika `9` merupakan perpangkatan, maka `10` adalah angka dengan pangkat `9`. dan di cetak maka hasil yang keluar pada output adalah `1000000000`.

11. Jika 10 merupakan perpangkatan, maka 10 adalah angka dengan pangkat 10. dan di cetak maka hasil yang keluar pada output adalah 10000000000.

Maka jika perintah dijalankan hasil yang keluar ialah :

![Penggunaan String Format](Lab1/ScreenShot_Lab1/Output_Penggunaan_String_Format(1).png)

**(Gambar di bawah merupakan lanjutan perintah pada string format)**

![Penggunaan pada String Format](Lab1/ScreenShot_Lab1/Perintah_Penggunaan_String_Format(2).png)

Pada perintah di atas merupakan jenis konversi data perpangkatan yang mempunyai jarak antar baris yang disejajarkan dengan yang lain, untuk lebih jelasnya yaitu :

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

![Penggunaan String Format](Lab1/ScreenShot_Lab1/Output_Penggunaan_String_Format(2).png)

# Lab 2

