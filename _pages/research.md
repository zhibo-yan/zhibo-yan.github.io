---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

My research has been focused on building efficient, performant systems for sensing, computing, communicating and securing the information in our connected world. Throughout my career, my research has aimed to solve the fundamental and near-impossible problems, which has often led to new areas of research and commercialization solutions. My approach to research is as follows: I identify core challenges with building next-generation technologies, form those as research topics and solve those with creativity and analytical understanding of the problem and go at length to solve them, including building integrated circuits or building robots, end-to-end systems. My research group [WCSNG Group](https://wcsng.ucsd.edu/) continues to work with same philosophy of solving fundamental problems, impacting areas of from IoT to robotics, to mobile sensing, mobile computing to every-day life. Specifically, my research agenda is focused on building systems in the broad areas of vision/perception systems, sensing systems, wireless communications, wireless networking. As such, my work has inspired significant follow-up work on almost all of the topics I have worked on. 

I have worked and introduced a range of research areas and topics from communications, sensing, computing, and networking. My research career began by solving an open problem on enabling full-duplex radios in wireless communication. Specifically, It is, rather, it was well known that full-duplex radios are near impossible to achieve, with multiple wireless textbooks claiming it. This work inspired my research philosophy as well to a large extent to focus on identifying the fundamental problem on different topics and solving those problems, which inadvertently leads to significant impact and evolves new research areas to work on. My group has worked on the following topics following my research philosophy: sensing of radios in environments (radars, wireless localization, WiFi-SLAM), Wireless Sensing Driven Communication and Cloud RAN, Wireless Sensing for autonomous systems, Smart Surfaces based wireless networking and computing, Scalable and Ultra-low-power WiFi connectivity for IoT, Optimized Edge Node Compute, Full-duplex radios for networking and sensing, mm-accurate wireless sensing and localization, building scalable and reliable 5G mm-wave and autonomous perception systems using cameras and radars. 


<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
