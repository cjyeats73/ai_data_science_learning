# ai_data_science_learning

## Overview
This repository is a learning assignment where I attempted to recreate an example notebook by prompting a large learning AI to create code snippets for me. 

This notebook evaluates card transaction data. It does some basic exploratory data analysis and uses some basic machine learning models to predict card fraud.

## Reflection
AI can be a very useful tool when you know what you want the AI to do specifically. Specifically, it's great at knowing which functions and libraries I wanted to use. Also, if you got the "Plus" version of ChatGPT you could have it store each new piece of code you create within it. You could theoretically just download the whole file and have it up and running in seconds.

However, I begin to wonder if it's even worth it, since it took me the exact same time, if not longer, to get the AI to do exactly what I wanted it to do. At a certain point, I feel like using AI to generate one piece of code and then just copy/pasting the code over and over again and using it as a template would have been easier.

I feel like this would be even difficult if I had no clue what I wanted the AI to make me. If one doesn't know exactly what they're looking for, they would end up making incredibly general prompts, which leave a lot of room for confusion. A good example of this is if I typed "Create a histogram titled 'Title'." This is way too general, you need to put data in to actually get results. As an AI is still a computer, it will do **exactly** what you tell it to. It will also find the cheapest solution to such problems, which might not be what the prompter wants. If we wanted a histogram with 50 bins specifically, but never specify it, the AI will give a standard answer of 30 bins.

I checked every snippet of code I recieved from the AI to see if it worked as intended. I think that just checking all the code you recieve from AI is a good practice, since even one miswording can shift the results you're looking for entirely. For example, when picking a random seed for the train_test_split function for the machine learning part of this assignment, I forgot to specify the function to stratify the data. This made it so that my results for the k-NN data were slightly different from the example workbook.