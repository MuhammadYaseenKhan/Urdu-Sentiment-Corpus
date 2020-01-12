# Urdu Senitment Corpus: A labeled dataset for Urdu sentiment analysis and sentiment classification

### About the dataset
The dataset contains 999 tweets in Urdu language, collected between 14 August 2014 – 17 December 2014. During the mentioned period, the political parties in Pakistan, in particular, Pakistan Tehreek-e-Insaf (PTI) and Pakistan Awami Tehreek (PAT) were protesting in Islamabad against the government. The tweets were publicly available and randomly selected. So it was used on “as is” basis. 

Each tweet in the data set was labelled by three judges, whether it is Positive (P), Negative (N) or Objective (O)? The final label was considered positive where the tweet got two positive votes, so with the negative, otherwise, it was called objective.

![Judging Criterion](https://latex.codecogs.com/gif.latex?f%28L_1%5En%2C%20L_2%5En%2C%20L_3%5En%29%20%3D%20%5Cleft%5C%7B%20%5Cbegin%7Barray%7D%7Bl%20l%7D%20%5Cmathbb%7BP%7D%20%26%20%5Csum_%7B%5Csubstack%7B%20i%3D1%20%5C%5C%20L_i%5En%20%3D%3D%20P%20%7D%7D%20%5Cgeq%202P%5C%5C%20%5Cmathbb%7BN%7D%20%26%20%5Csum_%7B%5Csubstack%7B%20i%3D1%20%5C%5C%20L_i%5En%20%3D%3D%20N%20%7D%7D%20%5Cgeq%202N%5C%5C%20%5Cmathbb%7BO%7D%20%26%20Otherwise%20%5Cend%7Barray%7D%20%5Cright.)

Where ![](https://latex.codecogs.com/gif.latex?%24L_1%5En%2C%20L_2%5En%24) and ![](https://latex.codecogs.com/gif.latex?L_3%5En) are individual labels given by judges ![](https://latex.codecogs.com/gif.latex?L_1%2C%20L_2) and ![](https://latex.codecogs.com/gif.latex?L_3) to tweet ![](https://latex.codecogs.com/gif.latex?n). ![](https://latex.codecogs.com/gif.latex?%24%5Cmathbb%7BP%7D%24) and ![](https://latex.codecogs.com/gif.latex?%24%5Cmathbb%7BN%7D%24) are positive and negative labels (true labels / classes), and ![](https://latex.codecogs.com/gif.latex?%24%5Cmathbb%7BO%7D%24) stands for the objective.

The authors and judges were not aligned/agree/disagree with the tweets and persons whom they belong. 

### Legends
- The hash sign # coming at the start of the line means a comment.
- Each line (if not a comment) has the Urdu text enclosed in quotes, and the class / final label assigned to that tweet. i.e. P, N, or O i.e. Positive, Negative or Objective respectively. A comma (,) separates the quoted Urdu text and its class.


### Citing and Referencing 
If you are using this dataset in your research, please cite the following associated work done in the preparation of this dataset.
```
[Khan, Muhammad Yaseen, Shah Muhammad Emaduddin, and Khurum Nazir Junejo. 
"Harnessing English Sentiment Lexicons for Polarity Detection in Urdu Tweets: A Baseline Approach." 
In 2017 IEEE 11th International Conference on Semantic Computing (ICSC), pp. 242-249. IEEE, 2017.](https://www.researchgate.net/publication/311693013_Harnessing_English_Sentiment_Lexicons_for_Polarity_Detection_in_Urdu_Tweets_A_Baseline_Approach)
```

```
[Khan, Muhammad Yaseen, and Nizami, Muhammad Suffian. 
"Urdu Sentiment Corpus (v1.0): Linguistic Exploration and Visualization of Labeled Datasetfor Urdu Sentiment Analysis." 
In 2020 IEEE 2nd  International Conference On Information Science & Communication Technology (ICISCT). IEEE, 2020.](https://www.researchgate.net/publication/338396518_Urdu_Sentiment_Corpus_v10_Linguistic_Exploration_and_Visualization_of_Labeled_Dataset_for_Urdu_Sentiment_Analysis)
```

And, for the ![](https://latex.codecogs.com/gif.latex?%5Ctext%7B%5CLaTeX%7D) users BibTeX entry is:
```
@inproceedings{khan2017harnessing,
  title={Harnessing English Sentiment Lexicons for Polarity Detection in Urdu Tweets: A Baseline Approach},
  author={Khan, Muhammad Yaseen and Emaduddin, Shah Muhammad and Junejo, Khurum Nazir},
  booktitle={2017 IEEE 11th International Conference on Semantic Computing (ICSC)},
  pages={242--249},
  year={2017},
  organization={IEEE}
}
```

```
@inproceedings{khan2020usc,
  title={Urdu Sentiment Corpus (v1.0): Linguistic Exploration and Visualization of Labeled Datasetfor Urdu Sentiment Analysis.},
  author={Khan, Muhammad Yaseen and Nizami, Muhammad Suffian},
  booktitle={2020 IEEE 2nd International Conference On Information Science & Communication Technology (ICISCT)},
  pages={},
  year={2020},
  organization={IEEE}
}
```
