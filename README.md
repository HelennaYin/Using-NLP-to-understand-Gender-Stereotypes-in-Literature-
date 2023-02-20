This is a project for Data340: Natural Language Processing

## Introduction
Portrayal of women with gender Stereotypes has been widely found in entertainment and literature. There has been a lot of research and studies discussing gender stereotypes and sexism representations of female characters in media and literature. With the help of natural language processing, now we are able to look at large amounts of literature quickly and accurately, allowing researchers to identify patterns of portrayal of female characters that would be difficult or impossible to discern through manual reading.

The Bechdel test is developed as a simple indicator of whether female characters are portrayed with sexism representations in literary works. To pass the Bechdel test, this piece must feature at least two women who conduct meaningful conversations(conversations such as “Good morning” are not considered meaningful) and their conversations concern something other than men. One may be surprised to find that a vast majority of movie script and literature works cannot pass the Bechdel test. Although the Bechdel test is not deterministic on deciding whether certain works represent women with sexist ideas, it can serve as an indicator of how women are actively present in the story, and thus gives an initial assessment on the female characters portrayal. 

## Objective
The goal of this project is to create a pipeline which takes an input such as a novel/script and tells audiences if it can meet certain standards that are used to evaluate whether the piece portrays women with gender stereotypes and sexist ideas. I am going to use the Bechdel test for this project. NLP algorithms will come in for:\
(i) Determine the gender of speaker\
(ii) Determine if their conversation is meaningful\
(iii) Locate conversations in large chunks of text and the subject who engage in the conversation

## Methods
- Data Source: I will be using movie scripts from the Internet Movie Script Database (https://imsdb.com/)\
- Data Cleaning: The script will be put into formats that pairs each line with character names and their gender\
- Exploratory Data Analysis: tf-idf\
- Train the model to predict gender of the speaker\
- Train the algorithm to determine whether the conversation is meaningful with dependency parsing\
- Write the pipeline 

