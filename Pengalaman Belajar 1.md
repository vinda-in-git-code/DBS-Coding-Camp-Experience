# Pengalaman Belajar Ke - 1 di DBS Coding Camp 

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
1. HTML adalah singkatan dari Hypertext Markup Language, merupakan bahasa standar yang digunakan untuk merancang tampilan website.
2. Fungsi utama dari HTML adalah untuk membuat suatu halaman website menjadi lebih mudah dibaca dan dipahami. Karena itulah di dalamnya terdapat berbagai macam tag yang dapat dapat digunakan untuk memformat teks, seperti heading, paragraf, maupun link.
3. Berikut adalah contoh dari kode HTML:
   - <html> : tag paling dasar pada html, semua elemen lain harus di dalam tag ini.
   - <head> : tempat untuk menyimpan informasi dari dokumen HTML.
   - <title>: judul yang muncul di tab browser.
   - <body> : representasi dari suatu konten pada sebuah dokumen HTML.
   - <h1> : salah satu jenis dari 6 jenis heading yang paling tinggi.
   - <a dengan attribute href>: untuk membuat hyperlink ke suatu website.
   - <p> : paragraf.
4. Cascading Style Sheet atau biasa disingkat CSS merupakan standar W3C (World Wide Web Consortium) yang digunakan untuk mengatur visualisasi berkas yang ditulis pada HTML.
5. CSS bukanlah sebuah bahasa pemrograman karena di dalamnya tidak terdapat logika, tidak dapat membuat sebuah variabel, tidak adanya proses iterasi, dsb.
6. CSS hanya sebuah declarative language yang digunakan untuk mendeklarasikan suatu nilai yang nantinya digunakan untuk mengatur seperti apa sebuah elemen HTML ditampilkan pada browser.
7. Dengan menerapkan CSS, tampilan website kita akan lebih menarik. Berikut beberapa keuntungan yang didapatkan ketika kita menerapkan CSS.
8. Dapat mengontrol dan menerapkan layout secara presisi. Dengan menggunakan CSS kita bisa membuat sebuah website seperti dokumen cetak dengan desain yang menarik dan presisi.
9. Menghindari pekerjaan yang berulang-ulang dalam menerapkan styling. Kita dapat menetapkan styling pada beberapa berkas HTML hanya dengan menggunakan satu berkas CSS.
10. Didukung banyak browser. Seluruh browser saat ini minimal sudah mendukung CSS versi 2. Untuk browser yang populer seperti Chrome dan Firefox sudah mendukung CSS versi 3.
11. Supaya kemampuan Anda terlatih lebih dalam lagi, berikut ini terdapat beberapa tips yang dapat Anda terapkan : 
    - Banyak berlatih -> Ibarat sebuah pisau yang sudah lama tidak diasah, maka lama kelamaan pisau tersebut akan menjadi tumpul. Begitu juga dengan kemampuan yang sudah Anda miliki, jika tidak diimbangi dengan latihan berulang kali, maka semakin lama ilmu tersebut dapat membusuk begitu saja di kepala Anda. Maka, perbanyaklah latihan dengan cara mengubah-ubah project yang sudah ada atau bahkan menambahkan fitur baru pada project tersebut.
    - Berlatih berdasarkan topik yang diminati -> Jika Anda bosan ketika berlatih pemrograman, cobalah berlatih dengan topik yang Anda minati. Sebagai contoh Anda tertarik dengan sepak bola, maka buatlah aplikasi yang berkaitan dengan topik yang Anda minati tersebut, contohnya seperti papan penghitung skor, portal berita olahraga, atau dashboard live score. Dengan begitu, Anda akan memiliki semangat yang lebih dalam bereksplorasi.
#### Dokumentasi Pemrograman dan Pengembangan Aplikasi Perangkat Lunak : 
1. Pengarsipan adalah proses, cara, atau perbuatan mengarsipkan. Sedangkan arsip sendiri adalah tempat penyimpanan berkas (program atau data) sebagai cadangan. Sehingga pengarsipan perangkat lunak dapat diartikan sebagai proses mengarsipkan perangkat lunak atau aplikasi yang telah kita buat.
2. Version Control System merupakan tools untuk mengatur suatu perubahan dan konfigurasi dari suatu aplikasi, termasuk juga source code. Setiap perubahan yang dilakukan akan dicatat, sehingga memperjelas siapa yang telah melakukan perubahan tersebut. Selain itu, version control juga berfungsi sebagai backup files atau pengarsipan.
3. Kita bisa menggunakan Git secara free atau gratis kemudian menyimpannya juga di layanan online yang tersedia seperti GitHub, Bitbucket, dan Gitlab. Namun, salah satu yang cukup populer adalah GitHub.
4. GitHub merupakan layanan hosting repository Git berbasis web yang juga memiliki banyak fitur seperti bug tracking dan task management. Dengan menggunakan GitHub, kita bisa mengarsipkan perangkat lunak atau aplikasi kapan pun dan di mana pun.
5. Semua perubahan yang ada dalam repository Git dapat kita lihat dalam halaman history. Kita juga dapat melihat detail dari perubahan tersebut, seperti bagian mana yang ditambahkan atau dihilangkan.
6. Anda dapat menggunakan commit untuk menyimpan perubahan yang ada dalam Git. Selain itu, Anda juga dapat menggunakan fitur revert untuk kembali ke perubahan atau commit tertentu.
7. Saat Anda bekerja sebagai software developer, perusahaan tak hanya menginginkan fitur-fitur aplikasi bisa berjalan dengan baik ya. Perusahaan juga menginginkan kode dengan kualitas terbaik dan mampu menjadi pendukung bisnis. Salah satu indikatornya adalah Anda dapat melakukan perubahan dengan mudah pada aplikasi saat terdapat fitur baru. Selain itu, perusahaan dapat melakukan upaya (effort) seminimal mungkin untuk beradaptasi dengan kebutuhan bisnisnya.
8. Kode yang baik tak hanya mudah dibaca oleh komputer saja, namun mudah dibaca oleh manusia. Kenapa demikian? Karena programming kebanyakan tentang membaca, bukan menulis.
9. Style Guide merupakan kumpulan peraturan mengenai bagaimana cara penulisan kode yang baik bagi developer secara individu maupun tim. Pada style guide tertulis secara lengkap aturan yang harus diikuti oleh developer. Seperti penggunaan double atau single quote, indentasi, semicolon, penamaan variabel, dan lainnya.
10. Style guide yang sudah disepakati dan direkomendasikan oleh banyak developer itulah yang disebut dengan Code Convention. Tentunya setiap bahasa pemrograman memiliki berbagai referensi style guide terkenal yang direkomendasikan untuk Anda ikuti. Dalam bahasa Javascript, Anda dapat mengikuti style guide dari AirBNB JavaScript, Google JavaScript, dan Standard JavaScript.\
11. Alasan mengapa style guide penting bagi developer :
    - Konsistensi.
    - Membantu Proses Onboarding.
    - Menambah Wawasan.
    - Membantu proses Code Review.
12. Selain itu, dengan mengikuti style guide, Anda akan dapat beberapa keuntungan seperti :
    - Memahami dan membaca kode jadi lebih mudah.
    - Memelihara kode jadi lebih mudah untuk dipelihara.
    - Mengurangi kesalahan pengembang software yang sering terjadi.
    - Mengurangi beban secara kognitif saat memuat kode.
    - Menjadi lebih fokus pada permasalahan logika kode dibandingkan style-nya saat berdiskusi dengan rekan kerja Anda.
13. Komentar memiliki beberapa macam jenis, yakni :
    - Singleline atau satu baris (//)
    - Multiline atau beberapa baris (/* … */)
14. Selain menginformasikan apa yang terjadi dalam baris kode, komentar juga berfungsi untuk menonaktifkan suatu perintah dalam baris kode.
15. Ingat, tak semua kode perlu dikomentari ya. Terlebih jika sebuah hal yang mendasar, seperti perintah print.
16. Walaupun komentar tidak mempengaruhi performa kode, tetapi harus kita pastikan komentar yang dibuat cukup membantu untuk menjelaskan kode yang ada. Oleh karena itu, bijaklah dalam menuliskan komentar dalam kode. Jika dirasa komentar tidak diperlukan, Anda bisa menghapusnya.
17. Dokumentasi adalah deskripsi tertulis yang komprehensif dari perangkat lunak dalam berbagai bentuk dan tingkat perincian yang secara jelas mendefinisikan persyaratan, konten, komposisi, desain, kinerja, pengujian, penggunaan, dan pemeliharaan.
18. Dokumentasi teknis akan menceritakan mengenai produk dengan cara yang mudah untuk digunakan, dibaca, dimengerti, dan tentunya membantu pembaca.
19. Dokumentasi Teknis dibagi menjadi beberapa jenis dan area sesuai kebutuhan, berikut detailnya :
    - End-user support: Dokumen ini biasanya berisi tentang panduan pengguna, sistem bantuan secara online, catatan rilis, panduan pelatihan, panduan cara instalasi, atau prosedur operasional. Intinya adalah apa pun yang mendukung pengguna dengan produk Anda.
    - Marketing support: Dokumen ini fokus pada produk dan digunakan untuk memasarkan perusahaan Anda. Contohnya berupa video pelatihan berbasis komputer, presentasi, bantuan secara online, atau sebuah halaman untuk arahan teknis.
    - Development support: Dokumen ini berisi mengenai segala spesifikasi teknis dan fungsional, panduan pengembangan produk perangkat lunak, glosarium, atau prosedur serta tools untuk membantu tim dalam melakukan pekerjaan mereka.
    - Organization support: Dokumen ini berisi segala informasi mengenai perusahaan seperti struktur organisasi, panduan bekerja, alur kerja, kebijakan-kebijakan, aturan yang ada, dan hal lain yang perlu diketahui karyawan untuk melakukan pekerjaan mereka.
20. Dokumentasi teknis itu sendiri dapat dilakukan secara offline maupun online.
21. Ketika Anda membuat dokumentasi secara online, maka dapat diakses kapan saja dan di mana saja. Tentunya ini akan memudahkan dan tidak memakan waktu lama untuk memahaminya sehingga lebih efisien dan uptodate.
22. Beda cerita jika Anda mendokumentasikan sebuah aplikasi atau produk, namun disimpan dalam bentuk offline seperti catatan atau mungkin dalam bentuk buku. Jika dibutuhkan dalam keadaan terdesak, informasi tersebut tidak bisa langsung didapatkan. Bahkan proses pencariannya juga akan lebih rumit dibandingkan dokumentasi teknis secara online.
23. Manfaat yang akan didapatkan ketika kita mengimplementasikan dokumentasi teknis ketika pembuatan aplikasi, yaitu :
    - Meningkatkan retensi pengguna.
    - Menghemat waktu dan tenaga.
    - Meningkatkan penjualan produk Anda.
24. Berikut merupakan langkah singkat untuk membangunnya :
    - Tentukan siapa targetnya, apakah untuk rekan tim Anda atau untuk pengguna aplikasi Anda.
    - Pikirkan dengan matang dan jelas apa yang ingin Anda sampaikan ke dalam dokumentasi teknis.
    - Gunakanlah outline atau kerangka tulisan terlebih dahulu ketika membangunnya.
    - Anda juga dapat menggunakan ilustrasi dan teks dalam dokumentasi tersebut.
    - Terakhir, jika Anda sudah menyelesaikan dokumentasi teknis, maka pastikan kembali. Anda bisa membacanya kembali dan bila ada yang kurang sesuai segera Anda revisi.
25. JSDoc merupakan salah satu tools yang dapat digunakan untuk membuat dokumentasi teknis dari komentar yang diberikan pada berkas program Javascript.
26. Sebelum Anda mengomunikasikan perihal dokumentasi, Anda perlu memperhatikan beberapa hal penting berikut :
    - Pastikan apa yang sudah Anda tulis dalam dokumentasi sudah benar dan sudah sesuai.
    - Perlu kamu tahu bahwa suatu dokumentasi teknis tidak hanya ditujukan kepada Anda saja melainkan untuk orang lain.
    - Ketika menyampaikan pun harus dengan adab atau beretika atau sopan santun..
    - Pastikan Anda mendokumentasikan teknis aplikasi secara online, serta memikirkan juga siapa saja yang dapat mengaksesnya karena keamanan dokumentasi teknis juga perlu dipikirkan.
27. Sebelum Anda mengomunikasikan perihal dokumentasi, Anda perlu memperhatikan beberapa hal penting berikut :
    - Pastikan apa yang sudah Anda tulis dalam dokumentasi sudah benar dan sudah sesuai. Luangkan waktu untuk membaca kembali. Sebab, sebuah typo saja bisa menimbulkan masalah.
    - Dokumentasi ini tidak hanya ditujukan kepada Anda saja. Namun, untuk orang lain. Oleh karena itu, ketika Anda menuliskan dokumentasi teknis jangan terlalu berpikir secara tertutup. Jangan sampai hanya karena Anda merasa baik-baik saja, maka semua itu sudah selesai ya. Pastikan Anda memposisikan sebagai pembaca, baik atasan maupun stakeholder lainnya.
    - Ketika menyampaikan pun harus dengan adab ya. Sebab, sebaik apapun dokumentasi yang dibuat jika Anda menyepelekan masalah adab maka akan menimbulkan masalah. Contohnya, ketika sudah menentukan deadline pembuatan maka Anda harus menepatinya. Kalau dirasa ada yang salah, maka segeralah katakan. Jangan sampai ketika deadline datang, namun Anda justru memberikan seribu alasan karena dokumentasi belum siap.
    - Pastikan Anda mendokumentasikan teknis aplikasi secara online. Seperti yang sudah dijelaskan pada materi sebelumnya, mendokumentasikan secara online akan memberikan banyak manfaat. Namun, Anda perlu memikirkan juga siapa saja yang dapat mengaksesnya karena keamanan dokumentasi teknis juga perlu dipikirkan. Jangan sampai hal yang bersifat rahasia, justru karena keteledoran Anda menjadikan kebocoran informasi.
