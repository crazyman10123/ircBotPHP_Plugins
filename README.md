filter
------
This is a bad words filter. On startup, you should get a message saying 'missing badwords.txt'. This means that you need to create badwords.txt in the main directory, and put words (that should trigger the user being kicked) inside it. badwords.txt is a newline-seperated list, meaning one word per line.

This plugin has no commands. It simply kicks the user when they say any of the words contained in badwords.txt.
There is a Twitch compatible version included.


guessGame
---------
This plugin is a simple number guessing game, where you have to guess a random number between one and ten.

**Commands**

> `(prefix)guess <number>` - Sends the bot your guess, it will reply with **Nope, try again** or **You win**


isupService
-----------
The isupService plugin allows you to check whether a domain is online or not.

**Commands**

> `(prefix)isup <url>` - Returns whether the provided domain is online or offline


lmgtfyService
-------------
**Warning:** This can look snarky if you use it a lot, try and refrain from using it unless someone ask a stupid question.

The lmgtfyService (let me google that for you) is "For all those people who find it more convenient to bother you with their question rather than google it for themselves.". This plugin provides a search term on LMTFY and returns the URL.

**Commands**

> `(prefix)lmgtfy <search terms>` - Returns a lmgtfy url with the search terms entered


pastebinService
---------------
This simple plugin just returns the pastebin URL along with a message about not posting code in the channel.

**Commands**

> `(prefix)pastebin` - Returns the pastebin URL along with a message about not posting code in the channel


quotes
------
This plugin just returns a random, geeky quote whenever you run it. It requires a quotes.txt in the main directory, and this file should contain newline-seperated quotes, meaning one quote per line.

**Commands**

> `(prefix)quote` - Returns a random quote from quotes.txt


shortenService
--------------
This service shortens URLs to something like `tinyurl.com/<randomstring>`.

**Commands**

> `(prefix)shorten <url>` - Returns a shortened URL directing to the parameter passed.


feelingLuckyService
---------------------------
This service returns the Google I'm Feeling Lucky link for the query

**Comands**

> `(prefix)ifl <query>`

***