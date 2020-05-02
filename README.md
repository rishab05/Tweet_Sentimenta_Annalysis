# Tweet_Sentimental_Annalysis
User input a query(topic) and this program run Sentimental analysis on  tweets and show percentage of positive, negative and neutral tweets and also display top 10 tweets.


### Getting Started
To run this repository clone or download using above link.

### Prerequisites
 * Python-3.6
 * TextBlob
 * tweepy


#### Installing
Go to tweet_env1 (It is a python virtual environment)
```
$ source bin/activate
```
Or create your own python virtual environment
```
$ python3 -m env twee-env
$ cd twee-env
$ source bin/activate
```

Now after activating environment install two modules
```
$ pip install textblob
$ pip install tweepy
# Also, we need to install some NLTK corpora 
$ python -m textblob.download_corpora
#Corpora is nothing but a large and structured set of texts.
```

## Authentication:
In order to fetch tweets through Twitter API, one needs to register an App through their twitter account. Follow these steps for the same:

Open https://apps.twitter.com/ 
* and click the button: ‘Create New App’
* Fill the application details. You can leave the callback url field empty.
* Once the app is created, you will be redirected to the app page.
* Open the ‘Keys and Access Tokens’ tab.
* Copy ‘Consumer Key’, ‘Consumer Secret’, ‘Access token’ and ‘Access Token Secret’.
* open twee_sentan.py file and paste all these in the file and save it. After that run the python file.

Run the file after activating env and installing all the libraries 

```
$ python twee_sentan.py
#or
$ python3 twee_sentan.py
```


Created with :heart: by Rishabh Sharma
