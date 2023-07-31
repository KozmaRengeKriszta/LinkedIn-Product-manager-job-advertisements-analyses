# LinkedIn "Product manager" job advertisements analyses
A data science project about analyzing datas from **LinkedIn's Product Manager job advertisements**. Based on my analyses, a blog post will be prepared soon, which can be read by clicking on »» this link ««

This is my first text analytics analysis. I felt that I would be able to do all the steps I wanted in Python. So I used Python for everything from text cleaning to more complex AI analysis.

The first notebook contains the **codes used to clean the text**. The datas had to be collected from 5 csv files (which we scraped from LinkedIn using a program called PhantomBuster) and then get rid of unnecessary information (columns, duplicated rows and those rows that didn't even contain a product manager job advertisement)

The second notebook contains the **codes used to basic analyses** - information about companies, type of workplace and employment, define seniority level based on LinkedIn classification, some information about advertisements.

The next 4 notebooks contains the codes used to more complex analyses **to define seniority level / expected salary / expected education and certifications / language skills** based on the job descriptions. In these analyses I first used the **NLTK module** to process the text. Then I also performed analyzes with the help of **openAI API** for the sake of interest and clarification. First, I asked the AI ​​to extract relevant information from the text of job advertisements. Then I further analyzed this collected text using **chatGPT** (I made a description of the steps at these end of the codes).

The last 3 notebooks contains the codes used to more complex analyses **to define benefits and perks / expected soft skills / main tasks of applicants** based on the job descriptions. In these analyses I couldn't used the NLTK module anymore, because the job advertisements already used very different wording on these topics - so keywords no longer worked. So I performed analyzes with the help of **openAI API**. Again: first, I asked the AI ​​to extract relevant information from the text of job advertisements. Then I further analyzed this collected text using **chatGPT** (I made a description of these steps at the end of the codes).

It was a very exciting task and I am proud that I managed to extract so much useful information from the datas. I will definitely take the time to get to know more text analysis tools (for example LDA topicmodeling or spaCy library) so that I can prepare even better analyzes in the future.
