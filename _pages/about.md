---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<div class="cloud-container">
  <div class="sun"></div>
  <div class="cloud cloud1"></div>
  <div class="cloud cloud2"></div>
  <div class="cloud cloud3"></div>
  <div class="cloud cloud4"></div>
</div>

<style>
.cloud-container {
  width: 100%;
  height: 120px;
  background: linear-gradient(to bottom, #87CEEB 0%, #E0F6FF 100%);
  position: relative;
  overflow: hidden;
  margin: 20px 0;
  border-radius: 8px;
}
.cloud {
  position: absolute;
  background: white;
  border-radius: 100px;
  opacity: 0.9;
}
.cloud::before, .cloud::after {
  content: '';
  position: absolute;
  background: white;
  border-radius: 100px;
}
.cloud1 {
  width: 100px;
  height: 40px;
  top: 20px;
  animation: float1 20s infinite linear;
}
.cloud1::before {
  width: 50px;
  height: 50px;
  top: -25px;
  left: 10px;
}
.cloud1::after {
  width: 60px;
  height: 40px;
  top: -15px;
  right: 10px;
}
.cloud2 {
  width: 80px;
  height: 35px;
  top: 60px;
  animation: float2 25s infinite linear;
  animation-delay: -5s;
}
.cloud2::before {
  width: 40px;
  height: 40px;
  top: -20px;
  left: 15px;
}
.cloud2::after {
  width: 50px;
  height: 35px;
  top: -12px;
  right: 8px;
}
.cloud3 {
  width: 60px;
  height: 25px;
  top: 35px;
  animation: float3 30s infinite linear;
  animation-delay: -15s;
}
.cloud3::before {
  width: 30px;
  height: 30px;
  top: -15px;
  left: 10px;
}
.cloud3::after {
  width: 35px;
  height: 25px;
  top: -10px;
  right: 5px;
}
.cloud4 {
  width: 70px;
  height: 30px;
  top: 15px;
  animation: float4 22s infinite linear;
  animation-delay: -10s;
}
.cloud4::before {
  width: 35px;
  height: 35px;
  top: -18px;
  left: 12px;
}
.cloud4::after {
  width: 40px;
  height: 30px;
  top: -12px;
  right: 8px;
}
@keyframes float1 {
  from { left: -120px; }
  to { left: 100%; }
}
@keyframes float2 {
  from { left: -100px; }
  to { left: 100%; }
}
@keyframes float3 {
  from { left: -80px; }
  to { left: 100%; }
}
@keyframes float4 {
  from { left: -90px; }
  to { left: 100%; }
}
.sun {
  position: absolute;
  top: 15px;
  right: 20px;
  width: 40px;
  height: 40px;
  background: #FFD700;
  border-radius: 50%;
  box-shadow: 0 0 20px rgba(255, 215, 0, 0.5);
}
</style>

About Me
------
I am a first-year graduate student at the University of Pennsylvania, where I am pursuing a M.S.E. in data science. Currently, I am a research assistant at Penn's [Computational Social Listening Lab](https://csl-lab-upenn.github.io/), under Sharath Chandra Guntuku, PhD. There, I am working with Vivienne Bihe Chi, PhD on a project leveraging machine learning techniques to analyze multimodal primary care visit data and examine provider-patient trust. 

Before this, I earned my B.A. in Psychology with a certificate in data fluency from Brown University. I have an additional 4.5 years of combined research experience working at various psychology labs throughout my undergraduate career and, most recently, at UCSF's Eating Disorders Program as their clinical research coordinator. I am very interested in the application of statistical methods, innovative technologies, and data science in the study of mental health and human well-being, and I am especially passionate about researching and improving healthcare access and quality in marginalized and understudied populations!

My Research Journey
------
As mentioned above, I was originally trained in the field of psychology. I first had the pleasure of being exposed to developmental psychology and linguistic research under Roman Feiman, PhD at the [Brown Language and Thought Lab](https://sites.brown.edu/bltlab/) as a research assistant during my sophomore and junior years. Their research asks the following: What do babies think before learning language? How does language change thought in children? How are language and thought related in adults? This is where I learned all the tedious tasks human research involves (aka cold-calling, flyering, anything logistical...), and came to love working in a research setting. I also had quite a bit of fun running studies with toddlers.

My senior year I pivoted to work as a research intern at the [Rhode Island Resilience Lab](https://sites.brown.edu/riresiliencelab/) under Nicole Nugent, PhD, on a study examining the role social context plays in recovery from a traumatic event and hospitalization in adolescents. I am one of the many people who finds clinical psychology fascinating, and this was a wonderful fit for me. This project involved the pre-processing and analysis of messages across several platforms (iMessage, Snapchat, Twitter, Facebook, etc), and is what sparked my interest in the work that can be done at the intersection of psychology and data science.

After graduating, I spent 2 years at UCSF working at their [Eating Disorders Program](https://eatingdisorders.ucsf.edu/) as a clinical research coordinator with the intention of pursuing a PhD in psychology afterward. After 2 years of database management, analytics projects with team members, and clinic data collection, and with a lot of amazing mentorship (specifically Drs. Sasha Gorrell, Erin Accurso, and Erin Reilly), I decided the best next step for me would be a graduate degree in data science. And all of that is what brings me to Penn!

Other Interests
------
* New restaurant exploration
* The Eagles, of course
* Bad reality television
* Yoga & pilates
* Baking 🍪
