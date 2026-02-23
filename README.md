🎓 PENGEMBANGAN APLIKASI SISTEM KLASIFIKASI SIMPLISIA FRUTUS BERBAS WEB MENGGUNAKAN ALGORITMA CNN TRANSFER LEARNING

📖 Deskripsi

Aplikasi ini merupakan aplikasi pembelajaran berbasis web yang dikembangkan untuk membantu siswa **Farmasi** dalam mengidentifikasi jenis simplisia fructus menggunakan citra digital.

Aplikasi memanfaatkan teknologi Deep Learning dengan model Convolutional Neural Network (CNN) untuk melakukan klasifikasi citra simplisia fructus secara otomatis dengan tingkat akurasi yang optimal, tidak overfit maupun underfit. Sistem ini diharapkan dapat menjadi media pembelajaran interaktif dan inovatif dalam mata pelajaran Farmakognosi.

---

🧠 Metode yang Digunakan

- Deep Learning
- Convolutional Neural Network (CNN)
- Arsitektur model: Xception
- Klasifikasi citra berbasis upload gambar
- Evaluasi model menggunakan akurasi dan confusion matrix

Model hasil pelatihan disimpan dalam format ".h5" dan diintegrasikan langsung ke dalam aplikasi web berbasis Flask.

---

🛠️ Tech Stack

- Bahasa Pemrograman: Python
- Framework Web: Flask
- Deep Learning: TensorFlow / Keras
- Model CNN: Xception
- Frontend: HTML, CSS, JavaScript
- Tools: Git, GitHub

---

🎥 Demo Aplikasi

Demo penggunaan aplikasi dapat dilihat melalui video berikut:
👉 https://youtu.be/u-GqgQFD08E?si=zoSqWynZFNsQOEcC

---

🚀 Fitur Utama

- 📸 Upload citra simplisia fructus
- 🤖 Klasifikasi otomatis menggunakan CNN
- 📊 Menampilkan hasil prediksi
- 📈 Visualisasi akurasi training & validasi
- 📉 Confusion matrix untuk evaluasi model
- 🎓 Konten pembelajaran untuk siswa Farmasi yang User Friendly dengan Pengujian terhadap aplikasi berbasis ISO 25010

---

📂 Struktur Project

Projek-Tugas-Akhir-Skripsi-CNN-AI/
├── static/
│   ├── fructusadmin/
│   └── uploads/
├── templates/
│   ├── beranda.html
│   ├── belajar.html
│   ├── classifications.html
│   ├── cnn.html
│   └── developer.html
├── apps.py
├── passenger_wsgi.py
├── xception-fructus-99.23.h5
├── confusion matrix.png
├── training validasi akurasi.png
├── requirement.txt
└── README.md

---

⚙️ Cara Menjalankan Aplikasi

1. Clone repository
   git clone https://github.com/dianelnursa/Projek-Tugas-Akhir-Skripsi-CNN-AI.git
2. Masuk ke folder project
   cd Projek-Tugas-Akhir-Skripsi-CNN-AI
3. Install dependency
   pip install -r requirement.txt
4. Jalankan aplikasi Flask
   python apps.py
5. Buka browser dan akses
   http://127.0.0.1:5000

---

📊 Hasil Model

- Model CNN berbasis Xception
- Akurasi mencapai 99,23%
- Evaluasi model ditampilkan dalam:
  - Grafik training & validasi
  - Confusion matrix

---

🎯 Tujuan Pengembangan

- Membantu siswa Farmasi dalam mengenali simplisia fructus
- Menyediakan media pembelajaran berbasis AI
- Mengimplementasikan CNN dalam bidang pendidikan kesehatan
- Mendukung pembelajaran berbasis teknologi di SMK Kesehatan

---

👤 Pengembang

- Nama: Dian
- Project: Tugas Akhir / Skripsi
- Bidang: Artificial Intelligence & Web Development


---

📄 Lisensi

Project ini dikembangkan untuk keperluan akademik dan pembelajaran.
Penggunaan ulang diperbolehkan dengan mencantumkan sumber.

Apabila terdapat pertanyaan lebih lanjut terkait aplikasi ini, metode yang digunakan, atau permintaan source code training model dan dataset projek, silakan menghubungi pengembang melalui email berikut:

📧 Email: dianelnursa@gmail.com

Permintaan file training model akan dipertimbangkan khusus untuk keperluan akademik dan penelitian, dengan tetap memperhatikan etika penggunaan data dan hak cipta.

---

✨ Project ini merupakan implementasi nyata Deep Learning untuk mendukung pembelajaran Farmasi di tingkat SMK.
