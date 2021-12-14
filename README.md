# Chatbot
![ChatBoat](https://github.com/Ashlesha8421/Chatbot/blob/Ashlesha_Datir/ChatBot_GIF.gif)

# Business Problem :
Unavailability of chat option to get your data science interview questions with your answers, for a one step solution on your seeking Data Science interview answers for your questions

# Objective :
To create a Chat bot for providing seamless responses to Data Science interview questions with an appropriate answer

# What is Chatbot?
* -- A chatbot is a computer program governed by a set of pre-defined rules or artificial intelligence that grants it the capabilities to communicate with and like a human.
* -- A set of commands is fed into the system that makes it smart enough to interpret and react to user-inputted queries.

# PLANNING :
- Understanding Business problem & objective
- Defining Scope & Methodology
- Data gathering (“Web Scarping”)
- Text Pre-processing on data
- EDA
- Model Building
- Model Evaluation
- Model Deployment (GUI)
## SCOPE :
## Chatbot Name:- “Sarthi”
- Forming conversation using text only.
- Based on limited Topics in Data Science such as Supervise Learning and general.
- We have collected about 700+ Questions and Answers by web scraping.
- We are going with Rule-Based(Retrieval)Chatbot.
# CHATBOT METHODOLOGY :
- Defining the Chatbot’s Purpose and Managing Expectations

- Defining the Chatbot’s Personality( assist)

- Designing the User Journey and Conversation

- Testing


## DATASET :
The data(.csv) which we have extracted/Scraped from many websites.

The dataset mainly contains 2 columns which are Questions and Answers.

## TEXT PRE PROCESSING and EDA :
I performed EDA and visulization on the dataset such as tokenisation,normalisation,removing stop words,stemming,limatisation.

I did visulization using Wordcloud check the relation of the words using bi-grame and tri-gram

After performing all the EDA and Pre Processing methods the dataset with a new column as question clean.

## MODEL BUILDING :
We have extracted important word from “Question” and “User input”.
we had created strings of important word for both.
we find the similarity between these strings and for that we had used “Ratio” method.
we had considered only those which had more than 0.90 similarity score.

# Deployment (GUI) 

## DEPLOYMENT :
The deployement of chatbot is been done in GUI to make it more interactive.

## CHALLENGES FACED
- 1.Not all websites/local browsers are giving the permission to scrap their data. 
- 2.Even after scraping the data form websites we got lot of unwanted text/data which is not useful for us.

## OVERCAME BY
For permission issue we have used header agent to get permission from our local browsers.
For next issue we have used the source code the websites and only selected the tags of the data which we want to scrap.

## Business benifit:-
In furture we will be adding or trying to cover most of the topices in our chatbot we will be building chatbot into .exe file so that it can be used in offline as well.


