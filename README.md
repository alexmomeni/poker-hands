# Poker-Hands Dataset

This dataset was created by Robert Cattral and Franz Oppacher in January 2007 with the purpose to predict poker hands. The UCI Machine Learning repository hosts the dataset and Kaggle is running a classficiation competition on its website. 

The dataset description is summarised below: 

Each record is an example of a hand consisting of five playing cards drawn from a standard deck of 52. 

Each card is described using two attributes (suit and rank), for a total of 10 predictive attributes.

There is one Class attribute that describes the “Poker Hand”. 

Suits and ranks are represented as ordinal categories; Poker Hands are classified into ordinal categories. 

The order of cards is important, which is why there are 480 possible Royal Flush hands as compared to 4 (one for a each suit).

# Project objective: Discover the rules of poker

The dataset has been found to be a challenging for classification algorithms. Our project focuses on understanding why this is the case and will make a first attempt to address these obstacles in a classical classifier. More specifically, we will follow the steps below: 

## Discovery of the rules of poker
Can an unsupervised learning algorithm achieve automatic rule induction? 

## Prediction of poker hands
Can the previous analysis help construct a good classifier which can learn the rules without hand coding heuristics ?
