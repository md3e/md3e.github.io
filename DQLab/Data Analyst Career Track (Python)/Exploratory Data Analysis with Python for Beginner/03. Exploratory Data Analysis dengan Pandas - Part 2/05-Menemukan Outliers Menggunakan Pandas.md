# Menemukan Outliers Menggunakan Pandas

Sebelum menuju ke step by step dalam menemukan **outliers**, sedikit intermezo dahulu mengenai definisi dari **outliers**.

**Outliers** merupakan data observasi yang muncul dengan nilai-nilai ekstrim. Yang dimaksud dengan nilai-nilai ekstrim dalam observasi adalah nilai yang jauh atau beda sama sekali dengan sebagian besar nilai lain dalam kelompoknya.

![QuuF9t.md.png](https://iili.io/QuuF9t.md.png)

Pada umumnya, outliers dapat ditentukan dengan metric IQR (interquartile range).

Rumus dasar dari IQR: Q3 - Q1. Dan data suatu observasi dapat dikatakan outliers jika memenuhi kedua syarat dibawah ini:
- data < Q1 - 1.5 * IQR
- data > Q3 + 1.5 * IQR
 

Syntax di Python:

![QuRAZu.md.png](https://iili.io/QuRAZu.md.png)

Contoh case: mengidentifikasi IQR dari dataframe **nilai_skor_df**

![Qu5TSp.md.png](https://iili.io/Qu5TSp.md.png)

**Hasil**:

![Qu7dss.png](https://iili.io/Qu7dss.png)

Karena saat ini memiliki skor IQR, saatnya untuk menentukan Outliers. Kode di bawah ini akan memberikan output dengan beberapa nilai True atau False. Titik data di mana terdapat False yang berarti nilai-nilai ini valid sedangkan True menunjukkan adanya outliers.

![Qu7UEG.md.png](https://iili.io/Qu7UEG.md.png)

menghasilkan

![QuYzyN.png](https://iili.io/QuYzyN.png)
