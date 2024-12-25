# UAS-DEEP-LEARNING
CHATBOT LAYANAN PEMINJAMAN FASILITAS UNIVERSITAS BENGKULU
# Nama Anggota Kelompok 
1. Elisa (G1A021008)
2. Zhafirah Nur Shadrina (G1A021028)
3. Arya Bigtra Dhieva (G1A021088)
# LATAR BELAKANG
Univeristas Bengkulu merupakan salah satu perguruan tinggi yang perlu memanfaatkan teknologi untuk meningkatkan efektifitas layanan, seperti pembuatan chatbot untuk peminjaman fasilitas di Universitas Bengkulu. Mahasiswa seringkali terhambat dan bingung dalam mencari informasi terkait tata cara peminjaman fasilitas di Universitas Bengkulu. Oleh karena itu pengembangan chatbot untuk informasi mengenai peminjaman fasilitas di Universitas Bengkulu diperlukan agar memudahkan para mahasiswa dalam mengakses informasi mengenai peminjaman fasilitas secara mudah dan efektif.
# DATASET 
Dataset yang digunakan pada pembuatan ChatBot “Generasi Unib” disusun dalam format JSON yang dibuat secara manual berdasarkan informasi terkait peminjaman fasilitas di Universitas Bengkulu. Data ini dikumpulkan secara kolektif dari beberapa staff administrasi Universitas Bengkulu melalui wawancara dan pertanyaan – pertanyaan lisan. 
# MODEL
Model yang digunakan adalah Long Short Term Memory (LSTM)
# HASIL
1. Akurasi : 0,9893 setelah 500 epoch
2. Loss    : 0.0448

# GRAFIK PELATIHAN
![image](https://github.com/user-attachments/assets/662bb2e8-5e3c-4e59-b370-97b936bdd6ca)

# HASIL TES CHATBOT LAYANAN PEMINJAMAN FASILITAS UNIVERSITAS BENGKULU
![image](https://github.com/user-attachments/assets/e61ffd17-3c29-4853-b7fe-cc0125d48af2)
![image](https://github.com/user-attachments/assets/56b407af-618d-4846-bd06-5e7e76ff2f8b)

# KESIMPULAN
Dari pengujian model LSTM dalam membangun ChatBot layanan pinjaman fasilitas di Universitas Bengkulu dapat disimpulkan bahwa model mendapatkan akurasi yang cukup bagus yaitu dengan rata – rata akurasi sebesar 0.9893. Nilai loss pada model menunjukkan angka yang terbilang kecil yaitu sebesar 0.0448. Dengan ini, Proyek kali ini berhasil menghasilkan ChatBot yang dapat memberikan respon otomatis terhadap pertanyaan mahasiswa terkait peminjaman fasilitas di Universitas Bengkulu.

# Analisa Bagaimana Model Dapat Dikatakan Sebagai Deep Learning dan Bukan Shallow Learn
Model yang dibuat untuk ChatBot “Generasi Unib” merupakan model Deep Learning dan bukan Shallow Learn, karena model ini menggunakan arsitektur multi lapisan yang dapat memproses data kompleks. Terdapat layer LSTM dan Embedding yang merupakan ciri khas Deep learning. Model LSTM ini juga mempunyai banyak lapisan seperti input, embedding, flatten, maupun dense. Model dalam ChatBot “Generasi Unib” dibangun menggunakan TensorFlow Keras. Sedankan Shallow Learn adalah metode yang hanya menggunakan satu atau dua lapisan dan hanya dapat menangkap pola yang sederhana dalam data.
