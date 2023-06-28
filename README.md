<a href="https://discord.gg/8rxZVWdcze">
    <img src="https://img.shields.io/discord/681882711945641997?color=7289DA&label=Join our server&logo=discord&style=for-the-badge" alt="Discord">
</a>

# Coding-Bot-v6

> The sixth version of the beloved Coding Bot

## What is Coding-Bot-v6

Coding-Bot-v6 is a community bot designed to assist and support programmers within our coding community. It is the sixth version of our bot and offers advanced features and enhancements. The bot provides code-related help, suggestions, snippets, and fun.


## Commands

| Special Permissions | Name (prefixes) | Description | Usage |
| --------- | --------- | --------- | --------- |
| Owner Only | **Sync** | Sync all the slash commands globally | `{prefix}sync`
| Owner Only | **load** | Load a Cog. | `{prefix}load [cog]` |
| Owner Only | **unload** | Unload a Cog. | `{prefix}unload [cog]` |
| Owner Only | **reload** | Reload a Cog. | `{prefix}reload [cog]` |
| Owner Only | **loadall** | Load all Cog. | `{prefix}loadall` |
| Owner Only | **unloadall** | Unload all Cog. | `{prefix}unloadall` |
| Owner Only | **reloadall** | Reload all Cog. | `{prefix}reloadall` |
| Owner Only | **getusermetric** | Get User Metrics. | `{prefix}getusermetric [member]` |
| None | **trash** | Throw someone in the trash. | `{prefix}trash [user]` |
| None | **number** | Gets a random number. | `{prefix}number`: *will get a random number* <br> `{prefix}number [number]`: *will get the [number]*
| None | **meme** | Gets a random meme. | `{prefix}meme`: *will get a random meme* |
| None | **joke** | Gets a random joke. | `{prefix}meme`: *will get a random joke* |
| None | **eightball** | Returns a random response. | `{prefix}eightball [question]`: *will return a random response* |
| None | **token** | Generates a random token. | `{prefix}token`: *will generate a token* |
| None | **binary** | Commands for binary | `{prefix}binary` |
| None | **binary encode** | Encodes plaintext and return binary | `{prefix}binary [text]`: *return encoded text* |
| None | **binary decode** | Decode binary text to plaintext | `{prefix}binary [text]`: *return plaintext* |
| None | **reverse** | Reverse inputted string | `{prefix}reverse [string]`:*returns string reversed* | 
| None | **owofy** | Owofy inputted string | `{prefix}owofy [text]`:*returns owofy text* |
| None | **mock** | Mockify inputted string | `{prefix}mock [text]`:*returns mocked text* |
| None | **beerparty** | Start a beerparty 🍻!! | `{prefix}beerparty [reason]`:*start a beer party* |
| None | **source** (github, code) | Get the source of this bot | `{prefix}source` *will send link to my source code* <br > `{prefix}source [command]` *will send link to the source code of the command* <br> `{prefix}source [command] [subcommand]`: <br> *will send link to the source code of the subcommand*
| None | **define** | Gets deinitions from Urban Dictionary. | `{prefix}define [word]` *will send the definition of the word* |
| None | **avatar** | Commands for getting avatars. | `{prefix}avatar` *will send a list of available methods* |
| None | **avatar main** | Start a beerparty 🍻!! | `{prefix}avatar main [user]` *will send the main avatar of the user* |
| None | **avatar display** | Start a beerparty 🍻!! | `{prefix}avatar display [user]` *will send the display avatar of the user* |
| None | **helper** | Help command for helpers to manage the help channels | `{prefix}helper` *will send a list of available commands* |
| None | **helper warn** | Warns a member breaking rules in help channels | `{prefix}helper [member] [reason]` *will give the member a warning for x reason* |
| None | **helper warnings** | Shows a list of help warnings for a member. | `{prefix}helper warnings[<member]` *will give a list of warnings of the member* |
| None | **helper clearwarnings** | Clears a help warning from a member. | `{prefix}helper clearwarning [member] [index]` *will give the member a warning for x reason* |
| None | **helper ban** | Ban a member from help channels | `{prefix}helper [member] [reason]` *will ban from help channels for x reason* |
| None | **helper unban** | Unban a member from help channels | `{prefix}helper [member]` *will unban from help channels* |
| None | **helper verify** | Help verify a member | `{prefix}verify [member]` *will verify a member if the member can't be verified* |







## Self-Hosting: 
### Requirements
* [Python 3.10+](https://www.python.org/downloads/)
* [Modules in requirements.txt](https://github.com/The-Coding-Realm/coding-bot-v6/blob/master/requirements.txt)

### Quick Start
```sh
git clone https://github.com/The-Coding-Realm/coding-bot-v6.git  #Clone the repository
cd coding-bot-v6                   #Go to the directory
python -m pip install -r requirements.txt   #Install required packages
```

### Configuration
1. Rename .env.example to .env
2. Replace the empty space with your token:
```
TOKEN = your_token.here
```


After installing all packages and configuring your bot, start your bot by running `python main.py`


## Contribution
Coding Bot V6 is an open sourced discord bot, and we are looking more contributors to improve its code. Please check the wiki section reagarding to [How to Contribute](https://github.com/The-Coding-Realm/coding-bot-v6/wiki/How-To-Contribute)
