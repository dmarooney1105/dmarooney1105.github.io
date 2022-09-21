---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---
<div class="container header-contain invert primary-bg">
  <div class="headline">
    <h1 class="canon">Daniella Marooney</h1>
    <h2 class="double-pica">Designing simple solutions for people's complex problems.
    </h2>
    <!-- <h2 class="double-pica">Product designer who creates simple solutions for user's complex problems. I also code and aspire to be a front-end developer.</h2> -->
  </div>
  <div class="product-container">
    <img src="/images/stratus_main.png">
  </div>
</div>
<section id="projects" class="project-gallery default" style="padding-top: 50px;">
  <h2 class="trafalgar text-center">Projects</h2>
  <ul>
  {% assign sorted_projects = site.pages | sort: 'weight' %}
    {% for page in sorted_projects %}
      {% if page.type == "project" %}
        <li class="default"><img src="{{ page.gallery_image }}">
          <div class="what">
            <h2 class="double-pica">{{ page.title }}</h2>
          </div>
          <div class="tags">
          {% for tag in page.tags %}
            <div class="tag">
              <div data-icon="{% case tag %} {% when 'gamification' %} } {% when 'UI design' %} K {% when 'web design' %} # {% when 'web development' %} 3 {% when 'product design' %} % {% endcase %}" class="icon"></div>
              <h5 class="minion">{{ tag | capitalize }}</h5>
            </div>
          {% endfor %}
          </div>
          <center>
          <a href="{{ page.url }}">View Project</a>
          </center>
        </li>
      {% endif %}
    {% endfor %}

  </ul>
</section>

