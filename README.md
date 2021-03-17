# Poetry Generator for Urdu Language

## Introduction 
This problem falls under the text generation in Natural Language Processing. We are focusing on generating poetry in Urdu Language.

## Data
The data includes 1596 different stanzas in Urdu with variable number of verses.

## Processing
Firstly, I removed all the stop words and noise from the dataset and only kept the meaningful information.
Secondly, I tokenized all the text and generated ```Uni-grams```, ```Bi-grams``` and ```Tri-grams``` and calculated probabilities for each n-gram.
Laslty, I generated verses using the n-grams and their probabilities.
