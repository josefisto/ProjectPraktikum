<p align="center">
	BAHASA PEMROGRAMAN
</p>
<p align="center">
	KONDISIONAL DAN PERULANGAN
</p>
<p align="center">
	Dosen : Agung Nugroho, M.Kom
</p>
<p align="center"> 
	<b>Tugas untuk memenuhi syarat penilain pada Pert-7</b>
</p>

<p align="center">
	<img src="Logo/logo.png" alt="UPB" width="500" height="400">
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
	<img src="Logo/blank.png" width="20" height="20">
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

# Latihan 1

## Perulangan Bersarang for / Nested For

![Latihan 1](Screenshot/Latihan1.png)

Pada gambar di atas ditunjukkan bahwa hasil dari syntax yang di jalankan berupa pada gambar di bawah ini.

![Syntax](Screenshot/SyntaxLat1.png)

Keterangan syntax di atas dapat di uraikan, yaitu :

- `x = 10` dan `y = x` merupakan data integer
- `for i in range(x):` merupakan perulangan dimana data x di ulang hingga telesai
- `for j in range(y):` merupakan perulangan dimana data y melakukan perulang pada data x hingga data selesai terhitung
- `s=i+j` merupakan hasil dari perulangan dari i dengan j hingga hasil data perulangan digabungkan
- `print("{0:>5}". format(s), end='')` untuk menampilkan hasil data. Dimana `{0:>5}` memberi jarak data tertata rapih, `format(s)` menampilkan hasil dari i dengan j, `end=''` menata data secara horizontal
- `print()` menampilkan hasil dari data output `print("{0:>5}". format(s), end='')` di layar

Output atau hasil pada layar :

![Output](Screenshot/OutputLat1.png)

# Latihan 2

## Penggunaan Number

![Latihan2](Screenshot/Latihan2.png)

Pada gambar di atas ditunjukkan bahwa hasil dari syntax yang di jalankan berupa pada gambar di bawah ini.

![Syntax](Screenshot/SyntaxLat2.png)

Keterangan syntax di atas dapat di uraikan, yaitu :

- `import random` merupakan fungsi data number yang ada di python berfungsi menampilkan hasil data secara acak
- `x = int(input("Nilai Data: ")` merupakan data nilai integer yang nantinya nilai disebutkan bebas
- `for i in range(x):` fungsi perulangan dimana x nilai datanya akan di ulang
- `i = random.uniform(0.0, 0.5)` data i yang nantinya akan di hasilkan pada data random(teracak) dan uniform merupakan bilangan float, yang di mulai dari `0.0` sampai `0.5`

Output atau layar yang di hasilkan :

![Output](Screenshot/OutputLat2.png)

