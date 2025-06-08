# Prediksi Status Akademik Mahasiswa dengan Ensemble Learning

Proyek ini bertujuan untuk membangun model prediktif guna mengklasifikasikan status akademik akhir mahasiswa (Lulus, Dropout, atau Masih Enrolled) menggunakan metode ensemble learning seperti Random Forest, XGBoost, Stacking, dan AdaBoost.

## 📁 Struktur Folder

- `data/` : Dataset mentah yang digunakan (dari UCI Machine Learning Repository)
- `notebooks/` : Notebook eksperimen dan pelatihan model
- `laporan/` : File laporan makalah akhir (Word)

## 🔍 Metodologi

1. **EDA & Preprocessing**  
   - Visualisasi distribusi kelas
   - Encoding & scaling
   - Train-test split dengan stratifikasi

2. **Modeling**  
   - ✅ Random Forest  
   - ✅ XGBoost  
   - ✅ Stacking Classifier  
   - ✅ AdaBoost  

3. **Evaluasi**  
   - Accuracy, F1-Score, Confusion Matrix, Cohen's Kappa

## 📊 Hasil Akurasi

| Model         | Akurasi |
| ------------- | ------- |
| Random Forest | 76.9%   |
| XGBoost       | 80.7%   |
| Stacking      | 77.1%   |
| AdaBoost      | 77.2%   |

## 📚 Dataset

Dataset diambil dari [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/).  
Nama: *Predict students’ dropout and academic success*

## 👤 Author

Nizar Qulubi  
Mahasiswa Teknik Informatika  
Email: nizarqulubi2@gmail.com

---

Silakan gunakan atau modifikasi proyek ini untuk kebutuhan pembelajaran, penelitian, atau portofolio pribadi.

