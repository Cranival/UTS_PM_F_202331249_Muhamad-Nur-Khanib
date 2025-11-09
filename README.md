
## 📌 UTS Machine Learning Project

### 📖 Deskripsi
Proyek ini merupakan tugas UTS yang mencakup dua bagian utama:
1. **Regresi Linear**  
   Memprediksi *Government Transparency* berdasarkan *Corruption Perception* menggunakan dataset `R04_corruptions.csv`.
   
2. **Klasifikasi Naive Bayes**  
   Memprediksi apakah seseorang memiliki diabetes berdasarkan fitur kesehatan menggunakan dataset `K02_diabetes.csv`.

---

### ✅ Fitur Utama
- **Preprocessing Data**:  
  - Menghapus missing values  
  - Encoding kolom kategorikal (untuk klasifikasi)
- **Modeling**:  
  - Regresi Linear (sklearn)  
  - Naive Bayes (GaussianNB)
- **Evaluasi**:  
  - Regresi: R², MSE, RMSE, MAE  
  - Klasifikasi: Akurasi + Confusion Matrix
- **Visualisasi**:  
  - Scatter plot + garis regresi  
  - Confusion Matrix (heatmap)

---

### 📂 Struktur Notebook
- **Bagian 1: Regresi**
  - Load dataset
  - Scatter plot
  - Korelasi
  - Training model
  - Visualisasi garis regresi
  - Evaluasi (R², MSE, RMSE, MAE)
- **Bagian 2: Klasifikasi**
  - Load dataset
  - Encoding data kategorikal
  - Split train/test
  - Training Naive Bayes
  - Akurasi
  - Confusion Matrix

---

### 🔧 Teknologi
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

### 🚀 Cara Menjalankan
1. Clone repository:
   ```bash
   git clone https://github.com/username/uts-machine-learning.git
   ```
2. Masuk ke folder:
   ```bash
   cd uts-machine-learning
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Jalankan Jupyter Notebook:
   ```bash
   jupyter notebook UTS_Machine_Learning_Project.ipynb
   ```

---

👉 Mau saya buatkan juga **README.md lengkap** (siap upload ke GitHub) dan **requirements.txt** untuk dependencies?
