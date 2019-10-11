
<p align="center"><img width=25% src="https://github.com/darabigdata/IDWBotswana/blob/master/media/daralogo.png"></p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Python](https://img.shields.io/badge/python-v3.6+-blue.svg)
[![Build Status](https://travis-ci.org/darabigdata/WindhoekHack.svg?branch=master)](https://travis-ci.org/darabigdata/WindhoekHack)
![Dependencies](https://img.shields.io/badge/dependencies-up%20to%20date-brightgreen.svg)
[![GitHub Issues](https://img.shields.io/github/issues/darabigdata/WindhoekHack.svg)](https://github.com/darabigdata/WindhoekHack/issues)
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-orange.svg)
[![License](https://img.shields.io/cran/l/devtools.svg)](https://opensource.org/licenses/gpl-license)


## Introduction
 Welcome to the [DARA Big Data](https://www.darabigdata.com) project hackathon at the Namibia University of Science and Technology! <img src="https://github.com/darabigdata/WindhoekHack/blob/master/media/Namibia_120-animated-flag-gifs.gif" width=5%>

The DARA Big Data hackathon is designed to help you improve your data science skills in a friendly and supportive environment. At the hackathon, you will be grouped into **teams of four** and each team will work on completing the hack challenge. At the end of the hack each team will give a 5 minute (3 slide) presentation on the results of their challenge. These presentations will be judged by the organisers and there will be a prize for the winning team. The presentations will be judged on (1) the accuracy of the predicted results via machine learning and (2) visualisation/presentation of the data and results.

The DARA Big Data hack challenges will be run in Python3 using the [IDIA Cloud](idia.ac.za/research-and-projects/african-research-cloud). Students should have a basic working knowledge of Python (including the scipy and numpy libraries) - but you do not have to be an expert to take part and enjoy yourself!

-----

## The Challenge: Find All the Dead Stars

In this challenge you are tasked with building a classifier to separate out real astronomical signals from man-made radio frequency interference (RFI). The astronomical signals that you're looking for come from *pulsars*, the ultra-dense relics of exploded stars. You can read more about them in this [introduction to pulsars and how to classify them using random forests](https://as595.github.io/classification/). The dataset is available to you in two formats: (i) as [a set of eight numerical features](https://github.com/darabigdata/WindhoekHack/blob/master/data/pulsar.csv) per sample suitable for classification using random forests, SVMs, neural nets etc. and (ii) as [a set of images](https://as595.github.io/HTRU1/) that show the data that the numerical features are drawn from, suitable for [CNN based classification](https://as595.github.io/frdeepcnn/). Your **hack challenge** is to build the best classifier that you possibly can, remembering that we want as many correctly classified pulsars as possible, with as little contamination from RFI as possible...


-----

### Not at the hackathon, but want to test your code-building skills? Feel free!

```bash
> git clone https://github.com/darabigdata/WindhoekHack.git
```

Then make sure you have the right Python libraries for the tutorials. They can all be installed using pip and the [requirements.txt](https://github.com/darabigdata/WindhoekHack/blob/master/requirements.txt) file in the repo:

```bash
> pip install -r requirements.txt
```


-----

### DARA Big Data is supported by:

<p align="center"><img width=20% src="https://github.com/darabigdata/IDWBotswana/blob/master/media/Newton-Fund-Master-rgb.jpg", hspace="20"><img width=40% src="https://github.com/darabigdata/IDWBotswana/blob/master/media/stfc_logo.png", hspace="20"><img width=25% src="https://github.com/darabigdata/IDWBotswana/blob/master/media/dst_logo_crop.jpeg"><img width=30% src="https://github.com/darabigdata/WindhoekHack/blob/master/media/idia_logo.png"></p>
