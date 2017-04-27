# NUIG-sentiment
A sentiment predictor for tweets. Uses LSTM neural networks and pre-trained Glove word representations.

## REQUIREMENTS

This package requires python3.5, rest of the requirements are listed in the requirement file.
Read the separate readme provided in the "embeddings" and "savedModels" folders.

The embeddings need to be downloaded from here: 
http://nlp.stanford.edu/projects/glove/, download glove.6B.zip. Open the zipped file and use the embeddings of with 200 dimensions.

## INSTALLATION

Run: 
sentimentAPI.py

## USAGE

Type http://0.0.0.0:5000/text in your browser, where text can be a sentence or a tweet. 
The service should return 'positive', 'negative', or 'neutral'

## CREDITS (citations if available)

The neural network based classifier has been implemented using the deep learning library KERAS [site](https://keras.io).
Trained on flattened sentiment treebank dataset: https://nlp.stanford.edu/sentiment/ (Socher et al. 2013)

## ACKNOWLEDGEMENT

This development has been partially funded by the European Union through the MixedEmotions Project (project number H2020 655632), as part of the `RIA ICT 15 Big data and Open Data Innovation and take-up` programme.

![MixedEmotions](https://raw.githubusercontent.com/MixedEmotions/MixedEmotions/master/img/me.png) 

![EU](https://raw.githubusercontent.com/MixedEmotions/MixedEmotions/master/img/H2020-Web.png)

http://ec.europa.eu/research/participants/portal/desktop/en/opportunities/index.html

