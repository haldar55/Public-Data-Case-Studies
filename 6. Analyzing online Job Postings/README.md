# Business Objectives
Our main business objectives are to understand the dynamics of the labour market of Armenia using
the online job portal post as a proxy.<br>
A secondary objective is to implement advanced text analytics
as a proof of concept to create additional features such as enhanced search function that can add
additional value to the users of the job portal.

## Some Business Question to be answered
- **Job Nature and Company Profiles:** What are the types of jobs that are in demand in Armenia? How
are the job natures changing over time?
- **Desired Characteristics and Skill-Sets:**
What are the desired characteristics and skill-set of the candidates based on the job description
dataset? How these are desired characteristics changing over time?
- **IT Job Classification:** Build a classifier that can tell us from the job description and company
description whether a job is IT or not, so that this column can be automatically populated for new
job postings. After doing so, understand what important factors are which drives this classification.
- **Similarity of Jobs:** Given a job title, find the 5 top jobs that are of a similar nature, based on the job
post.

## Approach
- Data processing
- Topic Modelling utilized to answer the types of job available
- Clustering to identify the desired Skill sets
- Classification using Multinomial Naive Bayes classifier to identify IT Jobs
- Utilized Cosine Similarity on the TF-IDF model to identify similar jobs
