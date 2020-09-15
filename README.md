# Phase 2 Project

## Introduction

In this lesson, we review the guidelines for the Phase 2 Project.

## Objectives

You will be able to:

* Start your Phase 2 Project
* Check that your project meets the requirements
* Submit your project materials in Canvas
* Prepare for your project review

## Project Overview

Another module down--you're almost half way there!

![awesome](https://raw.githubusercontent.com/learn-co-curriculum/dsc-phase-2-project-online/master/halfway-there.gif)

All that remains in Phase 2 is to put our newfound data science skills to use with a large project! You should expect this project to take between 20 and 25 hours of solid, focused effort. If you're done way quicker, go back and dig in deeper or try some of the optional "level up" suggestions. If you're worried that you're going to get to 30 hrs and still not even have the data imported, reach out to an instructor in Slack ASAP to get some help!

### The Data

For this project, you'll be working with the King County House Sales dataset. We've modified the dataset to make it a bit more fun and challenging.  The dataset can be found in the file `kc_house_data.csv` in the data folder in this repo.

The description of the column names can be found in the `column_names.md` file in the data folder in this repo. As with most real world data sets, the column names are not perfectly described, so you'll have to do some research or use your best judgment if you have questions relating to what the data means.

You'll clean, explore, and model this dataset with a multivariate linear regression to predict the sale price of houses as accurately as possible.

### Business Problem

For this project, it will be up to you to define a stakeholder and business problem appropriate to this dataset.

## Deliverables

There are four deliverables for this project:

1. A **GitHub repository**
2. A **Jupyter Notebook**
3. A non-technical presentation **slide deck**
4. A non-technical presentation **recording**

Keep in mind that the audience for these deliverables is not only your teacher, but also potential employers. Employers will look at your project deliverables to evaluate multiple skills, including coding, modeling, communication, and domain knowledge. You will want to polish these as much as you can, both during the course and afterwards.

### GitHub Repository

Your GitHub repository is the public-facing version of your project that your instructors and potential employers will see - make it as accessible as you can. At a minimum, it should contain all your project files and a README.md file that summarizes your project and helps visitors navigate the repository.

### Jupyter Notebook

Your Jupyter Notebook is the primary source of information about your analysis. At a minimum, it should contain or import all of the code used in your project and walk the reader through your project from start to finish. You may choose to use multiple Jupyter Notebooks in your project, but you should have one that provides a full project overview as a point of entry for visitors.

For this project, your Jupyter Notebook should meet the following specifications:

#### Organization/Code Cleanliness

* The notebook should be well organized, easy to follow,  and code should be commented where appropriate.  
    * Level Up: The notebook contains well-formatted, professional looking markdown cells explaining any substantial code.  All functions have docstrings that act as professional-quality documentation
* The notebook is written for technical audiences with a way to both understand your approach and reproduce your results. The target audience for this deliverable is other data scientists looking to validate your findings.

#### Visualizations & EDA

* Your project contains at least 4 meaningful data visualizations, with corresponding interpretations. All visualizations are well labeled with axes labels, a title, and a legend (when appropriate)  
* You pose at least 3 meaningful questions and answer them through EDA.  These questions should be well labeled and easy to identify inside the notebook.
    * **Level Up**: Each question is clearly answered with a visualization that makes the answer easy to understand.   
* Your notebook should contain 1 - 2 paragraphs briefly explaining your approach to this project.

#### Model Quality/Approach

* Your model should not include any predictors with p-values greater than .05.  
* Your notebook shows an iterative approach to modeling, and details the parameters and results of the model at each iteration.  
    * **Level Up**: Whenever necessary, you briefly explain the changes made from one iteration to the next, and why you made these choices.  
* You provide at least 1 paragraph explaining your final model.   
* You pick at least 3 coefficients from your final model and explain their impact on the price of a house in this dataset.   

### Non-Technical Presentation Slides and Recording

Your non-technical presentation is your opportunity to communicate clearly and concisely about your project and it's real-world relevance. The target audience should be people with limited technical knowledge who may be interested in leveraging your project. For Phase 1, these would be Microsoft executives interested in making decisions about movie development.

Your presentation should:

* Contain between 5 - 10 professional-quality slides.  
    * **Level Up**: The slides should use visualizations whenever possible, and avoid walls of text.
* Take no more than 5 minutes to present.   
* Avoid technical jargon and explain the results in a clear, actionable way for non-technical audiences.

**_Based on the results of your models, your presentation should discuss at least two concrete features that highly influence housing prices._**

We recommend using Google Slides, PowerPoint or Keynote to create your presentation slides. We recommend using Zoom to record your live presentation to a local video file ([instructions here][]) - other options include Quicktime, PowerPoint, or Nimbus. Video files must be under 500 MB and formatted as 3GP, ASF, AVI, FLV, M4V, MOV, MP4, MPEG, QT, or WMV.

## Getting Started

Please start by reviewing this document. If you have any questions, please ask them in Slack ASAP so (a) we can answer the questions and (b) so we can update this document to make it clearer.

**When you start on the project, reach out to an instructor immediately via Slack to let them know and schedule your project review.** If you're not sure who to schedule with, please ask in your cohort channel in Slack.

Once you're done with the numbered topics in Phase 1, please start on the project. Do that by forking [the Phase 2 Project Repository][], cloning it locally, and working in the `student.ipynb` file. Make sure to also add and commit a PDF of your presentation to your repository with a file name of `presentation.pdf`.

## Project Submission and Review

Review [the Phase Project Submission and Review guidance][] to learn how to submit your project and how it will be reviewed. Your project must pass review for you to progress to the next Phase.

**Please note: We need to receive your complete submission at least 24 hours before your review to confirm that you are prepared for the review. If you wish to revise your submission, please do so no later than 3 hours before your review so that we can have time to look at your updated materials.**

## Summary

The end-of-phase projects and project reviews are a critical part of the program. They give you a chance to both bring together all the skills you've learned into realistic projects and to practice key "business judgement" and communication skills that you otherwise might not get as much practice with.

The projects are serious and important - they can be passed and they can be failed. Take the project seriously, put the time in, ask for help from your peers or instructors early and often if you need it, and treat the review as a job interview and you'll do great. We're rooting for you to succeed and we're only going to ask you to take a review again if we believe that you need to. We'll also provide open and honest feedback so you can improve as quickly and efficiently as possible.

[the Phase 2 Project Repository]: https://github.com/learn-co-curriculum/dsc-phase-2-project-online
[instructions here]: https://support.zoom.us/hc/en-us/articles/201362473-Local-recording
[the Phase Project Submission and Review guidance]: https://github.com/learn-co-curriculum/dsc-project-submissions-online
