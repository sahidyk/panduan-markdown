---
title: Daftar Butir
syntax-id: lists
api: "no"
---

Anda dapat menyusun daftar butir dalam bentuk daftar bernomor atau daftar butir tanpa nomor.

{% include syntax.html type="basic-sub" syntax-id="ordered-lists" %}

{% include syntax.html type="basic-sub" syntax-id="unordered-lists" %}

### Menambahkan Butir-butir dalam Daftar

Untuk menambahkan butir baru ke dalam suatu daftar sambil mempertahankan kelanjutan daftar, mulai butir baru dari barus baru diawali empat spasi/ketukan atau satu tombol tab, seperti ditunjukkan pada contoh-contoh di bawah ini.

#### Paragraf di dalam daftar butir

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

*   Ini adalah butir ke tiga, lanjutan daftar sebelumnya.


#### Kutipan di dalam daftar butir

```
*   Ini adalah butir pertama.
*   Ini adalah butir kedua.

    > Ini adalah kutipan yang disisipkan setelah butir kedua.

*   Ini adalah butir ke tiga, lanjutan daftar sebelumnya.
```

Hasil penulisan di atas adalah sebagai berikut:

*   Ini adalah butir pertama.
*   Ini adalah butir kedua.

    > Ini adalah kutipan yang disisipkan setelah butir kedua.

*   Ini adalah butir ke tiga, lanjutan daftar sebelumnya.

#### Blok kode/program di dalam daftar butir {#code-blocks-1}

[Blok kode/program](#code-blocks) biasanya diawali empat spasi kosong atau satu tombol tab. Untuk blok kode di dalam daftar butir, tambahkan delapan spasi atau dua tombol tab sebelumnya.

```text
1.  Buka file yang akan diperbarui.
2.  Cari blok kode berikut ini:

        <html>
          <head>
            <title>Judul Program</title>
          </head>

3.  Perbarui judul programnya sesuai dengan kegunaannya.
```

Hasilnya akan terlihat seperti di bawah ini:

1.  Buka file yang akan diperbarui.
2.  Cari blok kode berikut ini:

       ``` <html>
          <head>
            <title>Judul Program</title>
          </head>
       ```
3.  Perbarui judul programnya sesuai dengan kegunaannya.

#### Gambar di dalam daftar butir

```
1.  Open the file containing the Linux mascot.
2.  Marvel at its beauty.

    ![Tux, the Linux mascot](/assets/images/tux.png)

3.  Close the file.
```

Hasilnya akan terlihat seperti di bawah ini:

1.  Open the file containing the Linux mascot.
2.  Marvel at its beauty.

    ![Tux, the Linux mascot](/assets/images/tux.png)

3.  Close the file.

#### Daftar di dalam daftar

Anda dapat membuat daftar bernomor di dalam daftar tanpa nomor, dan sebaliknya.

```
1. Butir pertama
2. Butir kedua
3. Butir ketiga
    - Anak butir ketiga pertama
    - Anak butir ketiga yang kedua
4. Butir keempat
```

Hasilnya akan terlihat seperti di bawah ini:

1. Butir pertama
2. Butir kedua
3. Butir ketiga
    - Anak butir ketiga pertama
    - Anak butir ketiga yang kedua
4. Butir keempat
