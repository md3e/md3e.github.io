# Tugas Praktek

Waktu sebentar lagi menunjukkan pukul dua belas siang. Sebentar lagi jam makan. Latihan praktik tadi sudah cukup jelas buatku, aku pun mulai membereskan modul dan hendak menutup laptop. Tapi kegiatanku terhenti ketika Andra sudah kembali dari rapatnya dan segera menghampiriku, “Aksara, kamu sempat mengevaluasi performa cabang A bukan?”

“Iya, terakhir aku sedang cek dari sisi dataframe order_df. Sudah mau diminta hasilnya?” Aku melirik ke arah Andra yang sedang mencoret-coret buku catatannya sembari berdiri dari balik meja kerjaku. 

“Bukan, ini ada tambahan quick summary dari segi kuantitas, harga, freight value, dan weight yang dibeli konsumen. Ada juga nih median dari total pembelian konsumen per transaksi. Jadi, bisa sekalian kamu analisis,” ujar Andra sembari merobek halaman buku catatannya dan memberikannya padaku.

“Tolong yah, Aksara. Soalnya sehabis ini saya ada rapat lanjutan lagi di luar kantor, mungkin baru balik sore nanti untuk kita bahas bersama hasilnya.”

“Siap,” jawabku yakin. Ini waktunya aku menunjukkan pada Andra kalau aku bisa!

Aku mengambil selotip dan menempelkan catatan dari Andra tadi di samping layar laptop sembari mulai membuat syntaks Phyton di code editor.

Silkan klik tombol **submit** untuk melanjutkan.

```python
import pandas as pd
order_df = pd.read_csv("https://storage.googleapis.com/dqlab-dataset/order.csv")
# Quick summary  dari segi kuantitas, harga, freight value, dan weight
print(order_df.describe())
# Median dari total pembelian konsumen per transaksi kolom price
print(order_df.loc[:, "price"].median())
```
