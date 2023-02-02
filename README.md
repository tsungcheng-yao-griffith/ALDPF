# Abusive Messages and Personal Perceptions 

Repository for "ALDPF: An Abusive Language Dataset with Psychological Features". Full text of the paper can be found here

The dataset contains 114027 unfolded messages and psychological features, annotated by 505 MTurk workers. You can duplicate the dataset with the following steps.

* Access [Founta's Zenodo page](https://zenodo.org/record/3706866#.YjzZfDUReUk) and request access.
* Put ALDPF.py, datasetfinal_no_message.csv, index.csv, and hatespeech_text_label_vote.csv in the same folder.
* Execute ALDPF.py and obtain ALDPF.csv


_**About the ALDPF**_

This new dataset includes three columns to denote labels and messages, as well as the characteristics of the annotators who gave the label of each message.
* Labels: 1 refers to neutral, and 2 refers to harmful
* Message: Tweets selected from Founta's dataset
* Characteristics: Shortened General Attitude and Belief Scale (SGABS) was used, and the results are presented in the same sequence as they are in the original SGBAS. 


_**Appendix**_

* datasetfinal_no_message.csv: a dataset contains new labels and corresponding psychological features. 
* ALDPF.py: a python script to extract tweets from Founta's dataset and merge them with ALDPF.
* index.csv: a supporting document helps ALDPF.py to pull tweets.
* hatespeech_text_label_vote.csv: the full version of Founta's dataset, which can be acquired from Founta's Zenodo page.
* ALDPF.csv : the full version of ALDPF
