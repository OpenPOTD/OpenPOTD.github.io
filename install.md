---
layout: page
title: Get the Bot
---

First click the link here to add OpenPOTD to your server: https://discord.com/api/oauth2/authorize?client_id=763882474466967554&permissions=0&scope=bot

Once OpenPOTD is in your server, use the `%init` command to initialise OpenPOTD. OpenPOTD will try to infer the correct settings for your server; check if it's right with the `%config` command. If you would like to change any settings manually, use `%[setting name] [new setting]`, for example, `%potd_channel #problem-of-the-day`. 

Medal roles are slightly different. They should be set with `%medal_roles [bronze_role] [silver_role] [gold_role]`. 

Please make sure OpenPOTD has permissions to post in the designated problem channel. Furthermore, if you want OpenPOTD to be able to give and remove roles based on solving, please make sure OpenPOTD has the `Manage Roles` permissions and OpenPOTD's highest role is higher than the solver role. The same is true for medal roles. 
