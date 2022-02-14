# GBV
Data and Codes for the Gender Based Violence Paper
Download the required codes and Data from the path : https://drive.google.com/drive/folders/1wsIHm9ZFOt-DM9p8NiLaOQcjIhOWGHbR?usp=sharing

Read out following instructions for using the data and running the codes.
Data
Following is the description of all the data.
1. Unzip Data_Github.zip 
2. The folder contains four folders for all the four categories of considered tweets i.e. physical(physical violence tweets), sexual(sexual violence tweets), harmful(harmful practices tweets) and generic (generic tweets).  
3. For physical, sexual and harmful folders there are yearwise subfolders 2016,2017,2018. Within these folders there are multiple files containing the required tweet ids (01, 02, 03...).
4. The folder generic/ contains files 01, 02, 03 .... which has the required tweet ids for generic tweets. 
5. The code /Codes/crawl_tweet.py can be used to collect required meta-data from the tweet-ids.

Codes 
Unzip Codes.zip and all the required codes are present in this.
Following are description of all the codes.
1. preprocess.py : For preprocessing
2. location_tagging.py : For tagging location
3. divide_tweets_countrywise.py : For dividing tweets countrywise
4. generate_countrywise_words.py : For generating words for further analysis
5. get_correlation.py : For calculating correlation
6. create_graph.py : For creating graph between countries
7. get_correlation_catwise.py : For calculating correlation of different GBV categories
8. create_desired_country_folder.py : For considering tweets from the considered countries
9. calculate_document_frequency.py : For calculating document frequency of words.
10. create_random_tweets.py : For creating random tweets for each considered country
11. plot_scatter_random.py : For plotting scatter plots
12. get_most_freq_random.py : For getting most frequent words
13. filter_harmkeywords.py : For filtering harmful violence keywords
14. filter_phykeywords.py : For filtering physical violence keywords
15. filter_sexkeywords.py : For filtering sexual violence keywords

INPUT FILES
Few codes requires input files which are present in the Codes/ folder such as HarmPrac.txt, world_gazeteer.csv, ...

OUTPUT FILES
There are a few interim output files which are saved in the folder /Codes/outputs/

