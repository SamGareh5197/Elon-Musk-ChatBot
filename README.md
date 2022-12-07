# Elon-Musk-ChatBot
Have you ever wanted to chat to Elon Musk?

Now you can!!!

After downloading the elon_tweets.txt and ElonBot.ipynb files, just run the python script. Then ask him questions and watch him reply!

Check out the ElonBot Example Text file to see a typical conversation with this ChatBot.


### Dataset

In order to compile a large dataset of Elon Musk quotes, vocabulary and phrases, I scraped 100,000 of his tweets from Twitter using the Twitter Scraper script which I wrote. This can be found in the repository. After preproccessing the tweets, they were ready to be used on this ChatBot.


### Commands

In order to responsed negatively or exit the conversation, some predetermined commands had to be chosen. They are as follows:

negative_responses = ("no", "nope", "nah", "naw", "not a chance", "sorry", 'nothing', 'not')
exit_commands = ("quit", "pause", "exit", "goodbye", "bye", "later", "stop", "finish")

