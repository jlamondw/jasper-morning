import tweepy
from tweepy.streaming import StreamListener
from tweepy import OAuthHandler
from tweepy import Stream
from tweepy import *

import sys
import time
import re

# Written by Marc Laventure 

WORDS = ["MORNING", "COMMUTE"] 

PRIORITY = 1

# Input is latest retweet, mention, direct message ID
def getNotifications(mic,latestRetweet,latestMention,latestDirectMessage, api):
      
    mic.say("yo yo yo")

    return

def handle(text, mic, profile):
    
    # consumer_key = profile['keys']["TW_CONSUMER_KEY"]

def isValid(text):
    
    # tweetBool = bool(re.search(r'\bTweet\b', text, re.IGNORECASE))

    if tweetBool:
        return tweetBool
    else:
        return False