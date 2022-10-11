# Sorting Menggunakan Pandas

Sorting adalah sebuah metode mengurutkan data berdasarkan syarat kolom tertentu dan biasanya digunakan untuk melihat nilai maksimum dan minimum dari dataset. Library Pandas sendiri menyediakan fungsi sorting sebagai fundamental dari exploratory data analysis.

Syntax untuk operasi sorting pada Pandas:
```python
nama_dataframe.sort_values(by="nama_kolom")
```

**Contoh:**
_Sorting_ terhadap dataset nila_skor_df berdasarkan age!

```python
nilai_skor_df.sort_values(by="Age")
```

menghasilkan

![QQqSoX.png](https://iili.io/QQqSoX.png)

Function tersebut akan secara default mengurutkan secara ascending (dimulai dari nilai terkecil), untuk dapat mengurutkan secara descending (nilai terbesar lebih dahulu), dapat menggunakan properti tambahan:
```python
nama_dataframe.sort_values(by="nama_kolom", ascending=False)
```

**Contoh:**
_Sorting_ terhadap dataset nilai_skor_df berdasarkan age dimulai dari umur tertua!
```python
nilai_skor_df.sort_values(by="Age", ascending=False)
```

menghasilkan

![QQq6lf.png](https://iili.io/QQq6lf.png)

Fungsi _sorting_ di Pandas juga dapat dilakukan menggunakan lebih dari satu kolom sebagai syarat. Contohnya pada skenario di bawah, akan mencoba mengaplikasikan fungsi _sorting_ menggunakan Age dan Score sekaligus:

```python
# Syntax
nama_dataframe.sort_values(by=["nama_kolom_1", "nama_kolom_2"], ascending=[False, True])

# Contoh penggunaan pada dataframe nilai_skor_df
nilai_skor_df.sort_values(by=["Age", "Score"], ascending=[True, False])
```
