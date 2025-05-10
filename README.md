# Perceptron-JST-UAS

🧠 Perceptron untuk Klasifikasi Spesies Penguin
Notebook ini berisi implementasi dari Single-Layer Perceptron untuk melakukan klasifikasi dua spesies penguin: Adelie dan Gentoo berdasarkan fitur morfologis seperti panjang paruh, panjang sirip, kedalaman paruh, dan massa tubuh.

📌 Fitur-fitur utama:

Dataset diambil dari repositori penguins.csv via URL.

Data preprocessing dilakukan untuk memilih dua spesies dan menghapus data yang hilang.

Implementasi fungsi aktivasi step function.

Pelatihan model Perceptron menggunakan pembaruan bobot berbasis error pada setiap epoch.

Hasil pelatihan dicatat dalam bentuk DataFrame yang menunjukkan perubahan bobot (delta w), output prediksi (y'), nilai aktivasi (V), dan error untuk setiap data dan epoch.

⚙️ Parameter:

Learning rate: 0.1

Epoch: 5
