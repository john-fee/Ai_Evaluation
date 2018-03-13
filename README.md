# Ai Programming Evaluation

### Dependencies

All of the code for this report was run on the latest conda distribution (3.6.4) with the following additional dependencies:
- `nb_conda` for managing jupyter notebook environment
- `gensim` for text cleaning and tf-idf computation
- `spacy` for fast parsing and lemmatization
___
The conda environment used can be duplicated by navigating to the root of this project directory and running:

`conda env create -f environment.yml`

`python -m spacy download en`

in the command prompt.
___
The `movie_dataset.csv` should be downloaded and placed into the \data\ folder.
