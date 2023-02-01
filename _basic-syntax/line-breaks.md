---
title: Pergantian Baris
syntax-id: line-breaks
description: "Untuk menulis kalimat pada baris baru (pergantian baris dalam satu paragraf)  (`<br>`), akhiri kalimat dengan dua spasi atau lebih, lalu ketik tombol **[Enter]**."
examples:
  - markdown: |
      Kalimat pertama pada baris pertama.  
      Kalimat kedua pada baris kedua.
    html: "<p>TKalimat pertama pada baris pertama.  <br>Kalimat kedua pada baris kedua.</p>"
---

Untuk menulis kalimat pada baris baru (pergantian baris dalam satu paragraf)  (`<br>`), akhiri kalimat dengan dua spasi atau lebih, lalu ketik tombol **[Enter]**.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Markdown</th>
      <th>HTML</th>
      <th>Tampilan</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">Kalimat pertama pada baris pertama.   &nbsp;<br />Kalimat kedua pada baris kedua.
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">&lt;p&gt;Kalimat pertama pada baris pertama.&lt;br&gt;<br/> Kalimat kedua pada baris kedua.&lt;/p&gt;</code>
  </td>
  <td>
    <p>Kalimat pertama pada baris pertama.<br/>   
    Kalimat kedua pada baris kedua.</p>
  </td>
</tr>
</tbody>
</table>
### Praktik Terbaik Pergantian Baris

Anda dapat menggunakan dua spasi atau lebih (biasa disebut sebagai "*trailing whitespace*") untuk berganti baris pada hampir setiap aplikasi Markdown, tetapi hal itu merupakan kontroversial. Sulit untuk melihat beberapa spasi kosong di editor, dan banyak orang secara tidak sengaja atau sengaja menempatkan dua spasi setelah setiap kalimat. Untuk alasan ini, Anda mungkin ingin menggunakan sesuatu selain spasi kosong dan **[Enter]** untuk melakukan pergantian baris. Untungnya, ada opsi lain yang didukung oleh hampir setiap aplikasi Markdown: tag HTML `<br>`.

Untuk kompatibilitas, gunakan beberapa spasi kosong atau tag HTML `<br>` di akhir baris.

Ada dua opsi lain yang tidak direkomendasikan. **CommonMark** dan beberapa bahasa markup ringan lainnya memungkinkan Anda mengetik garis miringkiri (`\`) di akhir baris, tetapi tidak semua aplikasi Markdown mendukung ini, jadi ini bukan pilihan yang bagus dari perspektif kompatibilitas. Dan setidaknya beberapa bahasa markup ringan tidak memerlukan apa pun di akhir baris - cukup tekan **[Enter]** dan hasilnya akan berganti baris.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; Gunakan yang ini</th>
      <th>❌&nbsp; Jangan gunakan seperti ini</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
          Baris pertama diakhiri spasi kosong.  &nbsp;<br>
          Ini baris berikutnya.<br><br>
            Baris pertama diakhiri tag HTML.&lt;br&gt;<br>
      Ini baris berikutnya.<br><br>
    </code>
  </td>
  <td>
    <code class="highlighter-rouge">
    Baris pertama diakhiri garis miring kiri.\<br>
    Ini baris berikutnya.<br><br>
    Baris pertama tanpa diakhiri apa-apa (langsung tekan <b>[Enter]</b>).<br>
Ini baris berikutnya.<br><br>
</code>
      </td>
</tr>
</tbody>
</table>
