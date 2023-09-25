# Fake News Detection and Text Analysis: A Natural Language Processing Project

Assignment Overview:
The assignment involves analyzing a dataset containing fake news and real news articles using techniques learned in the course. The dataset used is the ISOT Fake News Dataset, which includes articles collected from Reuters.com (real news) and various sources flagged by Politifact and Wikipedia (fake news). There are approximately 12,600 articles in total, saved in two CSV files: "True.csv" and "Fake.csv." Each article includes information such as the title, text, type, and publication date.

**Tasks:**

**Data Extraction and Pre-processing:**

Write Python code to extract text data from both CSV files ("True.csv" and "Fake.csv").
Apply pre-processing tasks to the text data. This may include tasks like tokenization, lowercase conversion, stop word removal, or lemmatization. The rationale for the chosen pre-processing options should be explained in a Jupyter Notebook file.

**Data Analysis:**

Perform data analysis on the pre-processed text data, including both real and fake news articles.
List the top 50 stop words by frequency in fake news articles and real news articles.
List the top 50 content words by frequency in fake news articles and real news articles.
List the top 50 bigrams by frequency in fake news articles and real news articles.
List the top 50 bigrams by their Mutual Information scores (using a minimum frequency of 5) in fake news articles and real news articles.
List the top 50 adjective words in fake news articles and real news articles.


For each article, calculate and record various statistics:
including the total number of words, total number of content words, total number of words that are all capitalized (excluding "I"), total number of exclamation marks, and total number of punctuation marks. Save this information in CSV files by creating new columns.


**Interpretation of Results:**

Compare the analysis results between true news articles and fake news articles.
Provide explanations for any patterns or differences observed in the results. For example, discuss whether they tend to have a similar ratio of capitalized words.
Conduct additional analyses that help understand the results.

**Submission Requirements:**

Submit the Jupyter Notebook file with code and comments.
Ensure that the code is run, and results are displayed.
Name variables thoughtfully to make it intuitive for readers to understand the code's logic.
Include text blocks that describe the data pre-processing tasks and interpret the analysis results.
Submit two revised CSV files containing the analysis results.
