---
title: Tabel
syntax-id: tables
syntax-summary: |
    | Judul kolom 1 | Judul kolom 2 |
    | ------------- | ------------- |
    | Isi baris 1 kolom 1 | Isi baris 1 kolom 2 |
    | Isi baris 2 kolom 1 | Isi baris 2 kolom 2 |
---

Untuk menghasilkan tabel, gunakan tiga tanda hubung atau lebih (`---`) untuk membuat judul kolom, dan menggunakan garis tegak (`|`) untuk memisahkan setiap kolom. Anda dapat secara opsional menambahkan garis tegak di salah satu ujung tabel.

```
    | Judul kolom 1 | Judul kolom 2 |
    | ------------- | ------------- |
    | Isi baris 1 kolom 1 | Isi baris 1 kolom 2 |
    | Isi baris 2 kolom 1 | Isi baris 2 kolom 2 |
```

The rendered output looks like this:

| Judul kolom 1       | Judul kolom 2       |
| ------------------- | ------------------- |
| Isi baris 1 kolom 1 | Isi baris 1 kolom 2 |
| Isi baris 2 kolom 1 | Isi baris 2 kolom 2 |

<table class="table table-bordered">
  <thead>
    <tr>
      <th>Syntax</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Header</td>
      <td>Title</td>
    </tr>
    <tr>
      <td>Paragraph</td>
      <td>Text</td>
    </tr>
  </tbody>
</table>

Cell widths can vary, as shown below. The rendered output will look the same.

```
| Syntax | Description |
| --- | ----------- |
| Header | Title |
| Paragraph | Text |
```

<div class="alert alert-success">
  <i class="fas fa-lightbulb"></i> <strong>Tip:</strong> Creating tables with hyphens and pipes can be tedious. To speed up the process, try using the <a href="https://www.tablesgenerator.com/markdown_tables">Markdown Tables Generator</a>. Build a table using the graphical interface, and then copy the generated Markdown-formatted text into your file.
</div>

### Alignment

You can align text in the columns to the left, right, or center by adding a colon (`:`) to the left, right, or on both side of the hyphens within the header row.

```
    |Isi kolom rata kiri | Isi kolom di tengah |Isi kolom rata kanan|
    | :------------- | :-------------: | ----------:|
    | Isi baris 1 kolom 1 | Isi baris 1 kolom 2 | Isi baris 1 kolom 3 |
    | Isi baris 2 kolom 1 | Isi baris 2 kolom 2 | Isi baris 2 kolom 3 |
```

The rendered output looks like this:

|Isi kolom rata kiri | Isi kolom di tengah |Isi kolom rata kanan|
| :------------- | :-------------: | ----------:|
| Isi baris 1 kolom 1 | Isi baris 1 kolom 2 | Isi baris 1 kolom 3 |
| Isi baris 2 kolom 1 | Isi baris 2 kolom 2 | Isi baris 2 kolom 3 |

<table class="table table-bordered">
  <thead>
    <tr>
      <th style="text-align: left">Syntax</th>
      <th style="text-align: center">Description</th>
      <th style="text-align: right">Test Text</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left">Header</td>
      <td style="text-align: center">Title</td>
      <td style="text-align: right">Here’s this</td>
    </tr>
    <tr>
      <td style="text-align: left">Paragraph</td>
      <td style="text-align: center">Text</td>
      <td style="text-align: right">And more</td>
    </tr>
  </tbody>
</table>

### Formatting Text in Tables

You can format the text within tables. For example, you can add [links](/basic-syntax/#links), [code](/basic-syntax/#code-1) (words or phrases in backticks (`` ` ``) only, not [code blocks](/basic-syntax/#code-blocks)), and [emphasis](/basic-syntax/#emphasis).

You can't add headings, blockquotes, lists, horizontal rules, images, or HTML tags.

### Escaping Pipe Characters in Tables

You can display a pipe (`|`) character in a table by using its HTML character code (`&#124;`).
