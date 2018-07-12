---
layout: projects
title: COPD Care Plan
type: project
weight: 3
permalink: /project1/
gallery_image: /images/backgrounds/copd1.png
feature-image: /images/feature/chscopd-gif.gif
tags:
  - product design
  - gamification
  - UI design
description: ViiMed was asked by COPD Foundation to create an interactive educational program for patients diagnosed with COPD. Our ultimate goal was to engage, educate and change patient behavior.
theme: default
insight: COPD Foundation handed us their patient handout, The Big Fat Reference Guide, a 300 + page book filled with everything a patient would ever need to know. ViiMed's only healthcare experience thus far was in Orthopaedics but we knew our Chronic Disease template had to be more engaging for a patient population that was never going to be cured.
problem-image: /images/bfrg.jpg
collaborate: include
collaboration: The majority of the company (CEO, developers, solution architects, marketing, product, designers etc.) met in a conference room together and broke off into teams to tackle different ideas and concepts for creating a personalized care pathway.<br /><br /> To make the content tailored to the patient we decided to divide the program into three separate care plans (mild, moderate and severe) and the patient was assigned a pathway based off their assessment score.
collab_bg: /images/project_stages/workflow.jpg
ideas: The Front-end Software Engineer and I worked together with the nurse that worked at the COPD Foundation to gain insight on users' behavior (both the nurse or 'coach' and the patient). <br /><br />We compared the product to many existing educational platforms and discovered that in order to make the program more engaging and interactive, we could introduce the idea of gamification. This would be the first time we introduced any sort of gamification ideal into the software.
idea-image: /images/project_stages/points-1.png
usbaility: I created usability surveys for both the patient and nurse team to receive input on our original experience that we laid out.<br /><br /> The feedback guided us to change the pathway names from “mild, moderate, or severe,”  to “Pathways 1, 2, & 3” (patients that were placed in severe became discouraged from the beginning).
images_wireframes:
  - image_path: /assets/ui-document.jpg
    title: UI Document for Patient Dashboard
    description: I created a UI document with existing widgets the platform already had (only the design was tweaked) in order to have a back-up plan for the minimum viable product.
    link: /assets/dashboard-doc.pdf
  - image_path: /images/project_stages/wrieframe-thumbnail.png
    title: The Dashboard with Gamification
    description: These collection of wireframes show the gamification ideas like integrating our platform with the COPD Foundation’s social media site, trophy rooms where where patients could use their points to “purchase” helpful items (bluetooth inhalers, pulse oximeters etc. that integrated with our software).
    link: /assets/dashboards-wireframes3.pdf
---

  <div class="container-large container collaboration invert-shadow" style="background-image:linear-gradient(
      rgba(0, 0, 0, 0.45),
      rgba(0, 0, 0, 0.45)
    ), url('{{ page.collab_bg }}');">
    <div class="invert-shadow">
      <h2 class="trafalgar">Collaboration</h2>
      <p class="long-primer">{{ page.collaboration }}</p>
    </div>
  </div>

<div class="container-large" >
  <div contain-pair="{{ page.theme }}">
    <section class="copy" role="main">
      <h2 class="trafalgar">Ideas</h2>
      <p class="long-primer">{{ page.ideas }}</p>
    </section>
    <aside class="preview" role="complementary">
      <img src="{{ page.idea-image }}" class="mobile-resize">
    </aside>
  </div>
</div>

<div class="container default">
  <h2 class="trafalgar text-center" >Solutions</h2>
  <h2 class="double-pica text-center" style="margin-top:20px; margin-bottom: 20px;" >Wireframes, Prototypes, and Final Products</h2>
</div>

<div id="dashboard" project-elements="show-stopper" class="container invert-shadow"  style="background-image:linear-gradient(
    rgba(0, 0, 0, 0.5),
    rgba(0, 0, 0, 0.5),
    rgba(0, 0, 0, 0.75)
  ), url('/images/backgrounds/copd-macbook.jpg');">
  <h2 class="trafalgar" >The Dashboard</h2>

</div>
<div  project-elements="left" class="container default" >
  <h2 class="double-pica" >The Original Dashboard</h2>
  <p class="long-primer" >Most of ViiMed's products up until this point, revolved around orthopedics, and therefore the patient did not need to have a "dashboard." They just logged in and went straight to their activity list. <br><br> The Solution Architects used the page builder on the software to create a patient dashboard. The page builder on ViiMed's platform, serves for simple projects such as libraries and such. </p>

    <img class="single" src="/images/copd-dashboard-before@2x.jpg" >

</div>
<div  project-elements="middle" class="container default" >
  <h2 class="double-pica text-center" >Looks boring, right?</h2>
  <p class="long-primer text-center" >With the thought of gamification in mind, I decided to begin sketching out wireframes that not only improved the overall look and feel of the dashboard, but also incorporated some gamification elements to it such as: unlocked achievement badges, a trophy room where patients could use their points to purchase a bluetooth inhaler that connected to the platform (or other goodies), etc. </p>
  <div project-thumbnails>

    <ul>
      {% for image in page.images_wireframes %}
      <li >
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
<div  project-elements="middle" class="container default" >
  <h2 class="double-pica text-center" >The Final Dashboard Product</h2>
  <p class="long-primer text-center" >Using the page builder and existing widgets, I had to override the existing CSS code on the backend of the software (using inspect-element to replace the styles of existing classes attached to the widgets) to make the widgets have the "square design" and intended hover and mobile-view effects. </p>
</div>
<div before-after>
  <div before >
    <h3 class="great-primer">Mobile: Before</h3>
    <img src="/images/og-dash-mobile@2x.png">
  </div>
  <div after >
    <h3 class="great-primer text-center">Mobile: After</h3>
    <img src="/images/copd-dashboard-mobile1@2x.png">
    <img src="/images/copd-dashboard-mobile2@2x.png">
  </div>
</div>
<div  project-elements="middle" class="container default" >
  <h3 class="great-primer text-center" >Desktop View</h3>
  <center>
  <img src="/images/copd-desktop.png" class="single">
  </center>
</div>

<div contain-pair class="container alternate" id="gamification">
  <section class="copy" role="main" >
    <h2 class="trafalgar">Gamification</h2>
    <p class="long-primer">The Lead UX and UI Designer and I worked together with the nurse that worked at the COPD Foundation to gain insight on users behavior (both the coach and the patient). We did a lot of secondary research as well and read <a class="defaulter hvr-underline-from-center" href="https://www.amazon.com/Gamification-Design-Implementing-Mechanics-Mobile/dp/1449397670/ref=sr_1_1?s=books&ie=UTF8&qid=1496231774&sr=1-1&keywords=9781449397678" style="font-weight: 400;"> Gamification by Design</a>  by Gabe Zichermann and Christopher Cunningham because we came up with the idea to gamify the experience for the patients in order to encourage them to participate in educating themselves on their disease to manage their health and elongate their life.</p>
  </section>
  <aside class="preview" role="complementary" >
    <img src="/images/gamification-book.jpg">
  </aside>
</div>
<div contain-pair class="container alternate2">
  <section class="copy" role="main" >
    <h2 class="double-pica">Theme Development</h2>
    <h3 class="great-primer">From "Lung Island" to Real-World Environments</h3>
    <p class="long-primer">The COPD Foundation's "Big Fat Reference Guide" book takes on the theme of a safari and exploration on "Lung Island". Any "call outs" or "did you know?" blurbs included a graphical cartoon explorer dressed in safari gear. I worked closely with ViiMeds front-end software engineer took their theme of "Lung Island" and expanded upon it by creating different environmental realms that one would travel through on a game board and applied it to the Care Plan Courses. Each aspect of the program (from individual chapters in a course to library resources) was assigned an "environment."</p>
  </section>
  <aside class="preview" role="complementary" >
    <img src="/images/lung-island.jpg" class="mobile-resize">
  </aside>
</div>
<div project-elements="infographic" class="default" style=" background-color: #E0E0E0;">
  <h2 class="double-pica text-center">A Journey Through the Environments</h2>
  <div info-line>
    <img src="/images/project_stages/tiles.png" class="first">
    <div info-side="left-side">
      <div info="left arrow" >
        <h3 class="great-primer">Home</h3>
        <p class="long-primer">Home base, and where you can always return. Elements such as the dashboard, the patient journal, or messaging your coach would take on this theme.</p>
      </div>
      <div info="left arrow" >
        <h3 class="great-primer">Beach</h3>
        <p class="long-primer">The beach is where one goes to relax, play games, take a break from daily routines. This theme would essentially be applied to the trophy room, social media integrated with the platform etc.</p>
      </div>
      <div info="left arrow" >
        <h3 class="great-primer">Mountain</h3>
        <p class="long-primer">The mountain is an "uphill climb" and represents a challenge. This theme was applied to a "practice" activity that was sent to the patient during each individual course. An example of a "practice" activity included side-by-side recordings of patients completing pursed-lips-breathing exercises or other copd-related exercises that help them gain control of their disease. </p>
      </div>
    </div>
    <div info-side="right-side">
      <div info="right arrow"  >
        <h3 class="great-primer">Farm</h3>
        <p class="long-primer">The farm, or "the simple life," represents simplicity and the basics. This theme was applied to all introduction chapters of each course. </p>
      </div>
      <div info="right arrow" >
        <h3 class="great-primer">Forest</h3>
        <p class="long-primer">In the forest, one goes exploring deeper into nature, thus representing "deeper information." The middle chapters of a course (patients are exposed to deeper knowledge on the topic) would take on this theme.</p>
      </div>
      <div info="right arrow" >
        <h3 class="great-primer">Sky</h3>
        <p class="long-primer">One can see "everything" and has a broader view of an area from the sky. The sky represents a review of all information learned in a course or exit surveys testing the patient's knowledge on the topic.</p>
      </div>
      <div info="right arrow" class="default">
        <h3 class="great-primer">Cave or River</h3>
        <p class="long-primer">The idea of the cave or the river (we went along with the river) represents a detour or side quest. Elective courses were assigned this theme as an optional "side activity."</p>
      </div>
    </div>
  </div>
  <div info-mobile>
    <img src="/images/project_stages/tiles.png" class="second">
    <div>
      <div info="mobile" id="mobile1">
        <h3 class="great-primer">Home <i class="fa fa-caret-down "></i><i class="fa fa-caret-up "></i></h3>
        <p class="long-primer" id="show1">Home base, and where you can always return. Elements such as the dashboard, the patient journal, or messaging your coach would take on this theme.</p>
      </div>
      <div info="mobile" id="mobile2">
        <h3 class="great-primer">Beach <i class="fa fa-caret-down "></i><i class="fa fa-caret-up "></i></h3>
        <p class="long-primer" id="show2">The beach is where one goes to relax, play games, take a break from daily routines. This theme would essentially be applied to the trophy room, social media integrated with the platform etc.</p>
      </div>
      <div info="mobile" id="mobile3">
        <h3 class="great-primer">Mountain <i class="fa fa-caret-down "></i><i class="fa fa-caret-up "></i></h3>
        <p class="long-primer" id="show3">The mountain is an "uphill climb" and represents a challenge. This theme was applied to a "practice" activity that was sent to the patient during each individual course. An example of a "practice" activity included side-by-side recordings of patients completing pursed-lips-breathing exercises or other copd-related exercises that help them gain control of their disease. </p>
      </div>
      <div info="mobile" id="mobile4">
        <h3 class="great-primer">Farm <i class="fa fa-caret-down "></i><i class="fa fa-caret-up "></i></h3>
        <p class="long-primer" id="show4">The farm, or "the simple life," represents simplicity and the basics. This theme was applied to all introduction chapters of each course. </p>
      </div>
      <div info="mobile" id="mobile5">
        <h3 class="great-primer">Forest <i class="fa fa-caret-down "></i><i class="fa fa-caret-up "></i></h3>
        <p class="long-primer" id="show5">In the forest, one goes exploring deeper into nature, thus representing "deeper information." The middle chapters of a course (patients are exposed to deeper knowledge on the topic) would take on this theme.</p>
      </div>
      <div info="mobile" id="mobile6">
        <h3 class="great-primer">Sky <i class="fa fa-caret-down "></i><i class="fa fa-caret-up "></i></h3>
        <p class="long-primer" id="show6">One can see "everything" and has a broader view of an area from the sky. The sky represents a review of all information learned in a course or exit surveys testing the patient's knowledge on the topic.</p>
      </div>
      <div info="mobile" id="mobile7">
        <h3 class="great-primer">Cave or River <i class="fa fa-caret-down "></i><i class="fa fa-caret-up "></i></h3>
        <p class="long-primer" id="show7">The idea of the cave or the river (we went along with the river) represents a detour or side quest. Elective courses were assigned this theme as an optional "side activity."</p>
      </div>
    </div>
  </div>
</div>

<div project-elements="middle" class="container default">
  <h2 class="double-pica text-center">Theme & Gamification in Action</h2>
  <p class="long-primer text-center">I designed and created elements that went along with each theme. Once we began building out the care plan, we realized that for the first launch, we did not have a need for some of the "environments," so we eliminated "town" and "beach."</p>
  <div class="tiles" id="menu">
    <ul>
      <a href="#" onclick="return showDiv('1')"><li class="farm hvr-grow"><img src="/images/project_stages/farm.png">
      <h3 class="great-primer">Farm</h3></li></a>

      <a href="#content-divs" onclick="return showDiv('2')"><li class="forest hvr-grow"><img src="/images/project_stages/forest.png">
      <h3 class="great-primer">Forest</h3></li></a>
      <a href="#content-divs" onclick="return showDiv('3')"><li class="mountain hvr-grow"><img src="/images/project_stages/mountain.png">
      <h3 class="great-primer">Mountain</h3></li></a>
      <a href="#content-divs" onclick="return showDiv('4')"><li class="sky hvr-grow"><img src="/images/project_stages/sky.png">
      <h3 class="great-primer">Sky</h3></li></a>
      <a href="#content-divs" onclick="return showDiv('5')"><li class="river hvr-grow"><img src="/images/project_stages/river.png">
      <h3 class="great-primer">River</h3></li></a>
      <a href="#content-divs" onclick="return showDiv('6')"><li class="home hvr-grow"><img src="/images/project_stages/home.png">
      <h3 class="great-primer">Home</h3></li></a>
    </ul>
  </div>
</div>
<section id="content-divs">
  <section id="container1" class="farm">
    <h2 class="double-pica text-center" style="margin: 20px;">Farm</h2>
    <div class="colorbar" style="background-color: #DC9414;">
      <h4 class="pica text-center">#DC9414</h4>
    </div>

    <img src="/images/project_stages/copd-display@2x.jpg" class="display-case">

    <div class="container elements">
      <div class="display-card" style="background-color: #DC9414;">
        <div class="element">
          <img src="/images/project_stages/burlapseedsack.png">
        </div>

        <div class="info default invert">
          <h3 class="great-primer text-center">Bag of Seeds</h3>
          <p class="long-primer text-center">Created in Adobe Photoshop</p>
        </div>
      </div>
      <div class="display-card" style="background-color: #DC9414;">
        <div class="element">
          <img src="/images/project_stages/shovel.png">
        </div>

        <div class="info default invert">
          <h3 class="great-primer text-center">Shovel</h3>
          <p class="long-primer text-center">Created in Adobe Photoshop</p>
        </div>
      </div>
      <div class="display-card-other" style="background-color: #DC9414;">
        <div class="element">
          <img src="/images/project_stages/chatbubfarm.png">
        </div>

        <div class="info default invert">
          <h3 class="great-primer text-center">Chat Bubble</h3>
          <p class="long-primer text-center">CSS & HTML</p>
        </div>
      </div>
      <div class="display-card-other" style="background-color: #DC9414;">
        <div class="element">
          <img src="/images/project_stages/farm-download.png">
        </div>

        <div class="info default invert">
          <h3 class="great-primer text-center">Download Box</h3>
          <p class="long-primer text-center">CSS & HTML</p>
        </div>
      </div>
    </div>
  </section>
   <section id="container2" class="forest">
     <h2 class="double-pica text-center" style="margin: 20px;">Forest</h2>
     <div class="colorbar" style="background-color: #4F6E54;">
       <h4 class="pica text-center">#4F6E54</h4>
     </div>

     <img src="/images/project_stages/forest-display@2x.jpg" class="display-case">

     <div class="container elements">
       <div class="display-card" style="background-color: #4F6E54;">
         <div class="element">
           <img src="/images/project_stages/tent-with-logo.png">
         </div>

         <div class="info default invert">
           <h3 class="great-primer text-center">Tent</h3>
           <p class="long-primer text-center">Created in Adobe Photoshop</p>
         </div>
       </div>
       <div class="display-card" style="background-color: #4F6E54;">
         <div class="element">
           <img src="/images/project_stages/axe-with-stump.png">
         </div>

         <div class="info default invert">
           <h3 class="great-primer text-center">Axe & Stump</h3>
           <p class="long-primer text-center">Created in Adobe Photoshop</p>
         </div>
       </div>
       <div class="display-card-other" style="background-color: #4F6E54;">
         <div class="element">
           <img src="/images/project_stages/chatbubforest.png">
         </div>

         <div class="info default invert">
           <h3 class="great-primer text-center">Chat Bubble</h3>
           <p class="long-primer text-center">CSS & HTML</p>
         </div>
       </div>
       <div class="display-card-other" style="background-color: #4F6E54;">
         <div class="element">
           <img src="/images/project_stages/forest-download.png">
         </div>

         <div class="info default invert">
           <h3 class="great-primer text-center">Download Box</h3>
           <p class="long-primer text-center">CSS & HTML</p>
         </div>
       </div>
     </div>
   </section>
   <section id="container3" class="mountain">
   <h2 class="double-pica text-center" style="margin: 20px;">Mountain</h2>
   <div class="colorbar" style="background-color: #FA5C3E;">
     <h4 class="pica text-center">#FA5C3E</h4>
   </div>

   <img src="/images/project_stages/mountain-display@2x.jpg" class="display-case">

   <div class="container elements">
     <div class="display-card" style="background-color: #FA5C3E;">
       <div class="element">
         <img src="/images/project_stages/ice-axe.png">
       </div>

       <div class="info default invert">
         <h3 class="great-primer text-center">Ice Axe</h3>
         <p class="long-primer text-center">Created in Adobe Photoshop</p>
       </div>
     </div>
     <div class="display-card" style="background-color: #FA5C3E;">
       <div class="element">
         <img src="/images/project_stages/crampon.png">
       </div>

       <div class="info default invert">
         <h3 class="great-primer text-center">Crampon</h3>
         <p class="long-primer text-center">Created in Adobe Photoshop</p>
       </div>
     </div>
     <div class="display-card-other" style="background-color: #FA5C3E;">
       <div class="element">
         <img src="/images/project_stages/chatbubmountain.png">
       </div>

       <div class="info default invert">
         <h3 class="great-primer text-center">Chat Bubble</h3>
         <p class="long-primer text-center">CSS & HTML</p>
       </div>
     </div>
     <div class="display-card-other" style="background-color: #FA5C3E;">
       <div class="element">
         <img src="/images/project_stages/mountain-download.png">
       </div>

       <div class="info default invert">
         <h3 class="great-primer text-center">Download Box</h3>
         <p class="long-primer text-center">CSS & HTML</p>
       </div>
     </div>
    </div>
   </section>
   <section id="container4" class="sky">
   <h2 class="double-pica text-center" style="margin: 20px;">Sky</h2>
   <div class="colorbar" style="background-color: #00BAD7;">
     <h4 class="pica text-center">#00BAD7</h4>
   </div>

   <img src="/images/project_stages/sky-display@2x.jpg" class="display-case">

   <div class="container elements">
     <div class="display-card" style="background-color: #00BAD7;">
       <div class="element">
         <img src="/images/project_stages/cloud-final.png">
       </div>

       <div class="info default invert">
         <h3 class="great-primer text-center">Cloud</h3>
         <p class="long-primer text-center">Created in Adobe Photoshop</p>
       </div>
     </div>
     <div class="display-card" style="background-color: #00BAD7;">
       <div class="element">
         <img src="/images/project_stages/hangglider.png">
       </div>

       <div class="info default invert">
         <h3 class="great-primer text-center">Hang Glider</h3>
         <p class="long-primer text-center">Created in Adobe Photoshop</p>
       </div>
     </div>
     <div class="display-card-other" style="background-color: #00BAD7;">
       <div class="element">
         <img src="/images/project_stages/chatbubsky.png">
       </div>

       <div class="info default invert">
         <h3 class="great-primer text-center">Chat Bubble</h3>
         <p class="long-primer text-center">CSS & HTML</p>
       </div>
     </div>
   </div>
 </section>
 <section id="container5" class="river">
     <h2 class="double-pica text-center" style="margin: 20px;">River</h2>
     <div class="colorbar" style="background-color: #5B859A;">
       <h4 class="pica text-center">#5B859A</h4>
     </div>

     <img src="/images/project_stages/river-display@2x.jpg" class="display-case">

     <div class="container elements">
       <div class="display-card" style="background-color: #5B859A;">
         <div class="element">
           <img src="/images/project_stages/canoe4.png">
         </div>

         <div class="info default invert">
           <h3 class="great-primer text-center">Canoe</h3>
           <p class="long-primer text-center">Created in Adobe Photoshop</p>
         </div>
       </div>
       <div class="display-card" style="background-color: #5B859A;">
         <div class="element">
           <img src="/images/project_stages/lure.png">
         </div>

         <div class="info default invert">
           <h3 class="great-primer text-center">Fishing Lure</h3>
           <p class="long-primer text-center">Created in Adobe Photoshop</p>
         </div>
       </div>
       <div class="display-card-other" style="background-color: #5B859A;">
         <div class="element">
           <img src="/images/project_stages/chatbubriver.png">
         </div>

         <div class="info default invert">
           <h3 class="great-primer text-center">Chat Bubble</h3>
           <p class="long-primer text-center">CSS & HTML</p>
         </div>
       </div>
       <div class="display-card-other" style="background-color: #5B859A;">
         <div class="element">
           <img src="/images/project_stages/river-download.png">
         </div>

         <div class="info default invert">
           <h3 class="great-primer text-center">Download Box</h3>
           <p class="long-primer text-center">CSS & HTML</p>
         </div>
       </div>
     </div>
   </section>
   <section id="container6" class="home">
     <h2 class="double-pica text-center" style="margin: 20px;">Home</h2>
     <div class="colorbar" style="background-color: #4c5262;">
       <h4 class="pica text-center">#4c5262</h4>
     </div>

     <img src="/images/project_stages/home-display@2x.jpg" class="display-case">
   </section>
</section>


<div class="container" >
  <div contain-pair="{{ page.theme }}">
    <section class="copy" role="main">
      <h2 class="trafalgar">COPD Care Plan: Impact and Feedback</h2>
      <p class="long-primer">I created a user survey for patients to fill out while they were completing their program. We asked them all sorts of questions regarding the design, navigation, workflow, and gamification. Most said they really enjoyed the theme and gamification aspect, but that they did not see it as a motivating factor for them. We came to the conclusion that perhaps there was no correlation to motivation because patients could not do anything with their points (e.g., purchase items in a trophy room).
      <br><br>
      The COPD care plan was up and running. The theme elements and ideas that the Lead UX and UI designer and I developed became a large turning point for how we approached all other care plans. The elements we build were so often reused for other care plans, that we eventually built widgets out of them for solution architects to use instead of copying and pasting HTML code.</p>
    </section>
    <aside class="preview" role="complementary">
      <img src="{{ page.feature-image }}">
    </aside>
  </div>
</div>

<script>
function showDiv(idInfo) {
  var sel = document.getElementById('content-divs').getElementsByTagName('section');
  for (var i=0; i<sel.length; i++) { sel[i].style.display = 'none'; }
  document.getElementById('container'+idInfo).style.display = 'block';
  return false;
}


window.onload = function() { showDiv('1'); }
</script>
