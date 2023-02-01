---
title: Menulis Matematika dengan $$\LaTeX$$
syntax-id: mathlatex
description: "This is how to write mathematics in Markdown using $$\LaTeX$$"
examples:
  - markdown: |
      I really like using $$\LaTeX$$ in Markdown.

      I think I'll use it to format all of my documents from now on.
    html: "<p>I really like using $$\LaTeX$$ in Markdown.</p><p>I think I'll use it to format all of my documents from now on.</p>"
---

>Teks matematika dengan $\LaTeX$ dapat ditampilkan dengan mudah di Web Github yang diakses menggunakan Google Chrome atau Microsoft Edge, dengan cara menginstal Ekstensi Chrome [**XHub**](https://github.com/nschloe/xhub). Ekstensi ini juga dapat diinstal ke Microsoft Edge dari situs Ekstensi Google Chrome. Ekstensi XHub menggunakan KaTeX untuk memproses/menampilkan matematika dengan LaTeX. 
>
>Teks matematika di file Markdown yang disimpan di Github ditulis dengan format $$\int_0^{\infty} \sum_{k=1}^n \binom{n}{k} x^k \ dx $$ untuk *inline* dan

````
[
\int_0^{\infty} \sum_{k=1}^n \binom{n}{k} x^k \ dx 
]
````
untuk *display*.

Teks matematika di tengah baris: $$\int_0^{\infty} \sum_{k=1}^n \binom{n}{k} x^k \ dx $$.

Teks matematika pada baris terpisah:

[
\int_0^{\infty} \sum_{k=1}^n \binom{n}{k} x^k \ dx
]

> **Tips di atas ternyata gagal ketika file Markdown diakses sebagai blog di Gihub.**


Di Github, use inline and display math like

````markdown
Display math (see empty lines befor anda after LaTeX):

[ e^{i\pi} + 1 = 0]

and line math $a^2 + b^2 = c^2$ (no empty lines before/after LaTeX)
````
Hasilnya:
Display math:

[e^{i\pi} + 1 = 0]

and line math $a^2 + b^2 = c^2$.

e.g., _Cauchy's Theorem_:

Let $U$ be an open subset of the complex plane $\mathbb{C}$, and suppose the closed
disk $D$ defined as

[
D = \bigl\{z:|z-z_{0}|\leq r\bigr\}
]

is completely contained in $U$. Let $f: U\to\mathbb{C}$ be a holomorphic function,
and let $\gamma$ be the circle, oriented counterclockwise, forming the boundary of
$$D$$. Then for every $a$ in the interior of $D$,

]
f(a) = \frac{1}{2\pi i} \oint _{\gamma}\frac{f(z)}{z-a} dz.
]
