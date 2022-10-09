# B01_CTWHotWire

A car screwdriver hot wire minigame inspired by the GTA Chinatown Wars minigame.

**Exports List:**
```lua
exports['B01_CTWHotWire']:startMinigame(duration)
exports['B01_CTWHotWire']:stopMinigame(duration)
```

**Example:**
```lua
Citizen.CreateThread(function()
	local example = exports['B01_CTWHotWire']:startMinigame(15000)
	print(example)
end)
```

Value returned is a boolean by the export is a boolean.

**Support Discord:** 
http://www.discord.binary01studios.xyz/
