# Business Problem
Central banks collects information about customer satisfaction with the services provided by different banks. 
It also collects the information about the complaints.<br>
Bank users give ratings and write reviews about the services on central bank websites.
These reviews and ratings help banks evaluate services provided and take necessary action to improve customer service.<br><br>
While ratings are useful to convey the overall experience, they do not convey the context which led a reviewer to that experience.
If we look at only the rating, it is difficult to guess why the user rated the service as 4 stars.
However, after reading the review, it is not difficult to identify that the review talks about good 'service' and 'experience'.

# Objective of Case Study
- Performing Intent analysis
- Find key words (whether positive or negative, in customer feedback)
- Classifying the customer feedback into positive, negative or neutral
- Identify key themes of probelamatic feedback
- Predicting the star rating based on review

## Approach
- Data processing was carried out
-   removing punctuation and stop words
-   Part of speech tagging was done
-   text was cleaned and lemmatized
-   text was vectorized
-  Intent Analysis : Classifying reviews as positive, negative or neutral was carried out using Vader Package
-  Topic Modelling: LDA Model was used on vectorized text to achieve the same
-  Wordcloud is utilized to identify the action verbs and adjectives to get frequent positive/negative words
