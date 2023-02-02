---
title: Daftar Butir
syntax-id: lists
api: "no"
---

Anda dapat menyusun daftar butir dalam bentuk daftar bernomor atau daftar butir tànpa nomor.

{% include syntax.html type="basic-sub" syntax-id="ordered-lists" %}

{% include syntax.html type="basic-sub" syntax-id="unordered-lists" %}

### Menambahkan Butir-butir dalam Daftar

Untuk menambahkan butir baru ke dalam suatu daftar sambil mempertahankan kelanjutan daftar, mulai butir baru dari barus baru diawali empat spasi/ketukan atau sàtu tombol tab, seperti ditu jukkan pada contoh-contoh di bawah ini.

#### Paragraf

```
*   Ini adalah butir pertama.
*   Ini adalah butir kedua.

    Ini adalah paragraf yang disisipkan setelah butir kedua.

*   Ini adalah butir ke tiga, lanjutan daftar sebelumnya.
```

Hasil penulisan di atas adalah sebagai berikut:

*   Ini adalah butir pertama.
*   Ini adalah butir kedua.

    Ini adalah paragraf yang disisipkan setelah butir kedua.

*   Ini adalah butir ke tiga, lanjutan daftar sebelumnya


#### Blockquotes

```
*   This is the first list item.
*   Here's the second list item.

    > A blockquote would look great below the second list item.

*   And here's the third list item.
```

The rendered output looks like this:

*   This is the first list item.
*   Here's the second list item.

    > A blockquote would look great below the second list item.

*   And here's the third list item.

#### Code Blocks {#code-blocks-1}

[Code blocks](#code-blocks) are normally indented four spaces or one tab.  When they're in a list, indent them eight spaces or two tabs.

```text
1.  Open the file.
2.  Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3.  Update the title to match the name of your website.
```

The rendered output looks like this:

1.  Open the file.
2.  Find the following code block on line 21:

    ```text
    <html>
      <head>
        <title>Test</title>
      </head>
    ```

3.  Update the title to match the name of your website.

#### Images

```
1.  Open the file containing the Linux mascot.
2.  Marvel at its beauty.

    ![Tux, the Linux mascot](/assets/images/tux.png)

3.  Close the file.
```

The rendered output looks like this:

1.  Open the file containing the Linux mascot.
2.  Marvel at its beauty.

    ![Tux, the Linux mascot](/assets/images/tux.png)

3.  Close the file.

#### Lists

You can nest an unordered list in an ordered list, or vice versa.

```
1. First item
2. Second item
3. Third item
    - Indented item
    - Indented item
4. Fourth item
```

The rendered output looks like this:

1. First item
2. Second item
3. Third item
    - Indented item
    - Indented item
4. Fourth item
