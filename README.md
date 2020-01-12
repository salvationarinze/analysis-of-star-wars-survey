# Analysis of Star Wars Survey
This is a project carried out during my Data Analysis course on DataQuest

In this project, I worked with Jupyter notebook and analyzing data on the Star Wars movies.
While waiting for Star Wars: The Force Awakens to come out, the team at FiveThirtyEight became interested in answering some questions about Star Wars fans. In particular, they wondered: does the rest of America realize that “The Empire Strikes Back” is clearly the best of the bunch?

The team needed to collect data addressing this question. To do this, they surveyed Star Wars fans using the online tool SurveyMonkey. They received 835 total responses, which you download from their GitHub repository.

For this project, I cleaned and explored the data set in Jupyter notebook. To see a sample notebook containing all of the answers, visit the project's GitHub repository.

We need to specify an encoding because the data set has some characters that aren't in Python's default utf-8 encoding. I read more about character encodings on developer Joel Spolsky's blog.

The data has several columns, including:

    RespondentID - An anonymized ID for the respondent (person taking the survey)
    Gender - The respondent's gender
    Age - The respondent's age
    Household Income - The respondent's income
    Education - The respondent's education level
    Location (Census Region) - The respondent's location
    Have you seen any of the 6 films in the Star Wars franchise? - Has a Yes or No response
    Do you consider yourself to be a fan of the Star Wars film franchise? - Has a Yes or No response

There are several other columns containing answers to questions about the Star Wars movies. For some questions, the respondent had to check one or more boxes. This type of data is difficult to represent in columnar format. As a result, this data set needs a lot of cleaning.
