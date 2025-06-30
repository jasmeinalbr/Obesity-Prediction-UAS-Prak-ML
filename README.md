# TUGAS AKHIR - Prediksi Kategori Obesitas

Proyek ini merupakan tugas akhir yang bertujuan untuk membangun model machine learning untuk memprediksi kategori obesitas berdasarkan dataset `obesity_data.csv`. Proyek ini mencakup eksplorasi data, preprocessing, pelatihan tiga model (Logistic Regression, Random Forest, dan SVM), evaluasi performa, dan inferensi menggunakan model terbaik.

## Struktur Proyek
TUGAS AKHIR
├── data
│   └── obesity_data.csv          # Dataset utama yang berisi data obesitas
├── notebooks
│   └── obesity_prediction.ipynb  # Notebook Jupyter untuk analisis dan pemodelan
└── README.md                     # Dokumen ini

## Deskripsi

- **data/obesity_data.csv**: File CSV yang berisi data mentah dengan fitur seperti `Age`, `Gender`, `Height`, `Weight`, `BMI`, `PhysicalActivityLevel`, dan label `ObesityCategory`.
- **notebooks/obesity_prediction.ipynb**: Notebook Jupyter yang berisi kode untuk:
  - Eksplorasi Data (EDA)
  - Preprocessing (encoding kategorikal, standarisasi fitur)
  - Pelatihan dan evaluasi model (Logistic Regression, Random Forest, SVM)
  - Visualisasi (confusion matrix, perbandingan akurasi)
  - Inferensi dengan model terbaik (Random Forest)

## Persyaratan

Pastikan Anda memiliki lingkungan Python dengan library berikut terinstal:
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `numpy`

Anda dapat menginstal dependensi dengan perintah berikut:
```bash
pip install pandas matplotlib seaborn scikit-learn numpy
```

## Cara Penggunaan

### Kloning Repositori (jika menggunakan Git):
```bash
git clone <url-repositori>
cd TUGAS AKHIR
```

### Buka Notebook:
- Buka file `notebooks/obesity_prediction.ipynb` menggunakan Jupyter Notebook atau JupyterLab.
- Pastikan file `data/obesity_data.csv` berada di direktori `data/`.

### Jalankan Kode:
- Jalankan sel-sel secara berurutan untuk melihat hasil EDA, preprocessing, pelatihan model, evaluasi, dan inferensi.
- Perhatikan output visual seperti confusion matrix dan perbandingan akurasi model.

### Modifikasi (Opsional):
- Anda dapat menyesuaikan parameter model (misalnya, hyperparameter di GridSearchCV) atau menambahkan fitur baru di notebook sesuai kebutuhan.

## Hasil Utama

- **Model Terbaik**: Random Forest dengan akurasi 0.995, dipilih untuk inferensi karena performa terbaik.
- **Evaluasi**: Ketiga model (Logistic Regression, Random Forest, SVM) menunjukkan akurasi tinggi (0.965, 0.995, 0.980), dengan Random Forest memiliki minim kesalahan prediksi berdasarkan confusion matrix.
- **Inferensi**: Model digunakan untuk memprediksi kategori obesitas pada data baru dengan probabilitas per kategori.

## Kontribusi

Jika Anda ingin berkontribusi, silakan fork repositori ini, buat perubahan, dan ajukan pull request. Saran untuk perbaikan atau penambahan fitur sangat diterima!

## Lisensi

Tanpa lisensi spesifik

## Kontak

Untuk pertanyaan atau bantuan, silakan hubungi jasmein di jasmeinalbaar29@gmail.com
