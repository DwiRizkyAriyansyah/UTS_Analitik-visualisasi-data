
# 👟 Adidas vs Nike - Product Review Analysis

Proyek ini bertujuan untuk menganalisis data produk Adidas dan Nike serta memprediksi jumlah ulasan (`Reviews`) menggunakan beberapa model machine learning. Analisis dilakukan menggunakan Python dan Jupyter Notebook.

---

## 📦 Dataset

- **Nama File:** `Adidas Vs Nike.csv`
- Berisi data produk dari dua merek besar: **Adidas** dan **Nike**
- Fitur utama mencakup:
  - `Brand`
  - `Rating`
  - `Price`
  - `Reviews` (target)
  - dan beberapa atribut produk lainnya

---

## ⚙️ Proses Analisis

1. **Eksplorasi dan Pembersihan Data**
   - Menghapus missing values
   - Encoding kolom kategorikal
2. **Feature Scaling**
   - Standardisasi fitur numerik
3. **Modeling**
   - Tiga model yang digunakan:
     - Linear Regression
     - Naive Bayes
     - Decision Tree Regressor
4. **Evaluasi**
   - Menggunakan **Mean Squared Error (MSE)** dan **R² Score**
   - Visualisasi perbandingan performa model

---

## 🏁 Hasil

- Model terbaik berdasarkan nilai **R² Score tertinggi** adalah:
  - ✅ **Decision Tree Regressor**
- Artinya, model ini paling akurat dalam memprediksi jumlah ulasan produk berdasarkan fitur yang tersedia.

---

## 📁 Struktur Folder

```
📦 adidas-vs-nike-analysis
├── Adidas_VS_Nike_Analysis.ipynb   # Notebook utama
├── Adidas Vs Nike.csv              # Dataset
└── README.md                       # Dokumentasi proyek ini
```

---

## 💡 Catatan Tambahan

- Proyek ini cocok sebagai contoh analisis regresi dengan data real-world.
- Bisa dikembangkan lebih lanjut menggunakan hyperparameter tuning atau model yang lebih kompleks (Random Forest, XGBoost, dll).

---

## 🧑‍💻 Author

Made with 🧠 & ❤️ by [Your Name]
