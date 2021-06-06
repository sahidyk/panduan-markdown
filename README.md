# Panduan Markdown

[![Build Status](https://github.com/mattcone/markdown-guide/workflows/tests/badge.svg?branch=master)](https://github.com/mattcone/markdown-guide/actions)

*[Panduan Markdown](https://www.markdownguide.org)* ini adalah referensi Markdown komprehensif yang ditujukan bagi pemula dan mereka yang sudah mahir. Panduan ini dilatarbelangani oleh ketidakpuasan dengan referensi Markdown yang ada, yang tidak lengkap dan tidak memadai. Terjemahan bahasa Indonesia ini dilakukan oleh [Sahid](sahidyk.github.com) dari Panduan Markdown asli berbahasa Inggris.

### Menampilkan Panduan di Komputer Lokal

Sesuai dengan yang dijelaskan, Panduan ini ditulis dengan dan langsung menerapkan Markdown. Seluruh isi Panduan ini dapat ditampilkan secara interaktif sebagai halaman (situs) Web di komputer lokal (tidak harus terkoneksi Internet). Hal ini membantu untuk mempratinjau perubahan jika Anda mengedit isinya di komputer Anda sebelum diterbitkan di [GitHub](https://github.com). *Panduan Markdown* menggunakan [generator situs statis Jekyll](http://jekyllrb.com/). Untuk membuat situs lokal *Panduan Markdown* di komputer Anda, lakukan langkah-langkah sebagai berikut:

1. Komputer Anda harus terpasang software **Ruby**. Jika belum, unduh dari situs https://www.ruby-lang.org/en/downloads/. Untuk komputer MS Windows, Anda dapat mengunduh [RubyInstaller](https://rubyinstaller.org/downloads/) yang sudah sepaket dengan perlengkapan pengembangan software **Devkit**.

2. Pastikan Anda memiliki semua software yang diperlukan:

   > + [Ruby](https://www.ruby-lang.org/en/downloads/) versi **2.4.0** atau yang lebih baru, termasuk semua file-file header untuk mengembangan (Cek versi **Ruby** dengan perintah `ruby -v` pada jendela terminal.)
   >
   > + [RubyGems](https://rubygems.org/pages/download) (Cek versi Gems dengan perintah `gem -v` pada jendela terminal.)
   >
   > + Kompiler [GCC](https://gcc.gnu.org/install/) dan [Make](https://www.gnu.org/software/make/) (Cek versi masing-masing dengan perintah `gcc -v`,`g++ -v`, dan `make -v`). 
   >
   >   (Ketika Anda mimilih menginstal **Ruby+Devkit** dari **RubyInstaller**, Anda akan diberi pilihan untuk mengistal semua software tersebut, kecuali **Make**.)

3. Untuk menginstall **Make**  di MS Windows dapat menggunakan perintah `choco install make` pada jendela terminal atau **Powershell Win 10** sebagai **Admin**.

4. Install **Jekyll** melalui jendela terminal atau Powershell Win 10 sebagai Admin dengan perintah `gem install jekyll bundler`.

5. Pastikan Jekyll terpasang dengan benar: `jekyll -v`.

6. Kloning repositori panduan ini dari [GiHub](https://github.com/mattcone/markdown-guide) dengan salah satu cara:

   > + Gunakan tombol **Code** pada halaman repositori tersebut untuh mengunduhnya, atau
   > + Gunakan perintah `git clone https://github.com/mattcone/markdown-guide`.

7. Melalui jendela terminal, masuk ke folder hasil kloning tersebut, kemudian ketik perintah-perintah:

   > + `bundle install`
   > + `bundle exec jekyll serve`

8. Buka alamat URL http://127.0.0.1:4000/ dengan browser pilihan Anda.

9. Telusuri dan jelajahi isi Panduan ini melalui browser Anda tersebut.

## Lisensi

Seluruh isi Panduan ini diedarkan dengan lisensi [Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/), dan semua dokumen asli yang digunakan untuk memformat dan menampilkan isi panduan tersebut diedarkan dengan [lisensi MIT](LISENSI.txt).