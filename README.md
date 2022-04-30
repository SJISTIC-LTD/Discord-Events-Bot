# Discord-Events-Bot
We'll be using the discord.py Python library to write the code for the bot. discord.py is an API wrapper for Discord that makes it easier to create a Discord bot in Python.

How to Create a Repl and Install discord.py
You can develop the bot on your local computer with any code editor. However, in this tutorial, we'll be using Repl.it because it will make it simpler for anyone to follow along. Repl.it is an online IDE that you can use in your web browser.

Start by going to Repl.it. Create a new Repl and choose "Python" as the language.

To use the discord.py library, just write import discord at the top of main.py. Repl.it will automatically install this dependency when you press the "run" button.

If you prefer to code the bot locally, you can use this command on MacOS to install discord.py:

python3 -m pip install -U discord.py

You may have to use pip3 instead of pip.

If you are using Windows, then you should use the following line instead:

py -3 -m pip install -U discord.py

How to Set Up Discord Events for Your Bot
discord.py revolves around the concept of events. An event is something you listen to and then respond to. For example, when a message happens, you will receive an event about it that you can respond to.

Let’s make a bot that replies to a specific message. This simple bot code, along with the code explanation, is taken from the discord.py documentation. We will be adding more features to the bot later.

Add this code to main.py. (You can name the file something else if you like, just not discord.py.) I'll explain what all this code does shortly.
