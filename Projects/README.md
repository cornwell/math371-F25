# Fall 2025, Final Project

## Overview
The final project will give you the opportunity to analyze the data in the [class ``Reservoirs'' repository](https://github.com/cornwell/reservoir-data), data which is related to physical and chemical properties of the water found in the Liberty, Loch Raven, and Prettyboy reservoirs in the Chesapeake Bay watershed. Your analysis should use either regression or classification model(s) that we have discussed and take into account considerations such as statistical significance of variables and controlling overfitting. The projects are to be submitted on an individual basis; however, it is hoped that you will have discussions with other students and that this will provide opportunities to learn from each other.

You may choose either a regression task or a classification task. Depending on the specific task, and which part of the data used, the goals of your project may vary somewhat.

## Stages of the Project
1. Consider possible questions about the Reservoir data and select a machine learning task that might provide insight to that question. What hypothesis do you have about the data? (**By November 20, or before**)
2. Start the work to gather and clean your data from the larger dataset. Separate your data into training data and test data subsets. (The test data should never get used during the fitting process.) Make appropriate choices and work on fitting an appropriate machine learning model to the data. Consider your results and possible interpretations. (**Should be complete or near completion by Dec 4.**)
3. Make an appointment to briefly discuss your progress and results with Dr. Cornwell. (**Appointment should occur betweeen Dec 3 and Dec 8.**)
4. A final presentation. (**On Tuesday Dec 9 between 12:30 and 2:30 pm.**)


## Write-up and Project Presentations
Each student will turn in a write-up on their project. This should include a two-page summary and a Jupyter notebook with any relevant code. The write-up should be a PDF file and may include one or two key figures, but should mostly be text.

The write-up should include: 
* a discussion of the question being addressed, information about which data is used (_e.g._, is it only data from tributaries running into the Prettyboy reservoir?), and what steps were taken to process that data; 
* a discussion of the machine learning model being used for the task;
    * which model is it, what cost function was used for optimizing and why that cost function for your task? 
    * what choices were made in order to avoid overfitting?
    * were some of the initial features excluded after being found not significant, and what method was used to make such a decision?
* results of the model's performance on test data; 
* any summary or insights gained &ndash; is there a ``take-away'' of interest? 
* were there difficulties, and how might those be resolved in the future?

## Deadline: Tuesday, Dec 9.

## Evaluation Criteria
Projects will be assessed based on the following.
1. The data being thoroughly explored and understood.
2. Proper implementation, training, and use of your machine learning model. This includes appropriate separation between training and test data, and the use of techniques to avoid using too many parameters or overfitting the data.
3. Clarity and organization submitted documents.
4. A short final presentation on the results.

A grading rubric will be made available in Blackboard.