# Klasifikasi Gambar Rock, Scissor, Paper dengan CNN Sederhana

## Deskripsi

Notebook ini mendemonstrasikan proses klasifikasi gambar Rock, Scissor, Paper menggunakan Convolutional Neural Network (CNN) sederhana. Dataset yang digunakan terdiri dari gambar tangan yang menunjukkan tiga kelas tersebut.

## Langkah-langkah

1. **Persiapan**:
   - Mengunduh dataset Rock, Scissor, Paper.
   - Membagi dataset menjadi set pelatihan, validasi, dan pengujian.
2. **Augmentasi Data**:
   - Menggunakan `ImageDataGenerator` untuk memperbesar variasi data.
3. **Membangun Model CNN**:
   - Menyusun model dengan beberapa lapisan konvolusi dan pooling.
   - Menambahkan lapisan fully connected untuk klasifikasi.
4. **Pelatihan Model**:
   - Mengompilasi model dengan optimizer Adam dan loss categorical cross-entropy.
   - Melatih model dengan data pelatihan dan validasi.
5. **Evaluasi Model**:
   - Mengukur akurasi model menggunakan data pengujian.
   - Menampilkan kurva akurasi dan loss selama pelatihan.
6. **Prediksi**:
   - Menggunakan model yang telah dilatih untuk memprediksi gambar baru.

## Dependensi

- TensorFlow
- Keras
- Matplotlib
- NumPy
- Pillow

## Cara Menjalankan

1. Unggah notebook ini ke Google Colab atau jalankan di Jupyter Notebook.
2. Pastikan dataset tersedia dalam direktori yang sesuai.
3. Jalankan semua sel kode secara berurutan.

## Hasil

Model yang dilatih dapat mengenali gambar tangan dengan cukup baik. Evaluasi menunjukkan tingkat akurasi yang tinggi pada data pengujian.

## Catatan

- Anda dapat menyesuaikan parameter pelatihan seperti learning rate, batch size, dan jumlah epochs untuk meningkatkan performa model.
- Jika ingin mencoba model yang lebih kompleks, bisa menambahkan lebih banyak lapisan konvolusi atau menggunakan transfer learning.
