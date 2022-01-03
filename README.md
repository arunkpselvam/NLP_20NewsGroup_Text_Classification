# NLP_20NewsGroup_Text_Classification
20 Newsgroups Text Classification using Count Vectorizer and MultinomialNB
The 20 Newsgroups data set is a collection of approximately 20,000 newsgroup documents, partitioned (nearly) evenly across 20 different newsgroups. To the best of my knowledge, it was originally collected by Ken Lang, probably for his Newsweeder: Learning to filter netnews paper, though he does not explicitly mention this collection. The 20 newsgroups collection has become a popular data set for experiments in text applications of machine learning techniques, such as text classification and text clustering.

## Organization
The data is organized into 20 different newsgroups, each corresponding to a different topic. Some of the newsgroups are very closely related to each other (e.g. comp.sys.ibm.pc.hardware / comp.sys.mac.hardware), while others are highly unrelated (e.g misc.forsale / soc.religion.christian). Here is a list of the 20 newsgroups, partitioned (more or less) according to subject matter:

## Labels:
comp.graphics
comp.os.ms-windows.misc
comp.sys.ibm.pc.hardware
comp.sys.mac.hardware
comp.windows.x	rec.autos
rec.motorcycles
rec.sport.baseball
rec.sport.hockey	sci.crypt
sci.electronics
sci.med
sci.space
misc.forsale	talk.politics.misc
talk.politics.guns
talk.politics.mideast	talk.religion.misc
alt.atheism
soc.religion.christian

## Distribution:

Classes: 20
Samples tota: 18846
Dimensionality: 1
Features: text

## Activity
I have built a Multinomial Naive Bayes based on this dataset which can be used to classify new sentences in to these subgroups.

## Reference:
http://qwone.com/~jason/20Newsgroups/ <br>
https://scikit-learn.org/0.19/datasets/twenty_newsgroups.html <br>
https://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.MultinomialNB.html
