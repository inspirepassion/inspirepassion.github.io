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
        <p>**VQUNet: Vector Quantization U-Net for Defending Adversarial Attacks by Regularizing Unwanted Noise**</p>
        <p>*Zhixun He*, Mukesh Singhal </p>
        <p>You can add multiple paragraphs or other content here.</p>
        <p>You can add multiple paragraphs or other content here.</p>
        <p>You can add multiple paragraphs or other content here.</p>
    </div>
</div>


{% for post in site.publications reversed %}


  {% include archive-single.html %}


{% endfor %}

