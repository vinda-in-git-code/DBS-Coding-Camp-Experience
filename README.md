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
1. Sintaksis merupakan aturan-aturan yang ada dalam bahasa pemrograman. Sintaksis harus benar-benar dipatuhi aturannya supaya kode kita berjalan dengan baik.
2. Hampir semua bahasa pemrograman saat ini bersifat case sensitive. Artinya, setiap kapitalisasi huruf pada sebuah kode akan berpengaruh. Misalnya jika kita memiliki variabel bernama kucing dan Kucing, keduanya merupakan dua entitas variabel yang berbeda. Sedangkan kode yang bersifat non Case Sensitive berarti sebaliknya. Ia tidak akan terpengaruh dengan penulisan huruf besar atau kecil.
3. Program komputer terdiri dari kumpulan instruksi tunggal yang berkaitan satu sama lain. Instruksi-instruksi itulah yang disebut dengan statement. Dalam beberapa bahasa pemrograman misalnya seperti C, Java, dan sejenisnya, untuk mengakhiri suatu statement biasanya menggunakan tanda semicolon (;) atau titik koma. Kurangnya tanda semicolon (;) akan menyebabkan program gagal/error untuk dijalankan.
4. Tidak semua bahasa pemrograman menggunakan semicolon sebagai penutup statement. Ada juga yang tidak wajib menggunakan semicolon seperti Python, Swift, dan Kotlin.
5. Pseudocode atau kode semu merupakan istilah dalam pemrograman untuk menuliskan sebuah sintaksis, statement, algoritma, dan lainnya dalam bahasa yang bisa dipahami oleh manusia. Salah satu fungsi dari pseudocode adalah meningkatkan pemahaman dari pendekatan apa pun. Hal ini merupakan cara terbaik untuk menjelaskan apa yang kita inginkan dan melatih logika dalam pemrograman.
6. Whitespace saat kita mengetik kode biasanya berupa spasi atau tab untuk indentasi. Whitespace memang tidak mempengaruhi berjalannya suatu program. Namun, dalam bahasa pemrograman Python hal ini sangat sensitif dan berpengaruh terhadap berfungsinya suatu program.
7. Keyword merupakan kata kunci yang telah disediakan oleh sebuah bahasa pemrograman. Keyword tidak bisa berdiri sendiri guna membuat sebuah program yang dapat dijalankan. Kita harus mengkombinasikan keyword dengan logika pemrograman yang ada dengan bahasa yang kita pahami.
8. Variabel dalam pemrograman berfungsi untuk menyimpan nilai dari suatu data. Dalam satu variabel terdapat 3 bagian yaitu nama, tipe data, dan nilai dari variabel tersebut. Beberapa hal yang harus diperhatikan dalam variabel seperti, nama variabel tidak boleh ada spasi dan tidak boleh mengawali nama variabel dengan angka.
9. Operator sama dengan ("=") menyatakan perintah pada komputer untuk melakukan sesuatu atau bisa disebut assignment operator (operator penugasan).
10. Tipe data ada 3 jenis yaitu numerik, boolean, dan teks atau karakter. Contoh tipe data numerik yang sering digunakan adalah int (bilangan bulat) dan float (bilangan desimal). Kemudian untuk tipe data boolean memiliki dua nilai saja yaitu true dan false. Sedangkan tipe data berjenis teks atau karakter ada 2 yaitu char (untuk menampung satu karakter saja) dan string (untuk menampung banyak karakter atau kalimat).
11. Logika pemrograman dasar yang dapat diterapkan dalam pemrograman antara lain, logika perbandingan dan perulangan.
12. Dalam pemrograman, logika perbandingan berguna untuk membandingkan dua hal yang memiliki nilai dengan kondisi tertentu, salah satunya dengan operator ==. Logika perbandingan dapat kita bedakan menjadi sederhana dan kompleks. Untuk logika perbandingan sederhana kita dapat mengecek suatu kondisi menggunakan IF/Else saja. Kemungkinan yang dihasilkan oleh IF/Else ada dua. Jika kondisinya terpenuhi, maka ia akan mengeksekusi statement yang ada di dalam blok kode IF paling awal. Sedangkan jika tidak terpenuhi, ia akan mengeksekusi statement yang berada di dalam kondisi Else.
13. Logika perbandingan kompleks dapat menggabungkan IF/Else dengan AND dan OR. Penggunaan AND mengharuskan dua kondisi yang dibandingkan terpenuhi supaya bernilai true. Sedangkan untuk OR salah satu kondisi saja terpenuhi sudah bisa bernilai true.
14. Supaya tidak mengulangi menulis statement yang berulang kali, kita bisa menggunakan logika perulangan. Untuk membuat perulangan bisa menggunakan While atau For. While digunakan ketika kita tidak mengetahui berapa kali perulangan akan berjalan. Yang terpenting adalah selama kondisinya memenuhi syarat maka perulangan akan terus berjalan. Sedangkan dalam For, nilai perulangan, jumlah perulangan, dan akhiran yang biasanya berupa statement.
15. JavaScript erat kaitannya dengan pengembangan web yang berfungsi untuk membuat tampilan web terlihat dinamis dan interaktif. Selain itu terdapat beberapa kegunaan dari JavaScript seperti, mengembangkan aplikasi mobile, membuat game berbasis web, dan juga bisa digunakan untuk pengembangan back-end dari sebuah web.
16. Kita dapat menyimpan suatu nilai ke dalam variabel. ES6 mengenalkan dua cara baru untuk mendefinisikan variabel dalam JavaScript, yaitu menggunakan let dan const. Gunakan const untuk menyimpan nilai yang tidak akan berubah setelah diinisialisasi. Gunakan let apabila nilai di dalam variabel bisa berubah atau diinisialisasi ulang.
17. Terdapat 5 tipe data yang sering atau umum digunakan dalam JavaScript, antara lain: Undefined, Number, String, Boolean, dan Null.
18. Secara umum bahasa pemrograman memiliki 3 konsep dasar yang mirip yaitu :
    - Statement selalu dieksekusi secara berurutan dari atas ke bawah (Sequences).
    - Logika pemilihan keputusan sesuai kondisi yang berlaku, misalnya seperti IF/Else (Selection).
    - Sebuah proses yang dilakukan secara berulang, misalnya seperti For (Looping).
19. Bahasa JavaScript yang telah kita pelajari di materi sebelumnya merupakan salah satu media yang menerapkan 3 konsep dasar pemrograman seperti sequence, selection, dan looping. Ketika kita menggunakan bahasa pemrograman lain misalnya seperti C#, Java, Swift, dan lainnya, akan juga akan memuat 3 konsep dasar pemrograman yang telah disebutkan di atas.
20. Berikut beberapa tips yang dapat membantu Anda dalam belajar pemrograman :
    - Mengatur Waktu -> Tidak ada waktu merupakan alasan klasik ketika belajar pemrograman. Untuk mengatasi hal tersebut kita harus memiliki target belajar. Dengan memiliki target dan mengalokasikan waktu, maka Anda akan lebih terarah dan memiliki pencapaian belajar yang lebih terukur.
    - Perhatikan Kondisi Tempat Belajar -> Lingkungan tempat Anda belajar juga mempengaruhi kemampuan kita dalam mempelajari sesuatu. Hal tersebut terjadi karena otak Anda berasosiasi sesuai dengan konteks di mana Anda sedang mempelajari sesuatu. Dalam proses belajar, tempat atau suasana sangat penting supaya informasi yang kita pelajari bisa cepat kita serap.
    - Mulai dari yang Sederhana -> Dalam memulai belajar pemrograman jangan langsung loncat belajar yang sulit. Seperti sebuah pesan bijak, “Sesuatu yang besar dimulai dari langkah yang kecil” maka kita harus mulai melangkah dari yang paling sederhana dulu.
#### Modifikasi Aplikasi Perangkat Lunak : 
1. 
