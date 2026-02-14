# Pengalaman Belajar Ke - 2 di DBS Coding Camp 

## Tanggal : 10 Februari 2026<br>
### Mempelajari Pengenalan ke Logika Pemrograman (Programming Logic 101) =
- Mempelajari Computational Thinking.
- Mempelajari Logika & Algoritma secara umum.
### Rangkuman Kelas = 
#### Pendahuluan : 
1. Menurut Technopedia, logika pemrograman adalah sebuah kemampuan dasar yang menerapkan pemahaman operasi logika terhadap data ke dalam ilmu komputer [1]. Tidak berhenti di sana, logika pemrograman juga dapat membantu Anda untuk menyelesaikan masalah (problem solving), baik dalam bidang pemrograman maupun kehidupan sehari-hari.
2. Logika dan algoritma merupakan dua hal yang berbeda tetapi saling berkaitan satu sama lain. Jika sebelumnya logika pemrograman dapat membantu Anda untuk menyelesaikan permasalahan (problem solving), algoritma bertugas untuk membuat penyelesaiannya lebih terstruktur. Ketika menyusun algoritma, terdapat beberapa hal yang harus diperhatikan, seperti:
   - Finiteness (Keterbatasan) -> Algoritma yang berjalan dan memproses setiap langkah-langkahnya memiliki sifat terbatas, sehingga ia harus berhenti ketika semua langkah-langkahnya selesai dikerjakan.
   - Definiteness (Kepastian) -> Setiap langkah algoritma harus jelas, detail, dan tidak ambigu (makna ganda). Dengan kata lain, pembaca harus mengerti apa tujuan yang dimaksud.
   - Effectiveness (Efektifitas) -> Setiap algoritma harus dibuat secara efektif. Langkah-langkah yang ada di dalamnya juga harus sesuai kebutuhan dan tidak perlu berlebihan.
   - Input (Masukan) -> Algoritma pasti membutuhkan nol atau lebih masukan (input) sebelum prosesnya dimulai.
   - Output (Keluaran) -> Setiap input yang diproses oleh algoritma pasti memiliki satu atau lebih keluaran (output). Keluaran adalah besaran nilai yang memiliki hubungan dengan masukan (input).
3. Dua metode penalaran logika yang dapat diterapkan di bidang pemrograman ada 2, yaitu :
   - Induktif -> Menurut Stanford Encyclopedia of Philosophy, penalaran logika induktif adalah logika pendukung pembuktian. Secara sederhana metode induktif adalah sebuah metode berpikir menggunakan pengamatan dan digabungkan dengan pengalaman yang sudah Anda ketahui kebenarannya untuk mendapatkan sebuah kesimpulan.
   - Deduktif -> Menurut Chad Nilep dari Universitas Nagoya, logika penalaran deduktif adalah sistem yang tepat dan teratur bertujuan untuk memberikan dukungan pasti untuk suatu kesimpulan. Salah satu bentuk penalaran logika deduktif adalah silogisme. Menurut KBBI, silogisme adalah bentuk, cara berpikir atau menarik simpulan yang terdiri atas premis umum, premis khusus, dan simpulan [4].
4. Ada 3 jenis logika pemrograman yang akan kita bahas, antara lain :
   - Logika aritmatika -> Logika aritmatika dapat membantu pemecahan masalah terkait dengan perhitungan yang melibatkan operasi matematika seperti penjumlahan, pengurangan, dan lainnya.
   - Logika perbandingan -> Logika ini digunakan untuk membandingkan dua hal yang mempunyai nilai. Nilai inilah yang akan dibandingkan dengan nilai lain atau kondisi yang diinginkan.
   - Logika perulangan -> Logika perulangan adalah proses pengulangan instruksi yang dilakukan dalam kondisi yang telah ditentukan. Dalam pemrograman, kita harus menghindari menulis kode yang sama berulang kali. Hal tersebut dilakukan supaya proses menulis kode lebih efektif dan efisien.
#### Gerbang Logika :
1. Gerbang logika atau logic gate adalah sebuah rangkaian sirkuit digital yang berguna untuk memproses logika boolean (logika yang menghasilkan output benar atau salah). Gerbang logika ini menghasilkan output berupa 0 (salah) dan 1 (benar) berdasarkan input (masukan) yang kita berikan.
2. Tabel kebenaran merupakan kumpulan kombinasi beberapa nilai input berdasarkan logika yang kita buat untuk menghasilkan output (keluaran) yang masuk akal dalam bentuk tabel.
3. Terdapat 7 jenis gerbang logika, diantaranya seperti :
   - AND : Gerbang logika AND setidaknya memerlukan dua input. Jika input A dan B bernilai 1 (true), maka hasil outputnya juga pasti bernilai 1 (true). Sedangkan jika salah satu input saja bernilai 0 (false), maka hasil output juga akan 0 (false) [Lihat Gambar 1 di Releases yang Tag 2.1].
   - OR : Jika input A atau B bernilai 1 (true), maka hasil outputnya juga pasti bernilai 1 (true). Namun, jika input keduanya bernilai 0 (false), maka hasil outputnya juga akan 0 (false) [Lihat Gambar 2 di Releases yang Tag 2.2].
   - NOT : Gerbang logika NOT hanya memerlukan 1 input untuk mendapatkan satu keluaran. Jika input A bernilai 1 (true), maka hasilnya outputnya bernilai 0 (false). Sedangkan jika inputnya bernilai 0 (false), maka hasil outputnya bernilai 1 (true) [Lihat Gambar 3 di Releases yang Tag 2.3].
   - NAND : Jika input A dan B keduanya bernilai 1 (true), maka hasil outputnya adalah 0 (false). Sedangkan jika salah satu inputnya ada yang bernilai 0 (false), maka hasil outputnya adalah 1 (true) [Lihat Gambar 4 di Releases yang Tag 2.4].
   - NOR : Jika input A dan B keduanya bernilai 0 (false), maka hasil outputnya adalah 1 (true). Sedangkan jika salah satu input saja ada yang bernilai 1 (true), maka hasil outputnya adalah 0 (false) [Lihat Gambar 5 di Releases yang Tag 2.5].
   - XOR : Jika input A atau B nilainya berbeda misalnya A=0, B=1, maka hasil outputnya akan bernilai 1 (true). Tetapi jika kedua input nilainya sama misalnya A=1 B=1 atau A=0, B=0, maka hasil outputnya bernilai 0 (false)[Lihat Gambar 6 di Releases yang Tag 2.6].
   - XNOR : Jika input A atau B nilainya sama misalnya A=1, B=1 atau A=0, B=0, maka hasil outputnya akan bernilai 1 (true). Tetapi jika kedua input nilainya berbeda misalnya A=1 B=0 atau A=0, B=1, maka hasil outputnya bernilai 0 (false) [Lihat Gambar 7 di Releases yang Tag 2.7].
#### Computational Thinking : 
1. Ketika seorang programmer membuat sebuah program, mereka akan mulai berpikir secara terstruktur layaknya sebuah komputer mengeksekusi setiap perintah kode secara berurutan. Begitu pula saat memecahkan sebuah permasalahan. Mereka akan mencari solusi dari permasalahan secara terstruktur dan seefisien mungkin. Proses tersebut dikenal juga dengan computational thinking.
2. Terdapat 5 elemen dalam computational thinking antara lain :
   - Decomposition -> Decomposition merupakan teknik pemecahan masalah yang besar menjadi bagian-bagian kecil. Tujuan dari decomposition ini sendiri adalah membuat sebuah masalah lebih mudah dikelola dan dikerjakan.
   - Pattern Recognition -> Pattern Recognition merupakan teknik pemecahan masalah dengan melihat perbedaan atau persamaan pola dari berbagai permasalahan. Sehingga kita dapat memprediksi atau memproyeksikan solusi apa yang harus kita lakukan.
   - Abstraction -> Abstraction atau abstraksi merupakan teknik pemecahan masalah dengan penyaringan dan pengumpulan data yang bersifat umum. Selain itu abstraksi juga akan mengesampingkan detail data yang bersifat khusus atau yang tidak kita perlukan untuk lebih berkonsentrasi terhadap apa yang akan dilakukan.
   - Algorithms -> Algoritma merupakan sekumpulan alur instruksi yang berurutan untuk menyelesaikan permasalahan. Sehingga kita akan merangkai sekumpulan instruksi tersebut menjadi urutan yang terstruktur, logis, dan mudah dipahami. Ketika kita memberikan algoritma yang tidak cukup efisien terhadap komputer, maka hasilnya juga pasti tidak seperti yang diharapkan. Begitupun dalam kehidupan sehari-hari, jika kita tidak menyusun langkah-langkah penyelesaian dengan perencanaan yang baik, maka hasilnya juga tidak baik. Teknik menyusun algoritma ada 2 (dua) cara yaitu pseudocode dan flowchart. Flowchart atau bisa disebut dengan diagram alir merupakan bentuk penggambaran dengan pendekatan visual terkait langkah-langkah dan keputusan untuk melakukan sebuah proses, alur kerja, ataupun algoritma. Sedangkan Pseudocode merupakan istilah dalam pemrograman untuk menuliskan sebuah sintaks, statement, algoritma, dan lainnya dalam bahasa yang bisa dipahami oleh manusia.
   - Evaluation -> Proses terakhir yang dapat kita lakukan adalah melakukan evaluasi terhadap solusi yang telah kita dapatkan. Proses ini perlu dilakukan sebelum melangkah ke permasalahan atau tugas yang baru.
