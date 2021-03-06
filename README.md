# Instagram Manager Bot
The most advanced Instagram Downloader Bot.

You can Download almost anything From your Instagram Account.

**What Can Be Downloaded?:**
```
    1. All posts of any Profile. (Both Public and Private profiles which you follows.)
    2. All Posts from your feed.
    3. Stories of any profile (Both Public and Private profiles which you follows.)
    4. DP of any profile (No need to follow)
    5. Followers and Followees List of any Profile.
    6. Stories of your Followees.
    7. Tagged posts of any profile.
    8. Your saved Posts.
    9. IGTV videos.
    10. Highlights from any profiles.
    11. Any Public Post from Link(Post/Reels/IGTV)

```

**Available Commands and Usage**
```
/start - Check wheather bot alive.
/restart - Restart the bot (If you messed up anything use /restart.)
/help - Shows this menu.
/login - Login into your account.
/logout - Logout of your account.
/account - Shows the details of logged in account.

/posts <username> - Download posts of any username. Use /posts to download own posts or  /posts <username> for others.
Example : /posts samantharuthprabhuoffl

/igtv <username> - Download IGTV videos from given username. If no username given, downloads your IGTV.

/feed <number of posts to download> - Downloads posts from your feed.If no number specified all posts from feed will be downloaded.
Example: /feed 10 to download latest 10 posts from feed.

/saved <number of posts to download> - Downloads your saved posts. If no number specified all saved posts will be downloaded.
Example: /saved 10 to download latest 10 saved posts.

/followers <username> - Get a list of all followers of given username. If no username given, then your list will be retrieved.
Example: /followers samantharuthprabhuoffl

/followees <username> - Get a list of all followees of given username. If no username given, then your list will be retrieved.

/tagged <username> - Downloads all posts in which given username is tagged. If nothing given your tagged posts will be downloaded.

/story <username> - Downloads all stories from given username. If nothing given your stories will be downloaded.

/stories - Downloads all the stories of all your followees.

/highlights <username> - Downloads highlights from given username, If nothing given your highlights will be downloaded.

```

### Deploy to Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/NET-HACKER-BOTs/Instagram-bot)

While Deploying fill `INSTA_SESSIONFILE_ID`, either by running [generate_instagram_session.py](https://github.com/NET-HACKER-BOTs/Instagram-Bot/blob/main/generate_instagram_session.py]) in terminal or using /login after deploy or use [repl.it](https://replit.com/@subinps/generateInstagramSession)

For Generating Session after deployment, You Must leave the Variable as blank and fill manually after generating `INSTA_SESSIONFILE_ID` from your bot by sending /login.


### Deploy to VPS

```sh
git clone https://github.com/NET-HACKER-BOTs/Instagram-bot
cd Instagram-Bot
pip3 install -r requirements.txt
# <Create Variables appropriately>
python3 main.py
```

### Variables

* `API_HASH` API Hash from [my.telegram.org](https://my.telegram.org/)
* `API_ID` API ID from [my.telegram.org](https://my.telegram.org/)
* `BOT_TOKEN` Bot token from [@BotFather](https://telegram.dog/BotFather)
* `OWNER_ID` Telegram Id of Owner.
* `INSTAGRAM_USERNAME` Your Instagram username
* `INSTA_SESSIONFILE_ID` Your Instagram session file ID. Generate either by running [generate_instagram_session.py](https://github.com/NET-HACKER-BOTs/Instagram-Bot/blob/main/generate_instagram_session.py]) in terminal or using /login after deploy or use [repl.it](https://replit.com/@subinps/generateInstagramSession)



#### Support

Connect Me On [Telegram](https://telegram.dog/ImBhashitha)


```
LEGAL DISCLAIMER

Developer or his team won't be liable for any loss caused by MISUSE of this Script.
This Bot is Indended to be used only for Educational Purposes.

```
