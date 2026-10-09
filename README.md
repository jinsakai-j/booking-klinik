# Booking Klinik Sejahtera

Aplikasi untuk mengelola janji temu pasien di klinik. Dalam aplikasi ini
pasien bisa membuat janji temu baru, mengubah jadwal yang sudah dibuat,
dan melihat rincian appointment.

Halamannya ada 4:

- index.html, halaman utama berisi daftar janji temu dan daftar dokter
- booking.html, form untuk membuat janji temu baru
- edit.html, form untuk mengubah janji temu yang sudah ada
- detail.html, rincian dari satu janji temu

Data yang disimpan berupa data pasien (nama, NIK, tanggal lahir, jenis
kelamin, nomor HP) dan data appointment (dokter, tanggal, jam, metode
bayar, keluhan, dan status).

Untuk tahap ini baru dibuat strukturnya saja memakai HTML, belum ada CSS
dan JavaScript, jadi tampilannya masih polos.

Update week3
Sekarang udah ditambahin file style.css yang di-link ke semua halaman. HTML-nya sendiri gak diubah banyak, cuma nambah beberapa div sama span biar bisa di-styling.

Yang diterapin di CSS:
- font-family, font-size, font-weight buat judul sama teks isi biar konsisten
- styling list buat menu navigasi sama daftar dokter
- text-align buat judul dan label form
- warna background sama teks dibikin konsisten
- pakai div sama span buat nge-group elemen tertentu
- media query, jadi kalau layarnya sempit menu yang tadinya horizontal berubah jadi vertikal

Update week4
Di minggu ini tampilannya diganti pakai Bootstrap 5 yang dihubungkan lewat CDN, jadi gak perlu build atau install apa pun. HTML-nya diubah lumayan banyak, terutama header diganti jadi navbar Bootstrap, tabel dikasih class table, dan form dikasih class form-control sama form-select.

Alasan pakai Bootstrap: halaman di aplikasi ini isinya banyak tabel sama form, jadi komponen yang udah disediain Bootstrap tinggal dipakai dan hasilnya langsung rapi tanpa nulis CSS dari nol. Navbar-nya juga otomatis berubah jadi menu hamburger kalau layarnya kecil.

File style.css sekarang dikurangin, cuma nyimpen warna hijau buat identitas klinik aja. Untuk screenshot tampilan desktop sama mobile udah disimpan di folder docs/screenshots.

Rajaa Azharul Hanafi - 103022400116
