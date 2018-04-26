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
    {% for page in site.pages %}
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
<div class="experience">
  <h2 class="trafalgar text-center" style="padding: 70px 20px 50px 20px;">Professional Experience</h2>
  <div class="timeliner-container">
    <div class="timeline">
    <div class="entry">
      <div class="title">
        <h3>Dec. 2017 - Present</h3>
        <p>Stratus Intelligence</p>
        <h5 class="minion">Washington, D.C.</h5>
      </div>
      <div class="body">
        <h4 class="pica">Lead Product Designer</h4>
        <p>Part Time</p>
        <p>Stratus is a fintech start up focusing on making financial planning universally accessible to everyday people.</p>
        <ul>
          <li>Developing the vision and execution of entire Stratus platform.</li>
          <li>Conducting user testing to improve functionality and user experience of platform.</li>
          <li>Developing and coding company landing page.</li>
        </ul>
      </div>
    </div>
    <div class="entry">
      <div class="title">
        <h3>Oct. 2017 - Present</h3>
        <p>One World Identity</p>
        <h5 class="minion">Washington, D.C.</h5>
      </div>
      <div class="body">
        <h4 class="pica">Product & Instructional Designer</h4>
        <p>One World Identity is an identity industry community and professional services company.</p>
        <ul>
          <li>Designing and building course interface for Trust & Safety by incorporating gamification and innovative solutions to engage users with content.</li>
          <li>Conducting user testing to improve user experience for courses.</li>
          <li>Managing and designing company and conference landing pages.</li>
        </ul>
      </div>
    </div>
      <div class="entry">
        <div class="title">
          <h3>Feb. 2017 - Present</h3>
          <h5 class="minion">Washington. D.C.</h5>
        </div>
        <div class="body">
          <h4 class="pica">Freelance & Contract Work</h4>
          <p>Providing product design, web design and development as well as graphic design consultation for ViiMed, The World Health Organization and other entrepreneurial clients.</p>
        </div>
      </div>
      <div class="entry">
        <div class="title">
          <h3>June 2014 - Feb. 2017</h3>
          <p>ViiMed</p>
          <h5 class="minion">Washington, D.C.</h5>
        </div>
        <div class="body">
          <h4 class="pica">Product Designer & Creative Director</h4>
          <p>ViiMed is a telehealth software company delivering personalized care
          plans to patients while providers monitor and communicate
          with them via the platform.</p>
          <ul>
            <li>Designed and build responsive landing pages on ViiMed
            platform for both patients and doctors</li>
            <li>Developed high fidelity mockups and prototypes based on
            client feedback to improve patient and provider user
            experience</li>
            <li>Collaborated with front-end Senior Software Engineer to
            create gamified experiences that drive patient participation</li>
            <li>Worked cross-functionally to improve product and develop
            intuitive solutions</li>
            <li>Conducted all UX/UI design and usability audits for client
            workflows</li>
            <li>Created and distribute all of ViiMed’s marketing collateral
            and graphics</li>
            <li>Lead product demos at trade shows and business
            development meetings</li>
          </ul>
        </div>
      </div>
      <div class="entry">
        <div class="title">
          <h3>May 2014 - June 2014</h3>
          <p>ViiMed</p>
          <h5 class="minion">Washington, D.C.</h5>
        </div>
        <div class="body">
          <h4 class="pica">UI /UX & Graphic Design Intern</h4>
          <p>Switched career direction to pursue my passion for creative
          design through internship with ViiMed. Was offered a full
          time position within 3 weeks.</p>
        </div>
      </div>
      <div class="entry">
        <div class="title">
          <h3>Feb. 2012 - May 2014</h3>
          <p>Integrated Training Solutions (ITS)</p>
          <h5 class="minion">Falls Church, VA</h5>
        </div>
        <div class="body">
          <h4 class="pica">Marketing Coordinator</h4>
          <p>Government contract managing NLSC Program, a group of
          volunteers who provide language resources to U.S. federal
              agencies.</p>
          <ul>
            <li>Produced and designed graphics for marketing and outreach campaigns
            for more than 4,800 volunteer members and staff</li>
            <li>Conducted market research through questionnaires for
            strategic market expansion</li>
            <li>Planned and hosted monthly national recruiting and member events budgeted for $2,000+ with 50-60 attendees</li>
          </ul>
        </div>
      </div>

    </div>
  </div>
  <div class="timeliner-container">
    <div class="education">
        <h2 class="double-pica">Education</h2>
        <div class="body">
          <h4 class="pica">University of Maryland</h4>
        </div>
        <div class="title">
          <h5 class="minion">College Park, MD</h5>
          <p>Bachelor of Arts in Communication Studies</p>
          <p>2007 - 2011</p>
        </div>
      </div>
  </div>
</div>
<div class="container invert grapefruit-bg">
  <h2 class="trafalgar text-center">Skills & Languages</h2>
  <div class="skill-sets">
    <div id="skills" class="skills-container">
      <div class="skills">
        {% include skill.html progress="90" type="Spanish" dripicon="volume-full" %}
        {% include skill.html progress="75" type="HTML" dripicon="code" %}
        {% include skill.html progress="65" type="CSS" dripicon="code" %}
        {% include skill.html progress="30" type="JavaScript & jQuery"  dripicon="code" %}
        {% include skill.html progress="85" type="Adobe Illustrator"  dripicon="brush" %}
        {% include skill.html progress="85" type="Adobe Photoshop" dripicon="brush" %}
        {% include skill.html progress="60" type="Adobe Experience Design" dripicon="brush" %}
        {% include skill.html progress="50" type="Adobe InDesign" dripicon="brush" %}
        {% include skill.html progress="85" type="OmniGraffle" dripicon="browser" %}
        {% include skill.html progress="85" type="Sketch" dripicon="browser" %}
        {% include skill.html progress="60" type="InVision" dripicon="browser" %}
        {% include skill.html progress="85" type="PowerPoint" dripicon="monitor" %}
      </div>

    </div>
  </div>
</div>
