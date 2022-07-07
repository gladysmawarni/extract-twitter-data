# Extracting data from twitter
#### This repo has 2 scripts to extract data from twitter, by using Tweepy and Selenium.


### Tweepy
Tweepy is the twitter API wrapper for python, the documentation can be read [here](https://docs.tweepy.org/en/stable/).

In the script `twitter_tweepy` I utilize tweepy to get:
- Information about a user
- Information about the user's friends/followings
- The tweets for each users
- The trends in a specific place

### Selenium
[Selenium webdriver](https://www.selenium.dev/) is a browser automation library that can be used with Python to mimic a website and do some automation test.

In the script `twitter_selenium` I utilize selenium to:
- Login to twitter
- Search a user profile
- Get the tweets of said profile
