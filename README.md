#  Klasifikasi Gambar Bunga

Proyek ini dibuat untuk memprediksi gambar rose, tulip, dandelion, sunflower, daisy

## 📦 Library yang Digunakan

- Python  
- TensorFlow  
- Scikit-learn  
- Pandas  
- Matplotlib  
---

## 🗂️ Struktur Folder Proyek

- `notebook.ipynb`   : Notebook untuk training dan evaluasi model  
- `saved_model/`                        : Folder berisi file untuk deployment
  - `variables/`                 : menyimpan bobot dan variabel model 
  - - `variables.data-00000-of-00001` 
  - - `variables.index`   
- `tfjs_model/`               :model yang dapat dijalankan berbasis JavaScript
  - - `model.json`            : Konfigurasi model
  - - `group1-shard1of1.binn`
  - - `group1-shard1of2.binn`
  - - `group1-shard1of3.bin` 
- `tflite/`                      :mengoptimalkan penggunaan model di perangkat mobile
  - `model.tflite`        :  model yang sudah dioptimalkan untuk digunakan di perangkat mobile 
  - `label.txt`            : daftar label kelas yang digunakan oleh model
- `requirements.txt`               : File daftar pustaka yang dibutuhkan  
- `README.md`                      : Dokumentasi utama proyek  


## 🚀 Cara Menjalankan Proyek

Berikut adalah langkah-langkah yang dapat diikuti untuk menjalankan proyek ini:

### 1. Menyiapkan Lingkungan Virtual

Sebelum memulai, pastikan Anda menggunakan virtual environment agar dependensi proyek terisolasi dengan baik. Untuk membuat dan mengaktifkan lingkungan virtual, jalankan perintah berikut di terminal:

- **Untuk Windows:**
  ```bash
  python -m venv venv
  .\venv\Scripts\activate

- **Untuk Linux/mac:**
  ```bash
  python3 -m venv venv
  source venv/bin/activate
  
### 2. Instalasi Dependensi
 pip install -r requirements.txt
 
### 3. Jalankan proyek
 - Pada saat menjalankan cell Import module, masukan file kaggle.json. File tersebut didapatkan setelah anda mendaftarkan akun kaggle, lalu setelah mendaftar Klik Setting, gulir kebawah Cari API (create new token), lalu unduh. Setelah unduh, masukan file kaggle.json 
 - Run Cell analisis lainnya
 


