[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/hb20007/greek-dialect-classifier/master)

# Greek Dialect Classifier

> Putting an end to &ldquo;It’s all Greek to me.&rdquo;

A classifier that identifies Greek text as either Cypriot Greek (CG) or Standard Modern Greek (SMG)

For more information, you can read my thesis: [A Classifier to Distinguish Between Cypriot Greek and Standard Modern Greek](https://www.academia.edu/36753159/A_Classifier_to_Distinguish_Between_Cypriot_Greek_and_Standard_Modern_Greek).

## 1. Notebooks

|Index of Jupyter Notebooks|
|---|
|[1. Obtaining CG and SMG tweets](1-Obtaining-CG-SMG-Tweets.ipynb)<br>*Collecting the corpus*|
|[2. Data Analysis](2-Data-Analysis.ipynb)<br>*Analyzing the corpus*|
|[3. Building the Classifier](3-Building-the-Classifier.ipynb)<br>*Building the CG-SMG classifier*|

## 2. The corpus

The corpus can be found in the `Data` directory. It was collected by me personally and labeled into CG and SMG by separating the text into files.

|Index of files in corpus|
|---|
|[CG Facebook](Data/cg_fb.txt)<br>*CG text collected from Facebook posts and comments*|
|[CG Twitter](Data/cg_twitter.txt)<br>*CG text collected from tweets*|
|[CG Other](Data/cg_other.txt)<br>*CG text collected from forum posts, blogs, and news article comments*|
|[SMG Facebook](Data/smg_fb.txt)<br>*SMG text collected from Facebook posts and comments*|
|[SMG Twitter](Data/smg_twitter.txt)<br>*SMG text collected from tweets*|
|[SMG Other](Data/smg_other.txt)<br>*SMG text collected from forum posts, blogs, and news article comments*|

## 3. Instructions

To run the code, either clone the repository, download the dependencies, and run the Jupyter notebooks locally, or click on the Binder badge at the top of this README to run the notebooks on a remote server.

## 4. Trying the classifier

If you are only interested in running the classifier with your own input, go to the last section of [3. Building the Classifier](3-Building-the-Classifier.ipynb).
