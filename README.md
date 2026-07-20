# join our discord server https://discord.gg/BcnxDQa32N

- Server hops until vicious bee is found
- Auto attacks vicious bee
- Tracks stinger statistics
- Saves stats to vic.json
- Pings you in discord if you want
- Has a gui with stats

## How to use:
```lua
local g = getgenv()
g.hook = "" -- discord webhook url (optional)
g.uid = "" -- discord user id for ping (optional)
g.delay = "0" -- delay before server hop in seconds
g.minlvl = "1" -- minimum vic level to attack (1-12)
g.maxlvl = "12" -- maximum vic level to attack (1-12)
g.onlygifted = false -- true = only attack/find gifted vics, false = any
g.room = "" -- sync room name for searcher system (optional, any name)
g.mainuser = "" -- main user for auto searcher system (optional)
g.mainwait = true -- true = main waits for searchers, false = main hops if no vics in list

loadstring(game:HttpGet("https://raw.githubusercontent.com/1toop/vichop/main/hop.lua"))()
```

<img width="613" height="664" alt="image" src="https://github.com/user-attachments/assets/7be577d5-f13d-4bff-a342-adc098fa5527" />
