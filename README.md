# Humor Classifier
## Dataset Description

Dataset used [Link](https://github.com/CrowdTruth/Short-Text-Corpus-For-Humor-Detection)

It contains five pickle files:

*Positive Samples*
1. [Humorous One-liners](https://github.com/iamdsc/humor_detection/blob/master/datasets/humorous_oneliners.pickle)
12. [Longer Jokes](https://github.com/iamdsc/humor_detection/blob/master/datasets/oneliners_incl_doubles.pickle)

*Negative Samples*
1. [Reuters headlines](https://github.com/iamdsc/humor_detection/blob/master/datasets/reuters_headlines.pickle)
2. [English Proverbs](https://github.com/iamdsc/humor_detection/blob/master/datasets/proverbs.pickle)
3. [Wikipedia Sentences](https://github.com/iamdsc/humor_detection/blob/master/datasets/wiki_sentences.pickle)


Models used:


|   Models Description	|   Accuracy	|  F1 Score 	|
|---	|---	|---	|
|   1. Simple feed-forward network with dense layers on top of embedding layer	|   0.9660	|   0.9231	|
|   2. Without pre-trained word embeddings	|   0.9839	|   0.9568	|
|   3. Using Simple RNN layer on top of embedding layer	|   0.9686 	| 0.9413  	|
|   4. Using LSTM layer on top of the embedding layer	|	0.9587|	0.9514| 	|
|5. Using two Conv1D layers on top of the Embedding layer	   | 0.9674  	|   0.9469	|
|  7. Using GRU layer on top of Conv1D layer 	|    0.9617	|   0.9462	|
| 8. Using two GRU layers on top of two Conv1D layers  |  0.9599  |  0.9472 |






#### Team Members:
* [Amit Kumar](https://github.com/pymit/)
* [Aditya](https://github.com/adi160)
* [Yash Chandra Verma](https://github.com/ycv005)
* [Devesh Kaushik](https://github.com/deveshkau)
