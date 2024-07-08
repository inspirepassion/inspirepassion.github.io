---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

### 2024

<div class="row">
    <div class="column">
        <img src="/images/paper/paper_3.jpg" alt="Image Alt Text">
    </div>
    <div class="column">
        <p><strong>VQUNet: Vector Quantization U-Net for Defending Adversarial Attacks by Regularizing Unwanted Noise</strong></p>
        <p><strong>Zhixun He</strong>, Mukesh Singhal </p>
        <p><b><em>7th International Conference on Machine Vision and Applications, Mar. 2024</em></b></p>
        <p>You can add multiple paragraphs or other content here.</p>
        <p>You can add multiple paragraphs or other content here.</p>
    </div>
</div>


{% for post in site.publications reversed %}


  {% include archive-single.html %}


{% endfor %}

