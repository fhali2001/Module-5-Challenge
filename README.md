# Matplotlib Challenge

## What good is data without a good plot to tell the story?

In this assignment, you’ll apply what you've learned about Matplotlib to a real-world situation and dataset.

## Background
You've just joined Pymaceuticals, Inc., a new pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The executive team has tasked you with generating all of the tables and figures needed for the technical report of the clinical study. They have also asked you for a top-level summary of the study results.

## Files
Download the following files to help you get started:
- [Module 5 Challenge files](https://static.bc-edx.com/data/dl-1-2/m5/lms/starter/Starter_Code.zip)

## Instructions
This assignment is broken down into the following tasks:

1. Prepare the data.
2. Generate summary statistics.
3. Create bar charts and pie charts.
4. Calculate quartiles, find outliers, and create a box plot.
5. Create a line plot and a scatter plot.
6. Calculate correlation and regression.
7. Submit your final analysis.

## Requirements
**Prepare the Data (20 points)**
- The datasets are merged into a single DataFrame. (6 points)
- The number of mice are shown from the merged DataFrame. (2 points)
- Each duplicate mice is found based on the Mouse ID and Timepoint. (6 points)
- A clean DataFrame is created with the dropped duplicate mice. (4 points)
- The number of mice are shown from the clean DataFrame. (2 points)

**Generate Summary Statistics (15 points)**
- The mean of the tumor volume for each regimen is calculated using groupby. (2 points)
- The media of the tumor volume for each regimen is calculated using groupby. (2 points)
- The variance of the tumor volume for each regimen is calculated using groupby. (2 points)
- The standard deviation of the tumor volume for each regimen is calculated using groupby. (2 points)
- The SEM of the tumor volume for each regimen is calculated using groupby. (2 points)
- A new DataFrame is created with using the summary statistics. (5 points)

**Create Bar Charts and Pie Charts (15 points)**
- A bar plot showing the total number of timepoints for all mice tested for each drug regimen using Pandas is generated. (4.5 points)
- A bar plot showing the total number of timepoints for all mice tested for each drug regimen using pyplot is generated. (4.5 points)
- A pie plot showing the distribution of female versus male mice using Pandas is generated. (3 points)
- A pie plot showing the distribution of female versus male mice using pyplot is generated. (3 points)

**Calculate Quartiles, Find Outliers, and Create a Box Plot (30 points)**
- A DatFrame that has the last timepoint for each mouse ID is created using groupby. (5 points)
- The index of the DataFrame is reset. (2 points)
- Retrieve the maximum timepoint for each mouse. (2 points)
- The four treatment groups, Capomulin, Ramicane, Infubinol, and Ceftamin, are put in a list. (3 points)
- An empty list is created to fill with tumor volume data. (3 points)
- A for loop is used to display the interquartile range (IQR) and the outliers for each treatment group (10 points)
- A box plot is generated that shows the distribution of the final tumor volume for all the mice in each treatment group. (5 points)

**Create a Line Plot and a Scatter Plot (10 points)**
- A line plot is generated that shows the tumor volume vs. time point for one mouse treated with Capomulin. (5 points)
- A scatter plot is generated that shows average tumor volume vs. mouse weight for the Capomulin regimen. (5 points)

**Calculate Correlation and Regression (10 points)**
- The correlation coefficient and linear regression model are calculated for mouse weight and average tumor volume for the Capomulin regimen. (10 points)

## Grading
This assignment will be evaluated against the requirements and assigned a grade according to the following table:

Grade	Points
A (+/-)	90+
B (+/-)	80–89
C (+/-)	70–79
D (+/-)	60–69
F (+/-)	< 60

## Submission
Review all the figures and tables that you generated in this assignment. Write at least three observations or inferences that can be made from the data. Include these observations at the top of your notebook.

To submit your Challenge assignment, click Submit, and then provide the URL of your GitHub repository for grading.

**NOTE:** You are allowed to miss up to two Challenge assignments and still earn your certificate. If you complete all Challenge assignments, your lowest two grades will be dropped. If you wish to skip this assignment, click Next, and move on to the next module.

## IMPORTANT
It is your responsibility to include a note in the README section of your repo specifying code source and its location within your repo. This applies if you have worked with a peer on an assignment, used code in which you did not author or create sourced from a forum such as Stack Overflow, or you received code outside curriculum content from support staff such as an Instructor, TA, Tutor, or Learning Assistant. This will provide visibility to grading staff of your circumstance in order to avoid flagging your work as plagiarized.

If you are struggling with a challenge assignment or any aspect of the academic curriculum, please remember that there are student support services available for you:

- Ask the class Slack channel/peer support.
- AskBCS Learning Assistants exists in your class Slack application.
- Office hours facilitated by your instructional staff before and after each class session.
- Tutoring Guidelines - schedule a tutor session in the Tutor Sessions section of Bootcampspot - Canvas

If the above resources are not applicable and you have a need, please reach out to a member of your instructional team, your Student Success Advisor, or submit a support ticket in the Student Support section of your BCS application.

## Hints and Considerations
- Use the code comments in the provided starter file to guide you through this assignment.
- Use proper labeling for your plots. Include plot titles, axis labels, legend labels, x-axis and y-axis limits, etc.
- As you work on this assignment, refer to Stack Overflow and the Matplotlib documentation for guidance. These are essential tools in every data analyst's tool belt.
- Remember that there are many ways to approach a data problem: One way is to break up your task into micro tasks. For example, ask yourself questions like the following:
  - How does my DataFrame need to be structured so it has the correct x-axis and y-axis?
  - How do I build a basic scatter plot?
  - How do I add a label to a scatter plot?
  - Where in the DataFrame can I find the names that will go into the labels?
- Get help when you need it! Your instructional team is there for you.

## References
Data generated by MockarooLinks to an external site., LLC (2022). Realistic Data Generator.
