<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Final project for the Building AI course

## Summary

The main idea is to create a neural network that will translate the output values of other models to translate them into another language (for example, from English to German). For example, using the GPT-2 model, we trained it into English, now we have to make a new model that will translate the output data for another language with a different dictionary.

Presumably a vector structure will be used where each word will be given a vector. What will help to understand the meaning of words and make them easier to translate


## Background

1. The problem of lack of data, the amount of target text may be different in different languages. For example there are more programming books in English than in Arabic
2. Training. in different languages, if there is a lack of data, the accuracy will be different

## How is it used?

The main users are those who will use GPT like models

## Data sources and AI methods
The data should be taken from a specific subject domain because this will greatly increase the accuracy of the translation

We can use Wiki because it was used for GT-2 content

## Challenges

Limitations in the final result, because the model will be domain-specific, it will be limited in its translation and it will not be able to use words that it does not know about from the training data set

## What next?

This project requires a large domain data set in two different languages

It is necessary to understand how GPT-2 is configured and works
It is necessary to better understand how to create a vector dictionary

## Acknowledgments

https://transformer.huggingface.co
https://openai.com/blog/better-language-models/
