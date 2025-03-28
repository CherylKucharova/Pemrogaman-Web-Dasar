# Tech Stack dan Web Environment
Dalam pemrograman web, terdapat istilah "Tech Stack" dan "Web Environment". Tech stack adalah kombinasi teknologi yang digunakan perusahaan untuk membangun dan menjalankan aplikasi atau proyek. Kadang-kadang disebut “susunan solusi,” tech stack biasanya terdiri dari bahasa pemrograman, kerangka kerja, database, alat front-end, alat back-end, dan aplikasi yang terhubung melalui API, sedangkan Web Environment itu sendiri didefinisikan sebagai tumpukan situs web atau aplikasi situs web lengkap yang berisi semua yang dibutuhkan situs web atau aplikasi untuk memberikan fitur dan konten kepada pengguna.

Dalam perkembangannya terdapat 2 divisi besar pengembangan web, antara lain:
### **1. Pengembangan Front-End (pengembangan sisi klien)**
Pengembangan front-end mengacu pada pembuatan apa yang dilihat pengguna saat mereka memuat aplikasi web – konten, desain, dan cara Anda berinteraksi dengannya. Hal ini dilakukan dengan tiga kode yaitu HTML, CSS, dan JavaScript.
### **2. Pengembangan Back-End (pengembangan sisi server)**
Pengembangan back-end mengendalikan apa yang terjadi di balik layar aplikasi web. Back-end sering kali menggunakan basis data untuk menghasilkan front-end.

Namun dalam repository ini, akan fokus membahas terkait tech stack front-end (HTML) itu sendiri. 

# Tech Stack: Front-End (HTML)
Front-end adalah salah satu bagian dari website yang menampilkan tampilan bagi para pengguna untuk memperoleh informasi hingga interaksi dengan suuatu situs website atau aplikasi secara nyaman , tampilan atau antarmuka pengguna (user interface) yang melibatkan desain, struktur, dan elemen visual yang terlihat di layar, hal ini memungkinkan pengguna untuk berinteraksi dengan aplikasi yang kita miliki. Tugas front-end adalah memindahkan desain yang dibuat dari UI designer dalam bentuk yang lebih interaktif dan membuat desain tersebut lebih hidup.

HTML (Hyper Markup Language) adalah bahasa pengkodean yang digunakan untuk membuat dan menyusun konten pada halaman web. HTML digunakan untuk mendefinisikan struktur dan tampilan halaman web serta mengint. HTML menggunakan tag dan atribut untuk menentukan elemen dan makna konten web.

# Komponen HTML 
Beberapa komponen utama HTML secara umum sebagai berikut.

### **1. Tag**
Tag adalah komponen dasar dalam HTML yang digunakan untuk mendefinisikan struktur dan konten halaman web yang terdiri dari dua bagian, tag pembuka, dan tag penutup. Tag ditulis dengan tanda kurung <...> yang di dalamnya terdapat nama tag. <br> Beberapa jenis tag HTML sebagai berikut.
- "< HTML >"  : Memulai halaman HTML yang akan menampilkan elemen-elemen konten dan mendefinisikan seluruh dokumen HTML.
- "< Head > " : Berisi metadata informasi seperti deskripsi dan membuat halaman html yang berisi deskripsi dihasil percaharian serch egine.
- "< Title >" : Menetapkan judul halama web yang akan ditampilkan pada tab browser.
- "< Body >"  : Merupakan bagian utama dari halaman web, dimana berisi semua konten yang ingin ditampilkan kepada audiens.

### **2. Attributes** 
Attributes adalah bagian dari tag yang memberikan informasi penjelas dan tambahan tentang tag tertentu. Atribut terdiri dari dua bagian yaitu, nama atribut dan nilai atribut. Nama atribut ditulis didalam tag dan diikuti dengan tanda "=" dan nilai atribut diapit oleh tanda kutip dua. Beberapa jenis attribute khusus yang digunakan tag sebagai berikut.
- Action   : digunakan pada tag "< Form >".
- Src      : digunakan pada tag "< img >" , "< audio >" , "< embed >".
- Href     : digunakan pada tag "< a >" dan "< link >".
- Autoplay : digunakan pada tag "< audio >" dan "< vidio >".

### **3. Element** 
Element adalah komponen yang berisikan keseluruhan kode yang berawal dari tag pembuka hingga tag penutup, yang terdiri dari teks dan simbol. <br> Beberapa contoh elemen HTML secara umum sebagai berikut.
-  Heading   : "< h1 >", "< h2 >" , "< h3 >" digunakan untuk menampilkan judul atau heading dengan tingkatan yang berbeda.
-  Paragraph : "< p >" digunakan untuk menampilkan paragraf teks, setiap teks yang ditempatkan di dalam elemen ini akan ditampilkan sebagai satu paragraf teks terpisah oleh browser.
-  Image     : "< img >" digunakan untuk menampilkan gambar dihalaman web.

# Kelebihan dan Kekurangan HTML
| Kelebihan HTML | Kekurangan HTML |
|-----------|------------|
|**Kemudahan penggunaan dan pembelajaran HTML** <br> HTML umumnya umumnya mudah dipelajari, terutama bagi pemula dalam desain web. Tak hanya itu, perangkat lunak untuk HTML juga tersedia secara gratis.|**Halaman Statis HTML** <br> HTML umumnya digunakan untuk halaman web statis. Untuk membuat website dinamis, perlu menggunakan bahasa pemrograman lain seperti PHP atau ASP.|
|**Kompatibilitas Luas** <br> HTML didukung dan dapat dijalani secara alami oleh seluruh web browser dan digunakan secara luas.|**Tidak Interaktif** <br> HTML tidak dapat digunakan untuk membuat halaman web yang interaktif atau dinamis, seperti formulir atau animasi.|
|**Integrasi** <br> HTML mudah diintegrasikan dengan bahasa backend seperti PHP dan Node.js, serta dapat diintegrasikan dengan JQuery, JavaScripts, dan CSS.|**Keterbatasan Desain** <br> HTML memerlukan CSS (Cascading Style Sheets) untuk tampilan yang lebih menarik.|
|**Open-source** <br> HTML bersifat open source dan gratis, memungkinkan modifikasi bebas.|**Tidak Mendukung Logika Pemrograman** <br> User tidak dapat menjalankan logic dikarenakan HTML hanya mengatur struktur, tidak untuk perhitungan.|
|**Standarisasi** <br> HTML adalah standar resmi web yang dikelola oleh W3C, memiliki bahasa markup yang rapi dan konsisten.|**Keamanan** <br> HTML tidak sepenuhnya aman dikarenakan tidak memiliki pengamanan tambahan dan lemah sehingga menyebabkan keamanan rentan terhadap serangan.| 
|**Dukungan untuk Gambar dan Media** <br> HTML memungkinkan penyisipan gambar, video, dan objek multimedia lainnya, yang memperkaya konten halaman web.|**Tidak Mendukung Fungsionalitas Backend** <br> HTML tidak bisa berinteraksi langsung dengan server dan tidak mendukung penyimpanan data, sehingga memerlukan teknologi lain untuk menyimpan data.|
|**SEO-Friendly** <br> Struktur HTML yang baik membantu mesin pencari memahami konten halaman, yang dapat meningkatkan peringkat di hasil pencarian.|**Kurang Efisien untuk Proyek Besar** <br> HTML Sulit dikelola tanpa kerangka kerja tambahan, seringkali pengkodean yang panjang membuatnya kompleks atau rumit.|

# Tren Perkembangan HTML Pada Tahun 2025
Tahun 2025 diprediksi akan menjadi tahun penuh inovasi dalam pengembangan frontend, dengan beberapa tren dan teknologi baru yang akan mendominasi. Berikut adalah tren perkembangan tech stack frontend, khususnya HTML, pada tahun 2025 ini.
### 1. **HTML5 dan Aksesibilitas**
HTML5 tetap menjadi fondasi utama dalam pengembangan web. Dengan fokus pada aksesibilitas dan praktik SEO-friendly, pengembang diharapkan dapat memahami penggunaan tag semantik dan ARIA (Accessible Rich Internet Applications) untuk memastikan aplikasi web dapat diakses oleh semua pengguna, termasuk mereka yang memiliki disabilitas.

### 2. **Framework dan Library JavaScript Baru** 
JavaScript terus menjadi bahasa utama di sisi frontend. Beberapa framework dan perpustakaan yang perlu diperhatikan pada tahun 2025 meliputi: 
- Bereaksi: Masih dominan dengan penambahan fitur baru seperti React Server Components untuk meningkatkan performa aplikasi.
- Bahasa pemrograman Vue.js: Menyediakan kemudahan penggunaan dengan peningkatan kinerja di Vue.
- Langsing: Mendapat popularitas karena pendekatannya yang unik dalam membangun aplikasi dengan kode yang lebih sederhana saat build.

### 3. **Integrasi AI dan Pembelajaran Mesin**
Integrasi AI dalam frontend akan semakin mendalam, memungkinkan pengembang untuk menggunakan API dan perpustakaan AI untuk menciptakan pengalaman pengguna yang lebih pribadi, contohnya termasuk fitur rekomendasi otomatis dan chatbots pintar.

### 4. **WebAssembly (Wasm)**
WebAssembly memungkinkan eksekusi kode berkecepatan tinggi di browser, menjadikan aplikasi web lebih efisien dalam melakukan komputasi berat. Dengan dukungan dari berbagai bahasa pemrograman seperti C dan Rust, Wasm akan semakin penting bagi pengembang frontend.

### 5. **Jamstack dan Headless CMS**
Pendekatan Jamstack (JavaScript, APIs, and Markup) semakin populer karena menawarkan kecepatan dan keamanan yang lebih baik. Penggunaan headless CMS seperti Strapi dan Contentful akan meningkat, memungkinkan perpecahan antara frontend dan backend.

### 6. **Server-Side Rendering (SSR) dan Static Site Generation (SSG)**
Teknologi SSR dan SSG akan terus menjadi tren utama untuk meningkatkan kecepatan download halaman dan optimasi SEO. Framework seperti Next.js dan Nuxt.js sangat diandalkan untuk implementasi SSR.

### 7. **Motion UI dan Animasi Halus**
Animasi menjadi elemen penting dalam pengalaman pengguna, dengan tren motion UI yang semakin berkembang. Penggunaan perpustakaan seperti Framer Motion dan GSAP untuk menciptakan animasi interaktif akan semakin populer.

Dengan memahami tren ini, pengembang dapat mempersiapkan diri untuk mengembangkan aplikasi web yang lebih cepat, efisien, dan menarik di tahun 2025.

# Perusahaan/Web yang Menggunakan HTML
HTML digunakan secara luas oleh berbagai perusahaan untuk membangun struktur dan konten situs web mereka. Berikut adalah beberapa contoh perusahaan dan situs web yang menggunakan HTML.
### **1. Samsung Electronics Co., Ltd.**
Samsung Electronics Co., Ltd. adalah salah satu perusahaan terkemuka di dunia dalam industri elektronik dan teknologi, yang menggunakan HTML secara ekstensif dalam pengembangan situs web dan aplikasi mereka. Berikut adalah beberapa cara Samsung memanfaatkan HTML:
- Situs web resmi Samsung ( https://www.samsung.com ) dibangun dengan HTML untuk menyajikan produk, layanan, dan berita informasi terbaru. HTML digunakan untuk mengatur konten seperti teks, gambar, dan video, serta untuk memastikan situs tersebut responsif di berbagai perangkat.
- Samsung juga menyediakan panduan pengembangan untuk aplikasi yang berjalan di perangkat Galaxy, termasuk penggunaan HTML dalam membangun antarmuka pengguna (UI). Misalnya, dokumentasi dari Samsung Developer menjelaskan bagaimana menggunakan HTML untuk membuat layout yang sederhana dan interaktif dalam aplikasi berbasis web.
- HTML digunakan dalam halaman template yang dioptimalkan untuk perangkat Samsung Galaxy, memastikan bahwa pengalaman pengguna di ponsel tetap cepat dan responsif. Ini termasuk penggunaan elemen HTML yang dirancang agar sesuai dengan berbagai ukuran layar dan resolusi.
- Samsung Internet untuk Android mengintegrasikan banyak fitur berbasis HTML yang memungkinkan pengalaman browsing yang lebih baik. Ini mencakup optimalisasi kecepatan memuat dan dukungan untuk teknologi web modern seperti Progressive Web Apps (PWA), yang memanfaatkan HTML untuk memberikan pengalaman aplikasi asli di browser.

Dengan menggunakan HTML sebagai dasar pengembangan web dan aplikasi, Samsung memastikan bahwa produk dan layanan mereka dapat diakses dengan mudah oleh pengguna di seluruh dunia.

### **2. Tokopedia**
Tokopedia adalah salah satu platform e-commerce terbesar di Indonesia yang memanfaatkan HTML dalam pengembangan situs web dan aplikasinya. Berikut adalah beberapa cara Tokopedia menggunakan HTML.
- Tokopedia menggunakan HTML untuk membangun struktur dasar situs web mereka. HTML menyediakan elemen-elemen seperti header, footer, navigasi, dan konten produk yang memungkinkan pengguna menjelajahi berbagai kategori dan produk dengan mudah.
- HTML digunakan untuk membuat formulir interaktif di situs Tokopedia, seperti formulir pendaftaran pengguna, formulir pembelian, dan formulir pencarian. Ini memungkinkan pengguna untuk berinteraksi dengan platform secara efisien.
- Tokopedia juga menyediakan sumber daya pendidikan tentang HTML melalui platform mereka. Misalnya, mereka menawarkan kursus tentang dasar-dasar HTML yang membantu calon pengembang web memahami cara menggunakan bahasa ini untuk membuat situs web.
- Tokopedia menjual berbagai template HTML dan produk terkait lainnya di platform mereka, memungkinkan pengguna untuk membeli dan menggunakan template untuk keperluan desain web.
- Tokopedia mengadopsi teknologi web modern yang mengintegrasikan HTML dengan CSS dan JavaScript untuk menciptakan pengalaman pengguna yang responsif dan interaktif. Ini termasuk penggunaan teknik seperti Responsive Web Design (RWD) untuk memastikan situs dapat diakses dengan baik di berbagai perangkat.

Dengan memanfaatkan HTML sebagai bagian dari tech stack mereka, Tokopedia dapat memberikan pengalaman belanja online yang luas dan fungsional bagi penggunanya.

### **3. Go-Jek**
Go-Jek adalah perusahaan teknologi asal Indonesia yang menyediakan layanan transportasi, pengantaran makanan, dan berbagai layanan on-demand lainnya. Berikut adalah beberapa cara GoJek menggunakan HTML.
- Website Go-Jek dirancang menggunakan HTML yang responsif, memungkinkan tampilan yang baik di berbagai perangkat, baik desktop maupun mobile. Ini penting karena banyak pengguna mengakses layanan melalui smartphone.
- Di bagian atas pada tampilan menu, terdapat menu navigasi yang jelas, memungkinkan pengguna untuk dengan mudah menemukan informasi tentang layanan, promo, dan cara bergabung. Penggunaan tag HTML seperti <nav> untuk navigasi dan <header> untuk bagian atas halaman membantu dalam strukturisasi konten.
- Website ini memanfaatkan gambar dan video untuk menarik perhatian pengguna. Penggunaan elemen multimedia dalam HTML meningkatkan pengalaman pengguna dan menyampaikan informasi dengan lebih efektif.
- Meskipun HTML membangun struktur dasar, Go-Jek juga mengintegrasikan JavaScript untuk menambah elemen interaktif, seperti tombol pemesanan dan fitur pencarian.

Perusahaan Go-Jek menunjukkan bagaimana HTML dapat digunakan secara efektif dalam desain web untuk menciptakan pengalaman pengguna yang menarik dan fungsional.

### **4. Ruangguru**
Ruangguru adalah platform pendidikan digital yang sangat populer di Indonesia, yang menyediakan berbagai layanan belajar online untuk siswa dari berbagai jenjang pendidikan. Berikut adalah beberapa cara Ruangguru menggunakan HTML.
- Website Ruangguru dirancang dengan menggunakan HTML yang responsif, memungkinkan pengguna untuk mengakses materi pembelajaran dengan nyaman di berbagai perangkat, termasuk smartphone, tablet, dan desktop. Hal ini sangat penting mengingat banyak siswa yang menggunakan perangkat mobile untuk belajar.
- Website ini memiliki menu navigasi yang jelas dan mudah digunakan, memudahkan pengguna untuk menemukan informasi tentang berbagai layanan yang ditawarkan, seperti bimbingan belajar, video pembelajaran, dan latihan soal. Penggunaan elemen HTML seperti "< nav >" dan "< header >" membantu dalam menciptakan struktur yang terorganisir.
- Ruangguru memanfaatkan elemen multimedia dalam HTML untuk menyajikan konten pembelajaran yang menarik. Ini termasuk video pembelajaran, animasi, dan gambar yang mendukung materi ajar. Penggunaan tag  "< video >" dan "< img >" dalam HTML memungkinkan penyisipan konten visual yang memperkaya pengalaman belajar.
- Dengan peluncuran "Ruang Belajar Web" pada tahun 2022, Ruangguru memberikan kemudahan akses bagi pengguna yang sebelumnya mengalami keterbatasan dalam menggunakan aplikasi mobile. Website ini memungkinkan siswa untuk mengakses materi pembelajaran tanpa perlu mengunduh aplikasi, cukup melalui browser seperti Google Chrome.
- Meskipun HTML membangun struktur dasar website, Ruangguru juga mengintegrasikan JavaScript untuk menambah elemen interaktif, seperti fitur kuis dan forum diskusi antara siswa dan pengajar. Ini meningkatkan keterlibatan pengguna dalam proses belajar.

Ruangguru telah berhasil memanfaatkan teknologi web dengan baik melalui penggunaan HTML untuk menciptakan platform pendidikan yang tidak hanya informatif tetapi juga interaktif dan mudah diakses. Dengan fokus pada pengalaman pengguna dan aksesibilitas, Ruangguru terus berinovasi dalam menyediakan layanan pendidikan berkualitas tinggi bagi siswa di Indonesia.

### **5. Prudential**
Prudential adalah Perusahaan penyediaa asuransi di Indonesia yang memberikan perlindungan kesehatan dan risiko keuangan yang meliputi asuransii jiwa dan kesehatan serta manajemen investaasi yang bersistem berjangka dan seumur hidup untuk memberikan perlindungan bagi keluarga. Berikut adalah beberapa cara Prudential menggunakan HTML.
- Website Prudential dirancang untuk meningkatkan kemudahan akses informasi dengan aman, dan interaktif bagi nasabah , mendukung transaksi online, dan berkontribusi pada strategi pemasaran digital perusahaan.
- Prudential yang memiliki tujuan mendukung oprasional , layanan dan peningkatan pengalaman bagi nasabah pada perusahaan asuransi ini.
- Website Prudential menggunakan elemen seperti, elemen struktural, elemen interaktif, elemen media, elemen semantik, elemen pendukung aksesiblitas,  dan elemen modern HTML5. Elemen ini dgunakan untuk memberikan pengalaman pengguna yang optimal dengan antarmuka yang responsif.
- Elemen HTML semantik adalah yang paling penting untuk aksesibilitas digital mengguanakan elemen struktural untuk membnbuat situs atau aplikasi daan sebagai garis besar di layar dan untuk memudahkan navigasi. Elemen semantik memudaahkan screen reader untuk menginterpretasikan konten halaman web.
  
### **6. Pertamina**
Pertamina adalah Perusahaan terbesar kedua dibidang perminyakan milik negara (BUMN) yang menyediakan energi dan mengembangkan energi baru dan terbarukan khususnya minyak dan gas. Perusahaan memproduksi  banyak komoditas seperti bahan bakar, minyak tanah, LPG, LNG, dan Petrokimia. Beriku adalah beberapa cara Pertamina menggunakan HTML.
- Website pertamina dirancang untuk kebutuhan informasi sebagai penyediaa , interaksi , pengalaman pengguna, kemudahan navigasi, responsivitas dan interaktivitas.
- Elemen HTML yang digunakan struktur navigasi seperti (tentang kami, produk , layanan dan membuat daftar tautan dalam navigasi), konten utama seperti (header, section, article, dan footer), Media visual seperti (img dan video), Formulir interaktif seperti (form, input, textarea, dan button).
- HTML pada website pertamina diintergrasikan dengan CSS daan Bootstrap untuk memastikan tampilan responsif diberbagai peragkat daalam menyesusaikan tata letak berdasarkan ukuran layar dan memngatur dalam kolom dengan ukuran yang fleksibel.

# Sumber Data
https://accurate.id/teknologi/front-end-adalah/

https://www.biznetgio.com/news/apa-itu-html

https://ids.ac.id/apa-itu-tech-stack-memilih-apa-yang-ada-dalam-diri-kamu/

https://www.revou.co/panduan-teknis/tag-html

https://bcisnotes.com/fourthsemester/introduction-to-web-environment-web-environment-bcis-notes/

https://www.sekawanmedia.co.id/blog/pengertian-html/#:~:text=Sejarah%20HTML%20pertama%20kali%20dibuat,dalamnya%20terdalam%20sekitar%2018%20tag.

https://www.hi-interactive.com/blog/the-future-of-html-trends-tips-and-ai

https://roadmap.sh/frontend/technologies 

https://dev.to/jps27cse/the-ultimate-frontend-developer-roadmap-for-2025-4ndm 

https://i-as.dev/blog/tren-frontend-apa-yang-harus-anda-pelajari 

https://developer.samsung.com/galaxy-watch-tizen/creating-your-first-app/web-companion/build-ui.html 

https://developer.samsung.com/one-ui/structure/basic.html 

https://instapage.com/en/template/html-page-template-optimized-for-samsung-galaxy 

https://developer.samsung.com/internet/android/web-developer-guide.html

https://badoystudio.com/contoh-website-perusahaan/ 

https://www.hostnic.id/blog/tutorial/website/pengertian-html-fungsi-dan-kelebihan-serta-kekurangannya/

https://kelas.work/blogs/mengenal-bahasa-pemrograman-html-dan-fungsi-utamanya

https://www.exabytes.co.id/blog/pengertian-html/#Kelebihan-HTML

https://blog.ionnetwork.co.id/html-adalah/

https://www.ekrut.com/media/html

https://cloudku.id/html-atau-wordpress-mana-yang-lebih-baik/

https://www.hostinger.com/id/tutorial/apa-itu-html#Kelebihan_dan_Kekurangan_HTML

https://www.biznetgio.com/news/apa-itu-html

https://myedusolve.com/id/blog/html-adalah-definisi-komponen-dan-fungsi-bagi-website

https://www.prudentialsyariah.co.id/id/privacy-notice/

https://webdevlabs.wordpress.com/2012/01/15/pertamina-css-logo/

<!DOCTYPE html>
<html>
<body>

<h2>Mind Map Tech Stack Front-End (HTML)</h2>
<img src="https://github.com/CherylKucharova/Pemrogaman-Web-Dasar/blob/a98a0ee56a08df178809f5c5a1569ee237fbbbef/Mind%20map.jpg">


</body>
</html>

