---
layout: page
title: Data Project
nav_order: 8
description: PDF Links and Assignment Information for the Data Skills Demonstration Project
---

# Data Skills Demonstration Project

### PDF Links 

[Data Skills Demonstration Project Part I](https://ph142-ucb.github.io/su23/src/part1-instructions_su23.pdf) (Due Wed. Jul 19th) 

[Data Skills Demonstration Project Part II](https://ph142-ucb.github.io/su23/src/part2-instructions_su23.pdf) (Due Mon. Jul 31st)

[Data Skills Demonstration Project Part III](https://ph142-ucb.github.io/su23/src/part3-instructions_su23.pdf) (Due Mon. Aug 14th)

**Due dates:** 

- **Part I is due on July 19th at 10pm PST**
- **Part II is due on July 31st at 10pm PST**
- **Part III is due on August 14th at 12pm noon PST**

**Make sure to provide enough time for Gradescope submission to be uploaded if you include large visualizations.**

* Late penalty: 50% late penalty if submitted within 24 hours of due date, no marks for assignments submitted thereafter.

**Submission Process (READ CAREFULLY):**

* Download your PDF from Datahub using the File Viewer on the bottom right panel of RStudio. (More -> Export) 
* Please submit a PDF of your group project to Gradescope here. When turning in each part, please
submit all questions through the current part. For example when turning in Part II, include all
questions from Part I.
* Make sure to add all of your group members to the submission. Only one group member has to submit. Non-submitting group members should confirm that the project submission appears in their gradescope account.  
* Please answer each problem on a new page. You can specify a pagebreak in Rmd using '\\newpage'.
* You must indicate on Gradescope which questions are on which pages. If the page thumbnails make it difficult to see on Gradescope, open the PDF in a PDF viewer at the same time so you can make the selections accurately.
* If the submission guidelines are not followed, we may deduct points, as this creates a logistic burden on our end to have to resolve individual cases.


------- 

## Instructions:

Your task for this project is to find data that is related to health, public health, biology, sociology, demography, justice, or another topic affiliated with public health or biology. The data should have human beings as the unit of analysis, or be based on aggregates of human data (for example rates of mortality) for multiple units of analysis (multiple hospitals/clinics etc).  

These data could be a preexisting data set that has been made publicly available on the Internet, data you have access to (and permission to use) from your lab or internship, or, less frequently, something you create (with appropriate permission) from a hard copy. You will then import your data into R and use it to demonstrate concepts covered in class in three submissions, each focused on one of the three sections of the class:

* Part I: Collecting, Exploring, and Visualizing Data (Based on material in the textbook Edition 4 Chapters 1-8 and early lectures on `dplyr` and `ggplot2`)
* Part II: From Chance to Inference (Edition 4 Chapters 9-16)
* Part III: Statistical Inference (Edition 4 Chapters 17-25 and lectures on bootstrapping and permutation tests)


The objectives of this assignment are to:

* Gain competence finding public health data and reading it into R to perform your own analyses.
* Apply the PPDAC framework to a question of your choosing.
* Develop your ability to choose statistical methods appropriately.
* Demonstrate your newly-acquired statistical skills.
* Demonstrate your ability to communicate statistical analyses and findings.

Because we are asking you to provide some visualizations and use the same dataset for parts II and III of the project, make sure that you choose a dataset with enough  observations (rows) to have something that you can interpret.  Confirm with your supporting GSI that you have an appropriate dataset.  You will also need a dataset large enough so that you can run a statistical test in part III.  A good general guide here is to choose a dataset with at least 100 observations, and at least 30 in each group if you are comparing across groups.  For example, if you are answering a question about mean days in the ICU between groups of patients exposed to some intervention procedure vs. not, you would want to have data on at least 100 patients, at least 30 of which had undergone the intervention and at least 30 of whom had not.  Your outcome of interest should be something that can be defined as a continuous, discrete or binary variable.  

