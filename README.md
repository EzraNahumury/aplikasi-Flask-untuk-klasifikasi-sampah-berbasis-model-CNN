
# 🗑️ Aplikasi Flask untuk Klasifikasi Sampah Berbasis Model CNN

Aplikasi web berbasis **Flask** untuk melakukan klasifikasi sampah menggunakan model **TensorFlow Lite (.tflite)**.  
Project ini dibuat untuk mendukung transparansi dan efektivitas pengelolaan sampah melalui sistem bank sampah digital.

---


---

## 🚀 Cara Menjalankan

### 1. Clone Repository
```bash
git clone https://github.com/username/aplikasi-Flask-untuk-klasifikasi-sampah-berbasis-model-CNN.git
cd aplikasi-Flask-untuk-klasifikasi-sampah-berbasis-model-CNN
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

## 📝 Catatan

* Folder `.venv/` **jangan di-push ke GitHub**.
* File `Trash.ipynb` digunakan untuk eksperimen/training model, bukan untuk deployment.
* Model yang dipakai di web adalah `model_fix.tflite`.

---
