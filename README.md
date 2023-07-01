# Automated Entity Recognition in Colonial Records
This repository contains the accompanying code for the case study "Automated Entity Recognition in Colonial Records", part of the AM Research Methods series "Interrogating Colonial Documents and Narratives".

## Summary
Colonial archives contain vast and complex recordings of past events, and are typically accessed by experts using their knowledge of an archive and its finding aids. This effectively constitutes a steep barrier to a wider and more systematic use of colonial archives. Automated Entity Recognition is the machine learning task of automatically detecting mentions of entities of interest in a large collection of documents. These typically include persons, places, organisations, and more. As archives are increasingly digitised and their contents made into machine readable texts, is it becoming possible to apply Automated Entity Recognition to expand an archive’s finding aids and thus broaden access to the information it contains. In this case study we will discuss the use of Automated Entity Recognition on colonial archives, implement an entity recognition pipeline, and critically discuss our results in view of using Automated Entity Recognition for real world applications or research projects.

## Contents
- Folder [data](data): contains two text files with the automatically extracted texts of two set of documents for which the first 50 pages are also provided. Please refer to the case study for more context. 
- Folder [resources](resources): images used in the notebok.
- File [Automated Entity Recognition in Colonial Records](<Automated Entity Recognition in Colonial Records.ipynb>): a Jupyter notebook containing the commented code used for the case study.

## How to
You may simply open the notebook in a browser and read through it. Otherwise, you will have to download this repository, configure your Python environment and run it locally. Another option is to use [Google Colab](https://colab.research.google.com) and run it in the cloud.

The Python libraries used in this notebook are: `spacy`, `pandas`, `seaborn`, `matplotlib`, and the Python standard library. This notebook has been developed in `Python 3.10`.

## License
This repository is provided under an MIT license. The case study is coyright of AM Digital.