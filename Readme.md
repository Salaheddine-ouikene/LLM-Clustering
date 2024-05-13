# Projet TER : Large Language Models Enable Few-Shot Clustering 


## Abstract
In this project we study how to use Large Language Model to imporve clusetring results by incorporing LLMs in differentes stages :

1. **Before clustering** by generating key phrases extensions
2. **During clustering** by creating pairwise constraints to use in PCK-Means semi-supervised algorithmes
3. **After ckustering** by using LLMs to correct points assignation to clusters

## Base lines
### 1.Results reproduction
Our first aime was to try reproducing the results found by authors, for that we cloned all the git projects used by authors, we made the rights modifications to run the code after adding the needed datasets.
##### Improvement : 
1. The API used (Chat.completion) had been upgrade so we did the necessary changes in the code to make it run
2. We tried different number of constraints to study the evolution of the performences bases on the number of queries
3. Use of GPT 4.0 Turbo to study the impact of a better model on our results

##### Run 
Paste few_shot_clustering.ipynb to the initial project



### 2.Test on other dataset 
We explor the BBC_news dataset to test the effeciency of the methodes studier in the research paper
