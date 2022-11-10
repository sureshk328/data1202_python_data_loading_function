# DATA 1202 Assignment: Data Loading #
## Dataset To USe ##
A extraction of the top 4000 YouTube channels based on Subscribers.
```bash
https://www.kaggle.com/datasets/libinmathew264/youtube-top-4000-channels-based-on-subscribers
```
## Python Code ##

The Python Code addresses the following functionalaties:
* Create a function to calculate the distribution of channeltype from the top 1000 records.
  * Function to calculate the distribution of channeltype 'channeltype_distribution(df,grpbycol,coltocount)' has been created
* Load only the top 1000 records of the original 4000 into a separate CSV file, and to a database table. 
    * Loading top 1000 into new csv file
    * Create MySQL engine and connect with connection string in format 'dialect+driver://username:password@host:port/database'
    * Import into MySQL table
