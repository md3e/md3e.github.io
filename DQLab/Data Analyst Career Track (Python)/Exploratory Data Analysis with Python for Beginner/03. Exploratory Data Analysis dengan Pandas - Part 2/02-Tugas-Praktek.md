# Tugas Praktek

Baru saja aku menyimak beberapa halaman isi modul, Andra sudah kembali ke kantor dari rapat lanjutannya. Tampaknya Andra sosok yang begitu sibuk di kantor. Ketika tahu langkahnya berbelok menuju tempatku, aku dengan sigap menyiapkan laptop untuk menunjukkan hasil kerjaku padanya. 

“Pekerjaan tadi sudah selesai, Ndra. Bagaimana?” 

“Udah lebih rapi, ini nanti saya kasih ke kepala cabang untuk pertimbangan performa saat rapat,” ujar Andra cepat. Kulihat ia masih sibuk karena sesekali mengecek notifikasi ponselnya. 

Baru saja aku mau menutup program dan pergi ke pantry, Andra kembali memanggilku, “Satu lagi, Aksara.”

“Ada data tambahan lagi?” tebakku.

“Kamu buatkan price distributionnya juga ya dari pembelian produk di cabang tadi. Saya rasa itu penting untuk diberitahu ke mereka. Bikin saja dalam bentuk histogram price,” saran Andra. 

Aku pun kembali merebahkan diri di bangku dan mengutak-atik dataset order_df dengan jumlah bins=10:

```python
import pandas as pd
import matplotlib.pyplot as plt
order_df = pd.read_csv("https://storage.googleapis.com/dqlab-dataset/order.csv")
# plot histogram kolom: price
order_df[["price"]].hist(figsize=(4, 5), bins=10, xlabelsize=8, ylabelsize=8)
plt.show()  # Untuk menampilkan histogram plot
```
