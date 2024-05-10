# Kalkulator Nilai Perolehan Tanah Umum

Kalkulator Nilai Perolehan Tanah adalah sebuah aplikasi web sederhana yang memungkinkan pengguna untuk menghitung nilai perolehan tanah berdasarkan dua metode: NJOP (Nilai Jual Objek Pajak) dan Manual. Aplikasi ini berguna bagi mereka yang membutuhkan perkiraan biaya pembuatan surat tanah.

## Hitung Manual

![image](https://github.com/MRizkiMaulana/Kalkulator-Tanah-Umum/assets/100768439/a008825a-cb6c-4301-abe2-ae25c104afa3)

## Hitung NJOP

![image](https://github.com/MRizkiMaulana/Kalkulator-Tanah-Umum/assets/100768439/36145bea-e2fa-4254-a816-3a49fa77ea36)



## Fitur

- **Metode Hitung**: Pengguna dapat memilih antara dua metode perhitungan: NJOP atau Manual.
- **Input Data**: Pengguna diminta untuk memasukkan informasi seperti nama penjual, nama pembeli, alamat, nomor NOP SPPT, NJOP, luas tanah, dan luas bangunan.
- **Perhitungan Otomatis**: Berdasarkan input pengguna, kalkulator akan melakukan perhitungan otomatis dan menampilkan hasilnya.
- **Cetak Hasil**: Pengguna dapat mencetak hasil perhitungan untuk referensi.

## Teknologi yang Digunakan

- **HTML**: Digunakan untuk membangun struktur dan konten halaman web.
- **CSS**: Digunakan untuk mengatur tata letak dan gaya visual halaman web.
- **JavaScript**: Digunakan untuk mengatur logika perhitungan dan interaksi pengguna pada halaman web.
- **Radio Button dan Form Handling**: Menggunakan elemen radio button dan form handling dalam HTML untuk memungkinkan pengguna memilih metode perhitungan dan mengirimkan data ke JavaScript untuk diproses.
- **Event Listeners**: Menggunakan event listeners dalam JavaScript untuk menangani aksi pengguna seperti pengiriman formulir dan mencetak hasil.
- **Print Functionality**: Menambahkan fungsi untuk mencetak hasil perhitungan menggunakan JavaScript dan `window.print()`.

## Struktur File

- **index.html**: Halaman utama yang memuat pilihan untuk menggunakan kalkulator NJOP atau Manual.
- **njop.html**: Halaman untuk kalkulator nilai perolehan tanah menggunakan metode NJOP dan juga memilih perhitungan htung-ajb atau hitung-segel.
- **manual.html**: Halaman untuk kalkulator nilai perolehan tanah menggunakan metode manual dan juga memilih perhitungan htung-ajb atau hitung-segel.
- **animasi1.html**: Halaman untuk animasi NJOP.
- **animasi2.html**: Halaman untuk animasi Manual.
- **src**: Folder yang berisi file-file sumber seperti JavaScript dan CSS.
  - **js**: Folder yang berisi file JavaScript untuk logika perhitungan.
  - **css**: Folder yang berisi file CSS untuk gaya halaman.

## Cara Menggunakan

1. Buka file `index.html` menggunakan peramban web (browser) Anda.
2. Pilih metode hitung yang diinginkan (NJOP atau Manual).
3. Isi formulir dengan informasi yang diminta.
4. Pilih hitung-ajb atau hitung-segel, secara otomatis akan terpilih hitung-ajb
5. Klik tombol "Hitung" untuk melihat hasil perhitungan.
6. Opsional: Klik tombol "Cetak Hasil" untuk mencetak hasil perhitungan.

## Demo

Anda dapat melihat demo langsung dari aplikasi ini di [tautan](https://mrizkimaulana.github.io/Kalkulator-Tanah-Umum/).


