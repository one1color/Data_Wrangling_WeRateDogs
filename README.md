In this project, the tweet archive of the Twitter user WeRateDogs will be wrangled, analysed, and visualised.

The dataset that will be wrangled (and analysed and visualised) is the tweet archive of a Twitter user known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. 

# Dataset
There are three separate datasets that will be wrangled and analysed.
* WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively to use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017. (`twitter_archive_enhanced.csv`)

* The tweet image predictions, i.e., what breed of dog (or other objects, animal, etc.) is present in each tweet according to a neural network. This file (`image_predictions.tsv`) hosted on Udacity's servers and be downloaded programmatically using the Requests library and the following URL: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv

* Each tweet's retweet count and favourite (i.e. "like") count, and any additional data were obtained through Twitter API. Each tweet's entire set of JSON data was stored in a file called `tweet_json.txt` file.


# File
* After the completion of data cleaning, a new data file containing all the necessary information is stored as `twitter_archive_master.csv.`
* Data wrangling, analysis, and visualisation code are stored in `wrangle_act.ipynb`.  Report `wrangle_report.pdf` briefly describes the wrangling effort.  
* `act_report.pdf` is a report based on the analysis and visualisation of the data. 
