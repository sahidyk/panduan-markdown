---
layout: default
title: Lembar Contekan Markdown
description: Panduan ringkas sintaks Markdown.
last_modified_at: 2020-07-31
---

## Informasi Umum

Lembar contekan Markdown ini memberikan gambaran singkat tentang semua elemen sintaks Markdown. Sudah tentu contekan ini tidak mencakup seluruh sintkas Markdown, jadi jika Anda membutuhkan informasi lebih lanjut tentang salah satu elemen Markdown, lihat panduan referensi untuk [sintaks dasar](/basic-syntax) dan [sitakas lanjut](/extended-syntax).

## Sintaks Dasar

Berikut adalah elemen-elemen yang diuraikan dalam dokumen desain asli John Gruber. Semua aplikasi Markdown mendukung elemen-elemen ini.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Elemen Dokumen</th>
      <th>Sintaks Markdown</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="/basic-syntax/#headings">Judul</a></td>
      <td><code># Judul tingkat 1<br>
          ## Judul tingkat 2<br>
          ### Judul tingkat 3</code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#bold">Huruf tebal</a></td>
      <td><code>**tulisan tebal**</code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#italic">Tulisan miring</a></td>
      <td><code>*tulisan miring*</code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#blockquotes-1">Kutipan</a></td>
      <td><code>> Teks kutipan</code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#ordered-lists">Daftar Terurut</a></td>
      <td><code>
        1. Butir 1<br>
        2. Butir 2<br>
        3. Butir 3<br>
      </code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#unordered-lists">Daftar Tanpa nomor</a></td>
      <td>
        <code>
          - Butir pertama<br>
          - Butir kedua<br>
          - Butir ketiga<br>
        </code>
      </td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#code">Kode/perintah</a></td>
      <td><code>`kode`</code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#horizontal-rules">Garis mendatar</a></td>
      <td><code>---</code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#links">Link</a></td>
      <td><code>[Teks link](https://www.example.com)</code></td>
    </tr>
    <tr>
      <td><a href="/basic-syntax/#images-1">Gambar</a></td>
      <td><code>![Teks pengganti](image.jpg)</code></td>
    </tr>
  </tbody>
</table>

## Sintaks Lanjut

Elemen-elemen di bawah ini merupakan perluasan sintask dasar dengan menambahkan kemampuan-kemampuan lebih lanjut untuk mendukung dokumen yang lebih kompleks. Tidak semua aplikasi Markdown mendukung sintask tambahan ini. Anda harus membaca dokumen aplikasi yang Anda gunakan dan mencobanya.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Elemen Dokumen</th>
      <th>Sintaks Markdown</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="/extended-syntax/#tables">Tabel</a></td>
      <td><code>
          | Judul kolom 1      | Judul kolom 2 |<br>
          | ----------- | ----------- |<br>
          | Isi baris 1 kolom 1      | Isi baris 1 kolom 2        |<br>
          | Isi baris 2 kolom 1    | Isi baris 2 kolom 2        |
      </code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#fenced-code-blocks">Blok kode/perintah/program</a></td>
      <td><code>```<br>
      {<br>
      &nbsp;&nbsp;"firstName": "John",<br>
      &nbsp;&nbsp;"lastName": "Smith",<br>
      &nbsp;&nbsp;"age": 25<br>
      }<br>
      ```
      </code></td>
    </tr>
    <tr>
      <td><a href="/extended-syntax/#footnotes">Catatan kaki</a></td>
      <td><code>
        Ini adalah teks yang diberi catatan kaki. [^1]<br><br>
        [^1]: Keterangan catatan kaki.
  </code></td>
</tr>
<tr>
  <td><a href="/extended-syntax/#heading-ids">Nama (ID) Judul</a></td>
  <td><code>### Judul yang diberi nama {#judulID}</code></td>
</tr>
<tr>
  <td><a href="/extended-syntax/#definition-lists">Daftar Istilah/Definisi</a></td>
  <td><code>
    istilah<br>
    : teks penjelasan/pengertian
  </code></td>
</tr>
<tr>
  <td><a href="/extended-syntax/#strikethrough">Tulisan dicoret</a></td>
  <td><code>~~Tulisan ini dicoret.~~</code></td>
</tr>
<tr>
  <td><a href="/extended-syntax/#task-lists">Daftar Tugas</a></td>
  <td><code>
    - [x] Tugas yang sudah dikerjakan<br>
    - [ ] Tugas yang belum dikerjakan<br>
    - [ ] Tugas lain yang belum selesai
  </code></td>
</tr>
 </tbody>
</table>

## Unduh

Anda dapat mengunguh <a href="/assets/markdown-cheat-sheet.md" download="markdown-cheat-sheet.md">berkas lembar contekan Markdown ini</a> untuk dibuka dengan aplikasi Markdown yang Anda gunakan.

