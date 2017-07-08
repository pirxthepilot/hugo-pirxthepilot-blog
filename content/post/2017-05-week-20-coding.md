+++
date = "2017-05-21T08:53:17-05:00"
categories = []
keywords = []
description = ""
title = "Week 20: Coding"

+++

Back to coding this last week, where I wrote Python code for a Ninjam/Slack chat bot:

**[ninjam-slack-bot on github](https://github.com/pirxthepilot/ninjam-slack-bot)**

> Monitors a Ninjam server and sends notifications to a Slack channel everytime someone logs in. Also reports the count and list of currently logged in users.

I used [Errbot](http://errbot.io) as the chat framework. It's also my first project with Python 3!

I got to revisit the use of the `threading` library, and learned several new things along the way, the most useful of which is `Queue()` - indispensable as it provided a very convenient means for the Ninjam-side and Slack-side processes to send messages to each other.

For now, the bot is up and running in my otherwise-gathering-dust Raspberry Pi 3. I'll have to find a more suitable server to host it in for the long term.
