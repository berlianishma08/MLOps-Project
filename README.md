# MLOps-Project

## Gambaran Umum Proyek
Proyek ini mengimplementasikan pipeline MLOps untuk memprediksi kelangsungan hidup penumpang Titanic.

## Sumber Data
- Kumpulan data primer: Kumpulan data Kaggle Titanic (train.csv dan test.csv)
- https://www.kaggle.com/c/titanic/data

## Struktur Direktori
MLOps-Project-Model/ <br />
├── Data <br />
│   ├── clean                   # Data siap latih <br />
│   └── raw                     # Data mentah awal <br />
├── Log                         # Catatan proses seperti pelatihan dan evaluasi <br />
├── Model <br />
│   ├── metadata                # Info tambahan model <br />
│   ├── model                   # Model yang sudah dilatih <br />
│   └── preprocessor            # Objek preprocessing (scaler, encoder, dll) <br />
├── myenv                       # Virtual environment proyek <br />
├── Notebook                    # Eksperimen dan analisis dengan Jupyter Notebook <br/>
├── Result <br />
│   ├── predict                 # Hasil prediksi data baru <br />
│   └── scores                  # Skor evaluasi model <br />
├── Script                      # Skrip Python untuk tiap tahap ML <br />
│   ├── data_preparation.py     # Persiapan data <br />
│   ├── train_model.py          # Pelatihan model <br />
│   ├── evaluate_model.py       # Evaluasi model <br />
│   ├── deploy_model.py         # Deployment model <br />
│   └── predict_data.py         # Prediksi data baru <br />
├── .gitignore                  # Daftar file yang diabaikan Git <br />
├── environment.yml             # Konfigurasi environment Conda <br />
├── Makefile                    # Otomatisasi perintah <br />
├── README.md                   # Dokumentasi proyek <br />
├── requirements.txt            # Dependensi Python (pip) <br />
└── timestamp.txt               # Catatan waktu proses <br />

## Tools Used
- Python
- Pandas, NumPy for data processing
- Google Colab
