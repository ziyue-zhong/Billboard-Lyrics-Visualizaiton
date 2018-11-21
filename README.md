# Billboard-Lyrics-Visualizaiton

## Data

1964-2015 Billboard Hot100 Lyrics downloaded from Kaggle
https://www.kaggle.com/rakannimer/billboard-lyrics


## Project Details

First, I used python to process the excel data file which contains 4583 songs. I used NLTK package to tokenize the lyrics into tokens. Then, I removed the stop words, numbers and transformed all the text into lower case. In order to prepare the data for visualization in tableau, I also reshape the dataset in python to make sure each token is represented as an individual record in the data.

I then build the visualization in tableau. In order to make the information straightforward, I created the word map which shows the most frequent words appeared in lyrics of a specific song or in a specific year. Also, I drill down to show the trend of word 'love' during each time period. Also, I look at other dimensions by identifying the popular artisits in the last 50 years.

You can see the interactive viz through this link: https://public.tableau.com/profile/ziyue.zhong#!/vizhome/1965-2015BillboardHOT100SongsAnalysis/Dashboard2

