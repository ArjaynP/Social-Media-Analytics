# SocialMediaAnalytics

The objective of the project is to pre-process, analyze, and present data relating to people's current opinion on Tesla as a publicly traded company. The dataset contains 1800 to 3000 recent tweets about a given keyword. The dataset has been pre filtered prior to download to remove any non-english tweets and retweets, and remove all emojis as well as special characters.

The idea is to execute similar responsibilites/duties as a data analyst and perform some textual analysis on this data to attempt to derive some meaning. In this case, this project is an analysis of the current sentiment or opinion twitter users have of Tesla. This form of analysis of social media data can be a helpful indicator of the current public opinion regarding the stock.


To derive this sentiment these were the follwing steps I followed:
 Obtain the dataset.
 Clean the dataset using regular expressions in Notepad++ preferably.
 Import the data into Excel saving as a tsv (tabs separated values), sort it and use Excel’s built in remove duplicate tool (use vba as well to further remove any outstanding duplicates.
 Used a VBA fucntion called SentimentCalc to calculate the sentiment of each tweet.
 Used Excel buitl-in formulas to analyze the results
