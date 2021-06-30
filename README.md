## ***Yeet Bot***
This is my first Discord Bot.
It is a simple bot with a few Utility and meme commands.

### Functions:

* Post's Memes from Reddit
* Can fetch post's from any subreddit
* Server Statistics commands
* Minigames like 8ball,One Word Story and Rock-Paper-Scissors
* Space commands to find the time on Mars or to get the names of astronauts in Space
* Image manipulation with Pillow (Meme maker,Photo effects,Add text to images)
* Other of Memey commands

### Pictures:
![Meme](https://github.com/shri30yans/YeetBot/blob/main/Images/meme.jpg)   
*Post's memes from Reddit* 

![Reddit Search](https://github.com/shri30yans/YeetBot/blob/main/Images/reddit_search.jpg)   
*Getting post's from subreddit*   
 
![Space](https://github.com/shri30yans/YeetBot/blob/main/Images/space.jpg)   
*Space Commands*
     
![Wanted](https://github.com/shri30yans/YeetBot/blob/main/Images/image_manipulation.jpg)   
*Image manipulation with PIL*  

![Help Command](https://github.com/shri30yans/YeetBot/blob/main/Images/help.jpg)   
*Other Commands*   



### Basic Setup:
1. Install all the required modules with:

```
pip install -r requirements.txt
```

2. Obtain a Discord bot token from the [Discord developer portal](https://ptb.discord.com/developers/applications/)
3. Create a new Reddit Application from [Here](https://www.reddit.com/prefs/apps)
3. Create a .env similiar to the .env sample.
4. Fill in config.py with the required details including Reddit Application information.

### Setup for Heroku:
1. Create a new Reddit Application from [Here](https://www.reddit.com/prefs/apps)
2. Fork this repository and fill in config.py.
3. Obtain a Discord bot token from the [Discord developer portal](https://ptb.discord.com/developers/applications/)
4. On Heroku, open your App. Click on the Settings tab and scroll down to Buildpacks.
5. Within the settings for project in Heroku, create the following `Config Vars` to configure the Discord Bot Token

```
Python (Select it from the officially supported buildpacks)
```

### Run script:

    python bot.py
