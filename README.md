# aplikasi-Flask-untuk-klasifikasi-sampah-berbasis-model-CNN

Oke ✨, saya gabungkan semuanya jadi satu file **README.md** yang sudah rapi, lengkap dengan struktur project, cara install, run, fitur, catatan, lisensi, dan juga bagian screenshot kalau nanti kamu mau tambahkan.

Berikut kodenya:

```markdown
# 🗑️ Trash Classifier Web App

Aplikasi web berbasis **Flask** untuk melakukan klasifikasi sampah menggunakan model **TensorFlow Lite (.tflite)**.  
Project ini dibuat untuk mendukung transparansi dan efektivitas pengelolaan sampah melalui sistem bank sampah digital.

---

## 📂 Struktur Project
```

.
├── app.py                # Main Flask application
├── model\_fix.tflite      # Trained CNN model in TensorFlow Lite format
├── templates/
│   └── index.html        # Web interface for uploading images
├── static/               # (optional) CSS/JS/Images
├── .venv/                # Virtual environment (tidak perlu di-push ke GitHub)
└── Trash.ipynb           # Notebook for training and testing the model

````

---

## 🚀 Cara Menjalankan

### 1. Clone Repository
```bash
git clone https://github.com/username/trash-classifier-flask.git
cd trash-classifier-flask
````

### 2. Buat Virtual Environment (Opsional tapi disarankan)

```bash
python -m venv .venv
source .venv/bin/activate   # Mac/Linux
.venv\Scripts\activate      # Windows
```

### 3. Install Dependencies

Untuk kebutuhan full (Flask + TensorFlow + Pillow + Numpy):

```bash
pip install flask tensorflow pillow numpy
```

Jika hanya menjalankan model `.tflite` tanpa training:

```bash
pip install flask pillow numpy
```

### 4. Jalankan Aplikasi

```bash
python app.py
```

Aplikasi akan berjalan di browser lokal:

```
http://127.0.0.1:5000
```

---

## 🖼️ Fitur

* Upload gambar sampah dari browser.
* Model CNN TensorFlow Lite memprediksi jenis sampah.
* Hasil klasifikasi ditampilkan langsung di halaman web.

---

## 📸 Contoh Tampilan

Jika ingin menambahkan screenshot hasil aplikasi, simpan gambar di folder `static/` lalu tambahkan ke README:

```markdown
![Preview](static/preview.png)
```

---

## 📝 Catatan

* Folder `.venv/` **jangan di-push ke GitHub**.
* File `Trash.ipynb` digunakan untuk eksperimen/training model, bukan untuk deployment.
* Model yang dipakai di web adalah `model_fix.tflite`.

---

## 📜 Lisensi

MIT License © 2025 Ezra Kristanto Nahumury

```

---

Mau saya bikinkan juga **badge GitHub** (misalnya Python, Flask, TensorFlow) biar README-mu makin keren dan profesional?
```
