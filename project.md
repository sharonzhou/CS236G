---
# Page settings
layout: default
keywords:
comments: false

# Hero section
title: Project
description: One of CS236G's goals is to prepare you to apply GANs to real world tasks. The final project will get you started in that direction.


# Micro navigation
micro_nav: true
---

# Class Project Deliverables

This section contains the detailed instructions for the different parts of your project.

**Submission:** We will be using Gradescope for submission of all parts of the final project. We’ll announce when submissions are open for each part. You should submit on Gradescope as a group: that is, for each part, please make one submission for your entire project group and tag your team members.

## Project Inspo Part 1 (***Due 1/31***) - 5%
**Inspo**: Start exploring project ideas you find interesting (papers, blog posts, etc.). Either:
 - Discuss a project idea with a TA.
 - Write up a paragraph about an idea from this [spreadsheet](https://docs.google.com/spreadsheets/d/10yi7lMdpbz-u_0S9xTBMuDPOdfzDpF_JZu2P40ZC_nk/edit?usp=drive_web&ouid=111642539912347805933).

**Submission**: Nothing if you talked to a TA. Submit a pdf doc on Gradescope if you wrote a paragraph.

**Grading**: Graded on completion.

## Project Inspo Part 2 (***Due 2/7***) - 5%
**Inspo**: Find sources of inspiration that you think are cool.
 - You must include 7 sources, at least 2 of which must be academic papers, and write a brief paragraph on each
 - In your paragraph, give a brief mention of the sources that they relied on.

**Submission**: Include paragraphs about 7 sources as a pdf document. Your document should not exceed 4 pages.

**Grading**: This checkpoint is intended to help you read a wide variety of resources to find inspiration for your project. You will be assessed on the diversity of material (to prevent student mode collapse :D).

## Project Proposal (***Due 2/14***) - 10%
**Idea spew**: Let’s generate project ideas.
 - Create a list of 2+ project ideas you’d be interested in exploring. 
 - Include the dataset you plan to use, the model architecture, and the real-world application this will be used towards. 
 - At least two of the three among {dataset, model, application} must be novel. A novel dataset is one which has never had a GAN applied to it (we encourage you to get creative / scrape the data yourself).

**Submission**: Include 2 project ideas as a pdf document. Your document should not exceed 3 pages. Submit pdf on Gradescope.

**Grading**: The project proposal is intended to help you get into the habit of reading papers and thinking about your project. As long as you follow the instructions above and have two solid project ideas which follow the requirements, you should do well.

## Milestone 1 (***Due 2/24***) - 20%
**I haz the data**: Prepare the data.
 - Your dataset will be submitted as part of our course’s “data stash”. We get really psyched when we have a good stash. 💫
 - Write a paragraph or two about your dataset. We recommend writing this as though you are writing the dataset portion of your final report. The paragraph(s) should contain:
     - The type of data
     - Where/how you obtained it
     - The size of the dataset, the train/validation/test splits
     - Preprocessing done on the dataset

**Inkling**: Run a baseline model on your data and get cracking!
 - Manage your code in a github repository with clear instructions on how to run training and evaluation on your model in the README.md. Your code should be clean and well commented. Make sure that your github repository is public so your TAs can grade your submission.
 - Write an early draft of your report which should contain:
     - Title, Author(s)
     - Introduction
     - Description of your dataset (from I haz the data)
     - Approach: Describe your initial approach including, but not limited to your model, loss functions, and evaluation. 
     - Experiment: Describe methods and results from experiments that you ran. Visualize and analyse sample outputs from your baseline model.
     - Next Steps: Describe what you plan to do next for Milestone 2

**Submission**: Upload your dataset to CS236G’s GCS Bucket. Please find instructions on how to upload here. You should submit your draft on Gradescope as a pdf doc which should not exceed 3 pages. You should paste a url to your public github repository in the Gradescope submission.

**Grading**: This milestone is intended to ensure that your team is on track and has completed a baseline. If you have completed all the bullet points above, you should do well.

## Milestone 2 (***Due 3/7***) - 20%
**Ignition on**: You should have largely implemented the plan you set sail for ⛵️ (or an alternative prospect that you pivoted to).
 - Submit your project’s github repository with clear instructions on how to run training and evaluation on your improved model in the README.md. Your code should be clean and well commented. Make sure that your github repository is public so your TAs can grade your submission.
 - Expand on the early draft of your report from Milestone 1 by drafting the following sections:
     - Related Works: Outline how previous works have tackled technical challenges related to your line of work and how your approach is different (Minimum 5 sources).
     - Method: Outline and discuss the approach you took to improve on your baseline. 
     - Experiments: Describe methods and results from experiments that you ran. Visualize and analyse sample outputs from your improved model.

**Star-gazer**: Describe some highly risky experiments that you plan to perform. The more the merrier! 🤩
    - Outline the method and rationale for your risky experiments at the bottom of the doc

**Submission**: You should submit your draft on Gradescope as a pdf doc which should not exceed 5 pages. Include your risky experiment plan at the bottom of this doc. You should paste a url to your public github repository in the Gradescope submission.

**Grading**: This milestone is intended to ensure that your team is on track and has worked on improving on the baseline. If you have completed all the bullet points above, you should do well.

## Final Report (***Due 3/17***) - 40%
**The Finale**: Finish up your final draft! The project report should be at most 7 pages long and be written using this template. Below are the recommended format and rubric for the report:
 - Title, Author(s)
 - Abstract: Concisely outline the problem, your team’s approach, and findings.
 - Introduction: Outline the problem your team worked on, its significance, and provide an overview of your results.
 - Related Work: Outline how previous works have tackled technical challenges related to your line of work and how your approach is different.
 - Data: Outline the type of data you used, where/how you obtained it, the size of the dataset, the train/validation/test splits, and preprocessing (if any) done on the dataset.
 - Methods: Discuss and describe your approach and justify why it was used over alternate methods. Include diagrams, figures, and tables to delineate your methods.
 - Experiments: Outline the experiments which were performed to evaluate your approach. This could include an ablation study to demonstrate the impact of each of your methods (this is what your baseline is for), a hyper parameter search such as lambda values of loss function components, etc. If you tried to improve an existing model architecture, you could compare your experimental results with those of published works. Include graphs, tables, and figures to show your experimental results. Include the description and results of your risky experiments here! If it went well, congratulations! If it didn’t, that’s okay! Try to rationalize why your experiment may not have succeeded.
 - Conclusion: Summarize your results and what you have learned through your exploration. Mention how your exploration can be extended or applied to other contexts.

**Virtually-famous**: Submit a video no longer than two minutes about your project. Get creative!

**Team Playa**: Equal participation within your pair (N/A if flying solo). This to reduce the case where one person does all the work, and make it a bit easier on an individual. Each partner will fill out a form, outline their own and their partner’s contribution to the project. 

**Don Quixote**: Make sure to include the quixotic experiments that you mentioned in Milestone 2 in your report. This will be weighted heavily as we want to encourage fearless exploration - don’t worry if experiments don’t pan out!

**Submission**: On Gradescope, upload a pdf of the completed final report, submit a url to your video presentation and github repository, and complete the project contribution form.

**Grading**: TBD with heavy weighting on risky experiments.
