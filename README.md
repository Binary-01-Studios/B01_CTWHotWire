# B01_CTWHotWire

B01_CTWHotWire

Exports List:
exports['B01_CTWHotWire']:startMinigame()
exports['B01_CTWHotWire']:stopMinigame()

Example:
Citizen.CreateThread(function()
	local example = exports['B01_CTWHotWire']:startMinigame() 
	Citizen.Wait(15000)
	print(example)
end)

Value returned is a boolean

Support Discord:
http://www.discord.binary01studios.xyz/
