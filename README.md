# Deep Learning With MNIST Dataset Using Pytorch 
Selamat datang dalam proyek "Deep Learning With MNIST Dataset Using PyTorch"! Dalam proyek ini,akan dilakukan pemodelan neural network dan memahami cara membangun, melatih, dan menguji model deep learning menggunakan dataset MNIST, yang merupakan salah satu dataset dalam computer vision.Tahapan-tahapan penting yang akan dilakukan mencakup import dataset, pemeriksaan data, desain jaringan saraf tiruan, serta evaluasi akurasi menggunakan berbagai fungsi aktivasi.

## Import MNIST Dataset
Dalam tahap ini, dilakukan import package dan library yang diperlukan seperti torch, torchvision, dan matplotlib. Selanjutnya, mendownload dataset MNIST menggunakan torchvision, mengonversi data menjadi tensor, dan melakukan normalisasi. Dataset dibagi menjadi data latih dan data uji, kemudian dimuat dengan menggunakan batch size dan transformasi.
## Sanity Check Image
Selanjutnya ,pemeriksaan data gambar, memeriksa ukuran gambar, dan menampilkan gambar dari setiap kelas (digit) dalam dataset MNIST. Langkah ini memastikan bahwa data telah diimpor dan disiapkan dengan benar sebelum digunakan untuk pelatihan model.

## Design Neural Network 
Merancang jaringan saraf tiruan (neural network) untuk mengklasifikasikan digit menggunakan tiga jenis fungsi aktivasi: Tanh, LeakyReLU, dan Sigmoid. Fungsi aktivasi memainkan peran penting dalam pelatihan model deep learning, memungkinkan model untuk mempelajari pola yang kompleks dalam data.
Untuk membuat feedforward neural network yang menklasifikasi digit , dengan fungsi aktivasi

## Accuracy Each Activation Function 
Setelah melatih model dengan jumlah epoch = 5, dihasilkan akurasi dari masing-masing model dengan fungsi aktivasi yang berbeda. Hasilnya menunjukkan bahwa model dengan fungsi aktivasi Sigmoid mencapai akurasi tertinggi, yaitu 95.54%. Ini menunjukkan bahwa Sigmoid adalah pilihan terbaik untuk tugas klasifikasi digit menggunakan dataset MNIST dalam proyek ini.
