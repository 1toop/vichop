# join our discord server https://discord.gg/BcnxDQa32N

- Server hops until vicious bee is found
- Auto attacks vicious bee
- Tracks stinger statistics
- Saves stats to vic.json
- Pings you in discord if you want
- Has a gui with stats

## How to use:
```lua
_G.hook = "" -- discord webhook url (optional)
_G.uid = "" -- discord user id for ping (optional)
_G.delay = "0" -- delay before server hop in seconds
_G.minlvl = "1" -- minimum vic level to attack (1-12)
_G.room = "" -- sync room name for searcher system (optional, any name)
_G.mainuser = "" -- main user for auto searcher system (optional)

_G.searcher = false -- true = searcher mode (finds and sends to webhook), false = killing vic
_G.vic = false -- send discord notification when vic found
_G.sprout = false -- send discord notification when sprout found
_G.windy = false -- send discord notification when windy found


loadstring(game:HttpGet("https://raw.githubusercontent.com/1toop/vichop/main/hop.lua"))()
```

<img width="613" height="664" alt="image" src="https://github.com/user-attachments/assets/7be577d5-f13d-4bff-a342-adc098fa5527" />
