# Greek Dialect Classifier

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/hb20007/greek-dialect-classifier/master)

> Putting an end to &ldquo;It’s all Greek to me.&rdquo;

A classifier that identifies Greek text as either Cypriot Greek (CG) or Standard Modern Greek (SMG)

For more information, you can read my thesis: [A Classifier to Distinguish Between Cypriot Greek and Standard Modern Greek][thesis].

## 1. Notebooks

| Index of Jupyter Notebooks                                                   |
| ---------------------------------------------------------------------------- |
| [1. Obtaining CG and SMG tweets][notebook-1]<br>*Collecting the corpus*      |
| [2. Data Analysis][notebook-2]<br>*Analyzing the corpus*                     |
| [3. Building the Classifier][notebook-3]<br>*Building the CG-SMG classifier* |

## 2. The corpus

The corpus can be found in the `Data` directory. It was collected by me personally and labeled into CG and SMG by separating the text into files.

| Index of files in corpus                                                                                        |
| --------------------------------------------------------------------------------------------------------------- |
| [CG Facebook][cg-fb]<br>*CG text collected from Facebook posts and comments*                                    |
| [CG Twitter][cg-twitter]<br>*CG text collected from tweets*                                                     |
| [CG Other][cg-other]<br>*CG text collected from forum posts, as well as comments on blogs and news articles*    |
| [SMG Facebook][smg-fb]<br>*SMG text collected from Facebook posts and comments*                                 |
| [SMG Twitter][smg-twitter]<br>*SMG text collected from tweets*                                                  |
| [SMG Other][smg-other]<br>*SMG text collected from forum posts, as well as comments on blogs and news articles* |

## 3. Instructions

To run the code, you can clone the repository, install the dependencies, and run the Jupyter notebooks on your local machine, or click the Binder badge at the top of this README to run the notebooks on a remote server.

## 4. Trying the classifier

If you want to run the classifier with your own input, go to the last section of [3. Building the Classifier][notebook-3].

[thesis]: https://www.academia.edu/36753159/A_Classifier_to_Distinguish_Between_Cypriot_Greek_and_Standard_Modern_Greek
[notebook-1]: 1-Obtaining-CG-SMG-Tweets.ipynb
[notebook-2]: 2-Data-Analysis.ipynb
[notebook-3]: 3-Building-the-Classifier.ipynb
[cg-fb]: Data/cg_fb.txt
[cg-twitter]: Data/cg_twitter.txt
[cg-other]: Data/cg_other.txt
[smg-fb]: Data/smg_fb.txt
[smg-twitter]: Data/smg_twitter.txt
[smg-other]: Data/smg_other.txt
