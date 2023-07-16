# retrieve-and-summarization
Building AI Course Project - Take A Stand
# Take A Stand - Retrieve and Summarize

Final project for the Building AI course

## Summary

Retrieve the most SEO efficient information from Google and have it summarized to a length variation of your choice. With this model, yoc can gain brief information on any topic - to allow you form an opinion!


## Background
Researching on a broad topic can be quite difficult. With this model, anyone can get the key points on any topic. It can be used for assignments and research purposes. My motivation for this project was to enable people get brief and credible summaries of broad topics.




## How is it used?
How It Is Used


*Input your topic of choice in the model's search bar. 


*In the next search bar, input how long you would like your summarization to be (from a range of 0 to 1).


*The AI model will then retreive information from the top results and use deep learning techniques to give an effective summarization

![image](https://github.com/XSTACYYY/retrieve-and-summarization/assets/138307115/c679fe1f-5e57-412f-8be7-8a07a3357f98)


Code Demo:
from googlesearch import search
from bs4 import BeautifulSoup
import requests
import spacy
from spacy.lang.en.stop_words import STOP_WORDS
from string import punctuation
from heapq import nlargest


#This allows the user to input a search or query
query = input("Enter the text to search: ")

#Summarization code
-------------------------

## Data sources and AI methods
https://www.google.com/

## Challenges

*It does not give expertly detailed information - only a brief summary


*Due to it still being a demo, summarizations may include more than one case of repitition

## What next?
With further improvement, the model could include more domains, such as ones more credible for academic research. It could also become more effective in summarization to produce the best possible result

## Acknowledgments
SpaCy Summarization Technique: https://www.activestate.com/blog/how-to-do-text-summarization-with-python/
Summarization Image Used: https://thecleverprogrammer.com/2020/12/31/text-summarization-with-python/
