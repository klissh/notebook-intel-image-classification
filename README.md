# 🏞️ Proyek Klasifikasi Gambar Pemandangan Alam

Proyek ini adalah submission untuk kelas **Belajar Machine Learning untuk Pemula** oleh Dicoding. Tujuannya adalah membangun sebuah model deep learning untuk mengklasifikasikan gambar pemandangan alam ke dalam enam kategori berbeda. Model ini dibangun menggunakan teknik **Transfer Learning** dengan memanfaatkan arsitektur **MobileNetV2**.

---

## 📚 Detail Proyek

-   **Dataset**: [Intel Image Classification](https://www.kaggle.com/datasets/puneet6060/intel-image-classification) (Natural Scenes) yang berisi ~17.000 gambar.
-   **Kategori (Kelas)**: `buildings`, `forest`, `glacier`, `mountain`, `sea`, `street`.
-   **Pembagian Dataset**: Dataset dibagi secara manual dengan rasio **60%** untuk data latih (*train*), **20%** untuk data validasi (*validation*), dan **20%** untuk data uji (*test*) menggunakan metode *stratified split*.
-   **Target Akurasi**: Mencapai akurasi di atas **85%** pada data training dan data testing.

---

## 🛠️ Teknologi yang Digunakan

Proyek ini dibangun menggunakan Python dengan beberapa library utama:

* ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
* ![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
* ![Scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
* ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
* ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
* ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

---

## 🚀 Cara Menjalankan

Untuk menjalankan proyek ini di lingkungan Anda sendiri, ikuti langkah-langkah berikut:

1.  **Clone Repository**
    ```sh
    git clone [https://github.com/klissh/notebook-intel-image-classification.git](https://github.com/klissh/notebook-intel-image-classification.git)
    cd NAMA_REPO
    ```

2.  **Buat Virtual Environment** (Opsional tapi direkomendasikan)
    ```sh
    python -m venv venv
    source venv/bin/activate  # Untuk Windows: venv\Scripts\activate
    ```

3.  **Install Dependensi**
    Pastikan Anda memiliki file `requirements.txt`, lalu jalankan:
    ```sh
    pip install -r requirements.txt
    ```

4.  **Jalankan Notebook**
    Buka dan jalankan file `notebook.ipynb` menggunakan Jupyter Notebook atau Google Colab.

---

## 📂 Struktur Direktori

Berikut adalah struktur file dan folder dalam submission ini:
.
├── /saved_model      # Model dalam format SavedModel
├── /tflite           # Model dalam format TFLite & label.txt
├── /tfjs_model       # Model dalam format TensorFlow.js
├── notebook.ipynb    # Notebook utama pengerjaan proyek
├── requirements.txt  # Daftar dependensi library
└── README.md         # File in
---

## 👤 Kontak

**Muhammad Muhibuddin Mukhlish**

* GitHub: [klissh](https://github.com/klissh)
* LinkedIn: [Muhammad Muhibuddin Mukhlish](https://www.linkedin.com/in/muhammad-muhibuddin-mukhlish/)