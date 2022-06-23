# Tutorial - Natural Language Processing (NLP) for historical texts

Materials for the [SunoikisisDC](https://sunoikisisdc.github.io) Summer 2022 Course on [Natural Language Processing (NLP) for historical texts](https://github.com/SunoikisisDC/SunoikisisDC-2021-2022/wiki/SunoikisisDC-Summer-2022-Session-9) (Session 9)


In this tutorial, we demonstrate how to use a custom version of the [Perdido](https://github.com/ludovicmoncla/perdido) geoparser python library developed in the framework of the [GEODE](https://geode-project.github.io) project.
We will use texts from Diderot and d’Alembert’s Encyclopédie as a case study for querying a corpus and wrangling geoparsed data. We will also compare Perdido’s NER annotations (e.g. its output) to the results of other well-known python NER libraries ([spaCy](https://spacy.io) and [Stanza](https://stanfordnlp.github.io/stanza/index.html)).


Thursday June 23, 2022, starting at 17:15 CEST (for 90 minutes).

**Convenors**: [Katie McDonough](https://www.turing.ac.uk/people/researchers/katherine-mcdonough) (The Alan Turing Institute) and [Ludovic Moncla](https://ludovicmoncla.github.io) (INSA Lyon)

**Slides**:

**Youtube link**: https://youtu.be/7NK2KyP2BYs


## Set up a conda environment

Follow the instructions bellow, if you want to run this tutorial from a local environment on your computer. 
Otherwise, you can also run the notebook remotely using [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/github/ludovicmoncla/SunoikisisDC-Summer2022-Session9/blob/main/Tutorial-geoparsing.ipynb) or  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ludovicmoncla/SunoikisisDC-Summer2022-Session9/main?filepath=Tutorial-geoparsing.ipynb)



### Clone this github repository

```bash
git clone https://github.com/ludovicmoncla/SunoikisisDC-Summer2022-Session9.git
```


### Configure the environment with all dependencies

#### Method 1


* Create a new python environment called `sunoikisis-py39` with all dependencies using the `environment.yml` configuration file:

```bash
conda env create -f environment.yml
```

* Activate the environment

```bash
conda activate sunoikisis-py39
```

#### Method 2

* Create a new environment called `sunoikisis-py39`

```bash
conda create -n sunoikisis-py39 python=3.9
```

* Activate the environment

```bash
conda activate sunoikisis-py39
```

* Install dependencies with `pip`

```bash
pip install -r requirements.txt
```


### Launch the jupyter server

```bash
jupyter notebook
```





