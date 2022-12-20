# Topic_Modelling-for-Amazon_Food_Reviews   
![image](https://user-images.githubusercontent.com/92949677/208638265-119fa2a4-7869-4476-aa38-434926817149.png)

## Introduction 

We encounter such huge texts of documents time and again. But, before reading the documents, if we can get an overview of what the documents are about, it would make the job so much easy. For example, before watching a movie, if we can watch its trailer, it can help us decide if the movie is worth it. Similarly, we can decide if the documents are worth the effort?

In this Project , we will see how to perform topic modelling, like, we have bunch of documents how can we identify each document on their topic.

## Problem  statement 

Amazon has very large number of customer and each day number of people give reviews about the food. So, if someonne wants to read reviews based on thier topic , then it will be very dificult for him, may be to read his review , he has to read all those appeas before it. It might takes a lot time and sometime customer won't able to find the review on their interest which may lead to customer dissatisaction.

## Objective 

As a Data Scientist our objective is to segragate all the reviews based on their topic , so if some customer wants to read review on their interest of topic , they can just click on the topic and can read all the related reviews based on topic.

## LDA in brief?

Latent Dirichilet Allocation is a topic modelling technique that generates topic based on word frequency rom set of documents.

## why we need LDA?

- If I am given 100000 reviews , and I want to read review based on Cost of food , then by making the use of LDA we can read that reviews in no time.

![image](https://user-images.githubusercontent.com/92949677/208642312-6de0c174-3a95-40e4-a4c1-a936fc7474ad.png)

## How do we do LDA?

1. Create collection of documents from the datasets.
2. Each documents represent reviews.
3. Data cleaning is the next step:
   1. Tokenizing - Converting a documents into its elements
   2. Stopping- Removing meaningless words
   3. Stemming - merging words that are equivalent in meanings
4. We will check the frequency of words and from which topic they belong
   

