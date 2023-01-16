# crimeinboston_eda_cpm2

Dipersiapkan oleh Andi Setianto

- Untuk mengakses direktori file / link secara lengkap, kunjungi https://linktr.ee/andisetianto

LATAR BELAKANG

Kota Boston merupakan salah satu kota tertua dan terkaya di Amerika Serikat, namun menjadi suatu ironi ketika mengetahui fakta bahwa kejahatan di kota Boston meningkat secara signifikan dari tahun ke tahun terutama dalam perampokan, pencurian dan pencurian mobil. Berdasarkan data Uniform Crime Reports (UCR), kota Boston dinobatkan sebagai kota dengan jumlah kejahatan terbanyak dibandingkan kota-kota lainnya. Departemen Kepolisian Boston (BPD) memberikan laporan tentang kejahatan yang terjadi di kota Boston antara 14 Juni 2015 dan 3 September 2018, beserta informasi tentang sifat kejadian, waktu kejadian, dan tempat geografis Tempat di mana kejahatan itu terjadi.

Dengan adanya data yang sudah terdokumentasi, analis kejahatan Departemen Kepolisian Boston berharap dapat memberikan wawasan untuk pengambilan keputusan, misalnya rumusan mengenai jumlah polisi yang tepat untuk berpatroli dan menyiagakan daerah rawan kejahatan, dan ingin meningkatkan kecepatan dan kesiagaan dalam merespon tindak kejahatan ataupun panggilan dari masyarakat yang terjadi di kota Boston, sehingga baik pencegahan ataupun penindakan dapat dijalankan secara tepat sasaran dan efektif.

TUJUAN ANALISIS
1. Membantu Boston Police Department dalam membuat kebijakan yang efektif dan efisien dalam merespon tindak kejahatan/ panggilan masyarakat yang terjadi di kota Boston
2. Menjadi referensi yang dapat membantu fungsi/aspek pencegahan kejahatan yang ada di Kota Boston
3. Membantu menurunkan angka kejahatan di Boston

PROBLEM STATEMENT

1. Bagaimana kondisi / tren tindak kejahatan di Kota Boston dari waktu ke waktu? 
2. Jika ditinjau dari jenis/bentuk kejahatan yang terjadi, apakah ada informasi yang dapat kita ekstrasi dari jenis kejahatan yang terjadi di Kota Boston?
3. Bagaimana kondisi tindak kejahatan di Kota Boston jika ditinjau berdasarkan lokasi kejadian ataupun kondisi geografis? 
4. Berdasarkan data yang ada, apakah penanganan yang dilakukan oleh pihak kepolisian sudah tepat sasaran? 
5. Apakah ada faktor lain yang relevan dengan tindak kejahatan di Kota Boston? misalnya cuaca dalam rentang wakta yang tersedia dalam data set.

KONTEKS DATA

Merupakan data laporan insiden kejahatan disediakan oleh Departemen Kepolisian Boston (BPD) untuk mendokumentasikan detail awal seputar insiden yang ditanggapi oleh petugas BPD. Berupa kumpulan data yang berisi catatan dari sistem laporan insiden kejahatan, yang difokuskan untuk merekam jenis insiden serta kapan dan di mana itu terjadi. Jangkauan data yaitu pada 14 Juni 2015 hingga 3 September 2018.

PENYEDIA DATA
Data tersebut disediakan oleh Analyze Boston. Apabila ingin mengakses lebih lanjut dapat melalui link berikut: https://www.kaggle.com/datasets/AnalyzeBoston/crimes-in-boston

PENJELASAN TIAP FIELD

1. INCIDENT_NUMBER : Merupakan primary key / penomoran yang bersifat unik untuk setiap kejadian yang terjadi
2. OFFENSE_CODE : Merupakan kode insiden yang terjadi
3. OFFENSE_CODE_GROUP : Merupakan kategori insiden yang terjadi
4. OFFENSE_DESCRIPTION : Deskripsi singkat yang menjelaskan terkait kejadian
5. DISTRICT : Kode distrik tempat terjadinya insiden
6. REPORTING_AREA : Kode area berdasarkan area/lokasi yang dilaporkan
7. SHOOTING : Field yang menunjukan apakah terjadi penemabakan atau tidak, bersifat True / Flase (Yes / No)
8. OCCURRED_ON_DATE : Tanggal dan waktu terjadinya insiden
9. YEAR : Tahun terjadinya insiden
10. MONTH : Bulan terjadinya insiden
11. DAY_OF_WEEK : Hari terjadinya insiden
12. HOUR : Jam terjadinya insiden
13. UCR_PART : Index Uniform Crime Report
14. STREET : Nama jalan tempat terjadinya insiden
15. Lat : Garis Lintang titik terjadinya insiden
16. Long : Garis Bujur titik terjadinya insiden
17. Location : Titik lokasi berdasarkan informasi garis lintang dan garis bujur

___
KONKLUSI

BERDASARKAN WAKTU:

Secara umum, jika dilihat dari prepektif waktu kejadian, kejahatan sering terjadi pada jam kerja / hari sibuk, dan puncaknya adalah hari Jumat malam hingga dini hari,

ACTION

Pihak kepolisian harus mengerahkan personilnya untuk berjaga pada jam – jam tersebut, khususnya di area kampus, area perkantoran, ataupun pusat keramaian / bisnis lainnya.
Terkait tingkat kejahatan pada Jumat malam / sabtu dini hari, polisi harus sering melaukan patrol, dan memusatkan pada titik hiburan malam, seperti bar, karaoke, dll. Karena ketika mabuk orang menjadi lebih tidak terkontrol.
Kemudian jika melihat pola yang terjadi, penjagaan polisi harus semakin ketat pada bulan Juni – Juli –Agustus, karena merupakan masa ajaran baru / masuk perkuliahan

BERDASARKAN TEMPAT

Polisi harus berjaga pada daerah yang rawan kejahatan, misalnya Roxbury, Dorchester, dan Soutboston, dan daerah lainnya yang berdekatan, ataupun daerah yang mobilisasinya menuju ke area rawan tersebut (jika di Indonesia contohnya adalah Jakarat – Bekasi, Jakarat Tangerang, dll). Karena berdasarkan referensi, Roxbury memang kota yang berbahaya. 

ACTION

Pihak keamanan harus mengingatkan pada pengunjung / pelancong wanita, ataupun penduduk sekitar agar membatasi jalan kaki dan bersepeda sendiri.

___
BERDASARKAN JENIS KEJAHATAN

Tingkat kejahatan tertinggi didominasi oleh pencurian / penyerangan hingga membuat tubuh terluka, penyalahgunaan senjata, dan pembunuhan. Maka dengan memfokuskan pada permasalahan tersebut, berpotensi menurunkan tingkat kejahatan secara signifikan. Meskipun presentase kejahatan penembakan hanya 0.32% dari seluruh data, hal tersebut tetap perlu menjadi perhatian khusus

ACTION

Salah satu solusinya adalah memperketat peredaran senjata, melalui regulasi yang mengikat. Terkait UCR,secara organsasi, polisi perlu membuat tim khusus yang berfokus pada setiap UCR, sehingga tiap jenis UCR dapat termonitoring dengan baik, selain itu kebijakan tentang UCR juga harus dikembangkan

___
BERDASARKAN PENANGANAN POLISI

Dari hasil analisa, Medical Assistance/ bantuan medis kepada korban di TKP
mendapati posisi tertinggi,

ACTION

Peningkatan kapasitas terkait ilmu medis harus ditingkatkan, baik dengan menambahkan kurikulum tentang penanganan pada pertolongan pertama pada pendidikan kepolisian, atau membangun pusat kesehatan pada daerah rawan.

___
BERDASARKAN FAKTOR LAIN

Musim dan cuaca memiliki pengaruh pada tingkat kejahatan

ACTION

Sosialisasi tentang pentingnya menjaga keamanan rumah saat musim panas, dan menerapkan alat keamanan (smart home) di rumah masing-masing.
Pihak kepolisian juga harus bekerja sama dengan instansi yang memiliki tupoksi terkait cuaca, agar memiliki data prakiraan cuaca dan menjadi dasar untuk pengerahan personil.

___
KONKLUSI UTAMA:

Secara pragmatis, pihak kepolisian perlu berjaga pada kota Roxbury dan sekitarnya, khususnya pada jam kerja dan hari jumat malam – hingga dini hari. Lalu memaksimalkan personil pada bulan Juni – Juli –Agustus, karena selain musim panas, juga masa perkuliahan dimulai.
(namun ini hanya solusi instant, berdasarkan tingkat urgensi yang paling tinggi saja, untuk memaksimalkannya perlu mempertimbangkan hasil analisa secara komprehensif)
 
__

DIREKTORI:

Kunjungi link https://linktr.ee/andisetianto untuk melihat file lainnya seperti PPT, file pendukung, link tableau, dan sebagainya.

