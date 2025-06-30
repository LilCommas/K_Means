#K-Means Clustering on Iris Dataset

Project ini merupakan implementasi **K-Means Clustering** sederhana menggunakan dataset klasik **Iris**. Dataset ini berisi fitur morfologi bunga seperti panjang dan lebar kelopak dan sepal, yang digunakan untuk mengelompokkan bunga ke dalam klaster tanpa mengetahui label aslinya.

---

##Dataset
Dataset yang digunakan: `IRIS.csv`  
Jumlah data: 150 baris  
Fitur yang digunakan:
- `sepal_length`
- `sepal_width`
- `petal_length`
- `petal_width`

Label asli (`species`) digunakan untuk evaluasi akhir, **tidak dipakai saat training model**.

---

##Tujuan Proyek
- Melakukan **unsupervised clustering** (tanpa label) menggunakan algoritma K-Means.
- Mengelompokkan data bunga iris ke dalam 3 klaster berdasarkan fitur numerik.
- Membandingkan hasil klasterisasi dengan label asli (`species`).
- Visualisasi distribusi dan hasil klasterisasi.

---

##Library yang Digunakan
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
