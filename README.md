# Text-classifier
Predict the category of the item by its title and description (**see example of the train, test, and categories dataset in the main script**).

This project uses title and description of a good (e.g., posting on a classified) to predict its category among given hierarchical categories (~50 categories).

The best baseline model turns out to be SVM (see the crossvalidation chunk in the Notebook) over the TF-IDF with text preprocessing (lowercasing, deleting irrelevant characters, stemming).


