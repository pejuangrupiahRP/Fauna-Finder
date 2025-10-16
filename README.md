🐾 Fauna Finder

Klasifikasi Jenis Hewan untuk Mendukung Konservasi Satwa Langka

Fauna Finder adalah proyek deep learning yang dikembangkan untuk mengidentifikasi spesies satwa langka di Indonesiadan beberapa hewan yang sering di jumpai di sekitar kita. Aplikasi ini menggunakan Convolutional Neural Network (CNN) untuk melakukan klasifikasi citra hewan secara otomatis dan akurat.
Tujuannya adalah mendukung upaya konservasi dengan memberikan alat bantu identifikasi cepat, akurat, dan mudah diakses melalui aplikasi mobile dan API berbasis web.

📘 Deskripsi Proyek

Indonesia memiliki keanekaragaman hayati yang sangat tinggi, termasuk berbagai satwa langka yang terancam punah.
Proyek Fauna Finder dikembangkan untuk membantu konservasi satwa langka melalui teknologi Deep Learning, khususnya dengan pemanfaatan CNN (Convolutional Neural Network) yang mampu mengenali pola visual dari gambar hewan.

Model yang dikembangkan dapat:

Mengklasifikasi jenis hewan langka seperti Jalak Bali, Komodo, Macan Tutul, dan Orang Utan

Mengidentifikasi gambar yang diunggah atau diambil melalui kamera

Menyediakan informasi deskriptif tentang satwa tersebut

Diakses melalui aplikasi mobile atau API yang dideploy di Hugging Face dan Vercel

🚀 Fitur Utama

🔍 Klasifikasi Satwa Langka berbasis CNN

📸 Deteksi Gambar dan Kamera langsung dari perangkat pengguna

🧠 Model Deep Learning dengan akurasi hingga 83%

☁️ Deploy Model di Hugging Face Spaces

🌐 Deploy API Backend dengan Express.js di Vercel

📱 Tampilan Mobile Friendly: Halaman utama, dashboard, deskripsi, dan kamera

🧩 Arsitektur Sistem

Model Deep Learning (CNN)
Dibangun dengan TensorFlow/Keras untuk klasifikasi multi-kelas citra hewan.

API Backend (Express.js)
Menyediakan endpoint prediksi gambar menggunakan integrasi dengan model di Hugging Face.

Frontend (Aplikasi Mobile)
Menampilkan hasil klasifikasi, deskripsi hewan, dan fitur kamera.

Deployment

Model: Hugging Face Spaces

API: Vercel

📊 Dataset

Dataset dikumpulkan dari Kaggle dan mencakup 8 kelas:

No	Spesies	Jumlah Citra
1	Jalak Bali	1487
2	Komodo	1500
3	Macan Tutul	1075
4	Orang Utan	1156
5	Anjing	1500
6	Ayam	1500
7	Kucing	1500
8	Kupu-Kupu	1500
⚙️ Teknologi yang Digunakan

Python (TensorFlow, Keras, NumPy, Matplotlib)

Deep Learning (CNN)

Express.js + Node.js

Gradio Client

Hugging Face Spaces

Vercel Deployment

Postman (pengujian API)

Android Mobile UI (Mockup)

📈 Hasil dan Akurasi

Akurasi Model: 83%

Metode Evaluasi: Confusion Matrix, Precision, Recall, dan F1-Score

Output: Label spesies satwa dengan confidence rate
