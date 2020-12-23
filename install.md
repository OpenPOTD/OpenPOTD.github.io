---
layout: page
title: Get the Bot
---

First click the link <a href="https://discord.com/api/oauth2/authorize?client_id=763882474466967554&permissions=0&scope=bot">here</a> to add OpenPOTD to your server. 

From here you need to ensure you have a few things set up:

### Server Setup

1. Have a role for the bot which can manage roles, and ensure this role is higher than any other roles it will be managing.
2. Have a role for the bot to ping. **By default the bot looks for** `@*-of-the-day`.
3. Have a role for people who have succesfully solved the QOTD. **By default the bot looks for** `@*-solved`.
4. Have a channel for posting the QOTD. **By default the bot looks for** `#*-of-the-day`.
5. Have 3 roles set up, for bronze, silver, and gold medalists. 

### Bot Setup

Now that the your server is all set up, type in `%init`. The bot will look for the aforementioned settings, and if it doesn't find anything you will have to manually set them in the way you will set up other commands below. The general form is `%[setting] [arguments]`. 

The first command you should run is `%config`. You will get an infobox as such (but with some or all of the fields not filled in):

![My helpful screenshot](/assets/ss.png)

You can now set the command prefix with `%command_prefix` **BROKEN**. From here on this shall be assumed to be unchanged. 

If you now a good time to set up medal roles. Run the command `%medal_roles [bronze role] [silver role] [gold role]`. You now should have a minimal working configuration of OpenPOTD. However, there are some further commands which you can view by entering `%help`:

1. `%check`: By running `%check [question number or date] [your answer to question]` the bot will check to see if you have solved it correctly.
2. `%fetch`: Running `%fetch [question number or date]` posts the appropriate question in the channel in which the command is called. 
3. `%info`: **NEED TO DEPRECIATE**
4. `%manual`: **DEPRECIATE**
5. `%nick`: Running `%nick [new nickname]` 
6. `%rank`: Run `%rank [season number]` to get that season's rankings
6. `%score`: Run `%score [season number]` to get that season's scores
7. `%self`: Running `%self` gives information on yourself in regards to OpenPOTD
8. `%toggle_anon`: Toggles your `anonymous` field in the OpenPOTD database

You can also change any of these commands at any time, or run `%help [command]` to get example usage.
