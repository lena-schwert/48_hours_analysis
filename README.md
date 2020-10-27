# 48 Hours Analysis

## About the project

The objective of this small university project was to gain insights into a small dataset in a very limited timeframe without knowing anything about the context of the data. Preparing the data for the analysis included a bit of data cleaning as well as identifying  and removing missing values..

The analysis was mostly exploratory, but aimed at answering concrete questions about the data with different methods:

- Are there different patterns in the meter readings for different meter types

	--> methods: time series plot + histograms
	
- Are some of the weather variables measuring very similar things?

	--> methods: Pearson correlation between features and principal component analysis (PCA) to discover redundancy
	
- Are there generally changes in energy consumption, based on the month, the weekday and the time of day?

	--> method:  boxplots
	
- What are the variables having the highest predictive power for the energy consumption?
	
	--> method: generalized linear model (GLM) with Gaussian error structure

## Context of the project

This project was conducted as part of the coursework of my Masters degree (Management & Data Science) in the winter term 2019/2020 (October - March). The task was to analyze an assigned dataset using R and statistical methods of our choice and then explain the insights gained in a short report.

## How to run the code

The code is embedded in the R Markdown file where it is also annotated and explained. Make sure you have the required libraries installed and have set the working directory. I used the R version 3.6.1.
