# Place_Identity_NLP
Code used in the research of Sviblovo district place identity

## Overwiew  
This code is a supplement to the place identity research of Moscow's Sviblovo district, aiming to determine the role of place identity and images of place in the struggle of citizens against the renovation process.  
**The analysis consists of several parts:**
1. acquiring the neccessary data via the API of the Vkontakte social network
2. determining the main themes discussed in the commentaries to the anti-renovation petition subscriptions (the data for this part was gathered manually)
3. determening the main place images and people's asocciations with their district using:  
  3.1. noun chunks with specific dependencies  
  3.2. NER methodology

## Packages used:
* Natasha libarary for NER and noun chunks
* NLTK for stop-words list
* scikitlearn for LDA-based topic modelling
