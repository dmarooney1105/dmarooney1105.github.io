---
layout: projects
title: ViiMed Website

weight: 4
gallery_image: /images/backgrounds/viimed1.png
tags:
  - web design
  - web development
permalink: /project2/
feature-image: /images/feature/viimed-max.png
description: The ViiMed website went under a lot of iterations. This page shows all the wireframes and Screenshots of different iterations of ViiMed's Website that I designed and developed.
theme: default
insight: ViiMed needed a website that spoke to its primary target audiences, CFOs at health systems (primary audience), patients, doctors and nurses. The website needed to address how the product was THE solution for health care. The original website was extremely text-heavy and did not explain what the product did, or how it helped health systems be more efficient and make doctors and nurses jobs easier.
problem-image:
collaborate:
collaboration:
collab_bg:
ideas:
idea-image: /images/project_stages/points-1.png
images_wireframes:
  - image_path: /images/feature/vii_thumb2.jpg
    title: Wireframe 1
    link: /images/feature/vii-wireframe1.jpg
  - image_path: /images/feature/vii_thumb3.jpg
    title: Wireframe 2
    link: /images/feature/vii-wireframe2.jpg
  - image_path: /images/feature/vii_thumb4.jpg
    title: Wireframe 3
    link: /images/feature/vii-wireframe3.jpg
images_wireframes2:
  - image_path: /images/feature/thumbz1.jpg
    title: ViiMed Home Page Banner
    link: /images/feature/viimed-second-iteration.png
  - image_path: /images/feature/thumbz2.jpg
    title: ViiMed About Us
    link: /images/feature/viimed-second-iteration3.png
  - image_path: /images/feature/thumbz3.jpg
    title: ViiMed About Us
    link: /images/feature/viimed-second-iteration4.png
  - image_path: /images/feature/thumbz5.jpg
    title: ViiMed About Us
    link: /images/feature/viimedwebseconditeration5.png
  - image_path: /images/feature/thumbz4.jpg
    title: Product & Value Propositions Section
    link: /images/feature/viimed2nditeration2.png
  - image_path: /images/feature/thumbz6.jpg
    title: What We Do Section
    link: /images/feature/viimed-second-iteration6.png
---

<div  project-elements="middle" class="container default" >
  <h2 class="trafalgar text-center" >Wireframing & First Build</h2>
  <p class="long-primer text-center" >Upon my first year of working there, a month or so after being hired from the internship position we decided to re-do the website. The Lead UX and UI Designer and I worked together with our CEO to map out the content for the website and then create a design based off the flow of the content.
  <br><br>
  We looked at different websites we liked, and analyzed the story they told. We chose similar design elements that we liked to include in our website. Once I drew out the wireframes, I began building out the site using Yeoman, Grunt, and Bower (scaffolding package for creating websites). </p>
  <div project-thumbnails>

    <ul>
      {% for image in page.images_wireframes %}
      <li class="nodesc">
      <div class="preview" style="background-position: center top; background-image: url('{{ image.image_path }}')">
      </div>
        <h3 class="great-primer">{{ image.title }}</h3>
        <center>
        <br>
        <a href="{{ image.link }}">View Document</a>
        </center>
      </li>
      {% endfor %}
    </ul>
  </div>
</div>
<div>
  <img src="/images/project_stages/vii-display@2x.jpg" class="display-case">
<div>
<div project-elements="middle" class="container default">
  <h2 class="trafalgar text-center" >Solution & Final Product for First Iteration</h2>
  <p class="long-primer text-center">While constructing the website based on the wireframe was a great start, many things changed along the way from the first wireframe. We began to realize that certain elements didn't correlate with our messaging, and thus we changed the design while we built. I sat in a conference room with my CEO to finalize the content and edit sections at the same time. </p>
</div>
<div>
  <img src="/images/project_stages/vii2-display@2x.jpg" class="display-case">
<div>
<div class="container default">
  <h2 class="double-pica text-center" >See it in Action</h2>
  <center>
  {% include video_vimeo.html video="include" vimeo-id="207363803" %}
  </center>
</div>
<div contain-pair class="container alternate2">
  <section class="copy" role="main" >
    <h2 class="trafalgar">Problem #2</h2>
    <h2 class="double-pica">The Next Remodel</h2>
    <p class="long-primer">The previous website I built held up well, but Marketing, Sales, and my CEO could not edit or update any content without having to go through me to update the code.
    <br><br>
    I moved the website over to WordPress to make it easier for anyone to go in and add content. This made it easier for design purposes because I worked with Marketing and our CEO to re-do and re-design the website within 5 days. Each of us worked on a different page - they wrote the content, and I did the artwork as well as designing the layouts.
    <br><br>
    I learned how to override existing code that existed in the WordPress theme we purchased to make elements look the way I wanted them to. I also added custom CSS to tweak the look of the generic theme template.</p>
  </section>
  <aside class="preview" role="complementary" >
    <img src="/images/feature/viimed-max.png" class="mobile-resize">
  </aside>
</div>
<div project-elements="middle" class="container default">
  <h2 class="trafalgar text-center" >Solution & Final Product for Second Iteration</h2>
  <div project-thumbnails>

    <ul>
      {% for image in page.images_wireframes2 %}
      <li class="nodesc">
      <div class="preview" style="background-position: center top; background-image: url('{{ image.image_path }}')">
      </div>
        <h3 class="great-primer">{{ image.title }}</h3>
        <p class="long-primer">{{ image.description }}</p>
        <center>
        <br>
        <a href="{{ image.link }}">View Document</a>
        </center>
      </li>
      {% endfor %}
    </ul>
  </div>
</div>
<div contain-pair class="container alternate">
  <section class="copy" role="main" >
    <h2 class="trafalgar">Problem #3</h2>
    <h2 class="double-pica">Productizing the Platform & Solving Isses with Bundled Payments</h2>
    <p class="long-primer">In 2016, the healthcare industry began to face an issue with CJR (comprehensive joint replacement) and bundled payments. ViiMed''s platform had a care pathway tailored to orthopedic surgery. Instead of labeling it as an individual use-case, we made the move to productize this care plan. The product was called "EXTEND."
    <br><br>
    I created a separate landing page for this product that told the story of how this product is a major solution for bundled payments. It was broken down into stating the problem, introducing our solution (EXTEND), and discussing how it helped solve this problem.
    <br><br></p>
  </section>
  <aside class="preview" role="complementary" >
    <img src="/images/showcase/extend-landing.jpg" class="mobile-resize">
  </aside>
</div>
<div project-elements="middle" class="container alternate2">
  <h2 class="trafalgar text-center" >Solution & Final Product for Third Iteration</h2>
</div>

<img src="/images/project_stages/extend-display@2x.jpg" class="display-case">
