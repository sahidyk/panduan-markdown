## Bagaimana Cara Kerjanya?

Dillinger membuat penulisan Markdown mudah karena menyembunyikan hal-hal yang terjadi di belakang layar, tetapi ada baiknya juga Anda menjelajahi bagaimana proses bekerja Markdown secara umum.

Ketika Anda menulis Markdown, teks disimpan dalam file teks ASCII yang memiliki ekstensi `.md` atau `.markdown`. Selanjutnya bagaimana? Bagaimana file asli Markdown Anda dikonversi menjadi HTML atau dokumen siap cetak?

Jawaban singkatnya adalah Anda memerlukan *Aplikasi Markdown* yang mampu memproses file Markdown. Terdapat banyak aplikasi yang tersedia - semuanya mulai dari skrip sederhana hingga aplikasi desktop yang terlihat seperti Microsoft Word. Terlepas dari perbedaan visual mereka, semua aplikasi melakukan hal yang sama. Seperti Dillinger, semuanya mengkonversi teks asli Markdown ke HTML sehingga dapat ditampilkan di browser web.

Aplikasi Markdown menggunakan sesuatu yang disebut *pengolah Markdown* (juga biasa disebut sebagai "*parser*" atau "*implementasi*") untuk mengambil teks asli Markdown dan memprosesnya menjadi format HTML. Pada saat itu, dokumen Anda dapat ditampilkan di browser web atau dikombinasikan dengan skrip pengaturan dokumen dan dicetak. Anda dapat melihat representasi visual dari proses ini di bawah ini.

<div class="alert alert-info">
  <i class="fas fa-info-circle"></i> <strong>Catatan:</strong> Aplikasi dan prosesor Markdown adalah dua komponen terpisah. Untuk penyederhanaan, keduanya digabungkan menjadi satu elemen ("Aplikasi Markdown") pada gambar di bawah ini.
</div>



<div style="text-align:center; margin:30px 0">
  <img src="../assets/images/process.png" class="img-fluid" alt="The Markdown Process">
</div>



Untuk meringkas, ini adalah proses empat bagian:

1. Buat file Markdown menggunakan editor teks atau aplikasi Markdown khusus. File harus memiliki ekstensi `.md` atau `.markdown`.
2. Buka file Markdown dalam aplikasi Markdown.
3. Gunakan aplikasi Markdown untuk mengkonversi file Markdown ke dokumen HTML.
4. Lihat file HTML di browser web atau gunakan aplikasi Markdown untuk mengonversinya ke format file lain, seperti PDF.

Dari perspektif Anda, prosesnya akan bervariasi agak tergantung pada aplikasi yang Anda gunakan. Misalnya, Dillinger pada dasarnya menggabungkan langkah 1-3 ke dalam satu antarmuka yang mulus — yang harus Anda lakukan adalah mengetik di panel kiri dan setelah diproses secara ajaib muncul di panel kanan. Tetapi jika Anda menggunakan alat bantu lain, seperti editor teks dengan generator situs web statis, Anda akan menemukan bahwa prosesnya jauh lebih terlihat.
