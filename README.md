# Twitter-Sentiment-Analysis
What is sentiment analysis?</br>
Sentiment Analysis is the process of ‘computationally’ determining whether a piece of writing is positive, negative or neutral. It’s also known as opinion mining, deriving the opinion or attitude of a speaker.
</br>
Why sentiment analysis?</br>
</br>
Business: In marketing field companies use it to develop their strategies, to understand customers’ feelings towards products or brand, how people respond to their campaigns or product launches and why consumers don’t buy some
products.
Politics: In political field, it is used to keep track of political view, to detect consistency and inconsistency between statements and actions at the government level. It can be used to predict election results as well!
Public Actions: Sentiment analysis also is used to monitor and analyse social phenomena, for the spotting of potentially dangerous situations and determining the general mood of the blogosphere.
Installation:</br>
</br>
Tweepy: tweepy is the python client for the official Twitter API.</br>
Install it using following pip command:</br>
pip install tweepy</br>
TextBlob: textblob is the python library for processing textual data.</br>
Install it using following pip command:</br>
pip install textblob</br>
Also, we need to install some NLTK corpora using following command:</br></br>

python -m textblob.download_corpora</br>
(Corpora is nothing but a large and structured set of texts.)</br>
</br>
Authentication:</br>
In order to fetch tweets through Twitter API, one needs to register an App through their twitter account. Follow these steps for the same:</br></br>
Open this link and click the button: ‘Create New App’</br>
Fill the application details. You can leave the callback url field empty.</br>
Once the app is created, you will be redirected to the app page.</br>
Open the ‘Keys and Access Tokens’ tab.</br>
Copy ‘Consumer Key’, ‘Consumer Secret’, ‘Access token’ and ‘Access Token Secret’.</br>
