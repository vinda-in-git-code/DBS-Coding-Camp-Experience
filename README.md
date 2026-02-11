# Pengalaman Belajar Pertama di DBS Coding Camp 

## Tanggal : 9 Februari 2026<br>
### Mempelajari Memulai Dasar Pemrograman utk Menjadi Pemrogram Software =
- Mempelajari Dasar Pemgrograman HTML & Java.
- Mengenal VCS & Github secara Umum.
- Mempelajari URS & SKPL.
### Rangkuman Kelas = 
#### Memahami Kebutuhan Aplikasi : 
1. User Requirement Specification (URS) adalah dokumen yang menyimpan informasi mengenai kebutuhan pengguna yang dibuat sebelum proses pengembangan suatu software. Dokumen ini bertujuan agar ketika ada yang membaca dokumen ini maka akan mendapatkan pemahaman yang sama akan kebutuhan user pada aplikasi.
2. Dokumen User Requirement Specification tidak boleh menggunakan jargon teknis yang hanya dipahami oleh kelompok tertentu, melainkan harus menggunakan bahasa yang bisa dipahami oleh seluruh stakeholder (pemegang kepentingan), seperti manajer, developer, customer, dan user.
3. Beberapa teknik requirement gathering yang bisa kita gunakan adalah :
   - Interview, proses wawancara yang berupa tanya jawab
   - User Stories, menuliskan kebutuhan user sesuai dengan role dan keinginannya \
   - Straw Man, menyampaikan ide tanpa menggunakan kode
   - Prototyping, membuat sampel program yang hanya memiliki fitur-fitur utamanya saja
4. Spesifikasi Teknis Aplikasi yakni dokumen yang menyimpan informasi detail mengenai fungsionalitas dari sistem/aplikasi, servis, dan juga limitasi-limitasinya.
5. Beberapa prinsip yang perlu diperhatikan ketika membuat spesifikasi teknis aplikasi seperti berikut :
   - Clear (jelas)
   - Unambiguous (tidak ambigu)
   - Mudah dipahami
   - Complete (lengkap)
   - Consistent (konsisten)
6. Dalam proses pembuatan spesifikasi teknis aplikasi kita perlu mempertimbangkan kebutuhan dari berbagai macam stakeholder. Berikut pandangan beberapa stakeholder terkait spesifikasi teknis :
   - Developer -> Dari sisi developer tentunya yang diperlukan ada kedetailan dan kejelasan spesifikasi. Karena merekalah yang akan mengimplementasinya ke dalam aplikasi.
   - Client/User -> Dari sisi client meskipun spesifikasi teknis lebih mengarah ke teknis akan tetapi mereka berharap tetap bisa dimengerti. Dalam artian istilah teknis yang dipakai harus bisa dibuat semudah mungkin untuk dimengerti.
   - Legal -> Karena spesifikasi teknis ini bisa menjadi kontrak, maka perlu memasukkan acceptance criteria dengan jelas juga. Acceptance criteria adalah klausul kriteria yang berisi apakah suatu fitur sudah berjalan dengan baik. Jika aplikasi yang dibuat lulus semua acceptance criteria maka seharusnya tidak ada masalah dari sisi kontrak/legal.
7. Dalam mengembangkan aplikasi, sebaiknya disiapkan juga plan B atau contingency plan. Contingency plan adalah suatu tindakan alternatif yang dipersiapkan ketika tindakan utama yang direncanakan untuk melakukan sesuatu gagal atau terhambat oleh berbagai faktor.
#### Perencanaan Modifikasi Aplikasi :
1. Spesifikasi Kebutuhan Aplikasi Perangkat Lunak adalah sebuah dokumen yang dibuat sebelum mengembangkan sebuah aplikasi perangkat lunak. Dokumen ini menjelaskan cara kerja dan kebutuhan fungsional maupun non-fungsional dari aplikasi yang digunakan pengguna nantinya.
2. Beberapa keuntungan yang didapatkan dari pembuatan dokumen Spesifikasi Kebutuhan Aplikasi Perangkat Lunak :
   - Desainer dalam tim baik dari sisi UI/UX akan mendapat gambaran sehingga mereka dapat mencocokkan desain dengan kebutuhan aplikasi.
   - Tim penguji aplikasi (tester) akan mendapatkan panduan untuk membuat studi kasus untuk melakukan proses pengujian aplikasi.
   - Pengguna (end user) akan mendapatkan gambaran umum terkait aplikasi yang akan dibuat.
   - Pihak investor juga akan mendapatkan gambaran umum terkait fitur apa saja yang ada di dalam aplikasi. Sehingga membantu mereka untuk mengambil keputusan untuk investasi atau tidak.
3. Cakupan elemen yang ada dalam dokumen Spesifikasi Kebutuhan Perangkat Lunak :
   - Tujuan dari aplikasi.
   - Deskripsi umum mengenai aplikasi.
   - Kebutuhan fungsional dan non fungsional dari aplikasi.
   - Performa aplikasi dalam proses produksi.
   - Antarmuka eksternal atau bagaimana sebuah aplikasi berinteraksi dengan perangkat keras atau perangkat lunak lainnya.
   - Batasan dari sistem aplikasi yang akan dibuat.
4. Kebutuhan fungsional menggambarkan bagaimana sistem membantu menyelesaikan tugas atau kebutuhan pengguna ketika menggunakan aplikasi yang kita buat. Kebutuhan fungsional ini sama halnya dengan fitur yang ditawarkan aplikasi untuk pengguna. Tanpa terpenuhinya kebutuhan fungsional dalam dokumen SKPL, sama halnya dengan Anda meniadakan fungsi atau fitur dari sebuah aplikasi.
5. Kebutuhan non fungsional mendukung kebutuhan fungsional yang sudah ada. Tanpa adanya persyaratan non fungsional, sistem aplikasi masih akan tetap bisa berjalan untuk memenuhi kebutuhan yang diinginkan pengguna. Walaupun begitu, kebutuhan non fungsional juga tetap harus diperhatikan karena dapat mempengaruhi pengalaman pengguna (user experience) ketika menggunakan aplikasi. Biasanya persyaratan non fungsional ini, meliputi kinerja, keandalan, keamanan, dan kegunaan dari aplikasi itu sendiri.
6. Anda dapat mengacu pada standar IEEE 1998 untuk menulis dokumen Spesifikasi Kebutuhan Perangkat Lunak. Standar ini dapat Anda sesuaikan kembali bergantung pada kebutuhan aplikasi atau perangkat lunak yang ingin dikembangkan ( lihat Gambar 1 buat lihat Strukturnya ).
7. Bahasa pemrograman tidak bisa langsung berkomunikasi dengan komputer. Komputer hanya bisa memahami bahasa mesin. Oleh karena itu diperlukan jembatan yaitu compiler atau interpreter supaya bahasa pemrograman bisa dipahami oleh komputer ( lihat Gambar 2 untuk Konteksnya ).
8. Berikut teknik penyelesaian masalah menggunakan cara berpikir komputasional :
   - Memecah permasalahan yang besar menjadi bagian kecil (decomposition) -> Dengan teknik decomposition tersebut, maka kita tidak lagi melihat sebuah permasalahan sebagai hal yang kompleks. Karena kita telah memecahnya menjadi bagian atau tugas-tugas kecil yang bisa dikerjakan.
   - Pelajari pola dari setiap permasalahan (pattern recognition) -> Pattern Recognition merupakan teknik pemecahan masalah dengan melihat perbedaan atau persamaan pola dari berbagai permasalahan. Sehingga kita dapat memprediksi atau memproyeksikan solusi apa yang harus kita lakukan. Ketika kita dihadapkan dengan banyak permasalahan, kita harus bisa mempelajari polanya supaya dapat menyelesaikan dengan cepat.
   - Mengabstraksikan suatu permasalahan (abstraction) -> Abstraksi merupakan cara berpikir komputasional yang identik dengan penyaringan dan pengumpulan data yang bersifat umum. Selain itu, abstraksi juga akan mengesampingkan detail data yang bersifat khusus atau yang tidak kita perlukan untuk lebih berkonsentrasi terhadap apa yang akan dilakukan.
   - Susun langkah menggunakan algoritma (algorithm) -> Algoritma merupakan sekumpulan alur instruksi yang berurutan untuk menyelesaikan permasalahan. Sehingga kita akan merangkai sekumpulan instruksi tersebut menjadi urutan yang terstruktur, logis, dan mudah dipahami. Algoritma yang dibuat harus memuat beberapa hal yaitu, titik awal, titik akhir, dan serangkaian instruksi yang jelas.
   - Mengevaluasi solusi yang didapatkan (evaluation) -> Proses terakhir yang dapat kita lakukan adalah melakukan evaluasi terhadap solusi yang telah kita dapatkan. Proses ini perlu dilakukan sebelum melangkah ke permasalahan atau tugas yang baru.
9. Flowchart atau bisa disebut dengan diagram alur merupakan bentuk penggambaran dengan pendekatan visual terkait langkah-langkah dan keputusan untuk melakukan sebuah proses, alur kerja, ataupun algoritma. Beberapa jenis flowchart antara lain, process, workflow, dan program flowchart.
10. Flowchart atau diagram alur memiliki beberapa simbol tertentu untuk mewakili fungsi atau langkahnya dalam sebuah proses. Garis dan panah menunjukkan urutan langkah dan hubungan antar blok diagram ( Simbol - simbol dan artinya ada di Gambar 3 ).
11. Untuk mengetahui tips sikap kerja dalam kolaborasi perencanaan aplikasi dengan tim, simak uraiannya di bawah ini :
    - Efektifkan Komunikasi -> Dalam proses kolaborasi pasti tidak pernah lepas dari diskusi timbal balik alias komunikasi. Komunikasi yang efektif antar anggota tim akan membuat informasi tersampaikan dengan baik. Tanpa adanya komunikasi maka segala informasi akan tak tersampaikan dan kolaborasi pun tidak akan berjalan dengan semestinya.
    - Bertanggung jawab pada tugas yang dikerjakan -> Membangun kepercayaan dalam tim juga berperan penting dalam keberhasilan kolaborasi. Mengapa demikian? Kepercayaan berarti Anda mengandalkan orang lain untuk melakukan sebuah pekerjaan. Anda percaya pada integritas dan kemampuan orang tersebut walaupun ada kemungkinan resiko yang bisa kembali ke diri Anda sendiri. Begitu pula sebaliknya, jika orang lain mengandalkan Anda untuk membantu pekerjaannya, maka orang tersebut percaya pada kemampuan dan integritas Anda.
    - Berikan Semangat Anda -> Kita telah mengetahui pentingnya membangun kepercayaan dalam sebuah proses kolaborasi. Selain itu kita juga harus selalu menunjukkan semangat dan bergairah dalam mengerjakan tugas. Semangat dapat mempengaruhi mental dari tim. Maka dari itu ketika ada anggota tim yang sedang terlihat lesu karena kehilangan semangat atau bahkan hampir putus asa, kita harus menyemangatinya. Mungkin terdengar sepele tetapi hal tersebut akan mempengaruhi psikis anggota tim.
    - Utamakan Diskusi -> Berpikir bersama dalam sebuah diskusi merupakan hal yang sangat penting dalam sebuah tim. Ketika muncul kendala yang cukup besar, diskusi bersama merupakan hal yang tepat untuk diterapkan. Jika rekan tim Anda berusaha menyelesaikan sendiri-sendiri, ajaklah mereka berdiskusi untuk mencapai tujuan bersama. Utarakan pendapat Anda sesuai dengan tujuan yang ingin dicapai. Anda juga harus bisa mendengarkan dan menghargai pendapat orang lain ketika mereka mengemukakan idenya.
    - Hindari Sikap Tidak Tanggap (Slow Response) -> Kondisi tidak tanggap atau slow response ini biasanya sering ditemui ketika bekerja secara jarak jauh. Satu-satunya cara untuk saling berkomunikasi adalah dengan mengirim pesan atau melakukan video call. Sehingga anggota tim yang bekerja secara jarak jauh harus selalu stand by apabila sewaktu-waktu ada hal penting yang harus segera dikerjakan.
    - Menentukan Prioritas -> Kita pasti akan menemui kondisi di mana banyak kerjaan atau todo yang harus kita kerjakan dalam satu waktu. Dan terkadang semua todo adalah hal penting yang memang harus dikerjakan.
#### Konsep Dasar Pemrograman : 
1. 
