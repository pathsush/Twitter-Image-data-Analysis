# Twitter-Image-data-Analysis

##  1. Introduction  

In this we will discuss about the process and effort that we made to learn about the data. This report is structured into the three format and the process that has been followed.  
•	Gathering Data  
•	Assessing Data  
•	Cleaning Data  
 Gathering Data 
 
  During this process data has been collected from various sources. Basically three sources has been used to gather the data.  
•	Original Twitter archive: This data has been downloaded and given from Udacity.  
•	Image Prediction data:  This data has been downloaded from Udacity server programmatically.  
•	Twitter data:- This data has been downloaded  using twitter API.  

## Assessing Data  
  
  During assessing data I came to find out various perspective that data was trying to convey.  
•	There are  4 different dog types i.e. doggo with count 2259, floofer with count 2346,pupper with count 2099 and puppo with count of 2326. 
•	These  
•	During the data access, I came to find out that there 745 records  that has name  none.  
•	Also, there are some of the records in denominator that has value which is not accurate.  
•	Source data has long and not on point description.  
•	There are null records in data frame that has been extracted from different sources.  
Cleaning Data  	Quality Issue 
•	Drop all retweet data from df twitter to make sure that only original rating exist. 
•	Drop all replies data from df twitter to make sure that only original rating exist.  
•	In dataset df_twiteer there is an unnecessary column like in_reply_to_status_id,in_reply_to_user_id, retweeted_status_id, retweeted_status_user_id, retweeted_status_timestamp 
•	DataType of timestamp is not correct.  
•	Missing info in expanded urls column that means it doesn't have image. 
•	There are missing name in df_twiteer. 
•	Rating_denominator has some incorrected value becuasuse maximum value denominator can have is 10. 
•	Columns name are not descriptive like p1,p2.  
•	Make the source content specific 

## Tidiness Issue  
• 	There are 3 different data frame that is used it can be merged one.  • 	Dropping 4 different column of dogtypes to include in one column.  

## Conclusion  
During the wrangling process there are lot of unclean data that needed to clean. All those issue has been cleaned. During this task, I get to know that though there might be the data but it might have many discrepancy and that needed to be clean. This need to be visualized in order to get more insight about the data.  
 
 
