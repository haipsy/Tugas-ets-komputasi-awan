# Tugas-ets-komputasi-awan
Repository ini digunakan untuk mengumpulkan tugas ETS
Proyek ini membangun end-to-end pipeline analisis sentimen cyberbullying berbasis AWS, dimulai dari pengumpulan 500 data sentimen berbahasa Indonesia yang disimpan di AWS S3 dengan struktur raw/processed dan fitur versioning. Data diproses melalui SageMaker menggunakan boto3, menghasilkan 312 data bersih setelah penghapusan missing value dan pembersihan teks, kemudian dilabeli menjadi dua kelas: cyberbully (68,9%) dan non-cyberbully (31,1%). Dari dua model yang diuji, Logistic Regression dipilih sebagai model final dengan akurasi tertinggi 93,65%, mengungguli Naive Bayes (90,48%), dan terbukti lebih andal dalam mendeteksi konteks kalimat yang ambigu.
Link Demo : https://youtu.be/AlfV4NeG_1U

Link Presentasi (gdrive) : https://drive.google.com/file/d/1WlzafPk3bd9UjWTdhQtgbFRUAA8XzJ-p/view?usp=sharing
