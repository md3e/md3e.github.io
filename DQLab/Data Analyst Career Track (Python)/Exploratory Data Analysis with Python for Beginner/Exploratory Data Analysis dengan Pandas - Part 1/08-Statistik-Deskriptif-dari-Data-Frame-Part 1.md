# Statistik Deskriptif dari Data Frame - Part 1

Statistik deskriptif atau summary dalam Python - Pandas, dapat diperoleh dengan menggunakan fungsi **describe()**, yaitu:

![QKJBvR.md.png](https://iili.io/QKJBvR.md.png)

Function describe dapat memberikan informasi mengenai nilai rataan, standar deviasi dan IQR (interquartile range).

Ketentuan umum:

Secara umum function **describe()** akan secara otomatis mengabaikan kolom category dan hanya memberikan summary statistik untuk kolom berjenis numerik.
Kita perlu menambahkan argument bernama **include = "all"** untuk mendapatkan summary statistik atau statistik deskriptif dari kolom numerik dan karakter.
yaitu

![QKJoTN.md.png](https://iili.io/QKJoTN.md.png)

**Contoh penggunaan describe() di Pandas!**

Terdapat dataframe Pandas dengan nama **nilai_skor_df** dengan informasi seperti gambar dibawah:

![QKJA4s.md.png](https://iili.io/QKJA4s.md.png)

dengan menggunakan fungsi describe pada **nilai_skor_df**

![QKJlu2.md.png](https://iili.io/QKJlu2.md.png)

menghasilkan

![QKJOuV.md.png](https://iili.io/QKJOuV.md.png)

Klik tombol Next untuk melanjutkan.
