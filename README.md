# Project Wrangle and Analyze Data - README
## Overview
Project Wrangle and Analyze Data was the second project carried out during the ALX - Udacity Nanodegree in Data Analytics. The project focused on real-world data, which rarely comes clean. Utilizing Python and its libraries, we embarked on a journey to gather data from various sources and in a variety of formats, assess its quality and tidiness, and subsequently clean it for exploratory analysis.

## Project Description
For this project, we chose to wrangle the tweet archive of Twitter user @dog_rates, popularly known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs, accompanied by humorous comments about the dog. The primary objectives of the project were as follows:

- **Data Gathering:** We gathered three different pieces of data from various sources using different methods. The primary data sources were as follows:

**twitter_archive_enhanced.csv:** This file was given in our Udacity workspace and was manually downloaded.
image_predictions.tsv: Hosted on Udacity's servers, this file was programmatically downloaded using the Requests library. The file was accessed from [here](https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv.)
- **Twitter API:** Using the Python tweepy library, we gathered additional data for each tweet, including retweet count and favorite ("like") count. This data was collected based on the tweet IDs found in the WeRateDogs Twitter archive data.
- **Data Assessment:** We assessed the gathered data through both visual and programmatic assessment methods. Visual assessment involved displaying each piece of data in the Jupyter Notebook for easy observation. Programmatic assessment, on the other hand, was carried out using pandas' functions and/or methods to identify any quality and tidiness issues within the datasets.

- **Data Cleaning:** The identified quality and tidiness issues were addressed through appropriate data cleaning techniques. This step ensured that the datasets were ready for further exploratory analysis.

- **Data Integration:** Finally, the gathered, assessed, and cleaned twitter archive data sets were merged into a master dataset. This master dataset was saved to a CSV file named "twitter_archive_master.csv," which was then used for the subsequent exploratory analysis.

## Repository Contents
The GitHub repository for Project Wrangle and Analyze Data contains the following files:

- **wrangle_and_analyze_data.ipynb:** This Jupyter Notebook is the main file that contains the entire data wrangling process, from data gathering to exploratory analysis.

- **twitter_archive_enhanced.csv:** This CSV file contains the raw data of the Twitter archive, which was manually downloaded.

- **image_predictions.tsv:** This TSV file contains the raw data from the image predictions, which was programmatically downloaded from Udacity's servers.

- **twitter_archive_master.csv:** This CSV file is the merged and cleaned dataset, ready for exploratory analysis.

- **README.md:** The README file you are currently reading, providing an overview of the project and repository contents.

## Requirements
To run the Jupyter Notebook and execute the data wrangling process, you will need the following dependencies:

- Python 3.10
- pandas
- NumPy
- requests
- tweepy
- Jupyter Notebook
Ensure that you have the necessary libraries installed before running the notebook.

## Data Source and Credits
The primary data for this project was sourced from the following:

- Udacity's Data Analytics Nanodegree Program (https://www.udacity.com/)
- Twitter API (https://developer.twitter.com/en/docs/twitter-api)
Special thanks to Udacity and Twitter for providing the data required for this analysis.

## License
The code and content in this repository are licensed under the MIT License. Feel free to use and modify the code as needed, but please acknowledge the original source.

## Acknowledgments
We would like to express our gratitude to ALX and Udacity for providing an excellent learning opportunity through the Data Analytics Nanodegree program.

For any questions or inquiries, please feel free to contact us.

Happy Data Wrangling and Analysis!
