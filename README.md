# Waffle Bot 

<img src="images/banner.png"> 

<p align="center">
    <b>An all-purpose Discord bot made with <a href="https://discord.js.org/#/">Discord.js</a></b>
</p>

### About Waffle Bot 
Waffle Bot is an all-purpose Discord bot born from the [Harvard Live](https://discord.gg/harvard) Discord server.  The first iteration of Waffle Bot was a funky little bot named Dapperwheel, who would insult specific users whenever they spoke.  Since then, Waffle Bot has come a long way from a spite-fueled fancy man on a [Onewheel](https://onewheel.com/) (hence the name Dapperwheel). 

Today, Waffle Bot connects users and brings together online communities.  Read more about Waffle Bot and invite it to your server today! 

    Author: Bella Tarantino 
    Current Release: Version 1.0.0
    Release Date: TBD 
    Last Updated: TBD 


### Key Features
`Version 1.0.0` of Waffle Bot is a work in progress and is more pared down than the version existing users may be familiar with.  Below is a list of the basic commands that Waffle Bot currently supports. 

#### Regular Commands
These commands require no special permissions or access. All users that share a server with Waffle Bot can use them. Regular commands should be sent in the server and not in Waffle Bot's DMs. 
```
w!help < command name >
    if given no argument, lists all regular Waffle Bot commands

    if given a valid command name, lists information about a specific command

w!ping
    pings Waffle Bot to check that it is online

w!user < @user || nickname || user id >
    displays information about the requested user

    should multiple users have the same nickname, whichever appears first in the user list is chosen

    if no argument is provided, the default user is the sender

w!server 
    displays information about the server the command is sent in 

w!coin
    flips a coin for the user. returns heads or tails.

w!roll 
    rolls a 6-sided die. returns an integer 1-6.
```

#### Moderator Commands 
These commands require `MANAGE_SERVER`, `MANAGE_MESSAGES`, `KICK_MEMBERS`, and `BAN_MEMBERS` permissions to use. Moderator commands should be sent in the server and not in Waffle Bot's DMs. 
```
w@help < command name >
    if given no argument, lists all Waffle Bot moderator commands

    if given a valid command name, lists information about a specific command

w@kick < @user > < message >
    kicks @user. if there is a second argument, Waffle Bot will attempt to DM the user with that message before kicking them  

w@ban < @user > < reason > < message >
    bans @user for the requested reason

    if there is no reason provided, will default to "Waffle Bot Ban" 

    if there is a third argument, Waffle bot will attempt to DM the user with the requested message before banning them
```

### Use Waffle Bot
Because Waffle Bot is not yet public to all users, if you would like to add Waffle Bot to your server, please fill out [this form](https://forms.office.com/Pages/ResponsePage.aspx?id=DQSIkWdsW0yxEjajBLZtrQAAAAAAAAAAAAe__YPWX79URUlHRThLSkk0OFk2Tk5HQVEwVkFEQ1ZaSy4u). Once your request has been approved, you will be given a temporary invite link. The information you provide in the form may be used to reach out to you with feedback requests. 

### Dependencies 
Waffle Bot is made with [Node.js](https://nodejs.org/en/about/). All dependencies are listed below. 

`Discord.js`

### Version History 

#### 1.0.0
Released on `DATE`. \
\
&ensp;&ensp;&ensp;<img src="images/waffle_spin.gif" height=15px> Initial release
