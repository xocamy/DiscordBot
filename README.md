# DiscordBot
Interactable Queue system for your discord Bot! 

Issue: None of the major Discord Bots out there have a clear, conscise, scalable queue system.

Solution: Using fundamental concepts from data structures and algorithms class, I present an intuitive, 
          thoroughly tested interactive code that handles all aspects of queues. By using Emoji reaction buttons, your users can:
          create the queue (seperate queues made for seperate text-channels)
          view the queue, join, leave, and ping the User who is up next!
          
The code can be snipped and inserted into your current python bot.

Currently, the code is a template for the instantiation of a whole bot in and of itself, where alls you need to do is create a new bot on the discord dev site, insert your custom token, and find out a place to host it. 

It's important you use your insert your own discord bot token. I didn't design this with the intention of having it be used on multiple servers.

Keep in mind rate-limiting, some commands require the bot to scan for every text chat sent on the server. 
          
