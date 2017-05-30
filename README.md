# Extracting images from the #machinelearningflashcards twitter hashtag
A very basic Python script to pull machine learning flashcards from Chris Albon's #machinelearningflashcards hashtag

All work on the flashcards are the work of Chris Albon (@chrisalbon).

Project was inspired by [Jasmine Dumas'](http://jasdumas.github.io/) [project](https://github.com/jasdumas/ml-flashcards) in R.

### Instructions
In order to access the Twitter API you need a Consumer Key and Consumer Secret Key. You can obtain these by using your Twitter account to create a twitter app at https://apps.twitter.com/app/new. Proceed to fill out the required information.

Once completed you'll be taken to a page containing the Consumer Key and Consumer Secret Key. Place these keys in a file called twitter_keys.py in the main directory. The python file you create should have two variables `consumer_key` and `consumer_secret` which should contain the keys you just obtained from twitter. The file should look something like this.

```python
# Variables that contains the user credentials to access Twitter API
consumer_key = "ENTER CONSUMER KEY HERE"
consumer_secret = "ENTER CONSUMER SECRET KEY HERE"
```


