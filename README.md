[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/hb20007/greek-dialect-classifier/master)

# Greek Dialect Classifier

> Putting an end to “It's all Greek to me”

This is a classifier that identifies Greek text as Cypriot Greek (CG) or Standard Modern Greek (SMG).

For more information, you can read my thesis: .

## 1. Notebooks
|Index of Jupyter Notebooks|
|---|
|[1. Obtaining CG and SMG tweets](https://github.com/hb20007/greek-dialect-classifier/blob/master/1-Obtaining-CG-SMG-Tweets.ipynb)<br>*Code used to collect tweets*|
|[2. Data Analysis](https://github.com/hb20007/greek-dialect-classifier/blob/master/2-Data-Analysis.ipynb)<br>*Analyzing the corpus*|
|[3. Building the Classifier](https://github.com/hb20007/greek-dialect-classifier/blob/master/3-Building-the-Classifier.ipynb)<br>*Building the CG-SMG classifier*|

## 2. The corpus
The corpus can be found in the `Data` directory. It was collected by me personally and labeled into CG and SMG by separating text into files.

|Index of files in corpus|
|---|
|[CG Facebook](https://github.com/hb20007/greek-dialect-classifier/blob/master/Data/cg_fb.txt)<br>*CG text collected from Facebook posts and comments*|
|[CG Twitter](https://github.com/hb20007/greek-dialect-classifier/blob/master/Data/cg_twitter.txt)<br>*CG text collected from tweets*|
|[CG Other](https://github.com/hb20007/greek-dialect-classifier/blob/master/Data/cg_other.txt)<br>*CG text collected from forum posts, blog and news article comments*|
|[SMG Facebook](https://github.com/hb20007/greek-dialect-classifier/blob/master/Data/smg_fb.txt)<br>*SMG text collected from Facebook posts and comments*|
|[SMG Twitter](https://github.com/hb20007/greek-dialect-classifier/blob/master/Data/smg_twitter.txt)<br>*SMG text collected from tweets*|
|[SMG Other](https://github.com/hb20007/greek-dialect-classifier/blob/master/Data/smg_other.txt)<br>*SMG text collected from forum posts, blog and news article comments*|

Feel free to use the corpus or a subsection of it in any kind of project as long as you provide a link to this repository.

## 3. Instructions
In order to run the code, either clone the repository and run Jupyter Notebooks locally, or click on the Binder badge at the top of this readme to instantly run the notebooks on a remote server. If you choose the latter option, you still need to use `nltk.download()` in order to download the required NLTK modules.

## 4. Trying the classifier
If what you are interesting in is running the classifier with your own text as input, go to the last section of the notebook [3. Building the Classifier](https://github.com/hb20007/greek-dialect-classifier/blob/master/3-Building-the-Classifier.ipynb).

## 5. Meta

H. Z. Sababa &mdash; hb20007 &mdash; hzsababa@outlook.com

Distributed under the MIT license. See `LICENSE.md` for more information.