# DEPRECATED JUST USE [NORMAL VERSION](https://github.com/Glaxier0/discord-bot-reddit-java)
# discord-bot-reddit-java-free-version
 A discord bot project that gathers posts from reddit and post them in discord channel.
 
### Used APIs ###
Reddit API - [JRAW Wrapper](https://github.com/mattbdean/JRAW)

Vimeo API - [clickntap Java SDK](https://github.com/clickntap/Vimeo) 

Vimeo API let us watch reddit videos directly in discord via embed. Any video hosting site can be used instead of Vimeo

Keep in mind vimeo has free 10 daily video upload quota. 

This version of bot is vimeo api free quota version. [If you have vimeo plus upgrade click me](https://github.com/Glaxier0/discord-bot-reddit-java) 

Basically what it does is keep deleting videos in vimeo account so our 10 quota limit refreshes. 

Difference between this version and normal version is free version can only hold 10 video at a time. 
Plus version can hold lots of videos. If you have vimeo plus don't bother with free version.

Discord API - [JDA Wrapper](https://github.com/DV8FromTheWorld/JDA)

### Things needed for project to work ###

Don't forget to edit application.properties in resources folder.

Reddit username, reddit password, reddit personal use script from [here](https://www.reddit.com/prefs/apps) 
Reddit client_id, client_secret.

Vimeo API TOKEN from [here](https://developer.vimeo.com/apps) with auth(you) public, private, create, edit, delete, upload scopes

DISCORD API BOT TOKEN from [here](https://discord.com/developers/applications)

An sql database named reddit_bot

reddit_bot database needs posts table.

[Table create script for postgresql](https://github.com/Glaxier0/discord-bot-java/blob/master/postgresql-create-script.md)

Some error may occur while creating table from script so an sql knowledge needed.

[Example bot created by me](https://discord.com/api/oauth2/authorize?client_id=855806720834928641&permissions=139623589952&scope=bot%20applications.commands)


