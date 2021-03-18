# WeRateDog-Account
**Objectives**:
> Use archived tweet data from WeRateDogs account and gather missing data by using API. <br>
> Assess and clean archived/gathered/predicted data. <br>
> Analyze WeRateDogs dataset and its neutral network predictions.
> 
## Gather
In this project, apart from archived tweet master data, the other two datasets are both gathered from online, one is collected by connecting to tweet API, the other is collected by simply downloading from Udacity database. Dataset gathered through tweet API is relatively more challenging since I've never used twitter before and it took some efforts to understand the contents. <br>
In the end, only tweet_id, retweet counts and favorite counts columns are kept from newly collected tweet dataset for further usage. For the other prediction dataset, images are also downloaded in order to visually take a look of the prediction (out of interests.)

## Assess
To assess gathered data, 2 methods are mainly used. One is programmatic assessment, the other is observation in spreadsheets. 2 methods are both very useful to identify potential issues, programmatic assessment is more for identifying logical issues, observation allows skimming the whole dataset. <br> 
There are quite some issues identified e.g. empty columns, duplicated data, useless data and rating extraction issues. <br>
The whole assessing process strictly follows tidiness and quality definitions.

## Clean
After assessing datasets, the process of defining - coding - testing is used in order to clean up datasets. Then cleaned datasets are saved to csv file on local directory. <br>
There are some small issues such as datatype issues, duplicated data which are easy to be cleaned. While issues such as empty records due to gathering or lacking specific rules to be identified are difficult to resolve. <br>
Depending on analytical objectives, datasets might need to be more strictly cleaned.

## Analytics
Only EDA is performed on this dataset in order to get a flavor of WeRateDog account such as its peak time, when it became popular, prediction resultss of neutral network.
