slack-boobs-bot
======
![Slack.com logo](https://slack.global.ssl.fastly.net/8872/img/landing_slack_hash_wordmark_logo.png "Slack.com")

Bot for Slack chat that posting great boobs images.


How it works
===

If this bot is integrated, it sends great tits image to channel, where keyword was triggered.
Bot integrates with Slack via Slack Webhooks mechanism.
This bot available at URL ```http://slack-boobs-bot.herokuapp.com/boobs```.
Everytime request is comming to ```http://slack-boobs-bot.herokuapp.com/boobs``` path, bot sends back payload with tits image.


Configuring Outgoing Webhook
---

Everything is simple. Slack should send a POST request to bot's url ```http://slack-boobs-bot.herokuapp.com/boobs```, like here:

![Configuring Outgoing Webhook](http://s3.postimg.org/j185vokqb/Screenshot_2014_04_26_13_13_50.png "Configuring Outgoing Webhook")

Then it responds with payload to Slack.

Credits
====

Thanx to guys from http://oboobs.ru for great API.
