# bootstrap

1. Pengertian Bootstrap
Apa itu Bootstrap: Bootstrap adalah sebuah framework (kerangka kerja) front-end sumber terbuka (open-source) yang populer dan dirancang khusus untuk mempermudah serta mempercepat pengembangan desain web yang responsif dan ramah seluler (mobile-first).   Kegunaannya: Menyediakan kumpulan komponen siap pakai (seperti tombol, navbar, modal, card) serta sistem grid CSS siap pakai sehingga pengembang tidak perlu menulis kode CSS dari nol untuk setiap elemen dasar tampilan web.
2.Memasang BootstrapAda beberapa cara umum untuk mengimpor atau menggunakan Bootstrap pada suatu proyek web:
-Menggunakan CDN (Content Delivery Network): Menyisipkan tautan (link) file CSS dan JavaScript eksternal dari layanan CDN resmi Bootstrap langsung ke dalam tag <head> dan sebelum penutup <body> di file HTML. (Cara ini paling cepat dan praktis tanpa perlu mengunduh file)
-Download File / Sourced Locally: Mengunduh berkas sumber CSS dan JS secara langsung dari situs resmi Bootstrap, lalu menyimpannya ke dalam folder proyek lokal dan menghubungkannya secara lokal menggunakan tag <link> dan <script>.
-Menggunakan Package Manager (npm / yarn / composer): Menginstal Bootstrap melalui manajer paket di terminal menggunakan perintah seperti npm install bootstrap@5.3.8 (biasanya digunakan pada proyek web modern berbasis framework atau bundler seperti Vite/Webpack).

3. Grid dan Breakpoint
Class Grid: Sistem tata letak berbasis flexbox di Bootstrap yang menggunakan struktur kontainer (.container), baris (.row), dan kolom (.col-*) untuk mengatur dan menyusun konten agar rapi secara horizontal dan vertikal dalam tata letak berbasis 12 kolom.
-Kegunaan Breakpoint: Batasan ukuran layar perangkat (seperti sm, md, lg, xl, xxl) yang mendefinisikan kapan tata letak grid atau komponen harus menyesuaikan diri secara responsif berdasarkan lebar layar perangkat pengguna (misalnya mengatur kolom agar berjajar di laptop, tetapi menumpuk ke bawah di layar ponsel).

4. Class Bootstrap (Minimal 5)Berikut adalah 5 contoh class yang disediakan oleh Bootstrap beserta kegunaannya:
-container / container-fluid: Digunakan untuk membungkus isi halaman, memberikan margin otomatis di sisi kiri/kanan, dan menjaga agar tata letak tetap berada di tengah.
-row: Digunakan sebagai wadah pembungkus kolom di dalam sistem grid agar elemen di dalamnya tersusun rapi secara horizontal.
-d-flex: Mengaktifkan model penataan fleksibel (Flexbox) pada suatu elemen HTML.
-shadow-sm / shadow: Memberikan efek bayangan (box-shadow) pada elemen (seperti kotak atau kartu) agar tampak seperti melayang atau lebih hidup.
-btn btn-primary: Mengubah tampilan tombol standar menjadi tombol bergaya interaktif dengan warna utama (biru) khas Bootstrap.

5. Gambar Responsif
Agar foto atau gambar pada website dapat tampil responsif dan otomatis menyesuaikan dengan ukuran layar perangkat, dapat menggunakan class bawaan Bootstrap yaitu img-fluid.
Cara penerapannya: Cukup tambahkan atribut class="img-fluid" di dalam tag gambar (<img>). Class ini secara otomatis akan menerapkan properti max-width: 100% dan height: auto sehingga ukuran gambar tidak akan keluar dari wadah atau merusak tata letak layar perangkat yang lebih kecil.
