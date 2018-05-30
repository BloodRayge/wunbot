# wunbot

wunbot is a Discord bot written in [Python](https://www.python.org "Python homepage"). It launches predesignated files in "bot directory/files"

![](gluten-free)
<img src="https://forthebadge.com/images/badges/gluten-free.svg">
### How do I set it up?
 
Simply replace apikey with your discord bot's apikey and run like any other python program `python3 wunbot.py` 

On windows, I like to make a .bat with the contents 
```
SET apikey=YOUR_ACTUAL_API_KEY
python FILENAME_TO_RUN.py
pause
```

Discord.py is a dependancy. Make sure to `python3 -m pip install -U discord.py` before running. 

### Commands
wunbot_LaunchFile.py:
`???launch [filename]`

wunbot_SendFileOnceDaily.py:
`!dayn` sends message with day/365
`!potd` sends pictures of the day

### Configuration

Add your bot's token in the designated place at the bottom of wunbot.py
