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
 - Your dataset will be submitted as part of our course’s “data stash”. If you can't share your data with everyone, no worries! We get really psyched when we have a good stash. 💫
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

**Submission**: Upload your dataset to the [CS236G Data Stash](https://drive.google.com/drive/folders/1HfbARC5vqnJEr52gvCAl7OVvKcVaT8Rj?usp=sharing). Either upload your entire dataset to the Google Drive Folder (if it's a reasonable size) or upload a pdf with a link to the dataset. You should submit your draft to Gradescope as a pdf doc which should not exceed 3 pages. You should paste a url to your public github repository in the Gradescope submission.

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
**The Finale**: Finish up your final draft! The project report should be at most 7 pages long and be written using the [CVPR style template](http://cvpr2020.thecvf.com/sites/default/files/2019-09/cvpr2020AuthorKit.zip).

Below is the recommended format for the report:

- Title, Authors(s)

- Abstract (2 points): Concise summary of the problem, approach, and key results. Less than 300 words.

- Introduction (2 points): Outline the problem your team worked on, its significance, and provide an overview of your results.

- Background/Related Work (8 points): Cover all of background, related works (minimum of 5), and pitfalls (if applicable) in detail.

- Dataset (4 points): Outline the type of data you used, where/how you obtained it, the size of the dataset, the train/validation/test splits, and preprocessing (if any) done on the dataset. Include basic stats, visualizations, and limitations if any.

- Methods (6 points): Discuss and describe your approach and justify why it was used over alternate methods. Methods and approaches should be explained clearly supplemented with equations and diagrams.

- Experiments (8 points): Outline the experiments which were performed to evaluate your approach. This could include an ablation study to demonstrate the impact of each of your methods (this is what your baseline is for), a hyper parameter search such as lambda values of loss function components, etc. If you tried to improve an existing model architecture, you could compare your experimental results with those of published works. Include graphs, tables, and figures to show your experimental results. Include the description and results of your risky experiments here! If it went well, congratulations! If it didn’t, that’s okay! Try to rationalize why your experiment may not have succeeded.

- Analysis (8 points): Make a direct comparison to baselines/previous works and explain your results. Explore the tradeoffs between approaches with theoretical basis.

- Conclusion (3 points):  Summarize your results and what you have learned through your exploration. Address areas for future exploration and research.

Below are some additional rubric items you should be aware of:

- Novelty (3 points): At least 2 of {dataset, model, application} are novel.

- Risky (8 points):
    - Significant implementation risk (eg. multi-gpu training, mixed precision, difficult model implementations, etc.)
    - Signficant conceptual risk (eg. incorporate ideas from distant domains, testing methods unfounded in literature, etc.)
    - Data-related risk (eg. challenging dataset to compile/scrape and clean/preprocess, implemented difficult dataset class like 3D patching, etc.)

- Bonus (3 points):
    - Create an interface for your model.
    - Clean-up your repo significantly and open-source it.
    - Show failed results.
    - Interesting pivot.

**Virtually-famous**: Submit a video no longer than two minutes about your project. Get creative! (6 points)

**Repository**: Your code should be organized and well commented with clear signs of original effort. It would be superb if you could open-source it! (6 points)

**Contributions**: Submit information about individual contributions and project sharing.
- TA Name
- All contributors
- Contributors for this class, if different from above
- Name of other class/group, if applicable
- Individual contributions (please be specific)
- Contributions specific to this class

**Don Quixote**: Make sure to include the quixotic (risky) experiments that you mentioned in Milestone 2 in your report. This will be weighted heavily as we want to encourage fearless exploration - don’t worry if experiments don’t pan out!

**Submission**: On Gradescope, upload a pdf of the completed final report, submit a url to your video presentation and github repository, and complete the project contribution questions.
