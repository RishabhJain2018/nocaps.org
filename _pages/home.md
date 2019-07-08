---
layout: default
permalink: "/"
---

<link rel="stylesheet" type="text/css" href="/static/css/home.css">

<div class="container">
  <div class="row">
    <!-- Teaser figure -->
    <div class="col-md-6 col-sm-6 col-xs-6 col-12">
      <img alt="{{ site.title }}" title="{{ site.title }}" id="teaser-figure" src="/static/img/paper/teaser.jpg">
      <p id="teaser-caption">
        The <span class="nocaps-word">nocaps</span> benchmark for novel object captioning (at scale).
      </p>
    </div>
    <!-- Abstract -->
    <div class="col-md-6 col-sm-6 col-xs-6 col-12">
      <p>
      Image captioning models have achieved impressive results on datasets containing limited visual concepts and large amounts of paired image-caption training data. However, if these models are to ever function in the wild, a much larger variety of visual concepts must be learned, ideally from less supervision.
      To encourage the development of image captioning models that can learn visual concepts from alternative data sources, such as object detection datasets, we present the first large-scale benchmark for this task. Dubbed <span class="nocaps-word">nocaps</span>, for novel object captioning at scale, our benchmark consists of 166,100 human-generated captions describing 15,100 images from the Open Images validation and test sets. The associated training data consists of COCO image-caption pairs, plus Open Images image-level labels and object bounding boxes. Since Open Images contains many more classes than COCO, nearly 400 object classes seen in test images have no or very few associated training captions (hence, <span class="nocaps-word">nocaps</span>). We extend existing novel object captioning models to establish strong baselines for this benchmark and provide analysis to guide future work on this task.
      </p>
    </div>
  </div>
</div>

<hr>

<h2 class="anchor" id="paper">Paper</h2>

<div class="paper-container row">
  <!-- nocaps: novel object captioning at scale -->
  <div class="paper-title col-md-12 col-sm-12 col-xs-12">
    nocaps: novel object captioning at scale
  </div>
  <!-- negative margin to account for superscripted asterisk -->
  <div class="paper-authors col-md-12 col-sm-12 col-xs-12" style="margin-top: -4px;">
    Harsh Agrawal<sup>*</sup>, Karan Desai<sup>*</sup>, Yufei Wang, Xinlei Chen, Rishabh Jain, Mark Johnson, Dhruv Batra, Devi Parikh, Stefan Lee, Peter Anderson
  </div>
  <!-- arxiv and website link -->
  <!-- <div class="paper-links col-md-12 col-sm-12 col-xs-12">
    
      <a class="paper-link button-div" href="//arxiv.org/abs/1812.08658" target="_blank">
        arxiv/1812.08658
      </a>
    
    <a class="paper-link button-div" href="/static/bibliography/nocaps_bibtex.txt" target="_blank">
      bibtex
    </a>
    <a class="paper-link button-div" href="/static/bibliography/nocaps_natbib.txt" target="_blank">
      natbib
    </a>
  </div> -->
  <div class="paper-banner col-md-12 col-sm-12 col-xs-12">
    <a href="//nocaps.org/paper.pdf" target="_blank"> <img src="/static/img/paper/nocaps_banner.jpg" alt="nocaps paper" title="nocaps paper"/> </a>
  </div>
</div>

<h2 class="anchor" id="people">People</h2>

<div class="people-container">
{% include people.html %}
</div>

<hr>

<div class="row">
  <!-- Subscribe -->
  <div class="col-md-6 col-sm-6 col-xs-6 col-12">
    <h3>Subscribe</h3>
    <form action="https://tinyletter.com/nocaps" method="post" target="popupwindow" onsubmit="window.open('https://tinyletter.com/nocaps', 'popupwindow', 'scrollbars=yes,width=800,height=600');return true">
      <label for="tlemail">Subscribe for <span class="nocaps-word">nocaps</span> release updates</label>
      <div class="row">
        <div class="col-md-8 col-sm-8 col-xs-8 col-8" style="margin: 10px 0 10px 0">
          <input type="text" name="email" id="tlemail" placeholder="Email address" style="width: 100%"/>
        </div>
        <div class="col-md-4 col-sm-4 col-xs-4 col-4" style="margin: 10px 0 10px 0">
          <button type="submit">Subscribe!</button>
        </div>
      </div>
    </form>
  </div>

  <!-- Contact -->
  <div class="col-md-6 col-sm-6 col-xs-6 col-12">
    <h3>Contact</h3>
    <span><b>Email:</b> contact@nocaps.org</span>
  </div>
</div>

<br/>
