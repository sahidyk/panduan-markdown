---
title: Format Teks
syntax-id: emphasis
api: "no"
---

Penekanan suatu teks dapat menggunakan huruf tebal atau huruf miring.

{% include syntax.html type="basic-sub" syntax-id="bold" %}

### Format Teks

Dalam menuliskan teks, Anda terkadang perlu menampilkan huruf, kata, frasa, atau kalimat, bahkan paragraf tertentu secara khusus, misalnya dengan huruf tebal, huruf miring, dan sebagainya. Untuk melakukan hal-hal semacam ini Markdown menggunakan pasangan satu, dua, atau tiga karakter (pasangan artinya mengapit tulisan) tertentu -- disebut **tag**, yang dijelaskan pada tabel berikut ini.

| **Format Teks**         | **Tag**                 | **Contoh**                               |
| :---------------------- | :---------------------- | :--------------------------------------- |
| Huruf Tebal             | `**teks**`              | **Teks dengan huruf tebal**              |
| Huruf Tebal             | `__teks__`              | __Teks dengan huruf tebal__              |
| Huruf Miring            | `*teks*`                | *Teks dengan huruf miring*               |
| Huruf Miring            | `_teks_`                | _Teks dengan huruf miring_               |
| Huruf Tebal dan Miring  | `***teks***`            | ***Teks dengan huruf tebal dan miring*** |
| Huruf Tebal dan Miring  | `**_teks_**`            | **_Teks dengan huruf tebal dan miring_** |
| Huruf Tebal dan Miring  | `___teks___`            | ___Teks dengan huruf tebal dan miring___ |
| Huruf Tebal dan Miring  | `_**teks**_`            | _**Teks dengan huruf tebal dan miring**_ |
| Teks dicoret            | `~~teks~~`              | ~~Teks ini dicoret~~                     |
| Teks diblok             | `==teks==`              | ==Teks ini diblok warna kuning==         |
| Indeks atau subskrip    | `~indeks~`              | Rumus kimia molekul air adalah H~2~O.    |
| Pangkat atau superskrip | `^pangkat^`             | Hasil 2^10^ adalah 1024.                 |
| Teks kode/perintah      | ``` `kode/perintah` ``` | ``` `x=10` ```                           |
| Garis bawah (tag HTML)  | `<u>Digarisbawahi</u>`  | <u>Digarisbawahi</u>                     |
