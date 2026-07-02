# Impact of Generative AI on Students: A Python Course Application

## Project Overview

This project was developed as part of a Python course to practise and apply Python programming skills. It analyses the relationship between Generative AI use and student outcomes. The objective is to examine whether the number of hours students spend using AI is associated with academic performance, skill retention, anxiety, and burnout risk.

## Dataset

The project uses a student-level dataset from Kaggle: *AI Impact on Students*. The data include information on students' academic background, AI usage, study habits, institutional policy, and well-being indicators.

## Main Variables

The main explanatory variable is:

- `Weekly_GenAI_Hours`

The main outcomes are:

- `Post_Semester_GPA`
- `Skill_Retention_Score`
- `Anxiety_Level_During_Exams`
- `Burnout_Risk_Level`

Control variables include:

- `Pre_Semester_GPA`
- `Major_Category`
- `Year_of_Study`
- `Traditional_Study_Hours`
- `Prompt_Engineering_Skill`
- `Tool_Diversity`
- `Paid_Subscription`
- `Institutional_Policy`

## Methodology

The analysis uses descriptive statistics and regression models to study the relationship between weekly AI usage and student outcomes while controlling for academic, demographic, and institutional characteristics.

## Preliminary Findings

The preliminary results suggest that:

- Weekly AI usage does not show a clear relationship with post-semester GPA.
- Weekly AI usage deteriorate skill retention.
- Weekly AI usage appears to be associated with burnout risk.
- The results should be interpreted as associations, not causal effects.

## Repository Structure

```text
CODE/          Python notebooks and scripts
DATA/          Dataset
Presentation/  Project presentation files
README.md      Project description
