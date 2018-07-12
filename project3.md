---
layout: projects
title: CHF Care Plan & Nurse Admin Dashboard
type: project
weight: 2
gallery_image: /images/backgrounds/chf1.png
tags:
  - product design
  - UI design
permalink: /project3/
feature-image: /images/feature/chf-mac.png
description: I worked directly with a cardiologist to come up with a Congestive Heart Failure (CHF) program to build with ViiMed’s platform. This product involved the re-design of the existing nurse coordinator dashboard.
theme: default
insight: Hospital systems have a big issue with Congestive Heart Failure patients in that they get readmitted back to the hospital post-discharge. Not only is this very expensive for the hospital, but it also reduces patient satisfaction scores and HCAHP scores. <br /><br />The Clinical Director and Fellowship Program Director for Cardiovascular Medicine at the University of Louisville approached ViiMed with the idea of creating a remote care plan for CHF patients after they leave the hospital. The idea behind the program was to minimize hospital readmissions during the critical 30 day period after the patient is discharged from the hospital.  
problem-image: /images/project_stages/chf-problem.jpg
collaborate:
collaboration:
collab_bg:
ideas:
idea-image: /images/project_stages/points-1.png
images_wireframes:
  - image_path: /images/project_stages/console2.png
    title: Too Much Text
    description: The black paragraph you see on the upper left of the patients' progress bar is a string of data collected from the enrollment form (the nurse fills out a form on the software to enroll the patient into the program prior to when they leave the hospital).
    link: /images/project_stages/console2.png
  - image_path: /images/project_stages/console1.png
    title: Two Interfaces Become One
    description: The nurse admin's to-do list is embedded within their dashboard where they manage their patients (two interfaces becoming one so they don't have to jump back and forth). It is also an overall view of each patient's severity rating. Clicking on an individual dot on the scatterplot allows the user to "drill down" into that patient's medical profile.
    link: /images/project_stages/console1.png
  - image_path: /images/project_stages/console-prototype.png
    title: The Winner
    description: It shows a high level view of the number of patients in each severity category, and allows for generic use for all use-cases. We discussed that this dashboard view was essentially easier for the dev team to tweak as it contained the majority of the existing features, but in a different layout.
    link: /images/feature/console-big.png
---

<div  project-elements="middle" class="container default" >
  <h2 class="trafalgar text-center" >The Workflow</h2>
  <p class="long-primer text-center" >The clinical director and I sat down and reviewed the typical problems congestive heart failure patients have when discharged from the hospital. Based on the typical timeline that a patient experiences significant changes with vital signs and recovery, we developed a workflow that triggered three activities every 7 days for the patient to complete (virtual visit where they record themselves or take a picture of how swollen their ankles are, recording and measuring vitals with bluetooth devices that integrate with the software, and a symptoms assessment).
  <br><br>
  Based on the patient’s response to each activity (if the vital signs were recorded out of range, symptoms responses that indicate a problem, or images that indicate an issue with the swelling of ankles) an alert would be triggered if there is an issue and the patient would be prioritized in red to the top of the dashboard so the nurses and care coordinator can intervene.</p>
</div>
<div>
  <img src="/images/project_stages/chf-display@2x.jpg" class="display-case">
</div>
<div  project-elements="left" class="container default" >
  <h2 class="double-pica" >The Original Nurse Admin Dashboard</h2>
  <p class="long-primer" >The existing ViiMed coordinator dashboard works very well for nurses who need to monitor patients throughout their orthopedic pathway. However, with congestive heart failure, it does not provide the high-risk alerts and prioritization needed to monitor patients who are more likely to be readmitted back to the hospital. It gives no insight at first glance when the patient’s discharge date was or what tasks the nurse or care coordinator need to complete in relation to each patient. </p>
</div>
<div>
  <img class="display-case" src="/images/og-dashboard-nurse.jpg" >
</div>
<div  project-elements="middle" class="container default" >
  <h2 class="trafalgar text-center" >Mockups & Prototypes</h2>
  <p class="long-primer text-center" >Working with the Clinical Director, I created various mockups with new features that would help the nurses monitor patients with congestive heart failure. I had to keep in mind that the elements of the dashboard had to be generic enough that it would work for orthopedics as well as other use-cases or products.</p>
</div>
<div project-thumbnails style="padding-bottom: 70px;">
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
<div project-elements="middle" class="container grapefruit-bg invert">
  <h2 class="trafalgar text-center" >Challenges I Faced</h2>
  <p class="long-primer text-center">Although the cardiologist I worked with gave great insight and ideas for redesigning the care coordinator dashboard, I knew it only solved the problem for a CHF care plan. </p>
  <div split="list">
    <ul class="invert-icons">
      <li data-icon="&#xe056;" class="icon long-primer"><span>Delivering Client Needs While Maintaining Product Standards</span></li>
      <li data-icon="&#xe004;" class="icon long-primer"><span>Nurse Admin Dashboard only Solved CHF Problems</span></li>
      <li data-icon="&#xe01d;" class="icon long-primer"><span>Some Features Did Not Line Up With Current Business Strategies</span></li>
      <li data-icon="&#xe02a;" class="icon long-primer"><span>Complexity of Creating a Generic Solution for Multiple Use-Cases</span></li>
    </ul>
  </div>
</div>

<div project-elements="middle" class="container default">
  <h2 class="trafalgar text-center" >The Solution</h2>
  <p class="long-primer text-center">Keeping in mind that products should not be made for one user, but rather all users I knew the dashboard needed to have generic features that can multiply across all use-cases. I researched multiple administrative dashboards and how they worked for different products.</p>
</div>
<div>
  <img src="/images/project_stages/chf-dash-display.png" class="display-case">
</div>
<div project-elements="middle" class="container default">
  <h2 class="trafalgar text-center" >Merging Two Interfaces</h2>
  <p class="long-primer text-center">I took into account feedback received from the orthopedic nurses about moving back and forth between the dashboard and their tasklist to complete their daily activities as well as the cardiologists suggestions for being able to mass send an activity to patients, seeing how many patients at once are high-risk, as well as other necessary characteristics to determine the priority of congestive heart failure patients.</p>
</div>
<div before-after>
  <div before-large>
    <h3 class="great-primer text-center">To-Do List Interface</h3>
    <img src="/images/project_stages/nurse-task.png">
  </div>
  <div after-large>
    <h3 class="great-primer text-center">To-Do List Inside Dashboard</h3>
    <img src="/images/project_stages/chf-combined.png">
  </div>
</div>


<div project-elements="middle" class="container default">
  <h2 class="trafalgar text-center" >See it in Action</h2>
  <p class="long-primer text-center">The design you see below mimics that of an e-mail dashboard where one can select multiple e-mails at once (in this case it is patients). The majority of the columns displayed on the dashboard would be default settings with the exception of some that could be configurable by the solution architect depending on the client (e.g., instead of discharge date for congestive heart failure use case, the Solution Architect could choose surgery date instead for the orthopedic care plan).</p>
  <center>
  <img src="/images/feature/chf-demo.gif" class="display-case card-display">
  </center>
</div>
