# StratsBot

[![Build Status](https://david-dm.org/stratsbot/stratsbot.svg)](https://david-dm.org/stratsbot/stratsbot)
[![Build Status](https://travis-ci.org/StratsBot/StratsBot.svg?branch=master)](https://travis-ci.org/StratsBot/StratsBot)
[![Coverage Status](https://img.shields.io/coveralls/StratsBot/StratsBot/master.svg)](https://coveralls.io/github/StratsBot/StratsBot?branch=master)
<a href="https://zenhub.io"><img src="https://img.shields.io/badge/KanBan%20Board-Zenhub.io-blue.svg"></a>
[![Translations](https://img.shields.io/badge/Translations-Transifex-135d91.svg)](https://www.transifex.com/stratsbot/stratsbot/)
[![Discord](https://discordapp.com/api/guilds/128598463947472897/widget.png?style=banner)](https://discord.gg/0iXEgtjdHgkpdsVr)
## About

A fantastic, helpful, and fun [Discord](https://discordapp.com/) chat bot! StratsBot comes with a bunch of cool and powerful commands for both Discord and games!

## [Changelog](CHANGELOG.md)

## How to use
#### Invitation
The easiest way to set this bot up on your server is to invite it to your Discord server, It is currently hosted 24/7 and will always get the newest features first.

In order to do that, just [click here](https://discordapp.com/oauth2/authorize?&client_id=269429486192164866&scope=bot&permissions=268561430) and choose a server. You need to have **Manage Server** permission on that server. You may remove some of the permissions if you wish, but be warned it may break current and upcoming features.

If you want to give the bot a first try, you may do that in the [Strats.co](https://discord.gg/WpYhTf8) Discord server.

If you have any questions, feedback or want to request features, you may also do that by leaving a message in [Strats.co](https://discord.gg/WpYhTf8), private messaging Vocino, as well as opening an [issue on Github](https://github.com/stratsbot/stratsbot/issues/new).

For self hosting, click [here](#localconfig).

## Commands
#### Help:
- `!help fun` - List of fun commands
- `!help useful` - List of useful commands
- `!help info` - List of information commands
- `!help games` - List of game commands
- `!help other` - List of other commands
- `!help all` - List all available commands in private chat
- `!memelist` - List of meme names for the `!meme` command
- `!setlanguage` - Set all help text to respond in a specified language

#### Fun:
- `!8ball` *question* - Answers the question
- `!animals` - Get various animal pictures
- `!cat` bomb *count* - Bombs chat with adorable cats
- `!pug` bomb *count* - Bombs chat with adorable pugs
- `!snake` bomb *count* - Bombs chat with adorable snakes
- `!chat` *text* - Chats with you
- `!coin` - Flips a coin
- `!comics` - Get a random comic from a bunch of different artists
- `!decide` *something* **or** *something...* - Decides between given words
- `!drama` *number* - Responds with a drama image, if no number is written, a random one
- `!emoji` *number* - Responds with an emoji copypasta, if no number is written, a random one
- `!meme` *meme name "top text" "bottom text"* -  Creates a meme with the given meme name and text
- `!quote` *number* - Responds with a quote, if no number is written, a random one
- `!robohash` - Get robot and monster images
- `!monster` - Get your personal monster
- `!robot` - Get your personal robot
- `!robothead` - Get your personal robot head
- `!roll` *times sides* - Rolls the dice a number of times with a number of sides, see `!random` for advanced generators
- `!translate` - Translate text in funny ways
- `!leet` *sentence* - 1337ifies the sentence
- `!snoop` *sentence* - Snoopifies tha sentence
- `!yoda` *sentence* - Yodaifies the sentence

#### Useful:
- `!ddg` *search terms* - Search the web, can also calculate and convert. Search other websites by appending its shortening (e.g. `!ddg !yt Hello`) See <https://duckduckgo.com/bang> for a list.
- `!gif` *gif tags* - Gets a gif from Giphy or Popkey matching the given tags (Use `!giphy` or `!popkey` to search the specific sites)
- `!join` - Shows a link that can be used to invite StratsBot to your server
- `!random` - Generate truly random numbers and strings
- `!fraction` *amount* *decimal places* *replace(optional)* - Generate a number of random real numbers between 0 and 1 with set decimal places, write **replace** at the end to disable duplicates (e.g. `!fraction 1 5 replace`)
- `!gaussian` *amount* *mean* *deviation* *significant digits* - Generate a number of random numbers from a Gaussian distribution (e.g. `!gaussian 1 50 10 5`)
- `!integer` *amount* *min* *max* *replace(optional)* - Generate a number of random integers between min and max, write **replace** at the end to disable duplicates (e.g. `!integer 2 1 50 replace`)
- `!string` *amount* *length* *charset(optional)* *replace(optional)* - Generate a number of random strings of a given length, can also input your own charset (default is the alphabet), as well as write **replace** at the end to disable duplicates. (e.g. `!string 1 10 abc123 replace`)
- `!unshorten` *url* - Unshortens a shortened link
- `!urban` *search terms* - Returns the summary of the first matching search result from Urban Dictionary
- `!videocall` *__Optional__ @username* - Start a one click video call or screenshare directly on Appear.in. Mention users to make it private.
- `!wiki` *search terms* - Returns the summary of the first matching search result from Wikipedia
- `!wolfram` *query* - Query Wolfram Alpha for almost anything
- `!youtube` *video tags* - Gets a video from Youtube matching the given tags

#### Information:
- `!avatar` *username* - Responds with your avatar, unless a username is specified
- `!channelinfo` *channelname* - Gives information about this channel, unless a channelname is specified
- `!ping` - Pong! Check StratsBot's pulse
- `!serverinfo` *servername* - Gives information about this server, unless a servername is specified
- `!servers` - Lists how many servers, channels and users the bot is connected to
- `!uptime` - Shows how long the bot has been online
- `!userinfo` *username* - Gives information about this user, unless a username is specified
- `!version` - Get information on the latest version of StratsBot

#### Games:

**Dota2**
- `!dota2` - Help
- `!dota2 best` *position* - Get the top 10 Heroes for a specific position
- `!dota2 build` *hero-name* - Get the most popular build for a Hero
- `!dota2 counters` *hero-name* - Get the top 10 counters for a Hero
- `!dota2 impact` - Get the top 10 Heroes with the biggest impact
- `!dota2 items` *hero-name* - Get the top 10 most used items for a Hero

**League of Legends**
- `!lol` - Help
- `!lol bans` - Get the top 10 most common bans
- `!lol best` *position* - Get the top 10 best champs for a position
- `!lol counters` *champ-name position* - Get the top 10 counters for a Champion and Position
- `!lol items` *champ-name position* - Get the highest win item sets for a Champion and Position
- `!lol match` *region summoner-name* - Get rank, champ, winrate, and games for all players in a __current__ match.
- `!lol skills` *champ-name position* - Get the highest win skills for a Champion and Position
- `!lol status` - Get the LoL Game and Client server status for all regions

**Overwatch**
- `!ow` - Help
- `!ow averages region battletag` - Player average stats
- `!ow time played region battletag` - Heroes most played
- `!ow games won region battletag` - Heroes with the most wins
- `!ow win percent region battletag` - Heroes with the highest win percentage
- `!ow eliminations region battletag` - Heroes with the most eliminations per life
- `!ow kill streak region battletag` - Heroes with the highest kill streak
- `!ow multikill region battletag` - Heroes with the most multikills
- `!ow objective kills region battletag` - Heroes with the most objective kills

#### Other:
- `!ayylmao`
- `!chillinmyb`
- `!endall`
- `!feelsbadman`
- `!feelsgoodman`
- `!jpeg`
- `!kappa`
- `!kappaHD`
- `!skeltal`
- `!starwars4`
- `!starwars5`

---

## Feature Requests

Have a feature in mind? We'd love to hear about it. Feel free to [open an issue](https://github.com/stratsbot/stratsbot/issues/new) and let us know.

## Contribute

Want to contribute to StratsBot? That's great! Be sure to check out the [CONTRIBUTE.md](CONTRIBUTE.md) doc for more information on how.

## Contributors

- Travis Vocino *(Maintainer)* - [@Vocino](https://github.com/vocino)
- Gravestorm *(Maintainer)* - [@Gravestorm](https://github.com/Gravestorm)
- Dustin Blackman *(Maintainer)* - [@dustinblackman](https://github.com/dustinblackman)

## [License](LICENSE)
