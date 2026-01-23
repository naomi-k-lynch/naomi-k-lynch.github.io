---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<style>
/* Neural Network Animation */
.neural-container {
  width: 100%;
  height: 200px;
  background: linear-gradient(to bottom, #87CEEB 0%, #E0F6FF 100%);
  position: relative;
  overflow: hidden;
  border-radius: 8px;
  margin: 20px 0;
  box-shadow: 0 4px 15px rgba(135, 206, 235, 0.3);
}
.star {
  position: absolute;
  background: white;
  border-radius: 50%;
  opacity: 0;
  animation: twinkle 3s ease-in-out infinite;
}
.star1 { width: 2px; height: 2px; top: 20%; left: 15%; animation-delay: 0s; }
.star2 { width: 3px; height: 3px; top: 35%; left: 25%; animation-delay: 0.5s; }
.star3 { width: 2px; height: 2px; top: 15%; left: 40%; animation-delay: 1s; }
.star4 { width: 3px; height: 3px; top: 50%; left: 20%; animation-delay: 1.5s; }
.star5 { width: 2px; height: 2px; top: 60%; left: 45%; animation-delay: 2s; }
.star6 { width: 3px; height: 3px; top: 25%; left: 65%; animation-delay: 0.8s; }
.star7 { width: 2px; height: 2px; top: 70%; left: 55%; animation-delay: 1.3s; }
.star8 { width: 3px; height: 3px; top: 40%; left: 75%; animation-delay: 1.8s; }
.star9 { width: 2px; height: 2px; top: 55%; left: 85%; animation-delay: 0.3s; }
.star10 { width: 3px; height: 3px; top: 80%; left: 70%; animation-delay: 2.3s; }
@keyframes twinkle {
  0%, 100% { opacity: 0; }
  50% { opacity: 0.5; }
}
.neuron {
  position: absolute;
  width: 20px;
  height: 20px;
  background: white;
  border-radius: 50%;
  border: 3px solid rgba(255, 255, 255, 0.9);
  box-shadow: 0 0 15px rgba(255, 255, 255, 0.8);
  z-index: 2;
}
.neuron.input1 { top: 40px; left: 8%; }
.neuron.input2 { top: 90px; left: 8%; }
.neuron.input3 { top: 140px; left: 8%; }
.neuron.hidden1-1 { top: 25px; left: 32%; }
.neuron.hidden1-2 { top: 70px; left: 32%; }
.neuron.hidden1-3 { top: 115px; left: 32%; }
.neuron.hidden1-4 { top: 160px; left: 32%; }
.neuron.hidden2-1 { top: 35px; left: 58%; }
.neuron.hidden2-2 { top: 85px; left: 58%; }
.neuron.hidden2-3 { top: 135px; left: 58%; }
.neuron.output1 { top: 65px; left: 84%; }
.neuron.output2 { top: 115px; left: 84%; }
.neuron {
  animation: neuron-pulse 3s ease-in-out infinite;
}
.neuron:nth-child(2n) { animation-delay: 0.5s; }
.neuron:nth-child(3n) { animation-delay: 1s; }
.neuron:nth-child(4n) { animation-delay: 1.5s; }
@keyframes neuron-pulse {
  0%, 100% { 
    transform: scale(1);
    box-shadow: 0 0 15px rgba(255, 255, 255, 0.6);
  }
  50% { 
    transform: scale(1.3);
    box-shadow: 0 0 25px rgba(255, 255, 255, 1), 0 0 35px rgba(135, 206, 235, 0.8);
  }
}
.neural-container svg {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 1;
}
.connection-line {
  stroke: rgba(255, 255, 255, 0.4);
  stroke-width: 2;
  fill: none;
}
.signal {
  r: 4;
  fill: #fff;
  filter: drop-shadow(0 0 4px rgba(255, 255, 255, 1));
}
.signal1 { animation: travel1 3s ease-in-out infinite; }
.signal2 { animation: travel2 3s ease-in-out infinite 0.5s; }
.signal3 { animation: travel3 3s ease-in-out infinite 1s; }
.signal4 { animation: travel4 3s ease-in-out infinite 1.5s; }
.signal5 { animation: travel5 3s ease-in-out infinite 2s; }
@keyframes travel1 {
  0% { cx: 8%; cy: 50px; opacity: 0; }
  10% { opacity: 1; }
  30% { cx: 32%; cy: 35px; }
  50% { cx: 58%; cy: 45px; }
  70% { cx: 84%; cy: 75px; }
  90% { opacity: 1; }
  100% { cx: 84%; cy: 75px; opacity: 0; }
}
@keyframes travel2 {
  0% { cx: 8%; cy: 100px; opacity: 0; }
  10% { opacity: 1; }
  30% { cx: 32%; cy: 80px; }
  50% { cx: 58%; cy: 95px; }
  70% { cx: 84%; cy: 125px; }
  90% { opacity: 1; }
  100% { cx: 84%; cy: 125px; opacity: 0; }
}
@keyframes travel3 {
  0% { cx: 8%; cy: 150px; opacity: 0; }
  10% { opacity: 1; }
  30% { cx: 32%; cy: 125px; }
  50% { cx: 58%; cy: 145px; }
  70% { cx: 84%; cy: 125px; }
  90% { opacity: 1; }
  100% { cx: 84%; cy: 125px; opacity: 0; }
}
@keyframes travel4 {
  0% { cx: 8%; cy: 40px; opacity: 0; }
  10% { opacity: 1; }
  30% { cx: 32%; cy: 70px; }
  50% { cx: 58%; cy: 85px; }
  70% { cx: 84%; cy: 75px; }
  90% { opacity: 1; }
  100% { cx: 84%; cy: 75px; opacity: 0; }
}
@keyframes travel5 {
  0% { cx: 8%; cy: 90px; opacity: 0; }
  10% { opacity: 1; }
  30% { cx: 32%; cy: 115px; }
  50% { cx: 58%; cy: 135px; }
  70% { cx: 84%; cy: 125px; }
  90% { opacity: 1; }
  100% { cx: 84%; cy: 125px; opacity: 0; }
}
</style>
<div class="cloud-container">
  <div class="sun"></div>
  <div class="cloud cloud1"></div>
  <div class="cloud cloud2"></div>
  <div class="cloud cloud3"></div>
  <div class="cloud cloud4"></div>
</div>
<div class="neural-container">
  <div class="star star1"></div>
  <div class="star star2"></div>
  <div class="star star3"></div>
  <div class="star star4"></div>
  <div class="star star5"></div>
  <div class="star star6"></div>
  <div class="star star7"></div>
  <div class="star star8"></div>
  <div class="star star9"></div>
  <div class="star star10"></div>
  <svg>
    <line class="connection-line" x1="8%" y1="50" x2="32%" y2="35" />
    <line class="connection-line" x1="8%" y1="50" x2="32%" y2="80" />
    <line class="connection-line" x1="8%" y1="50" x2="32%" y2="125" />
    <line class="connection-line" x1="8%" y1="100" x2="32%" y2="35" />
    <line class="connection-line" x1="8%" y1="100" x2="32%" y2="80" />
    <line class="connection-line" x1="8%" y1="100" x2="32%" y2="125" />
    <line class="connection-line" x1="8%" y1="100" x2="32%" y2="170" />
    <line class="connection-line" x1="8%" y1="150" x2="32%" y2="80" />
    <line class="connection-line" x1="8%" y1="150" x2="32%" y2="125" />
    <line class="connection-line" x1="8%" y1="150" x2="32%" y2="170" />
    <line class="connection-line" x1="32%" y1="35" x2="58%" y2="45" />
    <line class="connection-line" x1="32%" y1="35" x2="58%" y2="95" />
    <line class="connection-line" x1="32%" y1="80" x2="58%" y2="45" />
    <line class="connection-line" x1="32%" y1="80" x2="58%" y2="95" />
    <line class="connection-line" x1="32%" y1="80" x2="58%" y2="145" />
    <line class="connection-line" x1="32%" y1="125" x2="58%" y2="95" />
    <line class="connection-line" x1="32%" y1="125" x2="58%" y2="145" />
    <line class="connection-line" x1="32%" y1="170" x2="58%" y2="145" />
    <line class="connection-line" x1="58%" y1="45" x2="84%" y2="75" />
    <line class="connection-line" x1="58%" y1="45" x2="84%" y2="125" />
    <line class="connection-line" x1="58%" y1="95" x2="84%" y2="75" />
    <line class="connection-line" x1="58%" y1="95" x2="84%" y2="125" />
    <line class="connection-line" x1="58%" y1="145" x2="84%" y2="125" />
    <circle class="signal signal1" />
    <circle class="signal signal2" />
    <circle class="signal signal3" />
    <circle class="signal signal4" />
    <circle class="signal signal5" />
  </svg>
  <div class="neuron input1"></div>
  <div class="neuron input2"></div>
  <div class="neuron input3"></div>
  <div class="neuron hidden1-1"></div>
  <div class="neuron hidden1-2"></div>
  <div class="neuron hidden1-3"></div>
  <div class="neuron hidden1-4"></div>
  <div class="neuron hidden2-1"></div>
  <div class="neuron hidden2-2"></div>
  <div class="neuron hidden2-3"></div>
  <div class="neuron output1"></div>
  <div class="neuron output2"></div>
</div>

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
