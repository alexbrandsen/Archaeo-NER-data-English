# Archaeo NER data (English)

This repo contains annotated NER data in the BIO format, for the following archaeological entity types:

- Artefacts (objects)
- Time Periods
- Materials
- Locations
- Contexts
- Species

This data has been annotated by 2 archaeology students at native English level. 

## Files

The all.txt file contains all annotated data. As the data is quite varied, and some documents are significantly easier to predict than others, 5 fold cross validation is recommended, and these are provided in the 5-folds folder. The 5-folds-test-train-val-split folder contains the 5 folds already split into test, train and validation splits, for ease of use. Splits are not stratified, but based on keeping documents completely in one of the splits, as having parts of the same document in both test and train makes the task significantly easier, and an unfair advantage.

