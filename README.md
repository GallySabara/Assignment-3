**# Assignment 03 computer vision & natural language  processing**

**03_KELOMPOK F_1 Pemrosesan Gambar Digital**.
1.  Pustaka : Scikit-image, OpenCV, Numpy, Matplotlib
2.  Tujuan : Memproses gambar digital dengan operasi dasar pemrosesan citra.

**Langkah-langkah :**
1.  Konversi Warna : Ubah saluran warna dari BGR ke RGB dan dari BGR ke 
    skala abu-abu, lalu dari skala abu-abu ke biner menggunakan ambang batas.
2.  Plot Histogram : Visualisasikan histogram dari gambar asli dan gambar 
    greyscale untuk analisis distribusi intensitas.
3.  Pooling dan Block Reduce :
   -  Gunakan block_reduce()dengan fungsi np.minuntuk operasi min pooling 
      dan np.meanuntuk average pooling.
4.  CLAHE : Terapkan CLAHE (Contrast Limited Adaptive Histogram 
    Equalization) untuk mencerahkan gambar gelap, dan menyimpan gambar 
    hasilnya dengan ekstensi .png.

**03_KELOMPOK F_2 Pembelajaran Transfer untuk Klasifikasi Digit Tulisan Tangan**
1.  Dataset : Angka Tulis Tangan MNIST
2.  Pustaka : PyTorch, Torchvision, Scikit-learn
3.  Tujuan : Menggunakan Transfer Learning dengan model CNN pre-trained 
    untuk klasifikasi digit.

**Langkah-langkah :**
1.  Modifikasi Model : Ubah input layer dan output layer pada DenseNet dan 
    Vision Transformer (ViT) sesuai kebutuhan klasifikasi 10 kelas MNIST.
2.  Hyperparameter : Tentukan nilai batch size, learning rate, dan loss 
    functionuntuk multi-kelas.
3.  Model dan Pelatihan Pemanggilan :
   -  Pilih model (ResNet18, DenseNet121, atau ViT), tentukan jumlah epoch, 
      dan sediakan data loader untuk train dan validation set.
4.  Analisis Lapisan Beku :
   -  Menjawab pertanyaan terkait dampak pembekuan lapisan pada akurasi dan 
      kecepatan pelatihan. Semakin banyak lapisan yang di-freeze, akurasi 
      awal lebih rendah, dan waktu pelatihan lebih cepat karena parameter 
      yang dibor lebih sedikit.

**03_KELOMPOK F_3 Deteksi Objek Real-time dalam Video**
1.  Kumpulan data : video YouTube
2.  Pustaka : PyTorch, Numpy, OpenCV2
3.  Tujuan : Mendeteksi objek secara real-time dalam video menggunakan model 
    YOLOv5.

**Langkah-langkah :**
1.  Load Model : Gunakan model YOLOv5 untuk mendeteksi objek dalam video 
    dengan URL YouTube.
2.  Pertanyaan :
   -  Menjelaskan perbedaan antara klasifikasi gambar (pengklasifikasian 
      objek tunggal pada gambar) dan deteksi objek (mendeteksi lokasi dan 
      jenis objek dalam gambar).
   -  Identifikasi video di mana YOLOv5 memiliki akurasi deteksi terburuk 
      dan faktor-faktor yang mempengaruhi akurasi, seperti kondisi 
      pencahayaan, sudut pandang, atau kompleksitas gambar.

**03_KELOMPOK F_4 Klasifikasi Teks dengan BERT untuk Tweet Bencana**
1.  Kumpulan Data : Tweet Bencana
2.  Pustaka : NLTK, Pandas, Numpy, Scikit-learn, PyTorch, Transformers
3.  ujuan : Melakukan klasifikasi teks menggunakan model BERT untuk 
    memahami teks terkait bencana.

**Langkah-langkah :**
1.  Persiapan Data : Impor data pelatihan dan lakukan preprocessing. 
    Tentukan fitur (X) dan target (Y), serta pisahkan dataset menjadi 80% 
    pelatihan dan 20% validasi.
2.  Konfigurasi Model :
   -  Tentukan ukuran batch, jumlah label, jumlah epoch, dan kecepatan 
      pembelajaran untuk melatih BERT.
3.  DataLoader Setup : Lengkapi DataLoader untuk pelatihan, validasi, dan 
    pengujian.
4.  Hyperparameter Tuning : Jika akurasi kurang dari 80%, lakukan 
    penyesuaian hyperparameter untuk meningkatkan performa model.
5.  Pengujian : Pengujian impor dan praproses data, lalu siapkan DataLoader 
    untuk evaluasi akhir model pada uji data.
