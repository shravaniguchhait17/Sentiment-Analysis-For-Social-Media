# Sentiment-Analysis-For-Social-Media

The advent of social media has revolutionized communication, connecting people worldwide and granting instant access to vast amounts of information. However, along with this wealth of knowledge comes a spectrum of opinions, ranging from positive to negative, on various topics. Unfortunately, the anonymous nature of online platforms has given rise to bullying and the proliferation of hateful comments targeted at individuals or subjects.

This project analyses the sentiments of the user's tweets and classifies them as positive or negative using predictive analytics.

**Cleaning Data:**

<img width="573" alt="image" src="https://github.com/shravaniguchhait17/Sentiment-Analysis-For-Social-Media/assets/84240264/6dc68d50-4ddd-4f3d-909a-1f2ea9742b1d">

**Removing Punctuations, numbers and special characters:**

<img width="548" alt="image" src="https://github.com/shravaniguchhait17/Sentiment-Analysis-For-Social-Media/assets/84240264/dbdf7987-3c75-49f2-aae1-9453a12cb741">

**Removing short words:**

<img width="558" alt="image" src="https://github.com/shravaniguchhait17/Sentiment-Analysis-For-Social-Media/assets/84240264/a7940195-721c-4f53-9bf7-2de2d3bdab64">

**Tokenizing the cleaned tweets:**

<img width="335" alt="image" src="https://github.com/shravaniguchhait17/Sentiment-Analysis-For-Social-Media/assets/84240264/2991289b-b97f-4380-9c50-a910e55737f0">

**Stemming (Step-based process of stripping the suffixes ("ing","ly",etc.) from a word):**

<img width="345" alt="image" src="https://github.com/shravaniguchhait17/Sentiment-Analysis-For-Social-Media/assets/84240264/307bd06b-00a6-4126-b4bd-6e305cf4a655">

**Combining the data back:**

<img width="775" alt="image" src="https://github.com/shravaniguchhait17/Sentiment-Analysis-For-Social-Media/assets/84240264/4ed32207-0026-4712-91b4-12b1a68fba0d">

**Visualize the data using WordCloud for storing all the non-sexist/racist words and for storing sexist/racist words:**

![image](https://github.com/shravaniguchhait17/Sentiment-Analysis-For-Social-Media/assets/84240264/88236378-f234-4efb-a441-d26265694b88)

![image](https://github.com/shravaniguchhait17/Sentiment-Analysis-For-Social-Media/assets/84240264/376ce5a3-c5d6-44ff-bcb2-5b1c97126ad1)

**Extracting hastags from tweets:**

<img width="429" alt="image" src="https://github.com/shravaniguchhait17/Sentiment-Analysis-For-Social-Media/assets/84240264/052861db-b956-46ae-a671-5a473b5d23f5">

**Now unnesting the list:**

<img width="199" alt="image" src="https://github.com/shravaniguchhait17/Sentiment-Analysis-For-Social-Media/assets/84240264/c2a8e852-2001-4cae-a454-36978c7e4cfc">

**Positive word frequency:**

<img width="877" alt="image" src="https://github.com/shravaniguchhait17/Sentiment-Analysis-For-Social-Media/assets/84240264/0cdec18b-f96a-4730-a637-fa182a774b7d">

**Creating a dataset of the most frequent words:**

<img width="177" alt="image" src="https://github.com/shravaniguchhait17/Sentiment-Analysis-For-Social-Media/assets/84240264/0ce05d12-f456-432e-9c77-ef7a7acfc2ee">

**Plotting the bar plot for 20 most frequent words:**

<img width="530" alt="image" src="https://github.com/shravaniguchhait17/Sentiment-Analysis-For-Social-Media/assets/84240264/d7e40479-b4ad-4587-b943-18a8037e6e46">

**Negative Word Frequency:**

<img width="885" alt="image" src="https://github.com/shravaniguchhait17/Sentiment-Analysis-For-Social-Media/assets/84240264/19bc3689-5bb8-41ee-8046-8e6f7f3be87c">

**Creating a dataset of the most frequent words:**

<img width="195" alt="image" src="https://github.com/shravaniguchhait17/Sentiment-Analysis-For-Social-Media/assets/84240264/625c82e3-4b2d-417f-a16c-69c8de2595d1">

**Plotting the bar plot for the 20 most frequent negative words:**

<img width="491" alt="image" src="https://github.com/shravaniguchhait17/Sentiment-Analysis-For-Social-Media/assets/84240264/5dfec5d1-b9ee-42c9-8a2c-7eeb3136f44b">

**Feature Extraction from Cleaned Tweets using CountVectorizer (converting text data into numerical format for machine learning tasks):**

<img width="566" alt="image" src="https://github.com/shravaniguchhait17/Sentiment-Analysis-For-Social-Media/assets/84240264/c16d56bd-92ab-4e73-b8fe-85b7073234b1">

**Applying ML Models:**
**Logistic Regression**
**Results after prediction:
For a negative label : 1
For a positive label : 0**

<img width="145" alt="image" src="https://github.com/shravaniguchhait17/Sentiment-Analysis-For-Social-Media/assets/84240264/57b9be26-eacc-4762-8bfb-03116a628c13">
