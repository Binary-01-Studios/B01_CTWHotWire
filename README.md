# B01_CTWHotWire

B01_CTWHotWire

Exports List:<br />
exports['B01_CTWHotWire']:startMinigame()<br />
exports['B01_CTWHotWire']:stopMinigame()

Example:<br />
Citizen.CreateThread(function()<br />
	local example = exports['B01_CTWHotWire']:startMinigame() <br />
	Citizen.Wait(15000)<br />
	print(example)<br />
end)<br />

Value returned is a boolean

Support Discord:
http://www.discord.binary01studios.xyz/
