# bitcoinTwitterFeed
Data sets containing the twitter feed related to Bitcoin and the Bitcoin price against USD.

The data is collected from June 2018 till mid Dec 2018, around 29.75 million tweets are collected. There were some days when the server went down and the tweets were not collected. 

This is divided into two datasets, the first dataset of the tweets are collected by filtering the twitter strem using the following filter:
'bitcoin','btc','bitcoinprice','bitcoinnow','XBT','BTCUSD','XBTUSD', 'blockchain'.
The files are named twitterFeed*. Please note that due to the limitation on file size that can be uploaded to GitHub twitterFeed7.txt is zipped and then split into two files - twitterFeed7_2.7z.001 and twitterFeed7_2.7z.002.

The second dataset is collected using the following filters:
'#bitcoin','#btc','#bitcoinprice','#bitcoinnow','#XBT','#BTCUSD','#XBTUSD' 
The files are named twitterFeedBitcoin*
