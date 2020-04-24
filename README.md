# Group Project BT5153
NUS MSBA BT5153 Applied Machine Learning for Business Analytics

#### Group 08
#### Group Members: <br />
Abigail Tee Ren Hui <br />
Chua Wei Yang Rex <br />
Muhamad Imran Bin Mohd Yusof <br />
Kuah Jun Wei Jerome <br />
Seah Fang Ying 

## Data Source  <br />
Description:  <br />
* Scrape data from goodreads - book description, book genres and book reviews.  <br />

Code Files:  <br />
* Scrape(DescriptionGenres) <br />
* Scrape(Reviews) <br />

## Data Cleaning <br />
Description: <br />
* Text cleaning of book descriptions and reviews <br />
* Filter books based on description length and number of genres  <br />
* Filter reviews based on review length (for reviews of selected genres of books) <br />

Data Used: <br />
* Books dataset scraped from goodreads and book depository <br />
* Reviews dataset scraped from goodreads <br />

Code Files: <br />
* DataCleaning <br />

## Text Features <br />
Description:  <br />
* To obtain text features from book descriptions <br />
* 2 Models used: LDA and Doc2Vec <br />
* Plot of LDA and Doc2Vec outputs to explore the results <br />

Data Used:  <br />
* Cleaned book descriptions.  <br />

Code Files: <br />
* TextFeatures(LDA)  <br />
* TextFeatures(Doc2Vec) <br />
* TextFeatures(Plot)  <br />

## Search Engine <br />
Description: <br />
* To create a contextual search engine using the LDA Model <br />
* Model evaluation using book reviews proved to be a poor evaluation method <br />

Data Used: <br />
* Cleaned book description<br />
* Cleaned book reviews <br />
* LDA document topic distribution<br />

Code Files: <br />
* SearchEngine(LDA)<br />

## Genre Prediction (Doc2Vec and LDA) <br />
Description: <br />
* To predict book genres using different machine learning techniques – Classifier Chains, Label Powerset, Adapted Algorithm (MLkNN), Ensemble (RAkELd) and Neural Network <br />
* 2 Predictor variables used: (1) Document embeddings from Doc2Vec and (2) Document topic distribution from LDA <br />

Data Used: <br />
* Book genres  <br />
* Doc2vec document embeddings <br />
* LDA document topic distribution <br />

Code Files: <br />
* GenrePrediction(Doc2vec)<br />
* GenrePrediction(LDA)<br />

## Genre Prediction (CNN with Embedding)<br />
Description: <br />
* To predict book genres using CNN word embeddings <br />
* Best performing model  <br />

Data Used:<br />
* Cleaned book descriptions <br />

Code Files: <br />
* GenrePrediction(CNN_embedding)<br />





















