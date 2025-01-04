# Klasifikasi-Gambar-Daun-Untuk-Identifikasi-Jenis-Tanaman-menggunakan-Metode-CNN

### **Anggota Kelompok**
- Muhamad Ramadani (222102001)
- Salma Saffana Rizqi (222102031)
- Erika Mellyana Nur Fajrianti (222102019)

---

## **Deskripsi**
Project ini bertujuan untuk mengidentifikasi jenis tanaman berdasarkan gambar daunnya menggunakan metode **Convolutional Neural Network (CNN)**. Dataset yang digunakan terdiri dari 9 jenis daun tumbuhan, yaitu:  
- **Belimbing Wuluh**  
- **Jambu Biji**  
- **Jeruk Nipis**  
- **Kemangi**  
- **Lidah Buaya**  
- **Nangka**  
- **Pandan**  
- **Pepaya**  
- **Seledri**  

CNN merupakan salah satu teknik dari Artificial Neural Network (ANN) yang dirancang untuk memproses data gambar. Teknik ini banyak digunakan dalam berbagai aplikasi seperti klasifikasi gambar, segmentasi, dan deteksi objek, karena kemampuannya yang unggul dalam mengekstraksi fitur dari gambar dan menghasilkan hasil akurasi yang tinggi.

---

## **Dataset**
Dataset yang digunakan dalam project ini adalah **Indonesia Herb Leaf Dataset 3500**, yang diunduh dari [Mendeley Data](https://data.mendeley.com/datasets/s82j8dh4rr/1). Dari total 10 kelas yang tersedia dalam dataset, project ini hanya menggunakan 9 jenis daun. Alasan pemilihan ini adalah untuk memastikan distribusi data lebih seimbang, sehingga model dapat dilatih dengan lebih efektif dan menghasilkan performa yang lebih baik dalam mengklasifikasikan jenis daun.

---

## **Hasil**
Model CNN yang telah dibangun menunjukkan performa yang baik dalam klasifikasi gambar daun. Berikut adalah beberapa metrik performa:  
- **Akurasi pelatihan tertinggi**: 93.31%  
- **Akurasi keseluruhan pada data validasi**: 88%  

Model memberikan hasil optimal pada beberapa jenis daun, seperti **Kemangi**, **Pepaya**, dan **Seledri**, dengan metrik sempurna. Namun, masih ada ruang untuk perbaikan pada kelas tertentu, seperti **Jeruk Nipis** dan **Nangka**, untuk meningkatkan recall dan precision.

Dengan pengoptimalan lebih lanjut seperti augmentasi data, pengaturan hyperparameter, atau penanganan ketidakseimbangan kelas, model ini berpotensi memberikan hasil yang lebih akurat.

---

**Terima kasih!**
