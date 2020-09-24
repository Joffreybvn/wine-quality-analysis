# Wine Quality -  Analysis

Analysis and interpretation of a [red wine quality's dataframe](https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009).

### Objectives:
 - [x] Using Pandas for data manipulation.
 - [x] Using MatplotLib and/or Seaborn for plotting.
 - [x] Finding and understanding correlations between dataset's variables.

### Goals:
1. Determine **the criteria that influence the quality** of red wine by analysing the dataframe.
2. Find out **which are the best and worst** wines.

# Dataframe analysis
The complete analysis and its details is avaibale on [Google collab](https://colab.research.google.com/drive/1VdehLoCJraz0GHCz8B6EmgoCrP33TVoc?usp=sharing), or directly in the [notebook of this repo]().

## The target: the Quality

The quality index in the dataframe is obviously the target variable. A good quality means a good wine, while a bad quality means a bad wine. The following analysis tried to **understand and explain wich variables have influences on quality, how and how much ?**

### Variable distribution:
Fortunately, this dataset is quite clean. Same for the *quality*, which is quite well distributed:

**Skew:** 0.192 - **Kurtosis:** 0.340
![https://raw.githubusercontent.com/Joffreybvn/wine-quality-analysis/master/visualisations/quality.svg](https://raw.githubusercontent.com/Joffreybvn/wine-quality-analysis/master/visualisations/quality.svg)

## Correlations between variables

This heatmap shows the correlations bewteen variables, and was **used to investigate which kind of relations** variables have between them.

![https://raw.githubusercontent.com/Joffreybvn/wine-quality-analysis/master/visualisations/heatmap.svg](https://raw.githubusercontent.com/Joffreybvn/wine-quality-analysis/master/visualisations/heatmap.svg)

### Investigation order:
Some correlations are more interesting to investigate than others.

1. Investigate the 4 strongest correlations bewteen **quality** and *others variables**.
2. Investigate the strongest correlations **btween these 4 variables**.
3. Gradually investigate the strongest correlations between theses 4 variables, and **the rest of the variables** (the presumably "*less*" important ones).

The complete investigation with the observations, can be found on [Google collab](https://colab.research.google.com/drive/1VdehLoCJraz0GHCz8B6EmgoCrP33TVoc?usp=sharing), or directly in the [notebook of this repo]().

### Conclusions:

After investigating and understandng the nature of the correlations bewteen the *quality* and the *others variables*, I came to the following conclusion:

<p align="center">
  <img src="https://raw.githubusercontent.com/Joffreybvn/wine-quality-analysis/master/visualisations/wine.svg">
</p>
