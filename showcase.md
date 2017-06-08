---
layout: default
title: Showcase
bg_color: 3869f9
bigscreen_text: Showcase
permalink: /showcase/
leader: An assortment of a few marketing materials, artwork, landing pages, and presentations I've created over the years.
bigscreen-text-color: ffffff
bg_image: showcase.jpg
bigscreen_text_color: ffffff
---
<section class="bigscreen mediumpadding" style="padding-top: 135px; background-image: linear-gradient(
    rgba(56, 89, 249, 0.65),
    rgba(56, 186, 249, 0.65)
  ), url('/images/backgrounds/{{ page.bg_image }}');">
  <center>
  <div class="invert">
    <h1 style="text-shadow: none;" class="canon">{{ page.bigscreen_text }}</h1>
    <p style="text-align: center; margin-top: 20px; max-width: 500px;" class="long-primer invert">An assortment of a few marketing materials, artwork, landing pages, and presentations I've created over the years.</p>
  </div>
  </center>
</section>

<center>
  <div class="gallery-container">
    <h2>Designs & Artwork</h2>
      {% assign sorted_photos = site.portfolio_gallery | sort: "weight" %}
      <div class="photo-gallery">
        {% for image in sorted_photos %}
          <div class="cell">
          <a href="{{ image.link }}" target="_blank">
            <img src="{{ image.image_path }}" alt="{{ image.title}}" class="responsive-image">
            <div class="overlay">
              <div class="overlaytext">{{ image.title }}
              <p>{{ image.type }}</p>
              <p style="font-size:14px;">{{ image.tools }}</p></div>
            </div>
            </a>
          </div>
        {% endfor %}
      </div>
  </div>
