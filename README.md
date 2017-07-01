# Introduction
**Kirim Tugas** -- adalah aplikasi yang dapat digunakan oleh guru/pendidik untuk mengumpulkan tugas (praktikum) siswa dengan lebih cepat dan rapi melalui jaringan LAN.

file hasil tugas siswa yang dikirim akan disimpan dengan mengubah nama filenya sesuai isian siswa, ini bisa membantu guru/pendidik merapikan arsip haril karya siswa, dan untuk menghindari resiko kehilangan data karena lupa nama dan lokasi file.

meskipun dibuat sederhana, tanpa penggunaan database, semoga aplikasi ini bisa memenuhi fungsinya mengurangi penggunaan "flashdisk bervirus" dari siswa pada saat mengumpulkan tugas.


![alt text](https://preview.ibb.co/kKPZiQ/Screenshot_from_2017_07_01_15_30_01.png "Preview")

### Penggunaan
Sebelum siswa mulai upload, pastikan sudah mengisi beberapa pengaturan awal di file ```config.php```, meliputi :
- Nama mapel
- Kelas / rombongan belajar
- Nama tugas
- Format file
- Ukuran maksimal file
- Pilihan mengiring ulang

Setelah semua siswa selesai mengirim tugas, segera amankan (copas) file yang tersimpan di server ke lokal.

### Fitur
- [x] filter ukuran file
- [x] filter tipe file
- [x] filter kirim ulang dan duplikasi file
- [ ] Admin login

### Image Credits
- [Bootstrap](http://getbootstrap.com/)
