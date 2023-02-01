---
title: Judul dan Subjudul
syntax-id: headings
syntax-summary: |
  # H1
  ## H2
  ### H3
description: "Untuk menuliskan judul atau subjudul digunakan karakter `#` di depan teks judul atau subjudul. Banyaknya tanda `#` menandai tingkat subjudul. Markdown dapat membuat subjudul sampai tingkat 6, namun beberapa aplikasi Markdown hanya mampu membuat subjudul sampai tingkat 4. Tingkat subjudul menentukan besar/ukuran huruf."
examples:
  - markdown: "# Judul (Subjudul Tingkat 1)"
    html: "<h1>Judul (Subjudul Tingkat 1)</h1>"
  - markdown: "## Subjudul Tingkat 2"
    html: "<h2>JSubjudul Tingkat 2</h2>"
  - markdown: "### Subjudul Tingkat 3"
    html: "<h3>Subjudul Tingkat 3</h3>"
  - markdown: "#### Subjudul Tingkat 4"
    html: "<h4>Subjudul Tingkat 4</h4>"
  - markdown: "##### Subjudul Tingkat 5"
    html: "<h5>Subjudul Tingkat 5</h5>"
  - markdown: "###### Subjudul Tingkat 6"
    html: "<h6>Subjudul Tingkat 6</h6>"
additional-examples:
  - name: "Sintaks Alternatif untuk H1"
    description: "untuk menuliskan subjudul tingkat 1 dapat menggunakan beberapa karakter `=` di bawah tulisan judul (subjudul tingkat 1)."
    markdown: |
      Judul (Subjudul Tingkat 1)
      ===============
    html: "<h1>Judul (Subjudul Tingkat 1)</h1>"
  - name: "Sintaks Alternatif untuk H2"
    description: "Untuk subjudul tingkat 2 dapat menggunakan karakter -- di bawah tulisan subjudul tingkat 2."
    markdown: |
      Subjudul Tingkat 2
      ---------------
    html: "<h2>Subjudul Tingkat 2</h2>"
---

Untuk menuliskan judul atau subjudul digunakan karakter `#` di depan teks judul atau subjudul. Banyaknya tanda `#` menandai tingkat subjudul. Markdown dapat membuat subjudul sampai tingkat 6, namun beberapa aplikasi Markdown hanya mampu membuat subjudul sampai tingkat 4. Tingkat subjudul menentukan besar/ukuran huruf.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Sintaks Markdown</th>
      <th>Sintaks HTML</th>
      <th>Tampilan Teks Hasilnya</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code class="highlighter-rouge"># Judul (Subjudul Tingkat 1)</code></td>
      <td><code class="highlighter-rouge">&lt;h1&gt;Judul (Subjudul Tingkat 1)&lt;/h1&gt;</code></td>
      <td><h1 class="no-anchor" data-toc-skip="">Judul (Subjudul Tingkat 1)</h1></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">## Subjudul Tingkat 2</code></td>
      <td><code class="highlighter-rouge">&lt;h2&gt;Subjudul Tingkat 2&lt;/h2&gt;</code></td>
      <td><h2 class="no-anchor" data-toc-skip="">Subjudul Tingkat 2</h2></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">### Subjudul Tingkat 3</code></td>
      <td><code class="highlighter-rouge">&lt;h3&gt;Subjudul Tingkat 3&lt;/h3&gt;</code></td>
      <td><h3 class="no-anchor" data-toc-skip="">Subjudul Tingkat 3</h3></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">#### Subjudul Tingkat 4</code></td>
      <td><code class="highlighter-rouge">&lt;h4&gt;Subjudul Tingkat 4&lt;/h4&gt;</code></td>
      <td><h4 class="no-anchor">Subjudul Tingkat 4</h4></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">##### Subjudul Tingkat 5</code></td>
      <td><code class="highlighter-rouge">&lt;h5&gt;Subjudul Tingkat 5&lt;/h5&gt;</code></td>
      <td><h5 class="no-anchor">Subjudul Tingkat 5</h5></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">###### Subjudul Tingkat 6</code></td>
      <td><code class="highlighter-rouge">&lt;h6&gt;Subjudul Tingkat 6&lt;/h6&gt;</code></td>
      <td><h6 class="no-anchor">Subjudul Tingkat 6</h6></td>
    </tr>
  </tbody>
</table>

==Harap diperhatikan, perlu selalu diingat, sebaiknya tanda  `#` harus dipisahkan dengan teks subjudul. Jika tanda `#` tidak dipisah mungkin Anda tidak akan mendapatkan apa yang Anda harapkan!==

Tuliskan:

✅ `# Teks Judul `

dan jangan menuliskan dengan cara:

❌ `#Teks Judul.`

Selain menggunakan karakter `#` untuk menuliskan subjudul tingkat 1 dapat menggunakan beberapa karakter `=` di bawah tulisan subjudul, sedangkan untuk subjudul tingkat 2 dapat menggunakan karakter beberapa  `-`.

<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
      <th>Sintaks Markdown</th>
      <th>Tampilan Teks Hasilnya</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code class="highlighter-rouge"> Judul (Subjudul Tingkat 1)<br> ===========</code></td>
      <td><h1 class="no-anchor" data-toc-skip="">Judul (Subjudul Tingkat 1)</h1></td>
    </tr>
    <tr>
      <td><code class="highlighter-rouge">Subjudul Tingkat 2<br>---------</code></td>
      <td><h2 class="no-anchor" data-toc-skip="">Subjudul Tingkat 2</h2></td>
    </tr>
  </tbody>
</table>
