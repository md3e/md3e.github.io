# Rename Kolom Data Frame

Pada bagian ini, aku belajar cara mengganti nama kolom dataframe menggunakan Pandas. Mengganti nama kolom pada Pandas dapat dilakukan dengan 2 cara:
1. Menggunakan nama kolom;
2. Menggunakan indeks kolom.
 

**1. Rename menggunakan nama kolom**, Syntax:

```python
nama_dataframe.rename(columns={"column_name_before": "column_name_after"}, inplace=True)
```

Contoh penggunaan:
```python
nilai_skor_df.rename(columns={"Age": "Umur}, inplace=True)
```

**2. Rename menggunakan indeks kolom**, Syntax:
```python
nama_dataframe.columns.values[no_of_column] = "column_name_after"
```
Contoh penggunaan:

```python
nilai_skor_df.columns.value[0] = "Umur"
```
