---
layout: tools
title: Alat Bantu
description: Aplikasi dan komponen yang mendukung peningkatan fitur Markdown
last_modified_at: 2021-01-05
---

<div class="row">
  <div class="col-sm-3" style="padding-top:20px">
    <div class="card" style="width: 16rem; height: 15rem;">
      <div class="card-body">
        <h4 class="card-title no-anchor" style="margin-top: -20px;"><span class="emoji" style="font-size:30px">👋</span>&nbsp;&nbsp;&nbsp;Salam!</h4>
        <p class="card-text">Ini adalah daftar kumpulan alat bantu Markdown yang komprehensif. Butuh waktu lama untuk melengkapi dan memperbarui daftar ini! <a href="https://github.com/mattcone/markdown-guide/wiki/Markdown-tool-directory">Baca bagaimana cara Anda dapat berkontribusi.</a></p>
      </div>
    </div>
  </div>


  {% for tool in site.tools %}
  <div class="col-sm-3" style="padding-top:20px">
    <div class="card" style="width: 16rem; height: 15rem;">
      <div class="card-body">
        <h4 class="card-title no-anchor" style="margin-top: -20px; font-size: 20px;"><a href="{{ tool.url }}"><img src="/assets/images/tool-icons/{{ tool.icon }}" alt="{{ tool.title }} logo" style="width:50px; margin-top:-5px"></a>&nbsp;&nbsp;{{ tool.title }}</h4>
        <p class="card-text">{{ tool.description }}</p>
        <a href="{{ tool.url }}" class="btn btn-outline-secondary btn-sm">Learn more</a>
      </div>
    </div>
  </div>
  {% endfor %}
</div>
