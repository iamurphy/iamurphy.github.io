---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.Math - Joint Honours Applied Mathematics & Statistics, University of Waterloo, 2019
* M.Sc. - Statistics, University of British Columbia, 2019-Present
* Ph.D - Soon? Spoilers!

Research
======
For my Master's thesis, I am currently working with two wonderful professors–Dr. Nancy Heckman and Dr. Marie Auger-Méthé. I am working on analyzing extensive killer whale data. I am currently developing a tool that marine mammal researchers can use to classify the phases of their diving data, then use this data to build a model to predict the dive phase definitions for unseen dives. This tools will hopefully one day become an R package on CRAN that everyone can have access to. It will involve an interactive Shiny App as well, which has been loads of fun for me to develop. Stay tuned!

Work experience
======
* Jan - May 2020: Data Scientist - Vision Critical (Alida)
  * Duties included: Worked on a customer churn algorithm using survival analysis techniques. Found, cleaned, and verified lots of messy, messy, messy data.
  * Worked with R, SQL, and Python

* Sept - Dec 2018: Data Scientist - Bell Canada
  * Put together a customer retention machine learning algorithm to determine how much of a discount we could give to customers to retain them but to continue to profit.
  * Worked primarily in Python. 
  
* Jan - Apr 2018: Methodologist - Statistics Canada
  * Worked with monthly survey data related to energy expenditure of Canadian businesses.
  * Performed sample selection every month, then analyzed the resultant data from the previous month.
  * Generated monthly reports of the findings.
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>  
  
Skills
======
* R, R, and more R
* Python
* SQL
* Shiny Apps
 
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
