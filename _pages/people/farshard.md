---
title: "Chri Lab - Farshad"
layout: personal
permalink: /people/farshad/
sitemap: false
excerpt: "Personal webpage of Farshad"
---
{%- assign data = site.data.people -%}
{%- assign member = data.farshad -%}

<div class="row">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="22%" style="float: left" />
  <h1>{{ member.name }}</h1>
  <i style="font-size:20px">{{ member.info }}</i><br>

  {% if member.website %}<a href="{{ member.website }}" target="_blank"><i class="fa fa-home fa-3x"></i></a> {% endif %}
  {% if member.email %}<a href="mailto:{{ member.email }}" target="_blank"><i class="fa fa-envelope-square fa-3x"></i></a> {% endif %}
  {% if member.scholar %} <a href="{{ member.scholar }}" target="_blank"><i class="ai ai-google-scholar-square ai-3x"></i></a> {% endif %}
  {% if member.github %} <a href="{{ member.github }}" target="_blank"><i class="fa fa-github-square fa-3x"></i></a> {% endif %}
  {% if member.linkedin %} <a href="{{ member.linkedin }}" target="_blank"><i class="fa fa-linkedin-square fa-3x"></i></a> {% endif %}
  {% if member.twitter %} <a href="{{ member.twitter }}" target="_blank"><i class="fa fa-twitter-square fa-3x"></i></a> {% endif %}
  <!-- {% if member.researchgate %} <a href="{{ member.researchgate }}" target="_blank"><i class="ai ai-researchgate-square ai-3x"></i></a> {% endif %} -->
  <ul style="overflow: hidden">

  {% for education in member.education %}
	<li> {{ education }} </li>
  {% endfor %}

  </ul>
</div>

## Biography

<p>
I am a Ph.D. student in robotics at the Department of Mechanical Engineering and the School of Computing and Information Systems at the University of Melbourne. My research focuses on shared control in Human-Robot Interaction (HRI) and Human-Computer Interaction (HCI). I am supervised by Dr. Jonathan Eden, Dr. Wafa Johal, and Prof. Denny Oetomo.

I hold a master's degree in Mechatronics Engineering from Sharif University of Technology, where I worked on predicting knee joint angles in a lower limb exoskeleton robot using sEMG and IMU signals with deep neural networks. I also have a bachelor's degree in Mechanical Engineering from the University of Tehran, where I studied bipedal dynamic balance using control algorithms. 
<br/>

## Publications

    [1] F. H. Daryakenari, M. Mollahossein, A. Taheri, and G. R. Vossoughi, “Classification of Lower Limb Electromyographical Signals Based on Autoencoder Deep Neural Network Transfer Learning,” 10th RSI 		International Conference on Robotics and Mechatronics, ICRoM 2022, no. ICRoM, pp. 323–328, 2022, doi: 10.1109/ICRoM57054.2022.10025236.
    [2] M. Mollahossein, F.H. Daryakenari, M.H. Rohban, and G.R. Vossoughi, “Attention-Based Convolutional Neural Network Model for Human Lower Limb Activity Recognition using sEMG, ” arXiv, 2025.
    [3] F.H. Daryakenari, T. Farizeh, “A Novel Transformer-Based Method for Full Lower-Limb Joint Angles and Moments Prediction in Gait Using sEMG and IMU signals, ” arXiv, 	2025.

Contact me: f.haghgoodaryakenari[at]unimelb[dot]edu[dot]au
<br/>
[Google Scholar](https://scholar.google.com/citations?hl=en&authuser=2&user=qt7q0ZsAAAAJ)
<br/>
[LinkedIn](https://linkedin.com/in/farshad-haque-daryakenari)
<br/>
[Personal Webpage](https://sites.google.com/view/farshad-daryakenari/bio?authuser=2)

</p>

<div class="publications">

{% bibliography -f people/farshad%}

</div>
