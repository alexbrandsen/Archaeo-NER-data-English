# Archaeo NER data (English)

This repo contains annotated NER data, for the following archaeological entity types:

- Artefacts (objects)
- Time Periods
- Materials
- Locations
- Contexts
- Species

This data has been annotated by 2 archaeology students at native English level. 

The files are in the BIO format, so 1 token per line, followed by the POS and label, separated by spaces. Sentence boundaries are denoted by a double line ending. 

## Files

The all.txt file contains all annotated data. 

As the data is quite varied, and some documents are significantly easier to predict than others, 5 fold cross validation is recommended, and these are provided in the 5-folds folder. 

For ease of use, the 5-folds-test-train-split and 5-folds-test-train-val-split folders contain the 5 folds already split in test and train, and optionally validation sets.  

Splits are not stratified, but based on keeping documents completely in one of the splits, as having parts of the same document in both test and train makes the task significantly easier, and an unfair advantage.

