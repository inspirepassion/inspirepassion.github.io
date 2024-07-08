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

[//]: # (### 2024)

<div class="row">
    <div class="column">
        <img src="/images/paper/dissertation.png" alt="Image Alt Text">
    </div>
    <div class="column">
        <style>
        .column p {
            margin-bottom: 5px; /* Adjust the margin bottom as per your preference */
        }
        </style>
        <p><strong>Ph.D. Dissertation: Defense Frameworks Against Adversarial Attacks on Deep Learning Models</strong></p>
        <p style="font-size: 15px;"><strong>Zhixun He</strong></p>
        <p style="font-size: 12px;"><b><em>EECS, University of California, Merced</em></b></p>
        <a href="/files/papers/dissertation.pdf" style="font-size: 12px;">pdf</a>&nbsp;&nbsp;
    </div>
</div>

<div class="row">
    <div class="column">
        <img src="/images/paper/paper_3.jpg" alt="Image Alt Text">
    </div>
    <div class="column">
        <style>
        .column p {
            margin-bottom: -5px; /* Adjust the margin bottom as per your preference */
        }
        </style>
        <p><strong>VQUNet: Vector Quantization U-Net for Defending Adversarial Attacks by Regularizing Unwanted Noise</strong></p>
        <p style="font-size: 15px;"><strong>Zhixun He</strong>, Mukesh Singhal </p>
        <p style="font-size: 12px;"><b><em>7th International Conference on Machine Vision and Applications, Mar. 2024</em></b></p>
        <a href="/files/papers/paper3.pdf" style="font-size: 12px;">pdf</a>&nbsp;&nbsp;
        <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=d6Y4oBEAAAAJ&citation_for_view=d6Y4oBEAAAAJ:2osOgNQ5qMEC" style="font-size: 12px;">Google Scholar</a>&nbsp;&nbsp; 
        <a href="https://www.google.com" style="font-size: 12px;">Github (coming soon)</a>&nbsp;&nbsp;
    </div>
</div>

[//]: # (### 2022)

<div class="row">
    <div class="column">
        <img src="/images/paper/paper_2.png" alt="Image Alt Text">
    </div>
    <div class="column">
        <style>
        .column p {
            margin-bottom: -5px; /* Adjust the margin bottom as per your preference */
        }
        </style>
        <p><strong>Defense-CycleGAN: A Defense Mechanism Against Adversarial Attacks Using CycleGAN to
Reconstruct Clean Images</strong></p>
        <p style="font-size: 15px;"><strong>Zhixun He</strong>, Mukesh Singhal </p>
        <p style="font-size: 12px;"><b><em>3rd International Conference on Pattern Recognition and Machine Learning, Jul. 2022</em></b></p>
        <a href="/files/papers/paper2.pdf" style="font-size: 12px;">pdf</a>&nbsp;&nbsp;
        <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=d6Y4oBEAAAAJ&citation_for_view=d6Y4oBEAAAAJ:9yKSN-GCB0IC" style="font-size: 12px;">Google Scholar</a>&nbsp;&nbsp; 
        <a href="https://www.google.com" style="font-size: 12px;">Github (coming soon)</a>&nbsp;&nbsp;
    </div>
</div>

<div class="row">
    <div class="column">
        <img src="/images/paper/paper_1.png" alt="Image Alt Text">
    </div>
    <div class="column">
        <style>
        .column p {
            margin-bottom: -5px; /* Adjust the margin bottom as per your preference */
        }
        </style>
        <p><strong>Adversarial Defense Through High-Frequency Loss Variational Autoencoder Decoder and
Bayesian Update With Collective Voting</strong></p>
        <p style="font-size: 15px;"><strong>Zhixun He</strong>, Mukesh Singhal </p>
        <p style="font-size: 12px;"><b><em>17th International Conference on Machine Vision Applications, Jun. 2021</em></b></p>
        <a href="/files/papers/paper1.pdf" style="font-size: 12px;">pdf</a>&nbsp;&nbsp;
        <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=d6Y4oBEAAAAJ&citation_for_view=d6Y4oBEAAAAJ:d1gkVwhDpl0C" style="font-size: 12px;">Google Scholar</a>&nbsp;&nbsp; 
        <a href="https://www.google.com" style="font-size: 12px;">Github (coming soon)</a>&nbsp;&nbsp;
    </div>
</div>

<div class="row">
    <div class="column">
        <img src="/images/paper/paper_0.png" alt="Image Alt Text">
    </div>
    <div class="column">
        <style>
        .column p {
            margin-bottom: -5px; /* Adjust the margin bottom as per your preference */
        }
        </style>
        <p><strong>Active Learning of Reward Dynamics from Hierarchical Queries</strong></p>
        <p style="font-size: 15px;">Chandrayee Basu, Erdem Bıyık, <strong>Zhixun He</strong>, Mukesh Singhal, Dorsa Sadigh</p>
        <p style="font-size: 12px;"><b><em>Proceedings of the IEEE International Conference on Intelligent Robots and Systems (IROS), Nov. 2019</em></b></p>
        <a href="/files/papers/paper0.pdf" style="font-size: 12px;">pdf</a>&nbsp;&nbsp;
        <a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=d6Y4oBEAAAAJ&citation_for_view=d6Y4oBEAAAAJ:u-x6o8ySG0sC" style="font-size: 12px;">Google Scholar</a>&nbsp;&nbsp; 
    </div>
</div>


{% for post in site.publications reversed %}


  {% include archive-single.html %}


{% endfor %}

