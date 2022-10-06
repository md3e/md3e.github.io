# Mengenal dan Membuat Distribusi Data dengan Histogram

Tugas tambahan dari Andra tadi sudah kuselesaikan, selagi menunggu Andra kembali. Aku coba lanjut untuk menyimak pembahasan lanjutan mengenai *Exploratory Data Analysis* terlebih dulu.

Histogram merupakan salah satu cara untuk mengidentifikasi sebaran distribusi dari data. Histogram adalah grafik yang berisi ringkasan dari sebaran (dispersi atau variasi) suatu data. Pada histogram, tidak ada jarak antar batang/bar dari grafik. Hal ini dikarenakan bahwa titik data kelas bisa muncul dimana saja di daerah cakupan grafik. Sedangkan ketinggian bar sesuai dengan frekuensi atau frekuensi relatif jumlah data di kelas. Semakin tinggi bar, semakin tinggi frekuensi data. Semakin rendah bar, semakin rendah frekuensi data.

*__Syntax umum:__*

![Qoxkfn.md.png](https://iili.io/Qoxkfn.md.png)

Beberapa atribut penting dalam histogram pandas:
- *bins* = jumlah_bins dalam histogram yang akan digunakan. Jika tidak didefinisikan jumlah_bins, maka function akan secara default menentukan jumlah_bins sebanyak 10.
- *by* = nama kolom di DataFrame untuk di group by. (valuenya berupa nama column di dataframe tersebut).
- *alpha* = nilai_alpha untuk menentukan opacity dari plot di histogram. (value berupa range 0.0 - 1.0, dimana semakin kecil akan semakin kecil opacity nya)
- *figsize* = tuple_ukuran_gambar yang digunakan untuk menentukan ukuran dari plot histogram. Contoh: figsize=(10,12)

![QoINFn.md.png](https://iili.io/QoINFn.md.png)

Klik tombol Next untuk melanjutkan.
