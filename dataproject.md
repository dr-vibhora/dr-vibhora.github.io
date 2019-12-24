---
layout: default
mathjax: true
comments: true
title: Data science projects
permalink: /dataprojects/
---

## Projects

### 1. ANN for downscaling Groundwater model - [repo,](https://github.com/BrittGeek/Neural_Network) [poster,](https://srcole.github.io/assets/burrito/poster.pdf) [dashboard](https://sdburritos.herokuapp.com/)

This is my key PhD project where I have developed a scheme for downscaling key metrics for Groundwater (GW) Models uisng Remote Sensing (RS) and other modeling data via Artificial Neural Networks (ANN) approach. Conventionally, Groundwater Storage changes are required to be quantified using Groundwater Monitoring wells on the ground which are not able to measure such chnages on a consistent basis and are expensive to maintain. Satellite Remote Sensing based datasets such as from GRACE satellite provide harmonic coefficients which can be used to compute the Total Water Storage Changes through which Groundwater Storage Changes can be computed through rigorous analysis, althoigh such measurements still suffer from inaccuracies and coarse resolution of ~300 km which hinder accuarate analysis of GW storage chnages at a local level. We use GRACE satellite data along with Precipitation, Temperature, Evapotranspiration and SOil Moisture and other relevant data as input and Storage changes as Label data to improve the GWS estimates from satellite and to create better estimates for future as well. The work has been presented at key conferences   [Presentation for ANN approach in Grounwater Problems](https://www.czech-in.org/cmPortalV15/CM_W3_Searchable/iugg19/normal#!abstractdetails/0000801380).

### 2. Glacier - [Papers,](https://scholar.google.com/citations?user=fZe7tcwAAAAJ&hl=en) [methods paper repo,](https://github.com/voytekresearch/Cole_2018_cyclebycycle) [lab toolbox,](https://github.com/voytekresearch/neurodsp) [coupling toolbox](https://github.com/voytekresearch/pacpy)

For my PhD research, I developed, implemented, and justified a fundamentally new approach to analyzing brain rhythms. Conventional analysis revolves around the Fourier transform, which decomposes brain signals as a sum of sine waves. However, these brain rhythms are often nonsinusoidal in shape, and so Fourier analysis does not well capture all the information in the signal. I [wrote a review paper](https://linkinghub.elsevier.com/retrieve/pii/S1364661316302182) that summarized past reports of potentially interesting nonsinusoidal phenomena, developed a python- and pandas-based framework for analyzing waveform shape ([methods paper](https://www.biorxiv.org/content/early/2018/04/16/302000) and [library](https://github.com/voytekresearch/neurodsp)), and applied it to uncover physiological information contained in waveform shape (paper in prep). Additionally, I [wrote a paper](http://www.jneurosci.org/content/early/2017/05/02/JNEUROSCI.2208-16.2017) demonstrating how a previous high-profile result was artifactual because it did not properly accounting for waveform shape.

### 3. Computer Vision - [Crime Lab New York](https://urbanlabs.uchicago.edu/labs/crime-new-york) internship

Using scikit-learn, I built and iterated among several machine learning models trained on police officer activity to predict the likelihood of complaints of excessive force. These models are designed to be incorporated in an early intervention system (EIS) used to efficiently allocate training or other resources in police departments. I also used lots of pandas and seaborn to visualize trends in police officer behavior and variance across districts.

### 4.Urban Waste Monitoring and Classification with Data Driven Approach - [repo,](https://github.com/srcole/continu) [dashboard,](http://www.continu.site) [slides](http://bit.ly/continu-slides)

Keystroke patterns offer a unique biometric to identify individuals and authenticate them in a way that is difficult for malicious users to reproduce. As an Insight Data Science fellow, I worked with a project management fellow and a data engineering fellow towards a system to continuously authenticate users using their keystrokes. I trained a gradient boosting model in order to identify users with a 98% true positive rate and 98% true negative rate (recall), and designed a dashboard that a security team could use to visualize suspicious user activity.

### 5. Code sharing in neuroscience - [repo,](https://github.com/srcole/codesharing) [blog](https://srcole.github.io/2018/07/19/code_sharing_journals/)

I scraped the [PubMed API](https://www.ncbi.nlm.nih.gov/pmc/tools/developers/) to obtain the full text of around 170,000 articles from 20 different journals that publish neuroscience papers. I did some keyword searching in order to approximately determine which articles relied on custom-written scripts, and which articles publicly shared their code. This involved designing a tool to efficiently, semi-automatically, sift through 200 papers in order to validate the keyword-based estimates. Ultimately, I was able to see how journals vary in terms of code sharing and track how this has improved over time.

This project was expanded during a subsequent hackathon. [Our team improved and expanded the text mining to compute a measure of the openness of each journal ("O-Factor")](https://github.com/srcole/o-factor).





### 8. Politifact fact checks - [repo,](https://github.com/srcole/politifact-analysis) [blog post](https://srcole.github.io/2019/07/20/politifact/)

Politifact is a handy nonprofit organization that rates the truth value of political statements, mostly by American politicians. I scraped the results of their fact checking since their inception in 2007 and visualized some trends across time, geography, and the political spectrum.

### 9. Personal data requests - [repo,](https://github.com/srcole/personal-data-requests) [blog post](https://srcole.github.io/2019/08/17/personal-data-requests/)

The EU's General Data Protection Regulation (GDPR) law has prompted many web companies to allow its users to easily download (a subset of) the personal data they have stored. I was curious what information was held by the apps that I use (and what they would provide), so I requested, processed, analyzed, and visualized data from Spotify, Twitter, Amazon, Facebook, Apple, LinkedIn, Uber, Venmo, Bank of America, and Tinder.

### 13. Interactive visualization - [script,](https://github.com/srcole/qwm/blob/master/retire/make_bokeh.py) [blog](https://srcole.github.io/2017/09/09/retirement/)

I made a simple interactive graph using Bokeh that projects a savings plan to determine when you will have enough money to retire comfortably. I know I'm too young to be thinking about this already.


## Tutorials and teaching

Throughout my time doing these projects, I've also found it useful to make some lectures and tutorials for explaining concepts and tools. Here are some of them!

### 1. Neural signal processing - [Notebooks,](https://github.com/voytekresearch/neurodsp/tree/master/tutorials) YouTube videos ([1](https://www.youtube.com/watch?v=DIK5bfoTnlg)) ([2](https://www.youtube.com/watch?v=PAipVT_B_GY))

In order to help undergrads integrating into the lab, I and other lab members have written tutorials on how to use the standard tools that we use to analyze brain data. This has also included [empirical mode decomposition (EMD)](https://github.com/srcole/binder_emd) and [extracting data from images in a paper](
https://github.com/srcole/qwm/blob/master/misc/paper_data/Extract%20time%20series%20from%20a%20published%20figure.ipynb).



### 3. Introduction to data science - [Clustering slides,](https://srcole.github.io/assets/presentations/cogs108/clustering.html#/) [Linear regression notebook](https://github.com/srcole/qwm/blob/master/misc/COGS108_Multiple%20Linear%20Regression%20and%20Collinearity.ipynb)

As part of my advisor's introcution to data science undergraduate course, I gave a couple of guest lectures on clustering and multiple linear regression.
