# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1.	In two to three sentences, describe the purpose of your survey
2.	Describe your target population, sampling frame, sampling units, and overall sampling strategy.
3.	Write a 5-10 question survey to address your chosen scenario below.

##### Scenarios
1.	You work in the Human Resources Department at a large tech company. Over the past few months, the company has been experiencing a high turnover rate across many of its departments, specifically within the entry- and lower-level positions. The company wishes to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
2.	You work for a Canadian national political party during a federal election. Throughout the campaign period, your party has seen relatively high approval ratings, but an opposing party is also polling favorably and may still have a chance to win the election. You are one month away from the election and you want to understand what voters want from your party and its leader in order to maintain your lead and eventually win the election.
3.	You are a student researcher in the sociology department at the University of Toronto. You are working on a research project that concerns the relationship between music taste and age. This involves both comparisons between different people of different ages and comparisons of the same individual at different ages during their lifetime. You wish to understand to what extent age influences music taste, specifically as it relates to perceptions of popular music. Your results will be written into an academic paper that you hope to publish.

### Part B - Survey Evaluation:

For the **Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33)**, conducted by Statistics Canada find any and all available documentation for the data gathered and identify and describe the survey features indicated below.

1. Sample type
2. Sample size
3. Target population
4. Sampling frame
5. Survey mode(s) 
6. Timeline
7. Response rate
8. Weights
9. Data processing
10. Cleaning, imputation, etc
11. Sources of error
12. Limitations, known biases, etc
13. Link to documentation and any additional sources used


# Your Changes

## Part A - Survey Design: 

The number of your chosen topic: `1`

Describe the purpose of your survey:
The purpose of my survey is to determine the reason why there is a high turnover rate in lower tier employee positions. Secondarily, this survey aims to determine specifically what employees would want to improve employee satisfaction at the company. 

Describe your target population, sampling frame, sampling units, and observational units:
My target population would be entry and lower level positions in the specific departments that have the highest turnover rates, including those that have left the company (perhaps in the last 6 months or however long this 'high' turnover rate has been happening). The sampling frame would be the employee database. The sampling units would all current emplyees and those that had left while the turnover rate was high. The sampling units would be through email (we are a tech company so I assume they can use email). The observational units would be randomly sampled in a stratified manner from current (and separately) from those that had left. 

Your 5-10 question survey:
```
This survey was inspired by the survey that my undergraduate university recently sent out about alumni satisfaction.
For questions 1-7, rank how you feel about each statement from 1-5, where 1 is strongly disagree and 5 is strongly agree.
1. I feel that I have a good work-life balance. 
2. I recieve adequate support and training to finish my assigned tasks.
3. I am satisfied with the opportunities for career growth and advancement.
4. I feel that adequately compensated for my work.
5. I feel that my work is valued at this company. 
6. I feel comfortable raising concerns to my manager.
7. My coworkers make me feel welcome.
8. What is/was the biggest factor contributing to your decicision to stay at/leave the company? (short answer, open ended)
9. What changes would make you want to stay with the company long term? (short answer, open ended)
10. Do you have any other suggestions to improve our employee experience? (short answer, open ended)
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
1. Sample type: cross-sectional design, stratified sampling at the provincial AND census metro area (CMA).
2. Sample size: 24,000 surveys were expected to be completed. 
3. Target population: Volunteers in the listed CMAs (including Saint John, Montreal, Toronto, etc, full list on site). 
4. Sampling frame: Landline and cellular telephone numbers from the Cencsus and other Stats Canada sources. Numbers were grouped if they were associated with the same address. Aged 15 or older, 1 randomly selected member from any given household. 
5. Survey mode(s): telephone and self-completed via online questionnarie
6. Timeline: for 2018, this survey was administered from September to December.
7. Response rate: 41.9%
8. Weights: Weights were applied via a weighting factor that was applied at the person-level. Bootstrap weights were used.
9. Data processing: I believe I cover this in the rest of the points.
10. Cleaning, imputation, etc: Data was 'cleaned' to check integrity. This included checking birth date with age. imputation was done on the dataset, in 9 steps. These steps included imputing personal and family income, the formal volunteering variables, and variables associated with donation and solicitation methods. 
11. Sources of error: Imperfect coverage (differences in target and sample population, making your survey non-representative of the target population, such as people without a phone or internet) and non-response (people that don't respond to the survey, for example people that have very busy schedules like those with many children will end up missing from the datasets)
12. Limitations, known biases, etc: Those without a phone or internet would not be represented in the survey. Those from the same dwelling would not be surveyed, which could induce or remove bias depending on how you look at it. 
13. Link to documentation and any additional sources used: https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&amp;SDDS=4430, https://www23.statcan.gc.ca/imdb/p3Instr.pl?Function=assembleInstr&a=1&&lang=en&Item_Id=1183690 
```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 18/04/2025`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
