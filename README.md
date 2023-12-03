# Assignment 2
  
## Team members
- Daria Koroleva 40096402

- Marian Maksimos 40067018


## How to run experiments


### Requirements
 - To run the experiment it will be required to use Jupyter notebook or lab.
 - The python environment requires this packages installed:
	 - pip install -q gensim
	 - pip install -q pandas
	 - pip install -q matplotlib
     - pip install -q nltk
 - Download http://vectors.nlpl.eu/repository/20/40.zip
	- This is the model for Task 2 model English-CoNLL17-100
 	- unzip the content on the folder where executing the code  .\
	- after the extraction verify that this file is present in the folder 40
		.\40\model.bin
 - The other models are going to be downloaded in the execution by using gensim library
 - Verify that books for 5-books-corpus are in the root
   - aliseinwonderland.txt
   - the_hound_of_baskervilles.txt
   - frankenstein.txt
   - thegreatgatsby.txt
   - xmascarol.txt

###  Runing the experiment
 -  Open the file Assignment_2.ipynb on Jupyter notebook or lab
 -  Run all cells

## Output files

### Details output files for each model
 - word2vec-google-news-300-details.csv
 - English-CoNLL17-100-details.csv
 - glove-wiki-gigaword-100-details.csv
 - glove-twitter-100-details.csv
 - glove-twitter-200-details.csv
 - 5-books-corpus-100-5-details.csv
 - 5-books-corpus-100-10-details.csv
 - 5-books-corpus-300-5-details.csv
 - 5-books-corpus-300-10-details.csv

### Analysis output file for all models
 - analysis.csv