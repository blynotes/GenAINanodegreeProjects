# Udacity Generative AI Nanodegree - Project 2

## Overview
* My dataset is the Star Wars Characters from Wikipedia
* I wrangled the data into a good format for this project by putting the character names and the character description separated by a " => ".
* Created the embeddings using `text-embedding-ada-002` model
* Found the cosine similarity and cosine distances
* Created a prompt using tiktoken to make sure I did not exceed the token limits
* Leveraged `gpt-3.5-turbo-instruct` to answer my question both with and without the custom prompt
* Asked 2 questions that show the custom prompt helped improve accuracy of question relating to my dataset.
* Created an interactive question/answering cell using a `while` loop and `input`.  I asked 5 additional questions that further show the benefit of the custom prompt.

## Resources Used
* Udacity Generative AI Nanodegree Course 2 lesson materials