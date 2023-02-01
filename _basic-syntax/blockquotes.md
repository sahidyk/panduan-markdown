---
title: Teks Kutipan
syntax-id: blockquotes
syntax-summary: "> Teks kutipan"
description: "Untuk menuliskan teks kutipan, awali teks kutipan dengan tanda `>` dan pisahkan dengan spasi."
examples:
  - markdown: "> *Demi Kitab (Al-Qur'an) yang menerangkan. Sesungguhnya Kami menjadikan Al Quran dalam bahasa Arab supaya kamu memahami(nya).*  (Q.S. Az-Zukhruf: 2-3)"
    html: "<blockquote><p><i>Demi Kitab (Al-Qur'an) yang menerangkan. Sesungguhnya Kami menjadikan Al Quran dalam bahasa Arab supaya kamu memahami(nya)</i>. (Q.S. Az-Zukhruf: 2-3)</p></blockquote>"
additional-examples:
  - name: "Kutipan Terdiri Atas Beberapa Paragraf"
    description: "Untuk menuliskan kutipan yang terdiri atas beberapa paragraf, setiap paragraf diawali dengan tanda `>` dan antar paragraf dipisahkan dengan baris kosong yang diawali dengan tanda `>`."
    markdown: |
      > *Wahai orang-orang yang beriman! Janganlah suatu kaum mengolok-olok kaum yang lain (karena) boleh jadi mereka (yang diperolok-olokkan) lebih baik dari mereka (yang mengolok-olok) dan jangan pula perempuan-perempuan (mengolok-olokkan) perempuan lain (karena) boleh jadi perempuan (yang diperolok-olokkan) lebih baik dari perempuan (yang mengolok-olok). Janganlah kamu saling mencela satu sama lain dan janganlah saling memanggil dengan gelar-gelar yang buruk. Seburuk-buruk panggilan adalah (panggilan) yang buruk (fasik) setelah beriman. Dan barangsiapa tidak bertobat, maka mereka itulah orang-orang yang zalim.*  (Q.S 49:11)
      >
      > *Wahai orang-orang yang beriman! Jauhilah banyak dari prasangka, sesungguhnya sebagian prasangka itu dosa dan janganlah kamu mencari-cari kesalahan orang lain dan janganlah ada di antara kamu yang menggunjing sebagian yang lain. Apakah ada di antara kamu yang suka memakan daging saudaranya yang sudah mati? Tentu kamu merasa jijik. Dan bertakwalah kepada Allah, sesungguhnya Allah Maha Penerima tobat, Maha Penyayang.* (Q.S 49:12)
    html: "<blockquote><p><i>Wahai orang-orang yang beriman! Janganlah suatu kaum mengolok-olok kaum yang lain (karena) boleh jadi mereka (yang diperolok-olokkan) lebih baik dari mereka (yang mengolok-olok) dan jangan pula perempuan-perempuan (mengolok-olokkan) perempuan lain (karena) boleh jadi perempuan (yang diperolok-olokkan) lebih baik dari perempuan (yang mengolok-olok). Janganlah kamu saling mencela satu sama lain dan janganlah saling memanggil dengan gelar-gelar yang buruk. Seburuk-buruk panggilan adalah (panggilan) yang buruk (fasik) setelah beriman. Dan barangsiapa tidak bertobat, maka mereka itulah orang-orang yang zalim.  (Q.S 49:11)</i></p><p><i>Wahai orang-orang yang beriman! Jauhilah banyak dari prasangka, sesungguhnya sebagian prasangka itu dosa dan janganlah kamu mencari-cari kesalahan orang lain dan janganlah ada di antara kamu yang menggunjing sebagian yang lain. Apakah ada di antara kamu yang suka memakan daging saudaranya yang sudah mati? Tentu kamu merasa jijik. Dan bertakwalah kepada Allah, sesungguhnya Allah Maha Penerima tobat, Maha Penyayang. (Q.S 49:12)</i></p></blockquote>"
  - name: "Kutipan di dalam Kutipan"
    description: "Untuk menuliskan kutipan di dalam kutipan digunakan tanda `>>` di dalam kutipan kedua."
    markdown: |
      > Telah menceritakan kepada kami [Muhammad bin Al Mutsanna], telah menceritakan kepada kami [Yahya], dari [Isma'il] berkata, telah menceritakan kepada saya [Qais], dari [Ibnu Mas'ud radliallahu 'anhu] berkata, Aku mendengar Nabi Shallallahu'alaihiwasallam bersabda: 
      >> *Tidak boleh iri (dengki) kecuali kepada dua hal. (Yaitu kepada) seorang yang Allah berikan kepadanya harta lalu dia menguasainya dan membelanjakannya di jalan yang haq (benar) dan seorang yang Allah berikan hikmah (ilmu) lalu dia melaksanakannya dan mengajarkannya (kepada orang lain)*. 
    html: "<blockquote><p>Telah menceritakan kepada kami [Muhammad bin Al Mutsanna], telah menceritakan kepada kami [Yahya], dari [Isma'il] berkata, telah menceritakan kepada saya [Qais], dari [Ibnu Mas'ud radliallahu 'anhu] berkata, Aku mendengar Nabi Shallallahu'alaihiwasallam bersabda: </p><blockquote><p><i>Tidak boleh iri (dengki) kecuali kepada dua hal. (Yaitu kepada) seorang yang Allah berikan kepadanya harta lalu dia menguasainya dan membelanjakannya di jalan yang haq (benar) dan seorang yang Allah berikan hikmah (ilmu) lalu dia melaksanakannya dan mengajarkannya (kepada orang lain).</i></p></blockquote></blockquote>"
  - name: "Kutipan dengan Komponen Dokumen Lain"
    description: "Kutipan dapat memuat elemen-elemen dokumen Markdown lain, seperti butir-butir, teks dengan tulisan khusus, bahkan ekspresi matematika. Tidak semua elemen dokumen dapat dituliskan di dalam kutipan. Anda harus mencoba untuk mengetahuinya."
    markdown: |
      > ### Ciri-ciri orang beriman yang beruntung
      > Menurut Al-Qur'an, ciri-ciri orang beriman yang beruntung adalah:
      > 1. orang yang **khusyuk dalam salatnya**,
      > 2. orang yang **menjauhkan diri dari (perbuatan dan perkataan) yang tidak berguna**,
      > 3. orang yang **menunaikan zakat**,
      > 4. orang yang **memelihara kemaluannya**,kecuali terhadap istri-istri mereka atau hamba sahaya yang mereka miliki; maka sesungguhnya mereka tidak tercela,
      > 5. orang yang **memelihara amanat-amanat dan janjinya**,
      > 6. orang yang **memelihara salatnya**.
      >
      >  *Mereka itulah orang-orang yang akan mewarisi surga Firdaus dan mereka kekal di dalamnya.* (Q.S. 23: 1 - 11)
    html: "<blockquote><h3>Ciri-ciri orang beriman yang beruntung</h3>Menurut Al-Qur'an, ciri-ciri orang beriman yang beruntung adalah:<ol><li>orang yang <b>khusyuk dalam salatnya</b></li>,<li>orang yang <b>menjauhkan diri dari (perbuatan dan perkataan) yang tidak berguna</b>,</li><li><orang yang <b>menunaikan zakat</b>,/li><li>orang yang <b>memelihara kemaluannya</b>,kecuali terhadap istri-istri mereka atau hamba sahaya yang mereka miliki; maka sesungguhnya mereka tidak tercela</li>,<li>orang yang <b>memelihara amanat-amanat dan janjinya</b></li>,<li>orang yang <b>memelihara salatnya</b></li>.</ol><p><i>Mereka itulah orang-orang yang akan mewarisi surga Firdaus dan mereka kekal di dalamnya</i>. (Q.S. 23: 1 - 11)</p></blockquote>"
---

Untuk menuliskan suatu kutipan (langsung), gunakan tanda `>`  di depan teks kutipan. Teks kutipan dapat memuat teks dengan semua format. 

```
> *Demi Kitab (Al-Qur'an) yang menerangkan. Sesungguhnya Kami menjadikan Al Quran dalam bahasa Arab supaya kamu memahami(nya).* (Q.S. Az-Zukhruf: 2-3)
```

Hasilnya akan tampak seperti:

> *Demi Kitab (Al-Qur'an) yang menerangkan. Sesungguhnya Kami menjadikan Al Quran dalam bahasa Arab supaya kamu memahami(nya).*  (Q.S. Az-Zukhruf: 2-3)

### Kutipan Terdiri Atas Beberapa Paragraf

Untuk menuliskan kutipan yang terdiri atas beberapa paragraf, setiap paragraf diawali dengan tanda `>` dan antar paragraf dipisahkan dengan baris kosong yang diawali dengan tanda `>` .

```markdown
Di antara sendi-sendi pergaulan sesama manusia menurut Al-Qur'an adalah sebagai berikut:
> (Q.S 49:11):
>> *Wahai orang-orang yang beriman! Janganlah suatu kaum mengolok-olok kaum yang lain (karena) boleh jadi mereka (yang diperolok-olokkan) lebih baik dari mereka (yang mengolok-olok) dan jangan pula perempuan-perempuan (mengolok-olokkan) perempuan lain (karena) boleh jadi perempuan (yang diperolok-olokkan) lebih baik dari perempuan (yang mengolok-olok). Janganlah kamu saling mencela satu sama lain dan janganlah saling memanggil dengan gelar-gelar yang buruk. Seburuk-buruk panggilan adalah (panggilan) yang buruk (fasik) setelah beriman. Dan barangsiapa tidak bertobat, maka mereka itulah orang-orang yang zalim.*  
>
>(Q.S 49:12):
>> *Wahai orang-orang yang beriman! Jauhilah banyak dari prasangka, sesungguhnya sebagian prasangka itu dosa dan janganlah kamu mencari-cari kesalahan orang lain dan janganlah ada di antara kamu yang menggunjing sebagian yang lain. Apakah ada di antara kamu yang suka memakan daging saudaranya yang sudah mati? Tentu kamu merasa jijik. Dan bertakwalah kepada Allah, sesungguhnya Allah Maha Penerima tobat, Maha Penyayang.* 
```

Tampilan hasilnya:

Di antara sendi-sendi pergaulan sesama manusia menurut Al-Qur'an adalah sebagai berikut:
> (Q.S 49:11):
> > *Wahai orang-orang yang beriman! Janganlah suatu kaum mengolok-olok kaum yang lain (karena) boleh jadi mereka (yang diperolok-olokkan) lebih baik dari mereka (yang mengolok-olok) dan jangan pula perempuan-perempuan (mengolok-olokkan) perempuan lain (karena) boleh jadi perempuan (yang diperolok-olokkan) lebih baik dari perempuan (yang mengolok-olok). Janganlah kamu saling mencela satu sama lain dan janganlah saling memanggil dengan gelar-gelar yang buruk. Seburuk-buruk panggilan adalah (panggilan) yang buruk (fasik) setelah beriman. Dan barangsiapa tidak bertobat, maka mereka itulah orang-orang yang zalim.*  
>
> (Q.S 49:12):
>
> > *Wahai orang-orang yang beriman! Jauhilah banyak dari prasangka, sesungguhnya sebagian prasangka itu dosa dan janganlah kamu mencari-cari kesalahan orang lain dan janganlah ada di antara kamu yang menggunjing sebagian yang lain. Apakah ada di antara kamu yang suka memakan daging saudaranya yang sudah mati? Tentu kamu merasa jijik. Dan bertakwalah kepada Allah, sesungguhnya Allah Maha Penerima tobat, Maha Penyayang.* 

### Kutipan di dalam Kutipan

Untuk menuliskan kutipan di dalam kutipan digunakan tanda `>>` di dalam kutipan kedua.

```markdown
> Telah menceritakan kepada kami [Muhammad bin Al Mutsanna], telah menceritakan kepada kami [Yahya], dari [Isma'il] berkata, telah menceritakan kepada saya [Qais], dari [Ibnu Mas'ud radliallahu 'anhu] berkata, Aku mendengar Nabi Shallallahu'alaihiwasallam bersabda: 
>>*Tidak boleh iri (dengki) kecuali kepada dua hal. (Yaitu kepada) seorang yang Allah berikan kepadanya harta lalu dia menguasainya dan membelanjakannya di jalan yang haq (benar) dan seorang yang Allah berikan hikmah (ilmu) lalu dia melaksanakannya dan mengajarkannya (kepada orang lain)*. 
>
> ([Shahih Bukhari hadis nomor 1320, Lihat: Fathul Bari Ibnu Hajar](https://carihadis.com/Shahih_Bukhari/=ilmu))
```

Tampilan hasil penulisan di atas adalah:

> Telah menceritakan kepada kami [Muhammad bin Al Mutsanna], telah menceritakan kepada kami [Yahya], dari [Isma'il] berkata, telah menceritakan kepada saya [Qais], dari [Ibnu Mas'ud radliallahu 'anhu] berkata, Aku mendengar Nabi Shallallahu'alaihiwasallam bersabda: 
>
> >*Tidak boleh iri (dengki) kecuali kepada dua hal. (Yaitu kepada) seorang yang Allah berikan kepadanya harta lalu dia menguasainya dan membelanjakannya di jalan yang haq (benar) dan seorang yang Allah berikan hikmah (ilmu) lalu dia melaksanakannya dan mengajarkannya (kepada orang lain)*. 
> 
> ([Shahih Bukhari hadis nomor 1320, Lihat: Fathul Bari Ibnu Hajar](https://carihadis.com/Shahih_Bukhari/=ilmu))

### Kutipan dengan Komponen Dokumen Lain

Kutipan dapat memuat elemen-elemen dokumen Markdown lain, seperti butir-butir, teks dengan tulisan khusus, bahkan ekspresi matematika. Tidak semua elemen dokumen dapat dituliskan di dalam kutipan. Anda harus mencoba untuk mengetahuinya.

```markdown
> ### Ciri-ciri orang beriman yang beruntung
> Menurut Al-Qur'an, ciri-ciri orang beriman yang beruntung adalah:
> 1. orang yang **khusyuk dalam salatnya**,
> 2. orang yang **menjauhkan diri dari (perbuatan dan perkataan) yang tidak berguna**,
> 3. orang yang **menunaikan zakat**,
> 4. orang yang **memelihara kemaluannya**,kecuali terhadap istri-istri mereka atau hamba sahaya yang mereka miliki; maka sesungguhnya mereka tidak tercela,
> 5. orang yang **memelihara amanat-amanat dan janjinya**,
> 6. orang yang **memelihara salatnya**.
>
>  *Mereka itulah orang-orang yang akan mewarisi surga Firdaus dan mereka kekal di dalamnya.* (Q.S. 23: 1 - 11)
```

Tampilan hasilnya adalah:

> ### Ciri-ciri orang beriman yang beruntung
>
> Menurut Al-Qur'an, ciri-ciri orang beriman yang beruntung adalah:
> 1. orang yang **khusyuk dalam salatnya**,
> 2. orang yang **menjauhkan diri dari (perbuatan dan perkataan) yang tidak berguna**,
> 3. orang yang **menunaikan zakat**,
> 4. orang yang **memelihara kemaluannya**,kecuali terhadap istri-istri mereka atau hamba sahaya yang mereka miliki; maka sesungguhnya mereka tidak tercela,
> 5. orang yang **memelihara amanat-amanat dan janjinya**,
> 6. orang yang **memelihara salatnya**.
>
>  *Mereka itulah orang-orang yang akan mewarisi surga Firdaus dan mereka kekal di dalamnya.* (Q.S. 23: 1 - 11)

