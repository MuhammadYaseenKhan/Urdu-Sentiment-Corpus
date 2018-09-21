# Labelled Urdu Tweets for Sentiment Analysis

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
The details on distribution and results of data set can be sought at follows: 
```
Khan MY, Emaduddin SM, Junejo KN. 
Harnessing English Sentiment Lexicons for Polarity Detection in Urdu Tweets: A Baseline Approach. 
In Semantic Computing (ICSC), 2017 IEEE 11th International Conference on 2017 Jan 30 (pp. 242-249). IEEE.
```

And, for the ![](https://latex.codecogs.com/gif.latex?%5Ctext%7B%5CLaTeX%7D) users BibTeX entry is:
```
@inproceedings{khan2017harnessing,
  title={Harnessing English Sentiment Lexicons for Polarity Detection in Urdu Tweets: A Baseline Approach},
  author={Khan, Muhammad Yaseen and Emaduddin, Shah Muhammad and Junejo, Khurum Nazir},
  booktitle={Semantic Computing (ICSC), 2017 IEEE 11th International Conference on},
  pages={242--249},
  year={2017},
  organization={IEEE}
}
```

If you are using this data set, kindly refer the above paper or acknowledge the data set as follows:
```
Khan, Muhammad Yaseen; Emaduddin, Shah Muhammad and Junejo, Khurram Nazir. 2017. Data set of Urdu Tweets for Polarity Detection.
Department of Computer Science, Mohammad Ali Jinnah University, Karachi, Pakistan. http://urduopinion.com/data set/labelled-urdu-tweet-corpus-yek.txt
```
Or, if you are using ![](https://latex.codecogs.com/gif.latex?%5Ctext%7B%5CLaTeX%7D) then BibTeX entry is following.
```
@misc{urdutweetcorpusyek,
   title = {Urdu Tweet Corpus YEK},
   author = {Khan, Muhammad Yaseen; Emaduddin, Shah Muhammad and Junejo, Khurram Nazir},
   url = {http://urduopinion.com/data set/labelled-urdu-tweet-corpus-yek.txt},
   note = {Department of Computer Science, Mohammad Ali Jinnah University, Karachi, Pakistan},
   copyright = {Attribution-{NonCommercial}-{ShareAlike} 3.0 Unported ({CC} {BY}-{NC}-{SA} 3.0)},
   year = {2017} 
}
```
