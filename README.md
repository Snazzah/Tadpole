![BotBoy](https://raw.github.com/SnazzyPine25/Tadpole/master/tadpole-logo.png)
[![discord](https://img.shields.io/badge/discord-join-7289DA.svg)](https://discord.gg/0vjTDaDsgOQWUtlv)
============
A bot that connects multiple channels to each other.

## How to run
You need Ruby 2.3, Bundler.
First, install all the dependencies using `bundle install`. Then make a file called 1 `tadpole-auth` and follow this format:
```
TOKEN HERE
171456123456123456
```
Then, use `ruby tadpole.rb` to run it.

## Settings and Configuration
parsebots : Allow bot's messages through Tadpole bot.
max : Maximum connections allowed on one Tadpole.

### If you want Mention Prefixes:
In the file `tadpole.rb`, simply replace `USER_ID` with the bots User ID.

### If you want to control all commands everywhere:
In the file `tadpole.rb`, simply replace `158049329150427136` with your User ID.
