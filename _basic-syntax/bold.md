---
title: Tulisan Tebal
syntax-id: bold
syntax-summary: "**Tulisan tebal**"
description: "Untuk menebalkan teks, tambahkan dua tanda bintang atau garis bawah sebelum dan sesudah teks tersebut. Untuk menebalkan bagian tengah kata untuk penekanan, tambahkan dua tanda bintang tanpa spasi di sekitar huruf."
examples:
  - markdown: "Hati-hati menggunakan **tulisan tebal**."
    html: "Hati-hati menggunakan <strong>tulisan tebal</strong>."
  - markdown: "Hati-hati menggunakan __tulisan tebal__."
    html: "Hati-hati menggunakan <b>tulisan tebal</b>."
  - markdown: "Jangan suka meng-**kafir**-kan orang"
    html: "Jangan suka meng-<strong>kafir</strong>-kan orang"
---

Untuk menebalkan teks, tambahkan dua tanda bintang atau garis bawah sebelum dan sesudah teks tersebut. Untuk menebalkan bagian tengah kata (untuk penekanan), tambahkan dua tanda bintang tanpa spasi di sekitar huruf.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Markdown</th>
      <th>HTML</th>
      <th>Hasil (Tampilan)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code class="highlighter-rouge">Hati-hati menggunakan **tulisan tebal**.</code></td>
      <td><code class="highlighter-rouge">Hati-hati menggunakan &lt;strong&gt;tulisan tebal&lt;/strong&gt;.</code></td>
      <td>Hati-hati menggunakan <strong>tulisan tebal</strong>.</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">Hati-hati menggunakan __tulisan tebal__.</code></td>
      <td><code class="highlighter-rouge">Hati-hati menggunakan &lt;b&gt;tulisan tebal&lt;/b&gt;.</code></td>
      <td>Hati-hati menggunakan <b>tulisan tebal</b>.</td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">Jangan suka meng-**kafir**-kan orang.</code></td> <td><code class="highlighter-rouge">Jangan suka meng-&lt;strong&gt;kafir&lt;/strong&gt;-kan orang.</code></td>
      <td>Jangan suka meng-<strong>kafir</strong>-kan orang.</td>
    </tr>
  </tbody>
</table>

#### Praktik Terbaik Menulis Tebal

Aplikasi Markdown tidak selalu dapat memproses tulisan tebal dengan garis bawah di tengah kata. Untuk kompatibilitas, gunakan tanda bintang dalam menebalkan tulisan di tengah kata (untuk penekanan).

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>✅&nbsp; Gunakan ini</th>
      <th>❌&nbsp; Hindari yang ini</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code class="highlighter-rouge">
          Jangan suka meng-**kafir**-kan orang.
        </code>
      </td>
      <td>
        <code class="highlighter-rouge">
          Jangan suka meng-__kafir__-kan orang.
        </code>
      </td>
    </tr>
  </tbody>
</table>
