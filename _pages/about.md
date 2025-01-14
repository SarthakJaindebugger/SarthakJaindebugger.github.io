---
layout: about
title: About
permalink: /

subtitle: 

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: >
     <p> </p>
     <p> </p>
     <p> </p>

news: false
selected_papers: false
social: true
latest_posts:
  - date: "May 11, 2024"
    link: "https://www.linkedin.com/posts/creatersarthakjain_ai-cybersecurity-innovation-activity-7197480519066951680-9lph?utm_source=share&utm_medium=member_desktop"
    description: "International Conference on AI in Cyber Security"
  - date: "April 24, 2024"
    link: "https://www.linkedin.com/posts/creatersarthakjain_ucsandiego-education-innovation-activity-7188963899843440640-TimS?utm_source=share&utm_medium=member_desktop"
    description: "UC San Deigo International Event at Taj Palace, New Delhi"
  - date: "April 16, 2024"
    link: "https://www.linkedin.com/posts/creatersarthakjain_computervision-ai-mit-activity-7188588032936030208-8mME?utm_source=share&utm_medium=member_desktop"
    description: "Webinar on Computer Vision by Massachusetts Institute of Technology"
  - date: "March 7, 2024"
    link: "https://www.linkedin.com/feed/update/urn:li:activity:7167929915160416257/"
    description: "Webinar on Quantum Computing by IIT Madras"
  - date: "February 6, 2024"
    link: "https://www.linkedin.com/feed/update/urn:li:activity:7158450504539283457/"
    description: "Webinar on Human-Robot Interaction by Stanford University"
  - date: "April 6, 2023"
    link: "https://www.linkedin.com/feed/update/urn:li:activity:7051565419035279361/"
    description: "Webinar on Snow Leopard Conservation by WWF"  
---

A flora and fauna lover, with deep research interest in Machine Learning domain of **Signal/Speech Processing**. I work broadly in the areas of Automatic Speech Recognition (ASR), Deepfake Detection, Large Language Models (LLMs), Natural Language Processing, Foundation Models and Machine Learning Operations (MLOps). I'm also fascinated in exploring the areas of Computer Vision, Embodied AI, Robotics & Multi Agent Systems.

Beyond technical stuff, I love hitting the gym, work actively with ISCA-SAC podcast team as a host, sound mixing & editing. Also, when I unwind, I'm drawn to Netflix webseries & films for entertainment.

I am **open to collaborating** with individuals/ groups/ labs who share similar
 research interests, with the aim of working on a novel project and subsequently publishing a paper in a core A/A* conference like Interspeech, ICASSP, NeurIPS, ACL, NAACl etc or a reputable journal.

I can be reached at **sarthakjainssjj@gmail.com** & for urgent matters, please use **shubh2002jain@gmail.com**.

{% if page.latest_posts %}
<section>
  <h2>Latest Posts/ News</h2>
  <ul>
    {% for post in page.latest_posts %}
    <li>
      <span>{{ post.date }}</span>
      <a href="{{ post.link }}">{{ post.description }}</a>
    </li>
    {% endfor %}
  </ul>
</section>
{% endif %}
