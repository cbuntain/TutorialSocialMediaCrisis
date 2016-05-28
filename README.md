# Tutorial on Social Media Analytics During Crisis

This material is from a tutorial I taught at the 33rd HCIL Symposium at the University of Maryland in May 2016.
I've included both the tutorial's slides and Jupyter notebooks used to demonstrate methods for pulling your own data from Reddit, Facebook, and Twitter.
I didn't see much in the way of other material (beyond what I've posted before about Twitter analysis during Ferguson), so feel free to re-use and redistribute at your leisure! 

## Tutorial Overview

This tutorial will build practical experience in using Python + Jupyter Notebooks to analyze and discover insights from social media during times of crisis and social unrest. 
We demonstrate how temporal, network, sentiment, and geographic analyses on Twitter can aid in understanding and enhance storytelling of contentious events. 
Examples of events we might cover include the Boston Marathon Bombing, and the Charlie Hebdo Attack. 
Demonstrations will include hands-on exercises in extracting tweets by location, sentiment analysis, network analysis to visualize groups taking part in the discussion, and detecting high-impact moments in the data. 
Most of the work will be performed in the Jupyter notebook framework to aid in repeatable research and support dissemination of results to others.

## Material Overview

### Tutorial Introduction
- Slides/00 - Introduction.key
- Terror Data sets
	- Boston Marathon
		- 15 April 2013, 14:49 EDT -> 18:49 UTC
	- Charlie Hebdo
		- 7 January 2015, 11:30 CET -> 10:30 UTC
	- Paris Nov. attacks
		- 13 November 2015, 21:20 CET -> 20:20 UTC (until 23:58 UTC)
	- Brussels
		- 22 March 2016, 7:58 CET -> 6:58 UTC (and 08:11 UTC)

### Data Acquisition
- Covered under Slides/01 - Data Acquisition.key
- Topic 1: Introducing the Jupyter Notebook
	- Jupyter notebook gallery
- Topic 2: Data sources and collection
	- Notebook: __T02 - DataSources.ipynb__
	- Data sources:
		- Twitter
		- Reddit
		- Facebook
- Topic 3: Parsing Twitter data
	- Notebook: __T03 - Parsing Twitter Data.ipynb__
	- JSON format
	- Python json.load

### Data Analytics
- Notebook: __T04-08 - Twitter Analytics.ipynb__
- Topic 4: Simple frequency analysis
	- Top hash tags
	- Most common keywords
	- Top URLs
	- Top images
	- Top users
	- Top languages
	- Most retweeted tweet
- Topic 5: Geographic information systems
	- General plotting
	- Country plotting
	- Images from target location
- Topic 6: Sentiment analysis
	- Subjectivity/Objectivity w/ TextBlob
- Topic 7: Other content analysis
	- Topics in relevant data
- Topic 8: Network analysis
	- Building interaction networks
	- Central accounts
	- Visualization
