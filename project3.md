---
layout: page
title: Care Coordinator Dashboard & CHF
bigscreen_text: Care Coordinator Dashboard & CHF
feature-image: /images/feature/chf-mac.png
bg_color: e03d46
linkclass: canary-link
img-step-color: lite-content
img-step-color2: lite-content
bigscreen-text-color: ffffff
leader: I worked directly with a cardiologist to come up with a Congestive Heart Failure (CHF) program to build with ViiMed’s platform. The idea behind the program was to minimize hospital readmissions during the critical 30 day period after the patient is discharged from the hospital. <br /><br /> We worked together to come up with 3 activities the patient needs to complete in order to stay on track with their health, as well as important elements on the coordinator dashboard that were necessary for nurses to manage patients with the highest risk of readmissions.
images:
  - image_path: /images/project_stages/console-2thumb.png
    title: Mockup 1
    description: This mockup shows the typical way doctors read, according to the cardiologist I worked with. The black paragraph you see on the upper left of the patients' progress bar is a string of data collected from the enrollment form (the nurse fills out a form on the software to enroll the patient into the program prior to when they leave the hospital).The mockup also shows a readmissions risk percentage for each patient which would also be calculated by the medical history entered on the enrollment form and the care plan activities.  
    link: /images/project_stages/console2.png
  - image_path: /images/project_stages/console1-thumb.png
    title: Mockup 2
    description: Here we have the care coordinator or nurse's tasklist embedded within their dashboard where they manage their patients (two interfaces becoming one so they don't have to jump back and forth). This version also provides an overall view of each patient's severity rating. If you click on the individual dot on the scatterplot, you would essentially be able to "drill down" into that patient's medical profile.
    link: /images/project_stages/console1.png
  - image_path: /images/project_stages/console-prototype.png
    title: Mockup 3
    description: This last mockup is the one we concluded with. It shows a high level view of the amount of patients in each severity category, and allows for generic use for all use-cases. I will go into more detail regarding the purpose for the generic use later on. We discussed that this dashboard view was essentially easier for development to tweak as it contained the majority of the existing features, but in a different layout.
    link: /images/feature/console-big.png
---

{% include project-stage.html pjc-color="non-background" title_color="dark-neutral" leadin_color="dark-neutral" title="The Workflow" lead-in="The cardiologist and I sat down and reviewed the typical problems congestive heart failure patients have when discharged from the hospital. Based on the typical timeline that a patient experiences significant changes with vital signs and recovery, we developed a workflow that triggered three activities every 7 days for the patient to complete (virtual visit where they record themselves or take a picture of how swollen their ankles are, recording and measuring vitals with bluetooth devices that integrate with the software, and a symptoms assessment). <br /> <br /> Based on the patient’s response to each activity (if the vital signs were recorded out of range, symptoms responses that indicate a problem, or images that indicate an issue with the swelling of ankles) an alert would be triggered if there is an issue and the patient would be prioritized in red to the top of the dashboard so the nurses and care coordinator can intervene. " feature-image="/images/feature/chfworkflow.png" %}

{% include project-stage-bg.html pjc-color="non-background" title_color="dark-neutral" leadin_color="dark-neutral" title="The Existing Coordinator Dashboard" lead-in="The existing ViiMed coordinator dashboard works very well for nurses who need to monitor patients throughout their orthopedic pathway. However, with congestive heart failure, it does not provide the high-risk alerts and prioritization needed to monitor patients who are more likely to be readmitted back to the hospital. It gives no insight at first glance when the patient’s discharge date was or what tasks the nurse or care coordinator need to complete in relation to each patient." bg_image="console-before-bg.png" %}

<div class="parrot mediumpadding">
  <h2 class="lite-content">Iterations of the Coordinator Dashboard</h2>
  <p class="lite-content">Working with the cardiologist, I created various mockups with new features that would help the nurses monitor patients with congestive heart failure.</p>
  {% include image-steps.html %}
</div>

<center>
<div class="generic-container">
<h2 class="generic">Making the Dashboard Generic for all Use-Cases</h2>
<p>Although the cardiologist I worked with gave great insight and ideas for redesigning the care coordinator dashboard, I knew it only solved the problem for a CHF care plan. Keeping in mind that products should not be made for one user, but rather all users I knew the dashboard needed to have generic features that can multiply across all use-cases. I began doing online research of generic admin dashboards and came up with the design you see below. <br><br>
I took into account feedback received from the orthopedic nurses about moving back and forth between the dashboard and their tasklist to complete their daily activities as well as the cardiologists suggestions for being able to mass send an activity to patients, seeing how many patients at once are high-risk, as well as other necessary characteristics to determine the priority of congestive heart failure patients.<br><br> The design you see below mimics that of an e-mail dashboard where one can select multiple e-mails at once (in this case it is patients). The majority of the columns displayed on the dashboard would be default settings with the exception of some that could be configurable by the solution architect depending on the client (e.g., instead of discharge date for congestive heart failure use case, the Solution Architect could choose surgery date instead for the orthopedic care plan).
</p>
<img src="/images/feature/chf-demo.gif">
</div>
</center>
