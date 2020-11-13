---
layout: default
keywords:
title: CS236G Generative Adversarial Networks (GANs)
description: GANs have rapidly emerged as the state-of-the-art technique in realistic image generation. You'll start with basic GANs and learn all the way up to their state-of-the-art forms. The applications span realistic image editing that is omnipresent in popular app filters, enabling tumor classification under low data schemes in medicine, and visualizing realistic scenarios of climate change destruction. You'll also get to examine key challenges of GANs today, including reliable evaluation, inherent biases, and training stability. After this course, students should be familiar with GANs and the broader generative models and machine learning contexts in which these models are situated. 
buttons: [syllabus, piazza, video]
micro_nav: true
---
## Course Information
- This quarter ({{ site.course.quarter }}), CS236G meets for in-class lecture {{ site.course.time}}, {{ site.course.venue }}.
- All class communication happens on the [CS236G Piazza forum]({{ site.course.piazza }}). For private matters, please make a private note visible only to the course instructors. For longer discussions with TAs and to get help in person, we strongly encourage you to come to office hours. If you need to contact us via email, please email individual TAs.
- The course content and deadlines for all assignments are listed in our [syllabus](/syllabus).
- For general inquiries, please contact <{{ site.course.qa }}>.

<!-- Course Staff -->
{% include staff.html %}

## Logistics
All course announcements take place through the [class Piazza forum]({{ site.course.piazza }}). Please make sure to join!
#### Class components

CS236G has the following components:
* In class lecture - once a week (hosted on [Zoom](https://stanford.zoom.us/j/95170971060?pwd=bnNFU1pBWExlUlVUdDQ0RnNsYWQvQT09)). 
* Video lectures, programming assignments, and quizzes on Coursera
* [The final project](/project)
* [Weekly TA-led sections](/section)

#### Goals of CS236G

CS236G aims to get you excited about this advanced method. 
* In-class lectures on Tuesdays: these lectures will be a mix of advanced lectures on a specific subject that hasn't been treated in depth in the videos or guest lectures from industry experts. You can access these lectures on the [Zoom tab on Canvas](https://canvas.stanford.edu/courses/117317/external_tools/5384), and they will also be posted afterwards on [Canvas](https://canvas.stanford.edu/).
* Two modules from the [deeplearning.ai](https://www.deeplearning.ai/) [Deep Learning Specialization](https://www.deeplearning.ai/deep-learning-specialization/) on Coursera. You will watch videos at home, solve quizzes and programming assignments hosted on online notebooks.
* TA-led sections on Thursdays: Teaching Assistants will teach you hands-on tips and tricks to succeed, but also theorethical foundations.
* Project meeting with your TA mentor: CS236G is a project-based class. Through personalized guidance, TAs will help you succeed in implementing a successful GAN project this quarter.


One module of the [deeplearning.ai](https://www.deeplearning.ai/) [GANs Specialization](https://www.deeplearning.ai/generative-adversarial-networks-specialization/) on Coursera includes:

 * Videos. These are organized in "weeks". You will have to watch ≈10 videos (approx 10min each) every week.
 * In-video quizzes. These are sprinkled in every video for you to assess your understanding of the material.
 * Programming assignments (≈2h per week to complete). The programming assignments will usually lead you to build concrete algorithms, you will get to see your own result after you've completed all the code. It's gonna be fun! For both assignment and quizzes, follow the deadlines on the Syllabus page, not on Coursera.

## Prerequisites
Students are expected to have the following background:
 * Familiarity with basic programming (CS106B or CS101)
 * Familiarity with basics of deep learning (CS230 or CS221)
 * Familiarity with the probability theory (CS 109 or STATS 116)
 * Familiarity with linear algebra (MATH 51)

## Grading

Here's more information about the class grade:

#### Breakdown
 
* 50%: Class project - creativity and equal participation within a group will be rewarded
* 25%: Midterm
* 25%: Programming assignments & quizzes
* 0%: Attendance
* Extra credit: Your (or your GAN-generated) Memes. Requirements: Relevant and Appropriate with capital R and A there.

#### Class Project Deliverables

##### 20%, Proposal
* Inspo: Find sources of inspiration that you think are cool. You must include 7 sources, at least 2 of which must be academic papers, and write a brief paragraph on each. In your paragraph, give a brief mention of the sources that *they* relied on. You will be assessed on the diversity of material (to prevent student mode collapse :D).
* Idea spew: Create a list of 2+ project ideas you'd be interested in exploring. In each, you must include the dataset you plan to use, the model architecture, and the real-world application this will be used towards. At least two of the three among {dataset, model, application} must be novel. A novel dataset is one which has never had a GAN applied to it (we encourage you to get creative / scrape the data yourself).

##### 15%, Milestone 1 
* I haz the data: Your dataset will be submitted as part of our course's "data stash". We get really psyched when we have a good stash. 💫
* Inkling: Run a baseline model on your data and get cracking!

##### 15%, Milestone 2
* Ignition on: You should have largely implemented the plan you set sail for ⛵️ (or an alternative prospect that you pivoted to).
* Star-gazer: Describe some highly risky experiments that you plan to perform. The more the merrier! 🤩

##### 50%, Final Draft
* Team Playa: Equal participation within your pair (N/A if flying solo). This to reduce the case where one person does all the work, and make it a bit easier on an individual.
* Virtually-famous: Submit a video no longer than two minutes about your project.
* Don Quixote: Give the results of the quixotic experiments that you mentioned in Milestone 2. This will be weighted heavily as we want to encourage fearless exploration - don't worry if experiments don't pan out!
    ![](./images/don-quixote.gif)

#### Submitting Assignments
From the Coursera sessions (accessible from the invite you receive by email), you will be able to watch videos, solve quizzes and complete programming assignments. Each quiz and programming assignment can be submitted directly from the session and will be graded by our autograders.

You will submit your [project deliverables](/project/#project-deliverables) on [Gradescope](https://www.gradescope.com/courses/000). You should be added to Gradescope automatically by the end of the first week. If not you can join with course code **TBD**.

#### Late assignments
No late days. We won't grade them. You'll probably still do fine in the class.

#### Students with Documented Disabilities
Students who may need an academic accommodation based on the impact of a disability must initiate the request with the [Office of Accessible Education](https://oae.stanford.edu/) (OAE). Professional staff will evaluate the request with required documentation, recommend reasonable accommodations, and prepare an Accommodation Letter for faculty. Unless the student has a temporary disability, Accommodation letters are issued for the entire academic year. Students should contact the OAE as soon as possible since timely notice is needed to coordinate accommodations. The OAE is located at 563 Salvatierra Walk (phone: 723-1066).

#### Honor code
We strongly encourage students to form study groups. Students may discuss and work on programming assignments and quizzes in groups. However, each student must write down the solutions independently, and without referring to written notes from the joint session. In other words, each student must understand the solution well enough in order to reconstruct it by him/herself. In addition, each student should submit his/her own code and mention anyone he/she collaborated with. It is also an honor code violation to copy, refer to, or look at written or code solutions from a previous year, including but not limited to: official solutions from a previous year, solutions posted online, and solutions you or someone else may have written up in a previous year. Furthermore, it is an honor code violation to post your assignment solutions online, such as on a public git repo.

[The Stanford Honor Code](https://communitystandards.stanford.edu/policies-and-guidance/honor-code)

[The Stanford Honor Code as it pertains to CS courses](https://web.stanford.edu/class/archive/cs/cs106b/cs106b.1164/handouts/honor-code.pdf)


This site was forked from CS230: Deep Learning (https://CS230.stanford.edu).
