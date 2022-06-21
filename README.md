# SunoikisisDC-Summer2022-Session9
Materials for the SunoikisisDC 2021-2022 Course on Natural Language Processing (NLP) for Historical Maps (session 9)


https://sunoikisisdc.github.io



https://github.com/SunoikisisDC/SunoikisisDC-2021-2022/wiki/SunoikisisDC-Summer-2022-Session-9



## Set up a conda environment

* Clone this github repository

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

```python
pip install -r requirements.txt
```



[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/github/ludovicmoncla/SunoikisisDC-Summer2022-Session9/blob/main/Tutorial-geoparsing.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ludovicmoncla/SunoikisisDC-Summer2022-Session9/main?filepath=Tutorial-geoparsing.ipynb)




