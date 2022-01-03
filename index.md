---
layout: default
keywords:
title: CS236G Generative Adversarial Networks (GANs)
description: GANs have rapidly emerged as the state-of-the-art technique in realistic image generation. Its applications span realistic image editing that is omnipresent in popular app filters, enabling tumor classification under low data schemes in medicine, and visualizing realistic scenarios of climate change destruction. You'll also get to examine key challenges of GANs today, including reliable evaluation, inherent biases, and training stability. After this course, students should be familiar with GANs and the broader generative models and machine learning contexts in which these models are situated. 
buttons: [syllabus, piazza, video]
micro_nav: true
add_gif: gans_demo_2.gif
add_webp: gans_demo_2.webp
show_lecture_time: true
---

## Course Information
- This quarter ({{ site.course.quarter }}), CS236G meets for in-class lecture {{ site.course.time}}, {{ site.course.venue }}.
- All class communication happens on the [CS236G Piazza forum]({{ site.course.piazza }}). For private matters, please make a private note visible only to the course instructors. For longer discussions with TAs and to get help in person, we strongly encourage you to come to office hours. If you need to contact us via email, please email individual TAs.
- The course content and deadlines for all assignments are listed in our [syllabus](/syllabus).
- For general inquiries, please contact <{{ site.course.qa }}>.

<!-- Course Staff -->
{% include staff.html %}


## Course Goals
- Learn and build generative adversarial networks (GANs), from their simplest form to state-of-the-art models. 
- Implement, debug, and train GANs as part of a novel and substantial course project.
- Gaining familiarity with the latest cutting-edge literature on GANs.
- Reward risk-taking and creative exploration.

## Course Components
* In class lectures - twice a week on {{ site.course.time}} (hosted on {{ site.course.venue }}). 
* Video lectures, programming assignments, and quizzes on Coursera
* [The final project](/project)

## Lecture Schedule <a name="table"></a>

| Date | Week | Title |     Resources    |
|------|:----:|:-----:|:----------------:|
| 01/4/2021 | 1 | **Introduction & Coursera** | [Slides](https://drive.google.com/file/d/1Hm_EOtZm94C9OARpkfeALd7pLmp3B9_5/view?usp=sharing)<br /> [Welcome Video](https://stanford-pilot.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=525639ad-3bb0-4340-9a72-ae120002cd9f) <br /> [Course Overview Video](https://stanford-pilot.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=5bed7c96-16b5-4c00-bb06-ae120002f65e) <br /> [Coursera](https://www.coursera.org/learn/build-basic-generative-adversarial-networks-gans) |
| 01/11/2021 | 2 | **Coursera & Project Inspo** | [Coursera 1](https://www.coursera.org/learn/build-basic-generative-adversarial-networks-gans)<br />[Coursera 2](https://www.coursera.org/learn/build-better-generative-adversarial-networks-gans) <br/> [Project Inspo](https://stanford-pilot.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=5ef9ec0c-5444-47a6-8942-ae120002ce05) |
| 01/18/2021 | 3 | **Coursera** | [Coursera](https://www.coursera.org/learn/build-better-generative-adversarial-networks-gans) |
| 01/25/2021 | 4 | **Coursera** | [Coursera](https://www.coursera.org/learn/apply-generative-adversarial-networks-gans) |
| 02/01/2021 | 5 | **Midterm & How to Read a Paper** | [Slides](https://drive.google.com/file/d/1sV_wVEYQIQk4UVjkFZbka33z8KJONuUU/view?usp=sharing)<br />[How to Read a Paper Video](https://www.youtube.com/watch?v=ReIZgbCwfg0) |
| 02/08/2021 | 6 | **GANs Project Workshop** Part 1 | [Notebook](https://colab.research.google.com/drive/1YkPs4N886UIeIKULWUidmRlqg67OddNd?usp=sharing)<br />[](https://stanford-pilot.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=63d07b90-5790-4fd7-a891-accc0182bae6) |
| 02/10/2021 | 6 | **GANs Project Workshop** Part 2 | [Notebook](https://colab.research.google.com/drive/1_V9KhDwM0x9cNzMarF7Yd6IJoUHhIkPo?usp=sharing)<br />[GAN Starter Notebook](https://colab.research.google.com/drive/1q2eX8jY4269ITK48OAA14d-qARcGoEAo?usp=sharing)<br />[AWS Instructions](https://docs.google.com/document/d/1JvNcl8WXPGt5rPqWYlIcIePd_ov0FveXyGZlXn3Vc2Y/edit?usp=sharing)<br />[](https://stanford-pilot.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=d61a4316-f7bd-47d3-9473-acd3018728f1) |
| 02/15/2021 | 7 | **Artbreeder** | [Artbreeder (Joel)](https://www.artbreeder.com/)<br />[Video](https://stanford-pilot.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=1a262eec-2730-467a-92dd-ae120042e985) |
| 03/01/2021 | 8 | **Disentanglement & Interim Project Showcase** | [Disentanglement Video](https://stanford-pilot.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=29ca1879-079e-43b2-8f2e-ae120042fa00) |
| 03/08/2021 | 9 | **BigGAN** | [Video](https://stanford-pilot.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=8eae3ce5-0eb3-4225-9118-ae120002ce2f) |
| 03/16/2021 | 10 | **NVIDIA Research & Project Showcase** | [NVIDIA Research Interview](https://stanford-pilot.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=232b1ff2-ac5d-4a89-9306-ae120002ce5a) |


## Prerequisites
Students are expected to have the following background:
 * Familiarity with basic programming (CS106B or CS101)
 * Familiarity with basics of deep learning (CS230 or CS221)
 * Familiarity with the probability theory (CS 109 or STATS 116)
 * Familiarity with linear algebra (MATH 51)

## Grading
 
* 35%: Programming assignments
* 5%: Midterm
* 60%: Class project - creativity and equal participation within a group will be rewarded
* 0%: Attendance
* Extra credit: Your (or your GAN-generated) Memes. Requirements: Relevant and Appropriate with capital R and A there.

## Auditing

All students who are looking to audit the course should make a private post on [Piazza]({{ site.course.piazza }}). You should receive an invitation to the course's Canvas and the Coursera course in your Stanford email within 24-48 hours of submitting this form. Make a private piazza post (preferred) or email <{{ site.course.qa }}> if you did receive get the invitations.

This site was forked from CS230: Deep Learning (https://CS230.stanford.edu).
