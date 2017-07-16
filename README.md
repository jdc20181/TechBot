# TechBot
A Bot that will help with basic operational technical questions of Windows. 

This bot is from [this](https://github.com/liouh/chat-bot) respo. 


Some important things:

- Bot isn't a replacement for official support from Microsoft, or any other help site articles. 

- Bot relies on a Small Scale set of keywords. So its going to be hard. - Maybe I will adapt another system? 

- The bot isn't always going to be accurate. It is a bot!

- The bot will cite a brief few things along with a Verified source of information. 

- The bot is not smart. (yet?)

- The bot is currently a work in progress

- The bot is open to new knowledge, you need a basic understanding of the code though!

# Creating New Knowledge (committing)

To Create a new solution to a problem you need to follow a few guidelines:

- Must be Tech related e.g. How to reset my iphone. 

- Must include a reliable reproducable solution from a offsite link. Don't provide big long solutions. 

- Commits must have reasonably good English, and sentence structure, including grammar.

Follow the example, publish all new knowledge in the `chat-bot.js` folder. 

`if(this.match('How to Clear Cookies') || this.match('Clear Browser Data') || this.match('Clear Browsing History'))
return "Clearing Browsing data can be done in your browsers settings. Here is a helpful link: https://kb.iu.edu/d/ahic";`

If these are not kept, your PR will be kindly declined. 

# Creating Issues

If it don't happen twice, don't report it :) if it occurs more than once across browsers, or after refreshing the page, continue:

General users - Include:

- Screenshot (if possible)

- Brief description of what is happening. 

- Platform, and webbrowser.

Developers:

- Screenshot 

- Desc of what is happening

- Platform, and webbrowser

- solutions, including PR. 
		
