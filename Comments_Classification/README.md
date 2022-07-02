# Comments Classification

## Project Description

The online store launches a new service. Now users can edit and supplement product descriptions, just like in wiki communities. The store needs a tool that will look for toxic comments and submit them for moderation. At your disposal is a dataset with markup on the toxicity of edits.

## Goals

* Train the model to classify comments as positive or negative. 
* Build a model with a quality metric F1 value of at least 0.75.


## Data

* text — users comments;
* toxic — is comment toxic or not.

## Libraries used

- pandas
- numpy
- torch
- nltk
- transformers
- sklearn
- catboos
- bert
- pickle
- tqdm
