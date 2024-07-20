---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

My academic research falls into two main areas: The first one from the top is the study of **The Atmospheric Impairments on the High Frequency (microwave and mmWave)  Band**. This study is based on **ITU-R** study and published documents. The **ITU-R** study group,  which studies the **radio communication sector**, publishes scientific documents which studies many  atmospheric impairments such as rain, fog, cloud, temprature,...e.t.c. My main investigation in this research is specified to Rain Attenuation on microwave and mmWave band.  My aim is to design a deep learning based prediction model using the existing **ITU-R** research documents and prediction models for rain attenuation modeling. The region of interest of this research is **ETHIOPIA** and I believe this research will contribute a lot for Academicians, researchers and engineers in the region. 

My other main research was on a simple design of **UART Instruction Controller** based on **FPGA(Feild Programable Gate Array)**, a project that I developed a simple method to design such a port using  **Verilog HDL**. This research was a project submitted in partial fulfillment of the requirements for the degree of Bachelor in Communication Engineering. In this project I have developed a skills of hardware description language such as verilog and grasp a fundamental working principle of **FPGA**s. 



<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
